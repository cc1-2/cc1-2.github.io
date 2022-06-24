<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="./CSS/index.css">
</head>
<body>
   <div class="bcimage">
    <!-- 页眉区，其中有“首页”和nav导航区两个小块 -->
        <header>
        <p class="floatleft">首页</p>
        <!-- 导航区 -->
            <nav>
                <ul>
                    <li><a href="./introduction.html">我的资料卡 </a></li>
                    <li><a href="./movies.html">我的电影top榜单 </a></li>
                    <li><a href="./dance.html">我爱街舞   </a></li>
                </ul>
            </nav>
        </header>
        <!-- 放置头像区 -->
        <div id="img1">
            <img  src="./images/我的头像.png" alt="">
        </div >
        <!-- 放置姓名和出生日期区 -->
        <div id="p2"><span>CC,</span><span id="span1">2003-2-9</span></div>
        <!-- 放置welcome区 -->
        <div id="p1">Welcom!</div>
   </div>
   <!-- 表格区，包含四个图片小块 -->
    <table>
            <tr>
                <td><img src="./images/首页框.jpg" alt=""></td>
                <td><a href="./introduction.html"><img src="./images/个人资料框.jpg" alt=""></a></td>
            </tr>
            <tr>
                <td><a href="./movies.html"><img src="./images/电影框.jpg" alt=""></a></td>
                <td><a href="./dance.html"><img src="./images/街舞框.jpg" alt=""></a></td>
            </tr>
    </table>
    <div id="spiderman">
        <!-- 蜘蛛侠固定定位，链接表单界面 -->
        <a href="./record.html"><img src="./images/蜘蛛侠.png" alt=""></a>
    </div>
     <footer>感谢你的浏览！</footer>
</body>
</html>
