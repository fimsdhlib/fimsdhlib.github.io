---
layout: post
title:  "Documentation: Recognito"
categories: [ DH, documentation, recognito ]
image: assets/images/1.jpg
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
   <button class="tablinks" onclick="openCity(event, 'Toronto')">Examples</button>
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

<h4>Annotation Statistics</h4>
<p>Annotation statistics will give you an insight into activity levels, entities such as Places, and tag use within the document.</p>
  <img src="https://raw.githubusercontent.com/fimsdhlib/fimsdhlib.github.io/main/assets/images/macphail-8.png">

<sup>Fig.8 Dashboard</sup>

  <h4>Download Options</h4>
<p>Annotations and geo-located places can be downloaded in a variety of formats, including CSV, JSON-LD, RDF/Turtle, RDF/XML, GeoJSON, KML, TEI/XML, Markdown, IOB, and Spacy. Note, some of these exporters are currently in a beta phase.</p>

  <h4>Document Settings</h4>
<p>In the Document settings, metadata can be added to the document and the annotation preferences can be updated. Users can also view the edit history, download a backup package (in a ZIP file), or delete the document. Additionally, public access can be enabled and collaborators can be added through the Sharing menu. To add a collaborator, type their username into the search bar. You can then choose the level of access granted to the collaborator:
<ul>
<li>Read: Does not grant editing permissions, but allows the collaborator to view the document.</li>
<li>Write: Allows collaborator to view the document and add annotations.</li>
<li>Admin: Allows collaborator to view the document, add annotations, and perform administrative tasks (such as editing document metadata).</li>
</ul>
</p>
</div>

<div id="Toronto" class="tabcontent">
  <h3>Examples</h3>
  <h4>Example 1: Named Entity Recognition</h4>
  <p>While many of Recogito’s tools are designed to aid users in adding annotations manually, this method of annotating can be time-consuming. Recogito also offers Named Entity Recognition (NER) algorithms to automatically annotate text. This feature can be useful when analysing large quantities of cultural data.

This example will demonstrate how to use NER in Recogito. We will start by uploading a text file of Pride and Prejudice by Jane Austen.
</p>
<ol>
<li>In your personal workspace, click the New button then select From RISE Repository.</li>
<li>Scroll down and click on the MPIWG – A Multilingual Data Set of Novels collection.</li>
<li>Type “pride” into the search bar and click Search. <br>  <img src="https://raw.githubusercontent.com/fimsdhlib/fimsdhlib.github.io/main/assets/images/macphail-9.png"></li>
<li>Select the resource named “Prideand Prejudice” and check the box under Sections. Click the Load button in the upper right corner. It may take several minutes to upload.</li>
<li>Once uploaded, the new text file will appear under My Documents. Click it once to select it and open the Options drop-down menu. Choose Named Entity Recognition.<br><img src="https://raw.githubusercontent.com/fimsdhlib/fimsdhlib.github.io/main/assets/images/macphail-10.png"></li>
<li>For the purposes of this example, we will use the Stanford CoreNLP (en) engine to perform the NER analysis. Select it from the list of Recognition Engines then scroll down and click Start NER. This may take several minutes.</li>
<li>Once the analysis is complete, double-click on the Pride and Prejudice text file to open it. Approximately 4184 annotations should be added, including names of people and places. Scroll down the document and select an annotation to view its details. <br> <img src="https://raw.githubusercontent.com/fimsdhlib/fimsdhlib.github.io/main/assets/images/macphail-11.png"></li>

</ol>

<h4>Example 2: Relatons</h4>
  <p>Relations can be used to make connections between annotations. This can be useful for making connections between people, places, and/or events within the cultural data. The following example will demonstrate how to add Relations and export them as a CSV node and edge list which can be visualized using the software Gephi. If you wish to complete steps 7-9 of the example, ensure Gephi is installed on your computer (https://gephi.org/users/download/).
</p>
<p>For this example, we will continue using the Pride and Prejudice text file that was annotated using NER in Example 1 (please complete Example 1 before proceeding with this example).</p>

<ol>
<li>In your workspace, double-click the Pride and Prejudice text file under My Documents to open it.</li>
<li>On your keyboard, press CTRL+F and type “Lizzy” into the search box. Go to the first instance of the name.</li>
<li>In the Annotation mode bar, select Relations.</li>
<li>Select the first instance of “Lizzy” then select the name “Jane”. Type “Sisters” into the box that appears. Click the checkmark to save. <br><img src="https://raw.githubusercontent.com/fimsdhlib/fimsdhlib.github.io/main/assets/images/macphail-12.png"></li>
<li>In the main navigation bar, choose Download options.</li>
<li>Scroll down and download the Basic CSV file under the Relations heading.</li>
<li>Open Gephi. Select File > Open and navigate to the downloaded CSV file to open it.</li>
<li>In the import menu, click Next and Finish. <br> <img src="https://raw.githubusercontent.com/fimsdhlib/fimsdhlib.github.io/main/assets/images/macphail-13.png"></li>
<li>The network showing the relationship between Lizzy and Jane will appear in the window. <br> <img src="https://raw.githubusercontent.com/fimsdhlib/fimsdhlib.github.io/main/assets/images/macphail-14.png"></li>

</ol>


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
   