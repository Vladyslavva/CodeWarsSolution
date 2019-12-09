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

54) https://www.codewars.com/kata/513e08acc600c94f01000001
```javascript
function rgb(r, g, b){
    r = (r >= 0 && r <= 255) ? r : (r < 0) ? 0 : 255;
    g = (g >= 0 && g <= 255) ? g : (g < 0) ? 0 : 255;
    b = (b >= 0 && b <= 255) ? b : (b < 0) ? 0 : 255;
    rx = r.toString(16).length == 2 ? r.toString(16) : '0' + r.toString(16);
    gx = g.toString(16).length == 2 ? g.toString(16) : '0' + g.toString(16);
    bx = b.toString(16).length == 2 ? b.toString(16) : '0' + b.toString(16);
    return (rx + gx + bx).toUpperCase();
}
```

55) https://www.codewars.com/kata/55b75fcf67e558d3750000a3
```java 
public class Block{
	private int width;
  private int length;
  private int height;
  
  public Block (int... arg) {
    this.width = arg[0];
    this.length = arg[1];
    this.height = arg[2];
  }
  public int getWidth (){
    return this.width;
  }
   public int getLength (){
    return this.length;
  }
   public int getHeight (){
    return this.height;
  }
  
  public int getVolume () {
    return this.width * this.length * this.height;
  }
  
  public int getSurfaceArea () {
    return 2*this.width*this.length + 2*this.length*this.height + 2*this.width*this.height; 
  }
}
```
56) https://www.codewars.com/kata/5a03295680171ffd7b0000c7
```java 
public class EncapsulationDemo{
  private int number;
  private String stringValue;
  private Object anObject;
  
  public EncapsulationDemo () {}
  
  public EncapsulationDemo (int number, String stringValue, Object anObject) {
    this.number = number;
    this.stringValue = stringValue;
    this.anObject = anObject;
  }
  
  public void setNumber (int number) {
    this.number = number;
  }
  public int getNumber () {
    return this.number;
  }
  public void setStringValue (String stringValue){
    this.stringValue = stringValue;
  }
  public String getStringValue () {
    return this.stringValue;
  }
  
  public void setAnObject (Object anObject){
    this.anObject = anObject;
  }
  public Object getAnObject (){
    return this.anObject;
  }
}
```

57) https://www.codewars.com/kata/55c0a79e20be94c91400014b
```java 
public class Cube{
  private int Side;
  
  public void setSide (int num){
    this.Side = num;
  }
  public int getSide (){
    return this.Side;
  }
  
}
```

58) https://www.codewars.com/kata/5a00e05cc374cb34d100000d
```javascript
const reverseSeq = n => {
let arr = [];
  for(i = n; i > 0; i--){
  arr.push(i)
  }
  return arr;
};
```

59) https://www.codewars.com/kata/59706036f6e5d1e22d000016
```javascript
function wordsToMarks(string){
  let dict = {
  'a': 1,
  'b': 2,
  'c': 3,
  'd': 4,
  'e' : 5,
  'f' : 6,
  'g' : 7,
  'h' : 8,
  'i' : 9,
  'j' : 10,
  'k' : 11,
  'l' : 12,
  'm' : 13,
  'n' : 14,
  'o' : 15,
  'p' : 16,
  'q' : 17,
  'r' : 18,
  's' : 19,
  't' : 20,
  'u' : 21,
  'v' : 22,
  'w' : 23,
  'x' : 24,
  'y' : 25,
  'z' : 26
  }
  let count = 0;
  for (let i = 0; i < string.length; i++){
    count = count + dict[string[i]];
  }
  return count;
}
```

60) https://www.codewars.com/kata/56b29582461215098d00000f
```javascript
function pipeFix(numbers){
 let arr = [];
  for(i = numbers[0]; i <= numbers[numbers.length - 1]; i++){
    arr.push(i);
  }
  return arr;
}
```

61) https://www.codewars.com/kata/57241e0f440cd279b5000829
```javascript
function sumMul(n,m){
let sum = 0;
if (n <= 0 || m <= 0) return "INVALID";
  for (i = 0; i < m; i++){
  if (i % n === 0){
  sum = sum + i;
  } 
}
return sum;
}
```

62) https://www.codewars.com/kata/56b7f2f3f18876033f000307
```javascript
function inAscOrder(arr) {
  const arr1 = arr.slice(0);
  arr1.sort((a, b) => a - b);
  for(i = 0; i < arr1.length; i++){
    if (arr[i] !== arr1[i]) {
      return false;
    }
  }
  return true;
}
```
63) https://www.codewars.com/users/Vladyslavva/completed_solutions
```javascript
function cubeOdd(arr) {
let sum = 0;
for(i = 0; i < arr.length; i++){
  if(typeof arr[i] !== 'number') return undefined;
  if(arr[i] % 2 !== 0){
  sum = sum + (arr[i] ** 3)
  }
} 
return sum;
}
```

64) https://www.codewars.com/users/Vladyslavva/completed_solutions
```javascript
function divisors(int) {
let arr = [];
for(i = 2; i < int - 1; i++){
  if(int % i === 0){
  arr.push(i);
  }
} return arr.length === 0 ? int + ' is prime' : arr.sort((a, b) => a - b);
  
}
```

65) https://www.codewars.com/kata/5a3dd29055519e23ec000074
```javascript
function checkExam(array1, array2) {
let count = 0;
 for(let i = 0; i < array1.length; i++){
   if(array2[i] === '') continue;
   else if(array2[i] === array1[i]){
   count = count + 4;
   } else {
   count = count - 1;
   }
   
 } 
 return count < 0 ? 0 : count;
}
```

66) https://www.codewars.com/kata/5a3fe3dde1ce0e8ed6000097
```javascript
function century(year) {
  return year % 100 === 0 ? year / 100 : Math.floor(year/100) + 1;
}
```

67) https://www.codewars.com/kata/53dc23c68a0c93699800041d
```javascript
function smash (words) {
  return words.join(' ').toString();

}
```

68) https://www.codewars.com/kata/57a5c31ce298a7e6b7000334
```javascript
function binToDec(bin){
  return parseInt(bin, 2);
}
```

69) https://www.codewars.com/kata/55f73be6e12baaa5900000d4
```javascript
function goals (laLigaGoals, copaDelReyGoals, championsLeagueGoals) {
  const sum = (laLigaGoals + copaDelReyGoals + championsLeagueGoals);
  return sum;
}
```

70) https://www.codewars.com/kata/57ee4a67108d3fd9eb0000e7
```javascript
function gooseFilter (birds) {
  var geese = ["African", "Roman Tufted", "Toulouse", "Pilgrim", "Steinbacher"];
  return birds.filter(el => !geese.includes(el));
}
```

71) https://www.codewars.com/kata/5c374b346a5d0f77af500a5a
```javascript
function elevator(left, right, call){
  return Math.abs(call - right) <= Math.abs(call - left) ? "right" : "left";
}
```

72) https://www.codewars.com/kata/56cd44e1aa4ac7879200010b
```javascript
String.prototype.isUpperCase = function() {
  return this.toUpperCase() == this;
}
```

73) https://www.codewars.com/kata/5ae62fcf252e66d44d00008e
```javascript
function expressionMatter(a, b, c) {
  return Math.max(...[a + b + c, a * (b + c), (a + b) * c, a * b * c])
}
```

74) https://www.codewars.com/kata/5933a1f8552bc2750a0000ed
```javascript
function nthEven(n){
  return (n - 1) *2;
}```

75) https://www.codewars.com/kata/5266876b8f4bf2da9b000362
```javascript
function likes(names) {
  if(names.length === 0) return "no one likes this";
  if(names.length === 1) return names[0] + " likes this";
  if(names.length === 2) return names[0] + " and " + names[1] + " like this";
  if(names.length === 3) return names[0] + ", " + names[1] + " and " + names[2] + " like this";
  return names[0] + ", " + names[1] + " and " + (names.length - 2) + " others like this";
}
```

76) https://www.codewars.com/kata/57a1fd2ce298a731b20006a4
```javascript
function isPalindrome(x) {
  for(let i = 0; i < x.length/2; i++){
    if(x[i].toLowerCase() !== x[x.length - 1 - i].toLowerCase()) {
    return false;
    }
   }
   return true;
}
```

77) https://www.codewars.com/kata/56f695399400f5d9ef000af5
```javascript
function correctTail(body, tail){

  sub = body.substr(body.length-tail.length)

  if (sub === tail)  return true;

  else return false;
  }
```

78) https://www.codewars.com/kata/5bb904724c47249b10000131
```javascript
function points(games) {
let score = 0;
  for(let i = 0; i < games.length; i++){
   let a = games[i].split(':');
   if(+a[0] > +a[1]){
     score = score + 3;
   }else if (+a[0] === +a[1]){
    score = score + 1;
   }else score = score + 0;
  }
  return score;
}
```

79) https://www.codewars.com/kata/53dc54212259ed3d4f00071c
```javascript
function sum (numbers) {
  if(numbers.length === 0)return 0;
 return numbers.reduce ((x, y) => (x + y), 0);

}
```

80) https://www.codewars.com/kata/563b74ddd19a3ad462000054
```javascript
function stringy(size) {
  let str = '';
  for(let i = 0; i < size; i++){
    if (i % 2 === 0) {
      str = str + '1';
    } else {
      str = str + '0';
    }
  }
  return str;
}
```

81) https://www.codewars.com/kata/574b1916a3ebd6e4fa0012e7
```javascript
function isOpposite(s1,s2){
console.log(s1 + " " + s2)
 if(s1.length === 0 && s2.length === 0) return false;
 if(s1.length !== s2.length) return false;
 for(let i = 0; i < s1.length; i++){
   if (!(s1[i] !== s2[i] && s1[i].toLowerCase() === s2[i].toLowerCase())) return false;
   }
 return true;

}
```

82) https://www.codewars.com/kata/5875b200d520904a04000003
```javascript
function enough(cap, on, wait) {
  if((cap - on) >= wait) return 0;
  else return wait - (cap - on);
}
```

83) https://www.codewars.com/kata/586c1cf4b98de0399300001d
```javascript
function combat(health, damage) {
if(health <= damage) return 0;
  return health - damage;
}
```

84) https://www.codewars.com/kata/5865918c6b569962950002a1
```javascript
function strCount(str, letter){
  let cnt = 0;
  for(let i = 0; i < str.length; i++){
  if(str[i] === letter) cnt++;
  }
  return cnt;
}
```

85) https://www.codewars.com/kata/5c8bfa44b9d1192e1ebd3d15
```javascript
function warnTheSheep(queue) {
 for(let i = 0 ; i < queue.length; i++){
  if(queue[i] === "wolf") {
    if(queue.length - 1 === i) return "Pls go away and stop eating my sheep";
   else return "Oi! Sheep number " + (queue.length - i - 1) + "! You are about to be eaten by a wolf!";
   }
 }
}
```

86) https://www.codewars.com/kata/565f5825379664a26b00007c
```javascript
function getSize(w, h, d){
 let volume = w * h * d;
 let area = 2 * (h * d) + 2 * (h * w) + 2 *(d * w);
 return [area, volume];
}
```

87) https://www.codewars.com/kata/58235a167a8cb37e1a0000db
```javascript
function numberOfPairs(gloves){
let cnt = {};
let number = 0;
console.log(gloves);
 gloves.forEach(function (el) { cnt[el] = (cnt [el] || 0) + 1;});
 let arr = Object.values(cnt);
 for (let i = 0; i < arr.length; i++) {
   if (arr[i] >= 2) {
     number = number + Math.floor(arr[i]/2);
   }
 }
 return number;
}
```

88) https://www.codewars.com/kata/57356c55867b9b7a60000bd7
```java
public class BasicOperations
{
  public static Integer basicMath(String op, int v1, int v2)
  {
  if(op.equals("+")) return v1 + v2;
  if(op.equals("-")) return v1 - v2;
  if(op.equals("*")) return v1 * v2;
  return v1 / v2;

  }
}
```

89) https://www.codewars.com/kata/5a2fd38b55519ed98f0000ce
```javascript
function multiTable(number) {
let res = '';
  for (let i = 1; i <= 10; i++){
  res = res + (i + " * " + number + " = " + (number * i) + "\n");
    }
    return res.slice(0, res.length - 1);
}
```

90) https://www.codewars.com/kata/53af2b8861023f1d88000832
```java
public class Banjo {
  public static String areYouPlayingBanjo(String name) {
    if (name.charAt(0) == 'R' || name.charAt(0) == 'r') return name + " plays banjo";
   else return name + " does not play banjo";
   }
}
```

91) https://www.codewars.com/kata/557cd6882bfa3c8a9f0000c1
```javascript
function getAge(inputString){
for(let i = 0; i <= 9; i ++){
return +inputString[i];
  }
}
```

92) https://www.codewars.com/kata/5769b3802ae6f8e4890009d2
```javascript
function removeEveryOther(arr){
 let resArr = [];
  for(let i = 0; i < arr.length; i = i + 2){
    resArr.push(arr[i]);
  }return resArr;
}
```

93) https://www.codewars.com/kata/58dbdccee5ee8fa2f9000058
```javascript
function spEng(s){
return s.toLowerCase().includes("english");
}
```

94) https://www.codewars.com/kata/59dd3ccdded72fc78b000b25
```javascript
function whatday(num) {
let week = ["Sunday", "Monday", "Tuesday", "Wednesday", "Thursday", "Friday", "Saturday"];
return (num > 0 && num < 8) ? week[num - 1] : "Wrong, please enter a number between 1 and 7";
}
```

95) https://www.codewars.com/kata/5772da22b89313a4d50012f7
```javascript
function greet (name, owner) {
  return (name === owner) ? 'Hello boss' : 'Hello guest';
}
```

96) https://www.codewars.com/kata/58d248c7012397a81800005c
```javascript
var cubeChecker = function(volume, side){
if(side <= 0 || volume <= 0) return false;
console.log(volume ** (1/3));
 return Math.cbrt(volume) === side;
}
```

97) https://www.codewars.com/kata/5a8fbe73373c2e904700008c
```javascript
function solve(st){
 for(let i = 0; i < st.length; i++){
   if(st === st.split('').reverse().join('')) return true;
   else st = st[st.length - 1] + st.substring(0, st.length - 1);
   console.log(st);
 } return false;
}
```

98) https://www.codewars.com/kata/5b73fe9fb3d9776fbf00009e
```javascript
function sumOfDifferences(arr) {
 if (arr.length === 0 || arr.length === 1) return 0;
 arr.sort((a,b) => b - a);
 let sum = 0;
 for (let i = 1; i < arr.length; i++) {
   sum = sum + (arr[i - 1] - arr[i]);
 }
 return sum;
}
```

99) https://www.codewars.com/kata/570f6436b29c708a32000826
```javascript
function firstNonRepeated(s) {
  s.split('');
  console.log(s);
  for(let i = 0; i < s.length; i++){
    if(s.indexOf(s[i]) === s.lastIndexOf(s[i])) return s[i];
  }
  return null;
}
```

100) https://www.codewars.com/kata/59811fd8a070625d4c000013
```javascript
function integrate(coefficient, exponent) {
  return `${coefficient/(exponent + 1)}x^${exponent + 1}`;
}
```

101) https://www.codewars.com/kata/560dab9f8b50f89fd6000070
```javascript
let money = 10;
let candy = 1.42;
let chips = 2.40;
let soda = 1.00;
let change = money - candy - chips - soda;
```

102) https://www.codewars.com/kata/56f699cd9400f5b7d8000b55
```javascript
function fixTheMeerkat(arr) {
 return arr.reverse();
}
```

103) https://www.codewars.com/kata/58f8a3a27a5c28d92e000144
```javascript
function firstNonConsecutive (arr) {
 for(let i = 0; i < arr.length -1; i++){
  if(arr[i] != arr[i+1] - 1) return arr[i+1];
 }
 return null;
}
```

104) https://www.codewars.com/kata/55a5bfaa756cfede78000026
```javascript
function problem(x){
  if (typeof x === "string") return "Error";
  else return (x * 50) + 6;
}
```

105) https://www.codewars.com/kata/56f3f6a82010832b02000f38
```javascript
function describeAge(a){s="You're a(n)";return a<13?s+" kid" : (a>12 && a<18)?s+" teenager" : (a>17 && a<65)?s+" adult" : s+" elderly";}
```

106) https://www.codewars.com/kata/56f6919a6b88de18ff000b36
```javascript
function howManyDalmatians(number) {

  var dogs = ["Hardly any", "More than a handful!", "Woah that's a lot of dogs!", "101 DALMATIANS!!!"];

  var respond = number <= 10 ? dogs[0] : (number <= 50 ? dogs[1] : (number === 101 ? dogs[3] : dogs[2]));

return respond;
}
```

107) https://www.codewars.com/kata/56efc695740d30f963000557
```javascript
String.prototype.toAlternatingCase = function () {
  let newString = "";
  for(let i = 0; i < this.length; i++){
    if (this[i].toLowerCase() === this[i]) newString += this[i].toUpperCase();
    else newString += this[i].toLowerCase();
  } return newString;
}
```

108) https://www.codewars.com/kata/568d0dd208ee69389d000016
```javascript
function rentalCarCost(d) {
  if(d < 3) return d * 40;
  else if(d >= 3 && d < 7) return d * 40 - 20;
  else return (d * 40) - 50;
}
```

109) https://www.codewars.com/kata/54edbc7200b811e956000556
```javascript
function countSheeps(arrayOfSheep) {
let count = 0;
  for(let i = 0; i < arrayOfSheep.length; i++){
    if(arrayOfSheep[i] === true)
      count ++
    } return count;
  }
  ```

  110) https://www.codewars.com/kata/58e0f0bf92d04ccf0a000010
  ```javascript
function lostSheep(friday,saturday,total){
  let arr1 = friday.concat(saturday);
  return total - arr1.reduce((accum, current) => accum + current, 0);

  }
  ```

  111) https://www.codewars.com/kata/5a9e86705ee396d6be000091
  ```javascript
  function checkThreeAndTwo(array) {
    let a = 0;
    let b = 0;
    let c = 0;
    for(let i = 0; i < array.length; i++){
      if (array[i] === 'a') a = a + 1;
      if (array[i] === 'b') b = b + 1;
      if (array[i] === 'c') c = c + 1;

    }
    return (a + b === 5 || a + c === 5 || b + c === 5) &&  (a <= 3 && b <= 3 && c <= 3);
  }

  ```

  112) https://www.codewars.com/kata/59c8b38423dacc7d95000008
  ```javascript
function isValid(formula){
  if (formula.includes(1) && formula.includes(2)) return false;
  if (formula.includes(3) && formula.includes(4)) return false;
  if (formula.includes(5) || formula.includes(6)) {if (!(formula.includes(5) && formula.includes(6))) return false;}
  if (!(formula.includes(7) || formula.includes(8))) return false;
  return true;
}
  ```

  113) https://www.codewars.com/kata/555615a77ebc7c2c8a0000b8
  ```javascript
  function tickets(peopleInLine){
    let bank  = {
      25 : 0,
      50: 0,
      100: 0
    };
    if(peopleInLine[0] !== 25) return 'NO';
    bank['25'] += 1;
    for(let i = 1; i < peopleInLine.length; i++){
      if(peopleInLine[i] === 25){
        bank['25']+= 1;
      } else if (peopleInLine[i] === 50){
        if(bank['25'] > 0){
          bank['25'] -=1;
          bank['50'] +=1;
        } else return 'NO';
      } else {
        if(bank['25'] > 0 && bank['50'] > 0){
          bank['100'] +=1;
          bank['50'] -=1;
          bank['25'] -=1;
        } else if (bank['25'] > 2){
          bank['100'] +=1;
          bank['25'] -=3;
        } else return 'NO';

      }
    } return 'YES';
  }
  ```

  114) https://www.codewars.com/kata/545afd0761aa4c3055001386
  ```javascript
  function take(arr, n) {
    return arr.slice(0, n);
  }
  ```

  115) https://www.codewars.com/kata/55cbc3586671f6aa070000fb
  ```javascript
function checkForFactor (base, factor) {
  if(base % factor === 0) return true;
  else return false;
}
  ```

  116) https://www.codewars.com/kata/591588d49f4056e13f000001
  ```javascript
  function HQ9(code) {
    if(code.includes('H')) return 'Hello World!';
    if(code.includes('Q')) return 'Q';
    if(code.includes('9')) return '99 bottles of beer on the wall, 99 bottles of beer.\nTake one down and pass it around, 98 bottles of beer on the wall.\n98 bottles of beer on the wall, 98 bottles of beer.\nTake one down and pass it around, 97 bottles of beer on the wall.\n97 bottles of beer on the wall, 97 bottles of beer.\nTake one down and pass it around, 96 bottles of beer on the wall.\n96 bottles of beer on the wall, 96 bottles of beer.\nTake one down and pass it around, 95 bottles of beer on the wall.\n95 bottles of beer on the wall, 95 bottles of beer.\nTake one down and pass it around, 94 bottles of beer on the wall.\n94 bottles of beer on the wall, 94 bottles of beer.\nTake one down and pass it around, 93 bottles of beer on the wall.\n93 bottles of beer on the wall, 93 bottles of beer.\nTake one down and pass it around, 92 bottles of beer on the wall.\n92 bottles of beer on the wall, 92 bottles of beer.\nTake one down and pass it around, 91 bottles of beer on the wall.\n91 bottles of beer on the wall, 91 bottles of beer.\nTake one down and pass it around, 90 bottles of beer on the wall.\n90 bottles of beer on the wall, 90 bottles of beer.\nTake one down and pass it around, 89 bottles of beer on the wall.\n89 bottles of beer on the wall, 89 bottles of beer.\nTake one down and pass it around, 88 bottles of beer on the wall.\n88 bottles of beer on the wall, 88 bottles of beer.\nTake one down and pass it around, 87 bottles of beer on the wall.\n87 bottles of beer on the wall, 87 bottles of beer.\nTake one down and pass it around, 86 bottles of beer on the wall.\n86 bottles of beer on the wall, 86 bottles of beer.\nTake one down and pass it around, 85 bottles of beer on the wall.\n85 bottles of beer on the wall, 85 bottles of beer.\nTake one down and pass it around, 84 bottles of beer on the wall.\n84 bottles of beer on the wall, 84 bottles of beer.\nTake one down and pass it around, 83 bottles of beer on the wall.\n83 bottles of beer on the wall, 83 bottles of beer.\nTake one down and pass it around, 82 bottles of beer on the wall.\n82 bottles of beer on the wall, 82 bottles of beer.\nTake one down and pass it around, 81 bottles of beer on the wall.\n81 bottles of beer on the wall, 81 bottles of beer.\nTake one down and pass it around, 80 bottles of beer on the wall.\n80 bottles of beer on the wall, 80 bottles of beer.\nTake one down and pass it around, 79 bottles of beer on the wall.\n79 bottles of beer on the wall, 79 bottles of beer.\nTake one down and pass it around, 78 bottles of beer on the wall.\n78 bottles of beer on the wall, 78 bottles of beer.\nTake one down and pass it around, 77 bottles of beer on the wall.\n77 bottles of beer on the wall, 77 bottles of beer.\nTake one down and pass it around, 76 bottles of beer on the wall.\n76 bottles of beer on the wall, 76 bottles of beer.\nTake one down and pass it around, 75 bottles of beer on the wall.\n75 bottles of beer on the wall, 75 bottles of beer.\nTake one down and pass it around, 74 bottles of beer on the wall.\n74 bottles of beer on the wall, 74 bottles of beer.\nTake one down and pass it around, 73 bottles of beer on the wall.\n73 bottles of beer on the wall, 73 bottles of beer.\nTake one down and pass it around, 72 bottles of beer on the wall.\n72 bottles of beer on the wall, 72 bottles of beer.\nTake one down and pass it around, 71 bottles of beer on the wall.\n71 bottles of beer on the wall, 71 bottles of beer.\nTake one down and pass it around, 70 bottles of beer on the wall.\n70 bottles of beer on the wall, 70 bottles of beer.\nTake one down and pass it around, 69 bottles of beer on the wall.\n69 bottles of beer on the wall, 69 bottles of beer.\nTake one down and pass it around, 68 bottles of beer on the wall.\n68 bottles of beer on the wall, 68 bottles of beer.\nTake one down and pass it around, 67 bottles of beer on the wall.\n67 bottles of beer on the wall, 67 bottles of beer.\nTake one down and pass it around, 66 bottles of beer on the wall.\n66 bottles of beer on the wall, 66 bottles of beer.\nTake one down and pass it around, 65 bottles of beer on the wall.\n65 bottles of beer on the wall, 65 bottles of beer.\nTake one down and pass it around, 64 bottles of beer on the wall.\n64 bottles of beer on the wall, 64 bottles of beer.\nTake one down and pass it around, 63 bottles of beer on the wall.\n63 bottles of beer on the wall, 63 bottles of beer.\nTake one down and pass it around, 62 bottles of beer on the wall.\n62 bottles of beer on the wall, 62 bottles of beer.\nTake one down and pass it around, 61 bottles of beer on the wall.\n61 bottles of beer on the wall, 61 bottles of beer.\nTake one down and pass it around, 60 bottles of beer on the wall.\n60 bottles of beer on the wall, 60 bottles of beer.\nTake one down and pass it around, 59 bottles of beer on the wall.\n59 bottles of beer on the wall, 59 bottles of beer.\nTake one down and pass it around, 58 bottles of beer on the wall.\n58 bottles of beer on the wall, 58 bottles of beer.\nTake one down and pass it around, 57 bottles of beer on the wall.\n57 bottles of beer on the wall, 57 bottles of beer.\nTake one down and pass it around, 56 bottles of beer on the wall.\n56 bottles of beer on the wall, 56 bottles of beer.\nTake one down and pass it around, 55 bottles of beer on the wall.\n55 bottles of beer on the wall, 55 bottles of beer.\nTake one down and pass it around, 54 bottles of beer on the wall.\n54 bottles of beer on the wall, 54 bottles of beer.\nTake one down and pass it around, 53 bottles of beer on the wall.\n53 bottles of beer on the wall, 53 bottles of beer.\nTake one down and pass it around, 52 bottles of beer on the wall.\n52 bottles of beer on the wall, 52 bottles of beer.\nTake one down and pass it around, 51 bottles of beer on the wall.\n51 bottles of beer on the wall, 51 bottles of beer.\nTake one down and pass it around, 50 bottles of beer on the wall.\n50 bottles of beer on the wall, 50 bottles of beer.\nTake one down and pass it around, 49 bottles of beer on the wall.\n49 bottles of beer on the wall, 49 bottles of beer.\nTake one down and pass it around, 48 bottles of beer on the wall.\n48 bottles of beer on the wall, 48 bottles of beer.\nTake one down and pass it around, 47 bottles of beer on the wall.\n47 bottles of beer on the wall, 47 bottles of beer.\nTake one down and pass it around, 46 bottles of beer on the wall.\n46 bottles of beer on the wall, 46 bottles of beer.\nTake one down and pass it around, 45 bottles of beer on the wall.\n45 bottles of beer on the wall, 45 bottles of beer.\nTake one down and pass it around, 44 bottles of beer on the wall.\n44 bottles of beer on the wall, 44 bottles of beer.\nTake one down and pass it around, 43 bottles of beer on the wall.\n43 bottles of beer on the wall, 43 bottles of beer.\nTake one down and pass it around, 42 bottles of beer on the wall.\n42 bottles of beer on the wall, 42 bottles of beer.\nTake one down and pass it around, 41 bottles of beer on the wall.\n41 bottles of beer on the wall, 41 bottles of beer.\nTake one down and pass it around, 40 bottles of beer on the wall.\n40 bottles of beer on the wall, 40 bottles of beer.\nTake one down and pass it around, 39 bottles of beer on the wall.\n39 bottles of beer on the wall, 39 bottles of beer.\nTake one down and pass it around, 38 bottles of beer on the wall.\n38 bottles of beer on the wall, 38 bottles of beer.\nTake one down and pass it around, 37 bottles of beer on the wall.\n37 bottles of beer on the wall, 37 bottles of beer.\nTake one down and pass it around, 36 bottles of beer on the wall.\n36 bottles of beer on the wall, 36 bottles of beer.\nTake one down and pass it around, 35 bottles of beer on the wall.\n35 bottles of beer on the wall, 35 bottles of beer.\nTake one down and pass it around, 34 bottles of beer on the wall.\n34 bottles of beer on the wall, 34 bottles of beer.\nTake one down and pass it around, 33 bottles of beer on the wall.\n33 bottles of beer on the wall, 33 bottles of beer.\nTake one down and pass it around, 32 bottles of beer on the wall.\n32 bottles of beer on the wall, 32 bottles of beer.\nTake one down and pass it around, 31 bottles of beer on the wall.\n31 bottles of beer on the wall, 31 bottles of beer.\nTake one down and pass it around, 30 bottles of beer on the wall.\n30 bottles of beer on the wall, 30 bottles of beer.\nTake one down and pass it around, 29 bottles of beer on the wall.\n29 bottles of beer on the wall, 29 bottles of beer.\nTake one down and pass it around, 28 bottles of beer on the wall.\n28 bottles of beer on the wall, 28 bottles of beer.\nTake one down and pass it around, 27 bottles of beer on the wall.\n27 bottles of beer on the wall, 27 bottles of beer.\nTake one down and pass it around, 26 bottles of beer on the wall.\n26 bottles of beer on the wall, 26 bottles of beer.\nTake one down and pass it around, 25 bottles of beer on the wall.\n25 bottles of beer on the wall, 25 bottles of beer.\nTake one down and pass it around, 24 bottles of beer on the wall.\n24 bottles of beer on the wall, 24 bottles of beer.\nTake one down and pass it around, 23 bottles of beer on the wall.\n23 bottles of beer on the wall, 23 bottles of beer.\nTake one down and pass it around, 22 bottles of beer on the wall.\n22 bottles of beer on the wall, 22 bottles of beer.\nTake one down and pass it around, 21 bottles of beer on the wall.\n21 bottles of beer on the wall, 21 bottles of beer.\nTake one down and pass it around, 20 bottles of beer on the wall.\n20 bottles of beer on the wall, 20 bottles of beer.\nTake one down and pass it around, 19 bottles of beer on the wall.\n19 bottles of beer on the wall, 19 bottles of beer.\nTake one down and pass it around, 18 bottles of beer on the wall.\n18 bottles of beer on the wall, 18 bottles of beer.\nTake one down and pass it around, 17 bottles of beer on the wall.\n17 bottles of beer on the wall, 17 bottles of beer.\nTake one down and pass it around, 16 bottles of beer on the wall.\n16 bottles of beer on the wall, 16 bottles of beer.\nTake one down and pass it around, 15 bottles of beer on the wall.\n15 bottles of beer on the wall, 15 bottles of beer.\nTake one down and pass it around, 14 bottles of beer on the wall.\n14 bottles of beer on the wall, 14 bottles of beer.\nTake one down and pass it around, 13 bottles of beer on the wall.\n13 bottles of beer on the wall, 13 bottles of beer.\nTake one down and pass it around, 12 bottles of beer on the wall.\n12 bottles of beer on the wall, 12 bottles of beer.\nTake one down and pass it around, 11 bottles of beer on the wall.\n11 bottles of beer on the wall, 11 bottles of beer.\nTake one down and pass it around, 10 bottles of beer on the wall.\n10 bottles of beer on the wall, 10 bottles of beer.\nTake one down and pass it around, 9 bottles of beer on the wall.\n9 bottles of beer on the wall, 9 bottles of beer.\nTake one down and pass it around, 8 bottles of beer on the wall.\n8 bottles of beer on the wall, 8 bottles of beer.\nTake one down and pass it around, 7 bottles of beer on the wall.\n7 bottles of beer on the wall, 7 bottles of beer.\nTake one down and pass it around, 6 bottles of beer on the wall.\n6 bottles of beer on the wall, 6 bottles of beer.\nTake one down and pass it around, 5 bottles of beer on the wall.\n5 bottles of beer on the wall, 5 bottles of beer.\nTake one down and pass it around, 4 bottles of beer on the wall.\n4 bottles of beer on the wall, 4 bottles of beer.\nTake one down and pass it around, 3 bottles of beer on the wall.\n3 bottles of beer on the wall, 3 bottles of beer.\nTake one down and pass it around, 2 bottles of beer on the wall.\n2 bottles of beer on the wall, 2 bottles of beer.\nTake one down and pass it around, 1 bottle of beer on the wall.\n1 bottle of beer on the wall, 1 bottle of beer.\nTake one down and pass it around, no more bottles of beer on the wall.\nNo more bottles of beer on the wall, no more bottles of beer.\nGo to the store and buy some more, 99 bottles of beer on the wall.';

  }
  ```

  117) https://www.codewars.com/kata/563a631f7cbbc236cf0000c2
  ```javascript
function move (position, roll) {
  return (position + roll * 2);
}
  ```

  118) https://www.codewars.com/kata/5388f0e00b24c5635e000fc6
  ```javascript
 function swapValues() {
     var arg = Array.prototype.slice.call(arguments)[0];
     var temp = arg[0];
     arg[0] = arg[1];
     arg[1] = temp;
     return arg;
 }
  ```

  119) https://www.codewars.com/kata/5a34b80155519e1a00000009
  ```javascript
  function multipleOfIndex(array) {
    const arr = [];
    for(let i = 0; i < array.length; i++){
      if(array[i] % i === 0) arr.push(array[i]);
    }return arr;
  }
  ```

  120) https://www.codewars.com/kata/55d1d6d5955ec6365400006d
  ```javascript
function roundToNext5(n){
  while(true){
   if(n % 5 === 0) return n;
   n++;
  }
}
  ```

  121) https://www.codewars.com/kata/55eca815d0d20962e1000106
  ```javascript
  function generateRange(min, max, step){
    const arr = [];
    for( let i = min; i <= max; i = i + step){
      arr.push(i);
    }
    return arr;
    }

  ```

  122) https://www.codewars.com/kata/59ca8246d751df55cc00014c
  ```javascript
  function hero(bullets, dragons){
   return bullets/dragons >= 2;
  }
  ```

  123) https://www.codewars.com/kata/57a429e253ba3381850000fb
  ```javascript
function bmi(weight, height) {
  let bmi =  weight / (height ** 2);
  return bmi <= 18.5 ? "Underweight" : bmi <= 25.0 ? "Normal" : bmi <= 30.0 ?  "Overweight" : "Obese";
}
  ```

  124) https://www.codewars.com/kata/57e3f79c9cb119374600046b
  ``javascript
function hello(name) {
  if(name === undefined || name === '')return "Hello, World!";
  name = name.toLowerCase();
  name = name[0].toUpperCase() + name.slice(1, name.length);
  return `Hello, ${name}!`;
}
  ```

  125) https://www.codewars.com/kata/523b623152af8a30c6000027
  ```javascript
  function square(arg){
    return arg * arg;
  }
  ```


  126) https://www.codewars.com/kata/5b853229cfde412a470000d0
  ```javascript
  function twiceAsOld(dadYearsOld, sonYearsOld) {
    const age =  + (dadYearsOld - sonYearsOld * 2);
    return Math.abs(age);
  }
  ```

  127) https://www.codewars.com/kata/545991b4cbae2a5fda000158
  ```javascript
function include(arr, item){
  if(arr.includes(item)) return true;
  return false
}
  ```

  128) https://www.codewars.com/kata/58630e2ae88af44d2b0000ea
  ```javascript
  function isDivisible(wallLength, pixelSize){
    return wallLength % pixelSize == 0 ? true : false;
  }
  ```

  129) https://www.codewars.com/kata/554b4ac871d6813a03000035
  ```javascript
function highAndLow(s){
  let max, min, n, b = '';

  for(let i = 0; i < s.length; i++){
    if(s[i] !== ' '){
     b+=s[i];
    }
   if(s[i]=== ' ' || i === s.length - 1){
     n=+b;
     b = '';
     if(n > max || max === undefined) max = n;
     if(n < min || min === undefined) min = n;
   }

  }
  return max + ' ' + min;
}
  ```

  130) https://www.codewars.com/kata/5bb0c58f484fcd170700063d
  ```javascript
function pillars(num_pill, dist, width) {
  return num_pill > 1 ? dist * 100 * (num_pill - 1) + width * (num_pill - 2) : 0;
}
  ```

  131) https://www.codewars.com/kata/555086d53eac039a2a000083
  ```javascript
  function lovefunc(flower1, flower2){
    return ((flower1 % 2 === 0) && (flower2 % 2 !== 0)) || ((flower2 % 2 === 0) && (flower1 % 2 !== 0)) ? true : false;
  }
  ```

  132) https://www.codewars.com/kata/57e92e91b63b6cbac20001e5
  ```javascript
  function dutyFree(normPrice, discount, hol){
  return Math.floor(hol/((normPrice/100) * discount));
  }
  ```

  133) https://www.codewars.com/kata/582dafb611d576b745000b74
  ```javascript
var quote = function(fighter) {
  return fighter.toLowerCase() === 'george saint pierre' ? "I am not impressed by your performance." : "I'd like to take this chance to apologize.. To absolutely NOBODY!"
};
```

134) https://www.codewars.com/kata/57126304cdbf63c6770012bd
```javascript
function isDigit(s) {
  return s.trim() === '' ? false : !isNaN(s.trim());

}
```

135) https://www.codewars.com/kata/5a6663e9fd56cb5ab800008b
```javascript
var humanYearsCatYearsDogYears = function(humanYears) {
  let catYears = 0;
    let dogYears = 0;

    if (humanYears === 1) {
    catYears = 15;
    dogYears = 15;
    }

    else if (humanYears === 2)  {
    catYears = 24;
    dogYears = 24;
    }

    else {
        catYears = 4*(humanYears-2) + 24 ;
        dogYears= 5*(humanYears-2) + 24;
        }


    return [humanYears, catYears, dogYears];
}
```
136) https://www.codewars.com/kata/57fb09ef2b5314a8a90001ed
```javscript
function replace(s){
  const arrVowels = ['a', 'o', 'u', 'e', 'i'];
  let newS = '';
for(let i = 0; i < s.length; i++){
  if (arrVowels.includes(s[i].toLowerCase())) newS = newS + '!';
    else newS = newS + s[i];
}
  return newS;

}
```

137) https://www.codewars.com/kata/55fab1ffda3e2e44f00000c6
```javascript
function cockroachSpeed(s) {
  return Math.floor(s/0.036);
}
```

138) https://www.codewars.com/kata/55225023e1be1ec8bc000390
```java
public class Greeter {
  public static String greet(String name) {

    if(name.equals("Johnny")){
      return "Hello, my love!";
    }

    return String.format("Hello, %s!", name);
  }
}
```

139) https://www.codewars.com/kata/55acfc59c3c23d230f00006d
```javascript
function getASCII(c){
 const charCode = c.charCodeAt(0);
 return charCode;
}
```

140) https://www.codewars.com/kata/563c13853b07a8f17c000022
```javascript
function isToday(date) {
  const now = new Date();
  return now.getDate() === date.getDate() && now.getFullYear() === date.getFullYear() && now.getMonth() === date.getMonth();
}
```

141) https://www.codewars.com/kata/597c684822bc9388f600010f
```java
public class Dinglemouse {

  private String firstName;
  private String lastName;

  public Dinglemouse(String firstName, String lastName) {
    this.firstName = firstName;
    this.lastName = lastName;
  }

  public String getFullName() {
    if((this.firstName.equals("")) && (this.lastName.equals(""))) return "";
    if(this.firstName.equals("")) return this.lastName;
    if(this.lastName.equals("")) return this.firstName;
    return this.firstName + " " + this.lastName;
  }
}
```

142) https://www.codewars.com/kata/50654ddff44f800200000004
```java
public class Multiply {
    public static Double multiply(Double a, Double b) {
        return a * b;
    }
}
```

143) https://www.codewars.com/kata/582cb0224e56e068d800003c
```java
public class KeepHydrated  {

  public int Liters(double time)  {

    return (int)(time * 0.5);

  }

}
```

144) https://www.codewars.com/kata/55f9bca8ecaa9eac7100004a
```java
public class Clock
{
  public static int Past(int h, int m, int s)
  {
    return h * 3600000 + m * 60000 + s * 1000;
  }
}
```

145) https://www.codewars.com/kata/57202aefe8d6c514300001fd
```java
public class SaleHotdogs{
  public static int saleHotdogs(final int n){
    return n < 5 ? n*100 : n >= 5 && n < 10 ? n*95 : n*90;
  }
}
```

146) https://www.codewars.com/kata/59441520102eaa25260000bf
```javascript
function unusualFive() {
  return 'H'.charCodeAt() % 'C'.charCodeAt();
}
```

147) https://www.codewars.com/kata/555a67db74814aa4ee0001b5
``java
public class Number {

  public boolean isEven(double n) {
     if(n % 2 == 0) return true;
     else return false;
  }
}
```

148) https://www.codewars.com/kata/5302d846be2a9189af0001e4
```java
public class Hello{
  public String sayHello(String [] name, String city, String state){
   String str = "Hello, ";
    for( int i = 0; i < name.length; i++){
       if(i != name.length - 1) str = str + name[i] + " ";
       else str = str + name[i] + "!";
    }
    return str + " Welcome to " + city + ", " + state + "!";
  }
}
```

149) https://www.codewars.com/kata/55c7f90ac8025ebee1000062
```javascript
var sortArray = function(value) {
  return value.split('').sort((c, p) => (c - p)).join('');
}
```

150) https://www.codewars.com/kata/514a677421607afc99000002
```javascript
function getNames(data){
 return data.map(item => item.name);

}
```

151) https://www.codewars.com/kata/52e9aa89b5acdd26d3000127
```javascript
function hoopCount (n) {
  return ( n >= 10) ? "Great, now move on to tricks":  "Keep at it until you get it";
}
```

152) https://www.codewars.com/kata/52e9aa89b5acdd26d3000127
```javascript
function spam(number){
  return "hue".repeat(number);
}
```

153) https://www.codewars.com/kata/5708f682c69b48047b000e07
```javascript
function multiply(number){
  return number > 0 ? 5 ** number.toString().length * number: 5 ** (number.toString().length - 1) * number;
}
```

154) https://www.codewars.com/kata/5b4e779c578c6a898e0005c5
```javascript
function drawStairs(n) {
 let step = "I";
 for(let i= 1; i < n; i++){
   step = step +"\n" + " ".repeat(i) + "I";
 } return step;
}
```

155) https://www.codewars.com/kata/56598d8076ee7a0759000087
```java
public class TipCalculator {

  public static Integer calculateTip(double amount, String rating) {
  rating = rating.toLowerCase();
    switch (rating) {
      case "terrible": return 0;
      case "poor": return (int) Math.ceil(amount * 0.05);
      case "good": return (int) Math.ceil(amount * 0.1);
      case "great": return (int) Math.ceil(amount * 0.15);
      case "excellent": return (int) Math.ceil(amount * 0.2);

    }
    return null;
  }
}
```

156) https://www.codewars.com/kata/557af9418895e44de7000053
```java
public class RepeatIt {

  public static String repeatString(final Object toRepeat, final int n) {
   if (!(toRepeat instanceof String)) return "Not a string";
   String rez = "";
   for (int i = 0; i < n; i++) {
     rez = rez + toRepeat;
   }

   return rez;
  }

}
```

157) https://www.codewars.com/kata/5704aea738428f4d30000914
```java
public class Kata {
    public static String tripleTrouble(String one, String two, String three) {
        String res = "";
        for(int i = 0; i < one.length(); i++){
            String s = one.substring(i, i + 1) + two.substring(i, i + 1) + three.substring(i, i + 1);
            res+=s;
        }return res;
    }
}
```

157) https://www.codewars.com/kata/57f24e6a18e9fad8eb000296
```javascript
function howMuchILoveYou(n) {
  const flower = ['I love you', 'a little', 'a lot', 'passionately', 'madly', 'not at all'];
    return flower[(n - 1) % 6];
}
```

158) https://www.codewars.com/kata/554e4a2f232cdd87d9000038
```javascript
function DNAStrand(dna){
 let res = '';
 for(let i = 0; i < dna.length; i++){
   if(dna[i] === 'A') res += 'T';
   if(dna[i] === 'T') res += 'A';
   if(dna[i] === 'G') res += 'C';
   if(dna[i] === 'C') res += 'G';
 }
 return res;
}
```

159) https://www.codewars.com/kata/5890d8bc9f0f422cf200006b
```javascript
//return price without vat
function excludingVatPrice(price){
  if(price === null) return -1;
  return Math.round((price / 115)*10000)/100;
}
```

160) https://www.codewars.com/kata/51f41fe7e8f176e70d0002b9
```javascript
// input: names - unsorted strings
// output: case-agnostic sort
sortme = function( names ){
return names.sort(function (a, b) {
    return a.toLowerCase().localeCompare(b.toLowerCase());
});
}
```

161) https://www.codewars.com/kata/582e0e592029ea10530009ce
```java
public class Kata {
  public static String duckDuckGoose(Player[] players, int goose) {
    // Note: Player objects have a String field called 'name'.
    return players[(goose - 1) % players.length].name;
  }
}
```

162) https://www.codewars.com/users/Vladyslavva/completed_solutions
```java
public class SortAndStar {

  public static String twoSort(String[] s) {
  String max = s[0];
  String res = "";
  for(int i = 1; i < s.length; i++){
     if(s[i].compareTo(max) < 0) max = s[i];
   }
  for(int i = 0; i < max.length(); i++){
     res = res + max.charAt(i) + "***";
   }
   return res.substring(0, res.length() - 3);
  }

}
```

163) https://www.codewars.com/kata/5966e33c4e686b508700002d
```javascript
function sumStr(a,b) {
if(a==="" ) a = 0;
if(b==="" ) b = 0;
return (+a + +b) + "";
}
```

164) https://www.codewars.com/kata/563d59dd8e47a5ed220000ba
```javascript
function getSumOfDigits(integer) {
  let sum = null;
  let digits = integer.toString();
  for(let i = 0; i < digits.length; i++) {
    sum += +digits[i];
  }
  return sum;
}
```

165) https://www.codewars.com/kata/56f69d9f9400f508fb000ba7
```java
public class MonkeyCounter
{
  public static int[] monkeyCount(final int n){
  int[] monkeys = new int[n];
  for(int i = 0; i < n; i++){
     monkeys[i] = i + 1;
   }
   return monkeys;
  }
}
```

166) https://www.codewars.com/kata/5512a0b0509063e57d0003f5
```java
public class FirstClass {
    public static byte sum (byte a, byte b) {
        byte c = (byte)(a + b);
        return c;
    }
}
```

167) https://www.codewars.com/kata/55c28f7304e3eaebef0000da
```java
import java.util.*;

     class Kata {
       public static List CreateList(int number)
       {
         List list = new ArrayList();

         for(int count = 1; count <= number; count++)
         {
           list.add(count);
         }

         return list;
       }
     }
```

168) https://www.codewars.com/kata/571ec274b1c8d4a61c0000c8
```javascript
function helloWorld (str){
var str = "Hello World!";
console.log(str);
}
```

169) https://www.codewars.com/kata/534ea96ebb17181947000ada
```javascript
function breakChocolate(n,m) {
  if((n === 0 || m === 0) || (n === 1 && m === 1)){
  return 0;
  } else {
   return (n * m) - 1;
   }
}
```
























