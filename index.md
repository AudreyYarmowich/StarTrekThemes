<!DOCTYPE html>
<html lang="en">
<title>The Archivists</title>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="demo.css">
<link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Poppins">
<style>
body,h1,h2,h3,h4,h5 {font-family: "Poppins", sans-serif}
body {font-size:16px;}
.w3-third img{margin-bottom:-6px;margin-top:16px;opacity:0.8;cursor:pointer}
.w3-third img:hover{opacity:1}
</style>
<body>

<!-- Sidebar/menu -->
<nav class="w3-sidebar w3-deep-purple w3-collapse w3-top w3-large w3-padding" style="z-index:3;width:300px;font-weight:bold;" id="mySidebar"><br>
  <a href="javascript:void(0)" onclick="w3_close()" class="w3-button w3-hide-large w3-display-topleft" style="width:100%;font-size:22px">Close Menu</a>
  <div class="w3-container">
    <h3 class="w3-padding-64"><b>The<br>Archivists</b></h3>
  </div>
  <div class="w3-bar-block">
    <a href="#" onclick="w3_close()" class="w3-bar-item w3-button w3-hover-white">Home</a> 
    <a href="./existentialism/home.html" onclick="w3_close()" class="w3-bar-item w3-button w3-hover-white">Existentialism</a> 
    <a href="./linearity/home.html" onclick="w3_close()" class="w3-bar-item w3-button w3-hover-white">Non-Linearity</a> 
    <a href="./simulation/home.html" onclick="w3_close()" class="w3-bar-item w3-button w3-hover-white">Simulation/Reality</a>
  </div>
</nav>

<!-- Top menu on small screens -->
<header class="w3-container w3-top w3-hide-large w3-deep-purple w3-xlarge w3-padding">
  <a href="javascript:void(0)" class="w3-button w3-deep-purple w3-margin-right" onclick="w3_open()">☰</a>
  <span>Postmodern Themes in Narrative-based Interactive Electronic Media</span>
</header>

<!-- Overlay effect when opening sidebar on small screens -->
<div class="w3-overlay w3-hide-large" onclick="w3_close()" style="cursor:pointer" title="close side menu" id="myOverlay"></div>

<!-- !PAGE CONTENT! -->
<div class="w3-main" style="margin-left:340px;margin-right:40px">

  <!-- Header -->
  <div class="w3-container" style="margin-top:80px" id="showcase">
    <h1 class="w3-jumbo"><b>Postmodernism in Games</b></h1>
   <!--  <h1 class="w3-xxxlarge w3-text-deep-purple"><b>Showcase.</b></h1>
    <hr style="width:50px;border:5px solid rgb(106, 90, 205)" class="w3-round"> -->
  </div>
  
  <!-- Photo grid (modal) -->
  <!-- <div class="w3-row-padding">
    <div class="w3-third">
      <a href="minecraft.html">
        <img src="minecraft.jpg" style="width:100%" alt="Minecraft">
      </a>
      <img src="minecraft.jpg" style="width:100%" onclick="onClick(this)" alt="Light, white and tight scandinavian design">
    </div>

    <div class="w3-third">
      <img src="minecraft.jpg" style="width:100%" onclick="onClick(this)" alt="Windows for the atrium">
      <img src="minecraft.jpg" style="width:100%" onclick="onClick(this)" alt="Bedroom and office in one space">
    </div>

    <div class="w3-third">
      <img src="minecraft.jpg" style="width:100%" onclick="onClick(this)" alt="Windows for the atrium">
      <img src="minecraft.jpg" style="width:100%" onclick="onClick(this)" alt="Bedroom and office in one space">
    </div>
  </div>
 -->
  <!-- Modal for full size images on click-->
<!--   <div id = "replace" >
  <div id="modal01" class="w3-modal w3-black" style="padding-top:0" onclick="this.style.display='none'">
    <span class="w3-button w3-black w3-xxlarge w3-display-topright">×</span>
    <div class="w3-modal-content w3-animate-zoom w3-center w3-transparent w3-padding-64">
    <div class= "w3-third">
      <img id="img01" class="w3-image">
      <p id="caption"></p>
    </div>
  </div>
 -->
  <!-- Services -->
  <div class="w3-container" id="services" style="margin-top:25px">
    <h1 class="w3-xxxlarge w3-text-deep-purple"><b>Welcome.</b></h1>
    <hr style="width:50px;border:5px solid rgb(106, 90, 205)" class="w3-round">
    <p>This project acts as and archival and presents analysis of video games using postmodern themes. We have split the archive into three categories, games exploring themes of existentialism, non-linearity, and simulation and truth. There is a page for each source containing a description of the source, how it fits with the category we have placed it in, and what it adds to the understanding of that category.</p>

  </div>
  
  <!-- Designers -->
  <div class="w3-container" id="designers" style="margin-top:25px">
    <h1 class="w3-xxxlarge w3-text-deep-purple"><b>Objective.</b></h1>
    <hr style="width:50px;border:5px solid rgb(106, 90, 205)" class="w3-round">
    <p>The primary objective of this archive is to analysis several of our favorite video games by looking at them through the lense of any one of three postmodern themes, these being: Sartre’s Existentialist philosophy, unconventional forms of temporal storytelling, and Baudrillard’s Simulations and Simulacra. Format-wise, These analyses are done in a mixed-media format, combining digital elements such as embedded video players and image galleries with traditional text-based analysis.
    </p>
  </div>

    <div class="w3-row-padding" style="margin-top:25px">
    <div class="w3-third w3-margin-bottom">
      <ul class="w3-ul w3-light-grey w3-center">
        <li class="w3-deep-purple w3-xlarge w3-padding-32">
          <a href="./existentialism/home.html" onclick="w3_close()" class="w3-bar-item w3-button w3-hover-white">Existentialism</a>
        </li>
        <li class="w3-padding-16">
          <a href="./existentialism/minecraft.html" onclick="w3_close()" class="w3-bar-item w3-button w3-hover-dark-grey">Minecraft</a>
        </li>
        <li class="w3-padding-16">
          <a href="./existentialism/nierautomata.html" onclick="w3_close()" class="w3-bar-item w3-button w3-hover-dark-grey">Nier Automata</a>
        </li>
        <!-- <li class="w3-padding-16">
          <a href="./existentialism/darksouls.html" onclick="w3_close()" class="w3-bar-item w3-button w3-hover-dark-grey">Dark Souls</a>
        </li> -->
        <!-- <li class="w3-padding-16">
          <a href="./existentialism/sky.html" onclick="w3_close()" class="w3-bar-item w3-button w3-hover-dark-grey">Sky</a>
        </li> -->
        <li class="w3-padding-16">
          <a href="./existentialism/limbo.html" onclick="w3_close()" class="w3-bar-item w3-button w3-hover-dark-grey">Limbo</a>
        </li>
        <li class="w3-padding-16">
          <a href="./existentialism/specops.html" onclick="w3_close()" class="w3-bar-item w3-button w3-hover-dark-grey">Spec Ops: The Line</a>
        </li>
      </ul>
    </div>
        
    <div class="w3-third">
      <ul class="w3-ul w3-light-grey w3-center">
        <li class="w3-deep-purple w3-xlarge w3-padding-32">
          <a href="./linearity/home.html" onclick="w3_close()" class="w3-bar-item w3-button w3-hover-white">Non-Linear Story Telling</a>
        </li>
        <li class="w3-padding-16">
          <a href="./linearity/bioshockInfinite.html" onclick="w3_close()" class="w3-bar-item w3-button w3-hover-dark-grey">Bioshock Infinite</a>
        </li>
        <li class="w3-padding-16">
          <a href="./linearity/steinGate.html" onclick="w3_close()" class="w3-bar-item w3-button w3-hover-dark-grey">Steins Gate</a>
        </li>
        <!-- <li class="w3-padding-16">
          <a href="./linearity/nightInTheWoods.html" onclick="w3_close()" class="w3-bar-item w3-button w3-hover-dark-grey" >Night in the Woods</a>
        </li> -->
        <li class="w3-padding-16">
          <a href="./linearity/whatRemainsOfEdithFinch.html" onclick="w3_close()" class="w3-bar-item w3-button w3-hover-dark-grey">What Remains of Edith Finch</a>
        </li>
      </ul>
    </div>

    <div class="w3-third w3-margin-bottom">
      <ul class="w3-ul w3-light-grey w3-center">
        <li class="w3-deep-purple w3-xlarge w3-padding-32">
          <a href="./simulation/home.html" onclick="w3_close()" class="w3-bar-item w3-button w3-hover-white">Simulation/Reality</a>
        </li>
        <li class="w3-padding-16">
          <a href="./simulation/home.html" onclick="w3_close()" class="w3-bar-item w3-button w3-hover-dark-grey">Superhot</a>
        </li>
        <!-- <li class="w3-padding-16">
          <a href="./simulation/tokiToki.html" onclick="w3_close()" class="w3-bar-item w3-button w3-hover-dark-grey">Doki Doki Literature Club</a>
        </li> -->
        <li class="w3-padding-16">
          <a href="./simulation/theStanleyParable.html" onclick="w3_close()" class="w3-bar-item w3-button w3-hover-dark-grey">The Stanley Parable</a>
        </li>
        <li class="w3-padding-16">
          <a href="./simulation/papersPlease.html" onclick="w3_close()" class="w3-bar-item w3-button w3-hover-dark-grey">Papers, Please</a>
        </li>
        <li class="w3-padding-16">
          <a href="./simulation/mgs2.html" onclick="w3_close()" class="w3-bar-item w3-button w3-hover-dark-grey">Metal Gear Solid 2</a>
        </li>
      </ul>
    </div>
  </div>

  <!-- The Team -->
  <div class="w3-row-padding w3-grayscale" style="margin-top:25px">
    <h1 class="w3-xxxlarge w3-text-deep-purple"><b>The Team:</b></h1>
    <div class="w3-col m4 w3-margin-bottom">
      <div class="w3-light-grey">
        <div class="w3-container">
          <h3>Jeremy Bers</h3>
          <p class="w3-opacity">2nd Year ME Major</p>
          <p>Limbo / Papers, Please</p>
        </div>
      </div>
    </div>
    <div class="w3-col m4 w3-margin-bottom">
      <div class="w3-light-grey">
        <div class="w3-container">
          <h3>Daniel Ibarra </h3>
          <p class="w3-opacity">4th Year LMC Major</p>
          <p></p>
        </div>
      </div>
    </div>
    <div class="w3-col m4 w3-margin-bottom">
      <div class="w3-light-grey">
        <div class="w3-container">
          <h3>James Johnson</h3>
          <p class="w3-opacity">3rd Year CS Major (Intelligence/Devices)</p>
          <p>Spec Ops: The Line / Super Hot</p>
        </div>
      </div>
    </div>
    <div class="w3-col m4 w3-margin-bottom">
      <div class="w3-light-grey">
        <div class="w3-container">
          <h3>Lucas Liu</h3>
          <p class="w3-opacity">4th Year CS Major (Intelligence/Media)</p>
          <p>Nier Automata</p>
          <p class="w3-opacity"></p>
          <p></p>
        </div>
      </div>
    </div>
    <div class="w3-col m4 w3-margin-bottom">
      <div class="w3-light-grey">
        <div class="w3-container">
          <h3>Zhaoran Ma</h3>
          <p class="w3-opacity">2nd Year CS Major (Intelligence/People)</p>
          <p>What Remains of Edith Finch / Sky</p>
          <p class="w3-opacity"></p>
          <p></p>
        </div>
      </div>
    </div>
    <div class="w3-col m4 w3-margin-bottom">
      <div class="w3-light-grey">
        <div class="w3-container">
          <h3>Audrey Yarmowich</h3>
          <p class="w3-opacity">4th Year CS Major (Media/Info)</p>
          <p>Minecraft / The Stanley Parable</p>
        </div>
      </div>
    </div>
  </div>

  <!-- Packages / Pricing Tables -->
  <!-- <div class="w3-container" id="packages" style="margin-top:75px">
    <h1 class="w3-xxxlarge w3-text-deep-purple"><b>Packages.</b></h1>
    <hr style="width:50px;border:5px solid rgb(106, 90, 205)" class="w3-round">
    <p>Some text our prices. Lorem ipsum consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure</p>
  </div> -->


  
  <!-- Contact -->
  <!-- <div class="w3-container" id="contact" style="margin-top:75px">
    <h1 class="w3-xxxlarge w3-text-deep-purple"><b>Contact.</b></h1>
    <hr style="width:50px;border:5px solid rgb(106, 90, 205)" class="w3-round">
    <p>Do you want us to style your home? Fill out the form and fill me in with the details :) We love meeting new people!</p>
    <form action="/action_page.php" target="_blank">
      <div class="w3-section">
        <label>Name</label>
        <input class="w3-input w3-border" type="text" name="Name" required>
      </div>
      <div class="w3-section">
        <label>Email</label>
        <input class="w3-input w3-border" type="text" name="Email" required>
      </div>
      <div class="w3-section">
        <label>Message</label>
        <input class="w3-input w3-border" type="text" name="Message" required>
      </div>
      <button type="submit" class="w3-button w3-block w3-padding-large w3-deep-purple w3-margin-bottom">Send Message</button>
    </form>  
  </div> -->

<!-- End page content -->
</div>

<!-- W3.CSS Container -->
<div class="w3-light-grey w3-container w3-padding-32" style="margin-top:75px;padding-right:58px"><p class="w3-right"></a></p></div>

<script>
// Script to open and close sidebar
function w3_open() {
  document.getElementById("mySidebar").style.display = "block";
  document.getElementById("myOverlay").style.display = "block";
}
 
function w3_close() {
  document.getElementById("mySidebar").style.display = "none";
  document.getElementById("myOverlay").style.display = "none";
}

Modal Image Gallery
function onClick(element) {
  document.getElementById("img01").style = "argin-bottom:-6px;margin-top:16px;opacity:0.";
  // document.getElementById("replace").style.display = "block";
  var captionText = document.getElementById("caption");
  captionText.innerHTML = element.alt;

}
</script>

</body>
</html>
