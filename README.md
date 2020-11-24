# o-windows

```
<!DOCTYPE html>
<html lang="ru">
<!--Открытие html-->

<head>
    <!--Открытие тега head-->
    <meta charset="UTF-8">
    <!--Тип кодировки-->
    <title>Главная</title>
    <!--Заголовок-->
    <link rel="shortcut icon" href="source/icons/windows.ico" type="image/ico">
    <link rel="stylesheet" href="source/Style/style.css">
    <!--Подключение CSS-->
</head>
<!--Закрытие тега head-->

<body>
    <!--Открытие тега body-->
    <div id="container">
        <!--Открытие блока container-->
        <div id="header">
            <!--Открытие блока header-->

        </div>
        <!--Закрытие блока header-->
        <div id="navigation">
            <!--Открытие блока navigation-->
            <h3>Главная</h3>
            <!--текст-->
        </div>
        <!--Закрытие блока navigation-->
        <div id="menu">
            <!--Открытие блока menu-->
            <b style="color: #FFF">Меню</b>
            <!--текст-->
            <ul class="breadcrumbs">
                <!--Открытие тега ul-->
                <li>
                    <a href="Windows/Windows_XP.html" class="test">Windows XP</a>
                    <!--Ссылка на страницу Windows XP-->
                </li>
                <li>
                    <a href="Windows/Windows_Vista.html" class="test">Windows Vista</a>
                    <!--Ссылка на страницу Windows Vista-->
                </li>
                <li>
                    <a href="Windows/Windows7.html" class="test">Windows 7</a>
                    <!--Ссылка на страницу Windows 7-->
                </li>
                <li>
                    <a href="Windows/Windows8.1.html" class="test">Windows 8.1</a>
                    <!--Ссылка на страницу Windows 8-->
                </li>
                <li>
                    <a href="Windows/Windows10.html" class="test">Windows 10</a>
                    <!--Ссылка на страницу Windows 10-->
                </li>
            </ul>
            <!--Закрытие тега ul-->
            <br>
            <!--Отступ-->
            <br>
            <!--Отступ-->
            <iframe frameborder="no" scrolling="no" width="100%" height="280"
                src="https://yandex.ru/time/widget/?geoid=11047&lang=ru&layout=vert&type=digital&face=digits"></iframe>
        </div>
        <!--Закрытие блока menu-->
        <div id="content">
            <!--Открытие блока content-->
            </marquee>
            <!--закрытие бегущей строки-->
            <p>Всем привет! Вы находитесь на сайте в котором рассказывается о ОС Microsoft Windows.
                Пока на сайте есть информация о версиях Windows после 2000 года (на этом сайте не будет о Windows
                Server), но вскоре будет информация с Windows 95 по Windows me.</p>
            <!--текст-->
        </div>
        <!--Закрытие блока content-->
        <div id="clear">
        </div>
        <div id="footer">
            <!--Открытие блока footer-->
            <ul class="breadcrumbs">
                <li><a href="/" class="test">Главная</a></li>
                <li style="color: #fff0"><a href="source/">SOURCE CODE</a></li>
            </ul>
            <hr>
            <align="left"> &copy2019-2020
                <a href="https://vk.com/id529848206"><img src="source/icons/Vk.ico"></a>
                <!--ссылка на страницу в ВК-->
                <a href="http://t.me/zaharpetr"><img src="source/icons/telegram.ico"></a>
                <!--Ссылка на аккаунт в Telegram-->
        </div>
        <!--Закрытие блока footer-->
    </div>
    <!--Закрытие блока container-->
</body>
<!--Закрытие тега body-->

</html>
<!--Закрытие html-->
```
```
/*
© 2019-2020 Все права защищены
*/
html, body{
min-height: 100%;
font-family: Arial, sans-serif;
font-size: 15px;
text-align: auto;
background: #000 url("/source/photos/WIP-6th-anniversary-wallpaper-light.jpg") no-repeat;
background-attachment: fixed;
color: #000;
background-repeat: repeat-x;
background-size: 100%;
}
.breadcrumbs{
test-style: none;
display: inline-block;
font-size: 0;
}
.breadcrumbs li{
display: inline-block;
}
.breadcrumbs a{
width: 150px;
line-height: 15px;
display: block;
position: relative;
color: #fff;
font-size: 15px;
padding-left: 10px;
text-decoration: none;
-webkit-transition: ALL 0.5s;
transition: ALL 0.5s;
background: auto;
}
.breadcrumbs .test:hover,
.breadcrumbs .test.active{
background: auto;
}

#container{
background: #fff0;
margin: 5px auto;
width: 100%;
height: 1210px;
}
#header{              
background: #fff0;  
height: 100px;
width: 100%;
text-align: left;
}
#navigation{           
background: #f5f5f5;   
width: 100%;
height: 60px;
text-align: center;
border-radius: 60px ;
}
#menu{                  
background: #107C10;    
float: left;
width: 10%;
height: 1000px;
text-align: center;
border-radius: 20px 20px 20px 20px;
margin: 10px 0px 10px 0px;

}
#content{             
background: #ed812b00;  /*цвет content*/
float: left; 
width: 90%; /*ширина*/
height: 1000px; /*высота*/
text-align: center; /*расположение текста*/
border-radius: 20px ;
margin: 10px 0px 10px 0px;
}

#clear{
clear: both;
}
#footer{
    background: #808080; 
    height: 150px;
    width: 100%;
    color: #000;
    text-align: center;
    border-radius: 20px 20px 20px 20px;
}
```
#### За СССР

