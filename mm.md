# Тест: Цикли, методи масивів і базові знання JavaScript

---

### 1. Що виведе цей код?

```javascript
let sum = 0;
for (let i = 1; i <= 3; i += 1) {
  sum += i;
}
console.log(sum);
```

- A) 6
- B) 3
- C) 0

---

### 2. Що робить метод `push`?

- A) Видаляє останній елемент з масиву
- B) Додає елемент на початок масиву
- C) Додає елемент в кінець масиву

---

### 3. Що виведе цей код?

```javascript
let fruits = ["apple", "banana"];
fruits.push("orange");
console.log(fruits.length);
```

- A) 2
- B) 3
- C) 1

---

### 4. Який результат отримаємо?

```javascript
let numbers = [1, 2, 3];
numbers.pop();
console.log(numbers);
```

- A) [1, 2]
- B) [1, 2, 3]
- C) [2, 3]

---

### 5. Що робить цикл `for...of`?

- A) Перебирає індекси масиву
- B) Перебирає значення масиву
- C) Працює тільки з об'єктами

---

### 6. Що виведе цей код?

```javascript
let str = "hello";
console.log(str.length);
```

- A) 5
- B) 4
- C) 6

---

### 7. Який тип даних повертає метод `pop()`?

- A) Число
- B) Масив
- C) Значення останнього елемента

---

### 8. Який правильний синтаксис циклу `for`?

- A) `for i = 0; i < 5; i+=1`
- B) `for (i = 0; i < 5; i+=1)`
- C) `for (let i = 0; i < 5; i+=1)`

---

### 9. Що виведе цей код?

```javascript
let count = 0;
for (let i = 0; i < 4; i += 1) {
  count += 1;
}
console.log(count);
```

- A) 5
- B) 4
- C) 3

---

### 10. Що відбудеться при виклику `arr.pop()`?

- A) Додається новий елемент
- B) Видаляється останній елемент
- C) Очищується масив

---

### 11. Як перевірити довжину масиву `arr`?

- A) `arr.size()`
- B) `length(arr)`
- C) `arr.length`

---

### 12. Що виведе цей код?

```javascript
let text = "JavaScript";
console.log(text[0]);
```

- A) J
- B) a
- C) undefined

---

### 13. Що буде результатом?

```javascript
let x = "cat";
x = x.toUpperCase();
console.log(x);
```

- A) cat
- B) CAT
- C) CaT

---

### 14. Який результат виконання?

```javascript
let arr = [10, 20, 30];
let total = 0;
for (let num of arr) {
  total += num;
}
console.log(total);
```

- A) 60
- B) 30
- C) 0

---

### 15. Що означає вираз `i++`?

- A) Зменшити `i` на 1
- B) Залишити `i` без змін
- C) Збільшити `i` на 1

---

### 16. Що виведе цей код?

```javascript
let name = "Anna";
console.log(name.toLowerCase());
```

- A) ANNA
- B) anna
- C) Anna

---

### 17. Який метод видаляє останній елемент з масиву?

- A) `shift()`
- B) `pop()`
- C) `slice()`

---

### 18. Який результат буде?

```javascript
let a = 5;
let b = "5";
console.log(a == b);
```

- A) true
- B) false
- C) error

---

### 19. Що робить оператор `if`?

- A) Повторює дію кілька разів
- B) Виконує код, якщо умова істинна
- C) Завжди виконує код

---

### 20. Що означає `else` після `if`?

- A) Код виконується, коли умова `if` істинна
- B) Код виконується, коли умова `if` хибна
- C) Код виконується до перевірки `if`

---

### 21. Що виведе цей код?

```javascript
let message = "Hi!";
console.log(message.toUpperCase());
```

- A) hi!
- B) HI!
- C) Hi!

---

### 22. Як додати елемент в кінець масиву `arr`?

- A) `arr.unshift(x)`
- B) `arr.push(x)`
- C) `arr.pop(x)`

---

### 23. Який результат?

```javascript
let nums = [1, 2, 3];
nums.push(4);
console.log(nums[3]);
```

- A) 3
- B) 4
- C) undefined

---

### 24. Що виведе цей код?

```javascript
for (let i = 0; i < 3; i += 1) {
  console.log(i);
}
```

- A) 0 1 2
- B) 1 2 3
- C) 0 1 2 3

---

### 25. Що буде, якщо викликати `pop()` на порожньому масиві?

- A) Поверне null
- B) Поверне undefined
- C) Поверне помилку

---

### 26. Що виведе цей код?

```javascript
let word = "hello";
console.log(word[word.length - 1]);
```

- A) h
- B) o
- C) undefined

---

### 27. Який метод додає елемент на початок масиву?

- A) `push()`
- B) `pop()`
- C) `unshift()`

---

### 28. Який результат виконання?

```javascript
let items = ["a", "b"];
items.pop();
console.log(items.length);
```

- A) 2
- B) 1
- C) 0

---

### 29. Що виведе цей код?

```javascript
let str = "Code";
for (let char of str) {
  console.log(char);
}
```

- A) C o d e
- B) Code
- C) undefined

---

### 30. Що таке `arr.length`?

- A) Кількість символів у рядку
- B) Кількість елементів у масиві
- C) Значення останнього елемента масиву
