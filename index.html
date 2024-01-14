<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charSet="utf-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge,chrome=1" />
    <meta http-equiv="Cache-Control" content="no-transform" /> 
    <meta http-equiv="Cache-Control" content="no-siteapp" />
    <meta name="referrer" content="never">
    <meta name="renderer" content="webkit" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no" />
    <title>在线美女热舞</title>
    <link rel="stylesheet" href="style.css">
	<style>
	body {margin:0;}
	
	ul {
	  list-style-type: none;
	  margin: 0;
	  padding: 0;
	  overflow: hidden;
	  background-color: #FFFFCC;
	  position: fixed;
	  top: 0;
	  width: 100%;
	}
	
	li {
	  float: left;
	}
	
	li a {
	  display: block;
	  color: white;
	  text-align: center;
	  padding: 14px 16px;
	  text-decoration: none;
	}
	
	li a:hover:not(.active) {
	  background-color: #FFC0CB;
	}
	
	.active {
	  background-color: #FFC0CB;
	}
	
	</style>
</head>  
<?php


function sxvip(){
$list = file_get_contents('sxvip.dat');
$myfile = fopen("sxvip.dat", "w");
$sxvip = ($list+1);
fwrite($myfile,"$sxvip");
fclose($myfile);
return $sxvip;
}

function slzxrs(){
//首先你要有读写文件的权限，首次访问肯不显示，正常情况刷新即可
$online_log = "slvip.dat"; //保存人数的文件到根目录,
$timeout = 30;//30秒内没动则认为掉线
$entries = file($online_log);
$temp = array();
for ($i=0;$i<count($entries);$i++){
$entry = explode(",",trim($entries[$i]));
if(($entry[0] != getenv('REMOTE_ADDR')) && ($entry[1] > time())) {
array_push($temp,$entry[0].",".$entry[1]."\n"); //取出其他浏览者的信息,并去掉超时者,保存进$temp
}}
array_push($temp,getenv('REMOTE_ADDR').",".(time() + ($timeout))."\n"); //更新浏览者的时间
$slzxrs = count($temp); //计算在线人数
$entries = implode("",$temp);
//写入文件
$fp = fopen($online_log,"w");
flock($fp,LOCK_EX); //flock() 不能在NFS以及其他的一些网络文件系统中正常工作
fputs($fp,$entries);
flock($fp,LOCK_UN);
fclose($fp);
// echo "观看人数：".$slzxrs."人";
return $slzxrs;
}

?>  



    <section id="main">
        <video id="player" src="http://api.92fh.cam/api/mvsp?apiKey=b7c5108c7fdcdeb1c961e5f2353ff6b6" controls controlsList="nodownload" webkit-playsinline playsinline></video>
    </section>

<h6><center><p>当前在线：<?php echo slzxrs(); ?> 人_ 累计观看：<?php echo sxvip(); ?> 人</p></center></h6>

<?php

echo "共有23650个视频";


?>
    <section id="buttons">
        <button id="switch">自动切换</button>
        <button id="next">下一位</button>

 


   </section>
    <script>
    
    (function (window, document) {
        
        if (top != self) {
            window.top.location.replace(self.location.href);
        }
        var get = function (id) {
            return document.getElementById(id);
        }
        var bind = function (element, event, callback) {
            return element.addEventListener(event, callback);
        }
        var auto = true;
        var player = get('player');
        var randomm = function () {
            player.src = 'http://api.92fh.cam/api/mvsp?apiKey=b7c5108c7fdcdeb1c961e5f2353ff6b6';
            player.play();
        }
        bind(get('next'), 'click', randomm);
        bind(player, 'error', function () {
            randomm();
        });
        bind(get('switch'), 'click', function () {
            auto = !auto;
            this.innerText = '自动: ' + (auto ? '开' : '关');
        });
        bind(player, 'ended', function () {
            if (auto) randomm();
        });
    })(window, document);
    </script>
<script>
    document.addEventListener('contextmenu', event => event.preventDefault());
    document.addEventListener('keydown', event => {
        if (event.keyCode == 123 || (event.ctrlKey && event.shiftKey && event.keyCode == 73)) {
            event.preventDefault();
        }
    });
</script>
</body>
</html>