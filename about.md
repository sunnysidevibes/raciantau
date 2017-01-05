---
layout: default
title: About
permalink: /about/
---

<div class="about">
	<div class="intro">
		<img src="/img/about_intro.png" />
	</div>
	<div class="title">
		<img src="/img/about_title.png" />
	</div>
	<div class="container starring">
		<div class="inner starring"></div>
			<img class="back" src="/img/about_starring_drawing.png" />
	</div>
	<div class="cuties">
		<img src="/img/about_cuties.png" />
	</div>
	<div class="container violence">
		<img class="back" src="/img/about_impermanence_back.png" />
		<div class="inner violence"></div>
		<img src="/img/about_violence_word.png" />
	</div>
	<div class="container impermanence">
		<img class="back" src="/img/about_impermanence_back.png" />
		<div class="inner impermanence"></div>
		<img src="/img/about_impermanence_word.png" />
	</div>
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
