<html>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
<link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Montserrat">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
<style>
body, h1,h2,h3,h4,h5,h6 {font-family: "Montserrat", sans-serif}
.w3-row-padding img {margin-bottom: 12px}
.bgimg {
 
  background-repeat: no-repeat;
  
  background-image: url('https://serving.photos.photobox.com/796881921f80b97eac99f0c029975165eb53233ffe58d1f0fe9ac99417f8da41458fd680.jpg');
  min-height: 100%;
}
</style>
<body>

<!-- Sidebar with image -->
<nav class="w3-sidebar w3-hide-medium w3-hide-small" style="width:40%">
  <div class="bgimg"></div>
</nav>

<!-- Hidden Sidebar (reveals when clicked on menu icon)-->
<nav class="w3-sidebar w3-black w3-animate-right w3-xxlarge" style="display:none;padding-top:150px;right:0;z-index:2" id="mySidebar">
  <a href="javascript:void(0)" onclick="closeNav()" class="w3-button w3-black w3-xxxlarge w3-display-topright" style="padding:0 12px;">
    <i class="fa fa-remove"></i>
  </a>
  <div class="w3-bar-block w3-center">
    <a href="#" class="w3-bar-item w3-button w3-text-grey w3-hover-black" onclick="closeNav()">Home</a>
    <a href="#about" class="w3-bar-item w3-button w3-text-grey w3-hover-black" onclick="closeNav()">About</a>
    <a href="#contact" class="w3-bar-item w3-button w3-text-grey w3-hover-black" onclick="closeNav()">Contact</a>
  </div>
</nav>

<!-- Page Content -->
<div class="w3-main w3-padding-large" style="margin-left:40%">

  <!-- Menu icon to open sidebar -->
  <span class="w3-button w3-top w3-white w3-xxlarge w3-text-grey w3-hover-text-black" style="width:auto;right:0;" onclick="openNav()"><i class="fa fa-bars"></i></span>

  <!-- Header -->
  <header class="w3-container w3-center" style="padding:128px 16px" id="home">
    <h1 class="w3-jumbo"><b>Pan Shahbazi</b></h1>
    <p>Iranian-American, LA Based, DOO & Dev</p>
    <img src="https://serving.photos.photobox.com/796881921f80b97eac99f0c029975165eb53233ffe58d1f0fe9ac99417f8da41458fd680.jpg" class="w3-image w3-hide-large w3-hide-small w3-round" style="display:block;width:60%;margin:auto;">
    <img src="https://serving.photos.photobox.com/796881921f80b97eac99f0c029975165eb53233ffe58d1f0fe9ac99417f8da41458fd680.jpg" class="w3-image w3-hide-large w3-hide-medium w3-round" width="1000" height="1333">
   
  </header>

  
  <!-- About Section -->
  <div class="w3-content w3-justify w3-text-grey w3-padding-32" id="about">
    <h2>Nice to Meet You.</h2>
    <hr class="w3-opacity">
    <p>My name is Pan Shahbazi (short for Paniz Shahbazian); an Iranian-American, LA-based jack-of-all-trades. I currently work as the DOO of a company that brings new life to the world of hearing protection and music-related tech. I recently worked on an app ("Ear Scanner") that was released to the app store, which enables users to get a full scan of their ears at home (basically, ear molds without all the goop and having to travel to an audiologist). Feel free to check it out here.</p><p>

I'm also full-stack web-developer, with an extensive knowledge in UI/UX design. I'm fascinated by the possibilities of AI and what quantum computing can bring to our future. Follow me on my socials for more (linked at the bottom of this page).</p>

    

   

    
    
   
  <!-- End About Section -->
  </div>

  <!-- Contact Section -->
  <div class="w3-padding-32 w3-content w3-text-grey" id="contact" style="margin-bottom:64px">
    <h2>Want to Get in Touch?</h2>
    <hr class="w3-opacity">

    <div class="w3-section">
      <p><i class="fa fa-map-marker fa-fw w3-xxlarge w3-margin-right"></i> Los Angeles, California</p>
      
    </div>
    
    <!-- Image of location/map -->
 
<script src="https://apps.elfsight.com/p/platform.js" defer></script>
<div class="elfsight-app-1799076e-d996-443f-a7e0-c0b486c0d2f3"></div>
  
  <!-- End Contact Section -->
  </div>  
  
  <!-- Footer -->
  <footer class="w3-container w3-padding-64 w3-light-grey w3-center w3-opacity w3-xlarge" style="margin:-24px">
    <a href="https://facebook.com/PanShahbazi"><i class="fa fa-facebook-official w3-hover-opacity"></i></a>
     <a href="https://instagram.com/PanShahbazi"><i class="fa fa-instagram w3-hover-opacity"></i></a>
  <a href="https://twitter.com/PanShahbazi">   <i class="fa fa-twitter w3-hover-opacity"></i></a>
   <a href="https://linkedin.com/Pan-Shahbazi">  <i class="fa fa-linkedin w3-hover-opacity"></i></a>
   
  <!-- End footer -->
  </footer>
  
<!-- END PAGE CONTENT -->
</div>

<script>
// Open and close sidebar
function openNav() {
  document.getElementById("mySidebar").style.width = "60%";
  document.getElementById("mySidebar").style.display = "block";
}

function closeNav() {
  document.getElementById("mySidebar").style.display = "none";
}
</script>

</body>
</html>
