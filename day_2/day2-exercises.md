There are three main types of lists in HTML: ordered, unordered, and definition. What are their differences?

  Ordered lists are numbered in an order such as 1-5.  Unordered lists use bullet points (or another symbol) to make lists that are in no particular order. definition lists contain terms and their definitions, usually in o particular order.

What is the basic structure of an element used to link to another website?

```
<a href = "https://www.google.com">Google</a>
```
What attribute should you include in a link to open a new tab when the link is clicked?

```
target = "_blank"
```
  You should let the user know that they are about to be brought to a new window.


How do you link to a specific part of the same page?

  We label points of the code with the "id" attribute and then use the a href format but instead of an URL we use "#idname".  The "#" must be put in front of the id you are making a link for.


What is the purpose of CSS?

  To determine the color and format of our webpages.  It controls the text stylings and the backgrounds behind elements.


What does CSS stand for? What does cascading mean in this case?

   Cascading Style Sheets.  This refers to when a browser does not support a command or font or color then we provide within our code a second option for how to display the page.  If the secind option is not available then we "cascade" down to the next option.

What is the basic structure of a CSS rule?

```
h2 {
  font-family: Arial;
}
```

How do you link a CSS stylesheet to your HTML document?

  ```
<head>
<link href="mycsssheet.css" type="text/css" rel="stylesheets" />
</head>
  ```

When is it useful to use external stylesheets as opposed to using interal CSS?

  You should use external sheets in almost all cases because it provides uniformity for the site and prevents use from having to retype the same thing many times.  Internal should only be used on one page websites

Describe what a color hex code is.

  It is a six digit code referring to RBG values.  First two numbers refer to Red, the third and fourth letter rep. green, and the last two letters refer to the blue value.

What are the three parts of an HSL color property?
  Hue, Saturation, Lightness

In the world of typeface, what are the three main categories of fonts? What are the differences between them?

  1. Serif = These have extra accents or details on the ends of the letters. This is better for long texts.

  2. Sans-Serif = These have no extra detail. Then end of each letter is straight. Better for smaller texts.

  3. Monospace = All letters are the same width. Good for coding because it keeps everything aligned vertically


  When specifying font-size, what are the main three units used?

  * Pixels = about 72 per inch (12px)
  * Percentages = Relation to computer settings, default on most computers is 16px (%50 = 8px)
  * Ems = How many "m" widths (1em usually is 16px so 2em is 32px)
  * Points = Each point is 1/72 of an inch and the standard is 16pt. Used for printable pages
