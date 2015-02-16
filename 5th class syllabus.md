5th class
=========

Music: Steve Reich - Music For 18 Musicians

#Review reading
-----

* Student discussion/critique of [The Year's Best Art On The Internet](http://www.fastcolabs.com/3039947/the-years-best-art-on-the-internet)
* Use critique model discussed in class
* Watch videos, review websites

#Internet Graphics Review and cleanup site 

* reducing 8bit/256 colors to 4bit or 1bit GIF (to reduce file size)

#CSS Review

from [CSS intro](http://www.htmldog.com/guides/css/)

Using an external stylesheet
----------------------------

We put styling information inside the STYLE tag within the HEAD or else in an external file linked to within the HEAD.

As a rule, external stylesheets are used for sites with more than 1 page. 

Example styling
---------------

Red paragraphs and blue links.

```
p {
    color: red;
}

a {
    color: blue;
}
```

Color
-----

```
red
rgb(255,0,0)
rgb(100%,0%,0%)
#ff0000
#f00
```

Predefined color names include black, white, aqua, black, blue, fuchsia, gray, green, lime, maroon, navy, olive, orange, purple, red, silver, teal, white, and yellow. transparent 


Background Color

for example yellow text on blue background

```
h1 {
    color: yellow;
    background-color: blue;
}
```
These colors might be a little too harsh, so you could change the code of your CSS file for slightly different shades:

```
body {
    font-size: 14px;
    color: navy;
}

h1 {
    color: #ffc;
    background-color: #009;
}
```

Fonts
-----

* font size
* If the name of a font is more than one word, it should be put in quotation marks, such as font-family: "Times New Roman".
* font-weight states whether the text is bold or normal 

```font-weight: bold``` OR ```font-weight: normal```

* *italics* is dictated with font-style

```font-style: italic``` OR ```font-style: normal```

* text-decoration says whether text has a line over, under or through it

```
text-decoration: underline
text-decoration: overline
text-decoration: line-through
```
but underline should only be used for links

* text-transform changes case such as ```text-transform: uppercase``` or ```text-transform: lowercase```
* Text spacing

```
p {
    letter-spacing: 0.5em;
    word-spacing: 2em;
    line-height: 1.5;
    text-align: center;
}
```

Box Model
---------

* margin and padding are the two most commonly used properties for spacing-out elements. A margin is the space outside something, whereas padding is the space inside something.
* Nesting boxes
* Can be applied to any and everything on your page
* MARGIN BOX > BORDER BOX > PADDING BOX > ELEMENT BOX (such as image or text)

Border Style
------------

* The border around an element is set with ```border-style``` which can be solid, dotted, dashed, double, groove, ridge, inset and outset. 
* border-width sets the width of the border and border-color sets color, duh
e. g. This will make a red dashed border around all HTML secondary headers (the h2 element) that is 3 pixels wide on the top and bottom and 10 pixels wide on the left and right (these having over-ridden the 3 pixel wide width of the entire border).

```
h2 {
    border-style: dashed;
    border-width: 3px;
    border-left-width: 10px;
    border-right-width: 10px;
    border-color: red;
}
```

Update your HTML/Lab
--------------------

* using CSS rules, implement them in your project
* add an external stylesheet and link to it


#Reading
-------

[CSS Intermediate](http://www.htmldog.com/guides/css/intermediate/layout/) - paying close attention to image location and page layout

Assignment
----------
* Introduce Webify project and have students write a design brief