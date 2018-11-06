# javascript

## js数据类型
> 字符串 数字 布尔 数组 对象 null undefined

> 基本数据类型：undefined mull boolean string number 引用数据类型：Object Function Array Date RegExp

## js对象
> 属性和方法
```
 people.name="aa"; //属性
 people.name(); // 方法
```
## js函数
> 函数是由事件驱动的或者当它被调用时执行的可重复使用的代码块
```
function name(){
    // 执行的代码
}
```
## js运算符
> 运算符 = 用于赋值。  运算符 + 用于加值。
```
x=5; y=10;
z= x+y;
z= 15;
```
> 对带有字符串的+运算符 是将字符串拼接
```
x= '5'; y = 10;
z = x+y;
z = '510';
```
## js比较
> 比较和逻辑运算符用于测试 true 或 false
```
 == 等于 比较值
 === 等于 先比较类型 再比较值
 > 大于
 < 小于
 != 不等于
 >=
 <=
```
> 逻辑运算符
```
 &&  and
 ||  or
 !   not
```
> 三元运算符
```
a>b?a:b;  // a>b时 值为a 否则为b

```
## if else
> 常在写代码时，您总是需要为不同的决定来执行不同的动作。您可以在代码中使用条件语句来完成该任务
```
if (条件)
  {
  // 当条件为 true 时执行的代码
  }
else
  {
  // 当条件不为 true 时执行的代码
  }
```
> if... else if... else  使用 if....else if...else 语句来选择多个代码块之一来执行
```
if (条件 1)
  {
  // 当条件 1 为 true 时执行的代码
  }
else if (条件 2)
  {
  // 当条件 2 为 true 时执行的代码
  }
else
  {
  // 当条件 1 和 条件 2 都不为 true 时执行的代码
  }
```
## switch
> switch 语句用于基于不同的条件来执行不同的动作
```
switch(条件){
    case 条件1:  // 当条件与条件1 相等时
    // 执行代码
    break;
    case 条件2:  // 当条件与条件2 相等时
    //执行代码
    break;
    default :    // 当条件与条件1，2 都不相等时
    // 执行代码
}
```
## for 循环
> 循环可以将代码块执行指定的次数
```
for(var i=0;i<array.length;i++){
    //执行代码
}
```
> js支持不同类型的循环
```
for - 循环代码块一定的次数
for/in - 循环遍历对象的属性
while - 当指定的条件为 true 时循环指定的代码块
do/while - 同样当指定的条件为 true 时循环指定的代码块
```
> for in 示例
```
var person={fname:"John",lname:"Doe",age:25};

for (x in person)
  {
  txt=txt + person[x];
  }
  tet : "JohnDoe25"
```
> while 示例
```
while (i<5)
  {
  x=x + "The number is " + i + "<br>";
  i++;
  }
```
> break 跳出循环
```
for (i=0;i<10;i++)
  {
  if (i==3) break;
  x=x + i + "<br>";
  }
  0   1  2
```
