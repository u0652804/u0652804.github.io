---
layout:       post
title:        background_effects
category:     blog
description:  create a background effects side project
---

# background_effects 
 create a background effects side project

#####  outline
 - download js effects package in project path /js/
 - include js effects package in index1.html
 - embed index1 in home.html by iframe
 
#####  step
download js effects package in project path /js/
![](https://raw.githubusercontent.com/u0652804/u0652804.github.io/master/images/other/up_res/background_effects_p1.png)

include js effects package in index1.html

    <!doctype html>
    <html>
    <head>
      <meta charset="utf-8">
      <title></title>
      <style>
        *{margin:0;padding:0;}
        #large-header{
        	position: relative;
        	width: 100%;
        	overflow: hidden;
        	background:#2A2A2A;
        	z-index: 1;
        	height:469px;
        }
      </style>
    </head>
    
    <body>
     <div id="large-header">
         <canvas id="demo-canvas" width="1680" height="469"></canvas>
     </div>
     <!-- # js background effects -->
     <script src="js/EasePack.min.js"></script>
     <script src="js/TweenLite.min.js"></script>
     <script src="js/helloweb.js"></script>
    </body>
    </html>

embed index1 in home.html by iframe

    <!doctype html>
    <html>
    <head>
    <meta charset="utf-8">
    <title>粒子背景特效</title>
    <style>
    
    </style>
    </head>
    
    <body>
     <!-- embed a background-effect by iframe -->
     <div id="iframe-wrap">
         <iframe width="100%" height="876px" frameborder="0" src="index1.html" id="iframe"></iframe>
     </div>
    </body>
    </html>

#####  reference
 [canvas 网页粒子背景特效][1]
[1]: http://helloweb.wang/ziyuangongxiang/697.html "1"