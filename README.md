# Не доделано. Справился со всем до 9 строки описания.
Расширить функционал программы, сделанной в ходе Java_png_read.
Добавить проверку расширения, а также поддержку файлов BMP.
Обеспечить проверку сигнатуры заголовочной части как BMP так и PNG. Если проверка провалилась, дальше файл не читать.
Для формата BMP в таблицу прописывать:
Версию заголовочника BitmapInfoHeader
Ширину изображения
Высоту изображения
Размер таблицы цветов (если есть)
Размер отступа GAP1

Размер отступа GAP2
Размер профиля ICC
Отступ от конца профиля ICC до конца файла

Проверку сигнатуры выполнять в отдельном классе
