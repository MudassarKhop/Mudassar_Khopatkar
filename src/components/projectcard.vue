<template>
	<div class="card">
		<div id="img">
			<img v-bind:src="project.img" alt="" />
		</div>
		<div id="h1">
			<h4>{{ project.title }}</h4>
			<p>{{project.description}}</p>
		</div>
<div class="btn">

<a  v-bind:href="project.githhub" target="_blank"><i class="fa-brands fa-github"></i></a>
		
<a  v-bind:href="project.livelink" target="_blank"><i class="fa-solid fa-laptop"></i></a>

	
</div>
	</div>
</template>
<script>
	export default {
		props: ["project"],
	};
</script>
<style scoped>
	#img {
		position: relative;
		bottom: 12%;
	}
	img {
		position: relative;
		height: 240px;
		width: 280px;
		border-top-left-radius: 8%;
		border-top-right-radius: 8%;
	}
	#h1 {
		font-size: small;
		font-family: SpaceQuest2;
		text-shadow: 3px 3px black;
		letter-spacing: 3px;
	}
	.card {
		margin-top: 2%;
		background: #191c29;
		width: 280px;
		height: 350px;
		padding: 3px;
		border-radius: 6px;
		display: flex;
		flex-direction: row;
		flex-wrap: wrap;
		justify-content: center;
		align-items: center;
		text-align: center;
		font-size: 1.5em;
		color: white;
		border-top-left-radius: 15%;
		border-top-right-radius: 15%;
		border-bottom-left-radius: 8%;
		border-bottom-right-radius: 8%;
		animation: floating 5s ease-in-out infinite;
		box-shadow: 0 0px 25px 9px rgba(58, 39, 96, 0.6);
	}
	button {
		display: none;
		width: 80px;
		height: 30px;
		gap: 10px;
	}
	.btn{
		display: flex;
		flex-direction: row;
		flex-wrap: nowrap;
		justify-content: center;
		align-content: center;
margin-bottom: 10px;	
}
	.button:hover {
		box-shadow: none;
		filter: drop-shadow(4px 4px 4px grey);
		transition: box-shadow 0.5s ease-out;
		transition: filter 0.5s ease-in;
		color: black;
	}
	.card:hover button {
		background-color: transparent ;
		border: none;
		display: block;
		color: black;
		

	}
		.fa-laptop {
		font-size: 23px;
		display: inline-block;
		background: #212431;
		color: #fff;
		line-height: 1;
		padding: 8px 0;
		border-radius: 50%;
		text-align: center;
		width: 45px;
		transition: 0.3s;
		margin-top: 3px;
	}
		.fa-laptop:hover {
		background: white;
		color: #212431;
	}

	@keyframes floating {
		0% {
			transform: translateY(0);
		}
		50% {
			transform: translateY(-16px);
		}
		100% {
			transform: translateY(0);
		}
	}

	@media only screen and (max-width: 1020px) {
		img {
		position: relative;
		height: 240px;
		width: 280px;
		border-top-left-radius: 8%;
		border-top-right-radius: 8%;
	}
	.card{
		animation: none;
	}
	}

</style>
