Exceptio Slider
==============

Simple jQuery Slider

```
defaultOptions = {
		fx : 'slide', //slide,fade
		direction : 'right', //slide direction in slide fx
		sliderWidth : '100%', //ul element width
		wrapClass : null, //if you wish to add additional class in wrapper
		textAlign : 'center', //li element text-align
		pushOnHover : true, //apply push on mouse hover		
		delay : 5000, //fx duration
		beforeSlide : function(){}, //exec before slide
		afterSlide : function(){} //exec after slide		
	}
	
$(document).ready(function(){
		$('.test').exceptioSlider({
			fx : 'fade'
		});	
	});
	
<ul class="test">
	<li>123</li>
	<li>456</li>
	<li>789</li>
</ul>
```
