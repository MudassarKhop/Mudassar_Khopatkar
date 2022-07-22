<template>
	<section id="landing">
		<div class="container">
			<div class="stars">
				<Icons />
				<div class="head">
					<h1>MUDASSAR KHOPATKAR</h1>
					<p>-aspiring web developer-</p>
				</div>
				<div class="head2">
					<h1>WELCOME TO My UNIVERSE</h1>
				</div>
			</div>
			<div class="night">
				<div class="shooting_star"></div>
				<div class="shooting_star"></div>
				<div class="test"></div>
				<div class="test1"></div>
				<article class="earth-demo">
					<div class="earth">
						<a href="/about/"
							><img
								src="https://cssanimation.rocks/images/random/earth.png"
								alt=""
						/></a>
					</div>
					<div class="moon-container">
						<div class="moon">
							<a href="/projects/"
								><img
									src="https://cssanimation.rocks/images/random/moon.png"
									alt=""
							/></a>
						</div>
					</div>
				</article>
			</div>
		</div>
	</section>
</template>
<script>
	import icons from "@/components/icons.vue";
	import Icons from "@/components/icons.vue";
	export default {
		components: { icons, Icons },
	};
</script>
<style scoped>
	* {
		padding: 0;
		margin: 0;
		/* box-sizing: border-box; */
	}

	@font-face {
		font-family: SpaceQuest;
		src: url(../assets/fonts/SpaceQuest-Xj4o.ttf);
	}
	@font-face {
		font-family: SpaceQuest1;
		src: url(../assets/fonts/SpaceQuest-yOY3.ttf);
	}
	@font-face {
		font-family: SpaceQuest2;
		src: url(../assets/fonts/SpaceQuestItalic-60Rx.ttf);
	}
	@font-face {
		font-family: SpaceQuest3;
		src: url(../assets/fonts/SpaceQuestItalic-g8jY.ttf);
	}
	@font-face {
		font-family: SpaceMIssion;
		src: url(../assets/fonts/SpaceMission-rgyw9.otf);
	}
	@font-face {
		font-family: Edge;
		src: url(../assets/fonts/EdgeOfTheGalaxyPosterItalic-x3o1m.otf);
	}
	@font-face {
		font-family: EdgeReg;
		src: url(../assets/fonts/EdgeOfTheGalaxyRegular-OVEa6.otf);
	}
	@font-face {
		font-family: StarJedi;
		src: url(../assets/fonts/StarJedi-DGRW.ttf);
	}
	@font-face {
		font-family: Rocket;
		src: url(../assets/fonts/RocketRinder-yV5d.ttf);
	}
	.head {
		font-size: 40px;
		display: flex;
		flex-direction: column;
		flex-wrap: wrap;
		justify-content: center;
		align-items: center;
		color: white;
		letter-spacing: 2px;
		font-family: SpaceQuest1;
		text-shadow: 5px 5px black;
	}
	.head2 {
		position: relative;
		font-size: 45px;
		margin-top: 20%;
		display: flex;
		flex-direction: row;
		flex-wrap: wrap;
		justify-content: center;
		align-items: center;
		color: white;
		letter-spacing: 5px;
		font-family: Rocket;
		text-shadow: 10px 10px black;
	}

	body {
		background-color: #161a2d;
	}

	.container {
		position: relative;
		height: 100vh;
		background: linear-gradient(
			255.21deg,
			rgba(58, 39, 96, 0.6) 12.4%,
			rgba(25, 16, 41, 0.6) 33.1%,
			rgba(26, 23, 47, 0.6) 57.29%,
			rgba(32, 43, 65, 0.6) 77.17%,
			rgba(35, 99, 118, 0.6) 99.74%
		);
		overflow: hidden;
	}

	.night {
		position: relative;
		width: 100%;
		height: 100%;
		transform: rotateZ(45deg);
	}

	.test {
		position: absolute;
		left: 50%;
		top: 50%;
		color: transparent;
	}
	.test1 {
		position: absolute;
		left: calc(50% - -113px);
		top: calc(50% - 215px);
		color: transparent;
	}

	.shooting_star {
		opacity: 0.5;
		position: absolute;
		left: 50%;
		top: 50%;
		height: 2px;
		background: linear-gradient(-45deg, #5f91ff, rgba(0, 0, 255, 0));
		border-radius: 999px;
		filter: drop-shadow(0 0 6px #699bff);
		-webkit-animation: tail 13000ms ease-in-out infinite,
			shooting 13000ms ease-in-out infinite;
		animation: tail 13000ms ease-in-out infinite,
			shooting 13000ms ease-in-out infinite;
	}
	.shooting_star::before {
		content: "";
		position: absolute;
		top: calc(50% - 1px);
		right: 0;
		height: 2px;
		background: linear-gradient(
			-45deg,
			rgba(0, 0, 255, 0),
			#5f91ff,
			rgba(0, 0, 255, 0)
		);
		transform: translateX(50%) rotateZ(45deg);
		border-radius: 100%;
		-webkit-animation: shining 13000ms ease-in-out infinite;
		animation: shining 13000ms ease-in-out infinite;
	}
	.shooting_star::after {
		content: "";
		position: absolute;
		top: calc(50% - 1px);
		right: 0;
		height: 2px;
		background: linear-gradient(
			-45deg,
			rgba(0, 0, 255, 0),
			#5f91ff,
			rgba(0, 0, 255, 0)
		);
		transform: translateX(50%) rotateZ(45deg);
		border-radius: 100%;
		-webkit-animation: shining 13000ms ease-in-out infinite;
		animation: shining 13000ms ease-in-out infinite;
		transform: translateX(50%) rotateZ(-45deg);
	}
	.shooting_star:nth-child(1) {
		left: calc(50% - -113px);
		top: calc(50% - 215px);
		-webkit-animation-delay: 0;
		animation-delay: 0;
	}
	.shooting_star:nth-child(1)::before,
	.shooting_star:nth-child(1)::after {
		-webkit-animation-delay: 0;
		animation-delay: 0;
	}
	.shooting_star:nth-child(2) {
		top: calc(50%);
		left: calc(50%);
		-webkit-animation-delay: 3900ms;
		animation-delay: 3900ms;
	}
	.shooting_star:nth-child(2)::before,
	.shooting_star:nth-child(2)::after {
		-webkit-animation-delay: 3900ms;
		animation-delay: 3900ms;
	}

	@-webkit-keyframes tail {
		90% {
			width: 0;
		}
		95% {
			width: 100px;
		}
		100% {
			width: 0;
		}
	}

	@keyframes tail {
		90% {
			width: 0;
		}
		95% {
			width: 100px;
		}
		100% {
			width: 0;
		}
	}
	@-webkit-keyframes shining {
		95% {
			width: 0;
		}
		97% {
			width: 30px;
		}
		98% {
			width: 0;
		}
	}
	@keyframes shining {
		95% {
			width: 0;
		}
		97% {
			width: 30px;
		}
		98% {
			width: 0;
		}
	}
	/* @-webkit-keyframes shooting {
	  0% {
	    transform: translateX(0);
	  }
	  10% {
	    transform: translateX(300px);
	  }
	  10% {
	    transform: translateX(300px);
	  }

	} */
	@keyframes shooting {
		95% {
			transform: translateX(0);
		}
		100% {
			transform: translateX(300px);
		}
	}

	@keyframes move-twink-back {
		from {
			background-position: 0 0;
		}
		to {
			background-position: -10000px 5000px;
		}
	}

	.stars,
	.twinkling,
	.clouds {
		position: absolute;
		top: 0;
		left: 0;
		right: 0;
		bottom: 0;
		width: 100%;
		height: 100%;
		display: block;
	}

	.stars {
		background: black url(https://i.postimg.cc/cL0BR5C3/stars-1.png) repeat top
			center;
		z-index: 0;
		animation: animatedBackground 1000s linear infinite;
		background-position: 0 0;
		background-size: auto 100%;
	}

	.twinkling {
		background: transparent
			linear-gradient(
				255.21deg,
				rgba(58, 39, 96, 0.6) 12.4%,
				rgba(25, 16, 41, 0.6) 33.1%,
				rgba(26, 23, 47, 0.6) 57.29%,
				rgba(32, 43, 65, 0.6) 77.17%,
				rgba(35, 99, 118, 0.6) 99.74%
			)
			url(https://i.postimg.cc/KzMTSn4F/twinkling-1.png) repeat top center;
		z-index: 1;
		animation: move-twink-back 200s linear infinite;
	}

	@keyframes animatedBackground {
		from {
			background-position: 0 0;
		}
		/*use negative width if you want it to flow right to left else and positive for left to right*/
		to {
			background-position: 0 -10000px;
		}
	}
	.earth {
		animation: spin 50s linear infinite;
		position: absolute;
		top: calc(50% - 100px);
		left: calc(50% - 100px);
	}

	.earth img {
		height: 200px;
		display: flex;
		flex-direction: row;
		flex-wrap: wrap;
		justify-content: center;
		align-items: center;
		width: 200px;
	}

	.moon-container {
		position: absolute;
		top: calc(50% - 25px);
		left: calc(50% - 25px);
	}

	.moon {
		animation: spin 20s linear infinite;
		background: none;
		height: 50px;
		pointer-events: none;
		transform-origin: 25px;
		width: 50px;
	}

	.moon img {
		height: 50px;
		transform: translateX(-160px) translateY(-160px);
		width: 50px;
	}

	.earth img,
	.moon img {
		border-radius: 50%;
		box-shadow: 0 0 12em 1em rgba(110, 140, 200, 0.6);
	}

	.earth img,
	.moon img {
		border-radius: 50%;
		box-shadow: 0 0 12em 1em rgba(110, 140, 200, 0.6);
	}

	@keyframes spin {
		to {
			transform: rotateZ(360deg);
		}
	}
	
		
	@media only screen and (min-width: 1020px) {
		.head {
		font-size: 17px;
		margin-top: 5%;
		display: flex;
		flex-direction: row;
		flex-wrap: wrap;
		justify-content: center;
		align-items: center;
		color: white;
		letter-spacing: 2px;
		font-family: SpaceQuest1;
		text-shadow: 5px 5px black;
	}
	.head2 {
		position: relative;
		font-size: 11px;
		margin-top: 63%;
		display: flex;
		flex-direction: column;
		flex-wrap: nowrap;
		justify-content: center;
		align-items: center;
		color: white;
		letter-spacing: 5px;
		font-family: Rocket;
		text-shadow: 10px 10px black;
	}
	}
	@media only screen and (min-width: 414px) {
		.head {
		font-size: 17px;
		margin-top: 30%;
		display: flex;
		flex-direction: row;
		flex-wrap: wrap;
		justify-content: center;
		align-items: center;
		color: white;
		letter-spacing: 2px;
		font-family: SpaceQuest1;
		text-shadow: 5px 5px black;
	}
	.head2 {
		position: relative;
		font-size: 11px;
		margin-top: 63%;
		display: flex;
		flex-direction: column;
		flex-wrap: nowrap;
		justify-content: center;
		align-items: center;
		color: white;
		letter-spacing: 5px;
		font-family: Rocket;
		text-shadow: 10px 10px black;
	}
	}
	@media only screen and (min-width: 375px) {
		.head {
		font-size: 17px;
		margin-top: 5%;
		display: flex;
		flex-direction: row;
		flex-wrap: wrap;
		justify-content: center;
		align-items: center;
		color: white;
		letter-spacing: 2px;
		font-family: SpaceQuest1;
		text-shadow: 5px 5px black;
	}
	.head2 {
		position: relative;
		font-size: 11px;
		margin-top: 65%;
		display: flex;
		flex-direction: column;
		flex-wrap: nowrap;
		justify-content: center;
		align-items: center;
		color: white;
		letter-spacing: 5px;
		font-family: Rocket;
		text-shadow: 10px 10px black;
	}
	}
	@media only screen and (min-width: 390px) {
		.head {
		font-size: 17px;
		margin-top: 27%;
		display: flex;
		flex-direction: row;
		flex-wrap: wrap;
		justify-content: center;
		align-items: center;
		color: white;
		letter-spacing: 2px;
		font-family: SpaceQuest1;
		text-shadow: 5px 5px black;
	}
	.head2 {
		position: relative;
		font-size: 11px;
		margin-top: 63%;
		display: flex;
		flex-direction: column;
		flex-wrap: nowrap;
		justify-content: center;
		align-items: center;
		color: white;
		letter-spacing: 5px;
		font-family: Rocket;
		text-shadow: 10px 10px black;
	}
	}
	@media only screen and (min-width: 393px) {
		.head {
		font-size: 17px;
		margin-top: 27%;
		display: flex;
		flex-direction: row;
		flex-wrap: wrap;
		justify-content: center;
		align-items: center;
		color: white;
		letter-spacing: 2px;
		font-family: SpaceQuest1;
		text-shadow: 5px 5px black;
	}
	.head2 {
		position: relative;
		font-size: 11px;
		margin-top: 63%;
		display: flex;
		flex-direction: column;
		flex-wrap: nowrap;
		justify-content: center;
		align-items: center;
		color: white;
		letter-spacing: 5px;
		font-family: Rocket;
		text-shadow: 10px 10px black;
	}
	}
	@media only screen and (min-width: 360px) {
		.head {
		font-size: 17px;
		margin-top: 18%;
		display: flex;
		flex-direction: row;
		flex-wrap: wrap;
		justify-content: center;
		align-items: center;
		color: white;
		letter-spacing: 2px;
		font-family: SpaceQuest1;
		text-shadow: 5px 5px black;
	}
	.head2 {
		position: relative;
		font-size: 11px;
		margin-top: 63%;
		display: flex;
		flex-direction: column;
		flex-wrap: nowrap;
		justify-content: center;
		align-items: center;
		color: white;
		letter-spacing: 5px;
		font-family: Rocket;
		text-shadow: 10px 10px black;
	}
	}
	@media only screen and (min-width: 412px) {
		.head {
		font-size: 17px;
		margin-top: 30%;
		display: flex;
		flex-direction: row;
		flex-wrap: wrap;
		justify-content: center;
		align-items: center;
		color: white;
		letter-spacing: 2px;
		font-family: SpaceQuest1;
		text-shadow: 5px 5px black;
	}
	.head2 {
		position: relative;
		font-size: 11px;
		margin-top: 65%;
		display: flex;
		flex-direction: column;
		flex-wrap: nowrap;
		justify-content: center;
		align-items: center;
		color: white;
		letter-spacing: 5px;
		font-family: Rocket;
		text-shadow: 10px 10px black;
	}
	}
	@media only screen and (min-width: 820px) {
		.head {
		font-size: 30px;
		margin-top: 28%;
		display: flex;
		flex-direction: row;
		flex-wrap: wrap;
		justify-content: center;
		align-items: center;
		color: white;
		letter-spacing: 2px;
		font-family: SpaceQuest1;
		text-shadow: 5px 5px black;
	}
	.head2 {
		position: relative;
		font-size: 30px;
		margin-top: 32%;
		display: flex;
		flex-direction: column;
		flex-wrap: nowrap;
		justify-content: center;
		align-items: center;
		color: white;
		letter-spacing: 5px;
		font-family: Rocket;
		text-shadow: 10px 10px black;
	}
	}
	@media only screen and (min-width: 769px) {
		.head {
		font-size: 30px;
		margin-top: 20%;
		display: flex;
		flex-direction: row;
		flex-wrap: wrap;
		justify-content: center;
		align-items: center;
		color: white;
		letter-spacing: 2px;
		font-family: SpaceQuest1;
		text-shadow: 5px 5px black;
	}
	.head2 {
		position: relative;
		font-size: 25px;
		margin-top: 32%;
		display: flex;
		flex-direction: column;
		flex-wrap: nowrap;
		justify-content: center;
		align-items: center;
		color: white;
		letter-spacing: 5px;
		font-family: Rocket;
		text-shadow: 10px 10px black;
	}
	}
	@media only screen and (min-width: 912px) {
		.head {
		font-size: 35px;
		margin-top: 32%;
		display: flex;
		flex-direction: row;
		flex-wrap: wrap;
		justify-content: center;
		align-items: center;
		color: white;
		letter-spacing: 2px;
		font-family: SpaceQuest1;
		text-shadow: 5px 5px black;
	}
	.head2 {
		position: relative;
		font-size: 35px;
		margin-top: 32%;
		display: flex;
		flex-direction: column;
		flex-wrap: nowrap;
		justify-content: center;
		align-items: center;
		color: white;
		letter-spacing: 5px;
		font-family: Rocket;
		text-shadow: 10px 10px black;
	}
	}
	@media only screen and (min-width: 540px) {
		.head {
		font-size: 20px;
		margin-top: 5%;
		display: flex;
		flex-direction: row;
		flex-wrap: wrap;
		justify-content: center;
		align-items: center;
		color: white;
		letter-spacing: 2px;
		font-family: SpaceQuest1;
		text-shadow: 5px 5px black;
	}
	.head2 {
		position: relative;
		font-size: 15px;
		margin-top: 48%;
		display: flex;
		flex-direction: column;
		flex-wrap: nowrap;
		justify-content: center;
		align-items: center;
		color: white;
		letter-spacing: 5px;
		font-family: Rocket;
		text-shadow: 10px 10px black;
	}
	}
		@media only screen and (min-width: 280px) {
		.head {
		font-size: 12px;
		margin-top: 5%;
		display: flex;
		flex-direction: row;
		flex-wrap: wrap;
		justify-content: center;
		align-items: center;
		color: white;
		letter-spacing: 2px;
		font-family: SpaceQuest1;
		text-shadow: 5px 5px black;
	}
	.head2 {
		position: relative;
		font-size: 5px;
		margin-top: 90%;
		display: flex;
		flex-direction: column;
		flex-wrap: nowrap;
		justify-content: center;
		align-items: center;
		color: white;
		letter-spacing: 5px;
		font-family: Rocket;
		text-shadow: 10px 10px black;
	}
	}
</style>
