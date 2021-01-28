<!DOCTYPE html >
<html lang="en" style="height: 100%; width: 100%;">
<head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, minimum-scale=1.0, user-scalable=no">
    <title>主页</title>
    <meta http-equiv="pragma" content="Pragma">
    <link rel="shortcut icon" href="http://www.x95851.xyz:88/favicon.ico" type="image/x-icon" />
    <!-- <meta http-equiv="cache-control" content="public"> -->
    <meta http-equiv="Cache-Control" content="no-cache, no-store" />
    <meta http-equiv="Cache-Control" content="max-age=43200,must-revalidate" />
    <meta http-equiv="expires" content="3600">  
    <Meta http-equiv="Expires" Content="3600"> 
    <script type="text/javascript" src="http://www.x95851.xyz:88/JS/cook.js"></script>
    <style>*
        {margin:0;padding:0;}
        #wrap{width:800px;margin:0 auto;border:3px solid yellow;}
        #header{width:100%;border:3px solid red;}
        #main{width:100%;border:3px solid green;}
        a:link {color:#7B68EE;}      /* 未访问链接#00FFFF*/
        a:visited {color:#5749ac;}  /* 已访问链接 */
        a:hover {color:#FF00FF;}  /* 鼠标移动到链接上 */
        a:active {color:#0000FF;}  /* 鼠标点击时 */
        body {text-align: center;} table {margin: auto;}
        table, td, th{border:1px solid black;}td{padding:15px;}
    </style>
      <head>
        <style type="text/css">
             .top li a{
             /* 设置链接内容显示的格式*/
                 display: block; /* 把链接显示为块元素可使整个链接区域可点击 */
                 color:white;
                 text-align: center;
                 padding: 3px;
                 overflow: hidden;
                 text-decoration: none; /* 去除下划线 */
             }
             .top li {
                 float:left; /* 使li内容横向浮动，即横向排列  */
                 margin-right:2%;  /* 两个li之间的距离*/
                 position: relative;
                 overflow: hidden;
             }
             /* body{
                 background:#eff3f5;
             } */
        </style>
        <link type="text/css" rel="styleSheet"  href="/top_2.css" />
</head>
<script src="https://sdk.jinrishici.com/v2/browser/jinrishici.js" charset="utf-8"></script>
 
<body onload="divhidden();" background="img/background/background3.jpg"style=" background-repeat:no-repeat ;background-size:100% 100%;background-attachment: fixed;">
    <div class="top" style="height:auto;width:160%;margin-left: 0;background:#D6934D;position: fixed;top: 0;/*离顶部的距离为0*/margin-bottom: 5px;">
        <center> 
        <ul style="width: auto;list-style-type: none;white-space:nowrap;overflow: hidden;margin-left: 5%;  /*margin-top: 0;*/  padding: 0;">
            <li><a href="/"><b>首页</b></a></li>
            <div  id="delete0" style="display:block;margin-right:auto;">
                <h style="color:#C71585" id="username"></h>
                <span  style="color:green" type="button" onclick="delcook()">注销</span>
            </div>
            <div   id="delete1" style="display:block;margin-right:auto ">
                <a href="/"  style="color:green;text-decoration: none;">登录/注册</a>
            </div>
        </ul>
        </center>
    </div>
    
    <div style="margin-top:80px;top:0;width:100%;">
        <div style='height:80px;width:100%;'>
            <h1 style="color:red  ; text-align:center" >❤️API❤️</h1>
        </div>
        <span id="jinrishici-sentence"style="display:block;text-align:center;color:#00FF00;" >正在加载今日诗词....</span><br>
        <div id="main" style="text-align:center;padding: hight 555;" >
            <table style="text-align:center;">
                <tr><th><a style="display:none"></a></th></tr>
                
                <tr><th><a style="display:block" href="API/coding">编解码工具</a></th></tr>
                <tr><th><a style="display:block" href="API/music">音乐解析</a></th></tr>
                <tr><th><a style="display:none" href="API/mail">发送邮件</a></th></tr>
                <tr><th><a style="display:block" href="API/robot">聊天机器人</a></th></tr>
                <tr><th><a style="display:block" href="API/OCR">百度OCR</a></th></tr>
                <tr><th><a style="display:block"href="API/weather">天气预报</a></th></tr>
                <tr><th><a style="display:block" href="API/mycode">my简单加密</a></th></tr>
                <tr><th><a style="display:none" href="API/正则API/zz.html">正则测试</a></th></tr>
                <tr><th><a style="display:block" href="API/md及SHA加密/index.html">md及SHA加密</a></th></tr>
                <tr><th><a style="display:block" href="API/计算器/index.html">计算器</a></th></tr>
                <tr><th><a style="display:block" href="API/AESAPI">AES/CBC/PKCS5Padding</a></th></tr>
                <tr><th><a style="display:block" href="API/文件保存">文件上传</a></th></tr>
                <tr><th><a style="display:none" href="API/update/update.php">在线更新检测</a></th></tr>
                <tr><th><a style="display:block" href="API/lanzouyun">蓝奏云解析</a></th></tr>
                <tr><th><a style="display:block" href="API/发送消息给我/send.html">微信发消息</a></th></tr>
                <tr><th><a style="display:block" href="API/IP/">ip查询</a></th></tr>
                <tr><th><a style="display:block" href="API/ProxyIP">代理ip</a></th></tr>
                <tr><th><a style="display:block" href="API/抖音解析/抖音解析.html">抖音短视频解析</a></th></tr>
                <tr><th><a style="display:none" href="API/CODE">验证码</a></th></tr>
                <tr><th><a style="display:block" href="others/time">各网站时间</a></th></tr>




               
            </table>
        </div>
    </div>
    <div class='footer' style="text-align:center;display:block">
        <p style="display:block">个人专属网站，他人使用时，如有风险，本人概不负责！
    </div>
</body>
    <script>
        // $(document).ready(function(){
        // function t(){var e = $(".footer");var h = e.offset().top + e.height();if(h < document.body.clientHeight){$(".footer").css({position:"fixed",left:"20%",bottom:"0px"});return;}
        // function t2(){var a = $(document).scrollTop()+document.documentElement.clientHeight;if(a >= h){$(".footer").css({position:"fixed",left:"20%",bottom:"0px"});}else{$(".footer").removeAttr("style");}}t2();$(document).resize(t2);$(document).scroll(t2);}t();
        // });
    </script>
</html>
<script type="text/javascript" src="/JS/top.js"></script>
<script type="text/javascript">
        function divhidden(){
            cook=getck("binggan");
            if(!cook){
                document.getElementById("jinrishici-sentence").style.display="none";
            }
        }
</script>

