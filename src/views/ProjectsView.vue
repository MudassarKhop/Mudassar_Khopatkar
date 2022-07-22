<template>
	<section id="projects">
		<h2 class="heading">- some of my work -</h2>
		<h1 class="heading-">SUCCESSFUL MISSIONS</h1>
		<div class="projects-section">
			<div class="project-text2">
				<div class="iphone">
					<img
						class="png1"
						src="https://i.postimg.cc/SNyYbngh/Screenshot-2022-07-20-133024.png"
						alt=""
					/>
				</div>
				<div class="laptop">
					<img
						src="https://i.postimg.cc/vHFKXs8k/Screenshot-2022-07-20-133058-1.png"
						alt=""
						class="png2"
					/>
				</div>
					<div class="project-text">
						<h3 class="about-heading3">- FIND WHAT YOU'RE LOOKING FOR -</h3>
						<p id="para-about">
							USE THE SORT FUNCTION TO FIND PROJECTS WITH DISTINT LANGUAGES
						</p>
						<div class="projectFilter" v-if="filteredProjects">
							<select v-model="language">
								<option value="all">All</option>
								<option value="CSS">CSS</option>
								<option value="JAVASCRIPT">Javascript</option>
								<option value="BOOTSTRAP">Bootstrap</option>
								<option value="VUE">Vue</option>
							</select>
						</div>
					</div>
			</div>
		</div>
		<div class="cardholder">
			<Projectcard
				v-for="project of filteredProjects"
				:key="project.id"
				:project="project"
			/>
		</div>
	</section>
	<Footer />
</template>
<script>
	import Icons from "@/components/icons.vue";
	import Projectcard from "../components/projectcard.vue";
	import Footer from "../components/footer.vue";
	export default {
		components: { Footer },
		computed: {
			filteredProjects() {
				return this.projects.filter((project) => {
					let isMatch = true;
					if (this.language !== "all" && project.language !== this.language)
						isMatch = false;
					return isMatch;
				});
			},
		},
		data() {
			return {
				projects: [
					{
						id: "1",
						img: "https://i.postimg.cc/Vk9zYRtg/Screenshot-2022-07-21-095105.jpg",
						title: "_To-Dooo-List_",
						description: "",
						language: "JAVASCRIPT",
						date: "",
						github: "https://github.com/MudassarKhop/toDolist/",
						livelink: "https://starlit-dasik-66b676.netlify.app/",
					},
					{
						id: "2",
						img: "https://i.postimg.cc/0jJqhdxp/Screenshot-2022-07-21-095132.jpg",
						title: "_Car-Website_",
						description: "",
						language: "JAVASCRIPT",
						date: "",
						github: "https://github.com/MudassarKhop/car/",
						livelink: "https://muda-autohaus.netlify.app/",
					},
					{
						id: "3",
						img: "https://i.postimg.cc/tg2y642V/Screenshot-2022-07-21-095033.jpg",
						title: "BMI Calculator",
						description: "",
						language: "JAVASCRIPT",
						date: "",
						github: "https://github.com/MudassarKhop/BMI-CALCULATOR/",
						livelink: "https://jade-lolly-f704c9.netlify.app/",
					},
					{
						id: "4",
						img: "https://i.postimg.cc/G2fCMS0L/Screenshot-2022-07-21-095048.jpg",
						title: "Weather Converter",
						description: "",
						language: "JAVASCRIPT",
						date: "",
						github: "https://github.com/MudassarKhop/Weather-Concerter/",
						livelink: "https://dashing-dusk-c36bf8.netlify.app/",
					},
					{
						id: "5",
						img: "https://i.postimg.cc/7b8y4GYj/Screenshot-2022-07-21-094939.jpg",
						title: "Restaurant Website",
						description: "",
						language: "BOOTSTRAP",
						date: "",
						github: "https://github.com/MudassarKhop/restaurant/",
						livelink: "https://mudassarrestaurant.netlify.app/",
					},
					{
						id: "6",
						img: "https://i.postimg.cc/9M02YHng/Screenshot-2022-07-21-095153.jpg",
						title: "_Game-Website_",
						description: "",
						language: "VUE",
						date: "",
						github: "https://github.com/MudassarKhop/Sal/",
						livelink: "https://mellifluous-torte-f0f720.netlify.app/",
					},
					{
						id: "7",
						img: "https://i.postimg.cc/2SNzRJ13/Screenshot-2022-07-21-094959.jpg",
						title: "Mock Portfolio",
						description: "",
						language: "CSS",
						date: "",
						github: "https://github.com/MudassarKhop/Real-Portoflio/",
						livelink: "https://mudassarkhopatkar.netlify.app/",
					},
					{
						id: "8",
						img: "https://i.postimg.cc/43Jsn9bg/Screenshot-2022-07-21-095015.jpg",
						title: "Java-Calculator",
						description: "",
						language: "JAVASCRIPT",
						date: "",
						github: "https://github.com/MudassarKhop/applecalculator/",
						livelink: "https://gorgeous-profiterole-599685.netlify.app/",
					},
				],
				language: "all",
			};
		},
		components: { Projectcard, Icons, Icons, Icons, Icons, Projectcard },
	};
</script>
<style scoped>
	#projects {
		min-height: 100vh;
		padding: 50px;
		background: black
			linear-gradient(
				255.21deg,
				rgba(58, 39, 96, 0.6) 12.4%,
				rgba(25, 16, 41, 0.6) 33.1%,
				rgba(26, 23, 47, 0.6) 57.29%,
				rgba(32, 43, 65, 0.6) 77.17%,
				rgba(35, 99, 118, 0.6) 99.74%
			);
	}
	select{
		background-color:rgb(48, 48, 48) ;
	}
	option{
		font-family: Rocket;
		word-spacing: 5px;
	}
	.projects-section {
		display: flex;
		flex-wrap: nowrap;
		flex-direction: row;
		justify-content: center;
		align-items: center;
		margin-left: 5%;
		margin-bottom: 7%;
	}
	.projectdesc {
		display: flex;
		flex-direction: column;
		flex-wrap: nowrap;
	}
	.iphone {
		position: absolute;
		display: flex;
		flex-direction: row;
		flex-wrap: nowrap;
		justify-content: end;
		align-items: flex-end;
		margin-top: 7%;
		margin-left: 5%;
	}
	.laptop {
		display: flex;
		flex-direction: row;
		flex-wrap: nowrap;
		justify-content: end;
		align-content: flex-end;
		margin-top: 10%;
		/* margin-left: 15%; */
	}

	.png1 {
		height: 380px;
		width: 190px;
	}
	.png2 {
		width: 780px;
		height: 400px;
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

	/*  */

	.cardholder {
		display: flex;
		flex-direction: row;
		flex-wrap: wrap;
		justify-content: center;
		align-items: center;
		gap: 60px;
	}
	.projectFilter {
		display: flex;
		flex-direction: row;
		flex-wrap: nowrap;
		justify-content: center;
		align-content: center;
		margin-bottom: 5%;
	}
	select {
		width: 190px;
		height: 50px;
		filter: drop-shadow(4px 4px 4px grey);
	}
	.project-text {
		display: flex;
		flex-direction: column;
		flex-wrap: wrap;
		justify-content: center;
		align-items: center;
	}
	.project-text2 {
	}
	.about-heading3 {
		font-size: 15px;
		margin-bottom: 4%;
		color: #67b3e4;
		text-shadow: 7px 7px black;
		font-family: Rocket;
		letter-spacing: 4px;
	}
	#para-about {
		display: flex;
		flex-direction: column;
		flex-wrap: wrap;
		justify-content: center;
		align-items: center;
		font-family: SpaceQuest2;
		margin-bottom: 6%;
		text-shadow: 3px 3px black;
	}
	/*  */
	 @media only screen and (max-width: 1140px)  {
		.png1 {
		height: 120px;
		width: 90px;
	}
	.png2 {
		width: 520px;
		height: 200px;
	}
	.project-text {
		display: flex;
		flex-direction: column;
		flex-wrap: wrap;
		justify-content: center;
		align-items: center;
	}
	.about-heading3{
    font-size: 12px;
  
}
#para-about {
		font-size: 10px;
	}

	.projectfilter{
		margin-bottom: 50%;
	}
			.png1 {
	display: none;
	}
	.png2 {
		display: none;
	}
		.iphone {

		margin-top: 30%;
		margin-left: 20%;
	}
	 }

</style>
