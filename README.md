# Hands-on-CSS
CSS, or Cascading Style Sheets, tell the browser how to display the text and other content that you write in HTML. With CSS, you can control the color, font, size, spacing, and many other aspects of HTML elements.

Now that you've described the structure of your cat photo app, give it some style with CSS.
## What's CSS? 
After HTML flow you might be searching for something that makes things not better but hte best! And if you choose CSS, you are on the right designation. If HTML is the structure of the house then CSS is the look and feel of the house.
-  It's the language to make our web pages presentable in a effective way.
-  It's designed to make style sheets for web.

#### Now let's try to brek the acronym:
    cascading: Falling of styles
    Style: Adding designs/Styling our HTML tags
    Sheets: Writing our style in different documents
## History
-  1994 : First Proposed by Hakon Wium Lie on 10th October
-  1996: CSS was published on 17th November with influencer Bert Bos
-  Later he became co-author of CSS
-  1996 : CSS became official with CSS was published in December
-  1997 : Created CSS level 2 on 4th November 1998: Published on 12th May
## CSS Editors
-  Atom
-  Brackets
-  Espresso(mac user)
-  Notepad++ 
-  Komodo Edit(Easy&simple)
-  Sublime Text
-  Codepen (It's an online editor that I use)
## Basic Structure:
<p align="center"> <img src="https://user-images.githubusercontent.com/81810889/138478986-7941e96f-3013-43bb-b9e3-5849e20dccef.png" align="center" height="250" width="500" >  </p>

-  Selector: selects the element you want to target
-  There are few basic selectors like tags, id’s, and classes
-  All forms this key - value pair
-  Keys : properties(attributes) like color, font-size, background, width, height,etc
-  Value : values associated with these properties
-  Always remains same whether we apply internal or external styling 
## Comments
-   Comments don’t render on the browser
-   Helps to understand our code better and makes it readable.
-   Helps to debugging our code
-   Two ways to comment: Single line, Multiple line.
## Different ways to write CSS
-  Inline CSS; Internal CSS; External CSS - (3 ways to write CSS in our HTML file)
-  Inline > Internal > External - (Priority order)

### Inline CSS
-   Before CSS this was the only way to apply styles
-   Not an efficient way to write as it has lot a redundancy
-   Self contained 
-   Uniquely applied on each element
-   Idea of separation of concerns was lost
-   Example: 
<p align="center"> <img src="https://user-images.githubusercontent.com/81810889/138479475-57f624ad-d5a5-4f36-b93e-030b90364cc4.png" align="center" height="250" width="500" >  </p>

### Internal CSS

-   With the help of style tag we can apply styles within the HTML file
-   Redundancy is removed
-   But idea of separation of concerns still lost
-   Uniquely applied on single document
-   Example:
<p align="center"> <img src="https://user-images.githubusercontent.com/81810889/138479737-9850749c-c50e-4dc2-a569-e9422c0ac8fe.png" align="center" height="250" width="500" >  </p>

###  External CSS 
-   With the help of <link> tag in head tag we can apply styles
-   Reference is added 
-   File saved with .css extension
-   Redundancy is removed
-   Idea of separation of concerns is maintained
-   Uniquely applied on each document
-   Example:
<p align="center"> <img src="https://user-images.githubusercontent.com/81810889/138480109-5d278234-f570-43ea-ad77-b9d2e133912f.png" align="center" height="250" width="500" >  </p>

## CSS Selectors
-  Selector are used target elements and apply Css 
-  Three simple selectors
     -  Element Selector 
     -  Id Selector
     - Class Selector
-  Id > Class > Element (Priority of Selectors)
### Element Selector 
-  Used to select HTML elements by its name
-  How we do it
<br> h1
{
Color: red;
}<br>
We selected the heading tag and then changed the color property 
i.e text color to red. Now whatever is written in this tag (content) will 
have the text color as red.
### ID Selector
-  ID attribute is used to select HTML element.
-  Used to target specific or unique element 
-  How we do it
<p align="center"> <img src="https://user-images.githubusercontent.com/81810889/138480427-0f4963d8-c653-4a7c-bfa8-0063efa824a5.png" align="center" height="250" width="500" >  </p>

We selected id and then changed the color property i.e text color to 
red. Now whatever is written in this tag (content) will have the text color 
as red 
### Class Selector
-  Class attribute is used to select HTML element
-  Used to target specific class of element 
-  How we do it

<p align="center"> <img src="https://user-images.githubusercontent.com/81810889/138480642-d7b7884e-c7d3-4244-b8d1-0a2bd85b6551.png" align="center" height="250" width="500" >  </p>

We selected class and then changed the color property i.e text color 
to red. Now whatever is written in this tag (content) will have the text 
color as red 

### Universal Selector
-  Wild card character
-  Used to target specific all the elements
-  How we do it
<p align="center"> <img src="https://user-images.githubusercontent.com/81810889/138480826-68cd8f80-1218-441e-93cf-d0abbb007705.png" align="center" height="250" width="300" >  </p>

We selected all the elements then change the color property i.e text 
color to red. Now whatever is written in all the tags (content) will have 
the text color as red
### Group Selector
-  Group selector minimizes code
-  Used to target specific group of elements 
-  How we do it
<p align="center"> <img src="https://user-images.githubusercontent.com/81810889/138480913-1b0c6c5c-8771-4baf-b89a-19012382bfee.png" align="center" height="250" width="300" >  </p>

We selected these elements and then changed the color property i.e 
text color to red. Now whatever is written in these tags (content) will 
have the text color as red
### Descendant Combinator Selector
Combine two or more selectors
● How we do it

<p align="center"> <img src="https://user-images.githubusercontent.com/81810889/138481646-6ca50f30-3fd7-41ea-8745-2b367eb308cd.png" align="center" height="250" width="500" >  </p>

We selected class inside id then changed the color property i.e text 
color to red. Now whatever is written (content) will have the text color 
as red 

### Child Combinator Selector 
-  Combine two or more selectors like Descendant
● It only targets immediate child.
● How we do it
We selected class inside id then changed the color property i.e text 
color to red. Now whatever is written (content) will have the text color 
as red 

### Pseudo-class Selector
-  Used to target state of element
-  How we do it
<p align="center"> <img src="https://user-images.githubusercontent.com/81810889/138482059-9256e415-ed13-4dc6-b5f1-b444f8f20da2.png" align="center" height="250" width="500" >  </p>

We selected element and then changed the color property i.e text 
color to red. Now whatever is written in this tag (content) will have the 
text color as red 
## CSS Color
-  There are different colouring schemes in CSS
-  2 widely used techniques are as follows
   -  RGB
         - This starts with rgb and takes 3 parameter
         - 3 parameter basically corresponds to red, green and blue
         - Value of each parameter may vary from 0 to 255.
         - Eg: rgb(255,0,0); means color red
   -  HEX
         - Hex code starts with # and comprises of 6 numbers
         - which is further divided into 3 sets
         - Sets basically corresponds to Red, Green and Blue
         - A single set value can vary from 00 to ff 
         - Eg: #ff0000 ; means color red
## CSS Background
- There are different ways by which CSS can have effect on HTML elements
- Few of them are as follows:
   -  Color - used to set the color of the background
   -  Repeat - used to determine if image has to repeat or not and if it is repeating then how it should do that
   -  Image - used to set image as the background
   -  Position - used to determine the position of the image
   -  Attachment - It basically helps in controlling the mechanism of scrolling
### CSS Background Demo

<p align="center"> <img src="https://user-images.githubusercontent.com/81810889/138482769-6b09a3f3-28c4-4fb4-a4d3-79b25f19b762.png" align="center" height="350" width="500" >  </p>

## CSS Border
-  Helps in setting up the border for HTML elements
-  There are 4 properties that can help in setting up of border:
    -  Width - sets the width of the border
    -  Style - sets the style of border; Eg: solid, dashed etc.
    -  Color - sets the color of the border
    -  Radius - determines the roundness of the border
-  You can set the border for specifically top, right, bottom and left
-  We can also club top and bottom together and same goes for left and right
   -  Eg: border-width: 2px 5px; sets top and bottom 2px; left and right 5px
-  Border can also be set in a single line
   -  Eg: border : 2px solid blue; 

### CSS Border Example 
<p align="center"> <img src="https://user-images.githubusercontent.com/81810889/138482428-f3c6b847-e22b-423d-a91d-38243a004172.png" align="center" height="250" width="500" >  </p>

## Box Model
-  Every element in CSS can be represented using BOX model
- It helps developer to develop and manipulate the elements
- It consist of 4 edges
   -  Content edge - It comprises of the actual content
   -  Padding edge - It lies in between content and border edge
   -  Border edge - Padding is followed by the border edge
   -  Margin edge - It is outside border and controls margin of the element
   -  Example:
#styled{
border: 2px solid blue;
margin: 5px;
padding: 20px;
width:20px;
height:20px;
