---
layout: post
title:  "Tool Review: WordWanderer"
categories: [ DH, tutorial, wordwanderer, text analysis ]
image: assets/images/3.jpg
author: Adrienne

---

WordWanderer (https://wordwanderer.org/) is a text visualization tool used for simple language
analysis. Once the user inputs a text, or chooses one from several presets, the interface displays three
interactive views that the user can navigate between to explore the frequency each term appears, what
terms appear in proximity to others, and how strong those associations are. The user can also compare
two related terms to show all the collocated terms they have in common, and the strengths of those
associations relative to either term. Selecting or deselecting a term allows the user to move between
words in a display, and through each of these three views, endlessly exploring the nature and strengths
of these relationships through the differences in font size, highlighting colour, and placement.

### Development Status

This web-based tool is a prototype developed by Marian Dörk and Dawn Knight while at Newcastle
University, UK, with support from the RCUK Digital Economy programme (Dörk & Knight, n.d.). The tool
is a work-in-progress, as Dörk and Knight (2015) identified areas for further improvement over the next
year of research, several of which have not been resolved in the current iteration. The most recent
updates to the tool, whose code is on GitHub, appear to have been made in 2019 (nrchtct, n.d.). This
suggests the tool is no longer being updated, so some glitches in functionality are to be expected.

### Purpose

Emphasizing the value of exploring in an open-ended environment to engage with language, the
purpose of WordWanderer is to support a playful, accessible approach to linguistic analysis that can
serve as a more casual entry point into a text for a novice than “feature-rich and sophisticated tools,
aimed mainly at people with expertise” (Dörk & Knight, 2015, p. 1). After inputting a text, a word cloud
is displayed with the top 300 terms based on their frequencies; hovering over a term highlights others
that are associated with it. By selecting a term from this cloud view, or from a dropdown menu by
searching the whole text, the display shifts to context view in which the chosen term is moved to the
centre and surrounded with its related terms. The font size shows how often the terms appear together,
with horizontal proximity showing how closely; partial sentences in which the central term appears are
shown below the display. The user can then connect two terms appearing together to show all other
collocated words that they have in common. This comparison view pushes terms to the left or right to
show how strongly the shared words are associated with either term. Notably, the user cannot record or
save their progress, or directly export any results from this tool. The emphasis is on the experience of
navigating among words and finding and making connections; the results themselves are ephemeral.

### Evaluation

WordWanderer’s simple, intuitive interface is easy to grasp quickly. Unlike more sophisticated tools that
offer a range of options for uploading and preparing a text as first steps, with this tool, users need only
know how to copy and paste in order to start exploring. Their only decision is whether the text should
be all lowercase. A little patience may be needed while the loading icon cycles when inputting very long
texts, but the interactive visualization has smooth navigation between words and displays. The familiar
format of a word cloud consisting of tags is particularly user-friendly, and the minimalist design makes it
easy to locate the Help icon for guidance or to learn just by starting to click around.
One issue with the interface is that text overlaps in the context and comparison displays where terms
are sized and arranged based on their proximity. This creates difficulty distinguishing terms, making
them hard to read, impossible to select, or altogether invisible (see Figure 1). This problem is mitigated
somewhat in the context view, as the sentences consist of clickable tags; however, without the ability to
hover over terms to highlight the collocated ones, users cannot see the strength of these associations.
While the Dörk and Knight (2015) identified this as an issue to be resolved, its persistence in the current
prototype makes navigating a crowded result page challenging. 

<img src="https://github.com/fimsdhlib/fimsdhlib.github.io/blob/main/assets/images/aorr-1.PNG?raw=true">
<sup>Figure 1. Examples of overlapping terms, where seeing and selecting an individual one is difficult or impossible.</sup>

Once the visualization has loaded, the user may toggle options to show or hide common words, various
parts of speech, numbers, symbols, and even individual words or characters. This final option is
particularly useful when encountering glitches in how WordWanderer tokenizes text (see Figure 2).
These toggles are limited compared with the sophisticated options for preparing a text in advance
available in tools such as Lexos. However, having these simple filters available only after the text is
visualized can be an advantage for using WordWanderer as a teaching and learning tool. Apparent
mistakes or a word cloud dominated by irrelevant or redundant terms can demonstrate how to prepare
or manipulate data: for example, my trial text’s most strongly associated words with place were took,
take, and taken, a clear example of the value of lemmatization. Users can also consider whether the best
strategies to improve their visualizations are found in adjusting the text before or after it is outputted.

<img src="https://github.com/fimsdhlib/fimsdhlib.github.io/blob/main/assets/images/aorr-2.PNG?raw=true">
<sup>Figure 2. Despite common words and punctuation toggled off, “The appears as a top term; with spaces
around special characters in the original text, em dashes and curled quotation marks remained.</sup>

While WordWanderer uses the same analytic techniques as more sophisticated tools, like frequency
counts and collocation measures, it takes a unique approach in combining these elements into a single,
streamlined interface. In general, users can only ever view the results of those calculations as they
explore word associations across the different displays. The exception is the count of instances of a term
within the sentences in the context view. This simplicity ensures that a novice is not overwhelmed by a
complex interface, but it also limits the tool to basic representations over in-depth analysis.
The Help icon provides a brief overview of what the different displays show and how to navigate around
each of them. However, the specialized terminology used in these explanations (“relative frequencies”,
“proximal co-occurrence”, “combined association strength”) might be challenging for the novice, and
the tool does not provide further resources to support understanding of these terms or effectively
“reading” the results. Though WordWanderer is a very inviting tool, frustration around interpreting the
visualizations may dissuade novice users from continuing to explore with it. By contrast, having only the
visualizations without any of the underlying data or the ability to export results limits the usefulness of
the tool for experts wanting more in-depth analysis, particularly inhibiting the ability to compare texts.

### Conclusion

WordWanderer is best used to get an impression of a text. It is a great starting point for novices to
experiment and gain a general understanding of frequency analysis, collocation, and relationship
mapping, and would be suitable as a learning and teaching tool for engaging with these concepts.
Experts may find value in using this tool to identify trends or sticking points in their data as a first step in
preparing their text for a more in-depth research project using a more powerful analytical tool. 