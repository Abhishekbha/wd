# wd
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>website</title>
    <link rel="stylesheet" href="sileone.css">
</head>
 
<nav>   
    <img  class="logo" src="images/logo.png">
    <ul>
    <li><a href="#">Home</a></li>
    <li><a href="#">Gallery</a></li>
    <li><a href="#">About Us</a></li> 
    
    <div class="st"> 
    <li><a href="#">Menu</a></li> 
<div class="aa"> 
     <a class="Menu" href="#">Menu 1</a>  
      <a class="Menu" href="#">Menu 2</a>  
      <a class="Menu" href="#">Menu 3</a>  
</div>
</div>

    <li><a href="#">Contacts us</a></li>
</ul>
</nav> 
 

<div class="sl">
  <img class="mySlides" src="images/r.jpg" style="width:100%"  height="100%"  >
  <img class="mySlides" src="images/r1.jpg" style="width:100%" height="100%">
  <img class="mySlides" src="images/wq.jpg" style="width:100%" height="100%">
  <img class="mySlides" src="images/wqqq.jpg" style="width:100%" height="100%">
  <video class="mySlides" width="100%" height="100%" controls  source  src="q.mp4" type="video/mp4">

</div> 
  <button class="left " onclick="plusDivs(-1)">&#10094;</button>
  <button class=" right" onclick="plusDivs(1)">&#10095;</button>

<div id="sl1">
<center>
    <h1 style="color: black;"><i>  KlassyCafe
        THE BEST EXPERIENCE </i> </h1>
</center>
<button class="buu" type="button"><i>Make a Responsive</i></button>

</div>

<div id="box5">
<div id="box5_1">
<h2 class="we">ABOUT US<br>
We Leave A Delicious<br> Memory For You</h2>
<span class="we1">Klassy Cafe is one of the best <b color="blue">restaurant HTML templates</b> with Bootstrap 
v4.5.2 CSS framework. You can download and feel free to use this website
 template layout for your restaurant business. You are allowed to use this 
 template for commercial purposes.
</span>

<span class="we2">
You are NOT allowed to redistribute the template ZIP file on any template donwnload website. Please contact us for more information.
</span>
<div id="b1"></div>
<div id="b2"></div>
<div id="b3"></div>


</div>

<div id="boxwe3">
<img  class="im" src="images/r1.jpg" width="100%" height="90%">
</div>
</div>
<div id="form">

<div id="fo">
<span class="fo1">CONTACT US</br>
Here You Can Make A Reservation Or Just walkin to our cafe
</span>
<span class="fo2">Donec pretium est orci, non vulputate arcu hendrerit a. Fusce a eleifend riqsie, namei sollicitudin urna diam, sed commodo purus porta ut.
</span>

<div id="tw1"> 
<center>
<b class="ph"> Phone Number</b>
</center>
<span class="num">987-090-7890</span>
</br>

<span class="num1">881-340-8819</span>
</div>
<div id="tw2">
<b class="p1">EMAILS</b>
<span class="email"> <i> Hloinfo@Company.com</i> </span>
<span class="email1"><i> Abhi@Company.com</i>  </span>
</div>
</div>
<div class="boxn">
<div id="boxn1"> 
<h1 class="rese">Table Reservation</h1>
<form action="site2.php" method="POST">
<input class="name" type="text" name="name" placeholder="Enter your name">
<input class="emails" type="email" name="email" placeholder="Enter your email">
<input class="phone" type="phone" name="phone" placeholder="Enter your Phone">
<input class="gest"  type="int" name="gest" placeholder="Number of Guests">
<input class="date"   type="date" >
<input class="time"   type="time" placeholder="Time">
<input class="message"   type="message" placeholder="Message">

<input class="submit" type="submit" value="Make a Reservation">

</form>

</div>
 </div>
</div>

<?php



?>
<script>
var v = 1;
showDivs( );

function plusDivs(n) {
  showDivs(v += n);
}

function showDivs(n) {
  var i;
  var x = document.getElementsByClassName("mySlides");
  if (n > x.length) {v = 1}
  if (n < 1) {v = x.length}
  for (i = 0; i < x.length; i++) {
    x[i].style.display = "none";  
  }
  x[v-1].style.display = "block";  
}
 
</script>

    
</body>
</html>
