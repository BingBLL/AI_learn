# AI_learning

## Markdown 学习 [教程](https://www.runoob.com/markdown/md-tutorial.html)

### 文本格式
**This is bold text**    _This text is italicized_    ~~This was mistaken text~~ **This text is _extremely_ important** ***All this text is important*** \
This is a <sub>subscript</sub> text  This is a <sup>superscript</sup> text This is an <ins>underlined</ins> text
### 引用文本
> Text that is a quote
### 引用代码
Use `git status` to list all new or modified files that haven't yet been committed.
#### 围栏代码块
````
```
Look! You can see my backticks.
```
````
#### 语法高亮
```ruby
require 'redcarpet'
markdown = Redcarpet.new("Hello World!")
puts markdown.to_html
```
### 支持的颜色和模型
The background color is `#ffffff` for light mode and `#000000` for dark mode.
### 链接 
This site was built using [GitHub Pages](https://pages.github.com/).
### 图片
![Screenshot of a comment on a GitHub issue showing an image, added in the Markdown, of an Octocat smiling and raising a tentacle.](https://myoctocat.com/assets/images/base-octocat.svg)
### 列表
- George Washington
* John Adams
+ Thomas Jefferson

1. James Madison
2. James Monroe
3. John Quincy Adams

1. First list item
   - First nested list item
     - Second nested list item

## 数学基础
### [线性代数教程](https://www.bilibili.com/video/BV1ys411472E/)
#### 向量究竟是什么？
向量是空间中的箭头。 向量是有序数字的列表。\
向量加法和向量乘法： 线性代数每一个主题都是围绕两种运算。\
向量加法的定义差不多是线性代数中唯一允许向量离开原点的情形。\
(线性代数给物理学家和计算机图形程序员提供了一种语言，让他们通过计算机处理的数字来描述并操作空间。)

### [概率论与数理统计教程](https://zh.khanacademy.org/math/statistics-probability)
#### 分析一个分类变量
1. 数据集中的个体、变量和分类变量
当有人说起数据集中的个体时他们并不一定意味着必须是人，他们可以是事物。名字更像是一个标识符。有两个以上类别的变量是分类变量，并不是某种类型的可变数字。可变的数字是定量的变量，不是一个类别。\
(1) 个体是数据集里形容的人或是东西。
(2) 变量是我们可以观察到的个体的特性。
(3) 分类数据是分类或是标签，定量变数是数值。\
中位数：就是最中间的那个数字。 中点数：最高分数加最低分数除以2。

## [Python基础教程](https://www.runoob.com/python3/python3-tutorial.html)
### 1. 基本语法
### 2. 基本数据类型 
* Number（数字）
  - Python可以同时为多个变量赋值，如a, b = 1, 2。
  - 一个变量可以通过赋值指向不同类型的对象。
  - 数值的除法包含两个运算符：/ 返回一个浮点数，// 返回一个整数。
  - 在混合计算时，Python会把整型转换成为浮点数。
* String（字符串）
  - 反斜杠可以用来转义，使用r可以让反斜杠不发生转义。
  - 字符串可以用+运算符连接在一起，用*运算符重复。
  - Python中的字符串有两种索引方式，从左往右以0开始，从右往左以-1开始。
  - Python中的字符串不能改变。  
* bool（布尔类型）
  - 布尔类型只有两个值：True 和 False。
  - bool 是 int 的子类，因此布尔值可以被看作整数来使用，其中 True 等价于 1。
  - 布尔类型可以和其他数据类型进行比较，比如数字、字符串等。在比较时，Python 会将 True 视为 
           1，False 视为 0
  - 布尔类型可以和逻辑运算符一起使用，包括 and、or 和 not。这些运算符可以用来组合多个布尔表 
          达式，生成一个新的布尔值。
* List（列表）
  - 列表写在方括号之间，元素用逗号隔开。
  - 和字符串一样，列表可以被索引和切片。
  - 列表可以使用 + 操作符进行拼接。
  - `列表中的元素是可以改变的`   
* Tuple（元组）
  - 与字符串一样，元组的元素不能修改。
  - 元组也可以被索引和切片，方法一样。
  - 注意构造包含 0 或 1 个元素的元组的特殊语法规则。
  - 元组也可以使用 + 操作符进行拼接。
* Set（集合）
Python 中的集合（Set）是一种无序、可变的数据类型，用于存储唯一的元素。集合中的元素不会重复，并且可以进行交集、并集、差集等常见的集合操作。在 Python 中，集合使用大括号 {} 表示，元素之间用逗号 , 分隔。
另外，也可以使用 set() 函数创建集合。
注意：创建一个空集合必须用 set() 而不是 { }，因为 { } 是用来创建一个空字典。
* Dictionary（字典）
字典（dictionary）是Python中另一个非常有用的内置数据类型。列表是有序的对象集合，字典是无序的对象集合。两者之间的区别在于：字典当中的元素是通过键来存取的，而不是通过偏移存取。
字典是一种映射类型，字典用 { } 标识，它是一个无序的 键(key) : 值(value) 的集合。键(key)必须使用不可变类型。在同一个字典中，键(key)必须是唯一的。
  - 字典是一种映射类型，它的元素是键值对。
  - 字典的关键字必须为不可变类型，且不能重复。
  - 创建空字典使用 { }。
* bytes 类型 
在 Python3 中，bytes 类型表示的是不可变的二进制序列（byte sequence）。与字符串类型不同的是，bytes 类型中的元素是整数值（0 到 255 之间的整数），而不是 Unicode 字符。bytes 类型通常用于处理二进制数据，比如图像文件、音频文件、视频文件等等。在网络编程中，也经常使用 bytes 类型来传输二进制数据。创建 bytes 对象的方式有多种，最常见的方式是使用 b 前缀：
此外，也可以使用 bytes() 函数将其他类型的对象转换为 bytes 类型。bytes() 函数的第一个参数是要转换的对象，第二个参数是编码方式，如果省略第二个参数，则默认使用 UTF-8 编码。
* **注意:**
  - 不可变数据（3 个）：Number（数字）、String（字符串）、Tuple（元组）；
  - 可变数据（3 个）：List（列表）、Dictionary（字典）、Set（集合）。
  
### 数据类型转换
Python 数据类型转换可以分为两种：
1. 隐式类型转换 - 自动完成 \
在隐式类型转换中，Python 会自动将一种数据类型转换为另一种数据类型，不需要我们去干预。
2. 显式类型转换 - 需要使用类型函数来转换 \
在显式类型转换中，用户将对象的数据类型转换为所需的数据类型。 我们使用 int()、float()、str() 等预定义函数来执行显式类型转换。

### Python3 注释
在 Python3 中，注释不会影响程序的执行，但是会使代码更易于阅读和理解。 \
Python 中的注释有单行注释和多行注释。 
1. Python 中单行注释以 # 开头
2. 多行注释  
在 Python中，多行字符串（由三个单引号 ''' 或三个双引号 """ 包围的文本块）在某些情况下可以被视为一种实现多行注释的技巧。

**注意：** 在 Python 中，多行注释是由三个单引号 ''' 或三个双引号 """ 来定义的，而且这种注释方式并不能嵌套使用。

### Python3 运算符
* Python 算术运算符

|运算符|描述|实例|
|----|----|----|
|+|加 - 两个对象相加|a + b 输出结果 31|
|-|减 - 得到负数或是一个数减去另一个数|a - b 输出结果 -11|
|*|乘 - 两个数相乘或是返回一个被重复若干次的字符串|a * b 输出结果 210|
|/|除 - x 除以 y|b / a 输出结果 2.1|
|%|取模 - 返回除法的余数|b % a 输出结果 1|
|**|幂 - 返回x的y次幂|a**b 为10的21次方|
|//|取整除 - 往小的方向取整数|``` >>> 9//2  4     >>> -9//2    -5 ```|

* Python 比较运算符

|运算符|描述|实例|
|----|----|----|
|==|等于 - 比较对象是否相等|(a == b) 返回 False。|
|!=|不等于 - 比较两个对象是否不相等|(a != b) 返回 True。|
|>|大于 - 返回x是否大于y|(a > b) 返回 False。|
|<|小于 - 返回x是否小于y。所有比较运算符返回1表示真，返回0表示假。这分别与特殊的变量True和False等价。注意，这些变量名的大写。|(a < b) 返回 True。|
|>=|大于等于 - 返回x是否大于等于y。| (a >= b) 返回 False。|
|<=|小于等于 - 返回x是否小于等于y。|(a <= b) 返回 True。|

* Python 赋值运算符

|运算符|描述|实例|
|----|----|----|
|=|简单的赋值运算符|c = a + b 将 a + b 的运算结果赋值为 c|
|+=|加法赋值运算符|c += a 等效于 c = c + a|
|-=|减法赋值运算符|c -= a 等效于 c = c - a|
|*=|乘法赋值运算符|c *= a 等效于 c = c * a|
|/=	|除法赋值运算符|c /= a 等效于 c = c / a|
|%=|取模赋值运算符|c %= a 等效于 c = c % a|
|**=|幂赋值运算符|c **= a 等效于 c = c ** a|
|//=|取整除赋值运算符|c //= a 等效于 c = c // a|
|:=|海象运算符，这个运算符的主要目的是在表达式中同时进行赋值和返回赋值的值。Python3.8 版本新增运算符。|在这个示例中，赋值表达式可以避免调用 len() 两次:  ```if (n := len(a)) > 10: print(f"List is too long ({n} elements, expected <= 10)")```|

* Python 位运算符

|运算符|描述|实例|
|----|----|----|
|&|按位与运算符：参与运算的两个值,如果两个相应位都为1,则该位的结果为1,否则为0。|(a & b) 输出结果 12 ，二进制解释： 0000 1100|
|\||按位或运算符：只要对应的二个二进位有一个为1时，结果位就为1。| (a\|b)输出结果 61 ，二进制解释： 0011 1101|
|^|按位异或运算符：当两对应的二进位相异时，结果为1。|(a ^ b) 输出结果 49 ，二进制解释： 0011 0001|
|~|按位取反运算符：对数据的每个二进制位取反,即把1变为0,把0变为1。~x 类似于 -x-1|(~a ) 输出结果 -61 ，二进制解释： 1100 0011， 在一个有符号二进制数的补码形式。|
|<<|左移动运算符：运算数的各二进位全部左移若干位，由"<<"右边的数指定移动的位数，高位丢弃，低位补0。|a << 2 输出结果 240 ，二进制解释： 1111 0000|
|>>|右移动运算符：把">>"左边的运算数的各二进位全部右移若干位，">>"右边的数指定移动的位数|a >> 2 输出结果 15 ，二进制解释： 0000 1111|

* Python逻辑运算符

|运算符|逻辑表达式|描述|实例|
|----|----|----|----|
|and|x and y|布尔"与" - 如果 x 为 False，x and y 返回 x 的值，否则返回 y 的计算值。|(a and b) 返回 20。|
|or|x or y|布尔"或" - 如果 x 是 True，它返回 x 的值，否则它返回 y 的计算值。|(a or b) 返回 10。|
|not|not x|布尔"非" - 如果 x 为 True，返回 False 。如果 x 为 False，它返回 True。|not(a and b) 返回 False|

* Python成员运算符

|运算符|描述|实例|
|----|----|----|
|in|如果在指定的序列中找到值返回 True，否则返回 False。|x 在 y 序列中 , 如果 x 在 y 序列中返回 True。|
|not in	|如果在指定的序列中没有找到值返回 True，否则返回 False。|x 不在 y 序列中 , 如果 x 不在 y 序列中返回 True。|

* Python身份运算符

|运算符|描述|实例|
|----|----|----|
|is|is 是判断两个标识符是不是引用自一个对象|x is y, 类似 id(x) == id(y) , 如果引用的是同一个对象则返回 True，否则返回 False|
|is not|is not 是判断两个标识符是不是引用自不同对象|x is not y ， 类似 id(x) != id(y)。如果引用的不是同一个对象则返回结果 True，否则返回 False。|

**注：**  ```id()``` 函数用于获取对象内存地址。

* Python运算符优先级

|运算符|描述|
|----|----|
| ```(expressions...), [expressions...], {key: value...}, {expressions...}``` | 圆括号的表达式 |
|```x[index], x[index:index], x(arguments...), x.attribute```|读取，切片，调用，属性引用|
|await x|await 表达式|
|**|乘方(指数)|
|+x, -x, ~x|正，负，按位非 NOT|
|*, @, /, //, %|乘，矩阵乘，除，整除，取余|
|+, -|加和减|
|<<, >>|移位|
|&|按位与 AND|
|^|按位异或 XOR|
|\||按位或 OR|
|in,not in, is,is not, <, <=, >, >=, !=, ==|比较运算，包括成员检测和标识号检测|
|not x|逻辑非 NOT|
|and|逻辑与 AND|
|or|逻辑或 OR|
|if -- else|条件表达式|
|lambda|lambda 表达式|
|:=|赋值表达式|

### 条件控制
### 循环语句
### 推导式
### 迭代器和生成器










   

      









