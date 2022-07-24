<template>
  <div id="skills">
<div id="blue"></div>
		<div id="pink"></div>
		<div id="blue2"></div>
		<div id="glass-object">
			<div id="head">
				<h2 class="heading">- what i learnt -</h2>
				<h1 class="heading-">CAPTAINS's Skill set</h1>
			</div>
            <div id="cards">
                <div class="cards"><i class="fa-brands fa-js"></i></div>
                <div class="cards"><i class="fa-brands fa-vuejs"></i></div>
                <div class="cards"><i class="fa-brands fa-bootstrap"></i></div>
                <div class="cards"><i class="fa-brands fa-html5"></i></div>
                <div class="cards"><i class="fa-brands fa-css3"></i></div>
                <div class="cards"><i class="fa-solid fa-database"></i></div>
            </div>
        </div>
  </div>
</template>

<script>
export default {

}
</script>

<style>
#skills{
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
		min-height: 100vh;
		display: flex;
		flex-direction: column;
		flex-wrap: wrap;
		/* gap: 20px; */
	}
    	.fa-vuejs {
		font-size: 80px;

	}
	.fa-bootstrap {
          font-size: 80px;
	}
	.fa-html5 {
		font-size: 80px;
	}
	.fa-database {
				font-size: 80px;

	}
	.fa-css3 {
				font-size: 80px;
    }
    .fa-js{

        font-size: 80px;
    }
    .cards{
        display: flex;
        flex-direction: row;
        flex-wrap: wrap;
        justify-content: center;
        align-items: center;
        background-color: #191c29;
        font-size: 30px;
        height: 300px;
        width: 300px;
       box-shadow: 0 0px 25px 9px rgba(58, 39, 96, 0.6)
    }
    #cards{
        margin-top: 2%;
        display: flex;
        flex-direction: row;
        flex-wrap: wrap;
        justify-content: center;
        align-items: center;
        gap: 40px;
    }
</style>