<template>
	<section id="contact">
		<div id="blue"></div>
		<div id="pink"></div>
		<div id="blue2"></div>
		<div id="glass-object">
			<h2 class="heading">- lets get in touch -</h2>
			<h1 class="heading-">CONTACT ME</h1>
		</div>
		<div class="container-about"></div>
	</section>
</template>
<script>
	export default {};
</script>
<style scoped>
	#contact {
		height: 100vh;
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
		justify-content: center;
		align-items: center;
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
