<template>
	<div id="icons">
		<a href="https://www.instagram.com/mudathierkop/" target="blank"
			><i class="fa-brands fa-instagram"></i
		></a>
		<a href="https://github.com/MudassarKhop" target="blank"
			><i class="fa-brands fa-github"></i
		></a>
		<a href="https://twitter.com/MudathierKop" target="blank" id="twitter"
			><i class="fa-brands fa-twitter"></i
		></a>
		<a
			href="https://www.linkedin.com/in/mudassar-khopatkar-a9854023a/"
			target="blank"
			><i class="fa-brands fa-linkedin"></i
		></a>
	</div>
</template>
<script>
	export default {
		props: ["icon"],
	};
</script>
<style>
	#icons {
		display: flex;
		flex-direction: row;
		flex-wrap: nowrap;
		justify-content: flex-end;
		align-items: flex-end;
		padding: 50px;
	}

	.fa-brands {
		padding-right: 10px;
	}
	.fa-location-dot {
		font-size: 28px;
		display: inline-block;
		background: #212431;
		color: #fff;
		line-height: 1;
		padding: 8px 0;
		margin-right: 4px;
		border-radius: 50%;
		text-align: center;
		width: 45px;
		transition: 0.3s;
	}
	.fa-phone {
		font-size: 28px;
		display: inline-block;
		background: #212431;
		color: #fff;
		line-height: 1;
		padding: 8px 0;
		margin-right: 4px;
		border-radius: 50%;
		text-align: center;
		width: 45px;
		transition: 0.3s;
	}
	.fa-fax {
		font-size: 28px;
		display: inline-block;
		background: #212431;
		color: #fff;
		line-height: 1;
		padding: 8px 0;
		margin-right: 4px;
		border-radius: 50%;
		text-align: center;
		width: 45px;
		transition: 0.3s;
	}
	.fa-instagram {
		font-size: 28px;
		display: inline-block;
		background: #212431;
		color: #fff;
		line-height: 1;
		padding: 8px 0;
		margin-right: 4px;
		border-radius: 50%;
		text-align: center;
		width: 45px;
		transition: 0.3s;
	}
	.fa-github {
		font-size: 28px;
		display: inline-block;
		background: #212431;
		color: #fff;
		line-height: 1;
		padding: 8px 0;
		margin-right: 4px;
		border-radius: 50%;
		text-align: center;
		width: 45px;
		transition: 0.3s;
	}
	.fa-twitter {
		font-size: 28px;
		display: inline-block;
		background: #212431;
		color: #fff;
		line-height: 1;
		padding: 8px 0;
		margin-right: 4px;
		border-radius: 50%;
		text-align: center;
		width: 45px;
		transition: 0.3s;
	}
	.fa-facebook-f {
		font-size: 28px;
		display: inline-block;
		background: #212431;
		color: #fff;
		line-height: 1;
		padding: 8px 0;
		margin-right: 4px;
		border-radius: 50%;
		text-align: center;
		width: 45px;
		transition: 0.3s;
	}
	.fa-at {
		font-size: 28px;
		display: inline-block;
		background: #212431;
		color: #fff;
		line-height: 1;
		padding: 8px 0;
		margin-right: 4px;
		border-radius: 50%;
		text-align: center;
		width: 45px;
		transition: 0.3s;
	}
	.fa-whatsapp {
		font-size: 28px;
		display: inline-block;
		background: #212431;
		color: #fff;
		line-height: 1;
		padding: 8px 0;
		margin-right: 4px;
		border-radius: 50%;
		text-align: center;
		width: 45px;
		transition: 0.3s;
	}
	.fa-codepen {
		font-size: 28px;
		display: inline-block;
		background: #212431;
		color: #fff;
		line-height: 1;
		padding: 8px 0;
		margin-right: 4px;
		border-radius: 50%;
		text-align: center;
		width: 45px;
		transition: 0.3s;
	}
	.fa-google {
		font-size: 28px;
		display: inline-block;
		background: #212431;
		color: #fff;
		line-height: 1;
		padding: 8px 0;
		margin-right: 4px;
		border-radius: 50%;
		text-align: center;
		width: 45px;
		transition: 0.3s;
	}
	.fa-linkedin {
		font-size: 28px;
		display: inline-block;
		background: #212431;
		color: #fff;
		line-height: 1;
		padding: 8px 0;
		margin-right: 4px;
		border-radius: 50%;
		text-align: center;
		width: 45px;
		transition: 0.3s;
	}
	.fa-instagram:hover {
		background: radial-gradient(
			circle at 33% 100%,
			#fed373 4%,
			#f15245 30%,
			#d92e7f 62%,
			#9b36b7 85%,
			#515ecf
		);
	}
	.fa-google:hover {
		background-color: red;
		color: white;
	}
	.fa-twitter:hover {
		background-color: #1da1f2;
	}
	.fa-codepen:hover {
		background-color: black;
	}
	.fa-linkedin:hover {
		background: white;
		color: #0077b5;
	}
	.fa-facebook-f:hover {
		background: #4867aa;
		color: #ffffff;
	}
	.fa-whatsapp:hover {
		background: #26d047;
		color: #ffffff;
	}
	.fa-github:hover {
		background: white;
		color: #212431;
	}

	.fa-github:hover {
		background-color: linear-gradient(
			#405de6 #5851db #833ab4 #c13584 #e1306c #fd1d1d
		);
	}
</style>
