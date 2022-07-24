<template>
  	<div class="card">
		<div id="img">
			<img v-bind:src="testimonial.img" alt="" />
		</div>
		<div id="h1">
            <h2>
                {{testimonial.name}}
            </h2>
			<h4>{{ testimonial.title }}</h4>
			<p>{{testimonial.description}}</p>
		</div>
    </div>
</template>

<script>
export default {
     props:["testimonial"],
}
</script>

<style scoped>
@font-face {
    font-family: Atauri;
    src: url(../assets/fonts/Atures500PersonalUseOnly-GD6D.ttf);
}
	img {
		position: relative;
		height: 180px;
		width: 180px;
		border-radius: 50%;
	}
	#h1 {
		font-size: small;
		font-family: SpaceQuest2;
		text-shadow: 3px 3px black;
		letter-spacing: 3px;
	}
    #h1 h2{
    font-size: 20px;
    }
    #h1 h4{
        color:#67b3e4;
    }
    #h1 p{
        font-family: Atauri;
    }
	.card {
		margin-top: 2%;
		background: #191c29;
		width: 280px;
		height: auto;
		padding: 9px;
		border-radius: 6px;
		display: flex;
		flex-direction: row;
		flex-wrap: wrap;
		justify-content: center;
		align-items: center;
		text-align: center;
		font-size: 1.5em;
		color: white;
		box-shadow: 0 0px 25px 9px rgba(58, 39, 96, 0.6);
	}

	@media only screen and (max-width: 1020px) {
		img {
		position: relative;
		height: 180px;
		width: 180px;

	}
	.card{
		animation: none;
	}
	}

</style>