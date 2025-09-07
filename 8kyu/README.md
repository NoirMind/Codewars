# i'm starting codewars :

### 1-question:
[https://www.codewars.com/kata/50654ddff44f800200000004/train/javascript]


### my answer

``` 
function multiply(a, b){
 return a * b
  
} 
```


### 2-question: 
[https://www.codewars.com/kata/53da3dbb4a5168369a0000fe/train/javascript]
### my answer :

```
function evenOrOdd(number) {
 return number % 2 == 0?"Even":"Odd"
}
```

### 3-question

[https://www.codewars.com/kata/5265326f5fda8eb1160004c8/train/javascript]

### my answer 

```
function numberToString(num) {
 return ""+num
}
```

### 4-question

[https://www.codewars.com/kata/55685cd7ad70877c23000102/train/javascript]

### my answer 

```
function makeNegative(num) {
 return num >0 ? num*(-1):num 
}
```

### 5-question
[https://www.codewars.com/kata/53369039d7ab3ac506000467/train/javascript]
### my answer

```
function boolToWord( bool ){
 return bool ? "Yes" : "No"
}
```

### 6-question
[https://www.codewars.com/kata/56dec885c54a926dcd001095/train/javascript]

### my answers
```
function opposite(number) {
  return number >0? number*(-1):Math.abs(number)
}
```

### 7-question
[https://www.codewars.com/kata/523b4ff7adca849afe000035/train/javascript]

### my answers

```
function greet(){
  return "hello world!"
}
```

### 8-question

[https://www.codewars.com/kata/56bc28ad5bdaeb48760009b0/train/javascript]

### my answer

```
function removeChar(str){
 return str.slice (1, -1);
};
```

### 9-question

[https://www.codewars.com/kata/544675c6f971f7399a000e79/train/javascript]

### my answer

```
const stringToNumber = function(str){
  let num = 1234
  return Number(str);
}

```

### 12-question

[https://www.codewars.com/kata/57a0556c7cb1f31ab3000ad7/train/javascript]

### my answer 

```
function makeUpperCase(str) {
  return str.toUpperCase();
}

```

### 13-question 

[https://www.codewars.com/kata/583710ccaa6717322c000105/train/javascript]

### my answer

```
function simpleMultiplication(number) {
    return number % 2 === 0 ? number * 8 : number * 9;
  }

```

### 14-question 

[https://www.codewars.com/kata/57a0885cbb9944e24c00008e/train/javascript]

### my answer

```
function removeExclamationMarks(s) {
  return s.replaceAll("!", "");
}

```

### 15-question

[https://www.codewars.com/kata/57a0e5c372292dd76d000d7e/train/javascript]

### my answer 

```
function repeatStr (n, s) {
  return s.repeat(n);
  }

  ```

  ### 16-question

  [https://www.codewars.com/kata/53ee5429ba190077850011d4/train/javascript]

  ### my answer

  ```

  function doubleInteger(i) {
  // i will be an integer. Double it and return it.
  return i * 2;
}

```

### 17-question 

[https://www.codewars.com/kata/55a70521798b14d4750000a4/train/javascript]

### my answer 

```

function greet(name){
  return `Hello, ${name} how are you doing today?`
}("Ryan")

```

### 18-question 

[https://www.codewars.com/kata/5a3fe3dde1ce0e8ed6000097/train/javascript]

### my answer 

```

function century(year) {
  return Math.ceil(year / 100)
}

```

### 19-question

[https://www.codewars.com/kata/58dbdccee5ee8fa2f9000058/train/javascript]

### my answer 

```

function spEng(sentence){
  let lower = sentence.toLowerCase();
  if(lower.includes ("english")){
    return true
  }
  else return false
}

```
### 20-question 

[https://www.codewars.com/kata/55d24f55d7dd296eb9000030/train/javascript]

### my answer 

```

var summation = function (num) {
  let sum = 0
  for (let i = 1; i <= num; i++){
    sum += i;
  }
  return sum
}

```

### 21-question

[C:\Users\user\Desktop\Aslan Web\Codewars\8kyu\README.md]

### my answer 

```

function basicOp(operation, value1, value2){
  if(operation === "+") return value1 + value2;
  if(operation === "-") return value1 - value2;
  if(operation === "*") return value1 * value2;
  if(operation === "/") return value1 / value2;
}

```

### 22-question

[https://www.codewars.com/kata/57eadb7ecd143f4c9c0000a3/train/javascript]

### my answer 

```

function abbrevName(name){
  let arr = name.split(" ")
  return arr [0][0].toUpperCase() + "." + arr [1][0].toUpperCase();
}

```

### 23-question 

[https://www.codewars.com/kata/5583090cbe83f4fd8c000051/train/javascript]

### my answer 

```

function digitize(n) {
  return String(n)
    .split('')
    .map(Number)
    .reverse();
}

```

### 24-question

[https://www.codewars.com/kata/54dba07f03e88a4cec000caf/train/javascript]

### my answer 

```

function Dog (breed) {
  this.breed = breed;
}

var snoopy = new Dog("Beagle");

snoopy.bark = function() {
  return "Woof";
};

var scoobydoo = new Dog("Great Dane");

scoobydoo.bark = function() {
  return "Woof"
};


```

### 25-question

[https://www.codewars.com/kata/53f9ee9f64b19d4b1d0001ed/train/javascript]

### my answer 

```

function Warrior(n) {
  let name = n;   

  this.name = function(newName) {
    if (newName) {
      name = newName;
    }
    return name;
  };
}

Warrior.prototype.toString = function() {
  return "Hi! my name's " + this.name();
};


var albert = new Warrior("Albert");
console.log(albert.toString()); 
albert.name("Boris");
console.log(albert.toString());

```