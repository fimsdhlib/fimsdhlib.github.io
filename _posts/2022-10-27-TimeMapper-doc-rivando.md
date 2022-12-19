---
layout: post
title:  "Documentation: TimeMapper"
categories: [ DH, documentation, TimeMapper ]
image: assets/images/9.png
author: Ryan

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
  <button type="button" class="tablinks" onclick="openCity(event, 'London')" id="defaultOpen">Introduction</button>
  <button class="tablinks" onclick="openCity(event, 'Paris')">Getting Started</button>
  <button class="tablinks" onclick="openCity(event, 'Tokyo')">Features</button>
   <button class="tablinks" onclick="openCity(event, 'Toronto')">Examples</button>
</div>

<div id="London" class="tabcontent">
  <h3>What is TimeMapper?</h3>
  <p><a href="https://timemapper.okfnlabs.org/">TimeMapper</a> is an open-source web tool that allows users to visualise data in an interactive map, timeline, and info panel. Images, dates, text, and geolocation are all customizable and a template spreadsheet provided by TimeMapper makes it easy to prepare data for upload. This tool is very accessible as it is browser-based and requires no installation or specialised hardware. 
</p>
</div>

<div id="Paris" class="tabcontent">
  <h3>Getting Started</h3>
  <p>As mentioned, no software needs to be installed on your computer to use TimeMapper. All data is prepared in Google Sheets and uploaded into the TimeMapper browser interface where editing and customization can be completed.</p>

<p>Creating a Google account is necessary to use Sheets, which is free and can be done <a href="https://accounts.google.com/signup/v2/webcreateaccount?flowName=GlifWebSignIn&flowEntry=SignUp">here</a>. Further, a TimeMapper account is not necessary but is recommended. Proceeding without an account will result in your project being created anonymously and comes with less control once your project is published. Projects created within a TimeMapper account allow the user to delete, edit, and organise their projects, and allow the user to personalise the URL for the project. You can create an account and log in using your Twitter.</p>

<p>To access the Google Sheets template created by TimeMapper see <a href="https://docs.google.com/spreadsheets/d/1LlYBnfhvD3ZUXMGZ8e52UwYp-xn_NeWmaGBx7VBz5V8/edit#gid=0">here</a>. Save a copy to your Google Drive so you know everything is saved and accessible in the future. There are instructions below on how to do this. Also, there are instructions at the top of each column, read them for notes on inputting data. 
</p> 
</div>
<div id="Tokyo" class="tabcontent">
  <h3>Features</h3>

<h4>Maps</h4>
<ul>
<li>Include pinned locations with tags using geodata (longitude and longitude).</li>
<li>Create boundaries using GeoJSON objects (creates an outline around an area).</li>
<li>Maps are interactive, users can zoom in and out, move, and reveal information by clicking points.</li>
</ul>

<h4>Timeline</h4>
<ul>
<li>Dates can be plotted on the timeline (Eg. Prolonged events such as a person's lifespan, or a single day).</li>
<li>The timeline is interactive, allowing the user to scroll, zoom, and interact with the nodes and events.</li>
</ul>

<h4>Information Panel</h4>

<ul>
<li>Present images, text, dates, tags, and more.</li>
<li>This window scrolls page to page and is coordinated with the timeline and map.
</li>
</ul>

</div>

<div id="Toronto" class="tabcontent">
  <h3>Examples</h3>
  <h4>First Steps</h4>
  <p>Once you have decided to log in or work anonymously, you can start by viewing the Google Sheets <a href="https://docs.google.com/a/okfn.org/spreadsheet/ccc?key=0AqR8dXc6Ji4JdFRNOTVYYTRqTmh6TUNNd3U2X2pKMGc#gid=0">template</a> provided by TimeMapper. First, it is best to add a shortcut of the template to your Google Drive and then save a copy, which will allow you to edit.</p>

  <p>Add a shortcut to your Drive: File> Add a shortcut to Drive> Select the location in Drive and click Add Shortcut.</p>

  <p>Make a copy to edit: File> Make a copy> Change the file name, select the folder you want to save it in and click Make a copy.</p>
  <img src="https://raw.githubusercontent.com/fimsdhlib/fimsdhlib.github.io/main/assets/images/rivando-2-1.PNG">
  <p>This is now the file that you can use for this project. Each time you start a new project make a copy of
the original and rename it.</p>

<h4>Create a Simple Map</h4>
<p>Using the Google Sheets template from TimeMapper, you can choose to only input certain details
that pertain to the map or timeline. In this example, only the Title and Location are essential to
creating a basic map with pinned locations.</p>

<p>See the spreadsheet we will use below.</p>
  <img src="https://raw.githubusercontent.com/fimsdhlib/fimsdhlib.github.io/main/assets/images/rivando-2-2.PNG">
<p>For historic sites, research may be needed to find accurate geographic information. For this project,
the coordinates were found on Wikipedia. The simplest way to find most modern coordinates is via
Google Maps. See below.</p>

<ol>
<li>Open Google Maps and search the place.</li>
<li>Right-click on the marker for the place and click the longitude and longitude coordinates. The
coordinates are now copied.</li>
<li>Paste them into the spreadsheet under the Location column.</li>
</ol>
  <img src="https://raw.githubusercontent.com/fimsdhlib/fimsdhlib.github.io/main/assets/images/rivando-2-3.PNG">

<p>Once data input is complete it is time to prepare for uploading the spreadsheet to TimeMapper. First,
you need to publish the spreadsheet to the web. This will make the data in the spreadsheet viewable
by TimeMapper.</p>

<p>To do this: File> Share> Publish to web> click Publish> then copy the link provided.</p>
  <img src="https://raw.githubusercontent.com/fimsdhlib/fimsdhlib.github.io/main/assets/images/rivando-2-4.PNG">

<p>Now let’s move over to TimeMapper and put this data to use.</p>
<ol>
<li>Sign in (if you choose to).</li>
<li>Paste the link to your spreadsheet next to Data Source.</li>
<li>Type in your page title and (if you’re signed in) the URL you would like to use.</li>
<li>Select the data view. In this case, we want to select Map.</li>
<li>Click Publish.</li>
</ol>

  <img src="https://raw.githubusercontent.com/fimsdhlib/fimsdhlib.github.io/main/assets/images/rivando-2-5.png">

<p><a href="https://timemapper.okfnlabs.org/rrrivando/maponly#2">Here</a> is a link to what we created. Easy right?</p>

<h4>A Full Project</h4>
  <p>The next example will show the full breadth of TimeMapper. For the most part the process is the
same, there are just a couple of extra things to be mindful of. They are:
</p>
<p>Date Format</p>
<ul>
<li>mm/dd/yyyy OR dd/mm/yyyy are acceptable. Be consistent and be sure to select the format
you used in the customising menu.
</li>
<li>Are you only putting in the year? For dates that occurred BCE include a “-” symbol before the
year (eg. -1200, not 1200 BCE).
</li>
</ul>
<p>Start Point</p>
<ul>
<p>Where would you like the project to start? There are three options:
</p>
<li>First Event
</li>
<li>Last Event</li>
<li>Today</li>
<br>
<p>This selection will set the point in which the viewer begins.</p>
</ul>
<p><a href="https://docs.google.com/spreadsheets/d/e/2PACX-1vRi3ivqQ51OfTCl4PGtdfVsRgirKUK1HFtwfhDimxiWeNmjateEpJRWY4_Fh38x-G73cUFNz-HhxZmk/pubhtml">Here</a> is the example spreadsheet that is published to the web for this project. You’ll see that it holds
far more data and TimeMapper does an excellent job of coherently visualising this extra information.</p>

<p>Follow the same steps as above and create this project. Then take a look at how the data provided is
presented. You can see it here: <a href="https://timemapper.okfnlabs.org/rrrivando/7wondersancientworld#0">7 Ancient Wonders of the World.</a></p>

<h4>Making edits</h4>

Once the project is published there are only a few edits that can be made from within TimeMapper.
This includes changing the visualisation type, date handling, and the starting place for the timeline.
Edits to the Google Sheets document will continue to update automatically. So if data needs to be
changed or updated this can be done by editing the spreadsheet directly. The changes will be
reflected the next time the TimeMapper page is opened or refreshed.

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
   