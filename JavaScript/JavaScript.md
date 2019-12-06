### JavaScript学习资源
[JavaScript-廖雪峰官网](https://www.liaoxuefeng.com/wiki/1022910821149312)

### 学习笔记
#### 数据类型
##### null和undefined、数组、对象、变量、字符串、布尔值
##### Number
```
123; //整数123
0.456; //浮点数0.456
1.2345e3; //科学计数法表示1.2345x1000，等同于1234.5
-99; //负数
NaN; //NaN表示Not a Number，当无法计算结果时用NaN表示
Infinity; //Infinity表示无限大，当数值超过了JavaScript的Number所能表示的最大值时，就表示为Infinity
```
##### 比较运算符
```
注意NaN
NaN === NaN; // false  
isNaN(NaN); // true
注意浮点型 
1 / 3 === (1 - 2 / 3); // false 
Math.abs(1 / 3 - (1 - 2 / 3)) < 0.0000001; // true
```

### use strict
```

```