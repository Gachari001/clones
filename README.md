# clones
simple clone i didn on my lost Nokia lumia phone
<?php
 
include 'connect.php';
?>
<!DOCTYPE html>
<html>
<head>
<link href="css/w3v3.css" rel="stylesheet"/>
<meta name="viewport" content="width=device-width,initial-scale=1.0">
<style>
body{
background-color:#f9f8f8;
font-family:font-awesome;

font-size:10px;
}
.outterWrapper{
border-radius:30px;
background: #080808; /* For browsers that do not support gradients */
  background: -webkit-linear-gradient(left, #080808 , 	#181818,  #080808); /* For Safari 5.1 to 6.0 */
  background: -o-linear-gradient(right, #080808, 	#181818,  #080808); /* For Opera 11.1 to 12.0 */
  background: -moz-linear-gradient(right, #080808, 	#181818,  #080808); /* For Firefox 3.6 to 15 */
  background: linear-gradient(to right,  #080808 ,	#181818,  #080808); /* Standard syntax */

}
.innerWrapper{
position:relative;
width:inherit;



margin:5px auto;
margin-right:9.5px;
}
#innerWrapper{
	
	background-image:url('bg/Windows_Phone_8_StartScreen.png');
	background-size:310px 480px;
	background-repeat:no-repeat;
		background-position:7.3px 7px;
    border-radius-top-right: 10%;
    border-radius-top-left: 10%;
  border-top: 2px solid;
}
h3{
position:relative;
padding-top:-20px;
color:#F0F0F0;
text-transform:uppercase;
font-family:calibri;

}
.buttons{
position:relative;
top:.1%;
left:2.8%;

}
.apps{
position:absolute;
top:90%;
left:43%;

}
h3:after{
 display:block;
  position:absolute;
  border:1px solid #404040;
  top:18px;
  right:85%;
  width:20px;
  height:20px;
  content:'';
  
  background:transparent;
  -webkit-border-radius:8px;
  -moz-border-radius:8px;
  border-radius:8px;
}
h3:before{
 display:block;
  position:absolute;
  top:23px;
  z-index:1;
  right:86.5%;
  width:10px;
  height:10px;
  content:'';
  
  background:purple;
  -webkit-border-radius:5px;
  -moz-border-radius:5px;
  border-radius:5px;
}
.speaker:before{
 display:block;
  position:absolute;
  top:23px;
  z-index:1;
  right:41.5%;
  width:55px;
  height:10px;
  content:'';
  
  background:blue;
  -webkit-border-radius:3px;
  -moz-border-radius:3px;
  border-radius:3px;
}


#loader {
  position: absolute;
  left: 50%;
  top: 50%;
  z-index: 1;
  width: 150px;
  height: 150px;
  margin: -75px 0 0 -75px;
  border: 16px solid #f3f3f3;
  border-radius: 50%;
  border-top: 16px solid #3498db;
  width: 120px;
  height: 120px;
  -webkit-animation: spin 2s linear infinite;
  animation: spin 2s linear infinite;
}

@-webkit-keyframes spin {
  0% { -webkit-transform: rotate(0deg); }
  100% { -webkit-transform: rotate(360deg); }
}

@keyframes spin {
  0% { transform: rotate(0deg); }
  100% { transform: rotate(360deg); }
}

/* Add animation to "page content" */
.animate-bottom {
  position: relative;
  -webkit-animation-name: animatebottom;
  -webkit-animation-duration: 1s;
  animation-name: animatebottom;
  animation-duration: 1s
}

@-webkit-keyframes animatebottom {
  from { bottom:-100px; opacity:0 } 
  to { bottom:0px; opacity:1 }
}

@keyframes animatebottom { 
  from{ bottom:-100px; opacity:0 } 
  to{ bottom:0; opacity:1 }
}

#myDiv {
  display: none;
  text-align: center;
}


.light:before{
 display:block;
  position:absolute;
  top:40px;
  z-index:1;
  right:40.5%;
  width:6px;
  height:6px;
  content:'';
  
   background-color: purple;
    -webkit-animation-name: example; /* Chrome, Safari, Opera */
    -webkit-animation-duration: 4s; /* Chrome, Safari, Opera */
    animation-name: lights;
    animation-duration: 4s;
	 animation-iteration-count: infinite;
  -webkit-border-radius:3px;
  -moz-border-radius:5px;
  border-radius:5px;
}
/* Chrome, Safari, Opera */
@-webkit-keyframes lights {
    0%   {background-color: purple;}
    25%  {background-color: #00e04b;}
    50%  {background-color: purple;}
    100% {background-color: #00e04b;}
}

/* Standard syntax */
@keyframes lights {
    0%   {background-color: purple;}
    25%  {background-color: #00e04b;}
    50%  {background-color: purple;}
    100% {background-color: #00e04b;}
}
/* Chrome, Safari, Opera */
@-webkit-keyframes lights {
    0%   {background-color: purple;}
    25%  {background-color: #00e04b;}
    50%  {background-color: purple;}
    100% {background-color: #00e04b;}
}

/* Standard syntax */
@keyframes lights {
    0%   {background-color: purple;}
    25%  {background-color: #00e04b;}
    50%  {background-color: purple;}
    100% {background-color: #00e04b;}
}
.light2:before{
 display:block;
  position:absolute;
  top:40px;
  z-index:1;
  right:41.5%;
  width:6px;
  height:6px;
  content:'';
  
   background-color: purple;
    -webkit-animation-name: example; /* Chrome, Safari, Opera */
    -webkit-animation-duration: 4s; /* Chrome, Safari, Opera */
    animation-name: lights2;
    animation-duration: 4s;
	 animation-iteration-count: infinite;
  -webkit-border-radius:3px;
  -moz-border-radius:5px;
  border-radius:5px;
}

.light3:before{
 display:block;
  position:absolute;
  top:40px;
  z-index:1;
  right:41.5%;
  width:6px;
  height:6px;
  content:'';
  
   background-color: orange;
    -webkit-animation-name: example; /* Chrome, Safari, Opera */
    -webkit-animation-duration: 4s; /* Chrome, Safari, Opera */
    animation-name: lights2;
    animation-duration: 4s;
   animation-iteration-count: infinite;
  -webkit-border-radius:3px;
  -moz-border-radius:5px;
  border-radius:5px;
}
/* Chrome, Safari, Opera */
@-webkit-keyframes lights3 {
    0%   {background-color: orange;}
    25%  {background-color: #1b81ff;}
    50%  {background-color: orange;}
    100% {background-color: #1b81ff;}
}

/* Standard syntax */
@keyframes lights3 {
    0%   {background-color: orange;}
    25%  {background-color: #1b81ff;}
    50%  {background-color: orange;}
    100% {background-color: #1b81ff;}
}
.mySlides {
display:none;}
.btns li{
margin-top:-15px;
list-style-type:none;
float:left;
margin-left:-10px;

}
#p{
  color: #d98cb3;
}
label{
	color:#085a9d;
}
input[type="text"]{
	color:purple;
	font-weight:bold;
	font-size:14px;
	padding-left:40px;
	border-radius:3px;

}
.inputField:hover{box-shadow: 0 1px 3px #50c878, 0 1px 2px #29ff77; background-color:white;}

input[type="submit"]{
	font-size:14px;
	font-weight:bold;
	cursor:pointer;
}
.taskbtn{
	cursor:pointer;
}
.taskbtn:hover{
	color:purple;
	
}
</style>
<script>  
window.onload=function(){getTime();}  
function getTime(){  
var today=new Date();  
var h=today.getHours();  
var m=today.getMinutes();  
var s=today.getSeconds();  
// add a zero in front of numbers<10  
m=checkTime(m);  
s=checkTime(s);  
document.getElementById('txt').innerHTML=h+":"+m+":"+s;  
setTimeout(function(){getTime()},1000);  
}  
setInterval("getTime()",1000);//another way  
function checkTime(i){  
if (i<10){  
  i="0" + i;  
 }  
return i;  
}  
</script>
</head>
<body>

<div  class="w3-content w3-margin-top" style="max-width:315px;">
<div class="outterWrapper" style="height:640px;">
<header>
<span class="light"></span>
<span class="light2"></span>
<span class="light3"></span>
<h3 class="w3-center" style="margin-bottom:-20px;font-family:blandly;"><span class="speaker"><br></span>Noikia</h3>
</header>
<div class="innerWrapper w3-section w3-opacity:.5" id="innerWrapper" style="max-width:310px; height:495px;">


<div class="w3-container" >
<div class="w3-round-medium  w3-light-grey" style="margin-top:20px; opacity:.5;  margin-left:7px;">
<h4 class="w3-center" style="font-family:calibri; "><span style="font-weight:bold; color:#085a9d;"><u>Today</u></span><br>
<h4 style="text-align:center; color:blue;font-size:12px; font-family:font-awesome;">Current Time:<br/> <span  id="txt" style="text-color:purple;" document.getElementById('txt').innerHTML=h+":"+m+":"+s;</a> </span></h4>
</div>


<div class="w3-third">
<button class="w3-btn" onclick="document.getElementById('music').style.display='block'" style="background:transparent;">
<center>
<img src="gallery/music.png" height="57px" style="width:100%;"/><br>
<span style="color:white; font-family:fontawesome; font-weight:bold; font-size:12px;">Music</span>
</center>
</button>

<div class="w3-third">
<button class="w3-btn" onclick="document.getElementById('icon').style.display='block'" style="background:transparent;">
<center>
<img src="icons/social_networks-128.png" height="57px" style="width:100%;"/><br>
<span style="color:white; font-family:fontawesome; font-weight:bold; font-size:12px;">Icons</span>
</center>
</button>



<button class="w3-btn" onclick="document.getElementById('account').style.display='block'" style="background:transparent;">
<center>
<img src="gallery/account.png" height="57px" style="width:100%;"/><br>
<span style="color:white; font-family:fontawesome; font-weight:bold; font-size:12px;">Account</span>
</center>
</button>






<div class="w3-modal " id="account" style="margin-top:-6px;">
<div class="w3-modal-content w3-light-gray w3-animate-zoom" style="width:303.7px; height:476.7px;  overflow:scroll;">
<button class="w3-btn w3-light-blue w3-hover-orange w3-large" onclick="document.getElementById('account').style.display='none'" style="width:100%;">Go back</button>
<br>
<div class="w3-container w3-card-2 w3-round-medium w3-white w3-large">
<br>
<br>

<center>
<span class="w3-light-blue" style="font-family:britannic bold;font-weight:bold;color:#59677a; ">Today</span>
<br>
</center>
</div>
<br>
<br>
<div class="w3-center">
<form id="form_id" method="post" action="account.php" name="myForm">
<p><label>Username</label><br>
<input class="w3-input w3-round-medium" type="text" name="username" id="username"></p>
<p><label>Password</label><br>
<input class="w3-input w3-round-medium" type="password" name="password" id="password"></p>
<p class="w3-center">
<input class="w3-btn w3-light-blue w3-round-medium" value="login" id="submit" onclick="validate()"></p>
</form>
</div>


<script>
var attempt=3;
function validate(){
var username=document.getElementById("username").value;
var password=document.getElementById("password").value;
if (username=="empire"&&password=="password"){
alert("login successfully");
document.getElementById("success").style.display="block";
return false;
}else{
attempt--;
alert("you have "+attempt+" attempts left");
document.getElementById("success").style.display="none";
if(attempt==0){
document.getElementById("username").disabled=true;
document.getElementById("password").disabled=true;
document.getElementById("submit").disabled=true;
return false;
}
}
}
</script>
</div>
</div>
</div>



<div class="w3-modal" id="music" style="margin-top:-6px;">
<div class="w3-modal-content w3-animate-zoom w3-light-gray" style="width:303.7px; height:476.7px;  overflow:scroll;">
<button class="w3-btn w3-light-blue w3-hover-orange w3-large" onclick="document.getElementById('music').style.display='none'" style="width:100%;">Go back
 </button>

<label style="font-size:14px; font-weight:bold;">Can't Help Falling In Love - Julio Iglesias</label>
<audio controls style="width:290px;">
  <source src="songs/018 Can't Help Falling In Love - Julio Iglesias.ogg" type="audio/ogg">
  <source src="songs/018 Can't Help Falling In Love - Julio Iglesias.mp3" type="audio/mpeg">
Your browser suppord the audios
</audio><br>
<label style="font-size:14px; font-weight:bold;">Missing You Now - Michael Bolton</label>
<audio controls style="width:290px;">
  <source src="songs/021 Missing You Now - Michael Bolton.ogg" type="audio/ogg">
  <source src="songs/021 Missing You Now - Michael Bolton2.mp3" type="audio/mpeg">
Your browser suppord the audios
</audio><br>

<label style="font-size:14px; font-weight:bold;">Maraiah Carey-Anytime you need a friend</label>
<audio controls style="width:290px;">
  <source src="songs/105. Maraiah Carey-Anytime you need a friend.ogg" type="audio/ogg">
  <source src="songs/105. Maraiah Carey-Anytime you need a friend.mp3" type="audio/mpeg">
Your browser suppord the audios
</audio><br>

<label style="font-size:14px; font-weight:bold;">Irreplacable - Beyonce</label>
<audio controls style="width:290px;">
  <source src="songs/076 Irreplacable - Beyonce.ogg" type="audio/ogg">
  <source src="songs/076 Irreplacable - Beyonce.mp3" type="audio/mpeg">
Your browser suppord the audios
</audio><br>

<label style="font-size:14px; font-weight:bold;">Eamon How could You bring</label>
<audio controls style="width:290px;">
  <source src="songs/eamon.ogg" type="audio/ogg">
  <source src="songs/eamon.mp3" type="audio/mpeg">
Your browser suppord the audios
</audio><br>

<label style="font-size:14px; font-weight:bold;">Eminem ft sia(beatiful pain)</label>
<audio controls style="width:290px;">
  <source src="songs/eminem.ogg" type="audio/ogg">
  <source src="songs/eminem.m4a" type="audio/mpeg">
Your browser suppord the audios
</audio><br>

<label style="font-size:14px; font-weight:bold;">Katy Perry Unconditional</label>
<audio controls style="width:290px;">
  <source src="songs/katty.ogg" type="audio/ogg">
  <source src="songs/katty.mp3" type="audio/mpeg">
Your browser suppord the audios
</audio><br>

<label style="font-size:14px; font-weight:bold;">Kelly Rowland - Dilemma Rowland - Dilemma</label>
<audio controls style="width:290px;">
  <source src="songs/Kelly Rowland - Dilemma.ogg" type="audio/ogg">
  <source src="songs/Kelly Rowland - Dilemma.mp3" type="audio/mpeg">
Your browser suppord the audios
</audio><br>

<label style="font-size:14px; font-weight:bold;">Phill Collins - One more night</label>
<audio controls style="width:290px;">
  <source src="songs/129. Phill Collins - One more night.ogg" type="audio/ogg">
  <source src="songs/129. Phill Collins - One more night.mp3" type="audio/mpeg">
Your browser suppord the audios
</audio><br>

<label style="font-size:14px; font-weight:bold;">A thousand mile</label>
<audio controls style="width:290px;">
  <source src="songs/a thousand mile.ogg" type="audio/ogg">
  <source src="songs/a thousand mile.mp3" type="audio/mpeg">
Your browser suppord the audios
</audio><br>

<label style="font-size:14px; font-weight:bold;">battlefield</label>
<audio controls style="width:290px;">
  <source src="songs/battlefield.ogg" type="audio/ogg">
  <source src="songs/battlefield.mp3" type="audio/mpeg">
Your browser suppord the audios
</audio><br>

<label style="font-size:14px; font-weight:bold;">Luther Vondrous-I'd Radher</label>
<audio controls style="width:290px;">
  <source src="songs/104. Luther Vondrous-I'd Radher.ogg" type="audio/ogg">
  <source src="songs/104. Luther Vondrous-I'd Radher.mp3" type="audio/mpeg">
Your browser suppord the audios
</audio><br>

<label style="font-size:14px; font-weight:bold;">Michael Learns to rock-Paint ma love</label>
<audio controls style="width:290px;">
  <source src="songs/Michael Learns to rock-Paint ma love.ogg" type="audio/ogg">
  <source src="songs/Michael Learns to rock-Paint ma love.mp3" type="audio/mpeg">
Your browser suppord the audios
</audio><br>

<label style="font-size:14px; font-weight:bold;">Titanic Theme - Celine Dion</label>
<audio controls style="width:290px;">
  <source src="songs/081 Titanic Theme - Celine Dion.ogg" type="audio/ogg">
  <source src="songs/081 Titanic Theme - Celine Dion.mp3" type="audio/mpeg">
Your browser suppord the audios
</audio><br>

<label style="font-size:14px; font-weight:bold;">Usher_Moving_Mountains</label>
<audio controls style="width:290px;">
  <source src="songs/Usher_Moving_Mountains.ogg" type="audio/ogg">
  <source src="songs/Usher_Moving_Mountains.mp3" type="audio/mpeg">
Your browser suppord the audios
</audio><br>

<label style="font-size:14px; font-weight:bold;">Am alive</label>
<audio controls style="width:290px;">
  <source src="songs/Am alive.ogg" type="audio/ogg">
  <source src="songs/Am alive.mp3" type="audio/mpeg">
Your browser suppord the audios
</audio><br>
</div>
</div>
</div>

<div class="w3-third">
<button class="w3-btn" onclick="document.getElementById('videoModal').style.display='block'" style="background:transparent;">
<center>
<img src="gallery/vdio.jpg" height="57px" style="width:100%;"/><br>
<span style="color:white; font-family:fontawesome; font-weight:bold; font-size:12px;">Videos</span>
</center>
</button>


<div class="w3-third">
<button class="w3-btn" style="background:transparent;">
<center>
<img src="icons/1 Q7Bip063EKCyQJ1mgS8z-Q.png" height="57px" style="width:100%;"/><br>
<span style="color:white; font-family:fontawesome; font-weight:bold; font-size:12px;">Instagram</span>
</center>
</button>

<button class="w3-btn" onclick="document.getElementById('quotes').style.display='block'" style="background:transparent;">
<center>
<img src="gallery/quotes.jpg" height="57px" style="width:100%;"/><br>
<span style="color:white; font-family:fontawesome; font-weight:bold; font-size:12px;">Quotes</span>
</center>
</button>

</div>


<div class="w3-modal" id="videoModal" style="margin-top:-6px;">
<div class="w3-modal-content w3-animate-zoom w3-light-gray" style="width:303.7px; height:476.7px; overflow:scroll;">
<button class="w3-btn w3-light-blue w3-hover-orange w3-large" style="width:100%;" onclick="document.getElementById('videoModal').style.display='none'">Go Back
</span></button>

<label style="font-size:14px; font-weight:bold;">Vanessa-Mdee-Never-Ever</label>
<video width="287.3" height="200" controls>
  <source src="videos/Vanessa-Mdee-Never-Ever_(www.Naijaextra.com).mp4" type="video/mp4">
  <source src="videos/Vanessa-Mdee-Never-Ever_(www.Naijaextra.com).ogg" type="video/ogg">
</video><br>

<label style="font-size:14px; font-weight:bold;">Beyonce - Runnin (Lose it All)</label>
<video width="287.3" height="200" controls>
  <source src="videos/Beyonce - Runnin (Lose it All).mp4" type="video/mp4">
  <source src="videos/Beyonce - Runnin (Lose it All).ogg" type="video/ogg">
</video><br>

<label style="font-size:14px; font-weight:bold;">A Whole New World - Alex G </label>
<video width="287.3" height="200" controls>
  <source src="videos/A Whole New World - Alex G (Cover from Disney's 'Aladdin').mp4" type="video/mp4">
  <source src="videos/A Whole New World - Alex G (Cover from Disney's 'Aladdin').ogg" type="video/ogg">

</video><br>
 <label style="font-size:14px; font-weight:bold;">Beauty And A Beat - Justin Bieber </label>
<video width="287.3" height="200" controls>
  <source src="videos/Beauty And A Beat - Justin Bieber (Alex Goot, Kurt Schneider, and Chrissy Costanza Cover).mp4" type="video/mp4">
  <source src="videos/Beauty And A Beat - Justin Bieber (Alex Goot, Kurt Schneider, and Chrissy Costanza Cover).ogg" type="video/ogg">

</video><br>
<label style="font-size:14px; font-weight:bold;">Flashlights</label>
<video width="287.3" height="200" controls>
  <source src="videos/Flashlight - Bethany Mota - Pitch Perfect 2 _ Jessie J Cover.mp4" type="video/mp4">
  <source src="videos/Flashlight - Bethany Mota - Pitch Perfect 2 _ Jessie J Cover.ogg" type="video/ogg">

</video><br>
<label style="font-size:14px; font-weight:bold;">Give Your Heart A Break - Demi Lovato - Official Cover Video</label>
<video width="287.3" height="200" controls>
  <source src="videos/Give Your Heart A Break - Demi Lovato - Official Cover Video (Alex Goot & Alex G).mp4" type="video/mp4">
  <source src="videos/Give Your Heart A Break - Demi Lovato - Official Cover Video (Alex Goot & Alex G).ogg" type="video/ogg">
</video><br>

<label style="font-size:14px; font-weight:bold;">Nasty ft Runtown-They Said</label>
<video width="287.3" height="200" controls>
  <source src="videos/Nasty ft Runtown-They Said.mp4" type="video/mp4">
  <source src="videos/Nasty ft Runtown-They Said.ogg" type="video/ogg">
</video><br>

<label style="font-size:14px; font-weight:bold;">Flavour_Virtuous_Woman</label>
<video width="287.3" height="200" controls>
  <source src="videos/Flavour_-__Virtuous_Woman_[Official_Video].mp4" type="video/mp4">
  <source src="videos/Flavour_-__Virtuous_Woman_[Official_Video].ogg" type="video/ogg">
    </video><br>

<label style="font-size:14px; font-weight:bold;">Flavour_-__Virtuous_Woman_[Official_Video]</label>
<video width="287.3" height="200" controls>
  <source src="videos/Flavour_-__Virtuous_Woman_[Official_Video].mp4" type="video/mp4">
  <source src="videos/Flavour_-__Virtuous_Woman_[Official_Video].ogg" type="video/ogg">
</video><br>



<label style="font-size:14px; font-weight:bold;">'Let It Go' by James Bay - Christina Grimmie</label>
<video width="287.3" height="200" controls>
  <source src="videos/'Let It Go' by James Bay - Christina Grimmie   Before You Exit Cover.mp4" type="video/mp4">
  <source src="videos/'Let It Go' by James Bay - Christina Grimmie   Before You Exit Cover.ogg" type="video/ogg">
</video><br>

<label style="font-size:14px; font-weight:bold;">Friends Spoken Word</label>
<video width="287.3" height="200" controls>
  <source src="videos/Friends Spoken Word.mp4" type="video/mp4">
  <source src="videos/Friends Spoken Word.ogg" type="video/ogg">
</video><br>
</div>
</div>
</div>

<div class="w3-third">
<button class="w3-btn" onclick="document.getElementById('gallery').style.display='block'" style="background:transparent;">
<center>
<img src="gallery/Preview_2x.png" height="57px" style="width:100%;"/><br>
<span style="color:white; font-family:bradley hand itc; font-weight:bold; font-size:12px;">Gallery</span>
</center>
</button>


<div class="w3-third">
<button class="w3-btn"style="background:transparent;">
<center>
<img src="icons/twitter-128-1.png" height="57px" style="width:100%;"/><br>
<span style="color:white; font-family:fontawesome; font-weight:bold; font-size:12px;">Twitter</span>
</center>
</button>

</div>

<button class="w3-btn"style="background:transparent;">
<center>
<img src="icons/square-linkedin-128.png" height="57px" style="width:100%;"/><br>
<span style="color:white; font-family:fontawesome; font-weight:bold; font-size:12px;">Linkedin</span>
</center>
</button>

<div class="w3-modal" id="gallery" style="margin-top:-6px;">
<div class="w3-modal-content w3-animate-zoom w3-light-gray" style="width:303.7px; height:476.7px;  overflow:scroll;">
<button class="w3-btn w3-light-blue w3-hover-orange w3-large" style="width:100%;" onclick="document.getElementById('gallery').style.display='none'">Go Back
</button><br><br>

<div class="w3-row-padding">
<div class="w3-third">
<img src="image/20.jpg" height="80px" style="width:100%; cursor:pointer;" onclick="onClick(this)" class="w3-hover-opacity">
</div>
<div class="w3-third">
<img src="image/21.jpg" height="80px" style="width:100%; cursor:pointer;" onclick="onClick(this)" class="w3-hover-opacity" >
</div>
<div class="w3-third">
<img src="image/22.jpg" height="80px" style="width:100%; cursor:pointer;" onclick="onClick(this)" class="w3-hover-opacity">
</div>
</div><br>

<div class="w3-row-padding">
<div class="w3-third">
<img src="image/23.jpg" height="80px" style="width:100%; cursor:pointer;" onclick="onClick(this)" class="w3-hover-opacity">
</div>
<div class="w3-third">
<img src="image/crash.jpg" height="80px" style="width:100%; cursor:pointer;" onclick="onClick(this)" class="w3-hover-opacity" >
</div>
<div class="w3-third">
<img src="image/25.jpg" height="80px" style="width:100%; cursor:pointer;" onclick="onClick(this)" class="w3-hover-opacity">
</div>

</div><br>

<div class="w3-row-padding">
<div class="w3-third">
<img src="image/1.jpg" height="80px" style="width:100%; cursor:pointer;" onclick="onClick(this)" class="w3-hover-opacity">
</div>
<div class="w3-third">
<img src="image/2.jpg" height="80px" style="width:100%; cursor:pointer;" onclick="onClick(this)" class="w3-hover-opacity">
</div>
<div class="w3-third">
<img src="image/3.jpg" height="80px" style="width:100%; cursor:pointer;" onclick="onClick(this)" class="w3-hover-opacity">
</div>
</div><br>
<div class="w3-row-padding">
<div class="w3-third">
<img src="image/4.jpg" height="80px" style="width:100%; cursor:pointer;" onclick="onClick(this)" class="w3-hover-opacity">
</div>
<div class="w3-third">
<img src="image/5.jpg" height="80px" style="width:100%; cursor:pointer;" onclick="onClick(this)" class="w3-hover-opacity">
</div>
<div class="w3-third">
<img src="image/6.jpg" height="80px" style="width:100%; cursor:pointer;" onclick="onClick(this)" class="w3-hover-opacity">
</div>
</div><br>
<div class="w3-row-padding">
<div class="w3-third">
<img src="image/7.jpg" height="80px" style="width:100%; cursor:pointer;" onclick="onClick(this)" class="w3-hover-opacity">
</div>
<div class="w3-third">
<img src="image/8.jpg" height="80px" style="width:100%; cursor:pointer;" onclick="onClick(this)" class="w3-hover-opacity">
</div>
<div class="w3-third">
<img src="image/9.jpg" height="80px" style="width:100%; cursor:pointer;" onclick="onClick(this)" class="w3-hover-opacity">
</div>
</div><br>
<div class="w3-row-padding">
<div class="w3-third">
<img src="image/11.jpg" height="80px" style="width:100%; cursor:pointer;" onclick="onClick(this)" class="w3-hover-opacity">
</div>
<div class="w3-third">
<img src="image/12.jpg" height="80px" style="width:100%; cursor:pointer;" onclick="onClick(this)" class="w3-hover-opacity">
</div>
<div class="w3-third">
<img src="image/13.jpg" height="80px" style="width:100%; cursor:pointer;" onclick="onClick(this)" class="w3-hover-opacity">
</div>
</div><br>

<div class="w3-row-padding">
<div class="w3-third">
<img src="image/14.jpg" height="80px" style="width:100%; cursor:pointer;" onclick="onClick(this)" class="w3-hover-opacity">
</div>
<div class="w3-third">
<img src="image/15.jpg" height="80px" style="width:100%; cursor:pointer;" onclick="onClick(this)" class="w3-hover-opacity">
</div>
<div class="w3-third">
<img src="image/16.jpg" height="80px" style="width:100%; cursor:pointer;" onclick="onClick(this)" class="w3-hover-opacity">
</div>
</div><br>

<div id="img" class="w3-modal" onclick="this.style.display='none'" style="margin-top:-6px;">
<div class="w3-modal-content w3-animate-zoom" style="width:303.7px; height:476.7px;">

  <img id="images" class="w3-display-container" style="width:303.7px; height:476.7px;cursor:pointer;">
  <h5 class="w3-display-topleft" style="font-family:bradley hand itc;">click re-zoom</h5>
  </div>
</div>

</div>
</div>
</div>
</div>

<div class="w3-row-padding">
<div class="w3-third">

<div class="w3-modal" id="quotes" style="margin-top:-6px;">
<div class="w3-modal-content w3-light-gray w3-animate-zoom" style="width:303.7px; height:476.7px;  overflow:scroll;">
<button class="w3-btn w3-light-blue w3-hover-orange w3-large" onclick="document.getElementById('quotes').style.display='none'" style="width:100%;">
Go back</button>

<div class="w3-light-gray w3-margin-top">
<h4 class="w3-center w3-border w3-round-medium w3-green" style="font-family:fontawesome; font-weight:bold; color:#59677a;">Quotes</h4>
<center>
<span class=" scheduleBtns" onclick="document.getElementById('scheduleAddModal').style.display='block'" style="background:transparent;">

<img src="gallery/Address_Book_Old_school_Alt_blue.png" width="120px" height="120px"/><br>
<span style="font-family:fontawesome; font-weight:bold; font-size:12px; color:#59677a;">Add Quotes</span>
</span>
</center><br>


<div class="w3-modal " id="scheduleAddModal" style="margin-top:-6px;">
<div class="w3-modal-content w3-light-gray w3-animate-zoom" style="width:303.7px; height:476.7px;  overflow:scroll;">
<button class="w3-btn w3-light-blue w3-hover-orange w3-large" onclick="document.getElementById('scheduleAddModal').style.display='none'" style="width:100%;">Go back</button>
<div class="w3-container w3-card-2 w3-round-medium w3-white w3-large">
<center>
<span style="font-family:britannic bold;font-weight:bold;color:#59677a; ">Today</span>
<br>
</center>
</div>
<form method="post" action="quote.php">
<p><label style="font-size:14px; font-weight:bold;">Title</label>
<input class="w3-input w3-border inputField" type="text" name="category" requiorange /></p>
<p><label style="font-size:14px; font-weight:bold;">Name</label>
<input class="w3-input w3-border inputField" type="text" name="name" requiorange /></p>
<p><label style="font-size:14px; font-weight:bold;">Descriptions</label>
<textarea class="w3-input w3-border inputField" rows="4" cols="10" style="color:green;
  font-size:14px;" name="quote"></textarea></p>
<p>
<input class="w3-input w3-green w3-border w3-round-medium" type="submit" name="submit" value="Add" /></p>
</form>
</div>
</div>





<div class="w3-row-padding" style="margin-left:6px;">
<div class="w3-third">

<a href="view.php"><span class="scheduleBtns" style="background:transparent;">

<img src="gallery/not.jpg" height="70px" style="width:100%;"/><br>
<center>
<span style="font-family:fontawesome; font-weight:bold; font-size:12px; color:#59677a;">View Quotes</span></a>

</span>
</center>
</div>
<div class="w3-third">
<center>
<span class=" scheduleBtns" style="background:transparent;">

<img src="gallery/note.jpg" height="70px" style="width:100%; "/><br>
<span style="font-family:fontawesome; font-weight:bold; font-size:12px; color:#59677a;">Update Quotes</span>

</span>
</center>
</div>
<div class="w3-third">
<center>
<span class="  scheduleBtns" style="background:transparent;">

<img src="gallery/delete.png" height="70px" style="width:100%;"/><br>
<span style="font-family:fontawesome; font-weight:bold; font-size:12px; color:#59677a;">Delete Quotes</span>

</span>
</center>
</div>
</div>
</div>
</div>
</div>
</div>

</div>
</div>


<!--footer part content-->
<div class="w3-container buttons">
<ul class="btns">
<li>
<img src="icons/feedback.png" width="30px" height="30px" style="opacity:.5;"/>
</li>


<li style="padding-right:70px;padding-left:70px;"  >
<img src="icons/home.png" width="30px" height="30px" />
</li>


<li>
<img src="icons/ba.png" width="30px" height="30px" />
</li>
</ul>

</div>
</div>


<script>
var myIndex = 0;
carousel();

function carousel() {
    var i;
    var x = document.getElementsByClassName("mySlides");
    for (i = 0; i < x.length; i++) {
       x[i].style.display = "none";  
    }
    myIndex++;
    if (myIndex > x.length) {myIndex = 1}    
    x[myIndex-1].style.display = "block";  
    setTimeout(carousel, 6000);    
}
function onClick(element) {
  document.getElementById("images").src = element.src;
  document.getElementById("img").style.display = "block";
}

var myVar;

function myFunction() {
    myVar = setTimeout(showPage, 3000);
}

function showPage() {
  document.getElementById("loader").style.display = "none";
  document.getElementById("myDiv").style.display = "block";
}




</script>
</body>
</html>
