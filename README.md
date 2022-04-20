# 此仓库的作用

## 一、用C++练习数据结构算法

## 二、MarkDown语法练习

### 1.标题

示例：

```
   # 这是一级标题
   ## 这是二级标题
   ### 这是三级标题
   #### 这是四级标题
   ##### 这是五级标题
   ###### 这是六级标题
```
效果如下：

# 这是一级标题
## 这是二级标题
### 这是三级标题
#### 这是四级标题
##### 这是五级标题
###### 这是六级标题
### 2.字体

* 加粗

要加粗的文字左右分别用两个*号包起来

* 斜体

要倾斜的文字左右分别用一个*号包起来

* 斜体加粗

要倾斜和加粗的文字左右分别用三个*号包起来

* 删除线

要加删除线的文字左右分别用两个~~号包起来

示例：
```
   **这是加粗的文字**
   *这是倾斜的文字*`
   ***这是斜体加粗的文字***
   ~~这是加删除线的文字~~
```

效果如下：

**这是加粗的文字**

*这是倾斜的文字*

***这是斜体加粗的文字***

~~这是加删除线的文字~~

### 3.引用

在引用的文字前加>即可。引用也可以嵌套，如加两个>>三个>>>

n个...

示例：

```
   >这是引用的内容
   >>这是引用的内容
   >>>>>>>>>>这是引用的内容
```
>这是引用的内容
>>这是引用的内容
>>>>>>>>>>这是引用的内容

### 4.分割线

三个或者三个以上的 - 或者 * 都可以。

示例：

```
   ---
   ----
   ***
   *****
```

效果如下：

可以看到，显示效果是一样的。

---
----
***
*****

### 5.图片

语法：

```
   ![图片alt](图片地址 ''图片title'')

图片alt就是显示在图片下面的文字，相当于对图片内容的解释。
图片title是图片的标题，当鼠标移到图片上时显示的内容。title可加可不加
```

示例：
```
   ![image.jpg](https://s2.loli.net/2022/04/20/FqNO2ZlDofgjuV6.jpg)
```

效果如下：

![image.jpg](https://s2.loli.net/2022/04/20/FqNO2ZlDofgjuV6.jpg "alfa romeo 24周冠宇战车")

### 6.超链接

语法：
```
[超链接名](超链接地址 "超链接title")
title可加可不加
```

示例：
```
[简书](http://jianshu.com)
[百度](http://baidu.com)
```

效果如下：

[简书](http://jianshu.com)
[百度](http://baidu.com)

### 7.列表

#### 无序列表

语法：

无序列表用 - + * 任何一种都可以

```
- 列表内容
+ 列表内容
* 列表内容

注意：- + * 跟内容之间都要有一个空格
```

效果如下：

- 列表内容
+ 列表内容
* 列表内容

#### 有序列表

语法：

数字加点

```
1. 列表内容
2. 列表内容
3. 列表内容

注意：序号跟内容之间要有空格
```

效果如下：

1. 列表内容
2. 列表内容
3. 列表内容

#### 列表嵌套

上一级和下一级之间敲三个空格即可

* 一级无序列表内容
   * 二级无序列表内容
   * 二级无序列表内容
   * 二级无序列表内容

- 一级无序列表内容
   - 二级有序列表内容
   - 二级有序列表内容
   - 二级有序列表内容
   
+ 一级有序列表内容
   + 二级无序列表内容
   + 二级无序列表内容
   + 二级无序列表内容

1. 一级有序列表内容
   1. 二级有序列表内容
   2. 二级有序列表内容
   3. 二级有序列表内容

### 8.表格

语法：

```
   表头|表头|表头
   ---|:--:|---:
   内容|内容|内容
   内容|内容|内容

   第二行分割表头和内容。
   - 有一个就行，为了对齐，多加了几个
   文字默认居左
   -两边加：表示文字居中
   -右边加：表示文字居右
   注：原生的语法两边都要用 | 包起来。此处省略
```

示例：

```
   姓名|技能|排行
   --|:--:|--:
   刘备|哭|大哥
   关羽|打|二哥
   张飞|骂|三弟
```

效果如下：

姓名|技能|排行
--|:--:|--:
刘备|哭|大哥
关羽|打|二哥
张飞|骂|三弟


### 9.代码
语法：
单行代码：代码之间分别用一个反引号包起来

```
    `代码内容`
```

代码块：代码之间分别用三个反引号包起来，且两边的反引号单独占一行

```
   (```)
     代码...
     代码...
     代码...
   (```)
   注：为了防止转译，前后三个反引号处加了小括号，实际是没有的。这里只是用来演示，实际中去掉两边小括号即可。
```

示例：

单行代码

```
`create database hero;`
```

代码块

```
(```)
    int main(){
        printf("hello world");
        return 0;
    }
(```)
```

效果如下：

单行代码

`create database hero;`

代码块

 ```
    int main(){
        printf("hello world");
        return 0;
    }
```

### 10.流程图

```
```flow
st=>start: 开始
op=>operation: My Operation
cond=>condition: Yes or No?
e=>end
st->op->cond
cond(yes)->e
cond(no)->op
&```
```

效果如下：

st=>start: 开始
op=>operation: My Operation
cond=>condition: Yes or No?
e=>end
st->op->cond
cond(yes)->e
cond(no)->op
&```