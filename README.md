# Работа с SQL запросами (SELECT, WHERE, IN, JOIN, CASE)
*Примеры SQL запросов, выполненные в рамках курса Артёма Русова "Функциональное тестирование ПО"*


1. Выведите возраст всех персонажей так, чтобы среди них не было тех, у кого он одинаковый  

![sql_1](https://github.com/juuliadidenko/sql_home_assignment/assets/104693196/2d07e136-ab5c-4c54-bbdf-6b81957ae867)


2. Используя оператор IN, выведите имя и фамилию тех персонажей, у которых фамилия Crabbe, Granger или Diggory

![sql_2](https://github.com/juuliadidenko/sql_home_assignment/assets/104693196/166211f2-acd9-4486-8c00-115e89325b22)


3. Используя оператор CASE опишите следующую логику:
   Выведите имя и фамилию персонажа, а также следующий текстовое сообщение:  

   Если факультет Gryffindor, то в консоли должно вывестись Godric  
   Если факультет Slytherin, то в консоли должно вывестись Salazar  
   Если факультет Ravenclaw, то в консоли должно вывестись Rowena  
   Если факультет Hufflepuff, то в консоли должно вывестись Helga  
   Если другая информация, то выводится Muggle  

   Для сообщения используйте псевдоним Founders

![sql_3](https://github.com/juuliadidenko/sql_home_assignment/assets/104693196/a0dda39b-d9b2-4217-b771-89c09522211f)


4. Используя регулярное выражение найдите фамилии персонажей, которые не начинаются с букв H, L или S и выведите их

![sql_4](https://github.com/juuliadidenko/sql_home_assignment/assets/104693196/b00f1b4b-d0a9-4fca-8cbe-affad50d7e10)


5. Выведите имя, фамилию персонажей и название книги, которая на них числится

![sql_5](https://github.com/juuliadidenko/sql_home_assignment/assets/104693196/8c96d8c8-3f2a-44c0-a810-6b1dd6c91986)


6. Выведите имя, фамилию персонажей и название книги, вне зависимости от того, есть ли у них книги или нет

![sql_6](https://github.com/juuliadidenko/sql_home_assignment/assets/104693196/a0a7e3ad-eaae-456a-a5fc-e8097a7c9c7f)


7. Выведите название книги и имя патронуса, вне зависимости от того, есть ли информация о держателе книги в таблице или нет

![sql_7](https://github.com/juuliadidenko/sql_home_assignment/assets/104693196/a1378671-ba07-4444-95ce-3fd04530df92)


8. Выведите имя, фамилию, возраст персонажей и название книги, которая на них числится, при условии, что все владельцы книг должны быть старше 15 лет

![sql_8](https://github.com/juuliadidenko/sql_home_assignment/assets/104693196/2735aeb4-a32e-4d32-8a76-bd044d4741a7)


9. Используя вложенный запрос количество книг, у которых end_date больше, чем end_date у Hermione

![sql_9](https://github.com/juuliadidenko/sql_home_assignment/assets/104693196/6912bd92-b17b-484c-a73c-8c921ac15012)


10. С помощью вложенного запроса выведите имена всех патронусов, у которых владельцы старше возраста персонажа, у которого патронус Unknown

![sql_10](https://github.com/juuliadidenko/sql_home_assignment/assets/104693196/3e27403e-7d0b-49ba-812c-a12fc97fdfeb)


