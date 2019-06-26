##Hello

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

*https://www.codewars.com/kata/572b77262bedd351e9000076/solutions/javascript

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

function solution(str){
  return str.split('').reverse().join('');
}

```
*https://www.codewars.com/kata/count-odd-numbers-below-n/train/javascript

```
function oddCount(num){
  var count = 0;
  for(var i=0; i<num; i++){
    if(i % 2 ===1){
      count++;
    }
  }
  return count;
}
================