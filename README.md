<!DOCTYPE html>
<html lang="en">
<head>
	<meta charset="utf-8">
	<title>Under_Water_Table</title>
	<link rel="stylesheet" type="text/css" href="https://necolas.github.io/normalize.css/8.0.1/normalize.css">
</head>
<style type="text/css">

	*, *:before, *:after {
		box-sizing: border-box;
	}
	body{
		font-family: sans-serif;
		margin: 0px;

	}


	.main{
		color: #F5FCFF;
		display: flex;
		flex-direction: column;
		justify-content: space-between;

		height: 100vh;
		align-items: center;
		min-height: 600px;
		background: url('https://psv4.userapi.com/c848028/u385906289/docs/d5/01a2e7dd6ca4/FlattvivMore.png?extra=-9-VCXoYSmqmUHZun-O_JyQZYA55jQgMYdfqLQ7zHy3TO2EHqpJ6Mp3-nU6F6Qlz-tUMC_v-tPllVMzuQkRucQxq8jOUsErkzar5WxGh2BxaCrfHD1VgmfrJ_s1LciDVIJgCx2pMGdJarbRO9RN3wkrHfQ') no-repeat center;
		background-size: cover;
		
		position: relative;
	}
	.main-overlay{
			align-items: center;
		position: absolute;
		left: 0px;
		top: 0px;
		width: 100%;
		height: 100%;
		opacity: .5;
		z-index: 0;
		

	}
	.headR{
		display: flex;
		height: 20vh;
		justify-content: space-between;
		 
		width: 90%;
		position: relative;
		z-index: 2;
	}

	.menu{
		width: 60%;
	}

	.menu ul{
		display: flex;
		justify-content: space-between;
		outline-style: none;
		list-style: none;

	}
	.menu-Link{
		font-weight:bold;
		color: #FFFFFF;
		text-decoration: none;
	}
	.Flat{
		filter: blur(1px);
		width: 150px;
	    opacity: .8;
	}
	.get-start{
		margin-left: 20px;
		border: 2px dashed #FFCCE8;
		border-radius: 20px;
		padding: 10px 20px;
		text-transform: uppercase;
	}

	.main-txt{
		position: relative;
		z-index: 2;
		text-align: center;
	}
	.main-txt span{
		display: inline-block;
	}

	.main-txt h1{
		margin: 0.5rem;
		font-size: 70px;
	}
	.main-txt span::after{
		content: '';
		width: 100px;
		height: 2px;
		background-color: white;
		display: inline-block;
		vertical-align: middle;
		margin-left: 20px;
	}
	.main-txt span::before{
		content: '';
		width: 100px;
		height: 2px;
		background-color: white;
		display: inline-block;
		vertical-align: middle;
		margin-right: 20px;
	}

	.arw-down{

		position: relative;
		z-index: 2;
		height: 20vh;
		display: flex;
		justify-content: center;
		align-items: center;
	}
	.down{
		opacity: .8;
		text-align: center;
		line-height: 50px;
		width: 50px;
		height: 50px;
		background-color: #94FFB8;
		border-radius: 50%;
		box-shadow: 0px  0px 18.69px 2.31px rgba(240, 243, 231, 0.9);
	}
  

  .BubleS{
position: absolute;
		margin: 0px;
		width: 100%;
		height: 100%;
		z-index: 0px;
		overflow: hidden;
        top: 0px;
        left: 0px; 

	}
	.bubl{
		position: absolute;
		bottom: 0px;
	    z-index: 0px;
		background-color: #E0FFFC;
		border-radius: 50%;
		opacity: 0.5;
		animation: flying 10s infinite ease-in;
	}
	.bubl:nth-child(1){
			width: 40px;
		height: 40px;
		left: 10%;
		animation-direction: 8s;

	}
	.bubl:nth-child(2){
		width: 20px;
		height: 20px;
		left: 20%;
		animation-direction: 5s;
		animation-delay: 1s;
	}
	.bubl:nth-child(3){
		width: 50px;
		height: 50px;
		left: 35%;
		animation-direction: 10s;
		animation-delay: 2s;
	}
	.bubl:nth-child(4){
		width: 80px;
		height: 80px;
		left: 50%;
		animation-direction: 7s;
		animation-delay: 0s;
	}
	.bubl:nth-child(5){
		width: 34px;
		height: 34px;
		left: 55%;
		animation-direction: 6s;
		animation-delay: 2s;
	}
	.bubl:nth-child(6){
		width: 45px;
		height: 45px;
		left: 65%;
		animation-direction: 8s;
		animation-delay: 4s;
	}
	.bubl:nth-child(7){
		width: 25px;
		height: 25px;
		left: 75%;
		animation-direction: 7s;
		animation-delay: 2s;
	}
	.bubl:nth-child(8){
		width: 80px;
		height: 80px;
		left: 80%;
		animation-direction: 6s;
		animation-delay: 1s;
	}
	.bubl:nth-child(9){
		width: 15px;
		height: 15px;
		left: 70%;
		animation-direction: 9s;
		animation-delay: 0s;
	}
	.bubl:nth-child(10){
		width: 50px;
		height: 50px;
		left: 85%;
		animation-direction: 5s;
		animation-delay: 3s;
	}
	@keyframes flying{
		0%{
			bottom: -100px;
			transform: translateX(0px);
		}
		50%{
			transform: translateX(100px);
		}
		100%{
			bottom: 1000px;
			transform: translateX(200px);
		}
	}


</style>
<body>

	<div class="main">
		<div class="main-overlay"></div>
		<div class="headR">
			<div class="Logo">
				<img class="Flat" src="https://psv4.userapi.com/c848024/u385906289/docs/d15/3bc92ad239d8/FLati.png?extra=tzzvtl7a8jQ-GGI5PQFuGijZeyH7AjB2TBihGJMsakbGLdDDp8RzpNMGkt2Nvqg1VLqv_YHS3_Tliolc__zJCUX7iSYRlT8e7hxKPIk2NMtDC1QYxahn30oyHcoBWAHM9FqhE02_o7pYNDCTVfRQr8-LWA" alt="Logo">
			</div>
			<div class="menu">
				<ul>
					
					<li> <a href="#" class="menu-Link">◦ Home_Page   ◦  </a></li>
					<li> <a href="#" class="menu-Link">◦ SociaL   ◦  </a></li>
					<li> <a href="#" class="menu-Link">◦ CharacteristiC   ◦  </a></li>
					<li> <a href="#" class="menu-Link">◦ NotE    ◦  </a></li>
					<li> <a href="#" class="menu-Link">◦  PrinteR    ◦  </a></li>
					<li> <a href="#" class="get-start menu-Link"> Go_to_Start   </a></li>
				</ul>
			</div>
		</div>
		<div class="main-txt">
			
			<span>◌ social and analys ◌ </span>
			<h1>Fluttershy_Under_Water</h1>
			<p>● ● ●</p>
		</div>
		<a  class="main-arw">
			<div class="arw-down">
				<h1 class="down">▼</h1>
			</div>
		</a>
	</div>

	  <div class="BubleS">
  	 <div class="bubl"></div>
  	 <div class="bubl"></div>
  	 <div class="bubl"></div>
  	 <div class="bubl" ></div>
  	 <div class="bubl"></div>
  	 <div class="bubl"></div>
  	 <div class="bubl"></div>
  	 <div class="bubl"></div>
  	 <div class="bubl"></div>
  	 <div class="bubl"></div>
  </div>

</body>
</html>
