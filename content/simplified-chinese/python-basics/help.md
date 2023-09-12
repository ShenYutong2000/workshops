---
title: "求助, 我有困难!"
description: "Setting up headphones"
date: 2019-07-23T11:45:38-07:00
weight: 12
prereq: "None"
difficulty: "Beginner"
draft: false
---
##### 别担心！看看以下的信息是否有帮助，如果没有，随时联系我们之一，我们会提供更多帮助。

1.  缩进在Python中非常重要。在代码中要小心空格和Tab符号，因为缩进错误有时可能很难发现。

    ![IndentationError: expected an indented block](../img/screenshot-indentationerror.png)

    但好的一方面是，严格的格式使Python代码非常干净和有组织。你的所有变量和函数是否都按照指示正确缩进了吗？
2.  SyntaxError: 无效的语法
    验证你的关键字是否拼写正确，以及是否遵循了定义的结构。

3.  IndentationError: 意外的缩进
    如果看到这个错误，请检查缩进。

4.  NameError: 全局名称\'\-\--\'未定义
    在函数内定义的变量只能在函数内部使用。如果尝试在另一个函数中使用来自一个函数的变量，将收到此错误消息。

    要使信息可用于其他函数，可以使用`return`语句将其传递出一个函数，你可以将它分配给一个变量。然后，可以使用参数将其传递到另一个函数。有关详细解释，请阅读函数教程链接。

5.  无法识别错误：拼写错误？
    通常在关键字拼写错误时会收到此错误消息。检查所有的关键字。
6.  TypeError: 无法隐式将'int'对象转换为str
    请确保你没有尝试在字符串操作中使用整数（无法将字符串与整数连接起来。必须首先将整数转换为字符串）。