
[Tail Swap](https://www.codewars.com/kata/5868812b15f0057e05000001)
```javascript
function tailSwap(arr) {
      const arr2 = arr.map(el => el.split(":"));
      const arr3 = arr2[0].concat(arr2[1]);
      const x = arr3[0] + ":" + arr3[3];
      const y = arr3[2] + ":" + arr3[1];
      return [x,y];
    }
```
[String ends with?](https://www.codewars.com/users/Anastasiia%20Paromova/completed_solutions)
```javascript
function solution(str, ending){
  return str.endsWith(ending);
}
```
[Divide and Conquer](https://www.codewars.com/kata/57eaec5608fed543d6000021)
```javascript
function digits(num){
let numArray = [];
	let sum = 0;
	let nums = num.toString().split('');
	for (let i = 0; i < nums.length; i++) {
    console.log(nums[i])
    for ( let index = i+1; index < nums.length; index++) {
      console.log(nums[index])
      numArray.push(Number(nums[i]) + Number(nums[index]))
    }
	}
return numArray
}
```