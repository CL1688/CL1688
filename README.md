
<html><head> 
<title></title> 
<meta charset="utf-8"> 
<!--响应式--> 
<meta name="viewport" content="width=device-width, initial-scale=1, maximum-scale=1, user-scalable=no"><Style>/*这个是css样式*/ body .center {text-align:center;}
{
font-size:75%;
font-family:verdana,arial,'sans serif';
background-image:url('gradient.png');
background-repeat:repeat-x;
background-color:#FFFFF0;
color:#000080;
margin:70px;
}

h1 {font-size:200%;}
h2 {font-size:140%;}
h3 {font-size:110%;}

th {background-color:#ADD8E6;}

ul {list-style:circle;}
ol {list-style:upper-roman;}

a:link {color:#000080;}
a:hover {color:red;}</Style>
<script src="js/jq.js"></script></head>  
<body id="v1">

<h1 class="center">嗨！大家好！</h1> 
<hr id="v3"> 
<p id="v4"></p> 
<h2 id="v5"> 
<p class="center" style="font-family:arial;color:orange">
我现在出发开始吧！</p>😀💪</h2> 
<p id="v8"></p> 
<p id="v6"></p> 
<h8 class="center">这是学习创建的文件</h8>
<h6><p style="font-family:arial;color:red">大家好！介绍一下本人：我来自湖北，是草根打工人</h6> 
<a></a>
<p id="v9"></p> 
</body><img src="Screenshot_20220411_220620_com.rarible.android.release_edit_43375431541818.jpg"><img src="Screenshot_20220320_140342_com.baidu.netdisk.jpg""><img src="Screenshot_20220411_220644_com.rarible.android.release_edit_43405738517855.jpg">
</html>
<script>
function changeImage(){
    //通过查看src中是否有bulbon这个单词来判断当前状态并切换到另外一种状态
    element=document.getElementById('myimage');
    if (element.src.match("bulbon")){
        //如果src属性中有bulbon这个单词，则将其改为下面这个src
        element.src="https://www.w3cschool.cn/statics/images/course/pic_bulboff.gif";
    }
    else{
        //如果src属性中没有bulbon这个单词，则将其改为这个src
        element.src="https://www.w3cschool.cn/statics/images/course/pic_bulbon.gif";
    }
}
</script>
<img id="myimage" onclick="changeImage()" src="https://www.w3cschool.cn/statics/images/course/pic_bulboff.gif" width="100" height="180">
