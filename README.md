# Week9

// ------------------ Вопрос № 1 ------------------ //
Варианты объявления переменных:

- let (можно менять значение переменной);
- const (значение переменной менять нельзя);
- var (тоже самое, что и let, только устаревший вариант).

// ------------------ Вопрос № 2 ------------------ //
С помощью console.log('Hello');

// ------------------ Вопрос № 5 ------------------ //
Способы подключения к странице Java Script:
-между открывающим и закрывающим тегом <script>:
<script>
    alert('Hello!');
</script>

- отдельным файлом с расширением JS, а потом связать его с документом HTML:
<script src="./maim.js"></script>

- поместить код в атрибут событий HTML-элементов:
<!DOCTYPE html>
<html>
<head>

<script>
    function myFunction() {
    document.getElementById("demo").innerHTML = "Привет, javascript!";
    }
</script>

</head>
<body>

<p id="demo">Привет, мир!</p>
<button type="button" onclick="myFunction()">Кликни меня</button>

</body>
</html>

// ------------------ Вопрос № 6 ------------------ //
typeof str - синтаксис оператора;
typeof (str) - синтаксис функции;
Он возвращает тип аргумента, работает со скобками и без скобок - результат одинаковый.






//-----------------------------------------------------------------------//
Самым близким кажется метод Цицерона (потому что уже опробован много раз и не требует большого количества времени для запоминания).