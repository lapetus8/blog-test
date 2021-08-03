# 1-HTML的诞生
html诞生于1990年,由tim berners-lee(李爵士)发明,还顺便发明了http,url
# 2 HTML的起手式
```html
<!-- 文档类型:html -->
<!DOCTYPE html>
<!-- 最好变成zh-CN -->
<html lang="zh-CN">
  <head>
    <!-- 文件的字符编码 -->
    <meta charset="UTF-8" />
    <!-- 如果在IE中打开，提示升级最新IE -->
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <!-- 禁用缩放，兼容手机 -->
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <!-- 标题 -->
    <title>我的第一个网页</title>
    <style>
        <!-- 这里一定要写reset CSS语法,因为原生的太丑了 -->    
    </style>
  </head>
  <body>
  </body>
</html>
```
# 3 常用的表章节的标签
h1-6表示标题.1最大,6最小.

section表示段落

article表示一片文章

main表示主要内容

aside表示旁支内容

p 段落

header 头部

footer 脚部

# 4 全局属性
class 标签的类属性,一般作为过滤器试用

contenteditable 让用户可以直接编辑内容

hidden 隐藏标签

id 标签的唯一id 用来给CSS当过滤器,配合getElementById使用,注意避免和windows对象模型名字冲突

style设置样式

tabindex 用来设置tab下一个焦点的位置,正数按照顺序访问,0表示最后访问,这一点设计很奇葩.-1表示用眼tab不到它.

title 显示标题

解决单行文字溢出方法:

调整css

white-space: nowrap; 不要换行

text-overflow: ellipsis 溢出的部分用....

overflow: hidden; 溢出的部分隐藏

# 5 常用的内容标签
a 表示连接,但是自带下划线,一般再RESET CSS里面首先把它的下划线干掉

strong表示内容增强,视觉效果为增粗

em表示语气强调,视觉效果为斜体

code表示空格

pre标签内的空格,回车按照原来样式表示,不会省略为一个空格

ol+li:有序标签

ul+li:无序标签

dl+dt+dd:描述列表

br:换行




