<!DOCTYPE html>
<html>
<title>Beejam Game</title>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
<style>

	#watch-trailer {
		float:left;
		padding-top: 170px;
		padding-left: 40px;
		padding-right: 40px;
		text-align: center;
		position: relative;
		z-index:2;
	}

	#watch-trailer, #create-title, #follow-title {
		font-size: 60px;
		font-family: sans-serif;
		color:rgb(0,102,204);
	}
	
	#video-trailer {
		float:right;
		width:50%;
	
		position: absolute;
		z-index: 2;
		border-radius: 25px;
  		border: 4px solid #73AD21;
  		box-shadow: 3px 5px 10px black;
	}

	.rectangle-grey {
		height: 500px;
		width: 100%;
		background-color:rgb(235,236,237);
		position: relative;
		z-index: 1;

	}
	.rectangle-grey, .rectangle-white {
		border-top: 3px;
		border-top-color: rgb(204,204,202);
		border-top-style:solid;

	}

	.rectangle-white {
		height: 500px;
		width: 100%;
		background-color:white;
		position: relative;
		padding-top: 40px;
		z-index:2;
		
	}

	.download-rectangle {
		height: 200px;
		width:450px;
		margin-left: 5em;
		margin-top: -26em;
		background-color:lightgrey;

		position:absolute;
		border-radius: 50px;
		box-shadow: 3px 5px 10px black;

		
		border: 4px solid #73AD21;
		padding-top: .6em;
		
	}

	#apple-button {
		float:left;
		width: 47%;
		padding-left: 2em;
		padding-top: .4em;
	}

	#google-button {
		float:right;
		width: 47%;
		padding-right: 2em;
		padding-top: .4em;
	}

	#google-button:hover {
		opacity: 0.5;
	}

	#apple-button:hover {
		opacity: 0.5;
	}

	#intro-download {
		font-size: 40px;
	}

	#title-pic {
		position: relative;
		

	}

	#create-title {
		line-height: 93%;
		padding-top: 1.4em;
	}

	.intro-container {
		position: relative;
		text-align: center;
		
	}

	#game-logo {
		float:left;
		width: 30%;
		padding-left: 3.2em;
		padding-top: 3em;
		
	}

	.create-hive {
		float:right;
		width: 65%;
		text-align: left;
		
	}

	#create-text {
		font-size:25px;
	}

	#follow-title {
		font-size: 55px;
		padding-left: 1em;
		line-height: 93%;
	}

	.social-button {
		width: 10%;
		height: 140px;
		float:left;
		padding-left: 25em;
	}

	.social-button:hover {opacity: 0.5;}

	#insta-tag {
		float: left;
		padding-left: 2.4em;
		padding-top: 15em;
		
	}

  	.mail-button {
  		width: 10%;
		height: 140px;
		float:right;
		padding-right: 46em;
		padding-top: .5em;

  	}

  	.mail-button:hover {opacity: .5}

  	#mailing-list {
		float:right;
		padding-right: 30.5em;
		padding-top: 5.5em;
  	}

  	#address-info {
  		text-align: center;
  		opacity: .7;
  		font-size: .8em
  		
  		
  	}
  	.footer-box {
  		height: 100px;
  		width: 100%;
  		background-color: lightblue;
  		line-height: 90%;
  		padding-top: .1em;
  	}

  	#footer-info {
  		font-size: 17px;
  		text-align: center;
  		padding-top: 6px;
  		line-height: 0%;
  	}
  	
 	#footer-info, #address-info {
 		float:right;
 		width:70%;
 		padding-right: 475px;
 	}

  	#footer-contact {
  		font-size: 17px;
  		text-align: left;
  		float:left;
  		width:30%;
  		padding-left: 4em;
  		line-height: 140%
  	}

</style>
<body>

<!--Opening Image slide-->
<header>
	
	<div class="intro-container">
	
		<img id="title-pic" src="Beejam-title.jpg" alt="Beejam tittle picture" style="width:100%;">

		<div class="download-rectangle">
			<h2 id="intro-download"><b><em>Download it now!</em></b></h2>
			<a href="https://www.apple.com/app-store/">
				<img id="apple-button" src="apple-button.jpg" alt="apple button">
			</a>
			<a href="https://play.google.com/store/apps?hl=en_US&gl=US">
				<img id="google-button" src="google-button.jpg" alt="google button">
			</a>
		</div>
	</div>
</header>

<!-- Watch trailer Section -->
<div class="rectangle-white">
	<h1 id="watch-trailer"><b><em>Watch the trailer!</em></b></h1>
 	<video id="video-trailer" width="500" controls>
    	<source src="Beejam-Trailer1.mp4" type="video/mp4">
 	</video>
</div>


 <!-- Create your own hive Section -->
<div class="rectangle-grey">
 	<img id="game-logo" src="IMG_1529.jpeg" alt="App" width="335">
 	<div class="create-hive">
 		<h1 id="create-title"><b><em>Create your own hive <br> empire today!</em></b></h1>
 		<p id="create-text">Build your own bee world with BeeJam. Forage for resources, make honey, and raise bees to expand your hive empire. Sell honey in the market and use resources wisely to grow your hive quickly. Your new world awaits you. Come join us and download BeeJam.</p>
 	</div>
</div>

<!-- Follow us Section -->
<div class="rectangle-white">
	<h1 id="follow-title"><b><em>Follow us on instagram and sign up for <br>game updates!</em></b></h1>
	<div class="social-button">
		<a href="https://www.instagram.com/honeybeelabs/">
		<img src="insta-pic.jpg" alt="instagram">
		</a>
	</div>
	<div id="insta-tag">
		<h3><b>@honeybeelabs</b></h3>
	</div>
	<div class="mail-button">
		<a href="https://www.instagram.com/honeybeelabs/">
		<img src="mail-pic.jpg" alt="email">
		</a>
	</div>
	<div id="mailing-list">
		<h3><b>Join our mailing list</b></h3>
	</div>
	
</div>

<!-- Footer -->
<footer>
<div class="footer-box">
	<p id="footer-contact"><b>Contact us:</b> <br> beeyonce@honeybeelabs.com</p>
	<p id = "footer-info"><b>This game is made by HoneyBee Labs</b></p>
        <p id="address-info">330 Railroad Avenue, Greenwich, Connecticut <br>
        06830, United States</p>
</div>

</footer>

</body>
</html>
