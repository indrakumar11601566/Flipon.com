# Flipon.com
This as an Ecommerce Website


    #wrapper
{
    font-family:tahoma;
   
}
.container
{
    width:100%;
    max-width:1280px;
    margin:0 auto;
}
#subheader
{
    width:100%;
    height:30px;
    background-color:rgb(221, 68, 68);
    color:azure;
    margin-top: -15px;
}
#subheader p
{
    float:left;
    margin-top: 7px;
}
#subheader a
{
    float:right;
    line-height:30px;
    color:aliceblue;
    margin-left:30px;
    text-decoration: none;
    margin-left:30px;
}
#main-header{
    width:100%;
    height:100px;
    background:rgb(244, 63, 63);
    float:left;
    margin-top:-15px;
    
}
#logo{
    width:250px;
    margin-top:10px;
    float:left;
    
}
#ist
{
    color:cornsilk;
    font-size:45px;
    font-weight:bold;
    margin-left:15px;
    font-family:cursive;
}
#iist
{
    color:cornsilk;
    font-size:35px;
    font-weight:bold;
    margin-right:30px;
    font-family:cursive;
}
#search
{
    width:650px;
    float:left;
    padding:20px;
    margin-left:10px;
}
.search-area
{
    width:650px;
    height:50px;
    background:#fff;
    border:none;
    border-radius: 10px;
    float:left;
    padding-left:15px;
    box-shadow: 2px 3px 8px black;
  
}

.search-btn
{
    width:100px;
    height:50px;
    border-radius:10px;
    border:none;
    color:#fff;
    background:brown;
    margin-right:-400px;
    cursor:pointer;
    
}
#user
{
    width:300px;
    float:right;
    margin-top:20px;
}

#user li
{
    float:left;
    width:140px;
    margin-left:-10px;
    text-align:center;
    list-style:none;
    font-size:25px;
   
}
#user li:hover{
    font-size:30px;
    transition:all .5s ease;
}
#user li a{
    color:white;
    text-decoration:none;
}
/*#navigation{
    width:100%;
    height:30px;
   background:rgb(244, 63, 63);
    float:left;
    box-shadow:10px 14px 50px grey;
    
}
nav{
    width:1280px;
    margin:0 auto;
}
nav a
{
    margin-left:35px;
    color:white;
    text-decoration:none;
    
}
nav a:hover
{
 
    color:darkmagenta;
    transition:all .7s ease;
    
}*/
#navigation{
    width:100%;
    height:30px;
   background:rgb(244, 63, 63);
    float:left;
    box-shadow:10px 14px 50px grey;

}

nav{
    width:100%;
    margin:0;     /* edge to edge */
    
    
}

nav ul
{
    
    background-color:rgb(244, 63, 63);
    overflow:hidden;
    margin:0;
    padding: 0;
}

 nav ul.top li {
    list-style: none;
    float:left;
    
}
nav ul.top li.top-right{
    float: right;
}

nav ul.top li a{
    text-decoration:none;
    display: block;
/* same as below font-size:16px;*/
    min-height: 16px;   /*shrink */
    text-align: center;
    padding: 14px;
    text-transform: uppercase;
    color:white;
       
}
a{
    transition: 0.5s;
}

nav ul.top li a:hover{

    background-color:#2d7979;
    color:white;
  transform: scale(1.0);
    transition: transform 1000ms ease-in-out;
    
/* transform: rotate(20deg);

  //  transform: rotateX(360deg);
   //  transform: rotatey(95deg);
    font-size: 18px;*/
    
}
ul.top li.dropicon
{
    display: none;  /* hide unicode from dekstop*/
}

.dropclick {
    position: relative;
    display: inline-block;
}

.dropdown-content {
    display: none;
    position: absolute;
    background-color: #f9f9f9;
    min-width: 160px;
    box-shadow: 0px 8px 16px 0px rgba(0,0,0,0.2);
    z-index: 1;
}

.dropdown-content a {
    color: black;
    padding: 12px 16px;
    text-decoration: none;
    display: block;
}

.dropdown-content a:hover {background-color: #f1f1f1}

.dropdown:hover .dropdown-content {
    display: block;
}

.dropdown:hover .dropbtn {
    background-color: #3e8e41;
}

@media screen and (max-width:680px){
    
  ul.top li:not(:nth-child(1))   {
        
        display:none;  
    }
    
  ul.top li.dropicon 
    {
        display:block;
        float:right;
     }
    
    ul.top.responsive li.dropicon{
        position:absolute;
        top:0;
        right:0;
        
    }
    
/*  still inherit all previou <a> properties ,lets change */

    ul.top .responsive{
        position:relative;
    } 
    ul.top.responsive li{
        display:inline;
        float:none;
    }
    ul.top.responsive li a{
        display:block; 
        text-align: left;
    }
    
    
    
}


/*slider*/
#slider img{
    
    width:100%;
    height:60%;
    
    
}
#slider {
    width:100%;
    max-width:100%;
    float:left;
    margin-top: 3px;
    position: relative;
}
#slider ul{
  list-style:none;
   margin-left: -40px;
    
    
    
}
/*category*/
#heading-block
{
    width:100%;
    height:auto;
    float:left;
    color:rgb(221, 68, 68);

    font-size:22px;
}
#heading-block h2
{
    
    line-height:35px;
    border-left:20px solid brown;
    padding-left:10px;
}
.catbox{
    width:235px;
    height:235px;
    float:left;
    overflow:hidden;
    position:relative;
    margin:0 15 30 ;
    
    
}
.catbox span{
    width:100%;
    height:35px;
    line-height: 35px;
    background:rgba(0,0,0,0.6);
    color:white;
    display:block;
    bottom:30px;
    position:absolute;
    z-index:999;
    text-align:center;
    
}
.catbox:hover span
{
    color:aqua;
}
.catbox img
{
    max-width: :100%;
    transition:all .5s ease;
}
.catbox:hover img
{
    transform:scale(1.3,1.3);
    transition:all .5s ease;
}
.dot {
  cursor: pointer;
  height: 15px;
  width: 15px;
  margin: 0 2px;
    margin-top:-300;
  background-color: #bbb;
  border-radius: 50%;
  display: inline-block;
   
  transition: background-color 0.6s ease;
   
}
.active, .dot:hover {
  background-color: #717171;
}
  /*products css*/
.prod-box
{
    width:235px;
    height:290px;
    overflow:hidden;
    float:left;
    margin:0 10 30 0;
    position:relative;
}
.prod-box>img{
    max-width:160%;
}
.prod-trans{
    background:rgba(0,0,0,0.6);
    width:100%;
    height:100%;
    top:0;
    left:0;
    bottom:0;
    right:0;
    position:absolute;
    opacity:0;
   transition: all .5s ease;
}
.prod-box:hover .prod-trans{
    opacity: 1;
    transition: all .5s ease;
}
.product-feature
{
    text-align: center;
    margin-top:-150px;
    transition: all .5s ease;
    
}
.product-feature p
{
    color:#00eb00;
    font-family:verdana;
}
.prod-box:hover .product-feature{
    margin-top:150px;
    transition: all .5s ease;
}
.product-feature input
{
    width:150px;
    height:35px;
    font-size:17px;
    
}
.offer
{
    width:420px;
    float:left;
  
    margin-right:10px;
}
.offer:last-child{
    margin-right:0px;
}
.offer img
{
    width:100%;
}

#footer
{
    width:100%;
    height:300px;
    background:#f5f5f5;
    float:left;
}
.footer_sub1
{
    width:25%;
    float:left;
}

.footer_sub2
{
    width:20%;
    float:left;
list-style:  none;
    
    
}

.footer_sub2 ul li
{
    list-style:none;
}
.footer_sub2 ul li a
{
   text-decoration:none;
    color: black;
}
.footer_sub2 ul li a:hover{
    color:#1aaa1a;
    text-decoration:underline;
}

.footer_sub3
{
    width:35%;
    float:left;
}
    
#input1
{
    width:350px;
    border:none;
    height:50px;
    padding:15px;
    float:left;
}
.sub1
{
    height:50px;
    border:none;
    background:orange;
    float:left;
}
.par
{
    color:#999;
    font-style:italic;
    font-size:14px;
    
}


/*social*/
.footer_sub2
{
    
    transform: translate(-3%);
    width:30%;
    text-align: center;
    
    
    }
.btn
{
    display: inline-block;
    width:50px;
    height:50px;
    background:#f1f1f1;
    margin:5x;
    border-radius:30%;
    box-shadow:0 5px 5px -5px #00000070;
    color: #3498DB;
    overflow: hidden;
    position: relative;
    
}
.btn i
{
    line-height:50px;
    font-size:13px;
    transition: 0.2s linear;
}
.btn:hover i
{
    transform: scale(1.3);
    color:#f1f1f1;
    
    
}
.btn::before{
    content:"";
    position:absolute;
    width:120%;
    height:120%;
    background:#3498DB;
    transform: rotate(50deg);
    left:-110%;
    top:30%;
    overflow: hidden;
}
.btn:hover::before{
    animation:aaa 0.7s 1;
    top:-10%;
    left:-10%;
    
}
@keyframes aaa{
    0%{
        left:-110%;
        top:90%;
    }
     
     50%{
        left:10%;
        top:-30%;
    }
     100%{
        left:-10%;
        top:-10%;
    }
}

@media screen and(max:1280px)
{
    #subheader p{
        margin-left:10px;
    }  
}
@media screen and(max:1224px)
{

    
}
@media screen and(max:768px)
{
    
}

@media screen and(max:480px)
{
    
}
