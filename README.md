# toast & showMessage
这是一个简单的提示插件    适合移动端
toast
* position:  			  "absolute", 		       如果toast创建的位置不是body的话就absolute
* animateStyle:  		  "fadeInUp",				          进入的动画
* padding:              "10px 20px",              padding
* background:           "rgba(7,17,27,0.66)",     背景色
* borderRadius:         "6px",                     圆角
* duration:             3000,                     定时器时间
* fontSize:             14,                     字体大小
* content:              "这是一个提示信息",        提示内容
* color:                "#fff",                   文字颜色
* top:            	  "80%",                	bottom底部的位置    具体的数值 或者center  垂直居中
* zIndex:               1000001,                	层级
* isCenter:   		  true, 					   是否垂直水平居中显示
* closePrev: 			  true, 					在打开下一个toast的时候立即关闭上一个toast

$('div_toast').toast({
    content:'你好啊！'
});


showMessage: 四个参数 content:内容,duration:时长,isCenter:是否剧中,animateStyle:动画效果
$dw.showMessage('未曾遗忘的青春',3000,true,fadeInUp);


演示地址 http://www.ifmisswqq.com/works/Others/toast/
