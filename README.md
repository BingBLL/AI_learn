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
   

      









