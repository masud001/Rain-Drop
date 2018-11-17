# Rain-Drop
this is rain drop effect on canvas

HOW TO INSTALL IN YOUR PROJECT
*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*

STEP #1
--------
	Make a section OR div with id OR class Example: <div class="raindrop"></div
	you can use background-images your own choice on that div or section and make it's 	position "relative".

	you can add css like that : 
	.raindrop{
		background-color: #ededed;
		background-image: url('your images path');
		background-position: center;
		background-repeat: no-repeat;
		-webkit-background-size: cover;
		background-size: cover;
		background-attachment: fixed;
		width: 100%;
		height: 500px;
		position: relative;
	}

STEP #2
-------
	add three script, bottom of your html pages those script are : (this three file are 	mandetory....)

	<script src="jquery-3.3.1.min.js"></script>
	<script src="jquery-ui.min.js"></script>
	<script src="raindrops.js"></script> 


STEP #3
-------
	initiate raindrop function inside script tag bottom of the html pages

	example :
	<!-- init rain drop -->
	<script>
		$(document).ready(function(){
			"use strict";
			$(".raindrop").raindrops({
				color:"#f2f2f2",
				canvasHeight:50,
				rippleSpeed:.03,
				frequency:3,
				density:.01
			});
		});
	</script> 





