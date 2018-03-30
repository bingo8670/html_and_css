# HTML 概念集锦
- HTML：HyperText  Markup Language(超文本标记语言)，是用来描述网页的一种语言。
- 网页：是网站中的任何一个页面，通常文件扩展名为html或htm；
- 网站：用于展示相关内容的网页的集合；
- 超文本：用超链接的方法将各种不同空间的文字信息组织在一起的网状文本；
- 标记：用来区分文档中的不同部分的符号；
- 站点：存储了一个网站所有的文件的文件集合；
- 标题：标明文章、作品等内容等简短语句；
- 段落：<p></p>
- 属性：用来表示标签等特征；
- 属性值：为属性赋的值；
- 路径：文件(夹)所在的位置，分为绝对路径和相对路径；
- 无序列表：列表项没有先后顺序的列表形式；



## HTML 基本标记结构
<html>
  <head>
    <title></title>
  </head>
  <body></body>
</html>


## 标签
###双标签
- <a></a>   超链接，属性：href(链接地址)，target(blank:新页面打开；self:原页面打开)
- <b></b>   加粗 == <strong></strong>
- <h1..6></h1..6>   标题，属性：align(对齐方式)
- <i></i>   倾斜
- <ol><li></li></ol> 有序列表(ordered list)，属性：type(序号类型)，start(开始序号，必须为数字)
- <ul><li></li></ul> 无序列表(unordered list)，属性：type(序号类型)

###单标签
- <br/>     换行
- <image/>  图片，属性：src(路径)、width(宽度)、height(高度)、border(边框)、alt(提示性文字，图片不能加载时显示)
- &nbsp;    添加空格；


## 语法
<标记 属性=“属性值”>内容</标记>

    <dl>              # 自定义列表(definition list)
      <dt>            # 自定义项
        <dd></dd>     # 自定义项描述（无序号缩进）
      </dt>
    </dl>


    <table border/width/height/align/bgcolor>      # 表格
        <tr>                                       # 行
          <td></td>                                # 列
        </tr>
    </table>
