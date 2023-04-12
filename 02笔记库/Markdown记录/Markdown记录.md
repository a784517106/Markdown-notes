# *Markdown*记录

---

## 基础部分[^菜鸟教程]

[^菜鸟教程]: 学的不仅是技术，更是梦想！！！

---

### 快捷键

| Typora快捷键                                     |                    |              |                |
|:--------------------------------------------------:|:--------------------:|:--------------:|:----------------:|
| 快捷键                                           | 作用               | 快捷键       | 作用           |
| Ctrl+1                                           | 一阶标题           | Ctrl+B       | 字体加粗       |
| Ctrl+2                                           | 二阶标题           | Ctrl+I       | 字体倾斜       |
| Ctrl+3                                           | 三阶标题           | Ctrl+U       | 下划线         |
| Ctrl+4                                           | 四阶标题           | Ctrl+Home    | 返回Typora顶部 |
| Ctrl+5                                           | 五阶标题           | Ctrl+End     | 返回Typora底部 |
| Ctrl+6                                           | 六阶标题           | Ctrl+T       | 创建表格       |
| Ctrl+L                                           | 选中某句话         | Ctrl+K       | 创建超链接     |
| Ctrl+D                                           | 选中某个单词       | Ctrl+F       | 搜索           |
| Ctrl+E                                           | 选中相同格式的文字 | Ctrl+H       | 搜索并替换     |
| Alt+Shift+5                                      | 删除线             | Ctrl+Shift+I | 插入图片       |
| 注：一些实体符号需要在实体符号之前加""才能够显示 |                    |              |                |




---

### 列表

​	**无序列表**：破折号（-），星号（*）或加号（+）。**缩进**一个或多个项目以创建**嵌套列表**。

​	**有序列表**：数字。

1. 第一项：
    - 第一项嵌套的第一个元素
    - 第二项嵌套的第二个元素
2. 第二项：
    - 第二项嵌套的第一个元素
    - 第二项嵌套的第二个元素

---

### 区块  

1. 多层嵌套：
   > 最外层
   > > 第一层嵌套
   > > > 第二层嵌套
1. 区块中使用列表：
	> 区块中使用列表
	> 1. 第一项
	> 2. 第二项
	> + 第一项
	> + 第二项
	> + 第三项
3. 列表中添加区块
* 第一项
	> 菜鸟教程
	> 学的不仅是技术，更是梦想
* 第二项

---

### 代码

1. 代码条

​	`printf()`函数

如果**在代码中需要使用/`**，可以使用**````**或者转义符号**//** (注意这里需要**<font color='orange'>先转义再加粗</font>**)

 ``Use `code` in your Markdown file.``

这里**缩进会进入代码块**:（如果就是需要前面缩进怎么办呢？）
 	``Use `code` in your Markdown file.``

2. 代码块
	可以直接用4空格或者Tab，但是会出现部分代码在外面的bug，所以还是推荐用围栏法
```verilog
module mux2to1(out,a,b,sel)
  input a,b,sel;
  output out;

  wire out;
  assign out=(sel)?b:a;
endmodule
```

---

### 链接

1. 直接使用链接
   <http://www.runoob.com>

   **有的Markdown编辑器不使用<>也能实现**
   
   http://www.runoob.com

	点击显示：[菜鸟教程](http://www.runoob.com "学的不仅是技术，更是梦想！！！")

	**如果想禁用自动URL链接：**

   `http://www.runoob.com`（<font color='red'>**不太美观，有更好的方法吗？**</font>font>）
2. 使用变量进行链接（或者称为[引用样式链接](http://markdown.p2hp.com/basic-syntax/#reference-style-links)）

​		链接runoob是网址变量[RUNOOB][runoob]

​		缩写形式是：[runoob][]

​		<font color='red'>**这样写的好处是在多处进行引用时不用频繁地复制地址**</font>

[runoob]:http://www.runoob.com/

​		**HTML格式**：<a href="https://en.wikipedia.org/wiki/Hobbit#Lifestyle" title="Hobbit lifestyles">hobbit-hole</a>

***

### 图片

1. 只添加图片

   直接添加（可以添加标题）
   
   注意添加标题时一定要<font color='red'>**注意逗号是不是英文的**</font>

![费城的魔法花园。 这个地方真酷！](https://d33wubrfki0l68.cloudfront.net/eab45e25bb79970178fab7a2d10cba0209372a59/94d9e/assets/images/philly-magic-garden.jpg "Philadelphia's Magic Gardens")



![RUNOOB 图标](http://static.runoob.com/images/runoob-logo.png "RUNOOB")

2. 图片指向链接（<font color='red'>**该功能不确定有没有实现**</font>font>）

   [![沙漠中的一块老石头](Markdown%E8%AE%B0%E5%BD%95.assets/shiprock.jpg "Shiprock, New Mexico by Beau Rogers")] (https://www.baidu.com)

	在**路径或URL后面添加“ ”**可以**提供图片标题**，但是在**指向的网页链接**后面加是不可以的
	
	
	
	具体可以查询[Markdown中文网](http://markdown.p2hp.com/basic-syntax/#linking-images "链接图像")的技术手册



```flow
st=>start: Start:>http://alfred-sun.github.io
io=>inputoutput: verification
op=>operation: Your Operation
cond=>condition: Yes or No?
sub=>subroutine: Your Subroutine
e=>end:>https://github.com/adrai/flowchart.js
 
st->io->op->cond
cond(yes)->e
cond(no)->sub->io
```
