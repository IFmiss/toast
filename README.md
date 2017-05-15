# toast & showMessage
这是一个简单的提示插件    适合移动端
### toast
* ### position:<br/>  			 
如果toast创建的位置不是body的话就absolute
* ### animateStyle:<br/>  		 
进入的动画
* ### padding: <br/>  
padding
* ### background: <br/>
背景色
* ### borderRadius:<br/>
圆角
* ### duration: <br/>
定时器时间
* ### fontSize:  <br/>
字体大小
* ### content:  <br/>
提示内容
* ### color:  <br/> 
文字颜色
* ### top:    <br/>  
bottom底部的位置    具体的数值 或者center  垂直居中
* ### zIndex: <br/>         
层级
* ### isCenter:   <br/>
是否垂直水平居中显示
* ### closePrev: 		 <br/>	
在打开下一个toast的时候立即关闭上一个toast

<pre>
$('div_toast').toast({
    content:'你好啊！'
});
</pre>


showMessage:function(content,duration,isCenter,animateStyle){} 四个参数 content:内容,duration:时长,isCenter:是否剧中,animateStyle:动画效果
showMessage('未曾遗忘的青春',3000,true,fadeInUp);

<pre>
showMessage('这是提示信息',5000,false,'fadeIn');
</pre>

演示地址 http://www.daiwei.org/works/components/toast/
