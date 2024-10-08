Анализатор прайс-листов.

Описание:

В папке "prices" находятся несколько файлов, содержащих прайс-листы от разных поставщиков. Количество и название файлов заранее неизвестно, однако точно известно, что в названии файлов прайс-листов есть слово "price". Файлы, не содержащие слово "price" следует игнорировать. Формат файлов: данные, разделенные точкой с запятой.
Порядок колонок в файле заранее неизвестен, но известно, что столбец с названием товара называется одним из вариантов: "название", "продукт", "товар", "наименование". Столбец с ценой может называться "цена" или "розница". Столбец с весом имеет название "фасовка", "масса" или "вес" и всегда указывается в килограммах.
Остальные столбцы игнорировать.

Программа загружает данные из всех прайс-листов и предоставить интерфейс для поиска товара по фрагменту названия с сортировкой по цене за килограмм.
Интерфейс для поиска реализовать через консоль, циклически получая информацию от пользователя:
 - Если введено слово "exit", то цикл обмена с пользователем завершается, программа выводит сообщение о том, что работа закончена и завершает свою работу.

![image](https://github.com/user-attachments/assets/fe48c458-647d-4675-9c94-3b22824151d9)

 - При вводе слова "all" позволит получить полный список позиций в виде таблицы'.

![image](https://github.com/user-attachments/assets/3882eb74-5fda-49a0-88b6-e1dbc2fb78c0)
   
 - В противном случае введенный текст считается текстом для поиска. Программа должна вывести список найденных позиций в виде таблицы (Список ь отсортирован по возрастанию стоимости за килограмм.):

![image](https://github.com/user-attachments/assets/ca098112-aa45-45a1-a362-a1c8fe0049b5)

- Также предусмотрен вывод массива данных в текстовый файл output.html.

![image](https://github.com/user-attachments/assets/8ea9aa2e-53f3-493f-aa52-44ec0254bad0)
