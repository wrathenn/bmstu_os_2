С защиты:

1) Условия выхода из рекурсии (по коду)
- Ошибка при вызове lstat
- Если файл - не директория
- Ошибка вызова opendir / ошибка при открытии директории
- readdir вернул NULL/0 (вся директория прочитана)

2) Зачем вызывать chdir()?
- для смены текущей директории

3) Что дает смена текущей директории?
- в текущей директории можно пользоваться короткими именами файлов