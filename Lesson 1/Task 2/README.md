# Lesson 1
## Task 2

### Задание: Строковый буфер с очисткой
В некоторых языках программирования существует объект «строковый буфер», который аккумулирует внутри себя значения. Его функционал состоит из двух возможностей:

1) Добавить значение в буфер.

2) Получить текущее содержимое.

3) Очистить буфер.

Задача — реализовать строковый буфер на функциях в JavaScript, со следующим синтаксисом:

Создание объекта: 
```var buffer = makeBuffer();```
Вызов makeBuffer должен возвращать такую функцию buffer, которая при вызове buffer(value) добавляет значение в некоторое внутреннее хранилище, а при вызове без аргументов buffer() — возвращает его.
***buffer.clear()*** — очищает буфер.

Часть решения находится в файле task.js. Вам необходимо лишь изменить функцию makeBuffer.