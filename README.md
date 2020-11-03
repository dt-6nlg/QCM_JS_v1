# JS_DEBUGGING_DEV_QCM
## Part I
#### Answer the following questions:

- What does the `throw` keyword do?  
==>

- `TypeError` vs `ReferenceError`   
==>

- In the chrome dev tools, inside the sources tab, there is a "pause" button which allows you to "pause on caught exceptions". What is an `exception`?  
==>

- How do we "catch" errors in JavaScript?   
Give an example with code for what that might look like   
==>
```js
// YOUR CODE HERE
```

#### Explain what type of error will be thrown, why the error is occuring and how to fix it:

```javascript
// FIRST LINE OF JS SCRIPT
person;
```
Type of error ==>  
Why? ==>  

---------------------------------------------------------------------------------------------

```javascript
var data = {};
data.displayInfo();
```
Type of error ==>  
Why? ==>  

---------------------------------------------------------------------------------------------

```javascript
var data = {};
data.displayInfo.foo = "bar";
```
Type of error ==>  
Why? ==>  

---------------------------------------------------------------------------------------------

```javascript
function data(){
    var thing = "foo";
}
data()
thing;
```
Type of error ==>  
Why? ==>  

## Part II

Fix the broken code and explain what was wrong:

```javascript
for(var i=0; i > 5; i++){
    console.log(i)
}
```
**FIX**
```javascript
// YOUR CODE HERE
```
What was wrong ==> 

------------------------------------------------------------------------------------------

```javascript
function add5IfEven(num){
    if(num % 2 = 0){
        return num + 5
    }
    return num;
}
```
**FIX**
```javascript
// YOUR CODE HERE
```
What was wrong ==>

------------------------------------------------------------------------------------------

```javascript
function loopToFive(){
    for(var i=0, i < 5, i++){
        console.log(i)
    }
}
```
**FIX**
```javascript
// YOUR CODE HERE
```
What was wrong ==>

 ------------------------------------------------------------------------------------------
 
```javascript
var logOne = setTimeout(math.random() * 1000, function {
  console.gol("one!");
});
```
**FIX**
```javascript
// YOUR CODE HERE
```
What was wrong ==>

 ------------------------------------------------------------------------------------------
 
```javascript
function displayEvenNumbers(){
    var numbers = [1,2,3,4,5,6,7,8]
    var evenNumbers = []
    for(var i=0; i<numbers.length-1; i++;){
        if(numbers % 2 = 0); {
            evenNumbers.push(i)
        }
        return evenNumbers;
    }
}
displayEvenNumbers() // should return [2,4,6,8] 

// HINT - eight things need to be changed here for this to work! Start by fixing the syntax errors and then run the function to see what your output is
```
**FIX**
```javascript
// YOUR CODE HERE
```

What was wrong  
1.  
2.  
3.  
4.  
5.  
6.  
7.  
8.  
## Part III
```javascript
var sample = [1, 2, 3]
var result = sample.filter(elem => elem !== 2)
```
Output ==> 

-----------------------------------------------------------------
```javascript
var sample = [1, 2, 3]
var result = sample.map(elem => elem * 10)
```
Output ==> 

-----------------------------------------------------------------
```javascript
var sample = [1, 2, 3]
var result_filter = sample.filter(elem => elem !== 2)
var result_map = sample.map(elem => elem * 10)
var result_find = sample.find(elem => elem !== 2)
```
`typeof result_filter` ==>   
`typeof result_map` ==>   
`typeof result_find` ==>   

