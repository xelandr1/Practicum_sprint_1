Задание 1
реализованы шаги 1,2

**выбран фреймворк Webpack Module Federation т.к.:**
* нет необхоимости интеграции разнотипных фреймворков, используется только React 
* используются общие компоненты,
* использование Single-SPA будет более сложным


**разделение по доменам:**
* Авторизация
* Профиль пользователя
* Каталог мест

**структура разбиения микрофронтендов:**

auth - микрофронтенд авторизации
- src
- - blocks
- - - auth-form
- - components
- - - Login.js
- - - Register.js
- - utils
- - - auth.js


cards - микрофронтенд каталог мест
- src
- - blocks
- - - card
- - - places        
- - - popup
- - components
- - - AddPlacePopup.js
- - - Card.js
- - - ImagePopup.js
- - - PopupWithForm.js


host - основное приложение
- src
- - blocks
- - - content    
- - - footer          
- - - header         
- - - page 
- - components
- - - App.js
- - - Footer.js
- - - Header.js
- - - InfoTooltip.js
- - - ProtectedRoute.js
- - utils
- - - api.js
- - - auth.js


profile - микрофронтенд профиль пользователя
- src
- - blocks
- - - profile
- - components
- - - EditAvatarPopup.js
- - - EditProfilePopup.js
- - - PopupWithForm.js

----

Задание2

[sprint1-task2.drawio](sprint1-task2.drawio)


