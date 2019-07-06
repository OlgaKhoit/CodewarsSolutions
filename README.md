##Hello
```
function first(arr, n = 1) {
  let returnArr = [];
  if (n > arr.length) {
    return arr;
  }
  for (let i = 0; i < n; i++) {
    returnArr.push(arr[i]);
  }
  return returnArr;
}

``` 
*https://www.codewars.com/kata/5168bb5dfe9a00b126000018/solutions/solutions
             
```

function solution(str) {
  return str.split('').reverse().join('');
}

```
 *https://www.codewars.com/kata/count-odd-numbers-below-n/train/javascript
             
```

function oddCount(num) {
  var count = 0;
  for (var i = 0; i < num; i++) {
    if (i % 2 === 1) {
      count++;
    }
  }
  return count;
}
```
*https://www.codewars.com/kata/surface-area-and-volume-of-a-box/train/javascript
             
 ```

function getSize(width, height, depth) {
  var area = 2 * width * height + 2 * width * depth + 2 * height * depth;
  var volume = width * height * depth;

  return [area, volume];
}

```
 *https://www.codewars.com/kata/credit-card-issuer-checking/train/javascript
             
             
```

function getIssuer(number) {
  if (/^3[4|7]\d{13}$/.test(number)) return 'AMEX'
  if (/^6011\d{12}$/.test(number)) return 'Discover'
  if (/^5[1-5]\d{14}$/.test(number)) return 'Mastercard'
  if (/^4(\d{12}|\d{15})$/.test(number)) return 'VISA'
  return 'Unknown'
}
```
             
 *https://www.codewars.com/kata/remove-string-spaces/train/javascript
             
```

function noSpace(x) {
  let emptyString = '';
  for (i = 0; i < x.length; i++) {
    if (x[i] !== ' ') {
      emptyString += x[i];
    }
  }
  return emptyString;
}
```
*https://www.codewars.com/kata/convert-a-boolean-to-a-string/train/javascript
             
```

function booleanToString(b) {
  str = '';
  if (b === true) {
    return str = 'true';
  } else {
    return str = 'false';
  }
}
```
             
*https://www.codewars.com/kata/reversed-words/train/javascript
             
```

function reverseWords(str) {
  let split1 = str.split(' ');
  let rev = '';
  for (let i = split1.length - 1; i >= 0; i--) {
    rev += split1[i];
    rev += ' ';
  }
  return rev.slice(0, -1);
}
```
             
*https://www.codewars.com/kata/reverse-words/train/javascript
             
```

function reverseWords(str) {
    let split1 = str.split(' ');
    let rev = '';
    for (let i = 0; i < split1.length; i++) {
      for (let j = split1[i].length - 1; j >= 0; j--) {
        rev += split1[i][j];
      }
      rev += ' ';
    }
    return rev.slice(0, -1);

```
             
*https://www.codewars.com/kata/mumbling/train/javascript
             
```

    function accum(s) {
      let Arr = [];
      for (let i = 0; i < s.length; i++) {
        Arr.push(form(s[i], i + 1));
      }
      return Arr.join('-');
    }

    function form(str, num) {
      let letter = str.toUpperCase();
      while (letter.length != num) {
        letter += str.toLowerCase();
      }
      return letter;
    }
```
             
*https://www.codewars.com/kata/friend-or-foe/train/javascript
             
```

    function friend(friends) {
      let arr = [];
      for (let i = 0; i < friends.length; i++) {
        if (friends[i].length === 4) {
          arr.push(friends[i]);
        }
      }
      return arr;
    }

```
*https://www.codewars.com/kata/list-filtering/train/javascri
             
```

    function filter_list(l) {
      let arr = [];
      for (let i = 0; i < l.length; i++) {
        if (typeof l[i] === 'number') {
          arr.push(l[i]);
        }
      }
      return arr;
    }
  ```
             
*https://www.codewars.com/kata/count-odd-numbers-below-n/train/javascript
             
```             

    function oddCount(num) {
      let count = 0;
      for (let i = 0; i < num; i++) {
        if (i % 2 === 1) {
          count++;
        }
      }
      return count;
    }

```
 *https://www.codewars.com/kata/l1-set-alarm/train/javascript
             
```

    function setAlarm(employed, vacation) {
      if (employed && !vacation) {
        return true;
      } else {
        return false;
      }
    }

 ```

*https://www.codewars.com/kata/5a2be17aee1aaefe2a000151/solutions/javascript


```
function arrayPlusArray() {
    var res = 0;

  for (var i = 0 ; i < arguments.length; i+=1) {

    for (var j = 0; j < arguments[i].length ; j +=1) {

      res+=arguments[i][j];
    }
  }
 return res;
}
```

*https://www.codewars.com/kata/514b92a657cdc65150000006/solutions/javascript

```
function solution(number){
  var sum = 0;
  
  for(var i = 1;i< number; i++){
    if(i % 3 == 0 || i % 5 == 0){
      sum += i
    }
  }
  return sum;
}
```

*https://www.codewars.com/kata/57eaeb9578748ff92a000009/solutions/javascript

```
function sumMix(x){
var newArr = [];
  for(i=0; i< x.length; i++){
     if(typeof(x[i]) === 'string') {
        newArr.push(parseInt(x[i],10));
      } else newArr.push(x[i])
    }
    return newArr.reduce((a,b)=> a+b);
}
```
*https://www.codewars.com/kata/58bf9bd943fadb2a980000a7/solutions/javascript

```
function whoIsPaying(name){
  return name.length > 2 ? [name, name.slice(0,2)] : [name]
}
```

*https://www.codewars.com/kata/59bd5dc270a3b7350c00008b/solutions/javascript

```
function checkTheBucket(bucket){
 let gold = 'gold';
 for (let i = 0; i < bucket.length; i++){
 if (bucket[i] ==='gold'){
 return true;
 }
 }
 return false;
}

```
*https://www.codewars.com/kata/string-of-numbers/train/javascript

```
let strOfNums = (num1, num2) => {
  let str = '';
  let l = num1 < num2 ? num1 :num2;
  let h = l  === num1 ? num2 : num1;
  for (let i = l + 1; i < h  ; i++) {
  str += i;
  }
  return str;
}

```
https://www.codewars.com/kata/jennys-secret-message/train/javascript

```
function greet(name){
  return name !== "Johnny" ? "Hello, " + name + "!" : "Hello, my love!";
  }

```
*https://www.codewars.com/kata/string-repeat/train/javascript

```
function repeatStr (n, s) { 
let str = '';
for (let i = 0; i < n; i++) {
str += s; 
} 
  return str;
}

```
*https://www.codewars.com/kata/sum-without-highest-and-lowest-number/train/javascript
```
function sumArray(array) {
if (array == null) {
  return 0;
} else if (array.length < 2){
  return 0;
} else {
array = array.sort(function(a,b) { return a - b;});
let total = 0;
for(let i = 1; i < array.length - 1; i++) {
total += array[i];
}
  return total;
}
}
```
*https://www.codewars.com/kata/basic-mathematical-operations/train/javascript

```
function basicOp(operation, value1, value2){
  if(operation == '+')return value1 + value2;
  if(operation == '-')return value1 - value2;
  if(operation == '*')return value1 * value2;
  if(operation == '/')return value1 / value2;
}
```
*https://www.codewars.com/kata/to-square-root-or-not-to-square-root/train/javascript
```
function squareOrSquareRoot(array) {
  let proces = [];
for (let i=0; i<array.length; i++){
    let number = array[i];
 if (Math.sqrt(number) == Math.floor(Math.sqrt(number))){
  proces.push(Math.sqrt(number));
 } else {
 proces.push(number*number);
 }
 }
   return proces;
 }
```
* https://www.codewars.com/kata/rock-paper-scissors/train/javascript
```
const rps = (p1, p2) => {
  if (p1 === p2) return 'Draw!';
  if (p1 === 'rock' && p2 === 'scissors') return 'Player 1 won!';
  if (p1 === 'scissors' && p2 === 'paper') return 'Player 1 won!';
  if (p1 === 'paper' && p2 === 'rock') return 'Player 1 won!';
  return 'Player 2 won!';
};
```
*https://www.codewars.com/kata/convert-boolean-values-to-strings-yes-or-no/train/javascript
```
function boolToWord( bool ){
  return bool ? 'Yes' : 'No';
}
```
*https://www.codewars.com/kata/sorted-yes-no-how/train/javascript

```
function isSortedAndHow(array) {
let arr1 = [];
arr1 = arr1.concat(array);
arr1.sort(function(a,b){return b-a});
arr1 = arr1.join('');
let arr = [];
arr = arr.concat(array);
arr.sort(function(a,b){return a-b});
arr = arr.join('');
array = array.join('');
if(arr === array){
  return 'yes, ascending';
} else if(arr1 === array){
  return 'yes, descending';
} else{return 'no'}
}
```
*https://www.codewars.com/kata/keep-hydrated-1/train/javascript

```
function litres(time) {
let lit = time * 0.5; 
lit = lit - lit % 1; 
  return lit;
}
```

*https://www.codewars.com/kata/convert-a-number-to-a-string/train/javascript

```
function numberToString(num) {
  return `${num}`;
}
```

*https://www.codewars.com/kata/welcome/train/javascript
```
function greet(language) {
let database ={
english: "Welcome",
czech: "Vitejte",
danish: "Velkomst",
dutch: "Welkom",
estonian: "Tere tulemast",
finnish: "Tervetuloa",
flemish: "Welgekomen",
french: "Bienvenue",
german: "Willkommen",
irish: "Failte",
italian: "Benvenuto",
latvian: "Gaidits",
lithuanian: "Laukiamas",
polish: "Witamy",
spanish: "Bienvenido",
swedish: "Valkommen",
welsh: "Croeso"
}
  return database[language]||"Welcome";
}
```

*https://www.codewars.com/kata/square-n-sum/train/javascript

```
function squareSum(numbers){
let total = 0;
for(var i = 0; i < numbers.length; i++) {
total += numbers[i] * numbers[i]; 
}
  return total;
}

```

*https://www.codewars.com/kata/do-i-get-a-bonus/train/javascript
```
function bonusTime(salary, bonus) {
if(bonus === true){
  return '£' + salary * 10;
} else {
  return '£' + salary;
}
}
```
*https://www.codewars.com/kata/are-you-playing-banjo/train/javascript

```
function areYouPlayingBanjo(name) {
if (name.toLowerCase().charAt(0) == 'r'){
name = name + ' plays banjo';
} else {
name = name + ' does not play banjo';
}
  return name;
}
```
*https://www.codewars.com/kata/holiday-vi-shark-pontoon/train/javascript

```
function shark(pontoonDistance, sharkDistance, youSpeed, sharkSpeed, dolphin){
  if(dolphin){
    sharkSpeed /= 2;
  }
  return pontoonDistance/youSpeed < sharkDistance/sharkSpeed ? "Alive!" : "Shark Bait!";
}
```
*https://www.codewars.com/kata/returning-strings/train/javascript
```
function greet(name){
 return "Hello, " + name + " how are you doing today?";
 }
```
*https://www.codewars.com/kata/string-ends-with/train/javascript

```
function solution(str, ending){
return str.substr(-ending.length) === ending;
}
```
*https://www.codewars.com/kata/spongebob-meme/train/javascript

```
function spongeMeme(sentence) {
let str = '';
for(let i = 0; i < sentence.length; i++){
if(i % 2 === 0) { str += sentence[i].toUpperCase();
} else { str += sentence[i].toLowerCase();
}
}
  return str;
}
```
*https://www.codewars.com/kata/duck-duck-goose/train/javascript

```
function duckDuckGoose(players, goose) {
  return players[(goose - 1) % players.length].name;
}
```
*https://www.codewars.com/kata/removing-elements/train/javascript

```
function removeEveryOther(arr){
  var newArr=[];
for (var i = 0; i < arr.length; i+=2){
  newArr.push(arr[i]);
  }
return newArr;
}
```
*https://www.codewars.com/kata/transportation-on-vacation/train/javascript
```
function rentalCarCost(d) {
  let price = 40 * d;
  if (d < 3) return price
  return d >= 7 ? price - 50 : price - 20;
  }
```
*https://www.codewars.com/kata/find-the-first-non-consecutive-number/train/javascript

```
function firstNonConsecutive (arr) {
for (let i = 1; i < arr.length; i++) {
if (arr[i] - 1 !== arr[i - 1]) return arr[i];
}
  return null;
}

```
*https://www.codewars.com/kata/volume-of-a-cuboid/train/javascript
```
let Kata;
Kata = (function() {
function Kata() {}
Kata.getVolumeOfCuboid = function(length, width, height) {
    return length * width * height;
}
  return Kata;
})();
```
*https://www.codewars.com/kata/55902c5eaa8069a5b4000083/solutions/javascript

```
function formatMoney(amount){
  return `$${amount.toFixed(2)}`
}
```
*https://www.codewars.com/kata/a-function-within-a-function/train/javascript
```
function always (n) {
  return () => n;
}
```

*https://www.codewars.com/kata/sentence-smash/train/javascript
```
function smash (words) {
  return words.join(' ');
  }
 ```

 *https://www.codewars.com/kata/is-there-a-vowel-in-there/train/javascript
 ```
 function isVow(a){
 let newArr = a.map(function(n) {
 if (n === 97 || n === 101 || n === 105 || n === 111 || n === 117) {
   return String.fromCharCode(n);
 }
   return n;
 });
    return newArr;
 }
 ```
 *https://www.codewars.com/kata/grasshopper-if-slash-else-syntax-debug/train/javascript
 ```
 function checkAlive (health) {
  return (health <= 0) ? false : true
 }
 ```
 *https://www.codewars.com/kata/finish-guess-the-number-game/train/javascripte
 ```
 class Guesser {
 constructor(number, lives) {
 this.number = number
 this.lives = lives
 }
 guess(n) {
 if (!this.lives) throw new Error('You have no more life')
 if (n === this.number) return true
 this.lives--
     return false
 }
 }
 ```
 *https://www.codewars.com/kata/the-if-function/train/javascript
 ```
 function _if(bool, func1, func2) {
   bool ? func1() : func2();
 }
 ```

 *https://www.codewars.com/kata/printing-array-elements-with-comma-delimiters/train/javascript
 ```
 function printArray(array){
   return array.join(',');
   }
  ```
  *https://www.codewars.com/kata/simple-fun-number-1-seats-in-theater/train/javascript
  ```
  function seatsInTheater(nCols, nRows, col, row) {
    return (nCols - col + 1) * (nRows - row);
  }
  ```
  *https://www.codewars.com/kata/training-js-number-4-basic-data-types-array/train/javascript
  ```
  function getLength(arr){
    return arr.length;
  }
  function getFirst(arr){
    return arr[0];
  }
  function getLast(arr){
    return arr[arr.length - 1];
  }
  function pushElement(arr){
  let l =1;
  arr.push(l);
    return arr;
  }
  function popElement(arr){
  arr.pop();
    return arr;
  }

  ```
  *https://www.codewars.com/kata/how-many-stairs-will-suzuki-climb-in-20-years/train/javascript

  ```
  function stairsIn20(s){
    return s.reduce((s, day) => s.concat(day)).reduce((sum, count) => sum + count) * 20;
  }

  ```
  *https://www.codewars.com/kata/lario-and-muigi-pipe-problem/train/javascript
  ```
  function pipeFix(numbers){
  let first = numbers[0];
  let last = numbers[numbers.length-1];
  let arr = [];
  for(let i = first; i <= last; i++) {
  arr.push(i);
  }
    return arr;
  }

  ```
  *https://www.codewars.com/kata/fix-the-bugs-syntax-my-first-kata/train/javascript
  ```
  function myFirstKata(a, b) {
  if (typeof(a) != "number" || typeof(b) != "number") {
      return false;
  } else {
      return a % b + b % a;
  }
  }
  ```
*https://www.codewars.com/kata/leonardo-dicaprio-and-oscars/train/javascript
```
function leo(oscar){
if (oscar === 88) {
   return "Leo finally won the oscar! Leo is happy";
} else if (oscar === 86) {
    return "Not even for Wolf of wallstreet?!";
} else if (oscar < 88) {
    return "When will you give Leo an Oscar?";
} else {
    return "Leo got one already!";
}
}
```
*https://www.codewars.com/kata/how-good-are-you-really/train/javascript

```
function betterThanAverage(classPoints, yourPoints) {
let sum = 0;
for (let i = 0; i < classPoints.length; i++){
sum += classPoints[i];
}
sum = sum/classPoints.length
if(sum > yourPoints) {
   return false
} else {
    return true
}
}
```
*https://www.codewars.com/kata/how-old-will-i-be-in-2099/train/javascript
```
function  calculateAge(birthDate, otherDate) {
let age = otherDate - birthDate;
if(age === 1) {
  return 'You are ' + age + ' year old.';
} else if(age > 1) {
  return 'You are ' + age + ' years old.';
} else if (age < -1) {
   return 'You will be born in ' +  Math.abs(age) + ' years.';
} else if (age === -1) {
   return 'You will be born in ' + Math.abs(age) + ' year.';
} else {
   return 'You were born this very year!';
}
}
```
*https://www.codewars.com/kata/exclamation-marks-series-number-4-remove-all-exclamation-marks-from-sentence-but-ensure-a-exclamation-mark-at-the-end-of-string/train/javascript

```
function remove(s){
let str = "";
for(let i = 0; i < s.length; i++){
if(s[i] === "!"){
} else {
str += s[i];
}
}
  return str + "!";
}

 ```
 *https://www.codewars.com/kata/parse-nice-int-from-char-problem/train/javascript
 ```
 function getAge(inputString){
    return parseInt(inputString);
 }
```
*https://www.codewars.com/kata/vowel-remover/train/javascript
```
function shortcut(string){
let a = string.split('');
for (let i = string.length-1; i >= 0; i--) {
if (a[i] === "a"||
    a[i] === "e"||
    a[i] === "i"||
    a[i] === "o"||
    a[i] === "u") {
a.splice(i,1);
}
};
string = a.join('');
   return string;
}
```
*https://www.codewars.com/kata/sort-and-star/train/javascript
```
function twoSort(s) {
let b = s.sort()[0];
let a = b[0];
for(let i = 1; i < b.length; i++) {
a += "***" + b[i];
  }
  return a;
}
```
*https://www.codewars.com/kata/exclamation-marks-series-number-6-remove-n-exclamation-marks-in-the-sentence-from-left-to-right/train/javascript
```
function remove(s,n){
let array = s.split(""),
let count = 0;
for(let i = 0; i < array.length; i++){
if(array[i] === "!"){
count++;
if(array[i] === '!' && count <= n){
array.splice(i,1);
i--;
}
}
}
  return array.join("");
}
```




