<template>
	<section id="contact">
		<div>
			<h2 class="heading">- lets get in touch -</h2>
			<h1 class="heading-">JOIN THE FORCES</h1>
			<div id="map">
				<iframe
					src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d13233.337033150945!2d18.46262728338417!3d-33.983947139991216!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x1dcc42c52081a7cb%3A0x79fbdc90a0e82eac!2sClaremont%2C%20Cape%20Town%2C%207708!5e0!3m2!1sen!2sza!4v1658473922637!5m2!1sen!2sza"
					width="600"
					height="400"
					style="border: 10px black; margin-top: 6%; margin-left: 5%"
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
		height: 80vh;
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
		flex-direction: row;
		flex-wrap: nowrap;
	}
	#blue {
		position: absolute;
		margin-bottom: 20%;
		margin-right: 70%;
		border-radius: 50%;
		background-color: #67b3e4;
		width: 15%;
		min-height: 25%;
	}
	#blue2 {
		position: absolute;
		margin-left: 70%;
		border-radius: 50%;
		background-color: #67b3e4;
		width: 15%;
		min-height: 25%;
	}
	#pink {
		position: absolute;

		margin-top: 30%;
		margin-right: 25%;
		border-radius: 50%;
		background-color: #c292de;
		width: 15%;
		min-height: 25%;
	}
	#glass-object {
		padding: 30px;
		backdrop-filter: blur(40px);
		box-shadow: 0 2px 10px rgb(0 0 0 / 10%), 0 10px 15px rgb(0 0 0 / 20%);
		box-sizing: border-box;
		background-image: linear-gradient(
			45deg,
			rgba(255, 255, 255, 0.2),
			rgba(255, 255, 255, 0.2)
		);
		width: 90%;
		min-height: 90%;
		mix-blend-mode: hard-light;
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
</style>
