1) https://www.codewars.com/kata/convert-boolean-values-to-strings-yes-or-no/solutions/javascript
```javascript
function boolToWord( bool ){
  return bool ? 'Yes':'No';
}


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

3) https://www.codewars.com/kata/525f50e3b73515a6db000b83
```javascript
function createPhoneNumber(numbers){
  numbers.splice(0, 0, '(');
  numbers.splice(4, 0, ') ');
  numbers.splice(8, 0, '-');
  return numbers.join('');
}

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

6) https://www.codewars.com/kata/57a84137cf1fa5f9f80000d6
```javascript
function sumR(x) {
  let sum = 0;
  for(let i = 0; i < x.length; i++){
    sum = sum + x[i];
  }
  return sum;
}

7) https://www.codewars.com/kata/52af7bf41f5a1291a6000025
```javascript
function timeForMilkAndCookies(date){
  return date.getMonth() === 11 && date.getDate() === 24;
}

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

9) https://www.codewars.com/kata/5545f109004975ea66000086
```javascript
function isDivisible(n, x, y) {
if(n % x ===0 && n % y === 0 ) return true;
else return false;
}

10) https://www.codewars.com/kata/515e271a311df0350d00000f
```javascript
function squareSum(numbers){
  let sum = 0;
    for(let i = 0; i < numbers.length; i++){
      sum = sum + numbers[i]**2;
    }
  return sum;
}
