# markdown
h使用#即可，#的数目代表了h的级别

 \# h1  

 \## h2

 \### h3

 \#### h4

 \##### h5

 \###### h6

---
 # h1

 ## h2

 ### h3

 #### h4

 ##### h5

 ###### h6

#### text1 how

加粗使用 \*\*加粗内容**

 **加粗**


斜线使用 \*斜体\*

 *xieti*

斜体加粗 \*\*\* dd\***

使用\--进行划分界限

***


#### text2
引用1

(https://www.google.com)

https://www.google.com

引用2

\[google](https://www.google.com)

 [google](https://www.google.com)

 当然#方式的url也是支持，但是要记得索引的id地址要小写，不能有大写字母，不然无法成功。如图解释

 ⬇️
 ```bash
 [google](#text2)
 可以看到我们使用的是小写，如果我们首字母使用大写
 [google](# Text2)
 即便是id地址的确是这么写的也是无法成功运行
 [markdown](#markdown)
 ```


 图片引用使用 \! \[\] \( \)


表格使用

   | file One     | Header Two     |

  \|-|-|

  | Item One       | Item Two       |
  |ddddd|dddddddd|

  效果是这样的


  | Header One     | Header Two     |
  |-|-|
  | Item One       | Item Two       |
  |dddd|ddddfdfdfdfdfdfdfdfdf|

有序数字使用1. 2. 3. 即可

无序使用\- 或者 \*  即可

换行 直接使用enter换行即可

> markdown兼容html 使用html标签也是可以的< a href='https://www.baidu.com'\>baidu\</ a>

\> 引用
> >>> 这是引用
使用\`进行块儿注释\`

  `这是我写的例子，其实就是这样的感觉`。


代码块

 \``` languageName 例如js go py

func

pass

\```

```js
function age(){

  returen 'big one';
```

markdown 还支持类似jade的缩进方式，可以规定父类子类


- 推荐使用几款markdown编辑器

 1. atom
 2. sublime text

- markdown有更多详细使用方法请参考[详细内容](http://daringfireball.net/projects/markdown/syntax)

**对于缩进的演示**

- chapter
  - chapter1-1
  - chapter2-2
- chapter2
  - chapter2-1
  - chapter2-2

```bash
- chapter
  - chapter1-1
  - chapter2-2
- chapter2
  - chapter2-1
  - chapter2-2

```
讲真，在markdown中其实有很多的组合用法的

1. 最简单的一个就是斜粗体的用法 例如 ***这是斜粗体*** *这是斜体* **这是粗体**
2. 照片和url怎么组合呢？因为我们不仅要显示照片同时还要将其赋予一些功能，那么将照片放在URL的内部是一件比较好的事情。

这只是是照片：
![picture](http://car2.autoimg.cn/cardfs/product/g10/M01/A1/76/800x0_1_q87_autohomecar__wKgH0VkaUniADswMAAJUx9UYIzY248.jpg)
~~~
![picture](http://car2.autoimg.cn/cardfs/product/g10/M01/A1/76/800x0_1_q87_autohomecar__wKgH0VkaUniADswMAAJUx9UYIzY248.jpg)
~~~
这并不会有什么特殊的作用但是如果但是如果我们在外部潜逃一个url就OK了

[![picture][url1]][url1]

~~~
![picture][url1]
这种形式的话，适合重复性的运用，也就是常量，至于变量的话还是建议直接使用圆括号即可
~~~
能看出来这也是我们应该掌握的一个重点。
---
加入我们使用同一个根目录下的照片其实也是挺好的方式

[![picture](/image/picture1.jpg)](http://car.auto.ifeng.com/brand/20025/)

```

[![picture](/image/picture1.jpg)](http://car.auto.ifeng.com/brand/20025/)

```

```
[![picture](/image/picture1.jpg)](http://car.auto.ifeng.com/brand/20025/)
```

增加一个东西
mardkown中可以利用变量减少工作
例如
```js
[dd][url]

[url]:http://www.coastroad.net
```
这样 变量不会显示。
[url][url]

[url]:http://www.coastroad.net
这其实是常量的用法，还是挺舒服的。
也就是用 [] 代替 ()
