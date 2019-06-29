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

something to do