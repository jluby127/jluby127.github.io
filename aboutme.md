
Originally from the East coast I first became fascinated in physics and astronomy
from watching Science/Discovery/History Channel documentaries on the space race. Always wanting to be
an astronaut, I've been chasing the stars ever since, but now safely from the ground in California. For more about my astro journey, see [my astro story](./myastrostory).

#### education

<img align="right" src= "./images/IndvPagePhotos/happynewyear.jpg" width="400" height="550">

PhD in Physics - University of California, Irvine 2023
<br>
Masters in Physics - University of California, Irvine 2020
<br>
Bachelors in Physics and Applied Mathematics - Vanderbilt University 2016
<br>


#### a table of me

|          likes          |     dislikes      |    neutrals     |
|:------------------------|:------------------|:----------------|
| baseball                | untoasted bagels  | blue pens       |
| Bruce Springsteen       | neon colors       | mice            |
| wwii history books      | chalk             | lemon           |
| trains                  | bananas           | phone calls     |
| The Prestige            | wasps             | legal pad paper |


#### a comprehensive list of my favorite teams

NY Yankees, NY Football Giants, NY Rangers, Vanderbilt athletics

#### life accomplishments

one hole-in-three, 16/61 national parks, 19/30 baseball parks and 43*/50 states (see below)

#### Maps

I really like maps, so I thought I'd make a few. Click on the thumbnails on top to see the image enlarged below.


<html>
<meta name="viewport" content="width=480px, initial-scale=1">
<style>
body {
  font-family: Arial;
  margin: 0;
}

* {
  box-sizing: border-box;
}

img {
  vertical-align: middle;
}

/* Position the image container (needed to position the left and right arrows) */
.container {
  position: center;
}

/* Hide the images by default */
.mySlides {
  display: none;
  max-width:100%
}

/* Add a pointer when hovering over the thumbnail images */
.cursor {
  cursor: pointer;
}

/* Next & previous buttons */
.prev,
.next {
  cursor: pointer;
  position: absolute;
  top: 40%;
  width: auto;
  padding: 16px;
  margin-top: -50px;
  color: white;
  font-weight: bold;
  font-size: 20px;
  border-radius: 0 3px 3px 0;
  user-select: none;
  -webkit-user-select: none;
}

/* Position the "next button" to the right */
.next {
  right: 0;
  border-radius: 3px 0 0 3px;
}

/* On hover, add a black background color with a little bit see-through */
.prev:hover,
.next:hover {
  background-color: rgba(0, 0, 0, 0.8);
}

/* Number text (1/3 etc) */
.numbertext {
  color: #f2f2f2;
  font-size: 12px;
  padding: 8px 12px;
  position: absolute;
  top: 0;
}

/* Container for image text */
.caption-container {
  text-align: center;
  background-color: #222;
  padding: 2px 16px;
  color: white;
}

.row:after {
  content: "";
  display: table;
  clear: both;
}

/* Six columns side by side */
.column {
  float: left;
  width: 16.66%;
}

/* Add a transparency effect for thumnbail images */
.demo {
  opacity: 0.6;
}

.active,
.demo:hover {
  opacity: 1;
}
</style>
<body>

<div class="container">
<div class="row">
  <div class="column">
    <img class="demo cursor" src="images/Maps/Visited.png" style="width:100%" onclick="currentSlide(1)" alt="These are the states I've visited">
  </div>
  <div class="column">
    <img class="demo cursor" src="images/Maps/Lived.png" style="width:100%" onclick="currentSlide(2)" alt="These are the states I've lived in. Defined as signed a lease here.">
  </div>
  <div class="column">
    <img class="demo cursor" src="images/Maps/Roadtrip.png" style="width:100%" onclick="currentSlide(3)" alt="These are the states I passed through and enjoyed on my Summer 2018 Roadtrip. See Gallery for pics!">
  </div>
  <div class="column">
    <img class="demo cursor" src="images/Maps/Costco.png" style="width:100%" onclick="currentSlide(4)" alt="These are the states in which I've been to a Costco.">
  </div>
  <div class="column">
    <img class="demo cursor" src="images/Maps/Food.png" style="width:100%" onclick="currentSlide(5)" alt="A few of the best things I've eaten.">
  </div>
  <div class="column">
    <img class="demo cursor" src="images/Maps/Baseball.png" style="width:100%" onclick="currentSlide(6)" alt="Trying to make it to every MLBstadium.">
  </div>
  <div class="mySlides">
    <div class="numbertext">1 / 6</div>
    <img src="images/Maps/Visited.png" style="width:100%">
  </div>
  <!-- <div class="caption-container">
    <p id="caption"></p>
  </div> -->

  <div class="mySlides">
    <div class="numbertext">2 / 6</div>
    <img src="images/Maps/Lived.png" style="width:100%">
  </div>

  <div class="mySlides">
    <div class="numbertext">3 / 6</div>
    <img src="images/Maps/Roadtrip.png" style="width:100%">
  </div>

  <div class="mySlides">
    <div class="numbertext">4 / 6</div>
    <img src="images/Maps/Costco.png" style="width:100%">
  </div>

  <div class="mySlides">
    <div class="numbertext">5 / 6</div>
    <img src="images/Maps/Food.png" style="width:100%">
  </div>

  <div class="mySlides">
    <div class="numbertext">6 / 6</div>
    <img src="images/Maps/Baseball.png" style="width:100%">
  </div>

  <a class="prev" onclick="plusSlides(-1)">❮</a>
  <a class="next" onclick="plusSlides(1)">❯</a>

  <!--  -->
  </div>
</div>

<script>
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
  let dots = document.getElementsByClassName("demo");
  let captionText = document.getElementById("caption");
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
  captionText.innerHTML = dots[slideIndex-1].alt;
}
</script>

</body>
</html>

[Home](./)
