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


