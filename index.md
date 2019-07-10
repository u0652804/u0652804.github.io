---
layout: default
---
<style>
 #demo-canvas{
 	background:rgba(255,255,255,0);
 	position:absolute;
 	z-index:1;
 	top:0px;
 	left:0px;
 }
 
 #e_container {	
     top:0px;
 	 left:0px;
     z-index:2;
     position:absolute;
 }
 
 .index-content{	
     position:relative;
 	 z-index:2;
 }

</style>

<body>
  <div class="index-wrapper">
    <div class="aside" id="large-header"><!-- # js background effects : set id -->
	
	      <!-- # js background effects -->
          <canvas id="demo-canvas" width="500" height="1938"></canvas>
          
          <script src="js/backeff1/js/EasePack.min.js"></script>
          <script src="js/backeff1/js/TweenLite.min.js"></script>
          <script src="js/backeff1/js/helloweb.js"></script>
		  <!-- # js background effects -->
     
	 <div class="info-card" id="e_container">
	    <!--<div><img src="https://github.com/u0652804/u0652804.github.io/blob/master/images/avatar.jpg?raw=true" width="120px" /></div>-->
        <h1>boxunliao</h1>
        <div></div>
		<a href="https://github.com/u0652804" target="_blank"><img src="https://github.com/favicon.ico" alt="" width="25"/></a>
      </div>
      <div id="particles-js">
	  
	  </div>
    </div>

    <div class="index-content">
      <ul class="artical-list">
        {% for post in site.categories.blog %}
        <li>
          <a href="{{ post.url }}" class="title">{{ post.title }}</a>
          <div class="title-desc">{{ post.description }}</div>
        </li>
        {% endfor %}
      </ul>
    </div>
  </div>
</body>
