# Microverse Learning References
I'm organizing the content found on Microverse Programa

***
## CSS
#### CSS3 Basic
[Shay Howe on the Basics of HTML/CSS.](https://learn.shayhowe.com/html-css/building-your-first-web-page/)<br>
Basic Concepts of Selects -> Select By elements, by classes, by ID.
_Introduces the ideia of using **Using CSS Resets**._


[The Skinny on CSS Attribute Selectors](https://css-tricks.com/attribute-selectors/)<br>
Presents how to select by attributes [rel="value"] -> 
Introduces some best case of how to use each of them.
> [href$=".pdf"] { background: url(icon-pdf.png) left center no-repeat} gives a pdf icon to every link that ends with .pdf

[Play Time: Dynamic Selection](http://flukeout.github.io/)<br>

#### Box Model
[Opening the Box Model](https://learn.shayhowe.com/html-css/opening-the-box-model/)<br>
It presents how to interpreter the Box Model =><br>
The most interesting part was to set the attribute 
 box-sizing: border-box;
 So when we set width: 400px, margin: 10px, padding: 10px,
 the total width will be 400px;

[The CSS Box Model ](https://css-tricks.com/the-css-box-model/)<br>
A CSS Tricks article abouta how to interpret the block and inline displays =><br>
Basically, **every element in web design is a rectangular box**


### Floats and Positioning
[CSS Floats 101](https://alistapart.com/article/css-floats-101/)<br>
It introduces the concept of the _Normal Flow_ => <br>
Basically, when a float: left, right is applyed, it gets out of the normal flow and <br>
sticks to the left/right. They go from stacking on top of each other to sitting next to each other.

[CSS Positioning 101](https://alistapart.com/article/css-positioning-101/)<br>
Positining introduces the concept of moving the elements around in a relative ou absolute way. <br>
The coolest part is the use of absolute, which we can use to fix our element wherever we want.
**Things to Pay Attention** The use of positioning creates new position references.<br>
_Thus if we have div2 inside div1 and set div2 to absolut top:0, it will go to the top of div1._

[Learn CSS Positioning in Ten Steps](http://www.barelyfitz.com/screencast/html-training/css/positioning/)<br>
It teaches us in a interactive way ways of using positioning to create layouts.
