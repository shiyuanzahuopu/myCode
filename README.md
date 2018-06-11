<!DOCTYPE html>
<html>
<head>
	<title>我的个人主页</title>
	<meta charset="utf-8">
	<meta name=”viewport” content=”width=device-width, initial-scale=1″ />
	<link rel="stylesheet" type="text/css" href="personal.css">
	<link rel="stylesheet" href="font/iconfont.css">
	<link rel="stylesheet" href="font1/iconfont.css">
</head>

<body>

	<div id="nav">                                              <!-- 顶部导航栏 -->
		<div id="top">
			<span>我的个人主页</span>
		</div>
		<ul class="guide">
			<li class="link"><a class="scroll" href="#information">个人信息</a></li>
			<li class="link"><a class="scroll" href="#works">作品预览</a></li>
			<li class="link"><a class="scroll" href="#contact">联系我吧</a></li>
		</ul>
	</div>

	<a name="information"></a>									
    <div id="blank"></div>										<!-- 被导航栏遮盖的部分 -->

	<div id="main">														  <!-- 主体部分 -->
		<div class="container">										<!-- 中间显示内容 -->
			<div class="information">                         <!-- 个人资料展示 -->
				<div class="introduction">
					
				</div>
				<div class="photo">
					<img id="myphoto" src="y&f.jpg">
				</div>	
			</div>
			
			<div class="works" >									<!-- 个人作品缩略图 -->
				<a name="works"></a>
				<div class="headline">
					<h1>PORTFOLIO</h1>
				</div>
				<hr class="star_dark"></hr>
				<ul class="box">
					<a href="http://www.baidu.com" target="_blank"><li class="item"></li></a>
					<li class="item"></li>
					<li class="item"></li>
					<li class="item"></li>
				</ul>
			</div>	
			
			<div class="contact">									<!-- 与我联系 -->
				<a name="contact"></a>
				<div class="headline">
					<h1>CONTACT ME</h1>
				</div>
				<hr class="star_dark"></hr>
				<div class="input">
					<input type="text" name="" value="Name"></input>
					<input type="text" name="" value="Email Address"></input>
					<input type="text" name="" value="Phone Number"></input>
					<input type="text" name="" value="Message" id="Message"></input>
					<button type="submit" value="send" id="send">Send</button>
				</div>
				<div class="supplementary">
					<p>Want to get in touch with me? Be it to request more info about myself or my experience, to ask for my resume, tips on how to solve your sudoku, random questions about the universe and the meaning of life, or even if only for some nice Fika here in stunning Toronto... just feel free to drop me a line anytime.</p>
					<br />
					<p>I promise to reply A.S.A.P.</p>
					<p id="note">Note: No spam/soliciting pour moi, merci :)</p>
				</div>
			</div>								
		
		</div>

	</div>


	<div id="friendlink">							<!-- 社交网站链接 -->
		<div id="about" class="friendlink">
			<h3 class="about">ABOUT THIS PAGE</h3>
			<p id="made">Made with <i class="iconfont icon-beizi"></i> and <i class="iconfont icon-yinle"></i> by <a href="#" id="hhb">Hu Hangbin</a></p>
		</div>
		<div id="around" class="friendlink">
			<h3 class="around">AROUND THE WEB</h3>
			<ul id="font">
				<a href="https://im.qq.com/index.shtml" target="_blank">
					<li class="font-item">
						<i class="iconfont icon-qq"></i>
					</li>
				</a>
				<a href="https://weibo.com/" target="_blank">
					<li class="font-item">
						<i class="iconfont icon-weibo"></i>
					</li>
				</a>
				<a href="https://wx.qq.com/" target="_blank">
					<li class="font-item">
						<i class="iconfont icon-wechat"></i>
					</li>
				</a>
				<a href="https://github.com/github" target="_blank">
					<li class="font-item">
						<i class="iconfont icon-github"></i>
					</li>
				</a>				
			</ul>
		</div>
	</div>										
	

	<div id="footer">												<!-- 底栏 -->
		<p id="writer">Written and coded by Hu Hangbin</p>
	</div>											



	<script type="text/javascript">
		
	</script>
</body>
</html>

