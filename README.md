<img src='https://user-images.githubusercontent.com/74038190/213910845-af37a709-8995-40d6-be59-724526e3c3d7.gif' alt='JavaScript Coding Challenges' id='header' style='display:block; margin:0 auto; width:4500px; max-width:100%; height:auto;'/>
<h1 align="center">JavaScript Coding Challenges</h1>
<div align="center">
<a href="mailto:your-email@example.com">
<img src='https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white' alt='Gmail'/>
</a>
<a href="tel:+1234567890">
<img src='https://img.shields.io/badge/WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white' alt='WhatsApp'/>
</a>
<a href="https://your-website.com" target="_blank">
<img src='https://img.shields.io/badge/website-000000?style=for-the-badge&logo=About.me&logoColor=white' alt='Website'/>
</a>
<a href="https://www.facebook.com/your-profile" target="_blank">
<img src='https://img.shields.io/badge/Facebook-1877F2?style=for-the-badge&logo=facebook&logoColor=white' alt='Facebook'/>
</a>
<a href="https://www.linkedin.com/in/your-profile/" target="_blank">
<img src='https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white' alt='LinkedIn'/>
</a>
<a href="https://github.com/your-profile" target="_blank">
<img src='https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white' alt='GitHub'/>
</a>
</div>

---

## 📚 Table of Contents

| # | Topic |
|---|-------|
| 01–10 | [Basic Math & Operators](#-basic-math--operators) |
| 11–20 | [Strings](#-strings) |
| 21–30 | [Arrays](#-arrays) |
| 31–40 | [Objects](#-objects) |
| 41–50 | [Conditionals & Logic](#-conditionals--logic) |
| 51–60 | [Loops](#-loops) |
| 61–70 | [Functions & Scope](#-functions--scope) |
| 71–80 | [Array Methods](#-array-methods) |
| 81–90 | [DOM & Events (Concept)](#-dom--events-concept) |
| 91–100 | [Mixed / Problem Solving](#-mixed--problem-solving) |

---

## 🔢 Basic Math & Operators

##### 01. Create a function that takes two numbers and returns their sum.

```js
function addition(a, b) {
    // Write Your Solution Here
}
console.log(addition(10, 20)); // 30
console.log(addition(30, 20)); // 50
console.log(addition(10, 90)); // 100
```

<div align="center">
<a href="./cahallenges/01.js"><kbd>See Solution</kbd></a>
</div>
<details><summary style="cursor:pointer">✅ Solution</summary>

```js
function addition(a, b) {
    return a + b;
}
```

</details>

---

##### 02. Create a function that takes two numbers and returns their difference.

```js
function subtraction(a, b) {
    // Write Your Solution Here
}
console.log(subtraction(20, 10)); // 10
console.log(subtraction(50, 30)); // 20
console.log(subtraction(100, 40)); // 60
```

<div align="center">
<a href="./cahallenges/02.js"><kbd>See Solution</kbd></a>
</div>


---

##### 03. Create a function that takes two numbers and returns their product.

```js
function multiplication(a, b) {
    // Write Your Solution Here
}
console.log(multiplication(3, 4));  // 12
console.log(multiplication(5, 6));  // 30
console.log(multiplication(7, 8));  // 56
```

<div align="center">
<a href="./cahallenges/03.js"><kbd>See Solution</kbd></a>
</div>


---

##### 04. Create a function that takes two numbers and returns their quotient.

```js
function division(a, b) {
    // Write Your Solution Here
}
console.log(division(10, 2));  // 5
console.log(division(20, 4));  // 5
console.log(division(100, 10)); // 10
```

<div align="center">
<a href="./cahallenges/04.js"><kbd>See Solution</kbd></a>
</div>


---

##### 05. Create a function that returns the remainder of two numbers.

```js
function remainder(a, b) {
    // Write Your Solution Here
}
console.log(remainder(10, 3)); // 1
console.log(remainder(20, 6)); // 2
console.log(remainder(15, 5)); // 0
```

<div align="center">
<a href="./cahallenges/05.js"><kbd>See Solution</kbd></a>
</div>


---

##### 06. Create a function that returns the square of a number.

```js
function square(n) {
    // Write Your Solution Here
}
console.log(square(4));  // 16
console.log(square(5));  // 25
console.log(square(10)); // 100
```

<div align="center">
<a href="./cahallenges/06.js"><kbd>See Solution</kbd></a>
</div>


---

##### 07. Create a function that returns the square root of a number.

```js
function squareRoot(n) {
    // Write Your Solution Here
}
console.log(squareRoot(16));  // 4
console.log(squareRoot(25));  // 5
console.log(squareRoot(100)); // 10
```

<div align="center">
<a href="./cahallenges/07.js"><kbd>See Solution</kbd></a>
</div>


---

##### 08. Create a function that returns the absolute value of a number.

```js
function absoluteValue(n) {
    // Write Your Solution Here
}
console.log(absoluteValue(-10)); // 10
console.log(absoluteValue(5));   // 5
console.log(absoluteValue(-3));  // 3
```

<div align="center">
<a href="./cahallenges/08.js"><kbd>See Solution</kbd></a>
</div>


---

##### 09. Create a function that returns the larger of two numbers.

```js
function maxNumber(a, b) {
    // Write Your Solution Here
}
console.log(maxNumber(10, 20)); // 20
console.log(maxNumber(50, 30)); // 50
console.log(maxNumber(7, 7));   // 7
```

<div align="center">
<a href="./cahallenges/09.js"><kbd>See Solution</kbd></a>
</div>


---

##### 10. Create a function that rounds a number to the nearest integer.

```js
function roundNumber(n) {
    // Write Your Solution Here
}
console.log(roundNumber(4.3)); // 4
console.log(roundNumber(4.7)); // 5
console.log(roundNumber(5.5)); // 6
```

<div align="center">
<a href="./cahallenges/10.js"><kbd>See Solution</kbd></a>
</div>


---

**[⬆ Back to Top](#header)**

---

## 🔤 Strings

##### 11. Create a function that returns the length of a string.

```js
function stringLength(str) {
    // Write Your Solution Here
}
console.log(stringLength("hello"));       // 5
console.log(stringLength("JavaScript"));  // 10
console.log(stringLength(""));            // 0
```

<div align="center">
<a href="./cahallenges/11.js"><kbd>See Solution</kbd></a>
</div>


---

##### 12. Create a function that converts a string to uppercase.

```js
function toUpperCase(str) {
    // Write Your Solution Here
}
console.log(toUpperCase("hello"));      // HELLO
console.log(toUpperCase("javascript")); // JAVASCRIPT
```

<div align="center">
<a href="./cahallenges/12.js"><kbd>See Solution</kbd></a>
</div>


---

##### 13. Create a function that converts a string to lowercase.

```js
function toLowerCase(str) {
    // Write Your Solution Here
}
console.log(toLowerCase("HELLO"));      // hello
console.log(toLowerCase("JAVASCRIPT")); // javascript
```

<div align="center">
<a href="./cahallenges/13.js"><kbd>See Solution</kbd></a>
</div>


---

##### 14. Create a function that reverses a string.

```js
function reverseString(str) {
    // Write Your Solution Here
}
console.log(reverseString("hello"));  // olleh
console.log(reverseString("world"));  // dlrow
console.log(reverseString("12345"));  // 54321
```

<div align="center">
<a href="./cahallenges/14.js"><kbd>See Solution</kbd></a>
</div>


---

##### 15. Create a function that checks if a string is a palindrome.

```js
function isPalindrome(str) {
    // Write Your Solution Here
}
console.log(isPalindrome("racecar")); // true
console.log(isPalindrome("hello"));   // false
console.log(isPalindrome("madam"));   // true
```

<div align="center">
<a href="./cahallenges/15.js"><kbd>See Solution</kbd></a>
</div>


---

##### 16. Create a function that counts how many vowels are in a string.

```js
function countVowels(str) {
    // Write Your Solution Here
}
console.log(countVowels("hello"));      // 2
console.log(countVowels("javascript")); // 3
console.log(countVowels("sky"));        // 0
```

<div align="center">
<a href="./cahallenges/16.js"><kbd>See Solution</kbd></a>
</div>


---

##### 17. Create a function that capitalizes the first letter of a string.

```js
function capitalizeFirst(str) {
    // Write Your Solution Here
}
console.log(capitalizeFirst("hello"));      // Hello
console.log(capitalizeFirst("javascript")); // Javascript
```

<div align="center">
<a href="./cahallenges/17.js"><kbd>See Solution</kbd></a>
</div>


---

##### 18. Create a function that repeats a string n times.

```js
function repeatString(str, n) {
    // Write Your Solution Here
}
console.log(repeatString("ha", 3)); // hahaha
console.log(repeatString("ab", 2)); // abab
```

<div align="center">
<a href="./cahallenges/18.js"><kbd>See Solution</kbd></a>
</div>


---

##### 19. Create a function that trims whitespace from both ends of a string.

```js
function trimString(str) {
    // Write Your Solution Here
}
console.log(trimString("  hello  ")); // "hello"
console.log(trimString("  world "));  // "world"
```

<div align="center">
<a href="./cahallenges/19.js"><kbd>See Solution</kbd></a>
</div>


---

##### 20. Create a function that replaces all spaces in a string with hyphens.

```js
function spaceToHyphen(str) {
    // Write Your Solution Here
}
console.log(spaceToHyphen("hello world"));    // hello-world
console.log(spaceToHyphen("I love coding"));  // I-love-coding
```

<div align="center">
<a href="./cahallenges/20.js"><kbd>See Solution</kbd></a>
</div>


---

**[⬆ Back to Top](#header)**

---

## 📦 Arrays

##### 21. Create a function that returns the first element of an array.

```js
function firstElement(arr) {
    // Write Your Solution Here
}
console.log(firstElement([1, 2, 3]));       // 1
console.log(firstElement(["a", "b", "c"])); // a
```

<div align="center">
<a href="./cahallenges/21.js"><kbd>See Solution</kbd></a>
</div>


---

##### 22. Create a function that returns the last element of an array.

```js
function lastElement(arr) {
    // Write Your Solution Here
}
console.log(lastElement([1, 2, 3]));       // 3
console.log(lastElement(["a", "b", "c"])); // c
```

<div align="center">
<a href="./cahallenges/22.js"><kbd>See Solution</kbd></a>
</div>


---

##### 23. Create a function that returns the sum of all numbers in an array.

```js
function sumArray(arr) {
    // Write Your Solution Here
}
console.log(sumArray([1, 2, 3, 4, 5])); // 15
console.log(sumArray([10, 20, 30]));     // 60
```

<div align="center">
<a href="./cahallenges/23.js"><kbd>See Solution</kbd></a>
</div>


---

##### 24. Create a function that returns the largest number in an array.

```js
function maxInArray(arr) {
    // Write Your Solution Here
}
console.log(maxInArray([3, 1, 4, 1, 5, 9])); // 9
console.log(maxInArray([10, 20, 5]));         // 20
```

<div align="center">
<a href="./cahallenges/24.js"><kbd>See Solution</kbd></a>
</div>


---

##### 25. Create a function that returns the smallest number in an array.

```js
function minInArray(arr) {
    // Write Your Solution Here
}
console.log(minInArray([3, 1, 4, 1, 5, 9])); // 1
console.log(minInArray([10, 20, 5]));         // 5
```

<div align="center">
<a href="./cahallenges/25.js"><kbd>See Solution</kbd></a>
</div>


---

##### 26. Create a function that removes duplicate values from an array.

```js
function removeDuplicates(arr) {
    // Write Your Solution Here
}
console.log(removeDuplicates([1, 2, 2, 3, 3, 4])); // [1, 2, 3, 4]
console.log(removeDuplicates(["a", "b", "a", "c"])); // ["a", "b", "c"]
```

<div align="center">
<a href="./cahallenges/26.js"><kbd>See Solution</kbd></a>
</div>


---

##### 27. Create a function that flattens a nested array one level deep.

```js
function flattenArray(arr) {
    // Write Your Solution Here
}
console.log(flattenArray([1, [2, 3], [4, 5]])); // [1, 2, 3, 4, 5]
console.log(flattenArray([[1, 2], [3, 4]]));     // [1, 2, 3, 4]
```

<div align="center">
<a href="./cahallenges/27.js"><kbd>See Solution</kbd></a>
</div>


---

##### 28. Create a function that reverses an array.

```js
function reverseArray(arr) {
    // Write Your Solution Here
}
console.log(reverseArray([1, 2, 3, 4, 5])); // [5, 4, 3, 2, 1]
console.log(reverseArray(["a", "b", "c"])); // ["c", "b", "a"]
```

<div align="center">
<a href="./cahallenges/28.js"><kbd>See Solution</kbd></a>
</div>


---

##### 29. Create a function that checks if a value exists in an array.

```js
function includesValue(arr, val) {
    // Write Your Solution Here
}
console.log(includesValue([1, 2, 3], 2));     // true
console.log(includesValue([1, 2, 3], 5));     // false
console.log(includesValue(["a", "b"], "a")); // true
```

<div align="center">
<a href="./cahallenges/29.js"><kbd>See Solution</kbd></a>
</div>


---

##### 30. Create a function that returns the average of an array of numbers.

```js
function average(arr) {
    // Write Your Solution Here
}
console.log(average([1, 2, 3, 4, 5])); // 3
console.log(average([10, 20, 30]));     // 20
```

<div align="center">
<a href="./cahallenges/30.js"><kbd>See Solution</kbd></a>
</div>


---

**[⬆ Back to Top](#header)**

---

## 🗂️ Objects

##### 31. Create a function that returns the value of a specific key from an object.

```js
function getValue(obj, key) {
    // Write Your Solution Here
}
console.log(getValue({ name: "Alice", age: 25 }, "name")); // Alice
console.log(getValue({ name: "Bob", age: 30 }, "age"));    // 30
```

<div align="center">
<a href="./cahallenges/31.js"><kbd>See Solution</kbd></a>
</div>


---

##### 32. Create a function that returns all the keys of an object.

```js
function getKeys(obj) {
    // Write Your Solution Here
}
console.log(getKeys({ a: 1, b: 2, c: 3 })); // ["a", "b", "c"]
```

<div align="center">
<a href="./cahallenges/32.js"><kbd>See Solution</kbd></a>
</div>


---

##### 33. Create a function that returns all the values of an object.

```js
function getValues(obj) {
    // Write Your Solution Here
}
console.log(getValues({ a: 1, b: 2, c: 3 })); // [1, 2, 3]
```

<div align="center">
<a href="./cahallenges/33.js"><kbd>See Solution</kbd></a>
</div>


---

##### 34. Create a function that merges two objects into one.

```js
function mergeObjects(obj1, obj2) {
    // Write Your Solution Here
}
console.log(mergeObjects({ a: 1 }, { b: 2 })); // { a: 1, b: 2 }
```

<div align="center">
<a href="./cahallenges/34.js"><kbd>See Solution</kbd></a>
</div>


---

##### 35. Create a function that checks if a key exists in an object.

```js
function hasKey(obj, key) {
    // Write Your Solution Here
}
console.log(hasKey({ name: "Alice" }, "name")); // true
console.log(hasKey({ name: "Alice" }, "age"));  // false
```

<div align="center">
<a href="./cahallenges/35.js"><kbd>See Solution</kbd></a>
</div>


---

##### 36. Create a function that counts the number of keys in an object.

```js
function countKeys(obj) {
    // Write Your Solution Here
}
console.log(countKeys({ a: 1, b: 2, c: 3 })); // 3
console.log(countKeys({}));                    // 0
```

<div align="center">
<a href="./cahallenges/36.js"><kbd>See Solution</kbd></a>
</div>


---

##### 37. Create a function that converts an object to an array of [key, value] pairs.

```js
function objectToArray(obj) {
    // Write Your Solution Here
}
console.log(objectToArray({ a: 1, b: 2 })); // [["a", 1], ["b", 2]]
```

<div align="center">
<a href="./cahallenges/37.js"><kbd>See Solution</kbd></a>
</div>


---

##### 38. Create a function that deletes a key from an object and returns the updated object.

```js
function deleteKey(obj, key) {
    // Write Your Solution Here
}
console.log(deleteKey({ a: 1, b: 2, c: 3 }, "b")); // { a: 1, c: 3 }
```

<div align="center">
<a href="./cahallenges/38.js"><kbd>See Solution</kbd></a>
</div>


---

##### 39. Create a function that creates an object from two arrays (keys and values).

```js
function createObject(keys, values) {
    // Write Your Solution Here
}
console.log(createObject(["a", "b", "c"], [1, 2, 3])); // { a: 1, b: 2, c: 3 }
```

<div align="center">
<a href="./cahallenges/39.js"><kbd>See Solution</kbd></a>
</div>


---

##### 40. Create a function that inverts the keys and values of an object.

```js
function invertObject(obj) {
    // Write Your Solution Here
}
console.log(invertObject({ a: 1, b: 2, c: 3 })); // { 1: "a", 2: "b", 3: "c" }
```

<div align="center">
<a href="./cahallenges/40.js"><kbd>See Solution</kbd></a>
</div>


---

**[⬆ Back to Top](#header)**

---

## 🔀 Conditionals & Logic

##### 41. Create a function that checks if a number is even or odd.

```js
function evenOrOdd(n) {
    // Write Your Solution Here
}
console.log(evenOrOdd(4));  // "Even"
console.log(evenOrOdd(7));  // "Odd"
console.log(evenOrOdd(0));  // "Even"
```

<div align="center">
<a href="./cahallenges/41.js"><kbd>See Solution</kbd></a>
</div>


---

##### 42. Create a function that returns "Fizz" for multiples of 3, "Buzz" for multiples of 5, and "FizzBuzz" for both.

```js
function fizzBuzz(n) {
    // Write Your Solution Here
}
console.log(fizzBuzz(3));  // Fizz
console.log(fizzBuzz(5));  // Buzz
console.log(fizzBuzz(15)); // FizzBuzz
console.log(fizzBuzz(7));  // 7
```

<div align="center">
<a href="./cahallenges/42.js"><kbd>See Solution</kbd></a>
</div>


---

##### 43. Create a function that checks if a number is positive, negative, or zero.

```js
function checkSign(n) {
    // Write Your Solution Here
}
console.log(checkSign(5));  // "Positive"
console.log(checkSign(-3)); // "Negative"
console.log(checkSign(0));  // "Zero"
```

<div align="center">
<a href="./cahallenges/43.js"><kbd>See Solution</kbd></a>
</div>


---

##### 44. Create a function that checks if a person is eligible to vote (age >= 18).

```js
function canVote(age) {
    // Write Your Solution Here
}
console.log(canVote(20)); // true
console.log(canVote(17)); // false
console.log(canVote(18)); // true
```

<div align="center">
<a href="./cahallenges/44.js"><kbd>See Solution</kbd></a>
</div>


---

##### 45. Create a function that returns the grade letter for a given score.

```js
function getGrade(score) {
    // Write Your Solution Here
    // 90-100: A, 80-89: B, 70-79: C, 60-69: D, below 60: F
}
console.log(getGrade(95)); // A
console.log(getGrade(82)); // B
console.log(getGrade(55)); // F
```

<div align="center">
<a href="./cahallenges/45.js"><kbd>See Solution</kbd></a>
</div>


---

##### 46. Create a function that checks if a year is a leap year.

```js
function isLeapYear(year) {
    // Write Your Solution Here
}
console.log(isLeapYear(2000)); // true
console.log(isLeapYear(1900)); // false
console.log(isLeapYear(2024)); // true
```

<div align="center">
<a href="./cahallenges/46.js"><kbd>See Solution</kbd></a>
</div>


---

##### 47. Create a function that returns the maximum of three numbers.

```js
function maxOfThree(a, b, c) {
    // Write Your Solution Here
}
console.log(maxOfThree(3, 7, 5)); // 7
console.log(maxOfThree(10, 2, 8)); // 10
```

<div align="center">
<a href="./cahallenges/47.js"><kbd>See Solution</kbd></a>
</div>


---

##### 48. Create a function that checks whether a number is between two values (inclusive).

```js
function isBetween(n, min, max) {
    // Write Your Solution Here
}
console.log(isBetween(5, 1, 10));  // true
console.log(isBetween(15, 1, 10)); // false
console.log(isBetween(1, 1, 10));  // true
```

<div align="center">
<a href="./cahallenges/48.js"><kbd>See Solution</kbd></a>
</div>


---

##### 49. Create a function that returns the day name for a given day number (1=Monday … 7=Sunday).

```js
function getDayName(num) {
    // Write Your Solution Here
}
console.log(getDayName(1)); // Monday
console.log(getDayName(5)); // Friday
console.log(getDayName(7)); // Sunday
```

<div align="center">
<a href="./cahallenges/49.js"><kbd>See Solution</kbd></a>
</div>


---

##### 50. Create a function that returns "Discount" if price is above 100, otherwise "No Discount".

```js
function checkDiscount(price) {
    // Write Your Solution Here
}
console.log(checkDiscount(150)); // Discount
console.log(checkDiscount(80));  // No Discount
console.log(checkDiscount(100)); // No Discount
```

<div align="center">
<a href="./cahallenges/50.js"><kbd>See Solution</kbd></a>
</div>


---

**[⬆ Back to Top](#header)**

---

## 🔁 Loops

##### 51. Create a function that prints numbers from 1 to n using a for loop.

```js
function printNumbers(n) {
    // Write Your Solution Here
}
printNumbers(5); // 1 2 3 4 5
```

<div align="center">
<a href="./cahallenges/51.js"><kbd>See Solution</kbd></a>
</div>


---

##### 52. Create a function that calculates the factorial of a number.

```js
function factorial(n) {
    // Write Your Solution Here
}
console.log(factorial(5)); // 120
console.log(factorial(4)); // 24
console.log(factorial(0)); // 1
```

<div align="center">
<a href="./cahallenges/52.js"><kbd>See Solution</kbd></a>
</div>


---

##### 53. Create a function that returns the sum of numbers from 1 to n.

```js
function sumToN(n) {
    // Write Your Solution Here
}
console.log(sumToN(5));  // 15
console.log(sumToN(10)); // 55
```

<div align="center">
<a href="./cahallenges/53.js"><kbd>See Solution</kbd></a>
</div>


---

##### 54. Create a function that prints the multiplication table of a given number.

```js
function multiplicationTable(n) {
    // Write Your Solution Here
}
multiplicationTable(3);
// 3 x 1 = 3
// 3 x 2 = 6 ... up to 3 x 10 = 30
```

<div align="center">
<a href="./cahallenges/54.js"><kbd>See Solution</kbd></a>
</div>


---

##### 55. Create a function that returns all even numbers from 1 to n.

```js
function evenNumbers(n) {
    // Write Your Solution Here
}
console.log(evenNumbers(10)); // [2, 4, 6, 8, 10]
```

<div align="center">
<a href="./cahallenges/55.js"><kbd>See Solution</kbd></a>
</div>


---

##### 56. Create a function that returns all odd numbers from 1 to n.

```js
function oddNumbers(n) {
    // Write Your Solution Here
}
console.log(oddNumbers(10)); // [1, 3, 5, 7, 9]
```

<div align="center">
<a href="./cahallenges/56.js"><kbd>See Solution</kbd></a>
</div>


---

##### 57. Create a function that returns the nth Fibonacci number.

```js
function fibonacci(n) {
    // Write Your Solution Here
}
console.log(fibonacci(6)); // 8
console.log(fibonacci(7)); // 13
// Sequence: 0, 1, 1, 2, 3, 5, 8, 13 ...
```

<div align="center">
<a href="./cahallenges/57.js"><kbd>See Solution</kbd></a>
</div>


---

##### 58. Create a function that counts down from n to 1.

```js
function countDown(n) {
    // Write Your Solution Here
}
countDown(5); // 5 4 3 2 1
```

<div align="center">
<a href="./cahallenges/58.js"><kbd>See Solution</kbd></a>
</div>


---

##### 59. Create a function that finds the sum of all even numbers from 1 to n.

```js
function sumOfEvens(n) {
    // Write Your Solution Here
}
console.log(sumOfEvens(10)); // 30
console.log(sumOfEvens(6));  // 12
```

<div align="center">
<a href="./cahallenges/59.js"><kbd>See Solution</kbd></a>
</div>


---

##### 60. Create a function that finds all prime numbers up to n.

```js
function findPrimes(n) {
    // Write Your Solution Here
}
console.log(findPrimes(20)); // [2, 3, 5, 7, 11, 13, 17, 19]
```

<div align="center">
<a href="./cahallenges/60.js"><kbd>See Solution</kbd></a>
</div>


---

**[⬆ Back to Top](#header)**

---

## ⚙️ Functions & Scope

##### 61. Create a function that returns another function (closure) which adds a fixed number.

```js
function makeAdder(x) {
    // Write Your Solution Here
}
const add5 = makeAdder(5);
console.log(add5(3));  // 8
console.log(add5(10)); // 15
```

<div align="center">
<a href="./cahallenges/61.js"><kbd>See Solution</kbd></a>
</div>


---

##### 62. Create a recursive function that calculates the power of a number.

```js
function power(base, exp) {
    // Write Your Solution Here
}
console.log(power(2, 10)); // 1024
console.log(power(3, 3));  // 27
```

<div align="center">
<a href="./cahallenges/62.js"><kbd>See Solution</kbd></a>
</div>


---

##### 63. Create a function that accepts any number of arguments and returns their sum.

```js
function sumAll(...args) {
    // Write Your Solution Here
}
console.log(sumAll(1, 2, 3));       // 6
console.log(sumAll(10, 20, 30, 40)); // 100
```

<div align="center">
<a href="./cahallenges/63.js"><kbd>See Solution</kbd></a>
</div>


---

##### 64. Create a function that memoizes the result of another function.

```js
function memoize(fn) {
    // Write Your Solution Here
}
const double = memoize(n => n * 2);
console.log(double(5));  // 10
console.log(double(5));  // 10 (from cache)
```

<div align="center">
<a href="./cahallenges/64.js"><kbd>See Solution</kbd></a>
</div>


---

##### 65. Create a function that runs another function exactly once.

```js
function once(fn) {
    // Write Your Solution Here
}
const greet = once(() => console.log("Hello!"));
greet(); // Hello!
greet(); // (nothing)
greet(); // (nothing)
```

<div align="center">
<a href="./cahallenges/65.js"><kbd>See Solution</kbd></a>
</div>


---

##### 66. Create a function that returns a new function which calls the original with reversed arguments.

```js
function reverseArgs(fn) {
    // Write Your Solution Here
}
const subtract = (a, b) => a - b;
const reversedSubtract = reverseArgs(subtract);
console.log(reversedSubtract(3, 10)); // 7
```

<div align="center">
<a href="./cahallenges/66.js"><kbd>See Solution</kbd></a>
</div>


---

##### 67. Create a function that composes two functions together.

```js
function compose(f, g) {
    // Write Your Solution Here
}
const double = x => x * 2;
const addOne = x => x + 1;
const doubleThenAdd = compose(addOne, double);
console.log(doubleThenAdd(5)); // 11
```

<div align="center">
<a href="./cahallenges/67.js"><kbd>See Solution</kbd></a>
</div>


---

##### 68. Create a curried function for multiplication.

```js
function multiply(a) {
    // Write Your Solution Here
}
console.log(multiply(3)(4)); // 12
console.log(multiply(5)(5)); // 25
```

<div align="center">
<a href="./cahallenges/68.js"><kbd>See Solution</kbd></a>
</div>


---

##### 69. Create a function that delays execution using a callback.

```js
function delayedGreet(name, delay, callback) {
    // Write Your Solution Here
}
delayedGreet("Alice", 1000, (msg) => console.log(msg));
// After 1 second: "Hello, Alice!"
```

<div align="center">
<a href="./cahallenges/69.js"><kbd>See Solution</kbd></a>
</div>


---

##### 70. Create a function that returns a promise that resolves after a given number of milliseconds.

```js
function wait(ms) {
    // Write Your Solution Here
}
wait(1000).then(() => console.log("Done after 1 second!"));
```

<div align="center">
<a href="./cahallenges/70.js"><kbd>See Solution</kbd></a>
</div>


---

**[⬆ Back to Top](#header)**

---

## 🧰 Array Methods

##### 71. Use `.map()` to double every number in an array.

```js
function doubleAll(arr) {
    // Write Your Solution Here
}
console.log(doubleAll([1, 2, 3, 4])); // [2, 4, 6, 8]
```

<div align="center">
<a href="./cahallenges/71.js"><kbd>See Solution</kbd></a>
</div>


---

##### 72. Use `.filter()` to return only numbers greater than 10.

```js
function greaterThan10(arr) {
    // Write Your Solution Here
}
console.log(greaterThan10([5, 12, 3, 20, 8])); // [12, 20]
```

<div align="center">
<a href="./cahallenges/72.js"><kbd>See Solution</kbd></a>
</div>


---

##### 73. Use `.reduce()` to find the product of all numbers in an array.

```js
function productArray(arr) {
    // Write Your Solution Here
}
console.log(productArray([1, 2, 3, 4, 5])); // 120
```

<div align="center">
<a href="./cahallenges/73.js"><kbd>See Solution</kbd></a>
</div>


---

##### 74. Use `.find()` to return the first number greater than 10.

```js
function findFirstOver10(arr) {
    // Write Your Solution Here
}
console.log(findFirstOver10([3, 7, 12, 5, 20])); // 12
```

<div align="center">
<a href="./cahallenges/74.js"><kbd>See Solution</kbd></a>
</div>


---

##### 75. Use `.some()` to check if any number in an array is negative.

```js
function hasNegative(arr) {
    // Write Your Solution Here
}
console.log(hasNegative([1, -2, 3])); // true
console.log(hasNegative([1, 2, 3]));  // false
```

<div align="center">
<a href="./cahallenges/75.js"><kbd>See Solution</kbd></a>
</div>


---

##### 76. Use `.every()` to check if all values in an array are strings.

```js
function allStrings(arr) {
    // Write Your Solution Here
}
console.log(allStrings(["a", "b", "c"]));   // true
console.log(allStrings(["a", 1, "c"]));     // false
```

<div align="center">
<a href="./cahallenges/76.js"><kbd>See Solution</kbd></a>
</div>


---

##### 77. Use `.sort()` to sort an array of numbers in ascending order.

```js
function sortAscending(arr) {
    // Write Your Solution Here
}
console.log(sortAscending([3, 1, 4, 1, 5, 9])); // [1, 1, 3, 4, 5, 9]
```

<div align="center">
<a href="./cahallenges/77.js"><kbd>See Solution</kbd></a>
</div>


---

##### 78. Use `.flatMap()` to split sentences into individual words.

```js
function splitWords(arr) {
    // Write Your Solution Here
}
console.log(splitWords(["Hello World", "I love JS"]));
// ["Hello", "World", "I", "love", "JS"]
```

<div align="center">
<a href="./cahallenges/78.js"><kbd>See Solution</kbd></a>
</div>


---

##### 79. Use `.reduce()` to group an array of strings by their first letter.

```js
function groupByFirstLetter(arr) {
    // Write Your Solution Here
}
console.log(groupByFirstLetter(["apple", "banana", "avocado", "blueberry"]));
// { a: ["apple", "avocado"], b: ["banana", "blueberry"] }
```

<div align="center">
<a href="./cahallenges/79.js"><kbd>See Solution</kbd></a>
</div>


---

##### 80. Use chaining (`.filter().map()`) to get squares of all even numbers in an array.

```js
function squaresOfEvens(arr) {
    // Write Your Solution Here
}
console.log(squaresOfEvens([1, 2, 3, 4, 5, 6])); // [4, 16, 36]
```

<div align="center">
<a href="./cahallenges/80.js"><kbd>See Solution</kbd></a>
</div>


---

**[⬆ Back to Top](#header)**

---

## 🖥️ DOM & Events (Concept)

##### 81. Write a function that changes the text content of an element by its ID.

```js
function changeText(id, newText) {
    // Write Your Solution Here
}
// changeText("title", "Hello World");
// → document.getElementById("title").textContent = "Hello World"
```

<div align="center">
<a href="./cahallenges/81.js"><kbd>See Solution</kbd></a>
</div>


---

##### 82. Write a function that adds a CSS class to an element by its ID.

```js
function addClass(id, className) {
    // Write Your Solution Here
}
```

<div align="center">
<a href="./cahallenges/82.js"><kbd>See Solution</kbd></a>
</div>


---

##### 83. Write a function that toggles a CSS class on an element.

```js
function toggleClass(id, className) {
    // Write Your Solution Here
}
```

<div align="center">
<a href="./cahallenges/83.js"><kbd>See Solution</kbd></a>
</div>


---

##### 84. Write a function that creates a new `<li>` element and appends it to a `<ul>` by ID.

```js
function addListItem(ulId, text) {
    // Write Your Solution Here
}
```

<div align="center">
<a href="./cahallenges/84.js"><kbd>See Solution</kbd></a>
</div>


---

##### 85. Write a function that removes an element from the DOM by its ID.

```js
function removeElement(id) {
    // Write Your Solution Here
}
```

<div align="center">
<a href="./cahallenges/85.js"><kbd>See Solution</kbd></a>
</div>


---

##### 86. Write a function that changes the background color of an element.

```js
function changeBackground(id, color) {
    // Write Your Solution Here
}
```

<div align="center">
<a href="./cahallenges/86.js"><kbd>See Solution</kbd></a>
</div>


---

##### 87. Write a function that attaches a click event listener to a button.

```js
function onButtonClick(buttonId, callback) {
    // Write Your Solution Here
}
```

<div align="center">
<a href="./cahallenges/87.js"><kbd>See Solution</kbd></a>
</div>


---

##### 88. Write a function that reads the value of an input field.

```js
function getInputValue(inputId) {
    // Write Your Solution Here
}
```

<div align="center">
<a href="./cahallenges/88.js"><kbd>See Solution</kbd></a>
</div>


---

##### 89. Write a function that hides an element using inline styles.

```js
function hideElement(id) {
    // Write Your Solution Here
}
```

<div align="center">
<a href="./cahallenges/89.js"><kbd>See Solution</kbd></a>
</div>


---

##### 90. Write a function that counts all `<p>` tags in the document.

```js
function countParagraphs() {
    // Write Your Solution Here
}
```

<div align="center">
<a href="./cahallenges/90.js"><kbd>See Solution</kbd></a>
</div>


---

**[⬆ Back to Top](#header)**

---

## 🧩 Mixed / Problem Solving

##### 91. Create a function that counts the occurrences of each character in a string.

```js
function charCount(str) {
    // Write Your Solution Here
}
console.log(charCount("hello")); // { h: 1, e: 1, l: 2, o: 1 }
```

<div align="center">
<a href="./cahallenges/91.js"><kbd>See Solution</kbd></a>
</div>


---

##### 92. Create a function that checks if two strings are anagrams.

```js
function isAnagram(str1, str2) {
    // Write Your Solution Here
}
console.log(isAnagram("listen", "silent")); // true
console.log(isAnagram("hello", "world"));   // false
```

<div align="center">
<a href="./cahallenges/92.js"><kbd>See Solution</kbd></a>
</div>


---

##### 93. Create a function that finds the most frequent element in an array.

```js
function mostFrequent(arr) {
    // Write Your Solution Here
}
console.log(mostFrequent([1, 2, 2, 3, 3, 3])); // 3
console.log(mostFrequent(["a", "b", "a"]));     // a
```

<div align="center">
<a href="./cahallenges/93.js"><kbd>See Solution</kbd></a>
</div>


---

##### 94. Create a function that converts Celsius to Fahrenheit.

```js
function celsiusToFahrenheit(c) {
    // Write Your Solution Here
}
console.log(celsiusToFahrenheit(0));   // 32
console.log(celsiusToFahrenheit(100)); // 212
```

<div align="center">
<a href="./cahallenges/94.js"><kbd>See Solution</kbd></a>
</div>


---

##### 95. Create a function that converts a number to binary (string).

```js
function toBinary(n) {
    // Write Your Solution Here
}
console.log(toBinary(5));  // "101"
console.log(toBinary(10)); // "1010"
```

<div align="center">
<a href="./cahallenges/95.js"><kbd>See Solution</kbd></a>
</div>


---

##### 96. Create a function that chunks an array into groups of a given size.

```js
function chunkArray(arr, size) {
    // Write Your Solution Here
}
console.log(chunkArray([1,2,3,4,5], 2)); // [[1,2],[3,4],[5]]
```

<div align="center">
<a href="./cahallenges/96.js"><kbd>See Solution</kbd></a>
</div>


---

##### 97. Create a function that returns the intersection of two arrays.

```js
function intersection(arr1, arr2) {
    // Write Your Solution Here
}
console.log(intersection([1,2,3,4], [3,4,5,6])); // [3, 4]
```

<div align="center">
<a href="./cahallenges/97.js"><kbd>See Solution</kbd></a>
</div>


---

##### 98. Create a function that capitalizes every word in a sentence.

```js
function titleCase(str) {
    // Write Your Solution Here
}
console.log(titleCase("hello world from js")); // Hello World From Js
```

<div align="center">
<a href="./cahallenges/98.js"><kbd>See Solution</kbd></a>
</div>


---

##### 99. Create a function that deep clones an object.

```js
function deepClone(obj) {
    // Write Your Solution Here
}
const original = { a: 1, b: { c: 2 } };
const clone = deepClone(original);
clone.b.c = 99;
console.log(original.b.c); // 2 (unchanged)
```

<div align="center">
<a href="./cahallenges/99.js"><kbd>See Solution</kbd></a>
</div>


---

##### 100. Create a function that flattens a deeply nested array.

```js
function deepFlatten(arr) {
    // Write Your Solution Here
}
console.log(deepFlatten([1, [2, [3, [4, [5]]]]])); // [1, 2, 3, 4, 5]
```

<div align="center">
<a href="./cahallenges/100.js"><kbd>See Solution</kbd></a>
</div>

---

**[⬆ Back to Top](#header)**

---

<div align="center">

### 🚀 Keep Practicing Every Day — Consistency Beats Talent!

Made with ❤️ for JavaScript Learners

</div>