<!DOCTYPE html>
<html lang="zh-CN">
<meta name="viewport" content="width=device-width, initial-scale=1, maximum-scale=1, user-scalable=no">
<title>用户中心</title>
<link rel="stylesheet" href="__WCSS__/style.css">
<link rel="stylesheet" href="__WCSS__/meCen.css">
<script src="__WJS__/jquery1.11.1.min.js"></script>
<script type="text/javascript" src="__WJS__/jquery.glide.min.js"></script>
<script type="text/javascript" src="__COM__/layer/layer.js"></script>
<script type="text/javascript" src="__COM__/js/index.js"></script>

<body class="bg96">
<div class="header">
    <div class="userInfo">
		<a href="{:U('User/Personal')}"><div class="toux_icon"><img src="__IMGHEAD__/{$uinfo['img_head']}"></div></a>
    	<div class="uid_xy">
    		<p>UID:{$uinfo['userid']}</p>
    		<p>信用
			<for start="0" end="$uinfo['user_credit']">
				<span><img src="__WIMG__/aix-icon.png"></span>
			</for>
			</p>
    	</div>	
    </div>
    <div class="header_r"> <a href="{:U('User/Personal')}"><img src="__WIMG__/shez-icon.png" alt=""></a></div>
</div>

 <div class="cen_icon">
 	 <ul>
 	 	<li>
 	 		<a href="{:U('Index/turnout')}">
				<p>{$Think.lang.talk}</p>

				<a href="?l=zh-cn" >简体中文</a> | <a href="?l=en-us" >English</a>
 	 		</a>
 	 	</li>

 	 </ul>
 </div>
</div>

</body>

</html>
