## JavaScript Interview Questions

      This document is provided to who wants to prepare front-end interview
      so it doesn't explain the concepts deeply, if you need more details please google it. 
<br/>

1. Explan What Is Closure?

> - Closure gives an ability let inner function gain access to a variable declared in some other function scope, 
we can have private variable through closure w/o environment interference, A function returns another function. <br/>
> - [Without Use Closure](https://jsfiddle.net/yschen25/aofkj153/14/) <br/>
> - [Use Closure](https://jsfiddle.net/yschen25/pvqbxjr7) <br/>
> - More improvement [Use Anonymous And Arrow Function](https://jsfiddle.net/yschen25/rjefc2sg/) <br/>
> - Even use the same function, variables don't disturb each other cuz the excute environment is different [Use The Same Function](https://jsfiddle.net/yschen25/q5ohxarL/) <br/>

Related Reference : [深入淺出瞭解 JavaScript 閉包（closure）](https://pjchender.blogspot.com/2017/05/javascript-closure.html)
<br/>

2. Explain What Is Promise?

<br/>

3. Explain What Is The Difference Between ES5 And ES6?

<br/>

4. Explain What Is The Difference Between push(), pop(), unshift(), shift()?

| Methods |  push() | pop() | unshift() | shift() | 
|---|---|---|---|---|
|  | **ADD** the element in the **END** of array | **DELETE** the element in the **END** of array | **ADD** the element in the **BEGINNING** of array | **DELETE** the element in the **BEGINNING** of array |
<br/>

5. Explain What Is The Difference Between slice(), splice(), splite()?

| Methods |  slice(start, end) | splice(index, howmany, item1, ....., itemX) | split(separator, limit) | 
|---|---|---|---|
|  | (optional, optional) | (required, optional, optional)| (optional, optional) |
|  | (If use negative numbers it will select from the end of an array, it acts like "0" if omitted ; Whole array will be selected if omitted, use negative numbers will select from the end of an array) | (Specifies at what position to add/remove items, use negative values to specify the position from the end of the array ; The number of items to be removed, The new item(s) to be added to the array) | (Specifies the character, or the regular expression, to use for splitting the string;  Specifies the number of splits)|