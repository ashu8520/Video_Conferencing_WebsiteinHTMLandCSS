1.-  VIDEO CONFERENCING WEBSITE USING HTML LANGUGE.
<!DOCTYPE html>
<html lang="en">
<head>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>video Conferencing website</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
<div class="header">
    <nav>
        <img src="images/logo.png" class="logo">
        <ul>
            <li><img src ="images/live.png"class="active"></li>
            <li><img src ="images/video.png"></li>
            <li><img src ="images/notification.png"></li>
            <li><img src ="images/message.png"></li>
            <li><img src ="images/users.png"></li>
            <li><img src ="images/setting.png"></li>
         </ul>
    </nav>
    <div class="container">
        <div class="top-icons">
            <img src="images/search.png">
            <img src="images/menu.png">
        </div>
    <div class="row">
        <div class="col-1"></div>
            <img src="images/image.png" class="host-img">
                <div class="contarols">
                <img src="images/chat.png">
                <img src="images/disconnect.png">
                <img src="images/call.png"class="call-icon">
                <img src="images/mic.png">
                <img src="images/cast.png">
            </div>
            <div class="col-2">
                <div class="joined">
                    <p>PEOPLE ARE JOINED</p>
                    <div>
                        <img src="images/per-1.jpg">
                        <img src="images/per-2.jpg">
                        <img src="images/per-3.jpg">
                        <img src="images/per-4.jpg">
                        <img src="images/per-5.jpg">
                        <img src="images/per-6.jpg">
                        <img src="images/per-7.jpg">
                        <img src="images/per-8.jpg">
                        <img src="images/per-9.jpg">
                    </div>
                </div>
                <div class="invite">
                    <p>INVITE A MORE PEOPLE</p>
                    <div>
                        <img src="images/emp-1.jpg">
                        <img src="images/emp-2.jpg">
                        <img src="images/emp-3.jpg">
                        <img src="images/emp-4.jpg">
                        <img src="images/emp-5.jpg">
                        <img src="images/emp-6.jpg">
                        <img src="images/emp-7.jpg">
                        <img src="images/emp-8.jpg">
                        <img src="images/emp-9.jpg">
                        <img src="images/emp-10.jpg">
                        <img src="images/emp-11.jpg">
                        <img src="images/emp-12.jpg">
                    </div>
                </div>
                <div class="live">
                    <p>LIVE A PEOPLE</p>
                        <img src="images/peo-1.jpg">
                        <img src="images/peo-2.jpg">
                        <img src="images/peo-3.jpg">
                        <img src="images/peo-4.jpg">
                        <img src="images/peo-5.jpg">
                        <img src="images/peo-6.jpg">
                        <img src="images/peo-7.jpg">
                        <img src="images/peo-8.jpg">
                        <img src="images/peo-9.jpg">
                        <img src="images/peo-10.jpg">
                        <img src="images/peo-11.jpg">
                        <img src="images/peo-12.jpg">
                    </div>
                </div>
            </div>
        </div>
    </div>
</body>
</html>


2.-  VIDEO CONFERENCING WEBSITE USING CSS LANGUGE.
*{
    margin:0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'poppins',sans-serif;
}
nav{
    position: fixed;
    top: 0;
    left: 0;
    bottom: 0;
    background: #000707;
    width: 120px;
    padding: 10px 0;
}
.header{
    width: 100%;
    height: 185vh;
    background: #0bd3c6;
    position: absolute;
}
nav .logo{
    width: 100px;
    display: block;
    margin: auto;
    cursor: pointer;
}
nav ul{
    margin-top: 160px;
}
nav ul li{
    list-style: none;
}

nav ul li img{
    width: 50px;
    display: block;
    margin: 10px auto;
    padding: 10px;
    cursor: pointer;
    opacity: 0.5;
    border-radius: 10px;
    transition: opacity 0.5s, background0.3s;
}

nav ul li img:hover{
    opacity: 1;
    background: #03c058;
}

.active{
    opacity: 1;
    background: #5a91e9;
}

.live{
    opacity: 1;
    background: rgb(4, 135, 145);
}

.container{
    margin-left: 120px;
    padding: 0.2.5%;
}

.top-icons{
    display: flex;
    align-items: center;
    justify-content: flex-end;
    padding: 25px 0;
}
.top-icons img{
    width: 25px;
    margin-left: 40px;
    cursor: pointer;
}
.row{
    margin-top: 0px;
    display: flex;
    justify-content: space-between;
}
.col-1{
    flex-basis: 0%;
}
.col-2{
    flex-basis: 50%;
}
.host-img{
    width: 50%;
    height: 25%;
    border-radius: 30px;
}
.joined{
    width: 80%;
    height: 25%;
    border-radius: 30px ;
}
.invite{
    width: 80%;
    height: 25%;
    border-radius: 30px ;
}
.live{
    width: 80%;
    height: 25%;
    right: 0%;
    border-radius: 25px ;
}
.contarols{
    display: flex;
    align-items: center;
    justify-content: flex;
}
.contarols img{
    top: 0px;
    bottom: 10px;
    cursor: pointer;
    transition: transform 0.5s;
}
.contarols .call-icon{
    width: 80px;
}
.contarols img:hover{
    transform: translateY(-10px);
}
.joined{
    background: #4ae879;
    border-radius: 20px;
    padding: 50px 50px 50px;
    color:#fff;
    margin-bottom: 20px;
}
.joined div{
    margin-top: 0px;
    margin-left: 0px;
    display: grid;
    grid-template-columns: 70px 70px 70px ;
    grid-gap: 5px;
}
.joined img{
    margin-top: 0px;
    width: 90%;
    margin-left: 10px;
    border-radius: 20px;
    cursor: pointer;
}
.invite{
    background: #6b8bbf;
    border-radius: 20px;
    padding: 35px 35px 360px;
    color:#fff;
    margin-bottom: 20px;
}
.invite img{
    margin-top: 20px;
    width: 55px;
    margin-left: 30px;
    border-radius: 50%;
    cursor: pointer;
}
.live{
    background: #07224e;
    border-radius: 40px;
    padding: 40px 40px 40px;
    color:#fff;
    margin-bottom: 20px;
}
.live img{
    margin-top: 20px;
    width: 50px;
    margin-left: 10px;
    border-radius: 50%;
    cursor: pointer;
}


3.- OUTPUT SCREEN IMAGE
![Screenshot (69)](https://github.com/ashu8520/Video_Conferencing_WebsiteinHTMLandCSS/assets/140008822/6fe483ac-4a61-4f05-ab7c-bfac92721381)
