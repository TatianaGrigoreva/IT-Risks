## IT-Risks
#Задание 1.
1. Перед началом работы необходимо: PostgreSQL, MS SQL Server (если есть проблемы с созданием базы в PostgreSQL), Jupyter notebook. Кроме того с помощью командной строки необходимо установить пакеты:
* pip install WeasyPrint
* pip install pyodbc
* pip install psycopg2
* pip install cairocffi
* pip install sqlalchemy
* pip install jinja2
* pip install matplotlib
* pip install pandas (большинство уже скорее всего установленно по умолчанию)
2. После этого необходимо настроить сервер SQL и сохранить эти данные для дальнейшего использования в коде.
3. Исходные xlsx файлы следует поместить либо в папку с кодом, либо в директорию, путь в которую не содержит киррилицу. Например, C:/...
Инструкция по выполнению кода прописана в нем самом.

!!! После первого этапа необходимо проверить корректность переноса таблиц в базу.  Если на первом этапе база данных создалась некорректно, есть пропуск полей, который мешает дальнейшей работе скриптов, то следует развернуть готовую базу данных и продолжать работать на ней.(дальнейшие задания я выполняла на готовой базе , собранной в MS SQL Server с помощью импорта из файлов csv). Тогда нужно запустить скрипты из Task 1.1 для завершения создания базы и установления связей.

Скачать базу и файлы можно по ссылке: https://drive.google.com/drive/folders/1KycKod6XbNi1PI3JanV4TaituU2IVcwO?usp=sharing 

В связи с этим изменился способ подключения Python к базе данных. (альтернативное подключение для PostgreSQL будет указываться в коментариях к коду. 

4. Далее следует запустить скрипты из Task 1.2 и Task 1.3.

#Задание 2.

Второе задание запускается из файлов Task 2 и Task 2 (1), но во втором случае в файле отображается структура платежей. Данные есть для расчета небольшого количества облигаций. 

#Задания 3 и 4 запускается из файла Task 3,4. Необходимо следовать комментариям в файле
