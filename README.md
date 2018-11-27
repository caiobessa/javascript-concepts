## Big Words Java Script



### Primitive types: 
``` javascript
 boolean,  number, undefined, symbol, string, null. 
```



### Single Thread 

![alt text](execution_context.png "Logo Title Text 1")


### Associative 

```javascript 
var a =  2, b = 3, c =4;
a = b = c;

console.log(a);

result iguals 4. 
```
[Link](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Operator_Precedence) to search precedence

### Equanlity and comparesions

https://developer.mozilla.org/en-US/docs/Web/JavaScript/Equality_comparisons_and_sameness



### JSON and Object Literals 

Object literals exemple
```javascript
var objectLiteral = {
   firstName : "Caio",
   age : 18
}
```
JSON -> JavaSript Object Notation

```json
{
 "firstName" : "Caio",
 "age" : 18
}
```

tranformome object literal to JSON 
```javascript 
console.log(JSON.stringfy(objectLiteral));
````

### Function

- Function are objects
- funcation and object is passed by reference. primitive types are passed by value
