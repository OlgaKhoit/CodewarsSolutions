##Hello

* https://www.codewars.com/kata/you-only-need-one-beginner/train/javascript

```
function check(a,x){
for (i = 0; i < a.length; i++){
  if ( a[i] === x){
  return true;
}
if(typeof  a[i] === x === 'string'){
 return true;
 }
}
return false;
}
```

* https://www.codewars.com/kata/kata-example-twist/train/javascript

```
// add the value "codewars" to the websites array 1,000 times
let websites = [];
for (i = 0; i < 1000; i++) {
  websites.push('codewars');
  }
```
* https://www.codewars.com/kata/invert-values/train/javascript
```
function invert(array) {
for(i = 0; i <= array.length; i++){
if(!array[i]) continue;
array[i] = array[i] *(-1);
}
return array;
}
```

*https://www.codewars.com/kata/hello-name-or-world/train/javascript
```
function hello(name = '') {
if(!name.trim())  return "Hello, World!";
return 'Hello, ' + name[0].toUpperCase() + name.slice(1).toLowerCase() + '!';
 }
```
*https://www.codewars.com/kata/grasshopper-personalized-message/train/javascript

```
function greet (name, owner) {
 return name === owner ? 'Hello boss' : 'Hello guest';
}

```
* https://www.codewars.com/kata/round-to-nearest-0-or-5/train/javascript

```
function roundToFive(numbers){
  for ( i =0; 1 < numbers.length; i++){
  let remain = numbers[i] % 5
  if (remain >= 2.5){
  numbers[i] = numbers[i] -(5 - remain);
  } else{
  numbers[i] = numbers[i] - remain;
}
}
return numbers;
}
```
*https://www.codewars.com/kata/is-the-string-uppercase/train/javascript

```
String.prototype.isUpperCase  = function(){
  return this.toUpperCase() === this.toString();
}

```
*https://www.codewars.com/kata/51e704f2d8dbace389000279/solutions/javascript

```
function arraysSimilar(arr1, arr2) {
  if(arr1.length !== arr2.length)  return false;
  arr1 = arr1.sort();
  arr2 = arr2.sort();
  for(let i = 0; i < arr2.length; i++){
  if(arr1[i] === arr2[i]) return false;
 }
    return true;
  }
  ```
*new solution