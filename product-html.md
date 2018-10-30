# Flipon.com
This as an Ecommerce Website
<!DOCTYPE html>
<html>
<head>
	<title>Flipon</title>
	<meta name="viewport" content="width=device-width, initial-scale=1.0">
	<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css">
	<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.3.1/jquery.min.js"></script>
	<script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js"></script>
	<link rel="stylesheet" type="text/css" href="css/project.css">
	<link rel="stylesheet" href="http://maxcdn.bootstrapcdn.com/font-awesome/4.2.0/css/font-awesome.min.css">
	<link href="http://fonts.googleapis.com/css?family=Cookie" rel="stylesheet" type="text/css">
<head>
<body>
	<!DOCTYPE html>
<html lang="en">
<body>
	<div class="main_page">
		<nav class="navbar navbar-default">
		  <div class="container-fluid">
			<div class="navbar-header">
			  <a class="navbar-brand" href="#">WebSiteName</a>
			</div>
			<ul class="nav navbar-nav">
			  <li class="active"><a href="#">Home</a></li>
			  <li><a href="#">Page 1</a></li>
			  <li><a href="#">Page 2</a></li>
			  <li><a href="#">Page 3</a></li>
			</ul>
		  </div>
		</nav>

		<div class="container">
			<img class="image_s" src="Image/1women1.jpg">
			<img class="image_s" src="Image/women2.jpg">
			<img class="image_s" src="Image/women3.jpg">
			<img class="image_s" src="Image/women4.jpg">
		</div>
		<div class="product_details">
			<div>
				<p id="nm1">Anouk</p>
				<p id="nm2">Women Off-White & Navy Printed A-Line Kurti</p>
				<hr>
				<p class="price_tag"><strong>Rs. 1019</strong></p>
				<span id="addi">Additional tax may apply; charged at checkout</span><br>
				<h4 id="size_sel">SELECT SIZE</h4>
				<span id="size_chart">size chart</span>
			</div>
			<div class="size_buttons">
				<button class="buttons_s"><p class="inside_button">XS</p></button>
				<button class="buttons_s"><p class="inside_button">S</p></button>
				<button class="buttons_s"><p class="inside_button">M</p></button>
				<button class="buttons_s"><p class="inside_button">L</p></button>
				<button class="buttons_s"><p class="inside_button">XL</p></button>
				<button class="buttons_s"><p class="inside_button">XXL</p></button>
			</div>
			<div class="best_offers">
				<h4 id="best_t">BEST OFFERS &nbsp;&nbsp;
				<img id="best_tag" src="Image/tag.svg">
				</h4>
			</div>
			<hr>
			<div>
				<h5 id="pd_det1">BEST PRICE:<span id="pd_det2">Rs 699</span></h5> 
			</div>
			<ul class="pd_det_ul">
				<li>Applicable on: Orders above Rs. 1499 (only on first purchase)</li>
				<li>Coupon code: <b>MYNTRANEWW500</b></li>
				<li>Coupon Discount: Rs. 500 off, excluding tax (check cart for final savings)</li><br>
				<p class="pd_det4"><b>Flat Rs 200 cashback on PhonePe</b><br>
				<span class="pd_det3">Become a Myntra Insider and get Flat Rs 200 cashback on your next PhonePe Order.</span>
				</p>
				<p class="pd_det4"><b>10% Cashback for new Airtel Money users</b><br>
					<span class="pd_det3">10% Cashback for first transaction via Airtel Bank. TCA</span>
				</p>
				<p class="pd_det4"><b>10% SuperCash on MobiKwik</b><br>
					<span class="pd_det3">10% SuperCash on MobiKwik wallet</span>
				</p>
			</ul><br>
			<div>
				<h4 style="font-family:Rockwell;">PRODUCT DETAILS</h4>
			</div>
			<hr>
			<p style="font-family:Rockwell;">Off-white and navy blue printed A-line kurta, has a round neck, sleeveless, straight hem, side slits</p>
			<p class="pd_det4"><b>Material  Care</b><br>
				<span class="pd_det3">100% Cotton<br>Machine-wash</span>
			</p>
			<p class="pd_det4"><b>Product Code:</b>
				<span class="pd_det3">2322790</span>
			</p>
		</div>
	</div>
	<!-- Footer-->
	<footer class="footer-distributed">
			<div class="footer-left">
				<img class="footer_img" src="Image/flipon.png" >
				<p class="footer-links">
					<a href="#">Home</a>
					·
					<a href="#">Sign-Up</a>
					·
					<a href="#">AboutUs</a>
					·
					<a href="#">ContactUs</a>
				</p>
				<p class="footer-company-name">Flipon &copy; 2018</p>
			</div>
			<div class="footer-center">
				<div>
					<i class="fa fa-map-marker"></i>
					<p><span>Lovely Professional University</span></p>
				</div>
				<div>
					<i class="fa fa-phone"></i>
					<p>+91 9532769498</p>
				</div>
				<div>
					<i class="fa fa-envelope"></i>
					<p><a href="project/home.html" target="_blank">support@Flipon.com</a></p>
				</div>
			</div>
			<div class="footer-right">
				<p class="footer-company-about">
					<span>About the WebSite</span>
					This Is Strictly For Education Purpose Only #B-TECH #ENGINEERS.
				</p>
				<div class="footer-icons">
					<a href="#"><i class="fa fa-facebook"></i></a>
					<a href="#"><i class="fa fa-twitter"></i></a>
					<a href="#"><i class="fa fa-linkedin"></i></a>
					<a href="#"><i class="fa fa-github"></i></a>
				</div>
			</div>
		</footer>
</body>
</html>

</body>
</html>
//css

.main_page{
	position:relative;
}
.container{
	float:left;
	width:55%;
}
.image_s{
	max-width:45%;
	margin-left:15px;
	margin-bottom:10px;
	border:1px solid black;
}
.image_s:hover{
	cursor:pointer;
}
.size_buttons{
	position:inline-block;
	margin-top:10px;
}
.inside_button{
	font-size:18px;
	text-decoration:none;
	color:brown;
}
.buttons_s{
	margin:5px;
	background-color:pink;
	border:none;
	border-radius:45%;
	text-align:center;
	padding:15px;
	transition: transform .3s;
}
.buttons_s:hover{
	 transform: scale(1.1);
}
.price_tag{
	font-size: 24px;
    font-weight: 500;
    line-height: 1;
    color: #282C3F;
	font-family:Bodoni MT Black;
}
#addi{
	color: #7E808C;
    font-size: 14px;
    display: block;
}
#size_sel{
	display: inline-block;
    margin: 0px;
    font-weight: 500;
}
#size_chart{
	margin-left:5px;
    background-color: rgba(0, 0, 0, 0);
    border:2px;
    text-align: right;
    color: #ff3e6c;
    font-size: 18px;
    font-weight: 500;
    text-transform: uppercase;
}
#nm1{
	text-align:left;
	font-size:30px;
	font-family:Rockwell;
}
#nm2{
	text-align:left;
	font-family:Copperplate Gothic Bold;
	font-size:25px;
}
.size_buttons{
	display:inline-block;
	position:relative;
}
#best_t{
	margin-top:20px;
	font-family:Impact;
	font-size:16px;
}
#best_tag{
	max-width: 25px;
	max-height: 25px;
}
.product_details{
	
}
#pd_det1{font-family:Rockwell;font-size:17px;}
#pd_det2{font-family:Gunplay;font-size:15px;color:#ff3333;}
.pd_det3{font-family:Rockwell;font-size:15px;}
.pd_det4{font-family:Rockwell;}
.pd_det_ul{
	font-family:Rockwell;
	font-size:16px;
}
.footer-distributed{
	background-color: rgb(250, 251, 252);
	box-sizing: border-box;
	width: 100%;
	text-align: left;
	font: bold 16px Rockwell;
	padding: 55px 50px;
	margin-top: 80px;
}
.footer-distributed .footer-left,
.footer-distributed .footer-center,
.footer-distributed .footer-right{
	display: inline-block;
	vertical-align: top;
}
.footer-distributed .footer-center{
	width: 35%;
}
.footer-distributed .footer-center i{
	background-color:  #33383b;
	color: #ffffff;
	font-size: 25px;
	width: 38px;
	height: 38px;
	border-radius: 50%;
	text-align: center;
	line-height: 42px;
	margin: 10px 15px;
	vertical-align: middle;
}
.footer-distributed .footer-center i.fa-envelope{
	font-size: 17px;
	line-height: 38px;
}
.footer-distributed .footer-center p{
	display: inline-block;
	color: #8f9296;
	vertical-align: middle;
	margin:0;
}
.footer-distributed .footer-center p span{
	display:block;
	font-weight: normal;
	font-size:14px;
	line-height:2;
}
.footer-distributed .footer-center p a{
	color:  #8f9296;
	text-decoration: none;;
}
.footer-distributed .footer-right{
	width: 20%;
}
.footer-distributed .footer-company-about{
	line-height: 20px;
	color:  #8f9296;
	font-size: 13px;
	font-weight: normal;
	margin: 0;
}
.footer-distributed .footer-company-about span{
	display: block;
	color:  #8f9296;
	font-size: 14px;
	font-weight: bold;
	margin-bottom: 20px;
}
.footer-distributed .footer-icons{
	margin-top: 25px;
}
.footer-distributed .footer-icons a{
	display: inline-block;
	width: 35px;
	height: 35px;
	cursor: pointer;
	background-color:  #33383b;
	border-radius: 2px;
	font-size: 20px;
	color: #ffffff;
	text-align: center;
	line-height: 35px;
	margin-right: 3px;
	margin-bottom: 5px;
}
.footer-distributed .footer-left{
	width: 40%;
}
.footer_img{
	
}
