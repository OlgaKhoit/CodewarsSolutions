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
count = 0;
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
*https://www.codewars.com/kata/pole-vault-starting-marks/train/javascript
```
function startingMark(bodyHeight) {
let a = {x: 1.52, y: 9.45},
 b = {x: 1.83, y: 10.67},
 c = (b.y - a.y) / (b.x - a.x);
    return Math.round((c * bodyHeight + b.y - c * b.x) * 100) / 100;
}
```
*https://www.codewars.com/kata/basic-making-six-toast/train/javascript
```
function sixToast(num) {
  return Math.abs(num-6);
}
```
*https://www.codewars.com/kata/numerical-palindrome-number-5-1/train/javascript
```
function palindrome(num) {
  if(typeof num !== 'number' || num < 0) return "Not valid";
  if(num < 10) return false;
  num = num.toString().split('').sort();
  console.log(num);
  let count = 0;
  for(let i = 0; i < num.length - 1; i){
   if(num[i] === num[i+1]){
     count = count + 2;
     i = i + 2;
   } else i++;
  }
  if(num.length === count || num.length === count +1){
    return true;
  } else return false;
}

```
```
function palindrome(num) {
  if (typeof num !== 'number' || num < 0) return 'Not valid';
  let cnt = 0;
  let str = num.toString().split('').sort();
  if (str.length <= 1) return false;
  for (let i = 0; i < str.length - 1 ; i++) {
   if (str[i] === str[i + 1]) {
     cnt+=2;
     i++;
     }
  }
  return (str.length - cnt) <= 1 ? true : false;
}
```
*https://www.codewars.com/kata/5a523566b3bfa84c2e00010b

```
function minSum(arr) {
const s = arr.sort((a,b) => a-b)
let sum = 0;
for (let i = 0;i < arr.length/2 ;i++){
sum += s[i] * s[s.length-1-i]
}
   return sum
}
```
*https://www.codewars.com/kata/the-office-v-find-a-chair/train/javascript
```
function meeting(x, need){
if(need <= 0) {
  return 'Game On';
}
const taken = [];
for(let[{length: chairs}, people] of x){
let take = Math.min(Math.max(people- chairs, 0), need);
taken.push(take)
need -= take;
if(need <= 0){
  return taken;
}
}
  return 'Not enough!';
}
```
*https://www.codewars.com/kata/convert-to-binary/train/javascript
```
function toBinary(n){
  return Number(n.toString(2));
}
```
*https://www.codewars.com/kata/get-the-mean-of-an-array/train/javascript
```
function getAverage(marks){
 return Math.floor(marks.reduce((acc, cur) => acc + cur) / marks.length);
 }
 ```

 function getAverage(marks){

   let total = 0;
   for(let i = 0; i < marks.length; i++){
     total += marks[i];
   }
   return Math.floor(total / marks.length);
 }
 ```
 *https://www.codewars.com/kata/55a2d7ebe362935a210000b2/discuss
 ```
 class SmallestIntegerFinder {
 findSmallestInt(args) {
 let curretMin = args[0];
 for( let i = 1; i <= args.length; i++) {
 if(args[i] < curretMin) curretMin = args[i];
 }
    return curretMin;
 }
 }
 ```
 *https://www.codewars.com/kata/number-1-matrices-making-an-alternating-sum/train/javascript
 ```
 function scoreMatrix(matrix) {
 let score = 0;
 matrix.map((e,j) => {
 if (j%2 === 0){
    return e.map((v,i) => i % 2 === 0 ? score += v : score -= v)
 } else {
     return e.map((v,i) => i % 2 !== 0 ? score += v : score -= v)
 }
 })
     return score;
 }
 ```
 *https://www.codewars.com/kata/count-all-the-sheep-on-farm-in-the-heights-of-new-zealand/train/javascript
 ```
 function lostSheep(friday,saturday,total){
 let sum = 0;
 for (let i in friday){
 sum += friday[i];
 }
 for (let i in saturday){
 sum += saturday[i];
 }
   return total - sum;
 }
 ```
 *https://www.codewars.com/kata/return-the-first-m-multiples-of-n/train/javascript
 ```
 function multiples(m, n){
 const arr = [];
 for (let i = 1;i <= m;i++){
 arr.push(n*i)
 }
   return arr
 }
 ```
*https://www.codewars.com/kata/simple-simple-simple-string-expansion/train/javascript
```
function stringExpansion(str) {
let res = '';
let key = 1;
for(let i = 0; i < str.length; i++){
if (str[i] == +str[i]){
key = +str[i];
}else{
res += str[i].repeat(key);
}
}
  return res;
}
```
*https://www.codewars.com/kata/find-the-missing-element-between-two-arrays/train/javascript
```
function findMissing(arr1, arr2) {
let a1 = arr1.sort((a,b) => a-b);
let a2 = arr2.sort((a,b) => a-b);
for(let i = 0; i < a1.length; i++) {
if( a1[i] !== a2[i]) return a1[i]
 }
}
```
*https://www.codewars.com/kata/sum2total/train/javascript
```
function total(arr) {
if (arr.length == 1) return arr[0]
let s = []
for (let i = 0; i < arr.length - 1; i++) {
s.push(arr[i] + arr[i + 1])
}
  return total(s)
}
```
*https://www.codewars.com/kata/splicing/train/javascript
```
Array.prototype.removeValue = function(thing) {
if (this.indexOf(thing) == -1) return false;
let i ;
while ((i = this.indexOf(thing)) > -1) this.splice(i,1);
  return this;
}
```
*https://www.codewars.com/kata/a-gift-well-spent/train/javascript
```
let x = 20;
let arr = [10,34,10];
var buy = function(x, arr){
let res = [];
for (let i = 0; i < arr.length - 1; i++){
for (let q = i +1; q < arr.length; q++){
if(arr[i] +arr[q] === x) {
  return [i, q];
}
}
}
 return null;
};
```
*https://www.codewars.com/kata/maximum-triplet-sum-array-series-number-7/train/javascript
```
function maxTriSum(numbers){
  let sortedArr = Array.from(new Set(numbers)).sort((a,b) => b-a);
  return sortedArr[0] + sortedArr[1] + sortedArr[2];
}
```
```
function maxTriSum(numbers){
     let set = new Set(numbers);
     set = [...set].sort((a, b) => b - a);
     return set[0] + set[1] + set[2];
   }
 ```
 *https://www.codewars.com/kata/array-array-array/train/javascript
 ```
 function explode(x){
 let res = [];
 let score = 0;
 for(let i = 0; i < x.length; i++) {
 if(+x[i]){
 score +=x[i];
 }
 }
 while (score > 0) {
 score--;
 res.push(x);
 }
 return res;
 }
 ```
 *https://www.codewars.com/kata/sort-the-odd/train/javascript
 ```
 function sortArray(array) {
   let odd = array.filter(a => a % 2 !== 0).sort((a,b) => a - b);
   let res = array.map(a => a % 2 !== 0 ? odd.shift() : a);
   return res;
 }

```
*https://www.codewars.com/kata/numerical-palindrome-number-2/train/javascript
```
function palindrome(num){
 if(typeof num !== 'number' || num < 0 || num % 1 != 0){
  return "Not valid";
 }
   if(num < 10){
    return false;
   }
      let str = num + '';
        for(let i = 0; i < str.length; i++){
          if(str[i] === str[i + 1]  || str[i] === str[i + 2]) return true;
     }
        return false;
   }
   ````
 *https://www.codewars.com/kata/reverseit-1/train/javascript
 ```
function reverseIt(data){
  if (typeof data=== 'string') return data.split('').reverse().join('');
  if (typeof data === 'number') return data.toString().split('').reverse().join('')*1;
  return data
 }
 ```
 *https://www.codewars.com/kata/shorter-concat-reverse-longer/train/javascript
 ```
 function shorter_reverse_longer(a,b){
   if (a.length>b.length){return `${b}${a.split('').reverse().join('')}${b}`}
   if (a.length<b.length){return `${a}${b.split('').reverse().join('')}${a}`}
   return `${b}${a.split('').reverse().join('')}${b}`
 }
 ```
 *https://www.codewars.com/kata/training-js-number-1-create-your-first-js-function-and-print-helloworld/discuss/javascript
 ```
 function squares(x, n) {
 if (n <= 0) return [];
 let arr = [x];
 for (let i=0;i<n-1;i++)
 {
 arr.push(Math.pow(arr[i],2))
 }
 return arr;
 }
 ```
 *https://www.codewars.com/kata/training-js-number-1-create-your-first-js-function-and-print-helloworld/train/javascript
 ```
 function helloWorld(){
    let str = "Hello World!";
     console.log("Hello World!");
     }
  *https://www.codewars.com/kata/nth-floyd-line/train/javascript
  ```
  function nthFloyd(n){
    return Math.ceil((Math.sqrt(8 * n + 1) - 1) / 2)
  }
  ```
  *https://www.codewars.com/kata/string-average/train/javascript
  ```
  function averageString(str) {
    let num = 'zero,one,two,three,four,five,six,seven,eight,nine'.split(',');
    let arr = str.split(/\s/);
    let all = arr.map(s=>num.indexOf(s));
    let avg = all.reduce((a,b)=>a+b,0)/arr.length;
    let na = 'n/a';
    return all.some(n=>n<0) ? na : num[Math.floor(avg)] || na;
  }
  ```
  *https://www.codewars.com/kata/numerical-palindrome-number-5-1/train/javascript
  ```
  function palindrome(num) {
  if(typeof num !== 'number' || num < 0) return "Not valid";
  if( num < 10)  return false;
  num = num.toString().split('').sort();
  console.log(num);
  let count = 0;
  for(let i = 0; i < num.length - 1; i){
  if(num[i] === num[i+1]){
  count = count + 2;
  i = i + 2;
  } else i++;
  }
  if(num.length === count || num.length === count + 1){
  return true;
  }else return false;
  }

```
*https://www.codewars.com/kata/calculate-average/train/javascript
```
function find_average(array) {
 let sum = array.reduce((a, b) => a + b, 0);
  return sum/array.length;
}

```
*https://www.codewars.com/kata/5977618080ef220766000022/solutions/javascript
```
function usdcny(usd) {
  return `${(usd*6.75).toFixed(2)} Chinese Yuan`
  }
  ```
  *https://www.codewars.com/kata/short-long-short/train/javascript
  ```
  function solution(a, b){
    return a.length > b.length ? b + a + b : a + b + a;
  }
  ```
  *https://www.codewars.com/kata/return-to-sanity/train/javascript
  ```
  function mystery() {
    return {sanity: 'Hello'};
  }
  ```
  *https://www.codewars.com/kata/power/train/javascript
  ```
  function numberToPower(number, power){
    return (!power) ? 1 : (power > 1) ? number * numberToPower(number, power-1) : number;
    }
    ```
    *https://www.codewars.com/kata/grasshopper-terminal-game-combat-function-1/train/javascript
    ```
    function combat(health, damage) {
      return (health < damage) ? 0 : (health - damage);
    }
    ```
    *https://www.codewars.com/kata/grasshopper-bug-squashing/train/javascript
    ```
    var health = 100
    var position = 0
    var coins = 0

    function main () {
      rollDice()
      move()
      combat()
      getCoins()
      buyHealth()
      printStatus()
    }
    ```
    *https://www.codewars.com/kata/maxpossiblescore/train/javascript
    ```
    function maxPossibleScore(obj, arr) {
    let t = 0;
    arr = arr.map(a => a.toString());
    for(let x in obj) {
    t += obj[x] * (arr.includes(x) ? 2: 1);
    }
      return t;
    }
    ```
    *https://www.codewars.com/kata/getnames/train/javascript
    ```
    function getNames(data){
      return data.map(a => a.name);
      }
      ```
 *https://www.codewars.com/kata/esrever/train/javascript
  ```
  let reverse = function(array) {
  let temp = [];
  for(let i = array.length-1; i >= 0; i--) {
  temp.push(array[i]);
  }
  return temp;
  }
  ```
  *https://www.codewars.com/kata/you-got-change/train/javascript
  ```
  function giveChange(num) {
  let arr = [1, 5, 10, 20, 50, 100];
  for(let i = arr.length - 1; i >= 0; i--) {
  let temp = arr[i] * ~~(num/arr[i]);
  arr[i] = ~~(num/arr[i]);
  num -= temp;
  }
    return arr;
  }
  ```
  *https://www.codewars.com/kata/working-with-arrays-ii-and-why-your-code-fails-in-some-katas
  ```
  function removeNthElement(arr, n) {
  let arrCopy = arr.slice();
  arrCopy.splice(n, 1);
    return arrCopy;
  }
  ```
  *https://www.codewars.com/kata/whos-online/train/javascript
  ```
  const whosOnline = (friends) => {
  let obj = {};
  friends.forEach(friend=>{
  if(friend.status !== 'offline' && friend.lastActivity > 10){
  obj['away'] ? '' : obj['away'] = [];
  obj['away'].push(friend.username);
  }else {
  obj[friend.status] ? '' : obj[friend.status] = [];
   obj[friend.status].push(friend.username);
  }
  });
   return obj;
  }
  ```
  *https://www.codewars.com/kata/whats-my-golf-score/train/javascript
  ```
  function golfScoreCalculator(p, s){
   let r = 0;
   for (let i = 0; i < p.length; ++i)
   r += s[i] - p[i];
     return r;
  }
  ```
  *https://www.codewars.com/kata/57f222ce69e09c3630000212
  ```
  const well = x => {
    const good = x.filter(idea => idea === 'good').length
  if (good > 2) return 'I smell a series!'
    if (good > 0) return 'Publish!'
    return 'Fail!'
  }
  ```
  *https://www.codewars.com/kata/watching-your-pennies
  ```
  function manageMoney(cash,expenses,rate) {
    rate = rate/100
    for (let i = 0; i <= 11; i++) {
      cash = ((cash * rate) + cash) - expenses;
      if(cash <= 0) return 'You ran out of money after ' + i + ' months';
    }
    return 'You still have $' + cash.toFixed(2);
  }
  ```
  *https://www.codewars.com/kata/vasya-in-his-free-time/solutions/javascript
  ```
  function CalculateString(n, nums) {
  nums = nums.replace(/01|10/g, '');
  let l = nums.length;
    return l === n ? n : CalculateString(l, nums);
  }
  ````
  *https://www.codewars.com/kata/unflatten-a-list-easy
  ```
  const unflatten = flatArray => {
  let arr = [];
  while (flatArray.length)
  arr.push(flatArray[0] < 3 ? flatArray.shift() : flatArray.splice(0, flatArray[0]));
    return arr;
  };
  ```
  *https://www.codewars.com/kata/ultimate-array-reverser
  ```
  const ultimateReverse = s => {
    const arr = [...s.join('')].reverse();
    return s.map(word => arr.splice(0, word.length).join(''));
  };
  ```
  *https://www.codewars.com/kata/turn-any-word-into-a-beef-taco/train/python
  ```
  function tacofy(word) {
  let arr = ["shell"], obj = {
  "a" : "beef",
  "e" : "beef",
  "i" : "beef",
  "o" : "beef",
  "u" : "beef",
  "t" : "tomato",
  "g" : "guacamole",
  "c" : "cheese",
  "l" : "lettuce",
  "s" : "salsa"
  }
  word = word.toLowerCase().split("").map(a => obj.hasOwnProperty(a) ? obj[a] : null);
      return arr.concat(word).concat("shell").filter(a => a);
  }
  ```
  *https://www.codewars.com/kata/5b190aa7803388ec97000054
  ```
  function tram(stops, descending, onboarding){
  let res = 0, passengers = 0;
  for(let i = 0; i < stops; i++)
  res = Math.max(res, passengers += onboarding[i] - descending[i]);
    return res;
  }
  ```
  *https://www.codewars.com/kata/traffic-police-i/train/javascript
  ```
  var speedError = function(est, act, readings) {
  if ( readings[0][0] < 1 || readings[1][0] < 1 ) throw Error('Invalid reading');
  if ( readings[0][1] > readings[1][1] ) readings.reverse();
  let d1 = readings[0][0], d2 = readings[1][0], t = readings[1][1] - readings[0][1];
  function speed(c){
  let a = Math.sqrt(Math.abs(Math.pow(d1,2) - Math.pow(c,2))),
  b = Math.sqrt(Math.abs(Math.pow(d2,2) - Math.pow(c,2))),
  speed = ((a - b) / t) * 3.6;
     return Math.abs(Math.round( speed * 1e1 ) / 1e1);
  }
    return [speed(est), speed(act)];
  }
  ```
 *https://www.codewars.com/kata/thinking-and-testing-number-37-convert-number/train/javascript
 ```
 function testIt(f){
 let num = Math.round(+((f-32)/9*5)*100)/100
   return (num >= -273.15) ? num : "Invalid input!";
 }
 ```
 *https://www.codewars.com/kata/thinking-and-testing-retention-and-discard/train/javascript
 ```
 function testit(n) {
 let arr = [];
 for (let i = 1; i <= n; i += 2)
 if (n % i === 0) arr.push(i);
   return arr;
 }
 ```
 *https://www.codewars.com/kata/thinking-and-testing-a-and-b/train/javascript
 ```
 function testit(a,b){
   return a | b;
 }
 ```
 *https://www.codewars.com/kata/thinkful-string-drills-repeater/train/javascript
 ```
 const repeater = (string, n) => string.repeat(n);
 ```
 *https://www.codewars.com/kata/thinkful-list-and-loop-drills-inverse-slicer/train/javascript
 ```
function inverseSlice(items, a, b) {
  return items.filter(function(x,i) {
    return (i < a || i >= b)
    }
  )
}
```
*https://www.codewars.com/kata/the-pony-express/train/javascript
```

function riders(stations) {
 let n = 1, x = 0;
 for(let s of stations)
 if(x + s > 100)
 [n, x] =  [n+1, s];
 else x += s;
    return n;
}
```
*https://www.codewars.com/kata/the-poet-and-the-pendulum/train/javascript
```
function pendulum(a) {
let list = [], arr = [];
a.sort((b, c) => b - c).forEach((e, i) => (i % 2 ? arr : list).push(e));
  return list.reverse().concat(arr);
}
```
*https://www.codewars.com/kata/the-office-ii-boredom-score/train/javascript
```
const boredomScore = {
  accounts: 1,
  finance: 2,
  canteen: 10,
  regulation: 3,
  trading: 6,
  change: 6,
  IS: 8,
  retail: 5,
  cleaning: 4,
  'pissing about': 25,
}
let boredom = staff => {
let teamScore = Object.values(staff).reduce((total, department) => total + boredomScore[department], 0)
if (teamScore <= 80) return 'kill me now'
if (teamScore >= 100) return 'party time!!'
  return 'i can handle this'
}
```
*https://www.codewars.com/kata/the-ladies-of-eniac/train/javascript
```
function radLadies(name){
  return name.split('').map(function(symbol){
 let x;
if (isNaN(symbol) || symbol == ' ') x = symbol;
    switch (x) {
      case '%':
      case '$':
      case '&':
      case '/':
      case '£':
      case '?':
      case '@':
      return '';
      default:
      return x;
}
}).join('').toUpperCase();
}
```
*https://www.codewars.com/kata/tail-swap/train/javascript
```
function tailSwap(arr) {
let [a, b] = arr.map(s => s.split(':'));
  return [a[0] + ':' + b[1], b[0] + ':' + a[1]];
}
```
*https://www.codewars.com/kata/tabs-to-spaces
```
*https://www.codewars.com/kata/tiy-fizzbuzz/train/javascript
```
function tiyFizzBuzz(s){
let str='';
 for (let i=0; i<s.length; ++i){
 if (s[i]>='A' && s[i]<='Z'){
 if (s[i]=='A' || s[i]=='E' || s[i]=='I' || s[i]=='O' || s[i]=='U')
 str+='Iron Yard';
 else
 str+='Iron';
 }
 else
 {
 if (s[i]=='a' || s[i]=='e' || s[i]=='i' || s[i]=='o' || s[i]=='u')
 str+='Yard';
 else
 str+=s[i];
 }
 }
  return str;
}
```
*https://www.codewars.com/kata/switcheroo/train/javascript
```
function switcheroo(x){
  return x.split('').map(
  c => { if(c =='a') return c ='b'; if (c =='b') return c ='a'; return c;
}).join('');
}
```
*https://www.codewars.com/kata/sweet-dreams-are-made-of-cheese/train/javascript
```
function payCheese(arr) {
let res = 0;
for (let i = 0; i < arr.length; i++) {
    res += arr[i];
}
  return `£${Math.ceil(res/100)*8.75*4}`;
}
```
*https://www.codewars.com/kata/swap-the-head-and-the-tail/train/javascript
```
function swapHeadAndTail(arr) {
let num = arr.length/2;
  return arr.slice(Math.round(num)|0).concat(num == (num|0) ? [] : arr[num|0], arr.slice(0,num));
}
```
*https://www.codewars.com/kata/sushi-go-round-beginners/train/javascript
```
function totalBill(str) {
    return (str.replace(/\s/g, "").length * 2) - ~~(str.replace(/\s/g, "").length/5) * 2;
}
```
*https://www.codewars.com/kata/two-sum/train/javascript
```
function twoSum(numbers, target) {
for (let i = 0; i < numbers.length-1; i++)
for (let j = i+1; j < numbers.length; j++)
if (numbers[i] + numbers[j] === target) return [i, j];
}
```
*https://www.codewars.com/kata/sums-of-parts/train/javascript
```
function partsSums(ls) {
let arr = [0];
ls.reverse().forEach(v => arr.push(arr[arr.length-1] + v));
  return arr.reverse();
}
```
*https://www.codewars.com/kata/sum-number-1/train/javascript
```
function sum(num) {
let a = (num) ? n : 0,
f = function sum(b) {
if(isNaN(b)) return a;
a += b;
  return sum;
}
  return (num) ? f : 0;
}
```
*https://www.codewars.com/kata/1st-day-of-month-that-are-sunday-in-a-year-range/train/javascript
```
function getTotalSundays (yearInit, yearEnd) {
let num = 0;
for (let year = yearInit; year <= (yearEnd || yearInit); year++) {
for (let month = 0; month < 12; month++)
if ((new Date(year, month, 1)).getDay() === 0)
num++;
}
  return num;
}
```
*https://www.codewars.com/kata/empty-that-array/train/javascript
```
function empty(array) {
array.length = 0;
  return array;
}
```
*https://www.codewars.com/kata/even-numbers-in-an-array/train/javascript
```
function evenNumbers(array, number) {
  return array.filter(a => a % 2 === 0).slice(-number);
}
```
*https://www.codewars.com/kata/selective-array-reversing/train/javascript
```
function selReverse(array, length) {
let temp = [];
if(length > array.length) { return array.reverse(); }
if(!length) { return array; }
while(array.length) {
temp = temp.concat(array.splice(0, length).reverse())
}
    return temp;
}
```
*https://www.codewars.com/kata/equal-sides-of-an-array/train/javascript
```
let findEvenIndex = function(arr) {
let r = arr.reduce((a,b) => a + b, 0), left = 0;
for(let i = 0; i < arr.length; i++) {
if(i > 0) left += arr[i-1];
r -= arr[i];
if(left === r) return i;
}
  return -1;
}
```



