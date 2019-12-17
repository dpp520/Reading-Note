## JavaScript学习资源
[JavaScript-廖雪峰官网](https://www.liaoxuefeng.com/wiki/1022910821149312)

## 学习笔记
### 数据类型
#### null和undefined、对象、变量、字符串、布尔值
#### 数组
##### indexOf：与String类似，Array也可以通过indexOf()来搜索一个指定的元素的位置
```
var arr = [10, 20, '30', 'xyz'];
arr.indexOf(10); // 元素10的索引为0
arr.indexOf(20); // 元素20的索引为1
arr.indexOf(30); // 元素30没有找到，返回-1
arr.indexOf('30'); // 元素'30'的索引为2
```
##### slice：就是对应String的substring()版本，它截取Array的部分元素，然后返回一个新的Array
```
var arr = ['A', 'B', 'C', 'D', 'E', 'F', 'G'];
var aCopy = arr.slice();
aCopy; // ['A', 'B', 'C', 'D', 'E', 'F', 'G']
aCopy === arr; // false
```

#### Number
```
123; //整数123
0.456; //浮点数0.456
1.2345e3; //科学计数法表示1.2345x1000，等同于1234.5
-99; //负数
NaN; //NaN表示Not a Number，当无法计算结果时用NaN表示
Infinity; //Infinity表示无限大，当数值超过了JavaScript的Number所能表示的最大值时，就表示为Infinity
```
#### 比较运算符
```
注意NaN
NaN === NaN; // false  
isNaN(NaN); // true
注意浮点型 
1 / 3 === (1 - 2 / 3); // false 
Math.abs(1 / 3 - (1 - 2 / 3)) < 0.0000001; // true
```

## use strict
```
JavaScript在设计之初，为了方便初学者学习，并不强制要求用var申明变量。这个设计错误带来了严重的后果：如果一个变量没有通过var申明就被使用，那么该变量就自动被申明为全局变量。为了修补JavaScript这一严重设计缺陷，ECMA在后续规范中推出了strict模式，在strict模式下运行的JavaScript代码，强制通过var申明变量，未使用var申明变量就使用的，将导致运行错误。
```