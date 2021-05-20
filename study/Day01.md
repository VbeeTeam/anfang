# Day01  开班  

## Web前端实训安排

- 第一天：HTML、CSS基础回顾
- 第二天：网页布局
- 项目考核：平时成绩+项目成绩

## 前端和后端的区别

### 前端

![](C:\Users\susu\Desktop\温州商学院\day01\img\src=http___photo.16pic.com_00_05_66_16pic_566331_b.jpg&refer=http___photo.16pic.jpg)

### 后端

![](C:\Users\susu\Desktop\温州商学院\day01\img\src=http___images2.10qianwan.com_10qianwan_20180509_b_0_201805091348187671.jpg&refer=http___images2.10qianwan.jpg)

### 印象中的程序员

![](C:\Users\susu\Desktop\温州商学院\day01\img\微信图片_20210326135631.png)

### 实际工作中的

![image-20210327201144865](C:\Users\susu\AppData\Roaming\Typora\typora-user-images\image-20210327201144865.png)

![](C:\Users\susu\Desktop\温州商学院\day01\img\微信图片_20210326135651.png)



## 产品开发人员及流程



![](C:\Users\susu\Desktop\温州商学院\day01\img\微信图片_20210327204026.png)



## 前端技术栈



![](C:\Users\susu\Desktop\温州商学院\day01\img\微信图片_20210327203659.png)



## 认识网页

```
思考：网页主要由什么构成？

```

```
思考：网页是如何形成的呢?

```



## 常见浏览器介绍

```
浏览器是网页运行的平台，常用的浏览器有IE、火狐（Firefox）、谷歌（Chrome）、Safari和Opera等。我们平时称为五大浏览器。
```

<img src="C:\Users\susu\Desktop\温州商学院\day01\media\b.png" />

## 查看浏览器占有的市场份额（知晓）

查看网站： <a href="http://tongji.baidu.com/data/browser" target="_blank">http://tongji.baidu.com/data/browser</a>



## 浏览器内核

|         类别          |    内核     |
| :-------------------: | :---------: |
|          IE           |   Trident   |
| Mozilla FireFox(火狐) |    Gecko    |
|        Safari         |   WebKit    |
|    Chrome（谷歌）     | WebKit/Bink |
|     Opera（欧朋）     |   Presto    |



## Web标准（重点）

```
问：  哪个语言再全国基本都可以听得懂？ 
```

<img src="C:\Users\susu\Desktop\温州商学院\day01\media\bz.png" />

## Web 标准的好处

*1*、让Web的发展前景更广阔 
*2*、内容能被更广泛的设备访问
*3*、更容易被搜寻引擎搜索
*4*、降低网站流量费用
*5*、使网站更易于维护
*6*、提高页面浏览速度

##  Web 标准构成

 Web标准不是某一个标准，而是由W3C和其他标准化组织制定的一系列标准的集合。主要包括结构、表现和行为三个方面。

~~~
结构标准：结构用于对网页元素进行整理和分类，主要包括XML和XHTML两个部分。
样式标准：表现用于设置网页元素的版式、颜色、大小等外观样式，主要指的是CSS。
行为标准：行为是指网页模型的定义及交互的编写，主要包括DOM和ECMAScript两个部分
~~~

理想状态我们的源码： .HTML    .css   .js 

```
专业的人，写专业的代码
```

<img src="C:\Users\susu\Desktop\温州商学院\day01\media\wk.png" />



总结WEB标准：

结构标准：   <img src="C:\Users\susu\Desktop\温州商学院\day01\media\hb1.png" />  决定你是否有个好天然身体 



样式标准：   <img src="C:\Users\susu\Desktop\温州商学院\day01\media\hb2.png" />  决定你是否打扮的美丽外观



行为标准：   <img src="C:\Users\susu\Desktop\温州商学院\day01\media\hb3.jpg"  width="420"   />  决定你是否有吸引人的行为



## 开发工具的使用

### 1.Vscode的下载、安装

（1）官网https://code.visualstudio.com/Download下载最新版   最好下载zip格式

（2）解压到非系统盘，文件夹最好不要出现中文和空格，我解压到D:\VSCode-win32-x64-1.31.1，直接运行code.exe即可

### 2.安装常用插件

- Chinese (Simplified) Language：中文（简体）语言包为 VS Code 提供本地化界面

- html CSS Support ：提供基础的语法知识编写辅助

- Open-In-Browser：在vscode中打开浏览器访问

- Prettier - Code formatter:格式化代码

- Beautify：美化代码

## PhotoShop的使用

### 1.安装

### 2.常用快捷键

- Alt+鼠标滚轮放大缩小图片 
- 长按空格+鼠标左键拖动图片
- Ctrl+C复制选择区域图片
- Ctrl+N创建空白区域
- Ctrl+V粘贴图片
- Ctrl+Shift+Alt+S保存图片格式

### 3. .jpg .png .gif

#### .jpg: 支持有损压缩，不支持透明，不支持动画

#### .png: 不支持压缩，支持透明，半透明，不透明，不支持动画

#### .gif: 支持有损压缩，支持半透明，支持动画



## HTML、CSS基础回顾

## HTML

1.什么是HTML？



2.常用的标签：

（1）

- a
- span
- em
- b
- strong
- i

（2）

- div
- p
- ul
- li
- h1 - h6
- dl
- dt
- dd

(3)

- input
- select
- textarea
- img

3.元素类型转换

- none  
- block   
- inline   
- inline-block  

## CSS

1.什么是css？



2.css权重

|            类型             | 权重 |
| :-------------------------: | :--: |
|         ! important         | 无穷 |
|          内联样式           | 1000 |
|             id              | 100  |
| class/属性选择器/伪类:hover |  10  |
|   标签选择器/伪元素:after   |  1   |
|           通配符*           |  0   |



3. 盒模型

   

4. 浮动布局

   

5. 定位布局

   

   


### 前端工程师须知pc电脑端分辨率

按屏幕宽度大小排序（主流的用橙色标明）

分辨率  比例 | 设备尺寸

1024*500 （8.9寸）

1024*768 （比例4：3  | 10.4寸、12.1寸、14.1寸、15寸; ）

1280*800（16：10  |15.4寸）

1280*1024(比例：5：4  | 14.1寸、15.0寸)


1280*854(比例：15：10 | 15.2）

1366*768 (比例：16：9 | 不常见）

1440*900 （16：10  17寸 仅苹果用）

1440*1050（比例：5：4  | 14.1寸、15.0寸）

1600*1024（14：9  不常见）

1600*1200 （4：3 | 15、16.1）

1680*1050（16：10 | 15.4寸、20.0寸）

1920*1200 (23寸）

 

#### 通过上面的电脑屏幕及尺寸的例表上我们得到了几个宽度



### HTML、CSSPC端 浮动布局、定位布局



![](C:\Users\susu\Desktop\温州商学院\day01\img\卧龙控股.jpg)

