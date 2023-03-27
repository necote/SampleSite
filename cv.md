---
layout: page
title: Example CV
permalink: /cv/
---

There are many options for including a CV on your site. One is to just type the information into the page file, formatting and styling as desired with Markdown, like you would with any page. You might instead directly [link to the PDF](/assets/example-cv.pdf) to download but not display--as I've done here. Or, you even link out to a PDF hosted on Google Drive or another similar service--following the Markdown syntax for links, for an example see the [Resources]({% link resources.md %}) page of this site. 

Some, however, might find it preferable to embed a PDF that can be replaced when needed. The below serves as one example of this latter process.

<!--Change the width and height #s below to meet your own style requirements. You might just want to play around with these to see what works for you! Remember, "assets" is the name of the folder I created where my images and PDFs are stored. Update the below your own folder name and pdf name. -->

<object width="750" height="800" data="{{ site.url }}{{ site.baseurl }}/assets/example-cv.pdf" type="application/pdf"><p>If you see this message the PDF cannot be displayed.</p></object>


<br>

*****

<br>

💡Hint: You'll notice that I linked to a different page on this site above--I've also embedded a PDF--review the Markdown for this page to see how it's done. 

💡Hint: The size of the display window for the PDF can be adjusted per your needs. Review the Markdown file for this page to learn how to adjust this.  

💡Hint: The [Minima](https://github.com/jekyll/minima) template only includes one page (`about.md`). To make this page, I simply copied that first page and change its filename. Inside, I edited the title, permalink, and the text using Markdown.

