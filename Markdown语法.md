---

---

# Markdown语法

### 一、标题

示例：

        #  这是一级标题

        ... ...

        ######  这是六级标题

### 二、字体

加粗

        ****  文字左右各两个星号

斜体

        **  文字左右各一个星号

斜体加粗

        ***  文字左右各三个星号

删除线

        ~~  文字左右各两个波折线

### 三、引用

示例：

        >  在引用文字前加一个大于号，引用还可以嵌套

### 四、分割线

        三个或三个以上的"-"或者"*"都可以。

### 五、图片

语法：

        ![图片alt]（图片地址 ''图片title''）

        图片alt ：显示在图片下面的文字，相当于对图片内容的解释；

        图片title ：图片的标题，当鼠标移动到图片上时显示的内容，可加可不加。

示例：

        ![E:\Wireshark\20180925\图解三次握手](E:\Wireshark\20180925\图解三次握手.png)

### 六、超链接

语法：

        [超链接名]（超链接地址"超链接title"）

        title可加可不加

示例：

        [百度](http://www.baidu.com)

注：Markdown本身语法不支持打开链接，如果想打开链接需要使用html语言中的a标签代替

<a href="超链接地址" target="_blank">超链接名</a>

示例：

    <a href="https://www.baidu.com" target="_blank">百度</a>

### 七、列表

+ 无序列表

> 无序列表可以使用- + *任意一种

- 有序列表
1. 列表内容

2. 列表内容

3. 列表内容
* 列表嵌套

> 上一级和下一级之间敲三个空格即可

### 八、表格

        本程序里可以直接使用快捷键：Ctrl + T

### 九、代码

单行代码：代码之间用一反引号

        `代码内容`

代码块：代码之间用三个反引号，且两边的反引号单独占一行

```
test...
test...
test...
```

### 十、流程图

```graph BT
st=>start
op=>operation
cond=>condition:Yes or No?
e=>end
st->op->cond
cond(yes)->e
cond(no)->op
```


















