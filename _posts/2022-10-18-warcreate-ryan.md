---
layout: post
title:  "Tool Review: WARCreate"
categories: [ DH, tutorial, web archives, WARCreate, WARC ]
image: assets/images/1.jpg
author: Ryan

---
WARCreate is an open-source Google Chrome add-on that, with the click of a button, creates
a web archive file (.WARC) of the webpage you are visiting. Mat Kelly created the software
during his time as part of the Department of Computer Science at Old Dominion University
(Kelly & Weigle, 2012) and maintains WARCreate and other projects via a [GitHub repository](https://github.com/machawk1).

The tool is intended to allow the user to easily archive a web page using a standardised file
type, most notably used by the Internet Archive (Kelly & Weigle, 2012). While there are
other tools that auto crawl and archive the web, such as Wayback Machine via the Internet
Archive, there are many instances where users may choose to archive web pages
independently. For example, Wayback Machine does not archive every website on the
internet, cannot possibly scrape every iteration of a website, and does not archive websites
that are protected behind passwords (Kelly & Weigle, 2012). For scholarly pursuits,
WARCreate could be used to capture data from a private Facebook profile that is then used
for textual analysis. When considering the application of this tool the user should also take
into account geodata, as it allows users to capture a specific moment of a website that is
distinct to the user's location. For example, websites stored in the Internet Archive that are
aware of their user's geolocation will only be representative of a specific place (Kelly &
Weigle, 2012). Testing this theory, I searched for “craigslist.org” on Wayback Machine and
was redirected to the [Albuquerque iteration](https://web.archive.org/web/20220930051917/https://albuquerque.craigslist.org/). Comparably, using WARCreate will allow the
user to archive any geolocation of craigslist.

WARCreate is not the only web archiving tool out there. While Internet Archive is the
prevailing developer, with tools such as Wayback Machine, Archive-It, and Heritrix, there are
several other tools that perform a similar task. Webrecorder, MirrorWeb, and Web Curator
Tool are a few worth mentioning (Virginia Tech University Library, 2022). What sets
WARCreate apart is that it offers simple operation, is open source, and is easy to install as a
Google Chrome Extension.

Functionally, I had high hopes because the software looked simple to operate, but did have
to do a considerable amount of research and troubleshooting to find its potential. I started
by downloading [WARCreate](http://warcreate.com/) and installing it in my Chrome browser. This step is very intuitive
and requires little technical knowledge. From this point, the process of creating a WARC file
of your chosen webpage is as straightforward as clicking the chrome extension shortcut and
then clicking the Generate WARC button that pops up. One gripe I have is that there are no
progress indicators that establish the application is working. The application’s process of
creating the WARC file is not instantaneous which sometimes results in 30+ seconds of no
apparent action until the file begins to download. In the beginning, this left me wondering if
it was working at all.

After this, I had notable trouble viewing the WARC files I downloaded. The WARCreate
website clearly states that an additional tool is needed to view the newly created files. For
this Kelly created another piece of software called Web Archiving Integration Layer (WAIL),
which I found frustrating to use to the point that I sought other options. WAIL has its own
archiving functions built in and while I did not test those operations I was unable to figure
out how to view my newly made WARC files. Ultimately, via Virginia Tech University Library, I
found the web-based tool, [Replayweb.page](https://replayweb.page/) and was able to view the files WARCreate had
generated for the web pages I chose. Additionally, I was able to open WARC files in the
source code editor, Brackets, and view the HTML, text content, and other data.
WARCreate would benefit from more support material as guides and video tutorials are
scarce. For example, a guide that explicitly explains the software’s options and settings could
help make the tool more user-friendly. Similarly, tutorials or guides would be useful for WAIL
since it is the suggested companion software.

Practically, WARCreate is a valuable tool for research and in the classroom. Easily archiving a
web page with one click allows the user to consciously preserve data for future use and
demonstration. Among other methods of research, this use could include data mining,
tracking trends, curation, and/or visualisations. Further, WARCreate allows users to archive
their web projects and data in a standardised and readable format.
Despite needing to overcome some obstacles when learning how to view the WARC files, I
think WARCreate is a valuable tool that has many applications. The overall simplicity this
application provides is worthy of applause, but the addition of clear tutorials or guides
would maximise the software's potential for a wider audience.

## References

Kelly, M. & Weigle, M.C. WARCreate - Create Wayback-Consumable WARC Files from Any
Webpage. Proceedings of the ACM/IEEE Joint Conference on Digital Libraries (JCDL), pp.
437–438, Washington, DC, June 2012. https://dl.acm.org/doi/10.1145/2232817.2232930

Web Archiving: Tools. (2022, September 14). Virginia Tech University Library. Retrieved
October 2, 2022. https://guides.lib.vt.edu/webarchiving/tools