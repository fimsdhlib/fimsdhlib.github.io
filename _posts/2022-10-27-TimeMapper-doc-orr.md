---
layout: post
title:  "Documentation: TimeMapper"
categories: [ DH, documentation, TimeMapper ]
image: assets/images/9.png
author: Adrienne
datatable: true

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
  <button class="tablinks" onclick="openCity(event, 'Tokyo')">Creating a TimeMap</button>
   <button class="tablinks" onclick="openCity(event, 'Toronto')">Walkthrough</button>
</div>

<div id="London" class="tabcontent">
  <h3>What is TimeMapper?</h3>
  <p>TimeMapper (https://timemapper.okfnlabs.org/) is a web-based tool for creating interactive timemaps, 
visualizations with three components: a point on a map; a corresponding point (or range) on a timeline; 
and a card with contextual details and images. The tool can be used to create only a timeline, or only a 
map, but the power of TimeMapper lies in its ability to combine both to tell compelling stories that 
progress through both time and space.</p>
<p>
This guide includes three sections: <strong>Getting Started</strong>, an overview of the account and data to setup 
required before using the tool; <strong>Creating a Timemap</strong>, a how-to for using the tool's various features and 
functions; and a <strong>Walkthrough</strong> with step-by-step instructions for creating and updating a timemap.
</p>
</div>

<div id="Paris" class="tabcontent">
  <h3>Getting Started</h3>
  <h4>Account Setup</h4>
  <strong>Twitter Account</strong>
  <p>Linking TimeMapper with a Twitter account allows you to save your projects to your account, update 
their settings, and create unique, personalized URLs. You can create timemaps anonymously, but they 
will not be as customizable, and settings cannot be modified once the visualization is published. </p>

<p>Log in here: https://timemapper.okfnlabs.org/account/login</p>
  <strong>Google Account</strong>
<p>You will need a Google Account to create, modify, and publish the Google Sheets spreadsheet required 
to generate a timemap. Visualizations may be generated from pre-published spreadsheets, such as the 
sample provided by TimeMapper (here) or the example provided in the Walkthrough below. However, if 
using a spreadsheet you cannot edit data, you will not have control over the content of your timemap.</p>

<p>Log in here: https://docs.google.com/spreadsheets</p>
<h4>Data Setup</h4>

<p>Make a copy of the <a href="https://docs.google.com/spreadsheets/d/1LlYBnfhvD3ZUXMGZ8e52UwYp-xn_NeWmaGBx7VBz5V8/edit#gid=0">TimeMapper spreadsheet template</a> and save it to your Google Sheets workspace.
Rename the spreadsheet for your project and begin filling in your data. Each row represents an entry in 
your timemap, with a column for each element populating the map, timeline, and / or event card. 
The chart below explains the purpose of each column, and where and how the information will be 
displayed in your visualization; required columns are marked with an asterisk.</p>

<p>The chart below explains the purpose of each column, and where and how the information will be 
displayed in your visualization; required columns are marked with an asterisk.</p>
  <img src="https://raw.githubusercontent.com/fimsdhlib/fimsdhlib.github.io/main/assets/images/orr-2-1.PNG">
<p>The TimeMapper template spreadsheet contains two sample rows: one explains the purpose of each 
column, and one provides an example of data entry. Delete both rows before generating your timemap.</p>

<p>Though every row must have data for the Title, Start, and Location fields, the rest of the spreadsheet can 
be incomplete when you connect it with TimeMapper to generate your visualization. Data can be added, 
removed, or changed directly in the spreadsheet at any time, and the visualization will be updated.</p>

<p>The spreadsheet can include more columns than those listed in the table above, but they will not be 
displayed in the visualization.</p>
</div>
<div id="Tokyo" class="tabcontent">
  <h3>Choose Your Visualization Type 
</h3>

<h4>Timemap</h4>
<ul>
<li>The Timemap visualization combines navigation through time and space with the highly visual 
storytelling of event cards, which use descriptions, images, captions, and links to external sources. Users
clicking through cards follow the progression of events in both the timeline and the map; selecting a 
point in either allows the user to jump to the card for a particular event. At minimum, your spreadsheet 
must include Title, Start, and Location fields for every row.</li>
</ul>

<h4>Timeline</h4>
<ul>
<li>The Timeline displays an interactive timeline and event cards, but does not plot these onto a map. Users 
can navigate along the timeline and through the event cards to follow the linear progression of events. 
This visualization is valuable for creating storylines that do not have a particularly relevant geographic 
component. At minimum, your spreadsheet must include Title and Start fields for every row.</li>
</ul>

<h4>Map</h4>

<ul>
<li>The Map is a static map display only. No further details about events—such as the date—are included, 
so this option is just for visualizing and labeling geographic coordinates. At minimum, your spreadsheet 
must include Title and Location fields for every row.</li>
</ul>

  <h3>Choose Your Visualization Type 
</h3>
<p>You will need a URL to import your spreadsheet to TimeMapper. This can be done in two ways. </p>
<ol>
<li>When publishing your spreadsheet, copy the link that is generated in the pop-up window.
</li>
<li>Select the File menu and Share submenu, and select the option to "Share with others". Adjust 
the settings so that anyone with a link may view the document, and copy the link.
</li>
</ol>
  <h3>Generate Your Visualization
</h3>

<p>Navigate to the TimeMapper "Create" page, here: <a href="https://timemapper.okfnlabs.org/create">https://timemapper.okfnlabs.org/create</a></p>

<p>Scroll to Section 2. Connect and Customize. You will be prompted to log in with a Twitter Account if you 
have not already done so, and additional settings will become available, as indicated in the list below.</p>

<strong>Adjust Settings</strong>
<ul>
<li>Data Source: Paste the URL to your Google Sheets spreadsheet. If the link is invalid (such as if the entire 
spreadsheet has not been published) you will get a warning and the text box will be framed in red.</li>
<li>Title: Provide a Title for your visualization webpage.</li>
<li>Slug: If you are logged in, your username will generate the first part of a unique URL linking to your 
visualization webpage. Fill in the textbox to complete the URL. It must be different from any other 
timemaps you have already created, and it cannot be changed in the settings later.</li>
<li>Type of Data View: Select one of Timemap, Timeline, or Map for your visualization. </li>
<li>Ambiguous Date Handling: Select the matching format for how you have entered data in your 
spreadsheet. </li>
<li>Start from: Select the first event, the last event, or the current date as the point in time your user will 
see first when the timeline loads.</li>
</ul>
<strong>Publish</strong>

<p>Select the "Publish" button. This will redirect you to your visualization webpage.</p>

  <h4>Edit the Content </h4>
  <p>As you review your visualization, you may notice errors in your event cards, timeline, or map. Changes 
made to information in your Google Sheets spreadsheet will update the content of the timemap. There 
is a lag time—usually at least several minutes—so allow changes a chance to sync, and then refresh your 
visualization webpage to view updates.</p>

  <h4>Edit the Visualization </h4>
  <p>Most settings available when generating the visualization can be edited after the timemap is published
to your personal account. Select the Edit option in the top right corner of your visualization webpage to: </p>
<ul>
<li>Change the data source by changing the Google Sheets spreadsheet URL</li>
<li>Update the main display title</li>
<li>Change the visualization type</li>
<li>Change how the date format in the source data is interpreted</li>
<li>Change the starting point for the timeline</li>
</ul>

  <h4>Adjust Display</h4>
  <p>The style or layout of the visualizations is largely fixed, and typically varies only based on what fields are 
completed in the spreadsheet. The user can make only superficial changes to the display for readability, 
such expanding or contracting the timeline or zooming in on the map.</p>

  <h4>Share your Visualization</h4>
  <p>You have several options available for sharing your work.</P>
  <ul>
  <li>Link: Once published, anyone with the URL to your visualization will be able to see and share it. Your 
dashboard page will have all the timemaps connected to your account. Click your username in the top 
left corner of your visualization webpage, or the person icon in the top right corner.</li>
<li>Embed: In the top right corner of the visualization webpage, select the Embed option. A pop-up window will 
display with HTML embed code to copy and paste wherever you would like to embed the timemap. </li>
<li>Tweet: In the top right corner of the visualization page, select the Tweet button. You will be taken to your 
Twitter account (or sign-in page, if you are not logged in), where you can post about the timemap.</li>
  </ul>

</div>

<div id="Toronto" class="tabcontent">
  <h3>Walkthrough</h3>
  <p>This walkthrough will demonstrate how to create and modify a timemap using the travels of the 
protagonists in Jules Verne's Around the World in 80 Days as an example.</p>

  <h4>Connect your Data</h4>
  <p>Beginning with their departure on 2 October, 1872, each of the major stops that Fogg and Passepartout 
made during their whirlwind world tour are recorded in this Google Sheets spreadsheet:
https://docs.google.com/spreadsheets/d/1595qLwJuE2-
CDZkdO3lWJBjef_x2sb35VDOxcZxCpco/edit#gid=0</p>
<p>Save a copy of the spreadsheet to your own workspace, and keep the page open.</p>

  <h4>Create your Timemap</h4>
  <p>Follow the steps in Part 2 above to do the following: </p>
<p>Save a copy of the spreadsheet to your own workspace, and keep the page open.</p>
  <ul>
  <li>Publish your spreadsheet and copy the link</li>
<li>Navigate to TimeMapper: https://timemapper.okfnlabs.org/create</li>
<li>Connect your data to TimeMapper </li>
  <li>Publish your spreadsheet and copy the link</li>
<li>Navigate to TimeMapper: https://timemapper.okfnlabs.org/create</li>
<li>Adjust the settings as follows: </li>
<ul>
<li>Add your spreadsheet link as the data source</li>
<li>Name your project (e.g., Around the World in 80 Days</li>
<li>Select Timemap as the visualization type </li>
<li>Select dd/mm/yyyy as the date format</li>
<li>Select "first event" as the starting point</li>
</ul>
<li>Publish your Visualization</li>
  </ul>
  <h4>Update your Data</h4>
  <p>Unfortunately, the spreadsheet data is incomplete: there is a character missing from this version of the 
story. When in India, Fogg and Passepartout discover that the train route between Bombay and Calcutta 
is unfinished, and they cover a stretch of that leg by elephant. Along the way, they rescue a woman, 
Aouda, and she joins their journey. To add the missing piece of the story, navigate to your spreadsheet between the fifth and sixth rows.
</p>
<img src="https://raw.githubusercontent.com/fimsdhlib/fimsdhlib.github.io/main/assets/images/orr-3-1.PNG">

<p>Row 5 is the arrival in Bombay. Row 6 is the arrival in Calcutta. Add a new row for the leg between them 
by right-clicking on Row 6 and selecting "Insert 1 row above" from the menu.</p>

<p>Fill in the following details in your new row:</p>
<img src="https://raw.githubusercontent.com/fimsdhlib/fimsdhlib.github.io/main/assets/images/orr-3-1.PNG">

  <p>Make a copy to edit: File> Make a copy> Change the file name, select the folder you want to save it in and click Make a copy.</p>
  <img src="https://raw.githubusercontent.com/fimsdhlib/fimsdhlib.github.io/main/assets/images/orr-3-2.PNG">
 
  <p>Some descriptions also need to be updated to reflect points in the story where Aouda ought to appear:
</p> <img src="https://raw.githubusercontent.com/fimsdhlib/fimsdhlib.github.io/main/assets/images/orr-3-3.PNG">

<p>These updates to your spreadsheet should be published automatically if the "Automatically republish 
when changes are made" checkbox is toggled on (see above). Allow for lag time for the changes to sync.</p>

<p>Return to TimeMapper and refresh the page. A new point will appear on the map and along the timeline 
for the added leg of the journey. Clicking either of those points will display the new event card. Use the 
arrows to navigate to the other event cards to view the remaining updates in the descriptions.</p>
<img src="https://raw.githubusercontent.com/fimsdhlib/fimsdhlib.github.io/main/assets/images/orr-3-4.PNG">

<h4>Update Images</h4>
<p>As we click through the steps in the event cards, another error stands out: the image of Fogg's arrest in 
Liverpool is mistakenly used again earlier for their stopover in Singapore.</p>
  <img src="https://raw.githubusercontent.com/fimsdhlib/fimsdhlib.github.io/main/assets/images/orr-3-5.PNG">
<p>Replace the duplicated engraving with the correct one by updating the URL for the source image. In your
Google Sheets spreadsheet:</p>
<ul>
<li>Navigate to Row 8 for the arrival in Singapore</li>
<li>Delete the URL from the Media column.</li>
<li>Add the new URL: http://gutenberg.ca/ebooks/verne-80jours/verne-80jours-00-h-dir/images/081.png
</li>
</ul>
<p>The rest of the information remains the same. Refresh TimeMapper to view the update</p>
  <img src="https://raw.githubusercontent.com/fimsdhlib/fimsdhlib.github.io/main/assets/images/orr-3-6.PNG">

<h4>Share your Timemap</h4>
  <p>It should look something like this: https://timemapper.okfnlabs.org/aoatuwo/80-days-with-aouda
</p>

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
   