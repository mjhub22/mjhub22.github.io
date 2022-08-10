<html>
<head>
<style>
ul {
  border-radius: 25px;
  border: 2px solid #ffffff;
  list-style-type: none;
  margin: 0;
  padding: 0;
  overflow: hidden;
  background-color: #333;
}

li {
  float: left;
}

li a {
  display: block;
  color: white;
  text-align: center;
  padding: 14px 16px;
  text-decoration: none;
}

li a:hover {
  background-color: #111;
}
</style>
</head>
<body>

<ul>
  <li><a class="active" href="#home">Home</a></li>
  <li><a href="#section2">Projects</a></li>
  <li><a href="#section4">Descriptions</a></li>
  <li><a href="#section3">Leave a Comment</a></li>
</ul>

</body>
</style>
</head>
<!-- HTML TO IMPORT STYLE.CSS FILE -->
<head>    
    <link href="style.css" rel="stylesheet" type="text/css">
</head>
<!-- SMOOTH SCROLL/SITE NAVIGATION -->
<style>
    html {
        scroll-behavior: smooth;
        }
/*BACKGROUND COLOR/BOX SIZE FOR WELCOME MESSAGE  */
        #section1 {
          border-radius: 25px;
  border: 2px solid #ffffff;
  padding: 20px;
  width: 800px;
  height: 440px;
  background: #ED4264;  /* fallback for old browsers */
background: -webkit-linear-gradient(to right, #FFEDBC, #ED4264);  /* Chrome 10-25, Safari 5.1-6 */
background: linear-gradient(to right, #FFEDBC, #ED4264); /* W3C, IE 10+/ Edge, Firefox 16+, Chrome 26+, Opera 12+, Safari 7+ */
        }
/* BACKGROUND COLOR/BOX SIZE FOR CARD GRID*/
        #section2 { 
  border-radius: 25px;
  border: 2px solid #ffffff;
  padding: 20px;
  width: 800px;
  height: 440px;
  background: #ED4264;  /* fallback for old browsers */
background: -webkit-linear-gradient(to right, #FFEDBC, #ED4264);  /* Chrome 10-25, Safari 5.1-6 */
background: linear-gradient(to right, #FFEDBC, #ED4264); /* W3C, IE 10+/ Edge, Firefox 16+, Chrome 26+, Opera 12+, Safari 7+ */
}
/* BACKGROUND COLOR/BOX SIZE FOR COMMENTS */
#section3 { 
  border-radius: 25px;
  border: 2px solid #ffffff;
  padding: 20px;
  width: 700px;
  height: 440px;
  background: #ED4264;  /* fallback for old browsers */
background: -webkit-linear-gradient(to right, #FFEDBC, #ED4264);  /* Chrome 10-25, Safari 5.1-6 */
background: linear-gradient(to right, #FFEDBC, #ED4264); /* W3C, IE 10+/ Edge, Firefox 16+, Chrome 26+, Opera 12+, Safari 7+ */
}
</style>
</head>
<body>
<!-- WELCOME MESSAGE  -->
<div class="main" id="section1">
<style>
h1 {
  text-align: center;
  text-shadow: 0 0 3px #ff0059;
}
</style>
          <h1>Programming Languages</h1>
          <p>Excel VBA, SQL, Python &#128013;, HTML and CSS</p>
          <h1>Softwares, Libraries & Systems</h1>
          <p>Tableau, Excel, VSCode, Tweepy, OpenAI, Crontab</p>
        </div>
<!-- Responsive Card Grid Layout -->
        <head>
        <div class="main" id="section2">
          <title>Home</title>
          <meta charset="UTF-8" />
          <meta name="viewport" content="width=device-width" />
          <link rel="stylesheet" href="styles.css" />
        </head>
        <body>
      <section class="cards-wrapper">
        <div class="card-grid-space">
          <div class="num">01</div>
          <a class="card" href="https://twitter.com/M_Bot22" style="--bg-img: url(file:///Users/migueljaimes/Desktop/VS%20Code/Twitter%20AI%20PIC.jpeg)">
            <div>
              <h1>Twitter AI Bot</h1>
              <p>@M_Bot22 composes tweets that consist of computer programming jokes, motivational quotes and computer programming related questions.</p>
              <div class="date">July 2022</div>
              <div class="tags">
                <div class="tag">Python</div>
              </div>
            </div>
          </a>
        </div>
        <div class="card-grid-space">
          <div class="num">02</div>
          <a class="card" href="https://mjhub22.github.io/" style="--bg-img: url('file:///Users/migueljaimes/Desktop/VS%20Code/in-progress-icon-9.jpeg')">
            <div>
              <h1>TBD</h1>
              <p>TBD</p>
              <div class="date">August 2022</div>
              <div class="tags">
                <div class="tag">TBD</div>
              </div>
            </div>
          </a>
        </div>
      </section>      
        <div class="main" id="section4">
          <h1>Project Description 1 | Twitter AI Bot | Python &#128013;</h1>
          <p>My first project is a Python script that composes tweets via Tweepy Python library to access the Twitter API. The script uses an Artificial Intelligence Python library (Open AI) to access the OpenAI API. The script is scheduled to run every 10 minutes using the Crontab program. @M_Bot22 composes tweets that consist of computer programming jokes, motivational quotes and computer programming related questions.</p>
          <h1>Project Description 2 | TBD | TBD </h1>
          <p>In Progress</p>
        </div>
        <!-- Comment Box HTML -->
  <div class="main" id="section3">
  <div id="HCB_comment_box"><a href="http://www.htmlcommentbox.com">HTML Comment Box</a> is loading comments...</div>
  <link rel="stylesheet" type="text/css" href="https://www.htmlcommentbox.com/static/skins/bootstrap/twitter-bootstrap.css?v=0" />
  <script type="text/javascript" id="hcb"> /*<!--*/ if(!window.hcb_user){hcb_user={};} (function(){var s=document.createElement("script"), l=hcb_user.PAGE || (""+window.location).replace(/'/g,"%27"), h="https://www.htmlcommentbox.com";s.setAttribute("type","text/javascript");s.setAttribute("src", h+"/jread?page="+encodeURIComponent(l).replace("+","%2B")+"&mod=%241%24wq1rdBcg%24nlI%2FRs6Kb0IEsnaC3wvpX1"+"&opts=16798&num=10&ts=1659499823558");if (typeof s!="undefined") document.getElementsByTagName("head")[0].appendChild(s);})(); /*-->*/ </script>
  </div>
</body>
</html>
