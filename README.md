<html>
<head>
	<title>Portfolio Website</title>
	<link rel="stylesheet" type="text/css" href="style.css">
	<link rel="preconnect" href="https://fonts.gstatic.com">
  <link href="https://fonts.googleapis.com/css2?family=Josefin+Sans:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;1,100;1,200;1,300;1,400;1,500;1,600;1,700&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css" integrity="sha512-iBBXm8fW90+nuLcSKlbmrPcLa0OT92xO1BIsZ+ywDWZCvqsWgccV3gFoRBv0z+8dLJgyAHIhR35VZc2oM/gI1w==" crossorigin="anonymous" referrerpolicy="no-referrer" />
</head>
<body>
<!----hero Section start---->
	<div class="hero">
		<nav>
			<h2 class="logo"> My<span>Portfolio</span></h2>
			<ul>
				<li><a href="#">Home</a></li>
				<li><a href="#">Experience</a></li>
				<li><a href="Projects">Projects</a></li>
				<li><a href="#">Comments</a></li>
			</ul>
			<a href="#" class="btn">Contact Me</a>
		</nav>
		<div class="content">
			<h4>Hi, my name is</h4>
			<h1>Miguel <span>Jaimes</span></h1>
			<h3>I'm a Web Developer.</h3>
			<div class="newslatter">
				<form>
					<input type="email" name="email" id="mail" placeholder="Enter Your Email">
					<input type="submit" name="submit" value="Lets Start">
				</form>
			</div>
		</div>
	</div>
<!----About section start---->
	<section class="about">
		<div class="main">
			<!-- delete <img src="img/main-img.png"> delete -->
			<div class="about-text">
				<h2 style="text-align: center;"> Experience</h2>
				<h5> Programming Languages <span>Softwares, Libraries & Systems</span></h5>
				<p>I have some experience in the following program languages: Python &#128013; | HTML | SQL | Excel VBA. I have also used or currently use the following softwares, libraries and systems: Tableau | Excel | VSCode | Tweepy | OpenAI | Crontab.</p>
				<button type="button">Let's Talk</button>
			</div>
		</div>
	</section>
<!-----Projects section start----------->
	<div class="service">
		<div class="title">
			<h2>Projects</h2>
		</div>
		<div class="box">
			<div class="card">
				<i class="fas fa-user"></i>
				<h5>Twitter AI Bot</h5>
				<div class="pra">
					<p>@M_Bot22 composes tweets that consist of computer programming jokes, motivational quotes and computer programming related questions.</p>

					<p style="text-align: center;">
						<a class="button" href="#">Read More</a>
					</p>
				</div>
			</div>

			<div class="card">
				<i class="far fa-bell"></i>
				<h5>Project 2</h5>
				<div class="pra">
					<p>TBD</p>

					<p style="text-align: center;">
						<a class="button" href="#">Read More</a>
					</p>
				</div>
			</div>

			<div class="card">
				<i class="far fa-bell"></i>
				<h5>Project 3</h5>
				<div class="pra">
					<p>TBD</p>
					<p style="text-align: center;">
						<a class="button" href="#">Read More</a>
					</p>
				</div>
			</div>
		</div>
	</div>
<!-- Comment Box -->
 <div class="comment-box" id="HCB_comment_box"><a href="http://www.htmlcommentbox.com">HTML Comment Box</a> is loading comments...</div>
 <link rel="stylesheet" type="text/css" href="https://www.htmlcommentbox.com/static/skins/bootstrap/twitter-bootstrap.css?v=0" />
 <script type="text/javascript" id="hcb"> /*<!--*/ if(!window.hcb_user){hcb_user={};} (function(){var s=document.createElement("script"), l=hcb_user.PAGE || (""+window.location).replace(/'/g,"%27"), h="https://www.htmlcommentbox.com";s.setAttribute("type","text/javascript");s.setAttribute("src", h+"/jread?page="+encodeURIComponent(l).replace("+","%2B")+"&mod=%241%24wq1rdBcg%24nlI%2FRs6Kb0IEsnaC3wvpX1"+"&opts=16798&num=10&ts=1659499823558");if (typeof s!="undefined") document.getElementsByTagName("head")[0].appendChild(s);})(); /*-->*/ </script>
<!-- end www.htmlcommentbox.com -->
</div>
<!------footer start--------->
	<footer>
		<p>Miguel Jaimes</p>
		<div class="social">
			<a href="#"><i class="fab fa-facebook-f"></i></a>
			<a href="#"><i class="fab fa-instagram"></i></a>
			<a href="#"><i class="fab fa-dribbble"></i></a>
		</div>
	</footer>
</body>
</html>
