# Content First

> Content precedes design. Design in the absence of content is not design, it’s decoration.
>
> —[Jeffrey Zeldman](https://studio.zeldman.com), designer, writer, and publisher

> The Web is 90% text, so let’s style it first.
>
> —[Jeremy Thomas](http://marksheet.io/css-text.html), CSS guru and author of [MarkSheet](http://marksheet.io)

> Choosing a typeface is not typography.
>
> [iA](https://ia.net/topics/the-web-is-all-about-typography-period/), digital design and product agency

## Brief

Design a modern day type specimen single-page website for a not so modern web safe font, make it “cool” again, and showcase that accessible type, color, and layout is not only *cool*, but a *best practice* for inclusive and responsible web design.

Select a web safe font; show off its styles and weights: italic, normal, and bold; transform its cases: upper, lower, and even small-caps; change its size: 1em to 10em, smaller to larger; and even a swash such as a drop capital or an ornamental character such as an ampersand.

Focus on typographic color: style, weight, size, and spacing, before reversed type, foreground and background color. Let the type talk first, then enhance by layering on accessible color to better communicate an aesthetic or emotion for color blind, low vision, and sighted users alike.

## Work & Rubric

`100 points` (`130 points` total with Extra Credit)

Copy and paste this section into a new task list `issue` within your repo and title it as “Work & Rubric”. [`#tasklist`](https://github.com/blog/1825-task-lists-in-all-markdown-documents)

### Web Safe Typography

`30 points` (`10 points` each)

- [ ] Use of only a single web safe font along with its respective generic font genre name as a fallback
 - See [CSS Font Stack](http://www.cssfontstack.com) (`gte 90%` support on both Mac & Win)
 - See [Font Family Reunion](http://fontfamily.io) for compatibility across various devices
- [ ] Use `em` values for better web typography; `px` to `em` via [Pixem](http://matthewkosloski.me/labs/pixem/)
- [ ] Use of unitless `line-height` values, for example: `line-height: 1.15;`
  - See [Unitless line-heights](http://meyerweb.com/eric/thoughts/2006/02/08/unitless-line-heights/)

### Web Safe Colors

`10 points` (`5 points` each)

- [ ] Use of only [web safe colors](http://websafecolors.info); short hex color values are preferred, for example: `#663399` becomes `#639`
- [ ] Web safe color combinations must be [AA compliant](http://accessible-colors.com)

### Navigation

`20 points` (`5 points` each)

- [ ] Use of HTML `nav` element for primary internal navigation
- [ ] Navigation links to the following suggested sections, naming and order can be modified:
  - About
  - Characters
  - Styles & Weights
  - Try Me
  - Usage (optional)
  - Designer
  - Resources (optional)
- [ ] Style all links; active `a` and hover `a:hover` states
- [ ] Provide at least one "Back to Top, Menu, Navigation, etc." link
  - Maybe use an arrow? See [HTML Arrows](https://www.toptal.com/designers/htmlarrows/)

### Layout

`10 points` (`10 points` each)

- [ ] Use of media queries to provide responsive layout considerations for navigation, sections, typography, etc. for small to wider screens

### Best Practices

`20 points` (`4 points` each)

- [ ] When naming things — keep it lowercase, and use a hyphen (`-`) or an underscores (`_`), *not a space* (`%20`), for separating phrases in HTML and CSS, files, folders, etc.
- [ ] Format HTML and CSS via [DirtyMarkup](https://dirtymarkup.com)
  - `BBEdit` > `Markup` > `Utilities` > `Format…`
- [ ] Use CSS shorthand, [Shrthnd](http://shrthnd.volume7.io), for `font`, `margin`, et al. properties for brevity
- [ ] Use `em` values instead of `px` values, except for declaring a hairline rule (`border-top: 1px solid #000;`); `px` to `em` via [Pixem](http://matthewkosloski.me/labs/pixem/)
- [ ] Validate markup and style; fix all errors; resolve warnings (if possible)
  - [HTML Validation](https://validator.w3.org)
  - [CSS Validation](https://jigsaw.w3.org/css-validator/)

### GitHub

`10 points` (`5 points` each)

- [ ] Repo should contain only essential files:
  - `README.md`
    - Include a heading (title) and paragraph (description) for the project
   - `index.html` (HTML with added metadata, structure, and CSS)
  - `css` (folder containing external style sheets)
    - For example: `main.css` and `print.css`
  - `img` (folder containing images)
    - For example: `courier-typewriter.png` and `headshot-matthew-carter.jpg`
  - `versions` (optional folder containing tests, experiments, work in progress, etc.)
    - For example: `content-first-test-1.html`
  - `refs` (optional folder containing reference images [sketches, screenshots, etc.])
    - For example: `layout-1.png`
    - Or include a list of references (links) in the `README.md`
- [ ] Add a [description and url](https://i.imgur.com/CexeWBQ.gif) to your GitHub repo

- - -

### Extra Credit

`30 points` (`5 points` each)

- [ ] Optimization of images; JPG (`.jpg`) and PNG (`.png`) using [ImageOptim](https://imageoptim.com/mac) and SVG (`.svg`) using [SVGOMG!](https://jakearchibald.github.io/svgomg/)
- [ ] Test document outline for heading and section rank, [HTML5 Outliner](http://gsnedders.html5.org/outliner/), and update any _Untitled Section_ to display a proper heading (`h1`–`h6`) _See also [heading and section rank](https://www.w3.org/TR/html5/sections.html#rank)_
- [ ] Use of HTML viewport meta tag to control layout on mobile browsers
  - `<meta name="viewport" content="width=device-width, intitial-scale=1">`
- [ ] Use of vendor prefixed CSS `-webkit-text-size-adjust: 100%;` to prevent adjustments of font size after orientation changes in IE on Windows Phone and in iOS
  - See [normalize.css](https://github.com/h5bp/html5-boilerplate/blob/6180cd90fca68568353c20cc7f91f5d653583e7f/dist/css/normalize.css#L14-L15)
- [ ] Add a `rel=canonical` link in your webpage to suggest a strong hint to search engines to index the original cite source content. For example: `<link rel="canonical" href="https://en.wikipedia.org/wiki/Verdana">`
  - **Note** — Specify no more than one `rel=canonical` for a page. When more than one is specified, all rel=canonicals will be ignored.
  - See [5 common mistakes with rel=canonical](https://webmasters.googleblog.com/2013/04/5-common-mistakes-with-relcanonical.html)
- [ ] Add a link to your Haiku exercise in your `README.md` under the subheading of "Warm-Up" (It’s a good demo to show off)

## Web Safe Fonts

Select from the safest, most widely supported system fonts on Mac and Win, of the web safe fonts.

### Serif

- [Georgia](https://en.wikipedia.org/wiki/Georgia_(typeface))
  - Matthew Carter, Microsoft, 1993
- [Times New Roman](https://en.wikipedia.org/wiki/Times_New_Roman)
  - Stanley Morrison, *The Times*, 1931

### Sans-serif

- [Arial](https://en.wikipedia.org/wiki/Arial)
  - Robin Nicholas and Patricia Saunders, IBM, 1982
- [Arial Black](https://en.wikipedia.org/wiki/Arial)
  - Robin Nicholas and Patricia Saunders, IBM, 1982
- [Tahoma](https://en.wikipedia.org/wiki/Tahoma_(typeface))
  - Matthew Carter, Microsoft, 1994
- [Trebuchet MS](https://en.wikipedia.org/wiki/Trebuchet_MS)
  -  Vincent Connare, Microsoft, 1996
- [Verdana](https://en.wikipedia.org/wiki/Verdana)
  - Matthew Carter, Microsoft, 1996

### Monospace

- [Courier](https://en.wikipedia.org/wiki/Courier_(typeface))
  - Howard “Bud” Kettler, IBM, 1955
- [Courier New](https://en.wikipedia.org/wiki/Courier_(typeface)#Courier_New)
  -  Redrawn by Adrian Frutiger, IBM, 1961

## Readings & Resources

Copy and paste this section into a new task list `issue` within your repo and title it as “Readings & Resources”. [`#tasklist`](https://github.com/blog/1825-task-lists-in-all-markdown-documents)

**Note:** Prefixed `[ ] →` links are required reading (or viewing). `#readme`

### Web Safe Fonts

- [ ] → [The Myth of web-safe fonts](http://code.stephenmorley.org/html-and-css/the-myth-of-web-safe-fonts/)
- [CSS Font Stack](http://www.cssfontstack.com) (`gte 90%` support on both Mac & Win)
- [CSS Web Safe Fonts](http://www.ianbesler.com/fonts/)

### On Typography

- [ ] → [A Five Minutes Guide to Better Typography](http://pierrickcalvez.com/journal/a-five-minutes-guide-to-better-typography)
- [ ] → [How Typeface Influences the Way We Read and Think](http://theweek.com/articles/463196/how-typeface-influences-way-read-think)
- [ ] → [Typefaces for Dyslexia](https://bdatech.org/what-technology/typefaces-for-dyslexia/)
- [Fonts in Use](https://fontsinuse.com)

### Type Specimens

- [ ] → [Type Specimens (Curated from around the web)](https://typespecimens.io)
- [Daily Type Specimen](http://dailytypespecimen.com/archive)
- [Channel Verdana](https://www.microsoft.com/typography/web/fonts/verdana/)
- [Alma Mono](http://almamono.com)
- [Tofino](http://tofino.losttype.com)
- [Courier Prime](https://quoteunquoteapps.com/courierprime/)
- [Untitled Serif](https://klim.co.nz/retail-fonts/untitled-serif/)
- [The Inter UI font family](https://rsms.me/inter/)
- [Lehigh: A typeface by the LostType Co-op](https://lehigh.losttype.com)
- [Moriston](http://moriston.losttype.com)
- [Source Han Serif: An open source Pan-CJK typeface](https://source.typekit.com/source-han-serif/#story)
- [Tilda: A script typeface Jessica Hische](http://tilda.fontbureau.com)

### Type Terminology

- [Type Terms](https://www.supremo.tv/typeterms/)

### Trebuchet MS

- [The Brief Story of Trebuchet MS](https://www.fonts.com/font/microsoft-corporation/trebuchet-ms/story)
- [Microsoft's In-Depth Story of Trebuchet MS](https://www.microsoft.com/typography/fonts/family.aspx?FID=2)

### Matthew Carter

- [ ] → [Typographically Speaking: A Conversation with Matthew Carter](https://vimeo.com/140351682) `video`
- [ ] → [Matthew Carter: My Life in Typefaces](https://www.ted.com/talks/matthew_carter_my_life_in_typefaces) `video`
- [Interview with Matthew Carter](http://playgallery.org/stories/carter/)

### Web Safe Colors & Contrast

- [ ] →  [Web Safe Colors](http://websafecolors.info)
- [ ] → [What is Color Contrast?](http://a11yproject.com/posts/what-is-color-contrast/)
- [ ] → [Accessible Colors](http://accessible-colors.com)
- [ ] → [Color Safe](http://colorsafe.co)
- [Colour Contrast Analyser](https://www.paciellogroup.com/resources/contrastanalyser/)
- [Color Accessibility Workflows](https://alistapart.com/article/color-accessibility-workflows)

