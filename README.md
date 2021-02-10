# IRMIX-Radio
<html><!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="robots" content="index,follow"> 
    <link rel="icon" href="/images/logo.png">
    <link rel="stylesheet" href="/stylesheet.css">
    <title>IRMIX Radio Station</title>
</head>
<body>
<header> <img src="/images/logo.png" alt="logo" height="130px"> </header>

<nav>

    <a href="#"> HOME </a>

    <div class="dropdown">
      <button class="dropbtn">EXCLUSIVE</button>
      <div class="dropdown-content">
        <a href="#">ARTIST SPOTLIGHT</a>
        <a href="#">INTERVIEWS</a>
        <a href="#">ARCHIEVED SHOWS</a>
      </div>
    </div>

    <div class="dropdown">
      <button class="dropbtn">GUIDE</button>
      <div class="dropdown-content">
        <a href="#">PROGRAM GUIDE</a>
        <a href="#">ROKU</a>
        <a href="#">MEDIA KIT</a>
      </div>
    </div>

    <div class="dropdown">
      <button class="dropbtn">ABOUT</button>
      <div class="dropdown-content">
        <a href="#">HISTORY OF IRMIX RADIO</a>
        <a href="#">IRMIX RADIO STAFF</a>
        <a href="#">IRMIX RADIO HOSTS</a>
      </div>
    </div>

    <div class="search">
    <img src="/images/search.svg" alt="" >
</div>
</nav>

<div class="media-links">
    <a href="#"> <img src="/images/facebook.svg" alt="fb" style="padding-bottom: 10px;"> </a> 
    <a href="#"> <img src="/images/twitter.svg" alt="twitter" style="padding-bottom: 10px;"> </a>
    <a href="#"> <img src="/images/pinterest.svg" alt="pinterest" style="padding-bottom: 10px;"> </a>
<a href="#"> <img src="/images/email.svg" alt="email" style="height: 50px; width: 50px; padding-bottom: 10px;"> </a>
</div>

<main>
<img src="/images/www.irmixradio.net (5).png" alt="" style="height: 330px;">
<br>
<img src="/images/exclusive.PNG" alt="" style="width: 70rem;">
</main>

<section class="banner">
    <img src="/images/banner.PNG" alt="" style="height: 140px; width: 70rem;">
</section>

<div class="row">

    <div class="column">
 <!--      <section class="slides"> 
            <img src="/images/slide1.PNG" alt="Snow" >
        </section> --> 
        <div class="slideshow-container">

            <div class="mySlides fade">
              <img src="/images/slide1.PNG" style="width:100%">
            </div>
            
            <div class="mySlides fade">
              <img src="/images/slide2.JPG" style="width:100%">
            </div>
            
            <div class="mySlides fade">
              <img src="/images/slide3.JPG" style="width:100%">
            </div>

            <div class="mySlides fade">
                <img src="/images/slide4.JPG" style="width:100%">
              </div>

              <div class="mySlides fade">
                <img src="/images/slide5.JPG" style="width:100%">
              </div>

              <div class="mySlides fade">
                <img src="/images/slide6.JPG" style="width:100%">
              </div>

              <div class="mySlides fade">
                <img src="/images/slide7.JPG" style="width:100%">
              </div>

              <div class="mySlides fade">
                <img src="/images/slide8.JPG" style="width:100%">
              </div>

              <div class="mySlides fade">
                <img src="/images/slide9.JPG" style="width:100%">
              </div>
            
            </div>
            <br>
            
            <div style="text-align:center">
              <span class="dot"></span> 
              <span class="dot"></span> 
              <span class="dot"></span> 
              <span class="dot"></span> 
              <span class="dot"></span> 
              <span class="dot"></span> 
              <span class="dot"></span> 
              <span class="dot"></span> 
              <span class="dot"></span> 
            </div>

            <script>
                var slideIndex = 0;
                showSlides();
                
                function showSlides() {
                  var i;
                  var slides = document.getElementsByClassName("mySlides");
                  var dots = document.getElementsByClassName("dot");
                  for (i = 0; i < slides.length; i++) {
                    slides[i].style.display = "none";  
                  }
                  slideIndex++;
                  if (slideIndex > slides.length) {slideIndex = 1}    
                  for (i = 0; i < dots.length; i++) {
                    dots[i].className = dots[i].className.replace(" active", "");
                  }
                  slides[slideIndex-1].style.display = "block";  
                  dots[slideIndex-1].className += " active";
                  setTimeout(showSlides, 10000); 
                }
                </script>



    </div>

    <div class="column">
        <section class="video">
            <img src="/images/video.PNG" alt="" style="width: 40rem;">
        </section>
    </div>

    <div class="column">
        <section class="audio">
            <img src="/images/radio.PNG" style="width: 122%;" >
        </section>
    </div>

</div>

<section class="ad">
    <img src="/images/Capture.JPG" alt="" style="height: 140px; width: 70rem;">
</section>

<footer>
  <p> <strong>EXPLORE</strong> <br>
    Advertise  &nbsp; &nbsp; &nbsp; &nbsp;&nbsp;
    Common Sense Required &nbsp; &nbsp; &nbsp; &nbsp;&nbsp; 
    Program Guide  &nbsp; &nbsp; &nbsp; &nbsp;&nbsp;   
    ROKU &nbsp; &nbsp; &nbsp; &nbsp;&nbsp; <br><br>
    
    <strong>EXCLUSIVE </strong><br>            
    Tea Time Tuesdays with Tee     &nbsp; &nbsp; &nbsp; &nbsp;&nbsp;
    The Bridge with Cory George  &nbsp; &nbsp; &nbsp; &nbsp;&nbsp;
    Friday Night Jamz with DJ Suspence  &nbsp; &nbsp; &nbsp; &nbsp;&nbsp;
    Friday Night Jamz with DJ Extreme Detroit  &nbsp; &nbsp; &nbsp; &nbsp;&nbsp;    
    Friday Night Jamz with Dj Cos    &nbsp; &nbsp; &nbsp; &nbsp;&nbsp;               <br><br>
    
    Copyright © 2021, IRMIX Radio, LLC All rights reserved.</p>
</footer>

</body>
</html>
