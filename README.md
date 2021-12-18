<!DOCTYPE html>
<html>
	<head>
		<meta charset="utf-8">
		<title>不可以色色！</title>
		<style type="text/css">
			font
		</style>
	</head>
	<body>
		<!-- 1.多媒体 （音频，视频，和滚动字幕）
		 (1)音视频 本身都是二进制流数据   流媒体		
		(2)本地数据 （在某个磁盘的文件） 
			网络数据 (通过一个接口链接，发来的流数据) 
			音视频的播放，一般都要借助播放器来播放。
			2.html 自带两个基础播放器的元素，分别是音频（audio），视频（vidio）。
			
			3.音视频的播放，有浏览器限制。
			(市场上自主研发的浏览器有：IE  gegogle 火狐  4.safari )
			
			其它浏览器使用其中一种浏览器的内核
				1.autoplay :autoplay 自动播放 ，类似QQ空间背景音乐，打开网页自动播放
				2.controls ：controls 显示播放器控制器，可以进行暂停，调音 等系列播放设置功能 
				3.loop：loop: 播完重复，重复播放 （默认是播完即停）
				4.preload：preload，页面加载时准备视频，加载完成时播放开始（默认开始播放才加载视频）
			-->
		<video width="360px" height="600px" controls="controls" autoplay="autoplay" loop="loop">
			<source src="../res/_mp4%20(11).mp4">
			</source>
		</video>
		<video width="360px" height="600px" controls="controls" autoplay="autoplay" loop="loop">
			<source src="../res/_mp4%20(8).mp4">
			</source>
		</video>
		<video width="360px" height="600px" controls="controls" autoplay="autoplay" loop="loop">
			<source src="../res/_mp4%20(10).mp4">
			</source>
		</video>
		<video width="360px" height="600px" controls="controls" autoplay="autoplay" loop="loop">
			<source src="../res/_mp4%20(6).mp4">
			</source>
		</video>
		<div>
			<input type="text" placeholder="请输入你的弹幕" />
			<input type="button" value="发送弹幕" />
		</div>
		<!-- 滚动字幕：marquee (滚动)+ font (文本)
		direction：滚动方向 上下左右
		behavior="scroll":滚动方式，循环 一次 来回交替 
		scrollamount:滚动速度
		scrolldelay 
		-->
		<marquee direction="left" width="1500px" height="80px" behavior="scroll" bgcolor="#000000" scrollamount="40">
			<font color="yellow" size="17">
				💗💗💗
			</font>
		</marquee>
	</body>
</html>

