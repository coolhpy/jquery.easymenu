#jquery_easymenu

===概要===

这个一个jQuery的插件，它可以让您创建下拉试的导航菜单更加简单。

    无限子菜单显示
    兼容IE6+、FireFox、Chrome等
    轻量级，源码（含注释）还不到4K
    符合标准的html代码

===示例===

http://demo.hpyer.cn/js/easymenu/easymenu.html

===使用===

<html>
<head>
<script type="text/javascript" src="http://ajax.googleapis.com/ajax/libs/jquery/1.4/jquery.min.js"></script>
<link rel="stylesheet" type="text/css" href="jquery.easymenu.css" />
<script type="text/javascript" src="jquery.easymenu.js"></script>
</head>
<body>
<ul id="menu">
    <li><a href="#">Home</a></li>
    <li><a href="#">Tutorials</a>
    <ul>
        <li><a href="#">2nd Nav Link</a>
            <ul>
                <li><a href="#">3rd Nav Link</a></li>
                <li><a href="#">3rd Nav Link</a></li>
            </ul>
        </li>
        <li><a href="#">2nd Nav Link</a></li>
        </ul>
    </li>
</ul>
<script>$('#menu').easymenu();</script>
</body>
</html>
