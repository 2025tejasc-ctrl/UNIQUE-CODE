# UNIQUE-TAG

📘 Research on Frameset and Frame Tag in HTML
1️⃣ Introduction

The <frameset> and <frame> tags were used in early HTML to divide a web browser window into multiple sections, where each section could load a different HTML document simultaneously.

This technique was called framing.

It allowed developers to create layouts such as:

Navigation menu on left

Content on right

Header on top

2️⃣ Frameset Tag

The <frameset> tag defines how the browser window is divided.

Instead of using <body>, frameset pages use <frameset>.

Syntax
<frameset rows="value">
<frameset cols="value">

Example
<frameset cols="50%,50%">


This divides the page vertically into two equal parts.

3️⃣ Frame Tag

The <frame> tag defines the content displayed in each frame.

Each frame loads a separate HTML file using the src attribute.

Syntax
<frame src="page.html">

4️⃣ Attributes of Frameset
Attribute	Description
rows	Divides page horizontally
cols	Divides page vertically
border	Sets frame border
framespacing	Space between frames
5️⃣ Attributes of Frame
Attribute	Description
src	Page to display
name	Frame name
scrolling	yes / no / auto
noresize	Prevent resizing
6️⃣ Types of Frame Layouts
1. Vertical Frames

Page divided into columns.

2. Horizontal Frames

Page divided into rows.

3. Mixed Frames

Combination of rows + columns.

7️⃣ Advantages

Multiple pages in one window

Easy navigation layouts

Reusable menu sections

Reduced page reload

8️⃣ Disadvantages

Poor SEO support

Bookmarking issues

Printing problems

Not mobile friendly

Accessibility issues

9️⃣ Obsolescence (Important)

Frames are now deprecated in HTML5.

Modern web design uses:

CSS Flexbox

CSS Grid

<iframe>

Responsive layouts

Browsers no longer recommend framesets.

🔟 Conclusion

The <frameset> and <frame> tags played an important role in early web design by allowing multiple documents in a single browser window. However, due to usability and compatibility issues, they have been replaced by modern layout technologies in HTML5.
