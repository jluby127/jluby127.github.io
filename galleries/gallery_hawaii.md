<html>
<meta name="viewport" content="width=980px, initial-scale=1">
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

<h2 style="text-align:center">Photos from Hawaii - January 2020</h2>

<div class="container">
  <div class="mySlides">
    <div class="numbertext">1 / 6</div>
    <img src="./../images/PhotoGallery/hawaii/IMG_2844.JPG" style="width:100%">
  </div>

  <div class="mySlides">
    <div class="numbertext">2 / 6</div>
    <img src="./../images/PhotoGallery/hawaii/IMG_2911.JPG" style="width:100%">
  </div>

  <div class="mySlides">
    <div class="numbertext">3 / 6</div>
    <img src="./../images/PhotoGallery/hawaii/IMG_3006.JPG" style="width:100%">
  </div>

  <div class="mySlides">
    <div class="numbertext">4 / 6</div>
    <img src="./../images/PhotoGallery/hawaii/IMG_3029.JPG" style="width:100%">
  </div>

  <div class="mySlides">
    <div class="numbertext">5 / 6</div>
    <img src="./../images/PhotoGallery/hawaii/IMG_3184.JPG" style="width:100%">
  </div>

  <div class="mySlides">
    <div class="numbertext">6 / 6</div>
    <img src="./../images/PhotoGallery/hawaii/IMG_3281.JPG" style="width:100%">
  </div>

  <a class="prev" onclick="plusSlides(-1)">❮</a>
  <a class="next" onclick="plusSlides(1)">❯</a>

  <div class="caption-container">
    <p id="caption"></p>
  </div>

  <div class="row">
    <div class="column">
      <img class="demo cursor" src="./../images/PhotoGallery/hawaii/IMG_2844.JPG" style="width:100%" onclick="currentSlide(1)" alt="A misty morning on the north east side of the island, I loved the dense foliage and then was surprised by a pair of horses grazing.">
    </div>
    <div class="column">
      <img class="demo cursor" src="./../images/PhotoGallery/hawaii/IMG_2911.JPG" style="width:100%" onclick="currentSlide(2)" alt="An overcast morning watching waves break over the rocky shore. I love how this image is almost in black and white.">
    </div>
    <div class="column">
      <img class="demo cursor" src="./../images/PhotoGallery/hawaii/IMG_3006.JPG" style="width:100%" onclick="currentSlide(3)" alt="It rained and rained and rained all through the trip, swelling this river into one that rages and races to the sea. I was in awe of the violence of the water.">
    </div>
    <div class="column">
      <img class="demo cursor" src="./../images/PhotoGallery/hawaii/IMG_3029.JPG" style="width:100%" onclick="currentSlide(4)" alt="The same river, leading to Rainbow Falls, the volume of water and crash of thunder captured in an image.">
    </div>
    <div class="column">
      <img class="demo cursor" src="./../images/PhotoGallery/hawaii/IMG_3184.JPG" style="width:100%" onclick="currentSlide(5)" alt="Just north of Hilo there is a small scenic route along the coast. We stopped for smoothies at a roadside stand, then further up the road I saw this image and wanted to capture it. I love the black and white astetic with hints of green. See my paintings page for my attempt to capture this scene again on canvas.">
    </div>
    <div class="column">
      <img class="demo cursor" src="./../images/PhotoGallery/hawaii/IMG_3281.JPG" style="width:100%" onclick="currentSlide(6)" alt="Life, uh, finds a way...even in the volcanic rock of Volcanos National Park, greenery pokes through the seemingly desolate landscape.">
    </div>
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

[Back](./../gallery_overview2.html)
<br>
[Home](./../)
