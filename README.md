# Study_Notes
Study notes about compute
#一级标题
##二级标题
###三级标题
####四级标题

**加粗文本** __加粗文本__

==标记文本==
~~删除文本~~
*斜体* _斜体_
<u>这是下划线</u>

x^2^
H~2~O

> 引用文本
> >嵌套引用

来一段经典的 helloworld.c吧：（说明：位于Esc下面）
`int a=0;`

`include <stdio.h>`

`int main(void){
    printf("hello world!");
}`

下面又是一种代码块
```js/java/c#/text/c
void main(){return}
```

- [ ] 吃早餐
- [x] 背单词
  
使用- * + 配合缩进表示列表，（- * +后面都有空格）
- 大项目1
  * 中项目1
    + 小项目1
    + 小项目2
    + 小项目3
  * 中项目2
- 大项目2
- 大项目3


使用1. 2. 3. 这样排布列表 （.后面有空格）
1. 项目1
2. 项目2
3. 项目3

使用三个或三个以上的-或者*或者_
如:
分割线

---
***
___

[这个是链接名](这个是链接网站)
如
[我们和百度达成了战略合作，只要点击此链接您就能享受我们为您定制的专用搜索服务](http://www.baidu.com)
也可以这么写（[1]:https://www.csdn.net/前记得加一空行）
这篇文章取自了
[xxxxxx的观点][1]
[xxxxxx的看法][2]

[1]:https://www.csdn.net/
[2]:https://www.csdn.net/


和链接的形式没有什么差别，就是在链接之前加一个!，[]中的内容变成了图片的描述。
csdn支持直接拖曳添加图片，这个功能还是很赞的。

说实话居中和带尺寸的图片还是蛮有用的啦，会让博客看上起更加规整。我直接把csdn帮助的抄过来了：

图片: ![图片](https://avatar.csdn.net/7/7/B/1_ralf_hx163com.jpg)

带尺寸的图片: ![带尺寸的图片](https://avatar.csdn.net/7/7/B/1_ralf_hx163com.jpg =30x30)

|  1   |  2   |  3   |
| :--- | :--: | ---: |
|  4   |  5   |  6   |
|  7   |  8   |  9   |
|  10  |  11  |  12  |

反斜杠用于忽略符号，相当于编程语言里的转义作用。
如
\# 一级标题
\*加粗不加粗\*
\```
这不是代码段
\```
看起来就是回归本源了
