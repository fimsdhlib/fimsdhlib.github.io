---
layout: post
title:  "Tool Review: StoryMap JS"
categories: [ DH, tutorial, story map, geographical narrative, GIS ]
image: assets/images/1.jpg
author: Kaeleigh

---
StoryMap JS is an open-source tool that allows users to create a narrative using maps and images. Users can highlight locations on a map or static image and attach slides featuring media, such as images, videos, and/or text, to give information on each selected location. This tool was developed by Zach Wise, a professor at Northwestern University, and the Northwestern University Knight Lab team (Germuska, 2013). The code for StoryMap JS is stored in a public repository on GitHub (NUKnightLab, 2013). StoryMap JS was released in 2013 and the last announcement of updates to the tool was in 2016 (Germuska, 2013; Germuska, 2016), although it appears changes to the code continue to be made on GitHub. It is unclear which version of the tool is currently in use, however the Knight Lab website for StoryMap JS states the tool is still in a beta phase (Knight Lab, 2022).

StoryMap JS is not the only tool of its kind on the market; Esri’s ArcGIS StoryMaps product can also be used to create narratives using maps and other media (Esri, n.d.). However, Esri’s products are not open-source and often require the purchase of a license or subscription. StoryMap JS reduces the barriers for users by being a free tool.

## Authoring Tool Review

In terms of functionality, StoryMap JS has a simple user interface that is intuitive for most users that have some previous experience working with online tools. It has several options for pre-defined maps (along with the option for importing custom maps), it is easy to add, delete, and move slides, locations can be searched by address or coordinates, and media can be imported from a variety of sources. The StoryMap JS website also features frequently asked questions, support forums, and technical documentation that cover many of the issues users may encounter and the solutions are delivered succinctly (Knight Lab, 2022). However, by attempting to avoid a steep learning curve for new users, the developers limited the customizability of the story maps. For example, a default slide is displayed at the beginning of each story map, which is referred to as an overview slide. The overview slide is intended to show the entirety of the map or image that will be explored in the story map. Several users have complained about not being able to control the zoom on the overview slide, as it will sometimes choose a random location to display if the map is too large instead of showing the whole map. As a work around to this issue, the developers have suggested customizing the story map by editing the JSON file to remove the default overview slide. While writing and editing the code does give the user more control over how the final story map will look, it also requires the user to be knowledgeable in programming, so this method is less accessible to the average user.
	
There are several other limitations. StoryMap JS does not provide an option to import a pre-populated dataset of coordinates, such as a Microsoft Excel spreadsheet. This means the user is required to manually input each location on the map, which may be time consuming for larger story maps. In general, the tool is better designed for story maps with points concentrated in a smaller area. Story maps that have locations spread out across a larger area do not present well, as it takes longer for the content to load which results in the screen flashing black as the viewer clicks through each slide. Storymap JS provides limited space for text on each slide, so users must keep the text concise, and only one piece of media can be presented on each slide. The user must also have a Google account to utilize the tool, which may be bothersome for those who do not use Google.

## Gigapixel Feature

An element that enhances the flexibility of StoryMap JS is the gigapixel feature. StoryMap JS allows the user the option of uploading a large, high-quality image to use as the basis for their story map. Instead of using a pre-defined or custom map of the present-day world, users can instead create a story map featuring a historical map, a fictional map, or another image, such as a piece of artwork. On their website, Knight Lab demonstrates how the gigapixel feature can be used through their example exploring Hieronymus Bosch’s painting The Garden of Earthly Delights (Knight Lab, 2022). The example story map highlights sections of the painting and gives details on how colours and symbols were utilized in the painting to present a message to the observer, showing that StoryMap JS is not only limited to presenting information on geographic locations.

## Conclusion

Despite its limitations, StoryMap JS is an excellent tool for anyone looking to create a simple story map for free. Story maps allow viewers to consume information in a way that is interactive, which may be a more appealing method to some than reading through a long article. Presenting information in a variety of formats makes it accessible to a wider audience, making StoryMap JS a useful tool for researchers and educators to disseminate information effectively.
 
## References

Esri. (n.d.). Digital Storytelling with Maps ArcGIS StoryMaps. Retrieved 4 October 2022, from https://www.esri.com/en-us/arcgis/products/arcgis-storymaps/overview

Germuska, J. (May 24, 2016). A few small improvements to StoryMapJS. Northwestern University Knight Lab. https://knightlab.northwestern.edu/2016/05/24/a-few-small-improvements-to-storymapjs/

Germuska, J. (October 17, 2013). Announcing StoryMapJS developer release—A new tool for storytellers. Northwestern University Knight Lab. https://knightlab.northwestern.edu/2013/10/17/announcing-storymapjs-developer-release-a-new-tool-for-storytellers/

Knight Lab. (2022). StoryMap JS. https://storymap.knightlab.com

NUKnightLab. (2013). StoryMapJS: Maps that tell stories [JavaScript]. GitHub. https://github.com/NUKnightLab/StoryMapJS.
