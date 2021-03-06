# 百日算法
记录每天一道算法题(第十天才开始记录..)

## week1
### w1-1
观察下面的规律，写一个函数accum
```js
accum("abcd");    // "A-Bb-Ccc-Dddd"
accum("RqaEzty"); // "R-Qq-Aaa-Eeee-Zzzzz-Tttttt-Yyyyyyy"
accum("cwAt");    // "C-Ww-Aaa-Tttt"
```
[answer](https://github.com/wty521/alg-days/blob/master/week1/w1-1.js)

### w1-2
写一个函数求数组的最大值和最小值
```js
highAndLow("1 2 3 4 5"); // return "5 1"
highAndLow("1 2 -3 4 5"); // return "5 -3"
highAndLow("1 9 3 4 -5"); // return "9 -5"
```
[answer](https://github.com/wty521/alg-days/blob/master/week1/w1-2.js)
### w1-3
写一个函数判断字符串中x的数量和o的数量是否相等（忽略大小写）：
```js
XO("ooxx") => true
XO("xooxx") => false
XO("ooxXm") => true
XO("zpzpzpp") => true // 没有x也没有o，所有相等，都为0
XO("zzoo") => false
```
[answer](https://github.com/wty521/alg-days/blob/master/week1/w1-3.js)

### w1-4
写一个函数判断一个数字是不是某个整数的平方。
```js
is_square (-1) # => false
is_square   0 # => true
is_square   3 # => false
is_square   4 # => true
is_square  25 # => true
is_square  26 # => false
```
[answer](https://github.com/wty521/alg-days/blob/master/week1/w1-4.js)

### w1-5
写一个函数，将字符串除了最后的四位，其他都变成#
```js
maskify("4556364607935616") == "############5616"
maskify("64607935616")      == "#######5616"
maskify("1")                == "1"
maskify("")                 == ""
maskify("Skippy")           == "##ippy"
maskify("Nananananananananananananananana Batman!") == "####################################man!"
```
[answer](https://github.com/wty521/alg-days/blob/master/week1/w1-5.js)

### w1-6
下面三角形的数列：

             1
          3     5
       7     9    11
   13    15    17    19
21    23    25    27    29
...
写一个函数，给定行的序号，然后求和：
```js
rowSumOddNumbers(1) // 1
rowSumOddNumbers(2) // 3+5=8
rowSumOddNumbers(3) // 7+9+11=27
rowSumOddNumbers(42) // 74088
```
[answer](https://github.com/wty521/alg-days/blob/master/week1/w1-6.js)

### w1-7
将数字的每一位求平方，然后组合成新的数字（注意：请返回一个数字）
```js
squareDigits(9119) // 811181
```
[answer](https://github.com/wty521/alg-days/blob/master/week1/w1-7.js)

## week2
### w2-1
写一个函数 solution，求比一个数字 n 小的所有 3 和 5 的整数倍数和。
比如 10，比它小的 3、5 整数倍数有： 3,5,6,9， 所以和为 23。 比如 16， 比它小的 3，5 整数倍数有： 3,5,6,9,10,12,15，所以和为 60（15只计算1次）
```js
solution(10) // 23
solution(16) // 60
```
[answer](https://github.com/wty521/alg-days/blob/master/week2/w2-1.js)

### w2-2 
写一个二分查找函数bsearch
A 是一个已排序的数组，x 是目标值。      
如果找到目标值，返回目标值在数组中的序号。 如果没有找到目标值，返回目标值应该被插入的位置 比如数组: A = 3,5,7,13,22,25
```js
bsearch(A, 5) // 1
bsearch(A, 13) // 3
bsearch(A, 4) // 1
bsearch(A, -1) // 0
bsearch(A, -10000) // 0
bsearch(A, 30) // 6
```
[answer](https://github.com/wty521/alg-days/blob/master/week2/w2-2.js)

### w2-3
在一个数组中大部分都是奇数(或偶数），只有1个可能是偶数（或奇数），写一个函数special找到这个不一样的值。
```js
special( [2, 4, 0, 100, 4, 11, 2602, 36] ) // 11 唯一的奇数
special( [160, 3, 1719, 19, 11, 13, -21] ) // 160 唯一的偶数
```
[answer](https://github.com/wty521/alg-days/blob/master/week2/w2-3.js)

### w2-4
写一个函数reverse反转一个数组A 
要求： 不可以使用Array.reverse 请不要创建新数组
```js
reverse([1,3,5,7]) // [7,5,3,1]
```
[answer](https://github.com/wty521/alg-days/blob/master/week2/w2-4.js)
### w2-5
定义数组的旋转操作rotate(A,amount)，让数尾部amount个元素移动到头部。
例如数组：A=[1,2,3,4,5,6,7]
```js
rotate(A,1) // [7,1,2,3,4,5,6]
rotate(A,2) // [6,7,1,2,3,4,5]
rotate(A,3) // [5,6,7,1,2,3,4]
```
以此类推     
[answer](https://github.com/wty521/alg-days/blob/master/week2/w2-5.js)
### w2-6
实现一个递归版本的reserve函数，反转一个数组     
[answer](https://github.com/wty521/alg-days/blob/master/week2/w2-6.js)

## week2
### w3-1
写一个函数flat展平一个数组
```js
flat([1,[2,'a',[5,6]],8]) // [1,2,'a',5,6,8]
```
[answer](https://github.com/wty521/alg-days/blob/master/week3/w3-1.js)


