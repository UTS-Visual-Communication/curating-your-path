@meta: \
README.md \
@created: 22/09/2020 10:23 \
@updated: 22/09/2020 12:38 \
@tags: #t&i2 #curating-your-path


# Introduction to The Web

## session overviews

### session 1:

- html & css basics

### session 2:

- a basic responisve grid

### session 3:

- internal and external linking
- bringing everything together


## Week 2: Overview of Class for Session 1

Please take a look through these overviews before class so that you are prepared. If you are not up to speed on basic web programming we suggest working through these steps in your own time.

These short lectures could also be worthwhile watching over the weeks as well http://www.dontfeartheinternet.com/

### Download these files first. These are the files that students will be working with in class

* https://github.com/UTS-Visual-Communication/intro-to-web-resources

### How the web works
* get students to download the example files from GitHub (URL is in the main class website and as above)
* then to open the index.html file in Brackets
* Then use "live preview" to look at the site.
* get them to go to the assignment url (https://uts-visual-communication.github.io/intro-to-web/) it starts with http, explain that this means we are viewing the page over the internet. Basically when you put in a url, your computer requests files from a server that is hosting them, with this basic web page the browser interprets the html and the css files and displays it in the browser window
* the html (stands for hypertext markup language) describes the content of the page (i.e. the text, and what type of content the text is)
* the css (stands for cascading style sheet) styles the page

### Take students through the brief
* Talk students through what is required of them (see brief)
* Ask if they have any questions from the lecture / about the brief

### Take them through subject tools
* They should be using Brackets to edit their code and should be familiar with it by now.
* Ask them what browser they use, we recommend Firefox for its stance against web tracking. But can use Chrome or other browsers if prefer to test out our files
* get them to open the html file up in Brackets
* go through the basic document structure
* html (hypertext markup language) is a markup language
* it uses ‘tags’ to describe or 'mark up' the content of the page
* notice how there are opening tags and closing tags. Tags describe the content that is between their opening and closing
* head tag just contains information about the file that the browser uses to understand the file and display it
* body tag contains information about what to display in the browser window, they will be mainly changing things inside the body tags
* look at the code and change something the h1 tags, and save the file
* then go back to the browser and refresh it, they can see the changes
* each time they make a change they need to save

### Uploading a file to the server

**I am doing a video on uploading to the server. This is a task they will need to complete between this week and next.**
* but please talk them through the notion of working locally & viweing via "live preview" and viewing as a web page.

### Basic HTML elements (i.e. h, p , img)
* get them to drag the 1.1.2-basic-tags folder to the Brackets icon, this shows the whole working folder on the left hand panel of Brackets. Click on index.html
* talk through the different html tags
* When we have everything from a start tag to an end tag, it is is called a HTML element, some html elements have content, which is placed between the tags, some html elements like the br or img elements do not, these tags close and open in the one tag, see the img tag in the example.
* Take a look at the img tag - and the src attribute of the tag. This looks for a image file relative to the index.html file i.e. looking inside the folder called img and find the file xxxxxxx.jpg. Web images usually jpg, png or gif. For now we can get them to stick to jpgs
* They could find a jpg and put it in the img folder and then add another image to the page by copying the img tag there and changing the file name to their new file
* If they image is too large they may need to size the image in Photoshop. There is a link to this quick tutorial on how to do this on UTSOnline > Web Task Tutorials (https://www.taralesher.com/blog/exporting-photoshop-images-for-web)
* Main thing to pay attention to is the WIDTH and HEIGHT of the image in pixels
* Go through each of the tags h1 - h6 is the hierarchy of headings, with h1 the most semantically
* If time get them to open up 1.3-basic-visual-heirachy. HTML tage are semantic, we can see how the different tags denote what types of content the text is and creates a semantic hierarchy of information. The browser also does a basic stylised interpretation of this i.e. headings a bold and of different sizes and paragraph text is regular weight.
* We have also given them the basic file they will be working from (1.4-page-with-copy-text).
* They should now spend some time adding typographic heirachy to 1.1.4-page-with-copy-text

### CSS with focus on typography
* see session.2 > 2.1-basic-text-styling, this file  shows students how they can use css to control the style of the type
* we style our webpages using CSS, cascading style sheet. CSS = Style. HTML = Content.
* we reference an external stylesheet, a CSS file (show them CSS link, and get them to open up the CSS file in the HTML editor)
* take them through how to attach a style to a HTML element i.e. a h1 element
* h1 { } we denote the element we want to style and then have two curly brackets, inside these curly brackets we can style various properties of the element
* i.e. font-style: italic; it's always property: property-value;
* then show them font-family, and explain how their are common web-safe fonts available on machines
* see this link for a list https://www.w3schools.com/cssref/css_websafe_fonts.asp
* get them to set font-family for one of their type elements, it tries to load the first font specified in this list, and if this is not available the next one and so on. i.e. font-family: Arial, Helvetica, sans-serif; see https://www.w3schools.com/cssref/pr_font_font-family.asp
* so you cannot just use any font available on your system, as the person looking at your web page somewhere else might not have that font on their system. we will show them how you can get around this next
* then go through the rest of the properties in the template stylesheet provided
* give them time to play around with these


### How to use web fonts
* what if we want to use fonts that aren't  system fonts?
* then we can use fonts hosted by someone else or host fonts on our server
* for example typekit has web fonts you can use, but you need to pay for them
* for this we will just be using google's web fonts, as they have ok fonts, are easy to use and free, and will give you a sense of how web fonts work
* goto https://fonts.google.com/
* look at a font
* click select this font
* click family selected
* then on customise, here you can select which weight/s you want to use
* get students to pick one weight
* click on embed
* copy the standard embed link i.e. <link href="https://fonts.googleapis.com/css?family=Roboto" rel="stylesheet">
* and get them to paste it above where they import their style sheet, this is so that the fonts are referenced BEFORE they load their own style sheet and use them
* get them to go into their style sheet and for one of their type element tags (i.e. h1) copy the 'specify in css' from Google Fonts i.e. font-family: 'Roboto', sans-serif; as a property for their style
* save the file and refresh their version so they can see if their Google font has loaded
* you can also see example 2.2-web-fonts-example

### For Next Week:
Students are to select a place and create an illustration of it (they can do this anyway, hand-drawn, traced, a collage - and keep it simple!) and bring it in for next week. They should bring a print out of this for next week.

## Week 4: Overview of Class for 13th of August

### What have you illustrated?
* Get students into groups of about 4
* Get them to 'pin-up' their illustrations
* Share what their place is, what category is it? Why do they think it is interesting - what will they write about it?

### Basic Layout
* we can put space between blocks of type within a  element using the line-height property (i.e. within a paragraph), but if we want to create space between different elements i.e. between a h1 and a p, then we need to using padding/margin
* you can imagine each type element like a "block", that spans the width of the web browser
* i.e. if you do h1 {background: yellow;} we can see the 'box', this describes the 'content' area i.e. https://www.w3schools.com/css/css_boxmodel.asp
* if you set the padding i.e. padding: 20px, this will add 20px padding around the entire element on all sides. See what happens
* if we set the margin this creates space between the edge of the box and the next element
* margin is generally the best way to create space between elements
* you can image padding like pillows within a box padding from the edge of the box inside, you can image margins as being like moats, they add space outside from the edge of the box
* if you do margin: 0px 0px 20px 0px; this allows you to set different margins for the different sides of the element. this will put a 20px margin between the h1 element and the p element beneath it. the sides are top right bottom left
* for this you will just be taking them through applying padding and margin to the type elements i.e. adding white space

### For Next Week:
* Students are to work on their web page and to come in with a basic web page for next week, it should have a title, an image (their illustration or a placeholder) and their description. They should work on the detailing of the page. They should bring in a scanned or digital copy of their illustration if they have not placed it in yet.


## Week 5: Overview of Class for 13th of August

### Finishing / Refining (first hour)
* Help students with finishing up their web pages. Students can work on their projects more in the lead up to the portfolio review, but make sure each student has a web page up, and that it is at least a basic presentation of title, an illustration and a description

### Making our Text and Image II map of Sydney (second hour)
* Get students to bring up their web pages on screen and walk around the room and look at each others work
* They can pick two other people's websites that they want to link up with
* A person can only be linked to twice, we'll give you post-its. Each student writes their URL on two post its in front of their computer, if someone wants to link up to them they take the post it. If you have some post its at the end of class gather them up and give them to the next set up classes to use.
* Then take them through how to make a link, and how to link to each other's URLs i.e. a href=
* They are to think about how they want to do the link i.e. is it at the bottom of the page, or is it a word in their text? And what text is used for link i.e. "Another Mystery Structure" or "Nearby you might find..."
* If a student doesn't have a link (or have two), they can go to one of the other class rooms and link up with a student there. Please also keep a couple of URLs from your class to pass on to the next set of classes.
* If a student doesn't have a web page, just get them to work on the 1.4-page-with-copy-text in the examples folder and quickly change the text to their heading / description and add links in here.
* Make sure you have time in class for them to upload their web page and check their links work.
