<html>
  <head>
    <style>
    body {
      background-image: radial-gradient( circle farthest-corner at -4.5% 34.3%,  rgba(13,20,174,1) 0%, rgba(243,165,140,1) 90% );
    }
    ul {
      list-style-type: none;
      margin: 0;
      padding: 0;
      overflow: hidden;
      background-image: linear-gradient(to right, rgba(255,0,0,0), rgb(254, 165, 140));
    }
    li {
      float: left;
    }
    
    li a, .dropbtn {
      display: inline-block;
      color: white;
      text-align: center;
      padding: 14px 16px;
      text-decoration: none;
    }
    
    li a:hover, .dropdown:hover .dropbtn {
      background-image: radial-gradient( circle farthest-corner at -4.5% 34.3%,  rgb(172, 18, 255) 0%, rgba(243,165,140,1) 90% );
    }
    
    li.dropdown {
      display: inline-block;
    }
    
    .dropdown-content {
      display: none;
      position: absolute;
      background-image: radial-gradient( circle farthest-corner at -4.5% 34.3%,  rgba(13,20,174,1) 0%, rgba(243,165,140,1) 90% );
      min-width: 160px;
      box-shadow: 0px 8px 16px 0px rgba(0,0,0,0.2);
      z-index: 1;
    }
    
    .dropdown-content a {
      color: black;
      padding: 12px 16px;
      text-decoration: none;
      display: block;
      text-align: left;
    }
    
    .dropdown-content a:hover {background-color: #f1f1f1;}
    
    .dropdown:hover .dropdown-content {
      display: block;
    }
    </style>
    </head>
    <body>
    
    <ul>
      <li><a href="#home">Home</a></li>
      <li class="dropdown">
        <a href="javascript:void(0)" class="dropbtn">Projects</a>
        <div class="dropdown-content">
          <a href="https://twitter.com/M_Bot22">Twitter AI Bot</a>
          <a href="#">Link 2</a>
          <a href="#">Link 3</a>
        </div>
      </li>
    </ul>
    </body>
<head>    
    <link href="style.css" rel="stylesheet" type="text/css">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <style>
    * {box-sizing: border-box}
    body {font-family: Verdana, sans-serif; margin:0}
    .mySlides {display: none}
    img {vertical-align: middle;}
    
    /* Slideshow container */
    .slideshow-container {
      max-width: 2000px;
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
      color: #f2f2f2;
      font-size: 15px;
      padding: 8px 12px;
      position: absolute;
      bottom: 8px;
      width: 100%;
      text-align: center;
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
      background-color: #bbb;
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
</style>
</head>
  <body>
    <div class="slideshow-container">

      <div class="mySlides fade">
        <div class="numbertext">1 / 3</div>
        <img src="https://cdn1.epicgames.com/ue/product/Screenshot/NeonCityscreenshot01-1920x1080-3503e85db9ae18f6c8c1c6eb3544b287.png?resize=1&w=1920" style="width:100%">
        <div class="text">Neon City</div>
      </div>
      
      <div class="mySlides fade">
        <div class="numbertext">2 / 3</div>
        <img src="https://cdnb.artstation.com/p/assets/images/images/031/994/447/large/laury-guintrand-noctem-final-shot1-hd1.jpg?1605177028" style="width:100%">
        <div class="text">Cyber Neon City</div>
      </div>
      
      <div class="mySlides fade">
        <div class="numbertext">3 / 3</div>
        <img src="img_mountains_wide.jpg" style="width:100%">
        <div class="text">Caption Three</div>
      </div>
      
      <a class="prev" onclick="plusSlides(-1)">❮</a>
      <a class="next" onclick="plusSlides(1)">❯</a>
      
      </div>
      <br>
      
      <div style="text-align:center">
        <span class="dot" onclick="currentSlide(1)"></span> 
        <span class="dot" onclick="currentSlide(2)"></span> 
        <span class="dot" onclick="currentSlide(3)"></span> 
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
<h1>Project Description 1 | Twitter AI Bot | Python &#128013;</h1>
<p>My first project is a Python script that composes tweets via Tweepy Python library to access the Twitter API. The script uses an Artificial Intelligence Python library (Open AI) to access the OpenAI API. The script is scheduled to run every 10 minutes using the Crontab program. @M_Bot22 composes tweets that consist of computer programming jokes, motivational quotes and computer programming related questions.</p>
<h1>Programming Languages</h1>
<p>Excel VBA</p>
<p>SQL</p>
<p>Python &#128013;</p>
<p>HTML</p>
<p>CSS</p>
<h1>Softwares, Libraries & Systems</h1>
<p>Tableau, Excel, VSCode, Tweepy, OpenAI, Crontab</p>
</body>
</html>
