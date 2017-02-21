# Markdown-Study
## 1.概述

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

  [jiang_xinxing博客](http://blog.csdn.net/jiang_xinxing)

  [搜米域名网站源码](https://github.com/guoshijiang/soumi_yuming "搜米域名网站源码")

>> ###### 6.1.2 参考式

    代码
    [Markdown-Study][1]
    [plkingdom][2] 
    [jiang_xinxing博客][3]
    [soumi_yuming][4]。
    [1]:https://github.com/guoshijiang/Markdown-Study "Markdown-Study"
    [2]:https://github.com/guoshijiang/plkingdom "plkingdom"
    [3]:http://blog.csdn.net/jiang_xinxing "jiang_xinxing博客"
    [4]:https://github.com/guoshijiang/soumi_yuming
    
> 结果展示:

  [Markdown-Study][1]
  
  [plkingdom][2] 
  
  [jiang_xinxing博客][3]
  
  [soumi_yuming][4]。
  
  [1]:https://github.com/guoshijiang/Markdown-Study "Markdown-Study"
  
  [2]:https://github.com/guoshijiang/plkingdom "plkingdom"
  
  [3]:http://blog.csdn.net/jiang_xinxing "jiang_xinxing博客"
  
  [4]:https://github.com/guoshijiang/soumi_yuming

>> ###### 6.1.3 自动链接
    代码：
    <http://blog.csdn.net/jiang_xinxing/>
    <https://github.com/guoshijiang/Markdown-Study>
    
> 结果展示:

  <http://blog.csdn.net/jiang_xinxing/>
  
  <https://github.com/guoshijiang/Markdown-Study>
  
## 7.流程图
    
    代码：
    flow
    st=>start: Start:>https://www.zybuluo.com
    io=>inputoutput: verification
    op=>operation: Your Operation
    cond=>condition: Yes or No?
    sub=>subroutine: Your Subroutine
    e=>end
    st->io->op->cond
    cond(yes)->e
    cond(no)->sub->io

## 8.分割线
    
    代码
    * * *
    ***
    *****
    - - -
    ---------------------------------------
> 结果展示:
 * * *
 ***
 *****
 - - -
 ---------------------------------------
 
## 9.代码

> 对于程序员来说这个功能是必不可少的，插入程序代码的方式有两种，一种是利用缩进(Tab), 另一种是利用"ESC键下面的"`code`"键"。

>> 语法说明：
   插入行内代码，即插入一个单词或者一句代码的情况，使用`code`这样的形式插入。
   插入多行代码，可以使用缩进或者“` code “`,具体看示例。

注意： 缩进式插入前方必须有空行
> #### 9.1. 行内式

    代码：
    C语言里的函数 `scanf()` 怎么使用？

结果展示：

C语言里的函数 `scanf()` 怎么使用？

> #### 9.2. 缩进式多行代码

>> 缩进 4 个空格或是 1 个制表符

   一个代码区块会一直持续到没有缩进的那一行（或是文件结尾）。

       代码：
        #include <stdio.h>
        int main(void)
        {
            printf("Hello world\n");
        }

结果展示：

    #include <stdio.h>
    int main(void)
    {
        printf("Hello world\n");
    }

> #### 9.3. 用六个`s`包裹多行代码

代码：

    ```
    #include <stdio.h>
    int main(void)
    {
        printf("Hello world\n");
    }
    、、、

结果展示：

        #include <stdio.h>
        int main(void)
        {
            printf("Hello world\n");
        }

> #### 9.4. HTML 原始码

在代码区块里面， & 、 < 和 > 会自动转成 HTML 实体，这样的方式让你非常容易使用 Markdown 插入范例用的 HTML 原始码，只需要复制贴上，剩下的 Markdown 都会帮你处理，例如：

代码：

第一个例子：

    <div class="footer">
       © 2004 Foo Corporation
    </div>

结果展示：
 <div class="footer">
    © 2004 Foo Corporation
 </div>
 
第二个例子：

    <table>
        <tr>
            <th rowspan="2">值班人员</th>
            <th>星期一</th>
            <th>星期二</th>
            <th>星期三</th>
        </tr>
        <tr>
            <td>李强</td>
            <td>张明</td>
            <td>王平</td>
        </tr>
    </table>
    
结果展示：
 <table>
     <tr>
            <th rowspan="2">值班人员</th>
            <th>星期一</th>
            <th>星期二</th>
            <th>星期三</th>
     </tr>
     <tr>
            <td>李强</td>
            <td>张明</td>
            <td>王平</td>
    </tr>
</table>

## 10. 插入图像

> #### 10.1. 行内式

语法说明：![图片Alt](图片地址 “图片Title”)

代码：

    图片1： 
    ![图片1](http://img.blog.csdn.net/20170117175958468?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvamlhbmdfeGlueGluZw==/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast "图片1")

结果展示：

图片1： 
    ![图片1](http://img.blog.csdn.net/20170117175958468?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvamlhbmdfeGlueGluZw==/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast "图片1")

> #### 10.2. 参考式
    代码：
    图片1：
    ![图片1][图片1]
    [图片1]:http://img.blog.csdn.net/20170117175958468?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvamlhbmdfeGlueGluZw==/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast  "图片1"

结果展示：
图片1：
![图片1][图片1]
[flower]:http://img.blog.csdn.net/20170117175958468?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvamlhbmdfeGlueGluZw==/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast  "图片1"


## 11. 内容目录

在段落中填写 [TOC] 以显示全文内容的目录结构。

## 12. 注脚
    
    代码：
    使用 Markdown[^1]可以效率的书写文档, 直接转换成 HTML[^2], 你可以使用 Leanote[^Le] 编辑器进行书写。
    [^1]:Markdown是一种纯文本标记语言
    [^2]:HyperText Markup Language 超文本标记语言
    [^Le]:开源笔记平台，支持Markdown和笔记直接发为博文




