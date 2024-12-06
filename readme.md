# Введение в JavaScript

![JavaScript Logo](https://upload.wikimedia.org/wikipedia/commons/6/6a/JavaScript-logo.png)

JavaScript — это популярный язык программирования, который используется для создания интерактивных веб-сайтов. Он позволяет добавлять на страницы анимации, реагировать на действия пользователей и делать веб-приложения функциональными.

---

## Как появился JavaScript?

JavaScript был создан в **1995 году** разработчиком **Бренданом Айком** за **10 дней**.  
Основная идея заключалась в том, чтобы сделать веб-страницы интерактивными.  
С тех пор JavaScript стал основным языком программирования для работы в интернете.  

### Интересный факт:
JavaScript часто путают с Java, но это совершенно разные языки.

---

## Основные особенности JavaScript

- **Работает в браузере**: Код выполняется прямо на веб-странице.
- **Интерактивность**: Позволяет взаимодействовать с пользователем.
- **Простота изучения**: Подходит для начинающих программистов.
- **Универсальность**: Используется как на стороне клиента (в браузере), так и на стороне сервера (с Node.js).

---

## Variables
В программировании контейнер переменных (область хранения данных). Существует два типа инициализации переменных: var и let. Вы можете использовать оба из них. Однако между ними есть некоторые различия. Если вы уверены, что значение переменной не изменится на протяжении всей программы, рекомендуется использовать const.
 
 1. Имена переменных должны начинаться с буквы, подчеркивания _ или знака доллара $. 2. Имена переменных не могут начинаться с цифр. Например: let 1simpleText = 'Javascript действительно простой; console.log(1simpleText);


 ---

## Первое знакомство с JavaScript

### Как работает JavaScript?
Код JavaScript пишется в специальном блоке `<script>` или в отдельном файле с расширением `.js`.  
Пример встроенного JavaScript:

 


```html
<!DOCTYPE html>
<html lang="ru">
<head>
    <title>Пример JS</title>
</head>
<body>
    <h1 id="заголовок">Привет, мир!</h1>
    <button onclick="изменитьТекст()">Нажми меня</button>

    <script>
        function изменитьТекст() {
            document.getElementById("заголовок").textContent = "Вы изменили текст!";
        }
    </script>
</body>
</html>
