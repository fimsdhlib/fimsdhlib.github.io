---
layout: post
title:  "Tool Review: Twine"
categories: [ DH, tutorial, twine, storytelling, interactive ]
image: assets/images/1.jpg
author: Tash

---
In its own words, Twine is an “open-source tool for telling interactive, nonlinear stories.” (Twine, 2022). The program is primarily used by authors to write, code, and independently publish interactive fiction with customizable options and branching storylines. This open access program was created by Chris Klimas in 2009 to give interactive fiction authors complete creative control over publishing their work. It is trademarked by the registered nonprofit Interactive Fiction Technology Foundation.

For context, I am a complete Twine novice and only have a very basic understanding of HTML coding. However, I am an avid reader of Twine-based stories so I have some understanding of what the program can do. I also know that Twine has a thriving community of authors who share tutorials, UI templates, and coding advice for free online, but it can be hard to find these resources if you aren’t already familiar with the community.

To test Twine’s functionality and use as a transformative literary tool, I used the program to create a version of Sherlock Holmes: The Adventure of the Speckled Band that allows readers to customize the names and pronouns of Holmes and Watson. The HTML file is linked at the bottom of this review and can be opened in any browser.

Mainly, I was interested in the ability of the program’s find and replace tool to switch desired text with a variable code that would allow user input. I believe this is one of the main ways that Twine can be used in Digital Humanities projects to create or adapt literature as a collaborative, transformative experience.

This public domain text was chosen to explore how Twine could be used to experience literature and literary themes through different lenses. In Speckled Band, Holmes is particularly sympathetic and knowledgeable of the signs of domestic abuse, so the ability to customize Holmes' gender, pronouns, and name allows readers to explore the themes of this classic story from a feminist and/or queer lens.


## Beginner Guides

Through its home page, Twine can be downloaded onto multiple operating systems (for this review, I used the Windows desktop app). There is also a browser-based version of Twine that requires no account and features the same UI as the app.

Twine’s home page suggests beginners start with its linked Reference guide. This guide goes over the basic functions of building a story in Twine clearly and thoroughly, with straightforward headers that make for easy navigation. Twine also suggests a ‘Cookbook’ with more advanced advice, though I found it had less intuitive headers and more complex language. Both manuals are entirely text-based, which can make learning how to use a very visual UI rather challenging. For a coding beginner, the primary learning curve was very steep.


## User interface & Getting Started

Twine primarily works by writing text passages with can then be linked on a grid. The text inside each passage includes both the prose and code blended together. However, learning what code functions you can include in your story is quite difficult to begin with – it requires reading the Reference guide closely and returning to it regularly. 

Other UI features include a colour-coded tagging system for easy navigation, a CSS stylesheet, and a javascript window for adding custom functions.

<img src="https://github.com/fimsdhlib/fimsdhlib.github.io/blob/main/assets/images/thawk-1.PNG?raw=true">

<sup>Figure 1. Twine UI of a new story with linked passages.</sup>

<img src="https://github.com/fimsdhlib/fimsdhlib.github.io/blob/main/assets/images/thawk-2.PNG?raw=true">

<sup>Figure 2. A passage with a mix of HTML, Sugarcube variables, and basic text.</sup>

The most trouble I had at this early stage was parsing the difference between Twine’s four custom coding languages – Harlowe, Chapbook, Snowman, Sugarcube - and deciding which to use. Twine’s reference guides do not explain the languages well and only give a few bare bones examples. After much research, I learned that Harlowe and Chapbook mainly support basic functions while Sugarcube allows for more complexity and the use of macros. Since all the community resources I came across use Sugarcube, that’s the language I ultimately used. (The elusive Snowman remains a mystery).

## Advanced Functions

As an avid reader of Twine stories, I know of the more complex functions it can support – especially customization and story variables. These functions were unfortunately beyond Twine’s basic Reference guide, but the plethora of community-written tutorials were very valuable for adding the functions I needed. Authors’ personal and development blogs are the best place to start as they are often directly linked on any published story’s main page. Here I also found many excellent free templates with pre-loaded CSS and javascript to help make my projects UI’s much cleaner.

<img src="https://github.com/fimsdhlib/fimsdhlib.github.io/blob/main/assets/images/thawk-3.PNG?raw=true">

## Find and Replace Tool

The functionality of the find and replace tool was ultimately disappointing. The tool only allows users to replace all instances of the desired text without previews or context (or even advanced options to take account of things like capitalization). Since Holmes and Watson are not the only characters who use he/him pronouns in the story the tool supplied many false positives without any way to manually approve the change for only some instances. I quickly abandoned the tool in favour of manually adding the variable codes myself.

## Overall Impressions

Unfortunately, the find and replace tool was not advanced enough for confident or accurate use, so users should expect to add variable coding manually. Despite this setback (and despite the steep learning curve early on), with experience Twine’s UI has an intuitive flow and the visual grid makes it easy to sort and navigate a project. I recommend the reference guide as a good place for beginners, but intermediate users looking for more advanced coding functions may be disappointed with Twine’s official support pages. In that case, Twine’s best resource is the many community resources shared between authors online. Ultimately, Twine is a lightweight program that can support transformative literary projects if you know where to look for resources and are able to put in some manual work to make it shine.

## Example

<div>
    <iframe src="https://fimsdhlib.github.io/assets/int/tash-twine.html" height="700px" width="100%" allowfullscreen="" frameborder="0">
    </iframe>
</div>

## References

Doyle, A. C. (2022). Adventure 8: “The Adventure of the Speckled Band”. Lit2Go. (Original work 
published 1892). https://etc.usf.edu/lit2go/32/the-adventures-of-sherlock-holmes/352/adventure-8-the-adventure-of-the-speckled-band/

Twine. (2022). Twine is an open-source tool for telling interactive, nonlinear stories. 
https://twinery.org/

Twine. (n.d.a). Twine Cookbook. https://twinery.org/cookbook/

Twine. (n.d.b). Twine Reference. https://twinery.org/reference/en/
