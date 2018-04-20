# CSS
css 是层叠样式表（Cascading Style Sheet），用于控制页面的外观。

## 选择器
### 语法规范
    选择器 {
      属性a：属性值1;
      属性b：属性值2;
    }
- 标签选择器：p{color:red;}，适用于共性的属性；
- 类选择器：.aa{color:red;}，引用<p
  class="aa"></p>，可多次调用，适用于共性的属性。
- ID选择器：#aa{color:red;}，引用<p
  id="aa"></p>，不可多次调用，适用于单个页面的定制。
- 全局选择器：\*{color:red;}，\*表示所有标签。
- 伪类选择器：只针对超级链接, a:hover{color:red;}


### 样式表（根据css 代码所放位置的不同分为三种）
内嵌样式：
<style>
  /* 这里写CSS内容 */
</style>

行内样式：在html标记内，使用style属性定义css样式；
<p style="color:red"></p>

链接样式：在外部定义CSS样式表，通过<link>链接到页面的一种样式；
<link href="style.css" rel="stylesheet" type="text/css" />


### 属性
#### 文字属性
color：字体颜色
font-size：字号
font-family：字体
font-weight：字体加粗； bold：加粗； normal：普通字体；

#### CSS段落属性
文字修饰（text-decoration）：underline-下划线；none-无修饰；
水平对齐方式（text-align）
文本缩进（text-indent：2 em；） 数值+单位
文本行高（line-height）
背景复合属性（background）
列表项目符号的样式（list-style）

html的导航栏用无序列表ul做；



### 盒模型属性（上右下左，顺时针，缺省值为对称值）
margin：元素与元素之间的距离，盒子之间的距离。
padding：内容与边框之间的距离，内填充距离
border：边框复合属性，top，right，bottom，left；solid-实线，dashed-虚线；








