# Преобразование файлов инклинометрии

## Оглавление
[1. Описание программы](https://github.com/rafferti95/My-projects/blob/main-programs/3_Inclinometria/README.md#описание-программы)\
[2. Какой кейс решаем](https://github.com/rafferti95/My-projects/blob/main-programs/3_Inclinometria/README.md#какой-кейс-решаем)\
[3. Краткая информация о данных](https://github.com/rafferti95/My-projects/blob/main-programs/3_Inclinometria/README.md#краткая-информация-о-данных)\
[4. Этапы работы над программой](https://github.com/rafferti95/My-projects/blob/main-programs/3_Inclinometria/README.md#этапы-работы-над-программой)\
[5. Результат](https://github.com/rafferti95/My-projects/blob/main-programs/3_Inclinometria/README.md#результат)\
[6. Выводы](https://github.com/rafferti95/My-projects/blob/main-programs/3_Inclinometria/README.md#выводы)

### Описание программы
Преобразовать получаемые от заказчика данные к виду необходимому для работы.

↑[К оглавлению](https://github.com/rafferti95/My-projects/blob/main-programs/3_Inclinometria/README.md#оглавление)↑

### Какой кейс решаем
Необходимо преобразовать и объединить данные, которые предоставляет заказчик, в файл  пригодный для работы в рабочей программе.

↑[К оглавлению](https://github.com/rafferti95/My-projects/blob/main-programs/3_Inclinometria/README.md#оглавление)↑

### Краткая информация о данных
Для решения поставленной рабочей задачи необходимо сформировать файл инклинометрии, в котором кроме данных о пространственном положении ствола буровой скважины ничего не будет.
- **Инклинометрия** - набор данных, включающих в себя: *координаты, глубину и латеральные смещения*, которые характеризуют пространственное положение ствола буровой скважины.

<img src = https://cf2.ppt-online.org/files2/slide/4/4QVfKeqrWs81bLUR0OPzGhAm5p9cIxyaN32SuigZB/slide-14.jpg width = 50% height = 50%>

В свою очередь заказчик предоставляет данные о инклинометрии в файле-excel, который представляет собой дело скважины. В данном файле помимо нужной нам инклинометрии на разных листах содержится вся информация о скважине (*перечень данных не подлежит разглашению*). 

↑[К оглавлению](https://github.com/rafferti95/My-projects/blob/main-programs/3_Inclinometria/README.md#оглавление)↑

### Этапы работы над программой
* Перывм этапом работы стало написание программы для едичного файла. Данная программа открывала файл Excel на нужной странице, брала с него всю необходимую для работы информацию и формировала новый файл Excel;
* На втором этапе код программы из первого этапа был обёрнут в цикл, который поточно обрабатывал все файлы, содержащиеся в целевой папке. Затем все необходимые данные по всем скважинам складывались в один файл Excel;
* Добавлена проверка путём вывода номера скважины, полученных и преобразованных координат и магнитного склонения.

↑[К оглавлению](https://github.com/rafferti95/My-projects/blob/main-programs/3_Inclinometria/README.md#оглавление)↑

### Результат
Программа способна считывать все файлы из целевой папки и вычленять из предоставленных файлов всю необходимую информацию, преобразовывая её и *складывая* её в новый отдельный файл Excel.

↑[К оглавлению](https://github.com/rafferti95/My-projects/blob/main-programs/3_Inclinometria/README.md#оглавление)↑

### Выводы
Рабочий процесс по *открытию, копированию, вставке, удалению и форматированию*, занимающий половину рабочего дня, оптимизирован до нажатия пары клавишь. Теперь данный процесс занимает менее одной минуты.

↑[К оглавлению](https://github.com/rafferti95/My-projects/blob/main-programs/3_Inclinometria/README.md#оглавление)↑

→[Ссылка на программу](https://github.com/rafferti95/My-projects/blob/test-programs/3_Inclinometria/3_Inclinometria.ipynb)←
