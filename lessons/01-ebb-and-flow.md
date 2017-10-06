# Ebb & Flow

> The control which designers know in the print medium, and often desire in the web medium, is simply a function of the limitation of the printed page. We should embrace the fact that the web doesn’t have the same constraints, and design for this flexibility. But first, we must “accept the ebb and flow of things.”
>
> —John Allsopp, “[A Dao of Web Design](https://alistapart.com/article/dao)”

## Brief

Write a summary and illustrate an image for the seminal article “[A Dao of Web Design](https://alistapart.com/article/dao)” by John Allsopp, then as a class, we’ll work together to develop a responsive single-page website with semantic markup, flexible images, and a fluid grid.

## Work & Rubric

`100 points` (`120 points` total with Extra Credit)

Copy and paste this section into a new task list `issue` within your repo and title it as “Work & Rubric”. [`#tasklist`](https://github.com/blog/1825-task-lists-in-all-markdown-documents)

### Content First

`20 points` (`4 points` each)

- [ ] Write a [summary](https://seesparkbox.com/foundry/naming_css_stuff_is_really_hard) of the article, 256 words or fewer in length
- [ ] Use of [Markdown](https://guides.github.com/features/mastering-markdown/) to show the hierarchy and structure of the content, such as headings and subheadings, and paragraphs and lists
- [ ] Illustrate a [hero image](https://en.wikipedia.org/wiki/Hero_image), with a 2:1 ratio, in the existing style of [Kevin Cornell](http://www.bearskinrug.co.uk/projects/alistapart/)
  - First, solve the illustration; second, fuss over the visual style
  - Scan in or capture as a photo; edit and save for web in Photoshop (see [Imagery](#imagery) for details)
- [ ] Provide an “About the Author” section with [a brief bio](https://alistapart.com/author/johnallsopp), 2–3 sentences in length, and headshot photo `#selfie`
- [ ] Provide a “read the full article” link, to the original, at the end of the summary

### Semantic Markup

`20 points` (`4 points` each)

- [ ] Use of section (`header`, `footer`, `section`, etc.), and grouping (`figure`, `p`, `ul`, etc.) elements for chunking content into semantically structured content
- [ ] Use of `h1`–`h6` for headings and subheadings
- [ ] Use and understanding of the difference between `b` and `i`, and `strong` and `em`
- [ ] Use of `a` for external and fragment hyperlinks
- [ ] Use of the `alt` attribute to provide a [short description](http://centercentre.com/blog/2016-06-30-alt-text-is-part-of-your-sites-content), alternative text, of the visual content displayed in the hero image

### Imagery

`20 points` (`4 points` each)

- [ ] Size hero image at 960px × 480px (2:1)
  - 960px is the required width, however the height can be shorter than 480px (if necessary)
- [ ] Size headshot photo, cropped at 256px × 256px (1:1) or un-cropped at a maximum width of 256px wide
  - Use of the CSS property `overflow` to crop un-cropped headshot photo
  - Use of the CSS property `border-radius` to create a circular headshot photo
- [ ] Save images using Photoshop, export `Save for Web (Legacy)…` hero image as a PNG (`.png`) using the preset `PNG-8 128 Dithered` and headshot photo as a JPG (`.jpg`) using the preset `JPEG High`
  - Name images `hero-image-firstname-lastname.png` and `headshot-firstname-lastname.jpg` (replace `firstname` and `lastname` with your first and last name)
- [ ] Optimization images using [ImageOptim](https://imageoptim.com/mac)
  - Hero image should optimize at under 128kb
  - Headshot photo should optimize at under 64kb
- [ ] Use of an `img` folder to organize images

### Style as an Enhancement

`20 points` (`4 points` each)

- [ ] Use of meaningful CSS class selector names
- [ ] Author and apply styles for mobile first
- [ ] Author and apply media query styles for breakpoints
- [ ] Author and apply a print stylesheet to print as a single-page
- [ ] Use of a `css` folder to organize style sheets

### Best Practices

`10 points` (`2 points` each)

- [ ] When naming things — keep it lowercase, and use a hyphen (`-`) or an underscores (`_`), *not a space* (`%20`), for separating phrases in HTML and CSS, files, folders, etc.
- [ ] Format HTML and CSS via [DirtyMarkup](https://dirtymarkup.com)
  - `BBEdit` > `Markup` > `Utilities` > `Format…`
- [ ] Use CSS shorthand, [Shrthnd](http://shrthnd.volume7.io), for `font`, `margin`, et al. properties for brevity
- [ ] Use `em` values for better web typography; `px` to `em` via [Pixem](http://matthewkosloski.me/labs/pixem/)
- [ ] Validate markup and style; fix all errors; resolve warnings (if possible)
  - [HTML Validation](https://validator.w3.org)
  - [CSS Validation](https://jigsaw.w3.org/css-validator/)

### GitHub

`10 points` (`5 points` each)

- [ ] Repo should contain only essential files:
  - `README.md`
    - Include a heading (title) and paragraph (description) for the project
    - Include a menu (navigation) list to the following sections:
      - Draft
        - Draft of summary (text and image)
      - Revision
        - Revision of summary (text and image)
      - Final
        - Link to final version of summary as Markdown (`summary.md`)
        - Link to final version of summary as HTML without CSS (`summary.html`)
        - Link to final version of summary as HTML with CSS (`index.html`)
      - Notes (optional)
        - List of odds and ends
  - `index.html` (HTML with added metadata, structure, and CSS)
  - `summary.html` (Markdown to HTML with added semantics)
  - `summary.md` (Markdown only)
  - `css` (folder containing external style sheets)
    - For example: `main.css` and `print.css`
  - `img` (folder containing images)
    - For example: `hero-image-firstname-lastname.png` and `headshot-firstname-lastname.jpg`
  - `versions` (optional folder containing tests, experiments, work in progress, etc.)
    - For example: `test-1.html`
  - `refs` (optional folder containing reference images [sketches, screenshots, etc.])
    - For example: `sketch-1.png`
    - Or include a list of references (links) in the `README.md`
- [ ] Add a [description and url](https://i.imgur.com/CexeWBQ.gif) to your GitHub repo
  - For example: _A Summary of A Dao of Web Design_ and `https://johnallsopp.github.io/dao-summary`

- - -

### Extra Credit

`20 points` (`5 points` each)

- [ ] Redraw hero image [using Illustrator](https://design.tutsplus.com/tutorials/how-to-create-a-classic-vector-painting-with-watercolor-washes-and-line-art--vector-1481) or Sketch, not in Photoshop, and save as an SVG (`.svg`) `#vector`
- [ ] Optimization of SVG (`.svg`) using [SVGOMG!](https://jakearchibald.github.io/svgomg/)
- [ ] Use of the `src` (to embed the `.png`) and `srcset` (to embed the `.svg`) attributes for providing fallback and future-friendly image formats
- [ ] Test document outline for heading and section rank, [HTML5 Outliner](http://gsnedders.html5.org/outliner/), and update any _Untitled Section_ to display a proper heading (`h1`–`h6`) _See also [heading and section rank](https://www.w3.org/TR/html5/sections.html#rank)_

## Readings & Resources

Copy and paste this section into a new task list `issue` within your repo and title it as “Readings & Resources”. [`#tasklist`](https://github.com/blog/1825-task-lists-in-all-markdown-documents)

**Note:** Prefixed `[ ] →` links are required reading (or viewing). `#readme`

### Short & Sweet

- [ ] → [Steps to Writing a Summary](http://www.mrshatzi.com/files/summary.pdf) (See page 2 for summary guidelines.)
- [ ] → [Be Succinct! (Writing for the Web)](https://www.nngroup.com/articles/be-succinct-writing-for-the-web/)
- [Keep it short (but not too short)](http://www.learnnc.org/lp/editions/webwriting/708)

### Writing

- [ ] → [“Lean Content” by Stephanie Hay](https://www.youtube.com/watch?v=g2QO9nZUVk4&feature=youtu.be) `video`
- [Writing for the Web](https://www.usability.gov/how-to-and-tools/methods/writing-for-the-web.html)
- [Reading Content on Mobile Devices](https://www.nngroup.com/articles/mobile-content/)
- [Voice and Tone](http://styleguide.mailchimp.com/voice-and-tone/)

### Writing Tools

- [Measure Text Readability](https://readable.io/text/)
- [Hemingway Editor](http://www.hemingwayapp.com)
- [Nitpicker](http://nitpickertool.com)

### Meaningful Links

- [ ] → [“Learn More” Links: You Can Do Better](https://www.nngroup.com/articles/learn-more-links/)

### Responsive Web Design

- [ ] → [A Dao of Web Design](https://alistapart.com/article/dao)
- [ ] → [Responsive Web Design](https://alistapart.com/article/responsive-web-design)

### Web History

- [The History of the Web](http://thehistoryoftheweb.com/timeline/)
- [A Timeline of the History of the World Wide Web](http://webdirections.org/history/)
- [A Brief History of Markup](https://html5forwebdesigners.com/history/)

### Creativity

- [ ] → [David Lynch on Where Great Ideas Come From](https://vimeo.com/182093266) `video`
- [ ] → [Everything is a Remix Remastered](https://vimeo.com/139094998) `video`
- [ ] → [Malcolm Gladwell Looks At Technology Innovations](http://www.npr.org/2011/05/16/136368716/malcolm-gladwell-looks-at-technology-innovations) `audio`
- [Creation Myth](http://www.newyorker.com/magazine/2011/05/16/creation-myth)

### HTML Basics

- [Getting to Know HTML](http://learn.shayhowe.com/html-css/getting-to-know-html/)

### HTML Document Flow

- [The Flow](http://marksheet.io/css-the-flow.html)

### HTML Document Outline

- [Computer Says NO to HTML5 Document Outline](http://html5doctor.com/computer-says-no-to-html5-document-outline/)
- [Document Outlines in HTML 5.1](https://bitsofco.de/document-outlines-in-html-5-1/)
- [HTML 5 Outliner](https://gsnedders.html5.org/outliner/)

### CSS Basics

- [Getting to Know CSS](http://learn.shayhowe.com/html-css/getting-to-know-css/)

### CSS Box Model

- [CSS Box Model](https://developer.mozilla.org/en-US/docs/Learn/CSS/Introduction_to_CSS/Box_model)
- [Opening the Box Model](http://learn.shayhowe.com/html-css/opening-the-box-model/)
- [CSS Box Model Properties](http://cssreference.io/box-model/)
- [What’s the Deal with Collapsible Margins?](https://bitsofco.de/collapsible-margins/)

### CSS Typography

- [CSS Text](http://marksheet.io/css-text.html)
- [CSS Typography Properties](http://cssreference.io/typography/)

### HTML & CSS Reference

- [HTML5 Element Index](http://html5doctor.com/#glossary)
- [Mozilla Developer Network (MDN) Web Docs](https://developer.mozilla.org/en-US/)
- [Learn to Code HTML & CSS](http://learn.shayhowe.com/html-css/)
- [Marksheet](http://marksheet.io) A Free HTML & CSS Tutorial
- [HTML Reference](http://htmlreference.io)
- [CSS Reference](http://cssreference.io)

### Best Practices

- [Unitless line-heights](http://meyerweb.com/eric/thoughts/2006/02/08/unitless-line-heights/)

### Semantics, Syntax, and Vocabulary

- [ ] → [Naming CSS Stuff Is Really Hard](https://seesparkbox.com/foundry/naming_css_stuff_is_really_hard)
- [ ] → [Why You Should Say HTML Classes, CSS Class Selectors, or CSS Pseudo-Classes, but Not CSS Classes](http://tantek.com/2012/353/b1/why-html-classes-css-class-selectors)
- [ ] → [Semantic Content Markup](http://webstyleguide.com/wsg3/5-site-structure/2-semantic-markup.html)
- [HTML & CSS Vocabulary](http://apps.workflower.fi/vocabs/)
- [CSS Vocabulary](http://nimbupani.com/css-vocabulary.html)
- [Style Manual](http://stylemanual.org)

### Print Style Sheets

- [ ] → [I Totally Forgot About Print Style Sheets](https://uxdesign.cc/i-totally-forgot-about-print-style-sheets-f1e6604cfd6)

### Media Queries

- [ ] → [Designing for Every Screen](http://marksheet.io/css-responsiveness.html)

### HTML & CSS Validation

- [W3C HTML Checker](https://validator.w3.org) Validate HTML and check document outline
- [W3C CSS Checker](https://jigsaw.w3.org/css-validator/) Validate CSS

### Typographic Details

- [ ] → [Typography Cheatsheet](https://www.typewolf.com/cheatsheet)
- [HTML Arrows](https://www.toptal.com/designers/htmlarrows/) A delightful reference for HTML Symbols, Entities and ASCII Character Codes
- [Butterick’s Practical Typography](http://practicaltypography.com)

### Accessibility

- [ ] → [Alt Text is Part of Your Site’s Content](http://centercentre.com/blog/2016-06-30-alt-text-is-part-of-your-sites-content)
