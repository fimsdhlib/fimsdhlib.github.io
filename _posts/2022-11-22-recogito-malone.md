---
layout: post
title:  "Tool Review: Recogito"
categories: [ DH, review, recognto, gazetteer, ner, entity recognition ]
image: assets/images/5.jpg
author: Toby

---
This tool review  focuses on a useful digital annotation tool called Recogito.

### 1) A short description/context of the tool, where it originated, how it was created and by whom, development status
According to the Recogito “About” page, the project “is an initiative of the Pelagios Network, developed under the leadership of the Austrian Institute of Technology, University of Exeter and The Open University, with funding from the Andrew W. Mellon Foundation” (“About”), led by Leif Isaksen of the University of Exeter. Pelagios is a wide-ranging DH initiative that lends its tools and corpus to user-friendly annotations of text, of which Recogito is a flagship example. Built on extensive global authority files (or ‘Gazetteers’), Pelagios (and thus Recogito) is focused on linked annotation connected to a core lexicon, and focuses on “six core Activities in order to sustain and further develop work in linking historical documents and cultural heritage through common references to places”: annotation, collaboration, gazetteers, pedagogy, registry, and visualisation (“Activities”).

The tool was first developed (promoted as “Semantic Annotation without the pointy Brackets” [Github]) in 2016, launched in pre-release on October 13 of that year and in full on March 3, 2017. There have been eight updates to the program in the meantime, with the most recent (version 3.3) launching on September 12, 2019. It is freely available in its initial format, and is best utilised for geotagging and nametagging within text documents. Recogito also encompasses other developments such as Annotorious (a JavaScript library for image annotation), Recogito-JS (a JavaScript library for text annotation), and OpenSeadragon (a plugin for annotating high-res zoomable images), but this evaluation will focus on the original Recogito.


### 2) A short description of what the tool is meant to do; what doors does it open for scholarly pursuits; and if it is unique in that regard
Recogito is a tool that allows users to upload text to a free web-based platform, and to add metadata and annotations (fig.1)), which will remain embedded in the document when saved and re-uploaded or deployed in another context, such as on a website or project. Users can add extensive metadata to the document as a whole, as well as granular tagging, broken down by the controlled vocabulary of name, place, and event. So, if a user uploads a .txt file containing the St. Crispin’s Day speech from Henry V (IV.iii), the user may use the tool to identify names (“Bedford”, “Exeter”, as noted to the right), places (“Agincourt”), and events (“The Battle of Agincourt”, “St. Crispin’s Day”). The user can manually flag each relevant word to add a person/place/event tag to the term, and in the case of recurring words (“Bedford,” for example), Recogito prompts the user through Named Entity Recognition about whether they would like all additional instances to be similarly tagged. Interestingly, the geotagging element means that when a placename is tagged, Recogito offers a georesolving function built on a series of gazetteer authorities, which may be toggled between.

<img src="https://raw.githubusercontent.com/fimsdhlib/fimsdhlib.github.io/main/assets/images/malone-1.png">

<sup>Fig.1 Metadata for annotations.</sup>

<img src="https://raw.githubusercontent.com/fimsdhlib/fimsdhlib.github.io/main/assets/images/malone-2.png">

<sup>Fig.2 Additional comments.</sup>

<img src="https://raw.githubusercontent.com/fimsdhlib/fimsdhlib.github.io/main/assets/images/malone-3.png">

<sup>Fig.3 Additional georesolvers.</sup>

The mapping function works to detect the best possible match for the tagged keyword, and shows not only a geographical representation but also links to the selected gazetteers associated with the file (left, as we see Paris tagged with an Ancient Roman gazetteer for Henry VI Part One). Names, places, and events are colour-tagged for at-a-glance reference, and the use of automatically generated repeat tags mean that the user may tag a lengthy document in a very short amount of time.

<img src="https://raw.githubusercontent.com/fimsdhlib/fimsdhlib.github.io/main/assets/images/malone-4.png">

<sup>Fig.4 Mapping functions of place entities.</sup>

Recogito offers a simple interface and quick results, particularly in humanities projects which require a great deal of tagging. There are many data labeling tools available, such as Datasaur and Scale, but the manual nature of Recogito (along with the automated tag predictors), and its status as an Open Source software makes this very attractive. This can be used in a low-level metadata addition manner, or can be used to help tag a large document as part of a wider coding process. It’s certainly a tool I would have liked access to when tagging playtexts in the past.


### 3) A critical review of its function, considering elements such as: functionality and accessibility; performance; learning curve; documentation and additional support material; application; possible use cases (in the classroom or for research).

As a web-based platform, Recogito is very accessible. Account set-up is straightforward and the page’s Help section includes a useful set of YouTube videos which serve as a tutorial. The channel offers tutorials for both the beginner and the expert, which encourages user comfort with the tool. A major point of frustration, however, was the finicky nature of Recogito’s file management. It took me a couple of tries (and digging around in the FAQ section) before I realised that Recogito only accepts a limited list of file types (.txt, .xml, .JPEG, .TIFF, and .PNG, with Beta functionality on .IIIF and .CSV files). Not only this, but when uploading files, the “unsupported or unknown file format” error was more than often replaced by an “unknown or unsupported text encoding” error, even on files in .txt and .xml formatting. The UX of this error reporting system is very frustrating, with little guidance or advice about how to navigate it on what should be an accepted file or format. Once files are uploaded, tagging is simple and shortcuts allow for a great deal of progress in a short amount of time. I found it frustrating that .csv files could only be tagged by the individual cell, rather than the words within it, and navigation in this format was overall much less functional.

<img src="https://raw.githubusercontent.com/fimsdhlib/fimsdhlib.github.io/main/assets/images/malone-5.png">

<sup>Fig.5 Tagging a csv.</sup>

Despite these disadvantages (I won’t say they’re minor, because they drastically reduced the usability of this tool once I realised what it could not handle), this is a tool that takes a great deal of the heavy lifting out of text tagging and annotation. This would be a useful tool to run data through before publishing, building in semantic annotation in an easy to navigate setting. In addition, more advanced users may adjust their annotation preferences, which includes the option to select the gazetteers that are used (as noted above), or by adding a tagging vocabulary to ensure that the programme does not flag complex, uncommon words (such as we might find in foreign-language or early modern texts). 

<img src="https://raw.githubusercontent.com/fimsdhlib/fimsdhlib.github.io/main/assets/images/malone-6.png">

<sup>Fig.6 Adding additional tagging vocabulary.</sup>

Users have the opportunity to further tag their material with relationships between individuals (such as we see to the left, in the Player’s story of Priam and Hecuba), which offers a tagging sophistication that the user may choose to make public if so desired. This public tagging displays the annotations, maps, statistics, and allows for other users to download.

<img src="https://raw.githubusercontent.com/fimsdhlib/fimsdhlib.github.io/main/assets/images/malone-7.png">

<sup>Fig.7 Entity relationships.</sup>

Use cases for this product would include digital editorial work and tagging of named entities, particularly in regard to working towards TEI markup. Overall, this is a useful tool with an attractive interface. I would have been happier to use this with a little more guidance on error messaging (since as far as I could see the files I was attempting to upload were valid), but as a free means of demystifying tagging without asking a user to wade into the “pointy brackets” of XML or TEI, this is a nice middle ground for DHers who aren’t into the coding side of things but still need to lay tags. 


## Works Cited

“Recogito: About.” https://recogito.pelagios.org/help/about 

“Recogito: Activities.” https://pelagios.org/activities/ 

“Recogito: Frequently Asked Questions.” https://recogito.pelagios.org/help/faq 

“Recogito: Github.” https://github.com/pelagios/recogito2 

Shakespeare, William. The Internet Shakespeare Editions. https://internetshakespeare.uvic.ca/  
