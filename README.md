# Лабораторная работа 3

Ссылка на Google Colab:

https://drive.google.com/file/d/1Ii3j8PIAJBSy9e1r1mJo67dXVGJFUmED/view?usp=sharing

## Контрольные вопросы

### 1. Что такое csvsql, как она работает?

Функция csvsql является частью csvkit, данная функция используется для преобразования CSV файлов в таблицы для нужной базы данных. Функция также позволяет осуществлять запросы в формате SQL-запросов к файлам (то есть, получать информацию из самого файла испопльзуя синтаксис обращения к базе данных).

### 2. Можно ли объединить таблицы в базе данных, как это сделать?

В SQL базах данных для объединения таблиц используется оператор JOIN. Объединение требует наличия некоторой общей колонки данных в каждой таблице, которую можно использовать для однозначного объединения.

### 3. Какой метод Pandas позволяет добавлять информацию в базу данных?

Информацию из датафрейма pandas позволяет добавить как таблицу базы данных фукция to_sql. При использовании метода нужно быть осторожным и избегать конфликтов.

### 4. Что делает метод fetchall()?

Количество необходимых строк результата запроса можно регулировать (fetchone, fetchmany). Метод fetchall извлекает сразу все строки результата запроса.

### 5. Почему для обработки данных используется библиотека Pandas, можно ли выполнить такую же обработку другим способом?

Данные хранятся в таблицах и датафреймы pandas очень удобно использовать для манипуляций с табличными данными, также библиотека предлагает возможность SQL экспорта. Выполнить те же работы можно с ппомощью дополнительного кода и более сложных SQL-запросов.
