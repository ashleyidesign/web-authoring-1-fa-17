@channel

Hi all, no class today as I'm still unwell.

Instead you get a write-up of my lecture and some things to do before Monday. Here's what we would have talked about, and I'll review next week.

# File Naming Best Practices

Folder names and names of files you create, like .md, .html, .img etc, should always use lowercase letters and no spaces. Instead of spaces, you should be using _ or -. 

The reason for this is browsers and web apps don't see a space as a space, they see it as %20. This goes for other special characters. Yes you can use [emojis](https://qz.com/828436/the-land-rush-for-emoji-domains-is-coming/) in URLs nowadays, but 99.9% of the time using a special character in a filename or folder name will break the link. Here's an excellent reference on what not to use in filenames/foldernames: [http://www.mtu.edu/umc/services/digital/writing/characters-avoid/](http://www.mtu.edu/umc/services/digital/writing/characters-avoid/)

# HTML Overview

Here's a block of html code: '<a href="https://www.montserrat.edu/" target="_blank" class="button">Link to Montserrat</a>'

## Tags

An *HTML Tag* is the first thing that shows up when you start a line of code with <. In this case, the tag is 'a', which is a hyperlink. The tag has several attributes, such as an 'href' of 'https://www.montserrat.edu/' and a 'class' of 'button'. Other examples of HTML Tags is img, div, section, article and aside, some of which are referenced in **HTML5 for Web Designers**. 

HTML is just a bunch of tags put together to format the content. 

A guide to all the available tags in HTML5 and those depreciated in previous versions of HTML is here: [https://www.w3schools.com/tags/ref_byfunc.asp](https://www.w3schools.com/tags/ref_byfunc.asp)

## Elements

An element contains the start tag ('<a>'), the end tag ('</a>') and everything in between, like the content. You can nest elements inside of other elements, like an H1 inside of a link '<a href="https://www.montserrat.edu/" target="_blank" class="button"><h1>Link to Montserrat</h1></a>' or a link inside of a div:

>'<div>'
>   '<a href="https://www.montserrat.edu/" target="_blank" class="button">Link to Montserrat</a>'
>'</div>'

Some elements don't need an end tag, such as '<hr>' '<br>'. Another guide to elements is here: [https://www.w3schools.com/html/html_elements.asp](https://www.w3schools.com/html/html_elements.asp)

## Versions

The version of HTML we're working with, and where all of the web is heading, is HTML5. At the top of any HTML file, you need to specify which version of HTML you're using, so the browser knows what to expect. If you don't, and the browser doesn't default to HTML5, then some of the features you build may not work.

In our case, it's just '<!DOCTYPE html>'.

If you look at the source code for other websites, you'll see different versions that are way more complex on line 1: [view-source:http://art.yale.edu/](view-source:http://art.yale.edu/)

## Meta Data

The most basic structure for a website:

Line 1: Doctype
Line 2: start head tag
Line 3 - ?: page info like meta tags and the page title

Followed by links to CSS files, Javascript files and page-specific styling and a close head tag.

After '</head>' is '<body>' which contains all of the HTML you want the browser to render. Meta data can tell search engines what the page is about and tell the browser how to show the page.

## Visible Content

While most of the '<head>' is invisible when you look at a page, the one tag that will show somewhere is '<title>'. This is the name of the page in the browser tab. For example on the school's homepage, the title is '<title>Montserrat College Of Art | Beverly, Massachusetts, MA</title>' and if you [go look at the page in your browser](https://www.montserrat.edu/) you'll see that name in the tab. The title also shows up when you do a [search](https://www.google.com/search?q=montserat+college&rlz=1C1CHBF_enUS735US735&oq=montserat+college&aqs=chrome..69i57j0l5.2219j0j1&sourceid=chrome&ie=UTF-8).
    
Other visible content that gets rendered is anything within '<body' '</body', which is where the rest of your HTML and content goes.

## Uploading to Github

The easiest way to upload files to Github is drag-and-drop from your computer. If you navigate to your respository and drag a folder to anywhere on the screen, it will upload to the respository. You will first be asked to fill out a section called *Commit changes*. This is the changelog for your files, and will help you keep track of what was changed, so in case you need to go back to a previous version, you know what was changed when. Select **Commit directly to the 'master' branch** and click the green button.

## HTML Validation

When writing HTML by hand, it's pretty easy to have a typo, or forget to add your doctype or missing a > in just the wrong spot. Using an HTML validator will point out any issues you have in your code and explain why something is an issue.

[The W3 validator is the most common to use](https://validator.w3.org/#validate_by_input) and you can copy and paste your HTML code in there, or upload the file.

# For Monday

- read the above, and take a look at the links I included
- upload the markdown version of your summary & about the author to your ebb & flow github repository
- upload your illustration as a .png to your ebb & flow github repository in a folder called img
- if you are totally stuck on the above, email them to me instead
- read: [http://html5doctor.com/i-b-em-strong-element/](http://html5doctor.com/i-b-em-strong-element/)
- convert your markdown file to HTML using [Dillinger](https://dillinger.io/) - you can either upload the file or copy/paste then export as HTML (not styled HTML)

I'm around if you have any questions.