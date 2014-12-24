Exceptio Slider
==============

Simple jQuery Slider

```
$(document).ready(function(){
		$('.test').exceptioSlider({
			fx:'fade',
			afterSlide : function(){
				console.log('after');
			},
			beforeSlide : function(){
				console.log('before');
			}
		});	
	});	
```
