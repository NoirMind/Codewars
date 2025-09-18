# 7-kyu knowladge

## 1-chhi masala

["https://www.codewars.com/kata/54ff3102c1bad923760001f3/train/javascript"]

### question:
Return the number (count) of vowels in the given string.

We will consider a, e, i, o, u as vowels for this Kata (but not y).

The input string will only consist of lower case letters and/or spaces.

answer:
```
function getCount(str) {
  let vovel = ["a","e","i","o","u"]
  let resut = 0
  str.split("").map((item)=>{
    if(vovel.includes(item)){
      resut+=1
    }
  })
return resut
}
```