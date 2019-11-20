# Exercises: JavaScript loops

Paste your answers into this file.

<br>

## Print every number from 0 to 10

```
ANSWER HERE

for(i=0;i<11;i++){
    console.log(i);
}
```

<br>

## Print every number from 10 to 0

```
ANSWER HERE
var arr= [];
for(i=0;i<11;i++){
    arr.unshift(i);
}
console.log(arr);
```

<br>

## Print every number from 4 to -16

```
ANSWER HERE
var arr= [];
for(i=-16;i<5;i++){
    arr.unshift(i);
}
console.log(arr);
```

<br>

## Print every fifth number from 8 to 41

```
ANSWER HERE
```

<br>

## The classic Fizzbuzz Program

For every `number` between 1 and 100...

If the `number` is evenly divisible by 3, print "Fizz"

If the `number` is evenly divisible by 5, print "Buzz"

If the `number` is evenly divisible by 3 AND evenly divisible by 5, print "Fizzbuzz"


```
ANSWER HERE

var arr =[];
for (i=0;i<100;i++){
  arr.push(i+1);
  if(arr[i]%3 == 0){
    console.log('fizz');
  } 
  if(arr[i]%5 == 0){
    console.log('buzz');
  }
  if(arr[i]%3 == 0 && arr[i]%5 == 0){
    console.log('fizzbuzz');
  }
}

```

<br>


## The even/odd reporter

Write a for loop that will iterate from 0 to 20. For each iteration, it will check if the current number is even or odd, and report that to the screen (e.g. "2 is even").

```
ANSWER HERE


```

<br>

## Multiplication Tables

Write a for loop that will iterate from 0 to 10. For each iteration of the for loop, it will multiply the number by 9 and log the result (e.g. "2 * 9 = 18").

Bonus: Use a nested for loop to show the tables for every multiplier from 1 to 10 (100 results total).


```
ANSWER HERE


```

<br>


