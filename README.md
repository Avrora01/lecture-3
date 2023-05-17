# lecture-3
 ![Tux, the Linux mascot](/img/javascript-string.png)

 # Как изменить регистр
##### toLowerCase
> Преобразует символы в строке в нижний регистр.

**"Hello Tproger".toLowerCase();** // "hello tproger"

**toUpperCase**

>Преобразует символы в строке в верхний регистр.

**"Hello Tproger".toUpperCase();** // "HELLO TPROGER"

# Как объединить строки
**concat**

>Объединяет две или более строки и возвращает одну строку.

**"Hello".concat(" Tproger");** // "Hello Tproger"
**"Hello".concat(" T", "p", "r", "o", "g", "e", "r");** // "Hello Tproger"

# Как разделить строку на подстроки
**split**
>Разбивает строку в массив по указанному разделителю, которым  быть подстрока или регулярное выражение. Вторым параметром можно указать ограничитель.

// Получаем каждый символ
**"Hello Tproger".split("");** // ["H", "e", "l", "l", "o", " ", "T", "p", "r", "o", "g", "e", "r"]
// Получаем каждое слово из строки
**"Hello Tproger".split(" ");** //["Hello", "Tproger"]

// Устанавливаем ограничитель
**"Hello Tproger".split(" ", 1);** //["Hello"]