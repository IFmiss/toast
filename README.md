# toast & showMessage
这是一个简单的提示插件    适合移动端

演示地址  http://daiwei.org/components/toast/

### toast
* ### position:<br/>  			 
如果toast创建的位置不是body的话就absolute
* ### animateIn（上一个版本是animateStyle）:<br/>  		 
进入的动画
* ### animateOut（上一个版本是没有，写死的fadeout）:<br/>  		 
离开的动画 现在可以使用animate的动画
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


showMessage:function(content,duration,isCenter,animateIn,animateOut){} 五个参数 content:内容,duration:时长,isCenter:是否剧中,animateIn:进入动画效果,animateOut:离开的动画效果
showMessage('未曾遗忘的青春',3000,true,'bounceIn-hastrans','bounceOut-hastrans');

<pre>
showMessage('这是提示信息',5000,false,'bounceIn-hastrans','bounceOut-hastrans');
</pre>
* ### 注意：'-hastrans'是我在animate.css的基础上加的,目的是当元素为绝对定位又想用translate居中时候,修改translate的值无效,故做了一些修改,之前的class也可以正常使用

