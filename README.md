<!DOCTYPE html>
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<style>
* {
  box-sizing: border-box;
}
.menu {
  float: left;
  width: 20%;
}
.menuitem {
  padding: 8px;
  margin-top: 7px;
  border-bottom: 1px solid #f1f1f1;
}
.main {
  float: left;
  width: 60%;
  padding: 0 20px;
  overflow: hidden;
}
.right {
  background-color: rgb(173, 205, 230);
  float: left;
  width: 20%;
  padding: 10px 15px;
  margin-top: 7px;
}

@media only screen and (max-width:800px) {
  /* For tablets: */
  .main {
    width: 80%;
    padding: 0;
  }
  .right {
    width: 100%;
  }
}
@media only screen and (max-width:500px) {
  /* For mobile phones: */
  .menu, .main, .right {
    width: 100%;
  }
}
</style>
</head>
<div style="background-color:#f1f1f1;padding:15px;">
  <h1>Miguel Jaimes</h1>
  <h3>Projects and Experience</h3>
</div>

<body style="font-family:Arial;">
    <a class="weatherwidget-io" href="https://forecast7.com/en/33d47n117d70/dana-point/?unit=us" data-label_1="DANA POINT" data-label_2="WEATHER" data-theme="original" >DANA POINT WEATHER</a>
    <script>
    !function(d,s,id){var js,fjs=d.getElementsByTagName(s)[0];if(!d.getElementById(id)){js=d.createElement(s);js.id=id;js.src='https://weatherwidget.io/js/widget.min.js';fjs.parentNode.insertBefore(js,fjs);}}(document,'script','weatherwidget-io-js');
    </script>

<div style="overflow:auto">
  <div class="menu">
    <div class="menuitem"> <a href="https://www.w3schools.com/html/default.asp">HTML tutorial</a> </div>
    <div class="menuitem">Transport</div>
    <div class="menuitem">History</div>
    <div class="menuitem">Gallery</div>
  </div>

  <div class="main">
    <h2>The Walk</h2>
    <p>The walk from Monterosso to Riomaggiore will take you approximately two hours, give or take an hour depending on the weather conditions and your physical shape.</p>
  </div>

  <div class="right">
    <h2>Programming Languages</h2>
    <p>Python &#128013;, HTML, SQL, Excel VBA</p>
    <h2>Software</h2>
    <p>Tableau Data Visualization, Excel, VSCode, PyCharm</p>
  </div>
</div>


<div style="background-color:#f1f1f1;text-align:center;padding:10px;margin-top:7px;font-size:12px;"> Email: miguelrjaimes1@gmail.com </div>

</body>
</html>

