# 3-column-preview-card-component-challenge-hub



   In this project I used mainly flexbox in order to center the content in page. Within the container, I created 3 cards, each with the same components: Image, header, paragraph and button. After that, I styled in CSS according to the guide. I used media queries to accomplish the responsive layout that was required by the challenge.


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
    <link rel="stylesheet" href="Pagina test.css">
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
