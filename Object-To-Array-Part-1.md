Instructions from your teacher:
Module 0 Wiki: https://github.com/tim-hr/reactor-prep/wiki/Module-0

Write a function called "getAllKeys" which returns an array of all the input object's keys.
Example input: 
```javascript
{
  name : 'Sam',
  age : 25,
  hasPets : true
}
```
Function's return value (output) :
```javascript
['name', 'age', 'hasPets']
```

Do not use "Object.keys" to solve this prompt.

Note that your function should be able to handle any object passed in it.

E.g. it should also handle an input like:
```javascript
{
  a : 'a',
  number : 11,
  hungry : true,
  grammyWins : 1
}
```
Function's return value (output):
```javascript
['a', 'number', 'hungry', 'grammyWins']
```

Starter Code:
```javascriptfunction getAllKeys(obj) {
  // your code here
}
```
```javascript
function getAllKeys(obj) {
  
  for (var prop in obj) {
    if (obj.prototype.hasOwnProperty.call(obj, prop)) {
      
      
    }
  }
  return newArray;
}

getAllKeys({name: 'Sam', age: 25})
```

/* Takeaways

http://stackoverflow.com/questions/7306669/how-to-get-all-properties-values-of-a-javascript-object-without-knowing-the-key

*/ 
