<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
* {
  box-sizing: border-box;
}

body {
  background-color: #f1f1f1;
  padding: 20px;
  font-family: Arial;
}

<!-- /* Center website */ -->
.main {
  max-width: 1000px;
  margin: auto;
}

h1 {
  font-size: 50px;
  word-break: break-all;
}

.row {
  margin: 8px -16px;
}

<!-- /* Add padding BETWEEN each column */ -->
.row,
.row > .column {
  padding: 8px;
}

<!-- /* Create four equal columns that floats next to each other */ -->
.column {
  float: left;
  width: 25%;
}

<!-- /* Clear floats after rows */ -->
.row:after {
  content: "";
  display: table;
  clear: both;
}

<!-- /* Content */ -->
.content {
  background-color: white;
  padding: 10px;
}

<!-- /* Responsive layout - makes a two column-layout instead of four columns */ -->
@media screen and (max-width: 900px) {
  .column {
    width: 50%;
  }
}

<!-- /* Responsive layout - makes the two columns stack on top of each other instead of next to each other */ -->
@media screen and (max-width: 600px) {
  .column {
    width: 100%;
  }
}
</style>
</head>
<body>

<!-- MAIN (Center website) -->
<div class="main">

<h1>Galleries</h1>
<hr>

<!-- Portfolio Gallery Grid -->
<div class="row">
  <div class="column">
    <div class="content">
      <img src="/w3images/mountains.jpg" alt="Mountains" style="width:100%">
      <h3><a href="https://jluby127.github.io/galleries/gallery_zion.html">Zion National Park</h3>
      <p>I am always fascinated by colors of the desert red rocks. I didn't have long in the park, but we made the most of it. Will need to go back to do the Narrows and build up the courage to inch along the chains at the top of Angel's Landing.</p>
    </div>
  </div>

  <div class="column">
    <div class="content">
    <img src="/w3images/lights.jpg" alt="Lights" style="width:100%">
      <h3><a href="https://jluby127.github.io/galleries/gallery_glacier.html"> Glacier National Park</h3>
      <p>Instantly my new favorite park. The views, the lakes, the wildlife, a ridiculously windy road and a true at-one-with-Nature feel. 10/10 would recommend and can't wait to go back. </p>
    </div>
  </div>

  <div class="column">
    <div class="content">
    <img src="/w3images/nature.jpg" alt="Nature" style="width:100%">
      <h3><a href="https://jluby127.github.io/galleries/gallery_joshuatree.html"> Joshua Tree</a></h3>
      <p>LA's nearest National park, I've gone out a few times to see the spikey looking "trees" and climb in the playground of boulders.</p>
    </div>
  </div>

  <div class="column">
    <div class="content">
    <img src="/w3images/mountains.jpg" alt="Mountains" style="width:100%">
      <h3><a href="https://jluby127.github.io/galleries/gallery_sequoia.html"> Sequoia & King's Canyon</a></h3>
      <p>I couldn't shake the strong feelings of Yosemite with the canyon's granite cliff faces towering over the valley floor. Yet maybe a tenth of the people in the park. </p>
    </div>
  </div>
<!-- END GRID -->
</div>

<!-- Portfolio Gallery Grid -->
<!-- <div class="row">
  <div class="column">
    <div class="content">
      <img src="/w3images/mountains.jpg" alt="Mountains" style="width:100%">
      <h3><a href="https://jluby127.github.io/galleries/gallery_painting.html">Zion National Park</h3>
      <p>Sometimes I like to try painting. Here is my virtual show room.</p>
    </div>
  </div>

  <div class="column">
    <div class="content">
    <img src="/w3images/lights.jpg" alt="Lights" style="width:100%">
      <h3><a href="https://jluby127.github.io/galleries/gallery_glacier.html"> Glacier National Park</h3>
      <p>Instantly my new favorite park. The views, the lakes, the wildlife, a ridiculously windy road and a true at-one-with-Nature feel. 10/10 would recommend and can't wait to go back. </p>
    </div>
  </div>

  <div class="column">
    <div class="content">
    <img src="/w3images/nature.jpg" alt="Nature" style="width:100%">
      <h3><a href="https://jluby127.github.io/galleries/gallery_joshuatree.html"> Joshua Tree</a></h3>
      <p>LA's nearest National park, I've gone out a few times to see the spikey looking "trees" and climb in the playground of boulders.</p>
    </div>
  </div>

  <div class="column">
    <div class="content">
    <img src="/w3images/mountains.jpg" alt="Mountains" style="width:100%">
      <h3><a href="https://jluby127.github.io/galleries/gallery_sequoia.html"> Sequoia & King's Canyon</a></h3>
      <p>I couldn't shake the strong feelings of Yosemite with the canyon's granite cliff faces towering over the valley floor. Yet maybe a tenth of the people in the park. </p>
    </div>
  </div> -->
<!-- END GRID -->
<!-- </div> -->


<!-- END MAIN -->
</div>

</body>
</html>

[Home](./)
