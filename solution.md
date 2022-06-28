## Return Negative

```js
const makeNegative(num){
if (num < 0) {
  return num
} else if (num > 0){
  return num * (-1)
} else {
return 0
}
}
```

## Sum of Positive

```js
function positiveSum(arr) {
  let sum = 0
  for (let i = 0; i < arr.length; i++) {
    sum += arr[i] > 0 ? arr[i] : 0
  }
  return sum
}
```

## Function 2

```js
function square(num) {
  return Math.pow(num, 2)
}
```

## Sum Arrays

```js
function sum(numbers) {
  let sum = 0
  for (i = 0; i < numbers.length; i++) {
    sum += numbers[i]
  }
  return sum
}
```

## Reversed Strings

```js
function solution(str) {
  let reverseString = ''
  for (let i = str.length - 1; i >= 0; i--) {
    reverseString += str[i]
  }
  return reverseString
}
```
