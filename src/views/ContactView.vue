<template>
	<section id="contact">
		<h2 class="heading">- lets get in touch -</h2>
		<h1 class="heading-">JOIN THE FORCES</h1>
		<div class="contact-sec">
			<div class="col-md-4">
  <div class="form">

    <form class="register-form" action="https://formspree.io/f/mgedrzro" method="post">
      <input type="text" placeholder="Full Names"/>
      <input type="password" placeholder="Email Address"/>
            <input type="password" placeholder="Subject"/>
    </form>
    <form class="login-form" action="https://formspree.io/f/mgedrzro" method="post">
      <input type="text" placeholder="Full Name"/>
      <input type="text" placeholder="Email"/>
            <input type="text" placeholder="Phone Number"/>
            <textarea name="" id="submit-sec" class="mb-2 form-control" placeholder="Message"></textarea>

      <button type="submit">SUBMIT</button>
    </form>
  </div>
                        </div>
			<div id="map">
				<iframe
					src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d13233.337033150945!2d18.46262728338417!3d-33.983947139991216!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x1dcc42c52081a7cb%3A0x79fbdc90a0e82eac!2sClaremont%2C%20Cape%20Town%2C%207708!5e0!3m2!1sen!2sza!4v1658473922637!5m2!1sen!2sza"
					width="600"
					height="400"
					style="border: 10px black; margin-top: 6%;"
					allowfullscreen=""
					loading="lazy"
					referrerpolicy="no-referrer-when-downgrade"
				></iframe>
			</div>
			 
		</div>
	</section>
</template>
<script></script>
<style scoped>
	#contact {
		padding: 60px;
		min-height: 80vh;
		background: black
			linear-gradient(
				255.21deg,
				rgba(58, 39, 96, 0.6) 12.4%,
				rgba(25, 16, 41, 0.6) 33.1%,
				rgba(26, 23, 47, 0.6) 57.29%,
				rgba(32, 43, 65, 0.6) 77.17%,
				rgba(35, 99, 118, 0.6) 99.74%
			);
		display: flex;
		flex-direction: column;
		flex-wrap: nowrap;
		justify-content: center;
		align-content: center;
	}

	.contact-sec{
		display: flex;
		flex-direction: row;
	}
	.heading- {
		color: white;
		font-family: Rocket;
		text-shadow: 3px 3px black;
		letter-spacing: 1px;
		font-size: 30px;
	}
	.heading {
		color: #67b3e4;
		font-family: SpaceQuest;
		letter-spacing: 3px;
		text-shadow: 2px 2px black;
	}
	iframe{
		margin-left: 15%;
	}
	.form {
	width: 140%;
	height: 402px;
	position: relative;
	z-index: 1;
	background: #191c29;
	max-width: 360px;
	margin-left: 20%;
	margin-top: 35px;
	padding: 30px;
	text-align: center;
	box-shadow: 0 0 30px 0 rgba(0, 0, 0, 0.2), 0 5px 5px 0 rgba(0, 0, 0, 0.24);
}
.formbox {
	padding-left: 20%;
}
.form input {
	font-family: Rocket;
	outline: 0;
	background: #1d2537;
	width: 100%;
	border: 0;
	margin: 0 0 15px;
	padding: 15px;
	box-sizing: border-box;
	font-size: 14px;
}
.form button {
	font-family: "SpaceQuest1";
	letter-spacing: 2px;
	text-transform: uppercase;
	outline: 0;
	background: #1d5b6e;
	height: 100%;
	width: 100%;
	border: 0;
	padding: 15px;
	color: #ffffff;
	font-size: 14px;
	-webkit-transition: all 0.3 ease;
	transition: all 0.3 ease;
	cursor: pointer;
}
.form button:hover,
.form button:active,
.form button:focus {
	background: #252954;
}
.form .message {
	margin: 15px 0 0;
	color: #b3b3b3;
	font-size: 12px;
}
.form .message a {
	color: #1a2049;
	text-decoration: none;
}
.form .register-form {
	display: none;
}
.container {
	position: relative;
	z-index: 1;
	max-width: 300px;
	margin: 0 auto;
}
.container:before,
.container:after {
	content: "";
	display: block;
	clear: both;
}
.container .info {
	margin: 50px auto;
	text-align: center;
}
.container .info h1 {
	margin: 0 0 15px;
	padding: 0;
	font-size: 36px;
	font-weight: 300;
	color: #1a1a1a;
}
.container .info span {
	color: #4d4d4d;
	font-size: 12px;
}
.container .info span a {
	color: #000000;
	text-decoration: none;
}
.container .info span .fa {
	color: #ef3b3a;
}
.contact-container {
	height: 100%;
	width: 660px;
	align-items: center;
	background: radial-gradient(circle, #1a2049 0%, #13162f 100%);
	border-radius: 6px;
}
#submit-sec {
	font-family: Rocket;
	background-color:#1d2537;
	border: none;
    margin-bottom:15px;
	}
.fheading{
font-family: Rocket;
}
.fheading-{
font-family: SpaceQuest1;
}
	@media only screen and (max-width: 1020px){
		.contact-sec{
		display: flex;
		flex-direction: column;
	}
	.form {
	margin-left:0%;
	width: 100%;
	}
	
	iframe{
		width: 100%;
		margin-left: 0%;
	}
	#map{
		display: flex;
		flex-direction: row;
		flex-wrap: nowrap;
		justify-content: center;
		align-content: center;
	}
	}
</style>
