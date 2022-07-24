<template>
	<section id="about">
		<div id="blue"></div>
		<div id="pink"></div>
		<div id="blue2"></div>
		<div id="glass-object">
			<div id="head">
				<h2 class="heading">- past, present -</h2>
				<h1 class="heading-">CAPTAINS LOG</h1>
			</div>
			<div id="information" >
				
					<div class="text ">
						<p id="para-about">
							I'm an ambitious, focused and determined individual. I'm also very
							competitive. I always look for ways to challenge myself. I'm very
							patient with others and work well in a team environment. I have a
							very spontaneous personality, which makes me think the adventurous
							characteristic applies to me. I have always been fascinated with
							technology, and I hope to become a web or software developer.
						</p>
						<p id="para-about">
							In 2020 my friends from university asked me to help them build a
							basic HTML and CSS website for a project. I spent the night on
							YouTube learning HTML and CSS and built a decent website for them,
							and ever since then, I've realised that I'm passionate about this
							kind of work. I was unable to attend university after I matriculated
							because I could not get the funding, and then I applied to Life
							Choices Academy. It's a blessing for me to pursue what I love rather
							than go to university and do something I'd not enjoy.
						</p>
					</div>
					<div class="alignment">

						<div class="text-2">
							<div id="resume">
								<h3 class="about-heading3">- Work Experience -</h3>
								<p class="para-about2">
									Voluntary Work at High School (2019)
								</p>
								<p class="para-about2">Cattering at Ashuras Cattering (2019 Dec)</p>
								<p class="para-about2">
									Waiter at Mariams Kitchen (2021/2022)
								</p>
							</div>
						</div>
									<div id="img-me">		
										<img class="img-fluid d-flex"
											style="width:250px;
											height:250px; border-radius: 50%; "
											src="https://i.postimg.cc/CMNCwmnL/IMG-20220722-063300.jpg"
											alt=""
										/>
										</div>
										<div class="text-2-1">
	
											<div id="resume2">
												<h3 class="about-heading3">- Education -</h3>
												<p class="para-about2">Rylands Primary School</p>
												<p class="para-about2">Rylands High School</p>
												<p class="para-about2">Life Choices Coding Academy (currently)</p>
											</div>
										</div>		
					</div>
					
					<div class="text-3">
						<h3 class="about-heading3">- Football -</h3>
						<p id="para-about3" >
							Aside from my passion for web development, i have a strong bond with
							the sport of football which developed during my time in highschool.</p>
			
							<p id="para-about3">I've also developed many soft skills because of the sport such
							teamwork and patience, which is why i have a high level of
							appreciation for the sport.
						</p>
					</div>
					<div class="alignment2">

						<iframe class="img-fluid"
							style="width:580px;
							height:350px;"
							src="https://www.youtube.com/embed/bLLODPSs1B8"
							title="Highlights"
							frameborder="0"
							allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
							allowfullscreen
						></iframe>
			
					</div>
			</div>
		</div>
	</section>
</template>
<script>
	export default {};
</script>
<style scoped>
@font-face {
    font-family: Atauri;
    src: url(../assets/fonts/Atures500PersonalUseOnly-GD6D.ttf);
}
	body {
		background: black;
	}
	p{
		margin-bottom: 0;
	}
	#about {
		padding: 20px;
		min-height: 100vh;
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
		flex-wrap: wrap;
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
		backdrop-filter: blur(70px);
		box-sizing: border-box;
		background-image: linear-gradient(
			45deg,
			rgba(255, 255, 255, 0.2),
			rgba(255, 255, 255, 0.2)
		);
		width: 100%;
		max-height: 100%;
		display: flex;
		flex-direction: row;
		flex-wrap: wrap;
		/* gap: 20px; */
	}
	#information {
		min-height: 80vh;
		display: flex;
		flex-direction: column;
		flex-wrap: nowrap;
		justify-content: center;
		align-content: center;
		/* gap: 40px; */
	}
	.text {
		margin-top: 2%;
		display: flex;
		flex-direction: column;
		flex-wrap: wrap;
		justify-content: start;
		align-items: flex-start;
		width: 100%;
		overflow: wrap;
	}
	.text-2 {
		display: flex;
		flex-direction: row;
		flex-wrap: wrap;
		justify-content: start;
		align-items: flex-start;
		width: 30%;
				overflow: wrap;

	}
	.text-2-1{
        display: flex;
		flex-direction: row;
		flex-wrap: wrap;
		justify-content: end;
		align-items: flex-end;
		width: 30%;
				overflow: wrap;
	}
.alignment{
	margin-top: 3%;
	margin-bottom: 5%;
	display: flex;
	flex-direction: row;
	flex-wrap: wrap;
	justify-content: center;
	align-items: center;
}
	.text-3 {
		/* margin-top: 2%; */
		display: flex;
		flex-direction: column;
		flex-wrap: wrap;
		justify-content: stretch;
		align-items: flex-start;
		width: 100%;
				overflow: wrap;

	}
	.alignment2{
		margin-top: 2%;
		display: flex;
		flex-direction: row;
		flex-wrap: wrap;
		justify-content: center;
		align-items: center;
	}
	#para-about {
		font-size: 18px;
		display: flex;
		flex-direction: column;
		flex-wrap: wrap;
		justify-content: start;
		align-items: flex-start;
		font-family: Atauri;
		margin-bottom: 2%;
		text-shadow: 2px 2px black;
	}
		#para-about3 {
		font-size: 18px;
		display: flex;
		flex-direction: column;
		flex-wrap: wrap;
		justify-content: start;
		align-items: flex-start;
		font-family: Atauri;
		text-shadow: 2px 2px black;
	}
	.para-about2 {
		font-size: 18px;
		display: flex;
		flex-direction: column;
		flex-wrap: wrap;
		justify-content: start;
		align-items: flex-start;
		font-family: Atauri;
		text-shadow: 2px 2px black;
	}
	.heading- {
		color: white;
		font-family: Rocket;
		text-shadow: 7px 7px black;
		letter-spacing: 4px;
		font-size: 30px;
	}
	.heading {
		color: #67b3e4;
		font-family: SpaceQuest;
		letter-spacing: 3px;
		text-shadow: 5px 5px black;
	}
	.about-heading3 {

		color: #67b3e4;
		text-shadow: 7px 7px black;
		font-family: Rocket;
		letter-spacing: 3px;
	}
	#resume {
			margin-top: 5%;
		margin-bottom: 5%;
	}
	#resume2 {
		margin-top: 5%;
		margin-bottom: 5%;
	}
	#img-me{
		border: 5px red;
	}
	@media only screen and (max-width: 1020px) {
		#glass-object {
	
		display: flex;
		flex-direction: column;
		flex-wrap: wrap;
		/* gap: 20px; */
	}
  #information {
		min-height: 80vh;
		display: flex;
		flex-direction: column;
		flex-wrap: wrap;
		justify-content: center;
		align-content: center;
		gap: 40px;
	}
	.text{
		
		margin-top: 2%;
		display: flex;
		flex-direction: row;
		flex-wrap: wrap;
		justify-content: center;
		align-items: center;
		overflow: wrap;
	}
	
	.text-2 {
		margin-top: -1%;
		display: flex;
		flex-direction: row;
		flex-wrap: wrap;
		justify-content: center;
		align-items: center;
				overflow: wrap;

	}
	#resume2{
		display: flex;
		flex-direction: column;
		justify-content: center;
		align-items: center;
	}

	.text-3 {
		margin-top: 2%;
		display: flex;
		flex-direction: row;
		flex-wrap: wrap;
		justify-content: center;
		align-items: center;
				overflow: wrap;

	}
}
</style>
