# ToDoManager
---
Данный проект представляет из себя Full-Stack Веб приложение

## Использованные библиотеки и технологии
---
![](https://img.shields.io/badge/ASP.NET%20Core%206%20-blueviolet?style=for-the-badge&amp;logo=dotnet) ![](https://img.shields.io/badge/-Postman-orange?style=for-the-badge&logo=postman) ![](https://img.shields.io/badge/-MySQL-lightgrey?style=for-the-badge&logo=mysql)


## Frontend
---
Адаптива предусмотрено не было. Функционал frontend'a лежит на ванильном js без использования сторонних фреймворков или библиотек. Связь c backend'ом происходит через ajax запросы, прокидывая токен, полученный после удачного захода на свой аккаунт.
Функционал:
> - Добавлеие задач
> - Добавлеие групп
> - Разделение задач по группам
> - Возможность изменять называние групп, удалять их
> - Возможность изменять называние, основной текст, дедлайн задач и отмечать их как выполнеными, а также удалять

## Backend
---
 Backend построен на трехслойной архитектуре и реализует RESTful API для взаимодействия с клиентской частью. Также реализована аунтификация и авторизация через jwt токен, выдаваемым непосредственно самим Backend'ом после успешной аунтификации и авторизации. Ролей из-за ненадобности предусмотренно не было. База данных использовалась MySql.
