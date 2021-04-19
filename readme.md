
## ![logo](https://github.com/chokcoco/iCSS/blob/master/logo.jpg?raw=true)

```
原文简介：

CSS 奇技淫巧，在这里，都有。

本系列文章围绕 **CSS/Web动画** 展开，谈一些有趣的话题，内容天马行空，想到什么说什么，不仅是为了拓宽解决问题的思路，更涉及一些容易忽视或是十分有趣的 CSS 细节。
```


本文档为个人学习使用，记录在学习iCSS的过程中的想法同时自己复现原文中的内容，有兴趣的同学可以参考~

个人认为最重要的是在学习的过程中多了解css的各种特性，以及样式设计的复用性考虑，而不是单纯为了解题，一定要多看MDN文档。

==**建议网页显示和源文件配合享用~**==
**tips:** chrome使用ctrl+点击可以在新标签页打开网页

## 文章列表
#### 1、[下面这个左边竖条图形，只使用一个标签，可以有多少种实现方式：](http://htmlpreview.github.io/?https://github.com/KK-AI-LL/iCSS/blob/master/css_learn/1.左边框的多种实现方式.html)
[源文件](https://github.com/KK-AI-LL/iCSS/blob/master/css_learn/1.左边框的多种实现方式.html)

![image](https://user-images.githubusercontent.com/8554143/87442343-c686c780-c626-11ea-871a-d95f3176f6a4.png)

#### 2、[类似下面这样的条纹边框，只使用一个标签，可以有多少种实现方式 -- 从条纹边框的实现谈盒子模型：](http://htmlpreview.github.io/?https://github.com/KK-AI-LL/iCSS/blob/master/css_learn/2.条纹边框的多种实现方式.html)
[源文件](https://github.com/KK-AI-LL/iCSS/blob/master/css_learn/2.条纹边框的多种实现方式.html)

![image](https://user-images.githubusercontent.com/8554143/97247472-b6dc6900-183a-11eb-8331-ed952e4c2a1c.png)

#### 3、[层叠顺序（stacking level）与堆栈上下文（stacking context）知多少？](http://htmlpreview.github.io/?https://github.com/KK-AI-LL/iCSS/blob/master/css_learn/3.stacking-level_vs_stacking-context.html)
[源文件](https://github.com/KK-AI-LL/iCSS/blob/master/css_learn/3.stacking-level_vs_stacking-context.html)

#### 4、[从倒影说起，谈谈 CSS 继承 inherit](http://htmlpreview.github.io/?https://github.com/KK-AI-LL/iCSS/blob/master/css_learn/4.倒影2inherit.html)
[源文件](https://github.com/KK-AI-LL/iCSS/blob/master/css_learn/4.倒影2inherit.html)

#### 5、[纯 CSS 实现单行居中显示文字，多行居左显示，最多两行超过用省略号结尾](http://htmlpreview.github.io/?https://github.com/KK-AI-LL/iCSS/blob/master/css_learn/5.单行居中显示文字_多行居左显示_最多两行超过用省略号结尾.html)
[源文件](https://github.com/KK-AI-LL/iCSS/blob/master/css_learn/5.单行居中显示文字_多行居左显示_最多两行超过用省略号结尾.html)

![image](https://user-images.githubusercontent.com/8554143/97247656-0f136b00-183b-11eb-8d8f-fb27af99a04b.png)

#### 6、 [全兼容的多列均匀布局问题](http://htmlpreview.github.io/?https://github.com/KK-AI-LL/iCSS/blob/master/css_learn/6.全兼容的多列均匀布局问题.html)
[源文件](https://github.com/KK-AI-LL/iCSS/blob/master/css_learn/6.全兼容的多列均匀布局问题.html)

如何实现下列这种多列均匀布局：

![image](https://user-images.githubusercontent.com/8554143/87442550-03eb5500-c627-11ea-80f5-ada17a79a6d0.png)


#### 7、[全兼容的最后一条边界线问题](http://htmlpreview.github.io/?https://github.com/KK-AI-LL/iCSS/blob/master/css_learn/7.消失的边界线问题.html)
[源文件](https://github.com/KK-AI-LL/iCSS/blob/master/css_learn/7.消失的边界线问题.html)

看看下图，常见于一些导航栏中，要求每行中最后一列的右边框消失，如何在所有浏览器中最便捷最优雅的实现？

-------
