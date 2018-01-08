# mobilespace
This is a landing page full width with a space theme doing mobile applications.
<!DOCTYPE>
<html lang="en">
    
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-quip="X-UA-Compatible" content="ie=edge">
    <link rel="stylesheet" href="css/style.css">
    <title>Space Landing Page</title>
   </head>
<body>
    <header id="showcase">
        <h1>Welcome to Mobile Space</h1>
        <p>Makeing mobile apps for today's businesses.</p>
        <a href="#" class="button">Read More</a>
    </header>
    <section id="section-a">
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec fermentum, ante vel finibus scelerisque, lorem sapien lobortis nisl, eu dictum elit orci ac quam. Donec vel orci eu tellus dignissim consectetur non eget ligula. Nullam luctus eget leo ac placerat. Vivamus pulvinar, libero convallis vestibulum elementum, lorem magna dignissim risus, quis laoreet orci purus non lorem. In vel mollis enim. Phasellus eu vehicula eros, sed semper nisi. Vestibulum laoreet neque risus, vel ornare sem placerat ac. Nulla accumsan, tortor sed tempus interdum, diam orci dictum tellus, sed iaculis augue leo vel metus. Nunc accumsan nunc quis velit egestas vehicula. Pellentesque aliquet nibh nec est elementum posuere. Phasellus porta enim massa, eget sagittis sapien sagittis ac. Mauris a ex justo. Proin eget sem lorem.</p>
    
    </section>
    
    <section id="section-b">
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec fermentum, ante vel finibus scelerisque, lorem sapien lobortis nisl, eu dictum elit orci ac quam. Donec vel orci eu tellus dignissim consectetur non eget ligula. Nullam luctus eget leo ac placerat. Vivamus pulvinar, libero convallis vestibulum elementum, lorem magna dignissim risus, quis laoreet orci purus non lorem. In vel mollis enim. Phasellus eu vehicula eros, sed semper nisi. Vestibulum laoreet neque risus, vel ornare sem placerat ac. Nulla accumsan, tortor sed tempus interdum, diam orci dictum tellus, sed iaculis augue leo vel metus. Nunc accumsan nunc quis velit egestas vehicula. Pellentesque aliquet nibh nec est elementum posuere. Phasellus porta enim massa, eget sagittis sapien sagittis ac. Mauris a ex justo. Proin eget sem lorem.</p>
    
    </section>
    
    <section id="section-c">
        <div class="box-1">
        Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec fermentum, ante vel finibus scelerisque, lorem sapien lobortis nisl, eu dictum elit orci ac quam.
        </div>
        <div class="box-2">
        Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec fermentum, ante vel finibus scelerisque, lorem sapien lobortis nisl, eu dictum elit orci ac quam.
        </div>
        <div class="box-3">
        Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec fermentum, ante vel finibus scelerisque, lorem sapien lobortis nisl, eu dictum elit orci ac quam.
        </div>
        
        
    
    </section>
    
    
    
    </body>
</html>

//css page
*{
  margin:0;
    padding:0;
}

body{
    margin:0;
    font-family:Arial, "Helvetica Neue", Helvetica, sans-serif;
    font-size:17px;
    color:#fff;
    line-height: 1.6;
}

#showcase{
    background-image: url('/img/earth.jpeg');
    height:100vh;
    background-size:cover;
    background-position: center;
    display:flex;
    flex-direction:column;
    justify-content: center;
    align-items:center;
    text-align: center;
    padding:0 30px;
}

#showcase h1{
    margin-top: 130px;
    font-size:50px;
    line-height: 1.2;
    
}

#showcase p{
    font-size:20px;
}

#showcase .button{
    font-size:18px;
    text-decoration: none;
    color:#ffffff;
    border:#926239 1px solid;
    padding:10px 20px;
    border-radius:10px;
    margin-top:20px;
}

#showcase .button:hover{
    background:#926239;
    color:#fff;
}

#section-a{
    padding:20px;
    background:#926239;
    color:#fff;
    text-align:center;
}

#section-b{
    padding:20px;
    background:#fff;
    color:#926239;
    text-align:center;
}

#section-c{
    display:flex;
}

#section-c div{
    padding:20px;
}

#section-c .box-1, #section-c .box-3{
    background:#926239;
    color:#fff;
}

#section-c .box-2{
    background:#f9f9f9;
    color:#926239;
}






















