typora

# Markdown All in One 使用说明</br>

Markdown Preview Enhanced</br>
## Markdown All in One插件快捷键用法：

快捷键	操作</br>
Ctrl+B	加粗</br>
Ctrl+l	斜体</br>
Ctrl+l	斜体</br>
Alt+S	删除线</br>
Alt+C	勾选/取消勾选任务清单项目</br>
Ctrl+M	开启 LaTeX 数学公式编写</br>
1、单个回车，视为空格</br>
2、连续回车，才能分段</br>
3、行尾加两个空格，就可以段内换行</br>
4、注释可使用HTML的注释</br>
5、也可以使用HTML标签</br>

## I、标题
# H1标题
## H2标题 </br>
### H3标题 </br>
#### H4标题 </br>
##### H5标题 </br>
###### H6标题</br>
<h1> 标题 </h1>
<h2> 标题 </h2>

### ①无序列表
* 列表1 
* 列表2 
+ 列表3 
+ 列表4 
- 列表5 
- 列表6 </br>
### ②嵌套
有序无序均可嵌套，在上一级和下一级之间敲三个空格即可
* 列表1
   * 子列表1
   * 子列表2
* 列表2</br>
### ③有序列表
1. 文本 
2. 音乐 
3. 童话 
4. 列了都要爱 
5. 天下 
6. 电影 </br>

## 粗体
**粗体** </br>
__粗体__ </br>
<b>粗体</b> </br>
<strong>粗体</strong> </br>

## 斜体
*斜体*</br>
_斜体_</br>
## 粗体+斜体</br>
***粗斜体***</br>
___粗斜体___</br>

## 删除
~~删除~~

---
语法：<font face="字体">xxxx</font></br>
  eg:<font face="黑体">我是黑体字</font> </br>
     <font face="微软雅黑">我是微软雅黑</font> </br>
     <font face="STCAIYUN">我是华文彩云</font></br>
    <font size=4>字体大小</font>  </br>
    <font size=6>字体大小</font></br>
    <font color=#fbf7ae size=4>字体上色</font>  </br>
    <font color=red size=4>字体上色</font></br>
    
  <table><tr><td bgcolor=#7ec7f9>背景色的设置是按照十六进制颜色值：#7ec7f9</td></tr></table>
  <table><tr><td bgcolor=#71d8d2>背景色的设置是按照十六进制颜色值：#71d8d2</td></tr></table>
  <table><tr><td bgcolor=#A3c1ea>背景色的设置是按照十六进制颜色值：#A3c1ea</td></tr></table>
  <table><tr><td bgcolor=#CBB4e3>背景色的设置是按照十六进制颜色值：#CBB4e3</td></tr></table>
  <table><tr><td bgcolor=#C97586>背景色的设置是按照十六进制颜色值：#C97586</td></tr></table>

#ed556a 山茶红

---
## 链接 
1. 直接设置（行内形式） 语法：[链接名称]（链接地址 “链接title”） </br>
 eg： [百度](http://www.baidu.com "百度一下，你就知道") </br>
2. 间接设置（参考形式） 语法：[链接名称][标记] [标记]：链接地址“链接title” 
eg： [百度][1] [1]: http://www.baidu.com "百度一下，你就知道" （其中1为一个链接标记，可以用于多次要使用链接的时候） 
3. 隐式设置 语法：[链接名称][] [链接名称]：链接地址“链接title” eg： [百度][] [百度]: http://www.baidu.com "百度一下，你就知道" 
--- 
## 图片 
1. 直接设置（行内形式） 语法：![替换文本]（链接地址“链接地址”） </br>
   
eg： ![百度](https://www.baidu.com/img/bd_logo1.png "百度一下，你就知道")

2. 间接设置（参考形式）
    语法：[替换文本][标记]
        [标记]：链接地址“”
eg：
    ![百度][1]
    [1]: https://www.baidu.com/img/bd_logo1.png "百度一下，你就知道"
（建议将图片存在有道云中，将有道云作为图库来使用）</br>

3. html写法</br>
语法：<img src="" alt="" height="" width="" align=""/>

## 引用
> 一级引用
    >> 二级引用
        >>> 三级引用
1. 引用换行
        末尾加两个空格</br>
2. 引用内包含其他语法：
如：标题、列表、代码块
注：一定要写在开头处

---
***
## 下划线 
++下划线++     //有道云中可以实现
1. <u>下划线</u>  
    <span style="border-bottom:2px dashed red;">下划线</span>  
    <span style="border-bottom:2px solid red;">下划线</span> 
## 代码块
1. 代码句
    用反引号(\`)，就是英文状态下的波浪线
    eg：
    `我是代码句`

2. 代码块
    4个空格（或用Tab缩进）定义代码块
3. 用三个以上的反引号定义段开始和结
``` java
    public class Test {
        public static void main(String[] args) {
            System.out.println("Hello World");
            }
        }
```
## 表格
关于冒号（:）
	左边：以下内容左对齐
	右边：以下内容右对齐
	两边：以下内容居中对齐
项目	价格	数量
Computer	1600 元	5
Phone	12 元	12
Pipe	1 元	234

## 转义字符
\\　反斜杠
\`　反引号
\*　星号
\_　下划线
\+　加号
\-　减号
\#　井号
\.　句号
\~　感叹号

## 十、插件
目前用的比较多的chrome插件有

Markdown Preview Plus</br>
Markdown Viewer</br>
Markdown Viewer安装使用：</br>
1. 首先需要将 Markdown Viewer 下载到本地
    下载地址：https://github.com/simov/markdown-viewer
2. 打开chrome扩展程序
···   更多工具  扩展程序
将开发者模式打开
3. 将 Markdown Viewer 插件压缩文件拖至到此（注意：压缩文件）
4. 最后确认为使用状态
5. 打开md文档进行浏览

### 使用插件 Maridown pdf 将.md文件转换成其他格式
Maridown pdf插件可以简单的将编写的.md文件转换成其他格式的文件，一样地，在插件库中搜索安装 Maridown pdf 插件即可使用。

### <font color=#a0d8ef > 使用插件Markdown Preview Enhanced </font>
Markdown Preview Enhanced是一个很好用的完善预览功能的插件，可以更加形象的展示所编写的pdf格式的文档样式。在插件库中搜索markdown即可找到该插件，然后点击安装后重新加载。

### <font color=#C97586 > MarkDown PDF转html报错 </font>
ERROR: Failed to download Chromium! If you are behind a proxy, set the http.proxy option to settings.json and restart Visual Studio Code. See https://github.com/yzane/vscode-markdown-pdf#install
这个主要是因为它貌似要下载Chromium，通过这个来转换html，然而我们国内把这个墙了，所以除非你有代理的话可以在 settings.json 里设置一下，没有代理的话可能绕不过这个坑了。如果需求很强烈就尝试一下在线转换工具吧~

#+BEGIN_SRC plantuml :file ../img/orgmode-babel-sequenceuml.png
  Alice -> Bob: synchronous call
  Alice ->> Bob: asynchronous call
#+END_SRC


在主界面中，文件 >>首选项>>用户片段

选择需要新增代码补全的文件类型(vscode可以根据文件的不同来采用不同的代码补全方案,当然你也可以设置全局代码补全方案)
我们这里以.md文件为例,于是选择markdown即可

在书写md文件时,笔者经常会感觉添加代码块太麻烦了,一共需要输入六个反撇号,以及一个代码名称标识,如图:


于是笔者打算先添加一系列的代码块自动补全

模板
    "name"://该补全项目的名称,可以随便写，多个项目之间需要使用逗号隔开 {  
        "prefix": "输入此内容后触发补全联想", 
        "body":   "选中并按下回车后自动补全的内容",// $1代表光标默认位置
        "description": "此代码补全项的提示语" 
    }
因此,只需添加:

    "C++_block": {  
        "prefix": "```C++", 
        "body":   "```C++\n$1\n```$2",
           // 另外$1代表光标默认位置,$2代表按下tab后会切换至的下一个光标落点,此外shift+tab能够切换至上一个光标落点
    }

然而vscode对markdown默认关闭代码补全功能，经过笔者尝试，网上提供的自动开启代码补全的方法只能对工作区文件夹有效，无法做到在任意文件夹下有效

当处于临时文件夹编辑md文本内容时，需要使用ctrl+space手动打开代码补全功能。此外，该快捷键与切换输入法快捷键冲突，因此笔者建议下载markdown all in one 扩展插件

该扩展插件内置了一套逻辑，该逻辑可以使得vscode在任意文件夹下都有自动打开代码补全功能
```
"[markdown]": {
        "editor.wordWrap": "on",
        "editor.quickSuggestions": true
```


效果图（tab键可以切换至下一个填充位点，shift+tab可以切换至上一个）：

———————————————
### 表格
---------------------------
项目 | Value
-------- | -----
电脑 | $1600
手机 | $12
导管 | $1
| Column 1 | Column 2 |
|:--------:| -------------:|

### 插入Mermaid流程图
--------
mermaid
graph LR
A[长方形] -- 链接 --> B((圆))
A --> C(圆角长方形)
B --> D{菱形}
C --> D

mermaid
graph DT
B --> D

插入Flowchart流程图
-------
mermaid
flowchat
st=>start: 开始
e=>end: 结束
op=>operation: 我的操作
cond=>condition: 确认？
st->op->cond
cond(yes)->e
cond(no)->op
———————————————



图片缩放
<center>
<img src = "https://img-blog.csdnimg.cn/20190110153341989.jpg?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3dlaXhpbl8zODE4NDc0MQ==,size_16,color_FFFFFF,t_70" width=30% >

图片居中
<center>
<img src = "https://img-blog.csdnimg.cn/20190110153341989.jpg?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3dlaXhpbl8zODE4NDc0MQ==,size_16,color_FFFFFF,t_70">

图片右对齐
<div align=right>
<img src = "https://img-blog.csdnimg.cn/20190110153341989.jpg?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3dlaXhpbl8zODE4NDc0MQ==,size_16,color_FFFFFF,t_70" width=30% >


