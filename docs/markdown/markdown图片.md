<!--
 * @Author: your name
 * @Date: 2021-04-01 15:37:38
 * @LastEditTime: 2021-04-01 20:58:02
 * @LastEditors: Please set LastEditors
 * @Description: In User Settings Edit
 * @FilePath: \blog\blog\docs\markdown\markdown图片.md
-->

## Markdown 图片

Markdown 图片语法格式如下：

    ![alt 属性文本](图片地址)

    ![alt 属性文本](图片地址 "可选标题")

* 开头一个感叹号 !
* 接着一个方括号，里面放上图片的替代文字
* 接着一个普通括号，里面放上图片的网址，最后还可以用引号包住并加上选择性的 'title' 属性的文字。

使用实例：

    ![桂梓学长 图标](../_media/logo.png ':size=50%')

显示结果如下：

<img src='../_media/logo.png' width=400px>

<!-- ![桂梓学长 图标](../_media/logo.png ':size=50%') -->

当然，你也可以像网址那样对图片网址使用变量:

    这个链接用 1 作为网址变量 [guizi][1].
    然后在文档的结尾为变量赋值（网址）

    [1]: ../_media/logo.png

显示结果如下：

![图片示例1](../_media/markdown图片_1.png)

Markdown 还没有办法指定图片的高度与宽度，如果你需要的话，你可以使用普通的`<img>`标签。

    <img src="../_media/logo.png" width="50%"> 

显示结果如下：

<img src='../_media/logo.png' width=400px>

<!-- <img src="../_media/logo.png" width="50%">  -->
