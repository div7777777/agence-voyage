<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <title>AGENCE DE VOYAGE</title>
</head>
<body>
  <style>
    *{
    padding: 0;
    margin: 0;
}
/* slider 1 */

div.slides1 {
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: row;
    width: calc(500px*3);
    height: 1000;
    animation: glisse 14s infinite ease;
    max-width: 1000px;
    position: relative;
    margin: auto;

}

.img {
    width: 200px;
    height: 250px;
}
@keyframes glisse {
    0% {
        transform: translateX(0);
    }
    25% {
        transform: translateX(-250px);
    }
    50% {
        transform: translateX(-500px);
    }
    75% {
        transform: translateX(-750px);
    }
    100% {
        transform: translateX(-1000);
    }
}
/* slider 2 */


div.slides2 {
    display: flex;
    align-items: center;
    flex-direction: row;
    width: calc(500px*5);
    height: 1000;
    animation: glisse 12s infinite ease;
    max-width: 1000px;
    position: relative;
    margin: auto;

}

.img {
    width: 65px;
    height: 70px;
}
@keyframes glisse {
    0% {
        transform: translateX(0);
    }
    25% {
        transform: translateX(-250px);
    }
    50% {
        transform: translateX(-500px);
    }
    75% {
        transform: translateX(-250px);
    }
    100% {
        transform: translateX(0);
    }
}
/* contacte réseaux sociaux */


 /* menu humberger */
.accueil{
    color: red;
    font-family: 'Cinzel Decorative', cursive;
    max-width: 1000px;
    position: relative;
    margin: auto;
}
.burger a {
     display: block;
     color: white;
     font-size: 25px;
     padding-top: 18px; 
     text-decoration: none;
     max-width: 1000px;
     position: relative;
     margin: auto;
}
.flex{
    display: flex;
    justify-content: space-between;
    align-items: center;
    flex-direction: column;


}
.flex:hover{
    background-color: #800000;
}
.sidenav{

    height: 100%;
    width: 0;
    position: fixed;
    z-index: 1;
    top: 0;
    left: 0;
    background-color: #111;
    overflow-x: hidden;
    transition: 0.5s;
    padding-top: 60px;
}
 .sidenav a:hover {
     background-color: #800080;
     width: 100%;
     padding: 4px;
 }
 .sidenav .closebtn{
     position: absolute;
     top: 0;
     right: 25px;
     font-size: 36px;
     margin-left: 50px;
 }

 @media screen and (max-heigth: 450px){
     .sidenav{padding-top: 15px;;}
     .sidenav a {font-size: 18px;}
 }
/* contacte */
.icones{
    display: flex;
    justify-content: center;
    align-items: center;
    background: black;
    padding: 5px;
    max-width: 1000px;
    position: relative;
    margin: auto;
}
.icone{
    display: inline-block;
}

/* slider responsive */

.style-menu {
    display: flex;
    justify-content: center;
    background: black;
}

.style-menu [type="text"] {
    display: flex;
    justify-content: center;
    align-items: center;
    font-size: 20px;
    background: greenyellow;
    color : black;
    padding: 15px;
    margin: 15px;
    height: 20px;
    width: 500px;
}
.soumetre {
    display: flex;
    justify-content: center;
    align-items: center;
    margin: -110px;
}

/* slider */
* {box-sizing: border-box}
body {font-family: Verdana, sans-serif; margin:0}
.mySlides {display: none}
img {vertical-align: middle;}

/* Slideshow container */
.slideshow-container {
  max-width: 1000px;
  position: relative;
  margin: auto;
}

/* Next & previous buttons */
.prev, .next {
  cursor: pointer;
  position: absolute;
  top: 50%;
  width: auto;
  padding: 16px;
  margin-top: -22px;
  color: white;
  font-weight: bold;
  font-size: 18px;
  transition: 0.6s ease;
  border-radius: 0 3px 3px 0;
  user-select: none;
}

/* Position the "next button" to the right */
.next {
  right: 0;
  border-radius: 3px 0 0 3px;
}

/* On hover, add a black background color with a little bit see-through */
.prev:hover, .next:hover {
  background-color: rgba(0,0,0,0.8);
}

/* Caption text */
.text {
  color: red;
  font-size: 25px;
  padding: 8px 12px;
  position: absolute;
  bottom: 8px;
  width: 100%;
  text-align: center;
}
.text:hover{
    background: darkred;
    padding-top: 1px;
    

}

/* Number text (1/3 etc) */
.numbertext {
  color: #f2f2f2;
  font-size: 12px;
  padding: 8px 12px;
  position: absolute;
  top: 0;
}

/* The dots/bullets/indicators */
.dot {
  cursor: pointer;
  height: 15px;
  width: 15px;
  margin: 0 2px;
  background-color:#bbb;
  border-radius: 50%;
  display: inline-block;
  transition: background-color 0.6s ease;
}

.active, .dot:hover {
  background-color: #717171;
}

/* Fading animation */
.fade {
  animation-name: fade;
  animation-duration: 1.5s;
}

@keyframes fade {
  from {opacity: .4} 
  to {opacity: 1}
}

/* On smaller screens, decrease text size */
@media only screen and (max-width: 300px) {
  .prev, .next,.text {font-size: 11px}
}
/* menu */
.menu{
    display: flex;
    justify-content: center;
    background-color: black;
    max-width: 1000px;
    position: relative;
    margin: auto;

}
.item{
    display: inline-block;
}
  </style>
<div class="slider1">
    <div class="slides1">

        <div class="slide"><img src="images/slider1/2.jpg" alt=""></div>
        <div class="slide"> <img src="images/slider1/1.jpg" alt=""></div>
        <div class="slide"> <img src="images/slider1/1.jpg" alt=""></div>
        <div class="slide"> <img src="images/slider1/1.jpg" alt=""></div>
        <div class="slide"> <img src="images/slider1/3.jpg" alt=""></div>
        <div class="slide"> <img src="images/slider1/1.jpg" alt=""></div>
        <div class="slide"> <img src="images/slider1/2.jpg" alt=""></div>
        <div class="slide"> <img src="images/slider1/1.jpg" alt=""></div>
        <div class="slide"> <img src="images/slider1/1.jpg" alt=""></div>
        <div class="slide"> <img src="images/slider1/1.jpg" alt=""></div>
        <div class="slide"> <img src="images/slider1/3.jpg" alt=""></div>
        <div class="slide"> <img src="images/slider1/1.jpg" alt=""></div>
        <div class="slide"> <img src="images/slider1/2.jpg" alt=""></div>
        <div class="slide"> <img src="images/slider1/1.jpg" alt=""></div>
        <div class="slide"> <img src="images/slider1/1.jpg" alt=""></div>
    </div>
</div>
<div class="slider2">
    <div class="slides2">
        <div class="slide"><img src="images/slider2/terre.jpg" alt=""></div>
        <div class="slide"> <img src="images/slider2/a.jpg" alt=""></div>
        <div class="slide"> <img src="images/slider2/g.jpg" alt=""></div>
        <div class="slide"> <img src="images/slider2/e.jpg" alt=""></div>
        <div class="slide"> <img src="images/slider2/n.jpg" alt=""></div>
        <div class="slide"> <img src="images/slider2/c.jpg" alt=""></div>
        <div class="slide"> <img src="images/slider2/e.jpg" alt=""></div>
        <div class="slide"> <img src="images/slider2/w.jpg" alt=""></div>
        <div class="slide"> <img src="images/slider2/o.jpg" alt=""></div>
        <div class="slide"> <img src="images/slider2/r.jpg" alt=""></div>
        <div class="slide"> <img src="images/slider2/d.jpg" alt=""></div>
        <div class="slide"> <img src="images/slider2/t.jpg" alt=""></div>
        <div class="slide"> <img src="images/slider2/r.jpg" alt=""></div>
        <div class="slide"> <img src="images/slider2/a.jpg" alt=""></div>
        <div class="slide"> <img src="images/slider2/v.jpg" alt=""></div>
        <div class="slide"> <img src="images/slider2/e.jpg" alt=""></div>
        <div class="slide"> <img src="images/slider2/l.jpg" alt=""></div>
        <div class="slide"> <img src="images/slider2/terre.jpg" alt=""></div>
        <div class="slide"> <img src="images/slider2/a.jpg" alt=""></div>
        <div class="slide"> <img src="images/slider2/g.jpg" alt=""></div>
        <div class="slide"> <img src="images/slider2/e.jpg" alt=""></div>
        <div class="slide"> <img src="images/slider2/n.jpg" alt=""></div>
        <div class="slide"> <img src="images/slider2/c.jpg" alt=""></div>
        <div class="slide"> <img src="images/slider2/e.jpg" alt=""></div>
        <div class="slide"> <img src="images/slider2/w.jpg" alt=""></div>
        <div class="slide"> <img src="images/slider2/o.jpg" alt=""></div>
        <div class="slide"> <img src="images/slider2/r.jpg" alt=""></div>
        <div class="slide"> <img src="images/slider2/d.jpg" alt=""></div>
        <div class="slide"> <img src="images/slider2/t.jpg" alt=""></div>
        <div class="slide"> <img src="images/slider2/r.jpg" alt=""></div>
        <div class="slide"> <img src="images/slider2/a.jpg" alt=""></div>
        <div class="slide"> <img src="images/slider2/v.jpg" alt=""></div>
        <div class="slide"> <img src="images/slider2/e.jpg" alt=""></div>
        <div class="slide"> <img src="images/slider2/l.jpg" alt=""></div>
    </div>
</div>
<!-- menu -->
<div id="mySidenav" class="sidenav">
    <a href="javascript:void(0)" class="closebtn"  onclick="closeNav()">&times;</a>
    <div class="burger">
            <div class="flex">
                <a href="#"><img src="https://img.icons8.com/ios-filled/23/ffffff/home.png"/>  Home </a>
                <a href="#"><img src="https://img.icons8.com/ios-filled/23/ffffff/service.png"/>  Services</a>
                <a href="#"> <img src="https://img.icons8.com/external-others-iconmarket/23/ffffff/external-client-essential-others-iconmarket-3.png"/>  Clients</a>
                <a href="#"><img src="https://img.icons8.com/ios-filled/23/ffffff/phone-not-being-used.png"/>  Contact</a>
                <a href="#"> <img src="https://img.icons8.com/ios-filled/23/ffffff/order-delivered.png"/>  Adresse</a>
                <a href="#"><img src="https://img.icons8.com/wired/23/ffffff/book-and-pencil.png"/>  À propos</a>


            </div>

    </div>


</div>
<!-- accueil -->
<div class="accueil">
        <span style="font-size: 30px; cursor: pointer"; onclick = "openNav()"> &#9776; <img src="https://img.icons8.com/metro/50/000000/airplane-mode-on.png"/>AGENCE WORD TRAVEL
            <style>
                @import url('https://fonts.googleapis.com/css2?family=Cinzel+Decorative&family=El+Messiri&family=Palette+Mosaic&family=Rajdhani:wght@400;500&family=Schoolbell&display=swap');
                </style>
            
        </span>

</div>

<!-- services -->
    <!-- menu -->
    <nav class="menu">
          <ul class="items">
            <li class="item"><a href=""></a><img src="menu/1.jpg" alt=""></li>
            <li class="item"><a href=""></a><img src="menu/2.jpg" alt=""></li>
            <li class="item"><a href=""></a><img src="menu/3.jpg" alt=""></li>
            <li class="item"><a href=""></a><img src="menu/4.jpg" alt=""></li>
          </ul>
     </nav>

<!-- slider -->

<div class="slideshow-container">

    <div class="mySlides fade">
      <div class="numbertext">1 / 8</div>
      <img src="images/1.jpg" style="width: 100%">
      <div class="text">Espagne</div>
    </div>
    
    <div class="mySlides fade">
      <div class="numbertext">2 / 8</div>
      <img src="images/2.jpg"style="width: 100%">
      <div class="text">France</div>
    </div>
    
    <div class="mySlides fade">
      <div class="numbertext">3 / 8</div>
      <img src="images/3.jpg"style="width: 100%">
      <div class="text">Tunisie</div>
    </div>
    <div class="mySlides fade">
      <div class="numbertext">4 / 8</div>
      <img src="images/4.jpg"style="width: 100%">
      <div class="text">Canada</div>
    </div>
    <div class="mySlides fade">
      <div class="numbertext">5 / 8</div>
      <img src="images/5.jpg"style="width: 100%">
      <div class="text">Turquie</div>
    </div>
    <div class="mySlides fade">
      <div class="numbertext">6 / 8</div>
      <img src="images/6.jpg"style="width: 100%">
      <div class="text">Abu Dhabi</div>
    </div>
    <div class="mySlides fade">
      <div class="numbertext">7 / 8</div>
      <img src="images/7.jpg"style="width: 100%">
      <div class="text">Qatar</div>
    </div>
    <div class="mySlides fade">
      <div class="numbertext">8 / 8</div>
      <img src="images/8.jpg"style="width: 100%">
      <div class="text">Arabie Saoudit</div>
    </div>

    
    <a class="prev" onclick="plusSlides(-1)">❮</a>
    <a class="next" onclick="plusSlides(1)">❯</a>
    
    </div>
    <br>
    
    <div style="text-align:center">
      <span class="dot" onclick="currentSlide(1)"></span> 
      <span class="dot" onclick="currentSlide(2)"></span> 
      <span class="dot" onclick="currentSlide(3)"></span> 
      <span class="dot" onclick="currentSlide(4)"></span> 
      <span class="dot" onclick="currentSlide(5)"></span> 
      <span class="dot" onclick="currentSlide(6)"></span> 
      <span class="dot" onclick="currentSlide(7)"></span> 
      <span class="dot" onclick="currentSlide(8)"></span> 
    </div>
    <!-- menu contacte -->
<div class="icones">
  <ul>
    <li class="icone"><a href=""></a><img src="https://img.icons8.com/ios-glyphs/90/E74C3C/facebook.png"/></li>
    <li class="icone"><a href=""></a><img src="https://img.icons8.com/small/90/E74C3C/instagram.png"/> </li>
    <li class="icone"><a href=""></a><img src="https://img.icons8.com/dotty/90/E74C3C/email.png"/></li>
    <li class="icone"><a href=""></a><img src="https://img.icons8.com/fluency-systems-filled/90/E74C3C/call-squared.png"/></li>
    <li class="icone"><a href=""></a><img src="https://img.icons8.com/ios-filled/90/E74C3C/linkedin.png"/></li>
    <li class="icone"><a href=""></a><img src="https://img.icons8.com/ios-filled/90/E74C3C/twitter-circled--v1.png"/></li>
  </ul>

</div>   
<script>
  // menu burgeur
function openNav() {
  document.getElementById("mySidenav").style.width = "250px";
}

function closeNav() {
  document.getElementById("mySidenav").style.width = "0";
}



// slider

let slideIndex = 1;
showSlides(slideIndex);

function plusSlides(n) {
  showSlides(slideIndex += n);
}

function currentSlide(n) {
  showSlides(slideIndex = n);
}

function showSlides(n) {
  let i;
  let slides = document.getElementsByClassName("mySlides");
  let dots = document.getElementsByClassName("dot");
  if (n > slides.length) {slideIndex = 1}    
  if (n < 1) {slideIndex = slides.length}
  for (i = 0; i < slides.length; i++) {
    slides[i].style.display = "none";  
  }
  for (i = 0; i < dots.length; i++) {
    dots[i].className = dots[i].className.replace(" active", "");
  }
  slides[slideIndex-1].style.display = "block";  
  dots[slideIndex-1].className += " active";
}
</script> 

<!-- javascript -->
<script src="code.js"></script>
    
</body>
</html>![4](https://user-images.githubusercontent.com/99870561/164723309-7ac4af99-283b-4e42-8be7-b9506fb7b755.jpg)
![1](https://user-images.githubusercontent.com/99870561/164723453-2c518214-6681-40a7-b311-1bc18ed34083.jpg)
![2](https://user-images.githubusercontent.com/99870561/164723458-3e97568b-260b-491b-80a8-1fa92a502424.jpg)
![3](https://user-images.githubusercontent.com/99870561/164723462-ae13c066-db33-43d5-85b6-d5f41d565e4d.jpg)![1](https://user-images.githubusercontent.com/99870561/164723740-fcd671fc-ebc0-4267-8ebb-5a2d9c104512.jpg)
![2](https://user-images.githubusercontent.com/99870561/164723744-c1963169-b01c-4dcc-a60b-a647d97fee17.jpg)
![3](https://user-images.githubusercontent.com/99870561/164723747-327c0e4a-2cba-4252-8ad3-4489781b7d78.jpg)
![4](https://user-images.githubusercontent.com/99870561/164723750-78a583e1-0567-445c-aa42-ab348e00fe56.jpg)
![5](https://user-images.githubusercontent.com/99870561/164723752-d2b04ec0-dd56-41d6-8f27-2ca8738660c8.jpg)
![6](https://user-images.githubusercontent.com/99870561/164723765-9e49f958-d885-4a9c-8bf8-0fdb22187634.jpg)
![7](https://user-images.githubusercontent.com/99870561/164723769-f63c1708-25d8-4d29-9a2f-a279220822c3.jpg)
![8](https://user-images.githubusercontent.com/99870561/164723773-f46e36a5-243c-45f2-a337-f7105b4f9e88.jpg)
![a](https://user-images.githubusercontent.com/99870561/164723632-131d4a9a-9f2a-45a9-84bb-f71aac582eb8.jpg)
![c](https://user-images.githubusercontent.com/99870561/164723636-a8544dcc-ebaa-496e-8457-6e6e1ff81073.jpg)
![d](https://user-images.githubusercontent.com/99870561/164723640-8bc70c0f-bc3d-4355-bc33-8901bfa39e5e.jpg)
![e](https://user-images.githubusercontent.com/99870561/164723642-2ca90baf-4ed8-4a9a-bcfd-b2a08de6d6ba.jpg)
![g](https://user-images.githubusercontent.com/99870561/164723647-8ce95b1f-f1fe-42b5-9ebd-b2cf97d857c9.jpg)
![l](https://user-images.githubusercontent.com/99870561/164723649-5298e5cb-506f-4138-ab5a-c225ec50b80d.jpg)
![n](https://user-images.githubusercontent.com/99870561/164723650-b8bba472-1801-40e1-82eb-d306f4cf213d.jpg)
![o](https://user-images.githubusercontent.com/99870561/164723653-c016ec57-509a-480d-9d66-4537ef05447e.jpg)
![r](https://user-images.githubusercontent.com/99870561/164723655-16be0730-a607-4a54-b031-51b198fcc648.jpg)
![t](https://user-images.githubusercontent.com/99870561/164723657-f59ee5b0-5a73-4207-8ff6-e1f3fc558d7e.jpg)
![terre](https://user-images.githubusercontent.com/99870561/164723661-792571f8-5459-4619-8d3e-c3e9d983f4e2.jpg)
![v](https://user-images.githubusercontent.com/99870561/164723662-b3680a2c-5379-4a07-9b6d-ca4006e613f0.jpg)
![w](https://user-images.githubusercontent.com/99870561/164723665-47b353fe-dff4-488b-bcb9-a67795a8c6de.jpg)


