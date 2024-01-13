Visual Studio 2019
.NET Core 3.1
Для корректной работы веб-приложения необходимо осздать БД MSSQL Server. 
Для создания таблицы в папке проекта находится файл SQLQuery_orders.sql (код для создания таблицы Orders)
В файле appsettings.json находится строка подключения к БД
"ConnectionStrings": {
    "DefaultConnection": "Server=KOMPUTER\\SLAP25;Database=TestDB_orders;Trusted_Connection=true"
  }
  Необходимо заменить "Server=KOMPUTER\\SLAP25;Database=TestDB_orders" на Server=[Название сервера MSSQL]; Database=[Название созданной БД]"
  Отладку можно производить через IIS Express или спомощью дебага (ctrl+F5)
