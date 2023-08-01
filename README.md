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


3.- all image files
![emp-1](https://github.com/ashu8520/Video_Conferencing_WebsiteinHTMLandCSS/assets/140008822/d37e5c9e-1c9f-41df-8f6e-3e95d7dee48a)
![Uploading disconnect.png…]()
![chat](https://github.com/ashu8520/Video_Conferencing_WebsiteinHTMLandCSS/assets/140008822/8b6b3191-99b8-4e13-8f30-94e239cc460a)
![Uploading cast.png…]()
![Uploading call.png…]()
![Uploading video.png…]()
![Uploading users.png…]()
![Uploading setting.png…]()
![Uploading search.png…]()
![per-9](https://github.com/ashu8520/Video_Conferencing_WebsiteinHTMLandCSS/assets/140008822/9d7c924a-6612-436d-948a-e28f689636dd)
![per-8](https://github.com/ashu8520/Video_Conferencing_WebsiteinHTMLandCSS/assets/140008822/81606312-a1b6-47a8-ab7a-dbfccd152281)
![per-7](https://github.com/ashu8520/Video_Conferencing_WebsiteinHTMLandCSS/assets/140008822/8cbeb130-5b09-4b30-bdc6-b48c85832594)
![per-6](https://github.com/ashu8520/Video_Conferencing_WebsiteinHTMLandCSS/assets/140008822/71a0da38-f927-424c-b42e-4acce47b2524)
![per-5](https://github.com/ashu8520/Video_Conferencing_WebsiteinHTMLandCSS/assets/140008822/696ec103-1d38-472f-b217-324b310b46d5)
![per-4](https://github.com/ashu8520/Video_Conferencing_WebsiteinHTMLandCSS/assets/140008822/469b52ce-e599-4954-8666-9f7b21578f38)
![per-3](https://github.com/ashu8520/Video_Conferencing_WebsiteinHTMLandCSS/assets/140008822/442b9657-731e-44b3-ada7-aff29a999af3)
![per-2](https://github.com/ashu8520/Video_Conferencing_WebsiteinHTMLandCSS/assets/140008822/bb8b724e-55d0-4583-9431-b2e48b2bab0e)
![per-1](https://github.com/ashu8520/Video_Conferencing_WebsiteinHTMLandCSS/assets/140008822/dcae94b0-b0e5-470f-9217-42509caabe78)
![peo-12](https://github.com/ashu8520/Video_Conferencing_WebsiteinHTMLandCSS/assets/140008822/0aebb74d-729e-439c-bcbb-7b86cec0de6d)
![peo-11](https://github.com/ashu8520/Video_Conferencing_WebsiteinHTMLandCSS/assets/140008822/f5cbdc8d-5c6f-4a6b-93ac-f145a3f2366b)
![peo-10](https://github.com/ashu8520/Video_Conferencing_WebsiteinHTMLandCSS/assets/140008822/187f11d0-26ae-4f46-a3e0-33d6c5a2c1f9)
![peo-9](https://github.com/ashu8520/Video_Conferencing_WebsiteinHTMLandCSS/assets/140008822/221befe2-3b80-4151-aa27-06b1385608de)
![peo-8](https://github.com/ashu8520/Video_Conferencing_WebsiteinHTMLandCSS/assets/140008822/50f218bf-6985-434e-a3c1-5264896373e8)
![peo-7](https://github.com/ashu8520/Video_Conferencing_WebsiteinHTMLandCSS/assets/140008822/e9381984-8e10-40f9-acd5-ddff90f20bdc)
![peo-6](https://github.com/ashu8520/Video_Conferencing_WebsiteinHTMLandCSS/assets/140008822/49bfc7a2-12ad-4ffb-8b6b-21f65af4ce27)
![peo-5](https://github.com/ashu8520/Video_Conferencing_WebsiteinHTMLandCSS/assets/140008822/b2cbe03e-fbce-447f-aade-baab5d4d83a7)
![peo-4](https://github.com/ashu8520/Video_Conferencing_WebsiteinHTMLandCSS/assets/140008822/0ca339c4-5b13-4846-9443-18c7f585000b)
![peo-3](https://github.com/ashu8520/Video_Conferencing_WebsiteinHTMLandCSS/assets/140008822/947167ea-56a7-4a9e-b9bf-c998bb6336a4)
![peo-2](https://github.com/ashu8520/Video_Conferencing_WebsiteinHTMLandCSS/assets/140008822/c4ed6abd-f5ce-4525-b691-bfd4eb24e0ca)
![peo-1](https://github.com/ashu8520/Video_Conferencing_WebsiteinHTMLandCSS/assets/140008822/772f71cf-1781-4aad-bd9b-105f99291d21)
![Uploading notification.png…]()
![Uploading mic.png…]()
![Uploading message.png…]()
![Uploading menu.png…]()
![Uploading logo.png…]()
![Uploading live.png…]()
![Uploading image.png…]()
![emp-12](https://github.com/ashu8520/Video_Conferencing_WebsiteinHTMLandCSS/assets/140008822/ec1abce8-3b1a-4f78-9dca-38e1c8e69c98)
![emp-11](https://github.com/ashu8520/Video_Conferencing_WebsiteinHTMLandCSS/assets/140008822/634d1cfe-928f-47c9-9b00-3717d537600e)
![emp-10](https://github.com/ashu8520/Video_Conferencing_WebsiteinHTMLandCSS/assets/140008822/51a10c14-ffba-4492-9fdc-f41601960302)
![emp-9](https://github.com/ashu8520/Video_Conferencing_WebsiteinHTMLandCSS/assets/140008822/eb8f7889-a851-42c9-95cd-2212eda576fe)
![emp-8](https://github.com/ashu8520/Video_Conferencing_WebsiteinHTMLandCSS/assets/140008822/c70edb40-b195-45b4-9446-73f573fe1df3)
![emp-7](https://github.com/ashu8520/Video_Conferencing_WebsiteinHTMLandCSS/assets/140008822/f7568078-1b76-47fa-aea0-c7b692097930)
![emp-6](https://github.com/ashu8520/Video_Conferencing_WebsiteinHTMLandCSS/assets/140008822/ce8b7af9-6215-437c-9255-ceeed203febe)
![emp-5](https://github.com/ashu8520/Video_Conferencing_WebsiteinHTMLandCSS/assets/140008822/af1c81d3-8ba1-4fe7-bc9b-03e9e872656f)
![emp-4](https://github.com/ashu8520/Video_Conferencing_WebsiteinHTMLandCSS/assets/140008822/f8f6c02a-0885-4617-af73-648018b166d5)
![emp-3](https://github.com/ashu8520/Video_Conferencing_WebsiteinHTMLandCSS/assets/140008822/96cc4abb-90b5-4f0b-8f08-454bf7b021c2)
![emp-2](https://github.com/ashu8520/Video_Conferencing_WebsiteinHTMLandCSS/assets/140008822/7b7024ec-71cd-4ef4-9b96-40a8d54bbf69)

4.- OUTPUT SCREEN IMAGE
![Screenshot (69)](https://github.com/ashu8520/Video_Conferencing_WebsiteinHTMLandCSS/assets/140008822/6fe483ac-4a61-4f05-ab7c-bfac92721381)
