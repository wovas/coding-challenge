﻿Тестовое задание
================
__**Дано:**__ шаблонное приложение [ASP.Net Core MVC](https://docs.microsoft.com/ru-ru/aspnet/core/tutorials/first-mvc-app/?view=aspnetcore-2.2).
По шаблону, в приложении реализованая стандартная схема авторизации и регистрации по email/password. 

__**Необходимо:**__ Реализовать модель авторизации, где логином будет служить телефон пользователя, а пароль будет одноразовым (действительным в течении 5 минут после запроса) и будет отправляться ему на указанный при регистрации телефон.
Для отправки паролей воспользуйтесь сервисом [https://turbosms.ua/](https://turbosms.ua/) и его [SOAP API](https://turbosms.ua/soap.html) сервис предоставляет 10 бесплатных смс и пример проекта с интеграцией.

По максиммуму старайтесь использовать возможности расширения [Microsoft.AspNetCore.Identity](https://docs.microsoft.com/ru-ru/aspnet/core/security/authentication/identity?view=aspnetcore-2.2&tabs=visual-studio)

Как подготовить решение
-----------------------

Для оформления результатов и работы над заданием - сделайте fork данного репозитория, и когда все будет готово отпишите в telegram [@wovas](https://t.me/wovas)

**Не спешите и не сдавайтесь! У вас все получится!**

Если возникнут вопросы - обращайтесь!