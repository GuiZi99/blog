<!--
 * @Author: your name
 * @Date: 2021-04-01 15:28:24
 * @LastEditTime: 2021-04-01 15:35:26
 * @LastEditors: Please set LastEditors
 * @Description: In User Settings Edit
 * @FilePath: \blog\blog\docs\markdown\markdown链接.md
-->

## Markdown 链接

链接使用方法如下：

    [链接名称](链接地址)

    或者

    <链接地址>

例如：

    这是一个链接 [桂梓学长](https://github.com/GuiZi99/blog)

显示结果如下：

这是一个链接 [桂梓学长](https://github.com/GuiZi99/blog)

直接使用链接地址：

    <https://github.com/GuiZi99/blog>

显示结果如下：

<https://github.com/GuiZi99/blog>

### 高级链接

我们可以通过变量来设置一个链接，变量赋值在文档末尾进行：

    这个链接用 1 作为网址变量 [Google][1]
    这个链接用 guizi 作为网址变量 [guizi][guizi]
    然后在文档的结尾为变量赋值（网址）
    
      [1]: http://www.google.com/
      [guizi]: https://github.com/GuiZi99/blog

显示结果如下：

![链接示例1](../_media/markdown链接_1.png)