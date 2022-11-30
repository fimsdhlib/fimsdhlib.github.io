---
layout: post
title:  "Documentation: Recognito"
categories: [ DH, documentation, recognito ]
image: assets/images/5.jpg
author: Kaeleigh

---
<style>
* {box-sizing: border-box}
body {font-family: "Lato", sans-serif;}

h3 {
    margin-top: 1rem !important;
}
/* Style the tab */
.tab {
  float: left;
  border: 0px solid #ccc;
  background-color: #f1f1f1;
  width: 25%;
  height: auto;

}

/* Style the buttons inside the tab */
.tab button {
  display: block;
  background-color: inherit;
  color: black;
  padding: 22px 7px;
  width: 100%;
  border: none;
  outline: none;
  text-align: left;
  cursor: pointer;
  transition: 0.6s;
  font-size: 17px;
}

/* Change background color of buttons on hover */
.tab button:hover {
  background-color: rgb(253,217,61);
}

/* Create an active/current "tab button" class */
.tab button.active {
  background-color: rgb(253,217,61);
}

/* Style the tab content */
.tabcontent {
  float: left;
  padding: 0px 10px;
  border: 0px solid rgb(253,217,61);
  width: 75%;
  border-left: none;
  height: auto;

}
</style>

<body>

<div class="tab btn">
  <button type="button" class="tablinks" onclick="openCity(event, 'London')" id="defaultOpen">What is Recognito?</button>
  <button class="tablinks" onclick="openCity(event, 'Paris')">Getting Started</button>
  <button class="tablinks" onclick="openCity(event, 'Tokyo')">Features</button>
   <button class="tablinks" onclick="openCity(event, 'Tokyo')">Examples</button>
</div>

<div id="London" class="tabcontent">
  <h3>What is Recognito?</h3>
  <p>Recogito is an open-source software developed by the Pelagios Network. It is an annotation tool that allows users to add annotations to text, image, or spreadsheet files.

Recogito can be accessed at: <a href="https://recogito.pelagios.org/">https://recogito.pelagios.org/</a>

</p>
</div>

<div id="Paris" class="tabcontent">
  <h3>Getting Started</h3>
  <p>To begin using Recogito, you must create an account. Register with Recogito by entering a username, email address, and password to gain access to the workspace.</p> 

  <img src="https://raw.githubusercontent.com/fimsdhlib/fimsdhlib.github.io/main/assets/images/macphail-1.png">

<sup>Fig.1 Account setup.</sup>

<p>Once you have verified your account and signed in, Recogito will re-direct you to your personal workspace.</p>

  <img src="https://raw.githubusercontent.com/fimsdhlib/fimsdhlib.github.io/main/assets/images/macphail-2.png">

<sup>Fig.2 Adding a file</sup>

<p>Add a new text, image, or spreadsheet file by clicking on the New button. Accepted file formats include .txt, .xml, and .csv (must be UTF-8 character encoded), as well as JPEG, TIFF, and PNG images.</p>

<p>In the drop-down menu, select File upload and navigate to the desired file in the file browser to upload it. Your new file will appear under My Documents. Double-click it to open the Document view. You can now add annotations to your file.</p>
<h4>Adding Annotations to Text</h4>
<p>Highlight the word or phrase you want to annotate. A pop-up will appear, allowing you to categorize the selected text as a Place, Person, or Event, as well as add comments and/or tags. To edit or delete an annotation, click the arrow in the top right corner of the pop-up.</p>
  <img src="https://raw.githubusercontent.com/fimsdhlib/fimsdhlib.github.io/main/assets/images/macphail-3.png">

<sup>Fig.3 Adding an annotation to a word</sup>
<h4>Adding Annotations to Images</h4>
<p>Annotations can be added to images as a Point, Rectangle, Tilted Box, or Linked Box. Select Move in the Tools bar and use the scroll on your mouse or the +/- buttons to navigate the image. Then select the appropriate annotation method (e.g., Point) and double-click on the image to add an annotation.</p>
  <img src="https://raw.githubusercontent.com/fimsdhlib/fimsdhlib.github.io/main/assets/images/macphail-4.png">

<sup>Fig.4 Automatic georeferencing</sup>
</div>

<div id="Tokyo" class="tabcontent">
  <h3>Features</h3>
  <p>The main navigation bar features the document view, map view, annotation statistics, download options, and document settings.</p>
    <img src="https://raw.githubusercontent.com/fimsdhlib/fimsdhlib.github.io/main/assets/images/macphail-5.png">

<sup>Fig.5 Main navigation bar</sup>

<h4>Map view</h4>
<p>If an annotation is identified as a Place, it will be added to the Map view.</p>
  <img src="https://raw.githubusercontent.com/fimsdhlib/fimsdhlib.github.io/main/assets/images/macphail-6.png">

<sup>Fig.6 An identified place entity</sup>

<p>You can click on Map view to view all the annotated Places on the map.</p>

  <img src="https://raw.githubusercontent.com/fimsdhlib/fimsdhlib.github.io/main/assets/images/macphail-7.png">

<sup>Fig.7 All place entities will be included in the map view</sup>
</div>

<script>
function openCity(evt, cityName) {
  var i, tabcontent, tablinks;
  tabcontent = document.getElementsByClassName("tabcontent");
  for (i = 0; i < tabcontent.length; i++) {
    tabcontent[i].style.display = "none";
  }
  tablinks = document.getElementsByClassName("tablinks");
  for (i = 0; i < tablinks.length; i++) {
    tablinks[i].className = tablinks[i].className.replace(" active", "");
  }
  document.getElementById(cityName).style.display = "block";
  evt.currentTarget.className += " active";
}

// Get the element with id="defaultOpen" and click on it
document.getElementById("defaultOpen").click();
</script>
   
</body>
   