
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
	for (let i = 0; i < nums.length; i++){
    console.log(nums[i]);
    for ( let index = i+1; index < nums.length; index++){
      console.log(nums[index]);
      numArray.push(Number(nums[i]) + Number(nums[index]));
    };
	}
return numArray
}
```
[Credit Card Mask](https://www.codewars.com/kata/5412509bd436bd33920011bc)
```javascript
function maskify(cc) {
let hidden = "";
if (cc.length <=4){return cc;
} else {
for(let i =0; i<cc.length - 4;i++){
hidden += cc[cc.length-5-i]="#";
}
}
return hidden + cc.substring(cc.length -4);
}
```
[Breaking chocolate problem](https://www.codewars.com/kata/534ea96ebb17181947000ada)
```javascript
function breakChocolate(n,m) {
  if(n<=0 || m<=0) {
  return 0;
  }
  return n*m-1;
}
```
[Sum of angles](https://www.codewars.com/kata/5a03b3f6a1c9040084001765)
```javascript
function angle(n) {
return 180 * (n - 2);
}
```
[Discover The Original Price](https://www.codewars.com/kata/552564a82142d701f5001228)
```javascript
function discoverOriginalPrice(discountedPrice, salePercentage){
return Math.floor((discountedPrice / (1 -salePercentage/ 100)) * 100)/100;
}
```
[Return the closest number multiple of 10](https://www.codewars.com/kata/58249d08b81f70a2fc0001a4)
```javascript
const closestMultiple10 = num => {
  let c = num/10;
  let d = Math.round(c);
  return d*10;
};
```
[Century From Year](https://www.codewars.com/kata/5a3fe3dde1ce0e8ed6000097)
```javascript
function century(year) {
  return (year % 100 === 0) ? year/100 : Math.ceil(year/100);
}
```
[How many times should I go?](https://www.codewars.com/kata/57efcb78e77282f4790003d8)
```javascript
function howManyTimes(annualPrice, individualPrice) {
 let time = annualPrice/ individualPrice;
 return Math.ceil(time);
}
```