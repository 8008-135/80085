<!DOCTYPE html>
<html>
  <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>wip~</title>
    <style>
      a:hover {
        cursor: pointer;
      }
    </style>
    <!-- The style.css file allows you to change the look of your web pages.
         If you include the next line in all your web pages, they will all share the same look.
         This makes it easier to make new pages for your site. -->
   <link href="/style.css" rel="stylesheet" type="text/css" media="all">
  </head>

<body>
<div id="mySidenav" class="sidenav" style="background:url('/img-checkergreen.png');">
  <a href="javascript:void(0)" class="closebtn" onclick="closeNav()">&times;</a>
  
  <center><p><big>WARNING: BLINKIES/EYESTRAIN!</big><br>
  welcome to the secret garden! fairies reside here.<br>
  wanderers <u>turn back now</u>.<br><br>
  <img style="" alt="??" width="141" height="44" src="/amren4.gif"><br>
  <img style="" alt="??" width="200" height="231" src="/img-tink2.jpg"><br>
  <img style="" alt="??" width="200" height="27" src="/blinkie-1.gif"><br>
  <img style="" alt="??" width="100" height="100" src="/arrow-2.png">

<div class="popup" onclick="myFunction()"><img style="" alt="??" width="120" height="90" src="/clickme-1.png">
  <span class="popuptext" id="myPopup"><div class="popupheader">welcome:</div><div class="popupcontent">to my <s>secret</s> neocities page! enjoy my first html project. please contact me with any and all feedback, and to report any issues.</div></span>
</div>

<script>
// When the user clicks on <div>, open the popup
function myFunction() {
  var popup = document.getElementById("myPopup");
  popup.classList.toggle("show");
}
</script>

  <a class="hover">About Me</a>
  <a class="hover">Link 2</a>
  <a class="hover">Link 3</a>
  <a class="hover">Link 4</a>
  <transparent>secret mssg lol i needed some extra space here</transparent>
  </center>
<!-- Use any element to open the sidenav -->
</div>
<div id="onclick1">
<span onclick="openNav()">+</span>
</div>

<!-- Add all page content inside this div if you want the side nav to push page content to the right (not used if you only want the sidenav to sit on top of the page -->

<div id="main">
    <h1>wip!~</h1>
<center><b>Loading</b> <span class="one">.</span><span class="two">.</span><span class="three">.</span>​</center>

<div id="Progress_Status"> 
  <div id="myprogressBar"></div> 
</div>
<center><button onclick="update()">Click to Start</button></center> 

<script> 
function update() { 
  var element = document.getElementById("myprogressBar");    
  var width = 1; m
  var identity = setInterval(scene, 50); 
    
  function scene() { 
    if (width >= 99) { 
      clearInterval(identity); 
    } else { 
      width++;  
      element.style.width = width + '%';  
      element.innerHTML = width * 1  + '%';  
    } 
  } 
} 
</script> 

<br>
    <p><center><b>WARNING</b>! Pages include
    <div class="hover-title"><u>flashing images</u></div>
    <div class="hover-image"><img style="" alt="??" width="150" height="20" src="/blinkie-1.gif"></div>
 <i>&</i>
    <div class="hover-title"><u>eyestrain</u></div>
    <div class="hover-image"><img style="" alt="??" width="150" height="20" src="img-checkergreen2.png"></div> 
content.<br>
Photosensitive users be advised.</center>
    hehe thats me ~> <img style="" alt="??" width="150" height="150" src="/img-tink.JPG"><br>
    this is going to take quite some time.
    
</div>

<script>
/* Set the width of the side navigation to 250px */
function openNav() {
  document.getElementById("mySidenav").style.width = "250px";
}

/* Set the width of the side navigation to 0 */
function closeNav() {
  document.getElementById("mySidenav").style.width = "0";
}

/* Open the sidenav */
function openNav() {
  document.getElementById("mySidenav").style.width = "100%";
}

/* Close/hide the sidenav */
function closeNav() {
  document.getElementById("mySidenav").style.width = "0";
}
</script>


</body>

<!-- End page content -->
</html>
