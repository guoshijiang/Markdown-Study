# Markdown-Study
## 1.概述{#introduction}

Markdown是一种很简单的标记语言，它有很多优点，编写简单，容易学习，基本上花半个小时的时间就能学会。目前来看，支持Markdown语法的编辑器有很多,包括很多网站也支持了Markdown的文字录入。Markdown从写作到完成，导出格式随心所欲，你可以导出HTML格式的文件用来网站发布，也可以十分方便的导出PDF格式。 很多研发人员写文档时也会选用Markdown，简单而使用，难道你不心动吗，如果行动，就跟我一起来学习Markdown语法吧。

## 2.标题

> #### 2.1.标题的第一种为文字下方添加“=”和“-”
    代码：
    这是一个一级标题
    ============================
    这是一个二级标题
    --------------------------------------------------
    
>结果展示:
这是一个一级标题
============================
这是一个二级标题
-------------------------------------------------- 

> #### 2.1.标题的第二种为文字前面添加添加“#”
| markdown      | 对应的HTML标签 |
| ------------- |:------------:|
|#              |H1|
|##             |H2|
|###            |H3|
|####           |H4|
|#####          |H5|
|######         |H6|

> 结果展示:
#              H1
##             H2
###            H3
####           H4
#####          H5
######         H6

## 3.列表

> #### 3.1.无序列表
    代码：
    用到的符号*，+，- 
    * 列表1
    * 列表2
    * 列表3  
    + 列表1
    + 列表2
    + 列表3
    - 列表1
    - 列表2
    - 列表3
    
> 结果展示:   
* 列表1
* 列表2
* 列表3  
+ 列表1
+ 列表2
+ 列表3
- 列表1
- 列表2
- 列表3

> #### 3.2.有序列表
    代码：
    直接添加数字就可以形成
    1. Red
    2. Green
    3. Blue
    
> 结果展示:

1. Red 
2. Green
3. Blue

## 4.引用
> #### 4.1. 引用的多层嵌套
>> 区块引用可以嵌套（例如：引用内的引用），只要根据层次加上不同数量的 >：
    
    代码：
    >>> 250？
    >> 叫谁ne?
    > 您

> 结果展示:

>>> 250？

>> 叫谁ne?

> 您

> #### 4.2.引用其它要素
>> 引用的区块内也可以使用其他的 Markdown 语法，包括标题、列表、代码区块等：

    代码：
    > 1.   这是第一行列表项。
    > 2.   这是第二行列表项。
    > 
    > 给出一些例子代码：
    > 
    >     return shell_exec("echo $input | $markdown_script");

> 结果展示:

> 1.   这是第一行列表项。
> 2.   这是第二行列表项。
> 
> 给出一些例子代码：
> 
>     return shell_exec("echo $input | $markdown_script");

## 4.斜体与粗体
    代码：
    *斜体*或_斜体_
    **粗体**
    ***加粗斜体***
    ~~删除线~~
    
> 结果展示:

*斜体*或_斜体_
**粗体**
***加粗斜体***
~~删除线~~

## 5.表格
    代码
    | markdown      | 对应的HTML标签 |
    | ------------- |:------------:|
    |#              |H1|
    |##             |H2|
    |###            |H3|
    |####           |H4|
    |#####          |H5|
    |######         |H6|

> 结果展示:    
    
| markdown      | 对应的HTML标签 |
| ------------- |:------------:|
|#              |H1|
|##             |H2|
|###            |H3|
|####           |H4|
|#####          |H5|
|######         |H6|

## 6. 锚点和超链接
> #### 6.1.锚点
    代码：
    ## 1.概述{#introduction}
    跳转到[概述](#introduction)
    
> 结果展示: 

>>跳转到 [概述](#introduction)

> #### 6.1.超链接
>> ###### 6.1.1 行内式
    
    代码：
    [jiang_xinxing博客](http://blog.csdn.net/jiang_xinxing)
    [搜米域名网站源码](https://github.com/guoshijiang/soumi_yuming "搜米域名网站源码")
 
> 结果展示:

>>[jiang_xinxing博客](http://blog.csdn.net/jiang_xinxing)
  [搜米域名网站源码](https://github.com/guoshijiang/soumi_yuming "搜米域名网站源码")

>> ###### 6.1.2 参考式
    代码：
    网站[github.com][1]、
    [soumi_yuming][2]
    [我的博客][3]
    [plkingdom项目源码][2]
    [网站][]。
    [1]:https://github.com/guoshijiang/Markdown-Study
    [2]:https://github.com/guoshijiang/plkingdom "plkingdom"
    [3]:http://blog.csdn.net/jiang_xinxing "jiang_xinxing博客"
    [网站]:https://github.com/guoshijiang/soumi_yuming
    
> 结果展示:

>>网站[github.com][1]
  [soumi_yuming][2] 
  [我的博客][3]
  [plkingdom项目源码][2]
  [网站][]。
>>[1]:https://github.com/guoshijiang/Markdown-Study
  [2]:https://github.com/guoshijiang/plkingdom "plkingdom"
  [3]:http://blog.csdn.net/jiang_xinxing "jiang_xinxing博客"
  [网站]:https://github.com/guoshijiang/soumi_yuming

>> ###### 6.1.3 自动链接
    代码：
    <http://blog.csdn.net/jiang_xinxing/>
    <https://github.com/guoshijiang/Markdown-Study>
    
> 结果展示:

>><http://blog.csdn.net/jiang_xinxing/>
  <https://github.com/guoshijiang/Markdown-Study>


