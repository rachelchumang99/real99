<!DOCTYPE html>
<html>
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
<body class="w3-black">

<!-- Icon Bar (Sidebar - hidden on small screens) -->
<nav class="w3-sidebar w3-bar-block w3-small w3-hide-small w3-center">
  <!-- Avatar image in top left corner -->
  <img src="myimage6.jpeg" style="width:100%">
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
    <p>PHOTOS</p>
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
    <a href="#photos" class="w3-bar-item w3-button" style="width:25% !important">PHOTOS</a>
    <a href="#contact" class="w3-bar-item w3-button" style="width:25% !important">CONTACT</a>
  </div>
</div>

<!-- Page Content -->
<div class="w3-padding-large" id="main">
  <!-- Header/Home -->
  <header class="w3-container w3-padding-32 w3-center w3-black" id="home">
    <h1 class="w3-jumbo"><span class="w3-hide-small">I'm</span> Rachel Chumang</h1>
    <p>Marketing Manager.</p>
    <img src="mybannerhtml.jpeg" width="992" height="1108">
  </header>

  <!-- About Section -->
  <div class="w3-content w3-justify w3-text-grey w3-padding-64" id="about">
    <h2 class="w3-text-light-grey">About Me</h2>
    <hr style="width:200px" class="w3-opacity">
    <p>Some text about me. Some text about me. I am Rachel Chumang Anak Ramsay, a Marketing Manager of Nike Co. Sdn.Bhd with direct working experience in products for personalized marketing. 
	To aim use my proven success in identifying growth opportunities, strategic positioning of different products. . Here, I am looking forward to gain more experience and want to contribute 
	a productive a profitable workforce to your company.Back then, I was an alumni of the UiTM Sarawak Branch from 2012 to 2018. My education background starts with my  Diploma in Business Studies at UiTM Mukah Campus,
	 Sarawak and and supports with my Bachelor in Marketing and continue my Master Degree's in International Business at University Malaya. Every semester I got Dean Award and during my convocation I was awarded the vice cancelor award. I consider myself a problem solver, being able to think outside teh box to provide a solution taht may 
	not be obvious to others.
	 I acknowledges in managerial of business and I a professional person in doing any task. My work will satisfy you.Therefore, with the qualitify of my education, I wish I was given the opportunity to work at your company, and I am very happy to work with you
    </p>
    <h3 class="w3-padding-16 w3-text-light-grey">My Skills</h3>
    <p class="w3-wide">Marketing</p>
    <div class="w3-white">
      <div class="w3-dark-grey" style="height:28px;width:95%"></div>
    </div>
    <p class="w3-wide">Marketing Management</p>
    <div class="w3-white">
      <div class="w3-dark-grey" style="height:28px;width:85%"></div>
    </div>
    <p class="w3-wide">Photoshop</p>
    <div class="w3-white">
      <div class="w3-dark-grey" style="height:28px;width:80%"></div>
    </div><br>
    
    <div class="w3-row w3-center w3-padding-16 w3-section w3-light-grey">
      <div class="w3-quarter w3-section">
        <span class="w3-xlarge">15+</span><br>
        Partners
      </div>
      <div class="w3-quarter w3-section">
        <span class="w3-xlarge">60+</span><br>
        Projects Done
      </div>
      <div class="w3-quarter w3-section">
        <span class="w3-xlarge">90+</span><br>
        Happy Clients
      </div>
      <div class="w3-quarter w3-section">
        <span class="w3-xlarge">160+</span><br>
        Meetings
      </div>
    </div>

    <button class="w3-button w3-light-grey w3-padding-large w3-section">
      <i class="fa fa-download"></i> Download Resume
    </button>
    
    <!-- Grid for education -->
    <h3 class="w3-padding-16 w3-text-light-grey">My Education Background </h3>
    <div class="w3-row-padding" style="margin:0 -16px">
      <div class="w3-half w3-margin-bottom">
        <ul class="w3-ul w3-white w3-center w3-opacity w3-hover-opacity-off">
          <li class="w3-dark-grey w3-xlarge w3-padding-32">Basic</li>
          <li class="w3-padding-16">Diploma in Business Studies, University Teknologi Mara, Kampus Mukah</li>
          <li class="w3-padding-16">Bachelor in Marketing, University Teknologi Mara, Kampus Samarahan</li>
          <li class="w3-padding-16">master Degree's in International Business, University Malaya</li>
          
          <li class="w3-light-grey w3-padding-24">
            <button class="w3-button w3-white w3-padding-large w3-hover-black">Sign Up</button>
          </li>
        </ul>
      </div>
    <!-- End Grid/Education -->
    </div>
    
    <!-- Testimonials -->
    <h3 class="w3-padding-24 w3-text-light-grey">My Reputation</h3>  
    <img src="image8.jpg" alt="Avatar" class="w3-left w3-circle w3-margin-right" style="width:80px">
    <p><span class="w3-large w3-margin-right">Miss Photogenic.</span> CEO at Mighty Schools.</p>
    <p>Rachel Chumang saved us from a web disaster.</p><br>
    
    <img src="myimage3.jpeg" alt="Avatar" class="w3-left w3-circle w3-margin-right" style="width:80px">
    <p><span class="w3-large w3-margin-right">Tasha</span> CEO at Company.</p>
    <p>No one is better than Rachel Chumang, she is the best.</p>
  <!-- End About Section -->
  </div>
  
  <!-- Portfolio Section -->
  <div class="w3-padding-64 w3-content" id="photos">
    <h2 class="w3-text-light-grey">My Photos</h2>
    <hr style="width:200px" class="w3-opacity">

    <!-- Grid for photos -->
    <div class="w3-row-padding" style="margin:0 -16px">
      <div class="w3-half">
        <img src="rachelchumang.jpg" style="width:100%">
        <img src="image7.jpg" style="width:100%">
        <img src="myimage6.jpeg" style="width:100%">
      </div>

      <div class="w3-half">
        <img src="myimage1.jpeg" style="width:100%">
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
      <p><i class="fa fa-map-marker fa-fw w3-text-white w3-xxlarge w3-margin-right"></i> Kuching, Sarawak</p>
      <p><i class="fa fa-phone fa-fw w3-text-white w3-xxlarge w3-margin-right"></i> Phone: +02 387698</p>
      <p><i class="fa fa-envelope fa-fw w3-text-white w3-xxlarge w3-margin-right"> </i> Email: chel@mail.com</p>
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
