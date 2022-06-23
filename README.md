# ZuriAssignmentA
<!DOCTYPE html>
<html>
<head>
<meta charset="UFT-8">
<meta name="viewport" 
content="width=device-width,
initial-scale=1"> 
<title>Index</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Lexend+Deca&family=Poppins:wght@400;500;700&display=swap" rel="stylesheet">


<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Big+Shoulders+Display:wght@700&family=Lexend+Deca&family=Poppins:wght@400;500;700&display=swap" rel="stylesheet">
<style>
body {
display: flex;
color:hsla(0, 0%, 100%, 0.75);
width:auto;
height:100%;
border-radius: 1em;
margin: 10%;
background-color:hsl(0, 0%, 95%);
font-family: 'Big Shoulders Display', cursive;
font-family: 'Lexend Deca', sans-serif;
}

h1{
color:hsl(0, 0%, 95%);
} 

input {
border:1px solid;
border-radius: 50px;
padding: .5em 1em;
margin: .5em;
background-color:hsl(0, 0%, 95%);
}

#sedans{
background-color:hsl(31, 77%, 52%);
padding: 30px;
}
#sedans>input{
color:hsl(31, 77%, 52%);
}

#suvs{
background-color:hsl(184, 100%, 22%);
padding: 30px;
}
#suvs>input{
color:hsl(184, 100%, 22%);
}

#luxury{
background-color:hsl(179, 100%, 13%);
padding: 30px;
}
#luxury>input{
color:hsl(179, 100%, 13%);
}

</style>
</head>


<body>
<header>
<nav>
<a href="layout.html">CSS Flexbox</a>
</nav>
</header>
<div id="sedans">
<img src="icon-sedans.svg" alt="sedans">
<h1>SEDANS</h1>
<p>Choose a sedan for its affordability and excellent fuel economy. Ideal for cruising in the city or on your next road trip.</p>

<input type="submit" value="Learn More">
</div>

<div id="suvs">
<img src="icon-suvs.svg" alt="suvs">
<h1>SUVS</h1>
<p>Take an SUV for its spacious interior, power, and varsatility. Perfect for your next familly vaction aand off-roadd addventures.</p>

<input type="submit" value="Learn More">
</div>

<div id="luxury">
<img src="icon-luxury.svg" alt="luxury">
<h1>LUXURY</h1>
<p>Cruise in the best car brands without the bloated prices. Enjoy the enhanced comfort of a luxury rental and arrive in style.</p>

<input type="submit" value="Learn More"> 
</div>
</body>

</html>
