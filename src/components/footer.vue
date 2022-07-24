<template>
	<div id="logos">
		<div id="details">
			<div id="footer1" class="card w-100">
				<div style="margin-top: 8px" class="card-body2">
					<h2
						style="
							font-family: SpaceQuest;
							text-shadow: 3px 3px black;
							letter-spacing: 3px;
							margin-top: 10px;
							margin-bottom: 10px;
						"
					>
						Contact ME
					</h2>
					
							<p id="spacing" style="font-family: Atauri;">
								<i class="fa-solid fa-location-dot"></i> 314 IMAM HARRON RD,
								LANSDOWNE
							</p>
						
							<p id="spacing" style="font-family: Atauri; text-shadow: 2px black;">
								<i class="fa-solid fa-at"></i> khopatkarmudassar@gmail.com
							</p>
					
				</div>
				<div id="card-body1">
					<h2
						style="
							font-family: SpaceQuest;
							text-shadow: 3px 3px black;
							letter-spacing: 3px;
							margin-bottom: 8px;
						"
					>
						Discover
					</h2>
					<p style="margin-bottom: 10px; font-family: Atauri; ">
						Check out my code.
					</p>
					<div class="card-body1">
						<a id="spacing" href=""><i class="fa-brands fa-codepen"></i></a>
						<a
							id="spacing"
							href="https://github.com/MudassarKhop"
							target="blank"
							><i class="fa-brands fa-github"></i
						></a>
						<a
							id="spacing"
							href="https://www.linkedin.com/in/mudassar-khopatkar-a9854023a/"
							target="blank"
							><i class="fa-brands fa-linkedin"></i
						></a>
					</div>
				</div>
				
				
				<div id="card-body3">
					<h2
						style="
							font-family: SpaceQuest;
							text-shadow: 3px 3px black;
							letter-spacing: 3px;
							margin-bottom: 10px;
						"
					>
						Socials
					</h2>
					<p style="margin-bottom: 10px; font-family: Atauri; text-shadow: 2px black;">Find me on social media</p>
					<div  class="card-body3">
						<p id="spacing">
							<a href="#"><i class="fa-brands fa-instagram"></i></a>
						</p>
						<p id="spacing">
							<a href="#"><i class="fa-brands fa-facebook-f"></i></a>
						</p>
						<p id="spacing">
							<a href="#"><i class="fa-brands fa-google"></i></a>
						</p>
						<p id="spacing">
							<a href="#"><i class="fa-brands fa-twitter"></i></a>
						</p>
						<p id="spacing">
							<a href="#"><i class="fa-brands fa-whatsapp"></i></a>
						</p>
					</div>
				</div>
			</div>
		</div>
		<div id="details2">
			<div id="footer2" class="card" style="font-family:Rocket;">
				<p id="nav-foot2">©Life Choices-All Rights Reserved</p>
			</div>
		</div>
	</div>
</template>
<script>
	export default {};
</script>
<style scoped>
	@font-face {
    font-family: Atauri;
    src: url(../assets/fonts/Atures500PersonalUseOnly-GD6D.ttf);
}
	#logo {
		display: flex;
		flex-direction: row;
		flex-wrap: nowrap;
		justify-content: center;
		align-items: center;
	}
	#footer1 {
		height: 50vh;
		gap: 150px;
		background: rgba(29, 91, 110, 0.997) 99.74%;
	}
	
	.card-body1 {
		font-family: Atauri;
		display: flex;
		flex-direction: row;
		flex-wrap: wrap;
		justify-content: start;
		align-items: flex-start;
				
	}
	.card-body2 {
		display: flex;
		flex-direction: column;
		flex-wrap: wrap;
		justify-content: start;
		align-items: flex-start;
	}
	.card-body3 {
		display: flex;
		flex-direction: row;
		flex-wrap: wrap;
		justify-content: start;
		align-items: flex-start;
	}
	.card {
		height: 10vh;
		display: flex;
		flex-direction: row;
		flex-wrap: wrap;
		justify-content: center;
		align-items: center;
		background: rgba(15, 48, 58, 0.997) 99.74%;
	}
	#nav-foot {
		position: relative;
		left: -65%;
		font-size: 20px;
		font-family: Rocket;
		color: white;
		text-shadow: 3px 3px 4px black;
	}

	#nav-foot3 {
		margin-right: 7%;
	}
	.missing {
		color: transparent;
	}
	p{
		font-family: Atauri;
	}
	#spacing {
		margin-bottom: 10px;
		
	}
	li::marker {
		color: transparent;
	}
	@media only screen and (max-width: 1020px) {
		#footer1{
			display: flex;
			flex-direction: column;
			flex-wrap: wrap;
			justify-content: center;
			align-content: center;
			height: auto;
				gap: 50px;
				
		};
		#card-body1 {
		display: flex;
		flex-direction: column;
		flex-wrap: wrap;
		justify-content: center;
		align-items: center;
		margin-right: 10%;
	}
	.card-body1 {
		display: flex;
		flex-direction: row;
		flex-wrap: wrap;
		justify-content: center;
		align-items: center;
	
	}
	.card-body2 {
		display: flex;
		flex-direction: column;
		flex-wrap: wrap;
		justify-content: center;
		align-items: center;
	}
	.card-body3 {
		display: flex;
		flex-direction: row;
		flex-wrap: wrap;
		justify-content: center;
		align-items: center;
	}
	 
	}
	@media only screen and (max-width: 980px) {
		#footer1{
			display: flex;
			flex-direction: column;
			flex-wrap: wrap;
			justify-content: center;
			align-content: center;
			height: auto;
				gap: 50px;
				
		};
		#card-body1 {
		display: flex;
		flex-direction: column;
		flex-wrap: wrap;
		justify-content: center;
		align-items: center;
	
	}
	.card-body1 {
		display: flex;
		flex-direction: row;
		flex-wrap: wrap;
		justify-content: center;
		align-items: center;
	
	}
	.card-body2 {
		display: flex;
		flex-direction: column;
		flex-wrap: wrap;
		justify-content: center;
		align-items: center;
	}
	.card-body3 {
		display: flex;
		flex-direction: row;
		flex-wrap: wrap;
		justify-content: center;
		align-items: center;
	}
		 
	}
	@media only screen and (max-width: 992px) {
		#footer1{
			display: flex;
			flex-direction: column;
			flex-wrap: wrap;
			justify-content: center;
			align-content: center;
			height: auto;
				gap: 40px;
		};
		#card-body1 {
		display: flex;
		flex-direction: column;
		flex-wrap: wrap;
		justify-content: center;
		align-items: center;
		margin-top: 1%;

	}
	#card-body3 {
		display: flex;
		flex-direction: column;
		flex-wrap: wrap;
		justify-content: center;
		align-items: center;
		margin-bottom: 1%;

	}
	.card-body1 {
		display: flex;
		flex-direction: row;
		flex-wrap: wrap;
		justify-content: center;
		align-items: center;
	
	}
	.card-body2 {
		display: flex;
		flex-direction: column;
		flex-wrap: wrap;
		justify-content: center;
		align-items: center;
		
	}
	.card-body3 {
		display: flex;
		flex-direction: row;
		flex-wrap: wrap;
		justify-content: center;
		align-items: center;
	}
	 
		
	}
</style>
