---
layout: default
---

<body>
  <div class="index-wrapper">
    <div class="aside">     
	 <div id="large-header">
         <canvas id="demo-canvas" width="1680" height="469"></canvas>
     </div>
     
	 <div class="info-card">
	    <!--<div><img src="https://github.com/u0652804/u0652804.github.io/blob/master/images/avatar.jpg?raw=true" width="120px" /></div>-->
        <h1>boxunliao</h1>
        <div></div>
		<a href="https://github.com/u0652804" target="_blank"><img src="https://github.com/favicon.ico" alt="" width="25"/></a>
      </div>
      <div id="particles-js">
	    
		<!-- embed a background-effect by iframe -->
        <div id="iframe-wrap">
            <iframe width="100%" height="876px" frameborder="0" src="js/backeff1/index1.html" id="iframe"></iframe>
        </div>
	  
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
