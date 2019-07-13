1) https://www.codewars.com/kata/convert-boolean-values-to-strings-yes-or-no/solutions/javascript
```javascript
function boolToWord( bool ){
  return bool ? 'Yes':'No';
}
```



2) https://www.codewars.com/kata/57f36495c0bb25ecf50000e7
```javascript
function findSum(n) {
  let sum = 0;
   for(let i = 0; i <= n; i++){
     if(i % 3 === 0 || i % 5 === 0){
       sum = sum + i;
     }
   }

  return sum;
}
```

3) https://www.codewars.com/kata/525f50e3b73515a6db000b83
```javascript
function createPhoneNumber(numbers){
  numbers.splice(0, 0, '(');
  numbers.splice(4, 0, ') ');
  numbers.splice(8, 0, '-');
  return numbers.join('');
}
```

4) https://www.codewars.com/kata/5594463eaf1701909c0000d4
```javascript
function arraySum(arr) {
  let sum = 0;
    for(let i = 0; i < arr.length; i++){
      if(typeof arr[i] === 'number'){
        sum = sum + arr[i];
      }else if(Array.isArray(arr[i])){
        return sum + arraySum(arr[i]);
      }
    }
    return sum;
}
```


5) https://www.codewars.com/kata/586beb5ba44cfc44ed0006c3
```javascript
function sumEvenNumbers(input) {
  let sum = 0;
  for(let i = 0; i < input.length; i++){
    if(input[i] % 2 === 0){
      sum = sum + input[i];
   }
  }
  return sum;
}
```


6) https://www.codewars.com/kata/57a84137cf1fa5f9f80000d6
```javascript
function sumR(x) {
  let sum = 0;
  for(let i = 0; i < x.length; i++){
    sum = sum + x[i];
  }
  return sum;
}
```


7) https://www.codewars.com/kata/52af7bf41f5a1291a6000025
```javascript
function timeForMilkAndCookies(date){
  return date.getMonth() === 11 && date.getDate() === 24;
}
```


8) https://www.codewars.com/kata/5a2be17aee1aaefe2a000151
```javascript
function arrayPlusArray(arr1, arr2) {
  let sum1 = 0;
  let sum2 = 0;
   for(let i = 0; i < arr1.length; i++){
   sum1 = sum1 + arr1[i];
   }
   for(let j= 0; j < arr2.length; j++){
   sum2 = sum2 + arr2[j];
   }
   return sum1 + sum2;

}
```


9) https://www.codewars.com/kata/5545f109004975ea66000086
```javascript
function isDivisible(n, x, y) {
if(n % x ===0 && n % y === 0 ) return true;
else return false;
}
```


10) https://www.codewars.com/kata/515e271a311df0350d00000f
```javascript
function squareSum(numbers){
  let sum = 0;
    for(let i = 0; i < numbers.length; i++){
      sum = sum + numbers[i]**2;
    }
  return sum;
}
```

11) https://www.codewars.com/kata/53da6d8d112bd1a0dc00008b
```javascript
function reverseList(list) {
arr = [];
for(let i = list.length - 1; i >= 0; i--){
arr.push(list[i]);
}
return arr;
}
```

12) https://www.codewars.com/kata/5168bb5dfe9a00b126000018
```javascript
function solution(str){
  let str1 = '';
    for(let i = str.length - 1; i >= 0; i--){
      str1 = str1 + str[i];
    }
    return str1;
}
```

13) https://www.codewars.com/kata/57a0e5c372292dd76d000d7e
```javascript
function repeatStr (n, s) {
  return s.repeat(n);
}
```

14) https://www.codewars.com/kata/57eae20f5500ad98e50002c5
```javascript
function noSpace(x){
return x.split(' ').join('');
}
```

15) https://www.codewars.com/kata/51f2d1cafc9c0f745c00037d
```javascript
function solution(str, ending){
  return str.slice(str.length - ending.length) === ending;
}
```

16) https://www.codewars.com/kata/58ba6fece3614ba7c200017f
```javascript
function palindrome(num) {
  let str = '';
   if(typeof num !== 'number' || num < 0){
   return 'Not valid';
   }
    str = num + '';

     for(let i = 0; i < Math.floor(str.length / 2); i++){
      if(str [i] !== str[str.length - i - 1]){
        return false;
      }
  }
  return true;
}
```

17) https://www.codewars.com/kata/5aca48db188ab3558e0030fa
```javascript
function calcType(a, b, res) {
  if(a + b === res){
   return 'addition';
  }
   if(a - b === res){
   return 'subtraction';
  }
   if(a * b === res){
   return 'multiplication';
   }
    if(a / b === res){
   return 'division';
}
}
```

18) https://www.codewars.com/kata/58712dfa5c538b6fc7000569
```javascript
function countRedBeads(n) {

 if(n < 2){
 return 0;
}
 return (n - 1) * 2;
}
```

19) https://www.codewars.com/kata/555bfd6f9f9f52680f0000c5
```javascript
function reverseNumber(n){
 if(n >= 0){
 let arr = n.toString().split('').reverse();
  return +(arr.join(''));
   } else {
   n = n * (-1);
   let arr = n.toString().split('').reverse();
  return (-1) * (+arr.join(''));
  }
}
```

20) https://www.codewars.com/kata/514b92a657cdc65150000006
```javascript
function solution(number){
  let sum = 0;

  for(let i = 0; i < number; i++) {
    if(i % 3 === 0 || i % 5 === 0) {
      sum = sum + i;
    }
  }

  return sum;
}
```

21) https://www.codewars.com/kata/562e8a47ded765e36a00006b
```javascript
function reverseString(str) {

  return str.split('').reverse().join('');

}
```

22) https://www.codewars.com/kata/50ee6b0bdeab583673000025
```javascript
var a = "code";
var b = "wa.rs";
var name = a + b;
```

23) https://www.codewars.com/kata/5a2b703dc5e2845c0900005a
```javascript
function isDivideBy(number, a, b) {
  return number % a === 0 && number % b === 0 ? true : false;
}
```

24) https://www.codewars.com/kata/55a70521798b14d4750000a4
```javascript
function greet(name){
  return `Hello, ${name} how are you doing today?`;
}
```

25) https://www.codewars.com/kata/56f6ad906b88de513f000d96
```javascript
function bonusTime(salary, bonus) {
return bonus ? ('£' + salary * 10): '£' + salary;
}
```

26) https://www.codewars.com/kata/58bf9bd943fadb2a980000a7
```javascript
function whoIsPaying(name){
  let arr = [name];
  if(name.length > 2){
  let str = name.substring(0, 2);
  arr.push(str);
  }
  return arr;
}
```

27) https://www.codewars.com/kata/5701e43f86306a615c001868
```javascript
function getIssuer(number) {
console.log(number);
let str = number.toString();
  if((str.slice(0, 2) === '34' || str.slice(0, 2) === '37') && str.length === 15) return 'AMEX';
  else if((str.slice(0, 2) === '51' || str.slice(0, 2) === '52' || str.slice(0, 2) === '53' || str.slice(0, 2) === '54' || str.slice(0, 2) === '55') && str.length === 16) return 'Mastercard';
  else if(str.slice(0, 4) === '6011' && str.length === 16) return 'Discover';
  else if(str.slice(0, 1) === '4' && (str.length === 13 || str.length === 16)) return 'VISA';
  else return 'Unknown';
}
```

28) https://www.codewars.com/kata/57547f9182655569ab0008c4
```javascript
function replicate(times, number) {
  let arrr = [];
  return rep(times, number, arrr);

}

function rep (times, number, arr){
  if (times <= 0) return arr;
  arr.push(number);
  return rep(times - 1, number, arr);
}
```

29) https://www.codewars.com/kata/5558cc216a7a231ac9000022
```javascript
function duplicates(arr) {
  let arr1 = [];
  arrSort = arr.slice().sort();
  console.log(arrSort);
  for(i = 0; i < arr.length - 1; i++){
    if(arrSort[i] === arrSort[i + 1]){
      if (!arr1.includes(arrSort[i])) {
        arr1.push(arrSort[i]);
      }
    }
  }
  return arr1;
}
```

30) https://www.codewars.com/kata/544a54fd18b8e06d240005c0
```javascript
function min(arr, toReturn) {
  let min = arr[0];
  let minIndex = 0;
    for(i = 0; i < arr.length; i++){
      if(arr[i] < min){
        min = arr[i];
        minIndex = i;
      }
    }
    return toReturn === 'value' ? min: minIndex;
}
```

31)  https://www.codewars.com/kata/576b93db1129fcf2200001e6
```javascript
function sumArray(arr) {
console.log(arr);
  if(arr === null){
    return 0;
  }
  if(arr[0] === 0 || arr.length === 0) {return 0;}
  if(arr.length === 1) {return 0;}
  return eval(arr.join('+')) - Math.min.apply(null, arr) - Math.max.apply(null, arr);
}
```

32) https://www.codewars.com/kata/57073869924f34185100036d
```javascript
unction randomCase(x) {
let xNew = '';
  for (let i = 0; i < x.length; i++){
   if(Math.round(Math.random()) > 0){
     xNew += x[i].toUpperCase();
   } else{
     xNew += x[i].toLowerCase();
    }
  }
  return xNew;
}
```

33) https://www.codewars.com/kata/59d9ff9f7905dfeed50000b0
```javascript
function solve(arr){
 let alp = 'ABCDEFGHIJKLMNOPQRSTUVWXYZ';
 let arrNew = [];
  for(let i = 0; i < arr.length; i++){
   let count = 0;
   for(let j = 0; j < arr[i].length; j++){
     if(j === alp.indexOf(arr[i][j].toUpperCase()) ){
      count++;
     }
   }
   arrNew.push(count);
  }
  return arrNew;
}
```

34) https://www.codewars.com/kata/59325dc15dbb44b2440000af
```javascript
function isAlt(word) {
  let vowels = ['a', 'e', 'i', 'o', 'u'];
  let start;
  let consonants = ['b', 'c', 'd', 'f', 'g', 'h', 'j', 'k', 'l', 'm', 'n', 'p', 'q', 'r', 's', 't', 'v', 'w', 'x', 'y', 'z']
  if(vowels.includes(word[0])) {
    start = 0;
  } else start = 1;
  for (i = start; i < word.length; i = i + 2) {
    if (!(vowels.includes(word[i]))) {return false;}
  }
  if (start === 1) {start = 0;}
  else {start = 1;}
  for (i = start; i < word.length; i = i + 2){
    if (!(consonants.includes(word[i]))) {return false;}
    }
  return true;

} ```

35) https://www.codewars.com/kata/51e704f2d8dbace389000279
```javascript
function arraysSimilar(arr1, arr2) {
  if(arr1.length !== arr2.length) return false;
  arr1.sort();
  arr2.sort();
  for(let i = 0; i < arr1.length; i++){
    if( arr1[i] !== arr2[i]) return false;

  }
  return true;
}
```

36) https://www.codewars.com/kata/5966847f4025872c7d00015b
```javascript
function averageString(str) {
 let arr = ['zero', 'one', 'two', 'three', 'four', 'five', 'six', 'seven', 'eight', 'nine'];
 let arrStr = str.split(' ');
 let sum = 0;
   for (let i = 0; i < arrStr.length; i++) {
     sum += arr.indexOf(arrStr[i]);
     if (arrStr[i] === '' || arr.includes(arrStr[i]) === false) return 'n/a'
    }
  let avg = Math.floor(sum/arrStr.length);

    return arr[avg]
}
```

37) https://www.codewars.com/kata/5982619d2671576e90000017
```javascript
function spongeMeme(sentence) {
  let str = '';
  for(let i = 0; i < sentence.length; i++ ){
    if(i % 2 === 0){ sentence[i].toUpperCase()
      str = str + sentence[i].toUpperCase();
    } else {
      str = str + sentence[i].toLowerCase();

    }
  }
  return str;
}
```

38) https://www.codewars.com/kata/57a5b0dfcf1fa526bb000118
```javascript
function distinct(a) {
  return [...new Set(a)];
}
```

39) https://www.codewars.com/kata/56c22cdbe0c0f7cae2001789
```javascript
const avg = a => a.reduce((a,b)=> a + b) / a.length;
```


40) https://www.codewars.com/kata/52774a314c2333f0a7000688
```javascript
function validParentheses(par){
  const arr = [];
  const open = ['(', '{', '['];
  const close = [')', '}', ']'];
  for (let i = 0; i < par.length; i++){
  if(open.includes(par[i])) {
  arr.push(par[i]);
  } else {
  if(close.indexOf(par[i]) === open.indexOf(arr[arr.length - 1])) {
    arr.pop();
  } else {
  return false;
  }
  }
  }
  return arr.length === 0;
}
```

41) https://www.codewars.com/kata/58e26b5d92d04c7a4f00020a
```javascript
function palindrome(num) {
  if(typeof num !== 'number' || num < 0) return 'Not valid';
  if(num < 10) return false;
  num = num.toString().split('').sort();
  let cnt = 0;
  for(let i = 0; i < num.length - 1; i){
    if(num[i] === num[i + 1]){
    cnt = cnt + 2;
    i = i + 2;
    }else i++;
  }

  if(num.length === cnt || num.length === cnt + 1){
  return true;
  }else return false;
  }
  ```

  42) https://www.codewars.com/kata/5a523566b3bfa84c2e00010b
  ```javascript
  function minSum(arr) {
    let count = 0;
    arr.sort((a,b) => b - a);
    for(let i = 0; i < arr.length / 2; i++){
    count = count + arr[i] * arr[arr.length - 1 - i]
    }
    return count;
  }
  ```

  43) https://www.codewars.com/kata/5ae326342f8cbc72220000d2
  ```javascript
  function stringExpansion(str) {
    let res = '';
    let rep = 1;
    if (str === '') return res;
    for(let i = 0; i < str.length - 1; i++){
      if(+str[i] == str[i] && +str[i + 1] != str[i + 1]) {
        rep = +str[i];
      }
      if (+str[i] != str[i]){
        res = res + str[i].repeat(rep);
        }
    }
    if (+str[str.length - 1] != str[str.length - 1]) {
      res = res + str[str.length - 1].repeat(rep);
    }
    return res;
  }
  ```

  44) https://www.codewars.com/kata/57a5015d72292ddeb8000b31
  ```javascript
  function isPalindrome(line) {
  console.log(line);
  line = line + '';
  for(let i = 0; i < line.length / 2; i++){
    if(line[i] !== line[line.length - 1 - i]){
      return false;
    }
  }
    return true;
  }
  ```

  45)  https://www.codewars.com/kata/57a2013acf1fa5bfc4000921
  ```javascript
  function find_average(a) {
    let sum = 0;
    for(let i = 0; i < a.length; i++){
      sum = sum + a[i];
    }
    return sum / a.length;
  }
  ```

  46) https://www.codewars.com/kata/580755730b5a77650500010c
  ```javascript
  function sortMyString(S) {
    let str1 = '';
    for(let i = 0; i < S.length; i = i + 2) {
      str1 = str1 + S[i];
    }
    let str2 = '';
    for(let j = 1; j < S.length; j = j + 2){
    str2 = str2 + S[j];
    }
    let newS = 0;
    newS = str1 + ' ' + str2;
    return newS;
  }
  ```

  47) https://www.codewars.com/kata/56069d0c4af7f633910000d3
  ```javascript
  function search(budget, prices) {
  return prices.filter((el) => el <= budget).sort((a,b) => a-b).join();

  }
  ```

  48) https://www.codewars.com/kata/5899642f6e1b25935d000161
  ```javascript
function mergeArrays(arr1, arr2) {
let newArr = [];
for(let i = 0; i < arr1.length; i++){
  if(! newArr.includes(arr1[i]))
  newArr.push(arr1[i]);
}
for(let i = 0; i < arr2.length; i++){
  if(! newArr.includes(arr2[i]))
  newArr.push(arr2[i]);
}
return newArr.sort((a,b) => a-b);

}
```

49) https://www.codewars.com/kata/56069d0c4af7f633910000d3
```javascript
function search(budget, prices) {
return prices.filter((el) => el <= budget).sort((a,b) => a-b).join();

}
```

50) https://www.codewars.com/kata/580755730b5a77650500010c
```javascript
function sortMyString(S) {
  let str1 = '';
  for(let i = 0; i < S.length; i = i + 2) {
    str1 = str1 + S[i];
  }
  let str2 = '';
  for(let j = 1; j < S.length; j = j + 2){
  str2 = str2 + S[j];
  }
  let newS = 0;
  newS = str1 + ' ' + str2;
  return newS;
}
```

51) https://www.codewars.com/kata/5a5915b8d39ec5aa18000030
```javascript
function findMissing(arr1, arr2) {
  let misEl;
  let a1 = arr1.sort((a,b) => a - b);
  let a2 = arr2.sort((a,b) => a - b);
  for(let i = 0; i < a1.length; i++){
    if(a1[i] !== a2[i]) return a1[i];


  }

}
```

52) https://www.codewars.com/kata/54554846126a002d5b000854
```javascript
var buy = function(x, arr){
  let res = [];

  for(let i = 0; i < arr.length - 1; i++){
    for(let j = i + 1; j < arr.length; j++){
      if  (arr[i] + arr[j] === x){
      return [i, j];
      }
    }
  }
  return null;
}
```

53) https://www.codewars.com/kata/5aa1bcda373c2eb596000112
```javascript
function maxTriSum(numbers){
let sum = 0;
  let res = numbers.sort((a,b) => b - a);
  let arr = [];
  for(let i = 0; i < res.length; i++){
    if(arr.length >= 3){
      break
    }
    if(!arr.includes(res[i])) {
    arr.push(res[i]);
    sum += res[i];
      }
    }
    return sum;
}
```

54)



