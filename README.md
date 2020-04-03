+<!docktype html>
<html>
<head>
	<title> Drop Down Menu	</title>
	<link rel="stylesheet" href="style.css">
	<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css">
</head>


<body> 

<div class="menu-bar">
<ul>
<li class="active"><a href="#"><i class="fa fa-home"></i> Home</a> 
</li>
<li><a href="#"><i class="fa fa-user"></i>About us</a></i>
	<div class="sub-menu-1">
		<ul>
			<li><a href="#">Mission</a> </li>
			<li><a href="#">Vision</a> </li>
			<li><a href="#">Team</a> </li>
		</ul>
		</div>
	</li>
	
	
	
<li><a href="#"><i class="fa fa-clone"></i>Services</a>
	<div class="sub-menu-1">
			<ul>
			<li><a href="#">Web Desigining</a></li>
			<li class="hover-me"><a href="#">Marketing</a><i class="fa fa-angle-right"></i>
				<div class="sub-menu-2">
							<ul>
								<li><a href="#">SEO</a> </li>
								<li><a href="#">Social Media</a> </li>
								<li><a href="#">Email Marketing</a> </li>
							</ul>
						</div>
					</li>
			
			<li class="hover-me"><a href="#">Mobile App</a><i class="fa fa-angle-right"></i>
				<div class="sub-menu-2">
						<ul>
							<li><a href="#">Android App</a> </li>
							<li><a href="#">IOS App</a> </li>
							<li><a href="#">Pc App</a> </li>
							<li><a href="#">FLutter App</a></li>
							<li><a href="#">Unity App</a></li>
						</ul>
					</div>
				</li>
				</div>




	
<li><a href="#"><i class="fa fa-user"></i>Clients</a></i>
			<div class="sub-menu-1">
			<ul>
				<li><a href="#">TATA</a> </li>
				<li><a href="#">Lamborgini</a> </li>
				<li><a href="#">Ashock Leyland</a> </li>
				<li><a href="#">Maruti Suzuki</a> </li>
				<li><a href="#">Hero</a> </li>
				<li><a href="#">Honda</a> </li>
				<li><a href="#">Reliance</a> </li>
			</ul>
		</div>
	</li>

		
	


<li><a href="#"><i class="fa fa-angellist"></i>Investers</a> </li>
<li><a href="#"><i class="fa fa-inr"></i>Pricing<a/> </li>
<li><a href="#"><i class="fa fa-edit"></i>Training</a> </li>
<li><a href="#"><i class="fa fa-phone"></i>Contact</a> </li>
</ul>
</div>

<main>
	<section>
		<h2>Well come to My Webpage</h2>
		<h1>DO COME & VISIT MY Webpage<span class= "change-content">    </span>
		</h1>
		<a href=" " class="btnone"> Learn More</a>
		<a href="login.html" class="btntwo"> Signup Here</a>
	</section>
</main>


 </body>
</html>



+*{padding:0;
	margin:0;
}

body{background-image:url(Taj2.jpg);
	background-size:cover;
	background-repeat:no-repeat;
	background-position:;
	box-sizing:border-box;
	font-family:sans-serif;
}

.menu-bar{background:green;
			text-align:center;
}
.menu-bar ul{display:inline-flex;
			list-style:none;
			color;#fff;
}

.menu-bar ul li{width:100px;
				margin:12px;
				padding:10px;
}

.menu-bar ul li a{text-decoration:none;
					color:#fff;
}

.active, .menu-bar ul li:hover{background:purple;
								border-radius:2px;
								
}

.menu-bar .fa{margin:8px;
}

.sub-menu-1{display:none;
}

.menu-bar ul li:hover .sub-menu-1{display:block;
									position:absolute;
									background:green;
									margin-top:15px;
									margin-left:-15px;
}


.menu-bar ul li:hover .sub-menu-1 ul{display:block;
										margin;9px;
}

.menu-bar ul li:hover .sub-menu-1 ul li{width:200px;
										padding:8px;
										border-bottom:1px dotted #fff;
										background:transparent;
										border-radius:0;
										text-align:left;
}


.menu-bar ul li:hover .sub-menu-1 ul li:last-child{border-bottom:none;
}

.menu-bar ul li:hover .sub-menu-1 ul li a:hover{ color:blue;
}

.fa-angle-right{float:right;
}

.sub-menu-2 {display:none;
}
			
.hover-me:hover .sub-menu-2{position:absolute;
							display:block;
							margin-top:-40px;
							margin-left:140px;
							background:green;
							
}						


.sub-menu-3{display:;
}


main{ width:100%; height:85vh;
		display:flex;
		justify-content: center;
		align-items:center;
		text-align:center;
		color:white;
		}

section h2{font-size:35px; font-weight:200; letter-spacing:3px; text-shadow:2px 2px 4px black;
}

section h1{margin:30px 0 20px 0;
			font-size:55px;
			font-weight:700;
			text-shadow: 2px 1px 5px black;
			text-transform:uppercase;
}

section  a{padding:12px 30px;
			border-radius: 4px;
			outline:none;
			text-transform:uppercase;
			font-size:13px;
			font-weight:500;
			text-decoration: none;
			letter-spacing:1px;
			transition:all 0.7s easily;
}


section .btnone{/*background:#00b894;*/
				background:#fff;
				color:#00b894;
}
		.btnone:hover{background: #00b894;
					color: white;
		}
section .btntwo{/*background:#00b894;*/
				background: #00b894;
				color:white;		
}
		.btntwo:hover{background: #fff;
				color: #000;
		}





