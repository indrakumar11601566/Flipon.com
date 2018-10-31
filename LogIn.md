<!DOCTYPE html>
<html>
	<head>
		<title>SignUp</title>
		<meta name="viewport" content="width=device-width, initial-scale=1">
		<link rel="stylesheet" href="css/login.css" type="text/css"></link>
		<script src="js/login.js"></script>
</head>
	<body>	
				<div class="simple-form">
					<form class="registration" method="post" name="regno" >
						<h2 id="h21">Sign-In</h2>
						<input type="text" id="username" class="button" placeholder="Enter Your UserName" required><br><br>         
						<input type="password" id="password" class="button" placeholder="Enter Your Password" required><br><br>
						<input type="button" value="Login" id="butt" onclick="validate()"/>             
					</form>
				</div>
	</body>
</html>

///JS

<script>
body{
	background-image:url(../Image/american-casual-cheerful-1391380.jpg);
	background-repeat:no-repeat;
	background-size:100%;
}
#h21{
	font-family:Rockwell;
	color:white;
	font-weight:500;
}
.simple-form{
	text-align:center;
	margin: 40px 450px;
	padding: 20px 20px;
}
.registration{
	width:100%;
	//background-color:#051019;
	background:rgba(0,0,0,.8);
	opacity:0.8;
	padding:50px 0px;
	border-radius:5px;
	box-shadow:4px 6px 8px grey;
}
#button{
	width:250px;
	padding:10px;
	border-radius:5px;
	outline:0px;
}
#ph{
	width:180px;
	padding:10px;
	border-radius:5px;
	outline:0px;
}
#butt{
	width:250px;
	padding:10px;
	border-radius:5px;
	outline:0px;
	background-color:#0c6996;
	border:2px solid #01010c;
	color:aliceblue;
	font-size:19px;
}
#phone{
	width:65px;
	padding:10px;
	border-radius:5px;
	outline:0px;
}
#but{
	color:white;
	font-size:19px;
}
</script>
