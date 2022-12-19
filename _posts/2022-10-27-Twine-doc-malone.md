---
layout: post
title:  "Documentation: Twine"
categories: [ DH, documentation, Twine ]
image: assets/images/10.png
author: Toby

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
  <button type="button" class="tablinks" onclick="openCity(event, 'London')" id="defaultOpen">Getting Started</button>
  <button class="tablinks" onclick="openCity(event, 'Paris')">Features</button>
  <button class="tablinks" onclick="openCity(event, 'Tokyo')">Examples</button>
</div>

<div id="London" class="tabcontent">

  <p>Welcome to Twine, an intuitive and adaptive non-linear story creation tool ideal for generating narrative, workflow, and text-based storytelling. When you navigate to <a href="http://www.twinery.com/">www.twinery.com</a> you have the option to use this tool in either a browser-based or app-based format. The bulk of this tool’s functionality is identical between formats, but this guide is written with the app in mind as it provides greater facility for saving projects over time.</p>
  <p>When you begin at Twine, you have the option of touring through a starter guide, which includes a link to the indispensable <a href="https://twinery.org/cookbook/">“Twine Cookbook,”</a> an outstanding supplement to this documentation guide. This manual offers excellent insight into the features of Twine and is your first stop for troubleshooting any issues. In addition, Twine offers a detailed <a href="https://twinery.org/reference/en/">reference guide</a> which runs users through each element of the process step by step.</p>

<p>Even without the Twine Cookbook, however, setup is intuitive and simple. The desktop app is updated regularly (most recently August 2022) and can be downloaded for free from Github , for Linux, Mac, and PC. Once set up, Twine offers a simple menu to begin your project. Click on “+ New” to start what Twine calls a new “Story”.</p>
  <img src="https://raw.githubusercontent.com/fimsdhlib/fimsdhlib.github.io/main/assets/images/malone-3-1.png">

<p>Clicking through into a new story sets you up on a canvas, with useful guide markers that encourage your next steps. Double clicking on “Untitled Passage” sends you directly into your first story.</p>
  <img src="https://raw.githubusercontent.com/fimsdhlib/fimsdhlib.github.io/main/assets/images/malone-3-2.png">
  <p>Setup is very simple, with an attractive interface and built-in instructions. Please see the Features section for a more in-depth exploration of the User Experience in creating new stories.</p>
</div>

<div id="Paris" class="tabcontent">
<p>The primary feature of Twine is its ability to facilitate non-linear text stories. It does not host images or video, but allows creators to develop click-through stories in a number of attractive interfaces.
As noted above, when a user begins the first passage of their story, they type directly into the first box on the canvas to start to build their story, in the same way one might complete pages of a physical book, which leads to the next. The interesting thing about Twine is that it is set up to facilitate the Choose Your Own Adventure-style structure you may remember from childhood. As such, once you edit a passage (right), you can link to the following passage by placing the name of the next in double square brackets—[[…]]—which generates a link and begins the map of your project on the canvas. 
</p>
<p>Usefully, Twine does not require a passage to be created before it can be linked to: any phrase typed in double square brackets will automatically generate a connection, which allows for positive workflow. The interface displays as a series of networked nodes, linked with edges that show the direction of the story. As we can see to the left, these three passages are linked chronologically, meaning that the story can only flow in a single direction. </p>
  <img src="https://raw.githubusercontent.com/fimsdhlib/fimsdhlib.github.io/main/assets/images/malone-3-3.png">
<p>Usefully, however, stories can be complexified by adding multiple passage links, meaning the user is compelled to make a decision in order to move forward. This is useful in a workflow environment, where a user’s choices drive the information that is required.</p>
  <img src="https://raw.githubusercontent.com/fimsdhlib/fimsdhlib.github.io/main/assets/images/malone-3-4.png">
<p>In addition, once a passage has been created, opening any pair of double brackets will prompt the user to select any past passage from a drop-down menu, allowing users to return to past passages and which creates return arrows to indicate that new path. Once a user has created a series of story passages, they can run the story by clicking on the “Test from here” button, which gives a sense of what the end user will see and tests the flow. The result is a browser page—regardless of whether you are using the browser or app version—which can be customized in terms of font, size, and functionality.</p>
<img src="https://raw.githubusercontent.com/fimsdhlib/fimsdhlib.github.io/main/assets/images/malone-3-5.png">
<p>It is a simple view of the story, with links clearly delineated but few frills: indeed, Twine are quick to note in the Reference guide that there are things that Twine is “bad at”, such as “heavy use of multimedia … Online and multiplayer play … Works that involve a world model.” This is a simple interface designed for text-based, branching narratives</p>
<img src="https://raw.githubusercontent.com/fimsdhlib/fimsdhlib.github.io/main/assets/images/malone-3-6.png">
<img src="https://raw.githubusercontent.com/fimsdhlib/fimsdhlib.github.io/main/assets/images/malone-3-7.png">
<p>Other features of Twine include attractive markup languages including Harlowe 3.3.3 and Sugarcube v2 which impact the end presentation of the pages created but achieves this as a plug-in meaning users need no expertise in this language. Users can adjust the font, size, and colour of their end result, and can very quickly create stories ready for immediate deployment. Users can flip the text, insert effects, and add flourishes which change it from its simple original form.</p>
<img src="https://raw.githubusercontent.com/fimsdhlib/fimsdhlib.github.io/main/assets/images/malone-3-8.png">
<p>Experienced coders may be interested in features that include the opportunity to manipulate code at the touch of a button, but this is not necessary to the functionality of the programme.</p>
</div>
<div id="Tokyo" class="tabcontent">
<p>As noted above, Twine is clear on what it is “good” and “bad” at: its function is to provide text-based narrative, with simple functionality for branching choices. The Choose Your Own Adventure example is extremely apt: rather than asking the reader to turn to a variety of page options, clickable links do the same thing. This means that Twine is an excellent storytelling option for narrative structure. The only challenge in this kind of creation comes in the fact that it can be easy to lose track of threads to ensure that the story pushes through to the final conclusion. Dead ends are a concern, but this is mitigated with the mapping canvas that easily show orphan passages. For example, we can see how the traditional story of Little Red Riding Hood could be represented (and in turn rewritten) with reader choices: Little Red Riding Hood decides (or decides not to) visit her grandmother, and the reader chooses what she does along the way.</p>
<img src="https://raw.githubusercontent.com/fimsdhlib/fimsdhlib.github.io/main/assets/images/malone-3-9.png">
<p>Furthermore, Twine can be used to plot workflow, an extremely useful usage for training and orientation purposes. This kind of workflow can be used to guide a user through steps required to start a job, set up a programme, or navigate steps in a process. As we can see below, a mock workflow for a new user can be a valuable addition to any workplace.</p>
<img src="https://raw.githubusercontent.com/fimsdhlib/fimsdhlib.github.io/main/assets/images/malone-3-10.png">
<p>Once complete, users can publish their Twine, saved as an html file on a local drive, which can then be shared and activated with a web browser. Twine offers the ability to create, edit, archive, and tag stories, and while it struggles with graphics and large stories, for the function it offers, it is an intuitive platform that is simple to learn and navigate.</p>
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
   