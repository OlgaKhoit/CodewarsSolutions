##Hello

* https://www.codewars.com/kata/reverse-a-number/train/javascript

```
function reverseNumber(n) {
 if(n >= 0){
 let arr = n.toString().split('').reverse();
 return +(arr.join(''))
 } else {
 n = n * (-1);
 let arr = n.toString().split('').reverse();
 return (-1) * ( +( arr.join('')));
}
}

```

*https://www.codewars.com/kata/numerical-palindrome-number-1/train/javascript

```
function palindrome(num) { 
let str = '';
if (typeof num !== 'number' || num < 0){
  return 'Not valid';
  }
  str = num + '';
  for (let i = 0; i < Math.floor(str.length / 2); i++){
  if (str[i] !== str[str.length - i -1]) {
  return false;
  }
  }
  return true;
  }
```
*https://www.codewars.com/kata/calculate-average/train/javascript

```
function find_average(array) {
let sum = 0;
let count = 0;
for(let i = 0; i < array.length; i++){
sum += array[i]
count ++;
  }
  return sum/count;
}
```
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