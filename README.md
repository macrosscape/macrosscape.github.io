TO MAKE A BLOG PAGE:

open up TEMPLATE.HTML and copy its contents to a new file

name it something appropriate and easy to remember with a .html at the end

place the content for the page in the singleBlock div towards the bottom

there's a comment inside the block, you can ignore it, it's just there to make things clear

THE TAGS YOU MIGHT NEED:

<a> - Links

Set an href to wherever the link is going to direct to.
If it's an internal link, you can make it relative.
That is, if you're linking from one file (say, index) to another file in the same folder (like scans) you can just say href="scans.html".
Place text or an image inside the tag.
Link text will by default not be highlighted or anything like that on our pages.

Example:
<a href="index.html">Go back to the main page!</html>

<p> - Paragraph

Exactly what it says on the tin. Styled for big text with plenty of spacing between lines.

Example:
<p>A bunch of text that's important enough to take up the whole screen.</p>

<h1> - Header (Biggest)

For the largest and most attention-grabbing page titles and such.

Example:
<h1>Extra! Extra! Read all about it!</h1>

<h5> - Header (smaller)

Use for section headers and logical breaks in the flow of a page.

Example:
<h5>A List Of Links Follows</h5>

<span> - Span (of text)

The simplest tag to use for totally normal text, if it needs styling different from the default.

Example:
<span id="someText">A bunch of text that's not super mega important.</span>

<br> - Line break

Adding a newline or pressing enter doesn't mean anything to HTML, which just reads your file as one big block unless you format it manually. Insert line breaks wherever necessary. Since it's one contained tag that's not enclosing anything, it's written out as <br />.

Example: <br /><br />

<img> - Images!

Probably the most important one of the bunch, with the most moving parts. For every image on our site, we want:
- A source (src="website.org/image.png")
- Alt descriptive text in case things don't load (alt="A picture of a cat")
- A height and width, otherwise it defaults to the maximum size. (height="100" width="100")

So altogether, that looks like:
<img src="header.png" alt="Header Image" width="250" height="250" />

Of course, the width and height will change based on aspect ratio, what the image is, where it is, and what it's being used for.

To embed an image from google drive, get its embed id, and add it to the end of the following URL.
https://drive.google.com/uc?export=view&id=

More to come if the need presents itself.
