<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>Exploring Nature</title>

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family: Arial, Helvetica, sans-serif;
}

body{
    background:#656868;
}

.wrapper{
    padding:30px;
}

.container{
    width:640px;
    margin:auto;
    background:#FCF8E3;
    border:4px solid #F4F4EE;
}

.header{
    height:140px;
    background:url("https://picsum.photos/640/140?forest") center/cover no-repeat;
    position:relative;
}

.title{
    position:absolute;
    top:30px;
    left:30px;
    color:white;
}

.title h1{
    letter-spacing:8px;
    font-size:30px;
}

.title p{
    font-size:13px;
}

.content{
    display:flex;
}

.main{
    width:480px;
    padding:10px;
    background:#FCF8E3;
}

.main h3{
    color:#A0410D;
    margin-bottom:6px;
    margin-top:10px;
}

.main p{
    font-size:13px;
    color:#333;
    line-height:1.6;
    margin-bottom:10px;
}

.sidebar{
    width:160px;
    background:#F2CD77;
    padding:10px;
    border-left:1px dashed #999;
}

.sidebar h4{
    background:#595A38;
    color:white;
    padding:6px;
    margin-bottom:8px;
    font-size:14px;
}

.sidebar strong{
    font-size:13px;
}

.sidebar ul{
    list-style:square;
    padding-left:18px;
    margin-bottom:12px;
}

.sidebar li{
    font-size:12px;
    margin:4px 0;
}

.sidebar a{
    color:#0044cc;
    text-decoration:none;
}

.footer{
    height:70px;
    background:#595A38;
    color:white;
    display:flex;
    align-items:center;
    justify-content:center;
    font-size:13px;
}
</style>
</head>

<body>
<div class="wrapper">

<div class="container">

    <div class="header">
        <div class="title">
            <h1>WILDLANDS</h1>
            <p>UNDERSTANDING OUR LIVING PLANET</p>
        </div>
    </div>

    <div class="content">

        <div class="main">

            <h3>FORESTS</h3>
            <p>
            Forests cover nearly one third of the Earth's land surface and play a vital role in maintaining life.
            They regulate climate, store carbon, protect water sources, and provide habitat for millions of species.
            From tropical rainforests to boreal woodlands, these ecosystems support complex food chains and delicate
            environmental balances that have developed over millions of years.
            </p>


            <h3>OCEANS</h3>
            <p>
            Oceans cover more than seventy percent of the planet and contain most of its living space. They influence
            global weather systems, absorb heat from the sun, and generate the oxygen that many organisms depend on.
            Coral reefs, often called the rainforests of the sea, are among the most biologically diverse environments
            on Earth.
            </p>

  

            <h3>WILDLIFE</h3>
            <p>
            Wildlife refers to all undomesticated animals, plants, fungi, and microorganisms that exist in natural
            habitats. Each species, no matter how small, contributes to the stability of its ecosystem. Predators
            regulate populations, plants produce oxygen and food, and insects assist with pollination and soil health.
            </p>

          

        </div>

        <div class="sidebar">
            <h4>Related topics</h4>

            <strong>Environment</strong>
            <ul>
                <li><a href="#">Climate change</a></li>
                <li><a href="#">Renewable energy</a></li>
                <li><a href="#">Sustainable living</a></li>
            </ul>

            <strong>Ecology</strong>
            <ul>
                <li><a href="#">Food chains</a></li>
                <li><a href="#">Habitats</a></li>
                <li><a href="#">Ecosystems</a></li>
            </ul>

            <strong>Organizations</strong>
            <ul>
                <li><a href="#">World Wildlife Fund</a></li>
                <li><a href="#">Greenpeace</a></li>
                <li><a href="#">Conservation Intl.</a></li>
            </ul>
        </div>

    </div>

    <div class="footer">
        © 2026 Global Nature Archive
    </div>

</div>

</div>
</body>
</html>
