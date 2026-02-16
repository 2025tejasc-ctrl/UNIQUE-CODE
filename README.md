Research on Frameset and Frame Tag in HTML 

# Introduction 

The <frameset> and <frame> tags were involved in early HTML and were used to enable dividing a web browser window into several sections, each of which was capable of loading an HTML document at the same time. 

This technique was called framing. 

This enabled developers to create layouts like: 

Navigation menu on left 

Content on right 

Header on top 

# Frameset Tag 

The <frameset> tag is responsible for defining the division of the browser window. 

Instead of <body>, frameset pages have <frameset>. 

Syntax <frameset rows=”value”> <frameset cols="value"> 

Example <frameset cols="50%,50%"> 

This vertically divides the page into two equal parts. 

# Frame Tag 

The <frame> tag determines the content displayed in each frame. 

Each frame uses the src attribute to load a different HTML file. 

Syntax <frame src="page.html"> 

# Frameset Attributes 

Attribute	Description rows	Horizontally divides pages Divides page vertically border	Sets border for the frame framespacing	Spacing between frames 

# Attributes of Frame 

Attribute	Description; src	Display page Frame name scrolling yes / no /auto noresize	No resizing 

# Types of frame layouts 

Vertical Frames 

Page is divided into columns. 

2. Horizontal Frames 

Page is separated into rows; 

3. Mixed Frames 

Combination of rows + columns. 

# Advantages 

Several pages in one window 

Navigation using simple layouts 

Reusable menu blocks 

Reduced page reloads 

# Disadvantages 

Inadequate SEO support 

Bookmarking problems 

Problems with printing 

Not mobile friendly 

Accessibility problems 

# Obsolescence (Major) 

Frames are now deprecated in HTML5. 

Modern web designing uses: 

CSS Flexbox 

Css Grid 

<iframe> 

Responsive layouts 

Browsers do not recommend framesets anymore. 

# Conclusion 

The <frameset> and <frame> tags were crucial in early web design since they enabled the display of multiple documents in a single browser window. 

However, because of usability and compatibility issues, they have been phased out in favor of modern layout technologies in HTML5. 
