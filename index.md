<!DOCTYPE html>
<html>
<head>
<title>W3.CSS Template</title>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
<link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Montserrat">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
<style>
body, h1,h2,h3,h4,h5,h6 {font-family: "Montserrat", sans-serif}
.w3-row-padding img {margin-bottom: 12px}
/* Set the width of the sidebar to 120px */
.w3-sidebar {width: 120px;background: #222;}
/* Add a left margin to the "page content" that matches the width of the sidebar (120px) */
#main {margin-left: 120px}
/* Remove margins from "page content" on small screens */
@media only screen and (max-width: 600px) {#main {margin-left: 0}}
</style>
</head>
<body class="w3-black">

<!-- Icon Bar (Sidebar - hidden on small screens) -->
<nav class="w3-sidebar w3-bar-block w3-small w3-hide-small w3-center">
  <!-- Avatar image in top left corner -->
  <img src="data:image/jpeg;base64,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" style="width:100%">
  <a href="#" class="w3-bar-item w3-button w3-padding-large w3-black">
    <i class="fa fa-home w3-xxlarge"></i>
    <p>HOME</p>
  </a>
  <a href="#about" class="w3-bar-item w3-button w3-padding-large w3-hover-black">
    <i class="fa fa-user w3-xxlarge"></i>
    <p>ABOUT</p>
  </a>
  <a href="#photos" class="w3-bar-item w3-button w3-padding-large w3-hover-black">
    <i class="fa fa-eye w3-xxlarge"></i>
    <p>PROJECTS</p>
  </a>
  <a href="#contact" class="w3-bar-item w3-button w3-padding-large w3-hover-black">
    <i class="fa fa-envelope w3-xxlarge"></i>
    <p>CONTACT</p>
  </a>
</nav>

<!-- Navbar on small screens (Hidden on medium and large screens) -->
<div class="w3-top w3-hide-large w3-hide-medium" id="myNavbar">
  <div class="w3-bar w3-black w3-opacity w3-hover-opacity-off w3-center w3-small">
    <a href="#" class="w3-bar-item w3-button" style="width:25% !important">HOME</a>
    <a href="#about" class="w3-bar-item w3-button" style="width:25% !important">ABOUT</a>
    <a href="#photos" class="w3-bar-item w3-button" style="width:25% !important">PROJECTS</a>
    <a href="#contact" class="w3-bar-item w3-button" style="width:25% !important">CONTACT</a>
  </div>
</div>

<!-- Page Content -->
<div class="w3-padding-large" id="main">
  <!-- Header/Home -->
  <header class="w3-container w3-padding-32 w3-center w3-black" id="home">
    <h1 class="w3-jumbo"><span class="w3-hide-small">I'm</span> Quiance Bibbs.</h1>
    <p>Technical Writer and Software Engineer.</p>
    
  </header>

  <!-- About Section -->
  <div class="w3-content w3-justify w3-text-grey w3-padding-64" id="about">
    <h2 class="w3-text-light-grey">About Me</h2>
    <hr style="width:200px" class="w3-opacity">
    <p>Some text about me. Some text about me. I am lorem ipsum consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip
      ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum consectetur
      adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
    </p>
    <h3 class="w3-padding-16 w3-text-light-grey">My Skills</h3>
    <p class="w3-wide">Writing/Editing</p>
    <div class="w3-white">
      <div class="w3-dark-grey" style="height:28px;width:95%"></div>
    </div>
    <p class="w3-wide">Web Design</p>
    <div class="w3-white">
      <div class="w3-dark-grey" style="height:28px;width:65%"></div>
    </div>
    <p class="w3-wide">Photoshop</p>
    <div class="w3-white">
      <div class="w3-dark-grey" style="height:28px;width:80%"></div>
    </div><br>
    
    <div class="w3-row w3-center w3-padding-16 w3-section w3-light-grey">
      <div class="w3-quarter w3-section">
        <span class="w3-xlarge">11+</span><br>
        Partners
      </div>
      <div class="w3-quarter w3-section">
        <span class="w3-xlarge">55+</span><br>
        Projects Done
      </div>
      <div class="w3-quarter w3-section">
        <span class="w3-xlarge">89+</span><br>
        Happy Clients
      </div>
      <div class="w3-quarter w3-section">
        <span class="w3-xlarge">150+</span><br>
        Meetings
      </div>
    </div>

    <button class="w3-button w3-light-grey w3-padding-large w3-section">
      <a class="fa fa-download" href="https://docs.google.com/document/d/e/2PACX-1vTnp6dXhtYJz7vCW8cjpVBRSqo9QqdXuRSYXoFfKWaOoXdcqGLAjBt910s9LWQY4da2RyTVwtIBl1QU/pub"> </a> Download Resume
    </button>
    
    <!-- Grid for pricing tables -->
    <h3 class="w3-padding-16 w3-text-light-grey">My Services</h3>
    <div class="w3-row-padding" style="margin:0 -16px">
      
      <div class="w3-half">
        <ul class="w3-ul w3-white w3-center w3-opacity w3-hover-opacity-off">
          <li class="w3-dark-grey w3-xlarge w3-padding-32">Pro</li>
          <li class="w3-padding-16">Web Design</li>
          <li class="w3-padding-16">User Interface Design (Mobile)</li>
          <li class="w3-padding-16">Technical Writing</li>
          <li class="w3-padding-16">Copywriting</li>
          <li class="w3-padding-16">
            <h2>$ 55</h2>
            <span class="w3-opacity">per hour</span>
          </li>
          <li class="w3-light-grey w3-padding-24">
            <button class="w3-button w3-white w3-padding-large w3-hover-black">Request Service</button>
          </li>
        </ul>
      </div>
    <!-- End Grid/Pricing tables -->
    </div>
    
    <!-- Testimonials -->
    
  <!-- End About Section -->
  </div>
  
  <!-- Portfolio Section -->
  <div class="w3-padding-64 w3-content" id="photos">
    <h2 class="w3-text-light-grey">My Projects</h2>
    <hr style="width:200px" class="w3-opacity">

    <!-- Grid for photos -->
    <div class="w3-row-padding" style="margin:0 -16px">
      <div class="w3-half">
        <img src="https://m.media-amazon.com/images/I/61nt34iuBkL._SS500_.jpg" style="width:100%">
 
      </div>

      <div class="w3-half">
    
        
      </div>
    <!-- End photo grid -->
    </div>
  <!-- End Portfolio Section -->
  </div>

  <!-- Contact Section -->
  <div class="w3-padding-64 w3-content w3-text-grey" id="contact">
    <h2 class="w3-text-light-grey">Contact Me</h2>
    <hr style="width:200px" class="w3-opacity">

    <div class="w3-section">
      <p><i class="fa fa-map-marker fa-fw w3-text-white w3-xxlarge w3-margin-right"></i> Chicago, US</p>
      <p><i class="fa fa-phone fa-fw w3-text-white w3-xxlarge w3-margin-right"></i> Phone: +1 312 498 3585</p>
      <p><i class="fa fa-envelope fa-fw w3-text-white w3-xxlarge w3-margin-right"> </i> Email: quiancebibbs@gmail.com</p>
    </div><br>
    <p>Let's get in touch. Send me a message:</p>

    <form action="/action_page.php" target="_blank">
      <p><input class="w3-input w3-padding-16" type="text" placeholder="Name" required name="Name"></p>
      <p><input class="w3-input w3-padding-16" type="text" placeholder="Email" required name="Email"></p>
      <p><input class="w3-input w3-padding-16" type="text" placeholder="Subject" required name="Subject"></p>
      <p><input class="w3-input w3-padding-16" type="text" placeholder="Message" required name="Message"></p>
      <p>
        <button class="w3-button w3-light-grey w3-padding-large" type="submit">
          <i class="fa fa-paper-plane"></i> SEND MESSAGE
        </button>
      </p>
    </form>
  <!-- End Contact Section -->
  </div>
  
    <!-- Footer -->
  <footer class="w3-content w3-padding-64 w3-text-grey w3-xlarge">
    <i class="fa fa-facebook-official w3-hover-opacity"></i>
    <i class="fa fa-instagram w3-hover-opacity"></i>
    <i class="fa fa-snapchat w3-hover-opacity"></i>
    <i class="fa fa-pinterest-p w3-hover-opacity"></i>
    <i class="fa fa-twitter w3-hover-opacity"></i>
    <i class="fa fa-linkedin w3-hover-opacity"></i>
    <p class="w3-medium">Powered by <a href="https://www.w3schools.com/w3css/default.asp" target="_blank" class="w3-hover-text-green">w3.css</a></p>
  <!-- End footer -->
  </footer>

<!-- END PAGE CONTENT -->
</div>

</body>
</html>
