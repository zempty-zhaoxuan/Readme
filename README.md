<p align ="center">快速上手 markdown ，写出好看的 readme 文档</p>

该文档呈现的是显示效果，具体使用请点击编辑按钮看实际使用的 markdown 标签的使用

学习编写readme，文本下面是 = 会代表这行会是一个大标题，等于号的个数无限制
==

文本下面是----表示中标题，个数没有限制
-----

等级标题表示的方法如下：
==

#  一级标题
##  二级标题
###  三级标题
####  四级标题

文本编辑如何换行呢？ 用 html 中 的 br 标签就好！</br>

### Tab 按键会有如下的显示效果,添加两个 Tab 按键


                hello world
                helllo world
                hello world
      
      
### 下面的用法可以把内容进行区域化，
```
爱情是理解和体贴的别名。
——泰戈尔
```

### 这个通常用在代码上面 
```cpp
System.out.prinltn("hello world");
```

### 字体加粗
你好这是一个**残酷**的世界

### 字体斜体
你好这是一个*残酷*的世界

### 字体高亮
你好这是一个`残酷`的世界
### 插入链接

例子： [百度](www.baidu.com "百度链接")  

### 圆点符号

* 这里显示的是一个圆点，记得*后面有空格

### 圆点的层级结构

* 一级

    *  二级相对一级添加了两个 Tab

        * 三级相对二级添加了两个 Tab
  
  
 
 ### 缩进
 
 >太爷爷
 >>爷爷
 >>>爸爸
 >>>>儿子
 >>>>>孙子
 
 ### 插入图片
 
 
 如下格式括号中写的是图片的 url 同时还可以在括号里面添加双引号鼠标移动到图片会有提示效果
 
 ![Google](https://www.google.com/images/branding/googlelogo/1x/googlelogo_color_272x92dp.png "谷歌 logo")
 
 把图片提交到 GitHub 的仓库以后在 README.md 显示，括号里面的地址是在仓库里面打开图片在浏览器里显示的地址
 
 ![](https://github.com/kickcodeman/Readme/blob/master/pics/92776.jpg)
  
 点击图片进行超链接，如下所示：
 
 [![谷歌](https://www.google.com/images/branding/googlelogo/1x/googlelogo_color_272x92dp.png "点击进入谷歌")](https://www.google.com)
 
 ### 添加表格
 
 添加普通表格:</br>
 
| 表头1  | 表头2|
| ------------- | --------------|
| Content Cell  | Content Cell  |
| Content Cell  | Content Cell  |
 
 靠左，居中，靠右:</br>
 
 | 靠左| 居中 | 靠右 |
 | :--- | :---: | ---: |
 | 123 | 456 | 7890 |
 | 12345 | 789000 | 098765|
 | 762hdgkj | tyqiutyqoieu | hgjagkjan |
 
在表格中插入图片：</br>

| 图片 | 描述|
| ---- | -----|
![Google](https://www.google.com/images/branding/googlelogo/1x/googlelogo_color_272x92dp.png) | 这是 Google 的 Logo. 


### 添加视频链接

这种方法添加视频跟添加图片链接的方式相同,点击链接到视频：</br>

[![](https://github.com/kickcodeman/Readme/blob/master/pics/92776.jpg)](https://youtu.be/ow-b6W6qYF8 "点击会进行视频链接")
