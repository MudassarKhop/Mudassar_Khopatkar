<template>
	<section id="testimonials">
		<h2 class="heading">- what people say about me -</h2>
		<h1 class="heading-">CREWMATES</h1>
	</section>
</template>
<script>
	export default {
		data() {
			return {
				testimonials: [
					{
						id: "1",
						name:"CARLA LAWRENCE",
						img: "https://i.postimg.cc/Vk9zYRtg/Screenshot-2022-07-21-095105.jpg",
						title: "PEER",
						description: "Mudassar Khopatkar is a highly competent and  focused web developer. His friendly disposition draws his colleagues to him and he is impressionable to everyone he comes in contact with.",
						
					},
					{
						id: "2",
						name:"Zoe",
						img: "https://i.postimg.cc/Vk9zYRtg/Screenshot-2022-07-21-095105.jpg",
						title: "PEER",
						description: "Mudassar khopatkar is a dedicated person , he strives to reach his goals and will put twice the amount of work in to achieve everything . He is a extremely talented person with many skills .",
						
					},
					{
						id: "3",
						name:"Jesse Spencer",
						img: "https://i.postimg.cc/Vk9zYRtg/Screenshot-2022-07-21-095105.jpg",
						title: "PEER",
						description: "It is my great pleasure to have worked with Mudassar Khopatkar as he is a good team worker.He can collaborate and communicate with others on their ideas.",
						
					},
					{
						id: "4",
						name:"Tshimologo King",
						img: "https://i.postimg.cc/Vk9zYRtg/Screenshot-2022-07-21-095105.jpg",
						title: "PEER",
						description: "I am profoundly impressed with his intense focus and commitment. His enthusiasm towards his work is remarkable. I am convinced that he can make a more valuable contribution for future endeavours.",
						
					},
					{
						id: "5",
						name:"",
						img: "",
						title: "",
						description: "",
						
					},
					{
						id: "6",
						name:"",
						img: "",
						title: "",
						description: "",
						
					},
				],
			
			};
		},
		components: { Projectcard, Icons, Icons, Icons, Icons, Projectcard },
	};
</script>
<style scoped>
	#testimonials {
		height: 100vh;
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
