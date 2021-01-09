# learn-javascript
Learn Javascript with me!


#  Lesson 1

### **Javascript Data Types - (Primitive data types)**

1. Number : Integer/bigint/float. ex: 0,1,2,3. ex: 92731231 float: 34.5, 23.9, 14.2
```js
const numberInteger = 12; //output -> 12
const numberFloat = 34.5; //output -> 34.5

//use console.log() for print any kind of variables and display output.
console.log(numberInteger);
console.log(numberFloat);

```
2. String : Any grouping character surrounded by single quotes/double quotes. ex: "hello world" or 'I\'m robot'
```js
const doubleQuote = "hello world"; // output -> hello world
const singleQuote = 'I\m robot'; //output -> I'm robot

//use console.log() for print any kind of variables and display output.
console.log(doubleQuote);
console.log(singleQuote);
```

3. Boolean : True/False. ex: true/false.
```js
const isTrue = true; //output -> true
const isFalse = false; //output -> true

//use console.log() for print any kind of variables and display output.
console.log(isTrue);
console.log(isFalse);
```

4. Null : absence of a value. ex: null.
```js
const absence = null; //output -> null

//use console.log() for print any kind of variables and display output.
console.log(absence);
```

5. Undefined : absence of value/not yet defined. ex: undefined.
```js
const isUndefined = undefined; //output -> undefined
const aVariable;

//use console.log() for print any kind of variables and display output.
console.log(isUndefined); //output -> undefined
console.log(aVariable); //output -> undefined
console.log(typeof aVariable); //output -> undefined

```

6. Symbol : symbol that define variables.
```js
const isSymbol = Symbol("yes");

//use console.log() for print any kind of variables and display output.
console.log(isSymbol.toString()); // output -> Symbol("yes")
console.log(isSymbol.description); // output -> yes
```

7. Object : collections of related data. array, function, dan object.
```js
let isObjects = {
    name: "tustoz",  // by key "name" store value "tustoz"
    age: 17, // // by key "age" store value "17"
};

//use console.log() for print any kind of variables and display output.
console.log(isObjects); //output -> { name: 'tustoz', age: 17 }
```
