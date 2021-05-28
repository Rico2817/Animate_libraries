# Animate_libraries
一个css样式，里面包含了可以直接引用的动画类。
>第一次在github上写博客，这是我找到的一个css开源项目animate，这里简单介绍一下这个包的用法。

[![GitHub Version](https://img.shields.io/github/release/animate-css/animate.css.svg?style=for-the-badge)](https://github.com/animate-css/animate.css/releases) [![Github Star](https://img.shields.io/github/stars/animate-css/animate.css.svg?style=for-the-badge)](https://github.com/animate-css/animate.css/stargazers) [![Github Fork](https://img.shields.io/github/forks/animate-css/animate.css.svg?style=for-the-badge)](https://github.com/animate-css/animate.css/network/members) [![License](https://img.shields.io/github/license/animate-css/animate.css.svg?style=for-the-badge)](https://github.com/animate-css/animate.css/blob/main/LICENSE)
## 查看效果预览可以打开：
```shell
https://animate.style/
```
[Animate.Style效果预览](https://animate.style/)
>我这里用的版本是V4.1.1，如果需要别的版本也可以在里面下载。
>这边只简单介绍一下使用=w=。
## 安装
你可以直接在这个主页下载animate.css到你的css文件夹并配合`<link>`使用
同样你也可以直接通过下面的代码进行互联网上的获取。
```html
<head>
  <link
    rel="stylesheet"
    href="https://cdnjs.cloudflare.com/ajax/libs/animate.css/4.1.1/animate.min.css"
  />
</head>
```
## 如何使用
简单的通过在标签中加入`class=""`来调用animate.css中的动漫，至于`class=""·的`""`中填什么
就从上面的效果预览中获得对应的类名来使用啦。比如这里给图片添加一个抖动的动画：
```html
<!DOCTYPE html>
<html>
<head>
	<title>animate CSS style</title>
	<link rel="stylesheet" type="text/css" href="./css/animate.css">
</head>
<body>
<img class="animate__animated animate__bounce" src="./images/doge.jpg"/>
</body>
</html>
```
>这里要注意必须要先在前面加上`animate__animated`并且都是以`animate__`为前缀,里面是两个`_`
当然，还可以给这个抖动动画还有其他的动画属性，比如:

|ClassName|属性|
| --- | --- |
|animate__delay-2s|打开网页后延迟2s播放动画|
|animate__slow|设置动画播放速度为慢速(原速1s改为2s)|
|animate__slower|设置动画播放速度为更慢速(原速1s改为3s)|
|animate__fast|同理1s-->800ms|
|animate__faster|同理1s-->500ms|
|animate__repeat-1|重复1次|
|animate__infinite|重复无数次，一直播放|

如果还想获得更多的动画可以参考[Animate.Style效果预览](https://animate.style/)里面给出的动画：
![image](https://user-images.githubusercontent.com/57565901/120014447-a7154500-c014-11eb-8b29-5e8492f48962.png)
右侧可以直接复制动画对应的classname，添加到`class=""`就好了。
