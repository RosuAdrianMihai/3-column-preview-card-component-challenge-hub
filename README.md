<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>3-column-preview-card-component-challenge-hub</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Lexend+Deca&display=swap" rel="stylesheet">
<style>
    @import url('https://fonts.googleapis.com/css2?family=Big+Shoulders+Display:wght@700&family=Lexend+Deca&display=swap');
    </style>
    <link rel="stylesheet" href="3 card.css">
</head>
<body>
    
<div class="container">

<div class="card" id="one">
    <img src="icon-sedans.svg" alt="">
    <h3>Sedans</h3>
    <p>Choose a sedan for its affordability and excellent
        fuel economy. Ideal for cruising in the city or on your next
        road trip.</p>
    <button>Learn more</button>
</div>

<div class="card" id="two">
    <img src="icon-suvs.svg" alt="">
    <h3>Suvs</h3>
    <p>Take an SUV for its spacious interior, power, and versatility.
        Perfect for your next family vacation and off-road adventures.</p>
    <button>Learn more</button>
</div>

<div class="card" id="three"> 
    <img src="icon-luxury.svg" alt="">
    <h3>Luxury</h3>
    <p>Cruise in the best car brands without bloated prices. Enjoy the
        enhanced comfort of a luxury rental and arrive in style.</p>
    <button>Learn more</button>
</div>

</div>

</body>
</html>

body{
    margin:0px;
    font-size: 15px;
    font-family: 'Lexend Deca', sans-serif;
    font-family: 'Big Shoulders Display', cursive;
}






.card p{
    line-height: 24px;
    color:hsla(0, 0%, 100%, 0.75);
    letter-spacing: 0.9px;
    word-spacing: 3px;

}

button, h3, body{
    color:hsl(0, 0%, 95%);
    font-weight: 700;
}

#one button{
    color:hsl(31, 77%, 52%);
}

#two button{
    color:hsl(184, 100%, 22%);
}

#three button{
    color:hsl(179, 100%, 13%) ;
}


button:hover{
    background:none;
    cursor:pointer;
}

#one button:hover{
    background:none;
    color:hsl(0, 0%, 95%);
}

#two button:hover{
    background:none;
    color:hsl(0, 0%, 95%);
}

#three button:hover{
    background:none;
    color:hsl(0, 0%, 95%) ;
}

h3{
    font-size:30px;
}

button{
    margin-top:70px;
    padding: 10px 15px;
    border-radius:15px;
    border:solid 2px hsl(0, 0%, 95%);
}

#one{
    background-color: hsl(31, 77%, 52%);
}

#two{
    background-color: hsl(184, 100%, 22%);
}

#three{
    background-color:hsl(179, 100%, 13%) ;
}



@media (min-width: 376px)
{

.container{
    display:flex;
    align-items:center;
    margin:0% 25%;
}

body{
    display:flex;
    align-content:center;
    justify-content: center;
    height:100vh;
}
.container .card{
    width:1fr;
    padding:4.5%;
    flex:1 1;
    padding-bottom:40px;
}

#one{
    border-bottom-left-radius: 12px;
    border-top-left-radius: 12px;
}

#three{
    border-bottom-right-radius: 12px;
    border-top-right-radius: 12px;
}


}



@media (max-width: 375px)
{
    body{
        margin:0px;
    }

    .card{
        display:block;
        padding:6%;
        border-radius:0px;
    }

    button{
        margin-bottom:20px;
        margin-top:10px;
    }



}
