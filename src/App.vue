<template>
<head>
<title>W3.CSS Template</title>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
<link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Raleway">
</head>
<body>

<header class="w3-padding-64 w3-black" id="home">
  <div class="w3-content">
    <img class="w3-round-small" src="@/assets/front-page.png">
    <p class="w3-center"><a href="#aboutme" class="w3-button w3-white w3-round w3-padding-large w3-large">Get to know me!</a></p>
  </div>
</header>

<!-- Navbar (sticky bottom) -->
<div class="w3-bottom w3-hide-small">
  <div class="w3-bar w3-white w3-center w3-padding w3-opacity-min w3-hover-opacity-off">
    <a href="#home" style="width:33%" class="w3-bar-item w3-button">Home</a>
    <a href="#aboutme" style="width:33%" class="w3-bar-item w3-button">About Me</a>
    <a href="#rsvp" style="width:33%" class="w3-bar-item w3-button w3-hover-black">Contact Me</a>
  </div>
</div>

<div class="w3-content w3-padding-64 w3-white w3-center" id="aboutme">
  <div class="w3-content">
    <img class="w3-round-large w3-grayscale-min" src="@/assets/Photoshop.png" style="width:100%;margin:64px 0">
    <div class="w3-row">
      <div class="w3-half">
        <h2>Highschool</h2>
        <p>Junior HS - Misamis Union High School - June 2013 - Feb 2017</p>
        <p>Senior HS - La Salle University - August 2017 - April 2019</p>
        <h2>College</h2>
        <p>La Salle University - August 2019 - Feb 2023</p>
      </div>
      <div class="w3-half">
        <h2>NC II - Achievements</h2>
        <p>NC II - Cooking</p>
        <p>NC II - Driving</p>
        <p>NC II - Food & Beverage Services</p>
        <p>NC II - Housekeeping</p>
        <p>NC II - Bread & Pastry</p>
        
        <h2>Certificates</h2>
        <p>Dynamic Web App Integration featuring Laravel and VueJS Seminar Workshop - 2020</p>
      </div>
    </div>
  </div>
</div>

<!-- RSVP section -->
 <div class="w3-content w3-padding-64 w3-white w3-center" id="rsvp">
  <div class="w3-content">
    <img class="w3-round-large w3-grayscale-min" src="@/assets/junyoy.png" style="width:100%;margin:64px 0">
    <div class="w3-row">
   
<div class="w3-container w3-padding-64 w3-black w3-center w3-wide" id="rsvp">
  <h1>That's All Thank You!</h1>
  <p class="w3-xlarge">
    <button onclick="document.getElementById('id01').style.display='block'" class="w3-button w3-round w3-red w3-opacity w3-hover-opacity-off" style="padding:8px 60px">Interested?</button>
  </p>
</div>
 </div>
  </div>
</div>
<!-- RSVP modal -->
<div id="id01" class="w3-modal">
  <div class="w3-modal-content w3-card-4 w3-animate-zoom" style="padding:32px;max-width:600px">
    <div class="w3-container w3-white w3-center">
      <h1 class="w3-wide"></h1>
      <p>Can I know who is messaging me?</p>
      <form>
        <input class="w3-input w3-border" type="text" placeholder="Name - (Optional)" name="name">
      </form>
      <p><i>Want to call me?</i></p>
      <div class="w3-row">
        <div class="w3-half">
          <button onclick="document.getElementById('id01').style.display='none'" type="button" class="w3-button w3-block w3-green">Call</button>
        </div>
        <div class="w3-half">
          <button onclick="document.getElementById('id01').style.display='none'" type="button" class="w3-button w3-block w3-red">Cancel</button>
        </div>
      </div>
    </div>
  </div>
</div>

<!-- Footer -->
<footer class="w3-center w3-black w3-padding-16">
  <p>Powered by <a href="https://www.w3schools.com/w3css/default.asp" title="W3.CSS" target="_blank" class="w3-hover-text-green">w3.css</a></p>
</footer>
<div class="w3-hide-small" style="margin-bottom:32px"> </div>

</body>
 </template>
 <style>
img {
  width: 100%;
  height: auto;
}
</style>