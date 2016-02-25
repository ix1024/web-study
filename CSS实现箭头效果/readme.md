# CSS实现箭头效果 #

>有时候网页中使用箭头以增强效果，一般的做法是使用图片，今天我们使用CSSCSS来实现“箭头效果”，使用CSS我们必须兼容所有浏览器（IE6、7、8、9、10、+），Chrome，Firefox，Opear...


## Code ##

	<!doctype html>
	<html lang="en">
	<head>
	<meta charset="UTF-8">
	<meta name="Generator" content="Kingwell">
	<meta name="Author" content="Kingwell Leng">
	<meta name="Keywords" content="">
	<meta name="Description" content="">
	<title>Document</title>
	<style type="text/css">
	body,td,div,tr,table{padding:0; margin:0}
	table{width:50%; font-size:14px; font-family:Arial; color:#333}
	
	
	.arrow-top,.arrow-right,.arrow-bottom,.arrow-left{font-size:0; line-height:0; height:0; width:0; cursor:pointer}
	.box{ border:1px solid #CCC; width:100px; height:100px; padding:10px; background:#EEE; margin:10px}
	.arrow{ border-width:50px; border-color:red green blue black; border-style:solid solid solid solid}
	.arrow-bottom{ border-width:50px; border-color:red transparent transparent transparent;  border-style:solid dashed dashed dashed; border-bottom:none;}
	.arrow-left{ border-width:50px; border-color:transparent green transparent transparent;  border-style:dashed solid dashed dashed; border-left:none;}
	.arrow-top{ border-width:50px; border-color:transparent transparent blue transparent;  border-style:dashed dashed solid dashed; border-top:none;}
	.arrow-right{ border-width:50px; border-color:transparent transparent transparent black;  border-style:dashed dashed dashed solid; border-right:none;}
	</style>
	<script type="text/javascript">
	
	</script>
	</head>
	<body>
	<table>
	    <tr>
	        <td>
	            <div class="box">
	                <div class="arrow"></div>
	            </div>
	        </td>
	        <td>
	        <p>.arrow{ border-width:50px; border-color:red green blue black; border-style:solid solid solid solid}</p>
	        </td>
	    </tr>
	    <tr>
	        <td>
	            <div class="box">
	                <div class="arrow-top"></div>
	            </div>
	        </td>
	        <td>
	        <p>.arrow-top{ border-width:50px; border-color:red transparent transparent transparent;  border-style:solid dashed dashed dashed; border-bottom:none;}
	</p>
	        </td>
	    </tr>
	    <tr>
	        <td>
	            <div class="box">
	                <div class="arrow-right"></div>
	            </div>
	        </td>
	        <td>
	        <p>.arrow-right{ border-width:50px; border-color:transparent green transparent transparent;  border-style:dashed solid dashed dashed; border-left:none;}
	</p>
	        </td>
	    </tr>
	    <tr>
	        <td>
	            <div class="box">
	                <div class="arrow-bottom"></div>
	            </div>
	        </td>
	        <td>
	        <p>.arrow-bottom{ border-width:50px; border-color:transparent transparent blue transparent;  border-style:dashed dashed solid dashed; border-top:none;}
	</p>
	        </td>
	    </tr>
	    <tr>
	        <td>
	            <div class="box">
	                <div class="arrow-left"></div>
	            </div>
	        </td>
	        <td>
	        <p>.arrow-left{ border-width:50px; border-color:transparent transparent transparent black;  border-style:dashed dashed dashed solid; border-right:none;}
	</p>
	        </td>
	    </tr>
	</table>
	
	</body>
	</html>

## 效果图 ##
![CSS实现箭头效果](images/23151922-2b062c2c101a49238dc868ca0834c51b.png)