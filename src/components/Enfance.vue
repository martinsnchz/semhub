<!DOCTYPE html>
<html>
<head>
 <meta charset="UTF-8">

<script src="https://unpkg.com/vue"></script>

<h1>Le musée des Frères Wright</h1>


<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">





<style>

body {
    background-image: url( "https://78.media.tumblr.com/6e9049e02a6a9eb0d87fdf1de96a5366/tumblr_inline_o67yh3sJiw1sa90vo_540.jpg");
}

h1 {
    color: #333300;
    font-family: Arial, Helvetica, sans-serif;
    text-align: center;
    font-size: 40px;
    border-style: none;
    background-color: #ffffff;

}

p.article {
    color: #e6fff9;
    font-family: Arial ;
    text-align: justify;
    font-size: 16px;
    letter-spacing: 0.5px;
    line-height: 1.2 ;



}

art1 {
    color: #ffffff;
    font-family: Arial ;
    text-align: justify;
    font-size: 16px;
    letter-spacing: 0.5px;
    line-height: 1.2 ;
    text-decoration: line-through;





}

h3 {
    color: #666633;
    font-family: Arial, Helvetica, sans-serif;
    text-align: center;
    font-size: 20px;
    border-style: none;
Le musée des Frères Wright

}

img {
    display: block;
    margin-left: auto;
    margin-right: auto;
    padding: 8px;
    border: none;
}


.navbar {
    overflow: hidden;
    background-color: #666633;
    font-family: Arial, Helvetica, sans-serif;
}

.navbar a {
    float: left;
    font-size: 16px;
    color: white;
    text-align: center;
    padding: 14px 16px;
    text-decoration: none;
}

.dropdown {
    float: left;
    overflow: hidden;
}

.dropdown .dropbtn {
    cursor: pointer;
    font-size: 16px;
    border:none;
    outline: none;
    color: white;
    padding: 14px 16px;
    background-color: inherit;
    font-family: inherit;
    margin: 0;
}

.navbar a:hover, .dropdown:hover .dropbtn, .dropbtn:focus {
    background-color:  #271a0c;
}

.dropdown-content {
    display: none;
    position: absolute;
    background-color: #f9f9f9;
    min-width: 160px;
    box-shadow: 0px 8px 16px 0px rgba(0,0,0,0.2);
    z-index: 1;

}

.dropdown-content a {
    float: none;
    color: black;
    padding: 12px 16px;
    text-decoration: none;
    display: block;
    text-align: left;

}

.dropdown-content a:hover {
    background-color: #ddd;
}

.show {
    display: block;
}



div.transbox {
    margin: 40px;
    background-color: #000000;
    border: none;
    opacity: 0.5;
    filter: alpha(opacity=60); /* For IE8 and earlier */
    outline: 15px ;
    outline-color: #ffffff ;
    outline-offset: 15px;
    padding: 30px;

}

div.transbox art1 {
    color: #ffffff;
    font-family: Arial, Helvetica, sans-serif;
    text-align: justify;
    font-size: 18px;
    border: 15px ;
    border-style: none;
    outline-offset: 25px;
    margin: 100%;
    font-weight: none;



}

.inner-border {
    background: #000;
    color: #fff;
    margin: 50px;
    padding: 20px;
    position: relative;
    opacity: 0.7;
    filter: alpha(opacity=60); /* For IE8 and earlier */
}
.inner-border:before {
    border: 5px solid #000;
    content: "";
    position: absolute;
    top: -10px;
    bottom: -10px;
    left: -10px;
    right: -10px;
}

span {
    float: left;
    width: 0.7em;
    font-size: 400%;
    font-family: algerian, courier;
    line-height: 80%;
}

</style>
</head>



<body>

<div class="navbar">
  <a href="Site.vue">Home</a>
  <a href="#Introduction">Introduction</a>

  <div class="dropdown">
    <button class="dropbtn" onclick="myFunction()">Chronologie
      <i class="fa fa-caret-down"></i>
    </button>
    <div class="dropdown-content" id="myDropdown">
      <a href="Enfance.vue">Enfance</a>
      <a href="Debuts.vue">Débuts</a>
      <a href="#">Premières Inventions</a>
    </div>
  </div>
  <a href="Gallerie.vue">Gallerie</a>
  <a href="#chronologie">Vidéos</a>
  <a href="#chronologie">Sources</a>

</div>


<h3>Enfance</h3>

<img src="https://www.squaducation.com/sites/default/files/styles/blogs__280x180_/wright-brothers-young.png">

<div class="inner-border">
    <p class=article>
    <br/>

    <span> W</span> ilbur Wright est le plus âgé des deux frères, il est né le 16 avril 1967 à Millville dans l’Indiana. Son frère Orville, né le 19 août 1871 à Dayton, entretenait avec son frère une grande complicité, tout deux réalisèrent dès l’enfance des petites machines mécaniques qui leur servaient de jouets. Toute la famille Wright était portée sur l’invention, ce qui donna aux deux frères un cadre favorable pour exploiter le plus vite possible leur esprit inventif.<br/><br/><br/>
</p>
</div>






<script>

/* When the user clicks on the button,
toggle between hiding and showing the dropdown content */
function myFunction() {
    document.getElementById("myDropdown").classList.toggle("show");
}

// Close the dropdown if the user clicks outside of it
window.onclick = function(e) {
  if (!e.target.matches('.dropbtn')) {
    var myDropdown = document.getElementById("myDropdown");
      if (myDropdown.classList.contains('show')) {
        myDropdown.classList.remove('show');
      }
  }
}
</script>
</body>
</html>
