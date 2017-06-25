# markdown
> 这里就是很简单的入门不是很详细，

* h使用#即可，#的数目代表了h的级别

 \# h1  

 \## h2

 \### h3

 \#### h4

 \##### h5

 \###### h6


 # h1

 ## h2

 ### h3

 #### h4

 ##### h5

 ###### h6

# text1 how

* 加粗使用 \*\*加粗内容**

 **加粗**


* 斜线使用 \*斜体\*

 *xieti*

* 斜体加粗 \*\*\* dd\***



* 使用\--或者\***来进行划分界限

***


# text2
* 引用直接(https://www.google.com)


* 文字引用使用\[google](https://www.google.com)

 [google](https://www.google.com)
 当然#方式的url也是支持的例如

 ---
 [markdown](#markdown)
 ~~~
 [markdown](#markdown)
 ~~~


* 图片引用使用 \! \[\] \( \)


* 表格使用




   | file One     | Header Two     |

  \|:---|:-----|

  | Item One       | Item Two       |
  |ddddd|dddddddd|

  效果是这样的


  | Header One     | Header Two     |
  | :--------|:-----------|
  | Item One       | Item Two       |
  |dddd|ddddfdfdfdfdfdfdfdfdf|

* 有序数字使用1. 2. 3. 即可

* 无序使用\*  即可

* 换行 直接使用enter换行即可

* markdown兼容html 使用html标签也是可以的< a href='https://www.baidu.com'\>baidu\</ a>
* \> 引用
> >>> 这是引用
* 使用``进行块儿注释

  `这是我写的例子，其实就是这样的感觉`。


* 代码块 ～～～ function～～～（注意是英文～）

~~~
function age(){

  returen 'big one';

}
~~~

* markdown 还支持类似jade的缩进方式，可以规定父类子类


* 推荐使用几款markdown编辑器

 1. atom
 2. sublime text

* markdown有更多详细使用方法请参考[详细内容](http://daringfireball.net/projects/markdown/syntax)

测试环节
1. [text1](#text1-how)
2. [text2](#text2)

---

- chapter
  - chapter1-1
  - chapter2-2
- chapter2
  - chapter2-1
  - chapter2-2

~~~
- chapter
  - chapter1-1
  - chapter2-2
- chapter2
  - chapter2-1
  - chapter2-2

~~~
使用如此方法，就可以进行 实心和空心的交替使用。注意第二层和第一层的分割点是两个空格的（其实一个缩进就行，不过我们还是遵循标准，使用两个缩进为好）
