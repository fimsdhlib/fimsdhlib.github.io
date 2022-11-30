---
layout: post
title:  "Tool Review: Recognito"
categories: [ DH, tutorial, recognito, gazetteer, ner ]
image: assets/images/3.jpg
author: Adrienne

---

Recogito (https://recogito.pelagios.org/) is an online tool that supports semantic annotation of the
people, places, and events found in texts, images, and tabular data. By registering for an account with
Recogito, users get 200MB of storage in their workspace, where they can upload source material, create
annotations manually or automatically, add contextual comments and tags to each annotation, and
connect places in their data with geographic locations in authoritative digital gazetteers. Select aspects
of these annotations can be visualized, but the main strength of Recogito is its collaborative orientation.
In addition to using linked data principles for creating annotations and making data more discoverable,
Recogito users can work independently or share their documents privately or publicly to collaborate
with peers and the online community.

### Development Status

Recogito is one of several projects from the Pelagios Network, "a community-driven initiative that
facilitates better linkages between online resources documenting the past, based on the places that
they refer to" (Simon et al, 2017, p. 3). Developed in 2013, this web-based tool was relaunched in 2016
with a refined suite of features and the same focus around connecting data through common
geographic points. It is actively being developed. For example, the "Quick" annotation options now
include both Places and Persons (the tutorial indicates only Places is available). In their FAQ, the
developers share efforts to expand and align the available gazetteers—essentially, collections of
authority files for geographic locations—and invite contributors to help expand on the named entity
recognition engines used (Pelagios Network, n.d.-b). Recogito is a well-supported, active initiative by the
Pelagios Network, "developed under the leadership of the Austrian Institute of Technology, Exeter
University and The Open University, with funding from the Andrew W. Mellon Foundation" (Pelagios
Network, n.d.-a, para. 1), and the number of additional features currently launched in beta mode
suggests that the tool will continue to be improved.


### Purpose and Main Features

Recogito is aimed at a non-specialist audience, pitching itself as linked data and semantic annotation
"without the pointy brackets" or need to code (Pelagios Network, n.d.-c). From their source material,
users select a term either by highlighting a word / phrase in a text or drawing a box around it in an
image, and mark it as a Place, Person, or Event. With text, users can automatically mark terms by
running one of several named entity recognition engines, and confirm their accuracy by manually
verifying each automatically generated annotation (see Figures 1 and 2). Annotations can be modified in
a pop-up window by choosing or changing the entity type, adding freeform comments, listing keywords
as tags, and (if collaborating with others) creating a link to share the specific annotation. The window
can be reopened at any time to mark a term with multiple annotations, such as to select a second entity
type when a term (like "Romans") refers both to a people and a place, or link to another gazetteer
location when uncertainty around a place name can suggest several possible options (see Figure 3). In
text documents, users can also draw directional relationships by dragging a line between terms and
labelling the type (see Figure 4). While text is freeform, with both annotations and relationship,
previously used tags appear as suggestions to support consistent application. In addition, users can
upload a customizable thesaurus specific to each document to use a controlled vocabulary for
annotation tags that will also link any term with a URI for the concept.

Recogito provides a private workspace to store and manage resources, which includes a statistics
section for user activity, a useful feature for tracking progress on annotations and contributions from
different team members. Collaborators can be invited by their username, or with private and public links
that offer varying levels of edit permissions. Users should be conscious of copyright considerations
relating to their source materials before publicly sharing documents. 

### Evaluation

While social annotation tools such as Annotation Studio and Hypothesis allow similar collaborative
annotation of online resources, Recogito is unique in that it enforces the use of "ontological—or
semantic—annotation", that is, "annotations where terminology has a commonly understood meaning
according to a shared conceptualization" or "social understanding, expressed with a shared vocabulary"
(Simon et al, 2017, p. 7). The features for creating consistency with tags and relationships noted above
support this aim, but the centrepiece of this approach is the requirement to manually verify Place
annotations by matching terms with an existing record in one or more of Recogito's digital gazetteers.<sup>1</sup>

The digital gazetteers focus on historical places, with at least seven of the nine available relating to the
ancient world up to the 1800s, and only one, geonames, on contemporary populated places and
countries. As the developers note, different gazetteers "often provide overlapping, but also
complementary (and sometimes even conflicting) information about places for particular time periods
or regions" (Pelagios Network, n.d.-b). This can provide users with a range of possibilities for a precise
location, including how that location may have changed through history. When Recogito users publish
data generated with the tool, the use of linked data enables discovery of the connections made through
place. However, should no match be found (as was frequently the case with the very small towns
mentioned in my sample text), the undefined location cannot be manually added or verified within
Recogito, and these annotations will not appear in the tool's map visualization. The user can instead flag
the location for the community to address (presumably by updating a relevant gazetteer), and they can
still record details such as coordinates in a comment, data which will be available to download. 

Several design features make it evident that a goal of the tool is to simplify the user's experience and
improve their workflow. These include: toggling into the "Quick" annotation mode that pre-selects
either People or Places; changing the highlighting colour by entity type or by verification status to make
progress visible at a glance; and the ability to quickly flip between the source material and the map
visualization to check their work. Once a term is identified, the annotation can be applied in bulk to all
its other appearances. For each document, settings can be adjusted to select preferred gazetteers and
upload a unique vocabulary that speeds tagging by allowing selection from a searchable dropdown menu. An edit history allowing users to view who has made what changes, as well as options for creating
and restoring from backups.
 
The features for visualizing or analysing data within Recogito are limited as they are not intended for
sharing or interpreting results, but rather meant to improve the functionality of the workspace for users
to effectively annotate, track progress, and collaborate with peers. As places cannot be added except
through the gazetteers, the map visualization is best used for confirming the accuracy of those locations
and flagging unmatched ones; similarly, documents cannot be edited within Recogito, such as to correct
spelling errors (see Figure 5). Instead, users have multiple options for exporting data so that it can used
with more powerful digital humanities tools for visualization and analytics, such as network graphs or
interactive maps. Formats include CSV and RDF for annotations, GeoJSON for places, and TEI/XML for
annotated documents, with several other options available in beta (with some limitations). The capacity
to download work in multiple formats ensures that progress is not lost despite being unable to correct
any errors in the original material that were not identified before beginning the annotation process.

While the interface itself is straightforward and user-friendly, the biggest learning curve for Recogito is
identifying all the available features, especially as some options are in development or limited to specific
modes, such as the ability to create relationships within text documents only or the need to name a
term by transcribing it when working with an image. A review of the quick tutorial and FAQ provided by
Pelagios is recommended to grasp the main features of the interface. The developers have also created
an in-depth user guide hosted on GitHub (Vitale & Simon, 2020) that reviews Recogito's many functions,
and current limitations, and which invites contributors to make suggestions for further development. 

### Conclusion

Recogito is an excellent tool to enable users to quickly and efficiently annotate text, images, and even
spreadsheets, for the people, places, events, and relationships in their data. The selection and use of
gazetteers make this an appealing tool for annotating historic documents with a greater degree of
certainty around identifying places. The annotation features are flexible to easily accommodate unusual
or unique entities, and while the visualization options and the analytics dashboard in this tool are
limited, they suit its purposes of ensuring an effective workflow and tracking progress, particularly when
collaborating with peers. Rather than sharing findings from Recogito, it is best used as a social
workspace for creating a dataset that can then be used elsewhere with more powerful visualization and
analytics tools. Awareness of the limitations of certain features still under development is important to
avoid frustration. Perhaps the greatest value of Recogito is in contributing to an initiative that is actively
working to support linked open data principles for using and creating verified, authoritative information.

<sup>1. Though the developers have indicated a similar verification process is planned for marking people from
authoritative lists (Simon et al, 2017, p. 13), it seems this feature is not currently available</sup>

### Appendix: Musical Annotations

<img src="https://raw.githubusercontent.com/fimsdhlib/fimsdhlib.github.io/main/assets/images/orr-1.png">

<sup>Fig.1  Places identified through the named entity recognition engine run on the lyrics to "I've Been
Everywhere Man" by Stompin' Tom Connors. </sup>

<img src="https://raw.githubusercontent.com/fimsdhlib/fimsdhlib.github.io/main/assets/images/orr-2.png">

<sup>Fig.2 Places verified manually show all the known locations that Stompin' Tom Connors claims to
have been, man.</sup>

<img src="https://raw.githubusercontent.com/fimsdhlib/fimsdhlib.github.io/main/assets/images/orr-3.png">

<sup>Fig.3 The transcribers of the lyrics (Musixmatch, n.d.) could not keep up with Stompin' Tom and conflated two
locations into a third nonsensical one. Multiple place annotations can be included, and a comment added for
clarification.</sup>

<img src="https://raw.githubusercontent.com/fimsdhlib/fimsdhlib.github.io/main/assets/images/orr-4.png">

<sup>Fig.4 Marking directional relationships between terms with customized tags.</sup>


<img src="https://raw.githubusercontent.com/fimsdhlib/fimsdhlib.github.io/main/assets/images/orr-5.png">

<sup>Fig. 5 With no matching location in the gazetteers for Schreiber, it cannot be marked on the map.
Flagging the location allows the creation of an unverified annotation and notes made in the comment
can simplify updating data after it is downloaded. Note the errors in the original text that cannot be
corrected—the town is included in the slightly jumbled lyrics as "Scraber".</sup>


### References

Hypothesis. (n.d.). Retrieved November 21, 2022, from https://web.hypothes.is/
MIT HyperStudio. (2017). Annotation studio. Retrieved November 21, 2022, from
https://www.annotationstudio.org/project/

Musixmatch. (n.d.). I've been everywhere: Song by Stompin' Tom Connors. Lyrics. Retrieved November
11, 2022, from https://www.google.com/search?q=lyrics+to+i%27ve+been+everywhere+man
+stompin+tom&oq=lyrics+to+i%27ve+been+everywhere+man+stompin+tom

Pelagios Network. (n.d.-a). About us. Retrieved November 21, 2022, from https://pelagios.org/about-us/

Pelagios Network. (n.d.-b). Frequently asked questions. Retrieved November 21, 2022, from
https://recogito.pelagios.org/help/faq

Pelagios Network. (n.d.-c). Recogito, an initiative of Pelagios Commons. Retrieved November 21, 2022,
from http://recogito.pelagios.org/

Simon, R., Barker, E., Isaksen, L., & De Soto Cañamares, P. (2017). Linked data annotation without the
pointy brackets: Introducing Recogito 2. Journal of Map & Geography Libraries 13(1), 111-132.
https://doi.org/10.1080/15420353.2017.1307303

Vitale, V. & Simon, R. [pelagios]. (2020, January 24). Recogito tutorial. E. Barker (ed.). Retrieved
November 21, 2022, from https://github.com/pelagios/pelagios.github.io/wiki