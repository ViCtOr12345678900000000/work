<html lang ="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
    </head>
    <body id="background-change">
        <div class="darkmode">
            <button type="submit">Darkmode</button>
        </div>

        <div class="form">
            
            <form action="https://www.google.com/search" method="get">
                <input type="text" id="search" name="q" placeholder="Enter your search query">
                <button type="submit">Go!</button>
              </form>
            </div>
        <div class="title">
            <p>VC STORES</p>
        </div>
        <hr>
        <div class="bottom">
        <button type="submit">View Assets</button>
        <button type="submit">Customize Assets</button>
        <button type="submit">Build Assets</button>
        <button type="submit">Augments</button>
        </div>
    </body>
</html>


<style>
    @keyframes changeBackground{
        20% {background-image: url("https://i.pinimg.com/originals/85/6f/31/856f31d9f475501c7552c97dbe727319.jpg");}
        50% {background-image: url("https://www.wallpapersales.uk.com/wp-content/uploads/2018/11/82009.jpg");}
        75% {background-image: url("https://img.freepik.com/free-photo/abstract-blue-geometric-shapes-background_24972-1841.jpg");}
        100% {background-image: url("https://img.freepik.com/premium-photo/white-background-white-texture-background-banner-pattern-texture-abstract-clean-grunge-white_873925-75424.jpg");}
    }
    body{
        background-image: url("https://png.pngtree.com/thumb_back/fh260/background/20210915/pngtree-geometric-pattern-white-gold-minimalist-creative-background-image_879782.jpg");
        background-size:cover;
        background-repeat: no-repeat;
        background-position: center;
        background-attachment: fixed;
        animation-duration: s;
        animation-iteration-count: infinite;
        animation-name: changeBackground ;
    }
    .form{
        text-align: center;
        margin-top: 40px;
        margin-bottom: 50px;
        margin-right: 5px;
    }
    .title{
        margin-top: 10%;
        text-align: center;
    }
    p{
        font-size: xx-large;
        font-family: Arial, Helvetica, sans-serif;
        font-weight: bold;
    }
    
    input{
        border-radius: 50px;
        width: 200px;
        height: 20px;
        background-color: inherit;
        text-align: center;
        
        
        
    }
    button{
        border-radius: 20px;
        background-color: inherit;
        
    }
    hr{
        margin-top: 20%;
        text-align: center;
        width: 50%;
    }
    .bottom{
        text-align: center;
        margin-top: 100px;
        
        
    }
    .darkmode{
        text-align: center;
        margin-top: 20px;
        margin-right: 5px;
    }
    
</style>
