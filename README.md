# Что такое метод в JavaScript ?
+ **Методы JavaScript это действия, которые можно выполнить с объектами. Метод JavaScript это свойство, содержащее определение функции.**
---------
# Что такое масив в JavaScript?
+ **Массивы — это особый тип объектов. Оператор typeof в JavaScript возвращает "object" для массивов. Но массивы JavaScript лучше всего описывать как массивы. Массивы используют числа для доступа к своим «элементам»**
---
![](https://miro.medium.com/v2/resize:fit:2000/1*BwrqzA3hUC7u1VJSNAj0yg.png)
# Методы Массива
+ pop()
+ shift()
+ push()
+ unshift()
+ concat()
+ slice()
+ forEach()
+ map()
+ find()
+ filter()
+ reduce()
+ toSorted()
+ join()
+ includes
+ inddexOf()
+ splice()
+ toString()
+ toReversed()
---
# Метод push() :
+ **_Метод push () добавляет один или более элементов в конец массива и возвращает новую длину массива._**
```JavaScript
let fruits = ['apple', 'banana', 'orange'];
fruits.push('kiwi');
console.log(fruits); // ['apple', 'banana', 'orange', 'kiwi']
let numbers = [1, 2, 3];
numbers.push(4, 5, 6);
console.log(numbers); // [1, 2, 3, 4, 5, 6]
```
---
# Метод pop() :
+ **_Описание Метод pop удаляет последний элемент из массива и возвращает удалённое значение. Метод pop не является привязанным к типу; этот метод может быть вызван или применён к массивоподобным объектам_**
```JavaScript
const fruits = ["Banana", "Orange", "Apple", "Mango"];
fruits.pop();
```
---
# Метод unshift() :
+ **_Метод unshift Метод unshift добавляет неограниченное количество новых элементов в начало массива. При этом исходный массив изменяется, а результатом возвращается новая длина массива._**
```JavaScript
const fruits = ["Banana", "Orange", "Apple", "Mango"];
fruits.unshift("Lemon","Pineapple");
```
---
# Метод shift() :
+ **_Метод shift удаляет первый элемент из массива. При этом исходный массив изменяется, а результатом метода возвращается удаленный элемент._**
```JavaScript
var arr = ["мой","маленький", "массив"]
var my = arr.shift() // => "мой"
alert(arr[0]) // => "маленький"
// теперь arr = ["маленький", "массив"
```
---
# Метод toString() :
+ **Кратко Метод to String () возвращает строковое представление объекта. Метод автоматически вызывается, когда объект нужно представить в текстовом виде. При необходимости поведение метода можно изменить._**
```JavaScript
let number = 123;
let stringNumber = number.toString();
console.log(stringNumber); // Output: "123"

```
---
# Метод map() :
+ **_Метод map () создаёт новый массив с результатом вызова указанной функции для каждого элемента массива_**
```JavaScript
const sweetArray = [2, 3, 4, 5, 35]
const sweeterArray = sweetArray.map(sweetItem => {
    return sweetItem * 2
})

console.log(sweeterArray)
```
---
# Метод find() :
+ **_Сводка Метод find() возвращает значение первого найденного в массиве элемента, которое удовлетворяет условию переданному в callback функции. В противном случае возвращается undefined._**
```JavaScript
const numbers = [4, 9, 16, 25, 29];

// Функция обратного вызова для поиска числа больше 20
function isLargeNumber(element) {
  return element > 20;
}

// Использование метода find для поиска первого числа больше 20
const found = numbers.find(isLargeNumber);

console.log(found); // Вывод: 25

```
---
# Метод filter() :
+ **_Метод filter () создаёт новый массив со всеми элементами, прошедшими проверку, задаваемую в передаваемой функции._**
```JavaScript
let numbers = [1, 2, 3, 4, 5, 6];
let evenNumbers = numbers.filter(function(number) {
  return number % 2 === 0;
});

console.log(evenNumbers); // [2, 4, 6]
```
---
# Метод reduce() :
+ **_Метод reduce в JavaScript используется для последовательного применения функции к каждому элементу массива с целью получения одного итогового значения. Этот метод принимает два аргумента: функцию обратного вызова (callback) и необязательное начальное значение (initialValue)._**
```JavaScript
const numbers = [1, 2, 3, 4, 5];
const sum = numbers.reduce((accumulator, currentValue) => accumulator + currentValue, 0);
console.log(sum); // Выведет 15
```
---
# Метод toSorted() :
+ **_Метод toSorted() сортирует элементы массива в алфавитном порядке. Метод toSorted() возвращает новый массив. Метод toSorted() не перезаписывает исходный массив. Метод toSorted() является копирующей версией метода sort()_**
```JavaScript
const months = ["Mar", "Jan", "Feb", "Dec"];
const sortedMonths = months.toSorted();
console.log(sortedMonths); // ['Dec', 'Feb', 'Jan', 'Mar']
console.log(months); // ['Mar', 'Jan', 'Feb', 'Dec']

```
---
![](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSbokCROhMCbAb7aTE1OiBx102zVHmQVO2vwQ&s)
