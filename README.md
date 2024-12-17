# Методы строк в JavaScript

JavaScript имеет много удобных методов для работы со строками. Вот краткое описание самых простых и полезных из них.

## Основные методы

### Длина строки (`length`)
Показывает, сколько символов в строке.

```javascript
let str = "Привет!";
console.log(str.length); // Результат: 7
```

![Пример метода length](https://via.placeholder.com/500x150?text=Пример+метода+length)

### Проверка содержания (`includes`)
Проверяет, есть ли в строке определённая подстрока.

```javascript
let str = "Привет, мир!";
console.log(str.includes("мир")); // Результат: true
```

### Извлечение символа (`charAt`)
Возвращает символ по указанному номеру.

```javascript
let str = "Привет";
console.log(str.charAt(0)); // Результат: П
```

![Пример метода charAt](https://via.placeholder.com/500x150?text=Пример+метода+charAt)

### Индекс подстроки (`indexOf`)
Находит индекс первого появления подстроки в строке.

```javascript
let str = "Привет, мир!";
console.log(str.indexOf("мир")); // Результат: 8
```

---

## Методы изменения строки

### Удаление пробелов (`trim`)
Убирает лишние пробелы в начале и конце строки.

```javascript
let str = "   Привет!   ";
console.log(str.trim()); // Результат: "Привет!"
```

### Замена текста (`replace`)
Заменяет одно слово или часть строки на другую.

```javascript
let str = "Привет, мир!";
console.log(str.replace("мир", "JavaScript")); // Результат: Привет, JavaScript!
```

![Пример метода replace](https://via.placeholder.com/500x150?text=Пример+метода+replace)

### Разделение строки (`split`)
Разбивает строку на массив по разделителю.

```javascript
let str = "яблоко,банан,вишня";
console.log(str.split(",")); // Результат: ["яблоко", "банан", "вишня"]
```

![Пример метода split](https://via.placeholder.com/500x150?text=Пример+метода+split)

### Повторение строки (`repeat`)
Повторяет строку указанное количество раз.

```javascript
let str = "Привет! ";
console.log(str.repeat(3)); // Результат: Привет! Привет! Привет! 
```

---

## Заключение
Эти методы помогут вам легко работать со строками в JavaScript. Начните с простого и постепенно изучайте более сложные возможности!

