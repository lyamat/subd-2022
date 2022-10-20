# Matveyeu Ilya 053504


Сущности:
-------------------------
-	Books (книги)
-	Branches (отделения / филиалы)
-	Employees (работяги)
-	Future_goals (цели на будущее)
-	Logs (логи есть логи)
-	Promotions (акции)
-	Subscriptions (подписки)
-	Users (пользователи)

Функционал для пользователя:
-------------------------
-	Регистрация
-	Аутентификация
-	Удаление аккаунта
-	Просмотр целей на будущее и их авторов
-	Просмотр акций
-	Просмотр подписок и выбор из предложенных
-	Просмотр книг и отделений, в которых они есть в наличии. Выбор книг из имеющихся отделений

Функционал для работяг:
-------------------------
-	Просмотр пользователей и выбранных ими подписок
-	Просмотр работяг в соответствующем отделении
-	Просмотр логов
-	Работяга может иметь аккаунт пользователя в библиотеке со всеми вытекающими

Таблицы:
-------------------------
### books ###
![image](https://user-images.githubusercontent.com/65541361/196982194-ea0d49ca-a4a7-4309-bfef-4be7eeda180a.png)
### books_to_branches ###
![image](https://user-images.githubusercontent.com/65541361/196982525-1ca58adc-bb33-4256-adcf-a94b092f0cb9.png)
### branches ###
![image](https://user-images.githubusercontent.com/65541361/196985443-a86333b3-d85a-4f3f-86cf-858f30fd7439.png)
### employees ###
![image](https://user-images.githubusercontent.com/65541361/196983083-daefd16c-c476-4858-8256-60414bc088c9.png)
### employees_to_branches ###
![image](https://user-images.githubusercontent.com/65541361/196983269-84f959b8-5936-4955-9052-4aecc269cf5d.png)
### future_goals ###
![image](https://user-images.githubusercontent.com/65541361/196983360-6b49827b-3f1f-4bdf-b8f3-68e7f2edf74e.png)
### future_goals_to_employees ###
![image](https://user-images.githubusercontent.com/65541361/196983432-a4a452b7-2b84-4c29-b042-c9c494fad2a8.png)
### logs ###
![image](https://user-images.githubusercontent.com/65541361/196983542-9e87b6bd-d053-4804-a2cd-3af1f7d8c5b3.png)
### promotions ###
![image](https://user-images.githubusercontent.com/65541361/196983705-6eabba93-db31-4bd1-9042-8af6e32067a4.png)
### subscriptions ###
![image](https://user-images.githubusercontent.com/65541361/196983803-99416ba9-137b-440c-b8b5-6ff3639a0a2c.png)
### users ###
![image](https://user-images.githubusercontent.com/65541361/196983938-4f991b82-2436-4d39-a87a-cda0bab6bdd0.png)
### users_to_employees ###
![image](https://user-images.githubusercontent.com/65541361/196984010-55aafed0-5943-40a9-9a13-8ac4c1a73752.png)
### users_to_subscriptions ###
![image](https://user-images.githubusercontent.com/65541361/196984092-6bf95be6-fa95-4f1f-9b75-876e146a241a.png)

Entity Relationship (ER) Diagram Model
-------------------------
![SUBD_Diagramm](https://user-images.githubusercontent.com/65541361/196985997-fd143fc4-8d2f-4f93-bb37-1b34a6655174.png)
