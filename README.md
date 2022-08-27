# Тестирование API, Postman. 
Здесь можно посмотреть базовые запросы и тесты в web-версии приложения __Postman:__ https://www.postman.com/downloads/                       
Тестовая площадка __Dummy API:__ https://dummyapi.io/  
## POST - Создание пользователя
![скрин](https://github.com/mo-pozdina/API-Postman/blob/main/Requests/POST%2C%20GET/1%20POST%20-%20%D0%A1%D0%BE%D0%B7%D0%B4%D0%B0%D0%BD%D0%B8%D0%B5%20%D0%BF%D0%BE%D0%BB%D1%8C%D0%B7%D0%BE%D0%B2%D0%B0%D1%82%D0%B5%D0%BB%D1%8F.png)	
### POST - Создание пользователя с ""firstName"", ""lastName"" из 2 символов и повторяющимся email
![скрин](https://github.com/mo-pozdina/API-Postman/blob/main/Requests/POST%2C%20GET/4%20POST%20-%20%D0%A1%D0%BE%D0%B7%D0%B4%D0%B0%D0%BD%D0%B8%D0%B5%20%D0%BF%D0%BE%D0%BB%D1%8C%D0%B7%D0%BE%D0%B2%D0%B0%D1%82%D0%B5%D0%BB%D1%8F%20firstName%2C%20lastName%3D2%2C%20email%20%D0%B4%D1%83%D0%B1%D0%BB%D0%B8%D0%BA%D0%B0%D1%82.png)	
### POST - Создание пользователя с ""firstName"", ""lastName"" из 49 символов
![скрин](https://github.com/mo-pozdina/API-Postman/blob/main/Requests/POST%2C%20GET/6%20POST%20-%20%D0%A1%D0%BE%D0%B7%D0%B4%D0%B0%D0%BD%D0%B8%D0%B5%20%D0%BF%D0%BE%D0%BB%D1%8C%D0%B7%D0%BE%D0%B2%D0%B0%D1%82%D0%B5%D0%BB%D1%8F%20firstName%2C%20lastName%3D49%20%D0%91%D0%90%D0%93.png)
#### БАГ-РЕПОРТ
![скрин](https://github.com/mo-pozdina/API-Postman/blob/main/Requests/%D0%91%D0%90%D0%93-%D0%A0%D0%95%D0%9F%D0%9E%D0%A0%D0%A2%D0%AB/1.6%20POST%20-%20%D0%A1%D0%BE%D0%B7%D0%B4%D0%B0%D0%BD%D0%B8%D0%B5%20%D0%BF%D0%BE%D0%BB%D1%8C%D0%B7%D0%BE%D0%B2%D0%B0%D1%82%D0%B5%D0%BB%D1%8F%20firstName%2C%20lastName%3D49%20%D0%91%D0%90%D0%93-%D0%A0%D0%95%D0%9F%D0%9E%D0%A0%D0%A2.png)
## GET - Получение данных пользователя
![скрин](https://github.com/mo-pozdina/API-Postman/blob/main/Requests/POST%2C%20GET/7%20GET%20-%20%D0%9F%D0%BE%D0%BB%D1%83%D1%87%D0%B5%D0%BD%D0%B8%D0%B5%20%D0%B4%D0%B0%D0%BD%D0%BD%D1%8B%D1%85%20%D0%BF%D0%BE%D0%BB%D1%8C%D0%B7%D0%BE%D0%B2%D0%B0%D1%82%D0%B5%D0%BB%D1%8F.png)	
## GET - Получение списка пользователей из 51 шт.
![скрин](https://github.com/mo-pozdina/API-Postman/blob/main/Requests/POST%2C%20GET/10%20GET%20-%20%D0%9F%D0%BE%D0%BB%D1%83%D1%87%D0%B5%D0%BD%D0%B8%D0%B5%20%20%D1%81%D0%BF%D0%B8%D1%81%D0%BA%D0%B0%20%D0%BF%D0%BE%D0%BB%D1%8C%D0%B7%D0%BE%D0%B2%D0%B0%D1%82%D0%B5%D0%BB%D0%B5%D0%B9%3D51.png)	
## PUT - Изменение значения ключа ""title"" на значение, отличное от указанных в документации
![скрин](https://github.com/mo-pozdina/API-Postman/blob/main/Requests/PUT%2C%20DELEE/2%20PUT%20title%20%20-%20%D0%BE%D1%82%D0%BB%D0%B8%D1%87%D0%BD%D0%BE%D0%B5%20%D0%BE%D1%82%20%D0%B4%D0%BE%D0%BA%D1%83%D0%BC%D0%B5%D0%BD%D1%82%D0%B0%D1%86%D0%B8%D0%B8%20%D0%91%D0%90%D0%93.png)
#### БАГ-РЕПОРТ
![скрин](https://github.com/mo-pozdina/API-Postman/blob/main/Requests/%D0%91%D0%90%D0%93-%D0%A0%D0%95%D0%9F%D0%9E%D0%A0%D0%A2%D0%AB/2.2%20PUT%20title%20%20-%20%D0%BE%D1%82%D0%BB%D0%B8%D1%87%D0%BD%D0%BE%D0%B5%20%D0%BE%D1%82%20%D0%B4%D0%BE%D0%BA%D1%83%D0%BC%D0%B5%D0%BD%D1%82%D0%B0%D1%86%D0%B8%D0%B8%20%D0%91%D0%90%D0%93-%D0%A0%D0%95%D0%9F%D0%9E%D0%A0%D0%A2.png)
## PUT - Изменение значения ключa ""lastName"" на значение из 49 символов
![скрин](https://github.com/mo-pozdina/API-Postman/blob/main/Requests/PUT%2C%20DELEE/3%20PUT%20lastName%3D49.png)	
## PUT - Изменение значения ключа ""lastName"" на значение из 50 символов
![скрин](https://github.com/mo-pozdina/API-Postman/blob/main/Requests/PUT%2C%20DELEE/4%20PUT%20lastName%3D50.png)	
## PUT - Изменение значения ключа ""lastName"" на значение из 51 символа
![скрин](https://github.com/mo-pozdina/API-Postman/blob/main/Requests/PUT%2C%20DELEE/5%20PUT%20lastName%3D51%20%D0%91%D0%90%D0%93.png)	
#### БАГ-РЕПОРТ
![скрин](https://github.com/mo-pozdina/API-Postman/blob/main/Requests/%D0%91%D0%90%D0%93-%D0%A0%D0%95%D0%9F%D0%9E%D0%A0%D0%A2%D0%AB/2.5%20PUT%20lastName%3D51%20%D0%91%D0%90%D0%93-%D0%A0%D0%95%D0%9F%D0%9E%D0%A0%D0%A2.png)
## PUT - Изменение значения ключа ""picture"" на значение без протокола
![скрин](https://github.com/mo-pozdina/API-Postman/blob/main/Requests/PUT%2C%20DELEE/6%20PUT%20picture%20%D0%B1%D0%B5%D0%B7%20%D0%BF%D1%80%D0%BE%D1%82%D0%BE%D0%BA%D0%BE%D0%BB%D0%B0%20%D0%91%D0%90%D0%93.png)	
#### БАГ-РЕПОРТ
![скрин](https://github.com/mo-pozdina/API-Postman/blob/main/Requests/%D0%91%D0%90%D0%93-%D0%A0%D0%95%D0%9F%D0%9E%D0%A0%D0%A2%D0%AB/2.6%20PUT%20picture%20%D0%B1%D0%B5%D0%B7%20%D0%BF%D1%80%D0%BE%D1%82%D0%BE%D0%BA%D0%BE%D0%BB%D0%B0%20%D0%91%D0%90%D0%93-%D0%A0%D0%95%D0%9F%D0%9E%D0%A0%D0%A2.png)
## PUT - Изменение значения ключа ""gender"" на значение, отличное от указанных в документации
![скрин](https://github.com/mo-pozdina/API-Postman/blob/main/Requests/PUT%2C%20DELEE/7%20PUT%20gender%20%D0%B8%D0%B7%20%D1%81%D0%B8%D0%BC%D0%B2%D0%BE%D0%BB%D0%BE%D0%B2%20%D0%91%D0%90%D0%93.png)	
#### БАГ-РЕПОРТ
![скрин](https://github.com/mo-pozdina/API-Postman/blob/main/Requests/%D0%91%D0%90%D0%93-%D0%A0%D0%95%D0%9F%D0%9E%D0%A0%D0%A2%D0%AB/2.7%20PUT%20gender%20%D0%B8%D0%B7%20%D1%81%D0%B8%D0%BC%D0%B2%D0%BE%D0%BB%D0%BE%D0%B2%20%D0%91%D0%90%D0%93-%D0%A0%D0%95%D0%9F%D0%9E%D0%A0%D0%A2.png)
## PUT - Изменение значения ключа ""dateOfBirth"" на значение из 0
![скрин](https://github.com/mo-pozdina/API-Postman/blob/main/Requests/PUT%2C%20DELEE/8%20PUT%20dateOfBirth%20-%20%D0%BD%D1%83%D0%BB%D0%B8.png)
## DELETE	- Удаление пользователя
![скрин](https://github.com/mo-pozdina/API-Postman/blob/main/Requests/PUT%2C%20DELEE/9%20DELETE%20%D0%A3%D0%B4%D0%B0%D0%BB%D0%B5%D0%BD%D0%B8%D0%B5%20%D0%BF%D0%BE%D0%BB%D1%8C%D0%B7%D0%BE%D0%B2%D0%B0%D1%82%D0%B5%D0%BB%D1%8F.png)	
## DELETE	- Удаление удаленного пользователя
![скрин](https://github.com/mo-pozdina/API-Postman/blob/main/Requests/PUT%2C%20DELEE/10%20DELETE%20%D0%A3%D0%B4%D0%B0%D0%BB%D0%B5%D0%BD%D0%B8%D0%B5%20%D1%83%D0%B4%D0%B0%D0%BB%D0%B5%D0%BD%D0%BD%D0%BE%D0%B3%D0%BE%20%D0%BF%D0%BE%D0%BB%D1%8C%D0%B7%D0%BE%D0%B2%D0%B0%D1%82%D0%B5%D0%BB%D1%8F.png)	
