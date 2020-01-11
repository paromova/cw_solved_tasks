[Remove First and Last Character Part Two](https://www.codewars.com/kata/570597e258b58f6edc00230d)
```javascript
function array(arr){
  const newArr = arr.split(",");
  return newArr.length<3 ? null : newArr.slice(1, newArr.length-1).toString().replace(/,/gi," ");
}
```
[Reversed Strings](https://www.codewars.com/kata/5168bb5dfe9a00b126000018)
```javascript
function solution(str){
  let reverse = [];
  for(let i = 0; i<str.length; i++){
  reverse.unshift(str[i]);
  }
  return reverse.join("");
}
```