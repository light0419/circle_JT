# circle_JT
一个使用canvas编写的圆形进度条
======
##how to use
<body><br>
	<div id="dom"></div><br>
	<script><br>
		$.circleJt({<br>
			domId:'dom',//必需，圆形进度条画布依托的Dom的id\<br>
			radius:20,//必需，圆形进度条的半径\<br>
			pbColor:'green',//必需，圆形进度条的颜色\<br>
      pbWidth:'5',//非必需，原型进度条的宽度\<br>
      value:780,//必需，进度条当前的数值\<br>
      totalValue:1000,//非必需，进度的总值\<br>
      percentage:true,//非必需，是否在原型进度条的中间显示目前进度数\<br>
      fontSize:6,//非必须，进度数的字号\<br>
		});\<br>
	</script>\<br>
</body>\<br>



