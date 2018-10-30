# Flipon.com
This as an Ecommerce Website
<!DOCTYPE html>
<html>
	<head>
		<title>SignUp</title>
		<link href="css/signup.css" rel="stylesheet" type="text/css">
		<script src="jquery.js"></script>
		<script>
			function checkForm(){
			var Fname=document.forms["regno"]["fname"];
			var Lname=document.forms["regno"]["lname"];
			var Email=document.forms["regno"]["email"];
			var ph=document.forms["regno"]["num"];
			var password=document.forms["regno"]["Password"];
			if(Email.value.indexOf("@",0)<0)
			{
				alert("@ symbol missing");
				return false;
			}
			 if(ph.value == "")
			{
				alert("phone number field is blank");
				return false;
			}
			 if(password.value == "")
			{
				alert("please Enter Your Password");
				return false;
			}
			alert("form submitted");
			return true;
		}
	</script>
</head>
	<body >
		<div class="simple-form">
			<form class="registration" onsubmit="return checkForm()" action="home.html" method="post" name="regno" >
				<h2>Sign-Up Form</h2>
				<input type="text" name="fname" id="button" placeholder="Enter Your FirstName" required><br><br>        
				<input type="text" name="lname" id="button" placeholder="Enter Your LastName" required><br><br> 
				<input type="email" name="email" id="button" placeholder="Enter Your EmailId" required><br><br> 
				<input type="password" name="Password" id="button" placeholder="Enter Your Password" required><br><br>
				<select type="text" id="phone"><option>+91</option></select>		
				<input type="number" name="num" id="ph" placeholder="Enter Your PhoneNumber" required><br><br>		
				<input type="radio" name="gender" id="rd"><span id="but">Male</span><input type="radio" name="gender" id="rd"><span id="but">Female</span><br><br>
				<input type="submit" value="SignUp" id="butt">             
			</form>
		</div>
	</body>
</html>
//css

body{
	background-image:url(../img/american-casual-cheerful-1391380.jpg);
	background-repeat:no-repeat;
	background-size:100%;
}
h2{
	font-family:Rockwell;
	color:white;
	font-weight:500;
}
.simple-form{
	text-align:center;
	margin: 50px 450px;
}
.registration{
	width:100%;
	background-color:#051019;
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
#after{
	width:100%;
	background-color:#051019;
	opacity:0.8;
	padding:50px 0px;
	border-radius:5px;
	box-shadow:4px 6px 8px grey;
}
#but{
	color:white;
	font-size:19px;
}
