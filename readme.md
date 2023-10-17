# Упражнения

### Подготовка

1. Форкните текущий репозиторий на свою учетную запись github
2. Склонируйте свой репозиторий на компьютер
3. Выполните команду: `npm ci`

# Задание
- переключитесь в ветку ``
- в папке `src` создайте файл `functions.js`, в котором напишите пять функций (одно задание – одна функция) и экспортируйте их.

Для проверки решения выполните push в ветку `exercise_01`, после чего на вкладке `actions` посмотрите результат выполнения тестов.

### Локальная проверка
Для локальной проверки используйте `npm test`

### Задание 1

Реализовать функцию, которая принимает строку и целое число, а возвращает символ строки стоящий по указанному в числе индексу. Если символа на указанной позиции нет - возвращается пустая строка.

```js
getSymbol('The members', 4);  // 'm'
getSymbol('type can in', 1);  // 'y'
getSymbol('an error', 20);    // ''
```

### Задание 2

Реализовать функцию, которая принимает целое число из отрезка [100, 999] и возвращает число, без второй цифры исходного числа.

```js
removeDigit(208);  // 28
removeDigit(109);  // 19
removeDigit(940);  // 90
```

### Задание 3
Реализовать функцию, которая принимает два целых числа и возвращает информацию о том, является ли одно квадратом другого.

```js
isSquare(2, 4);    // true
isSquare(81, 9);   // true
isSquare(25, 125); // false
```

### Задание 4
Реализовать функцию, которая принимает целое положительное число и возвращает количество цифр в этом числе. Исходное число от 0 до 2000000000.

```js
numberLength(123);   // 3
numberLength(3);     // 1
numberLength(19283); // 5
```

### Задание 5

Реализовать функцию, которая принимает строку и возвращает строку-перевертыш.
```js
flipOver('hello');    // olleh
flipOver('swap');     // paws
flipOver('John Doe'); // eoD nhoJ
```