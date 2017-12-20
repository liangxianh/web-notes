### ECMAScript基本概念

#### 注意点
1. 标识符区分大小写
2. 标识符只能以_或者$开始
3. 标识符不能是保留字，也不能是关键字
4. 标识符的惯例命名格式是采用驼峰命名法
5. 注释方式
> 单行： ```//这是注释```

> 多行：```/****这是注释***/```

6. 严格模式限制 ```"use strict";```
7. 推荐语句以分号结尾，代码块推荐尽量包裹
8. 变量是松散类型的，也就是可以存储任何类型的值

#### 数据类型
> 5中简单数据类型： ```String , Number, Undefine, Null, Boolean```, 1种复杂数据类型 ```Object```

> 使用```typeof```检测变量的数据类型

> Boolean类型的字面值，true和false，是区分大小写的，True和False并不是boolean类型，他们只是标识符

> 在if判断语句中, 空字符串，数字0，undefined，null都是被转换为false

> ```NaN```，标识一个不是数值的数，它和任何数据类型的值都不相等， 存在```isNaN()```用来检测返回值是不是一个NaN

#### 操作符
> 相等和全等（== 和 ===), 全等要求数据类型也要相同

> break和countinue 用于控制循环语句执行， ```break;```完全跳出循环;```countinue;```仅仅是跳出此次循环

#### 函数
> 函数参数可通过```arguments```来获取，它是一个类似数组的值，但不是数组

> 没有函数重载， java语言中函数方法可命名相同，参数不同，都能生效；但是ecmascript不行，只会替换覆盖；
