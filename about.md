---
layout: default
title: About
permalink: /about/
---

<div class="about">
{% include ads01.html %}
{% include ad-mobile.html id="pw_adbox_79419_6_0" %}

 <img src="/img/ABOUT.png" />
<div class="startout">
	Links to start out!
  <div class="links">
    <a href="/archives/Battlemon">
    <div class="story">
      <div class="title">Battlemon</div>
      <img src="/img/content/poster01-bmon.png" />
      <div class="subtitle">The First Racia Story</div>
    </div>
    </a>
      <a href="/archives/Desperate+Times">
    <div class="story">
      <div class="title">Desperate Times</div>
      <img src="/img/content/POSTER01e-DESPERATE-TIMES.png" />
      <div class="subtitle">The First "RACINATAU" Story</div>
    </div>
    </a>
      <a href="/archives/Collision+2016">
    <div class="story">
      <div class="title">COLLISION 2016</div>
      <img src="/img/content/poster02-collision.png" />
      <div class="subtitle">The First Antau Story</div>
    </div>
    </a>
  </div>
</div>
	 {% include ad-skyscraper.html side="left" id="pw_adbox_79458_3_0" %}
	 {% include ad-skyscraper.html side="right" id="pw_adbox_79458_3_1" %}
</div>

<script>
window.onscroll = function(){
	console.log(window.scrollY);
   if(window.scrollY >= 790) { // change target to number
      $('.starring').css('background-attachment', 'scroll');
   }else{
      $('.starring').css('background-attachment', 'fixed');
	 }

	  if(window.scrollY >= 1180) { // change target to number
	 		$('.violence').css('background-attachment', 'scroll');
	  }else{
	 		$('.violence').css('background-attachment', 'fixed');
	  }

			  if(window.scrollY >= 1693) { // change target to number
			 		$('.impermanence').css('background-attachment', 'scroll');
			  }else{
			 		$('.impermanence').css('background-attachment', 'fixed');
			  }
};
</script>
