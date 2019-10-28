# google-homepage
From The Odin Project's [curriculum](http://www.theodinproject.com/courses/web-development-101/lessons/html-css)
odin-project
My attempt at recreating google homepage

about href="#"
Hyperlink placeholders: #
An example where a hyperlink placeholder makes sense is within template previews. 
On single page demos for templates, I have often seen <a href="#"> so that the anchor tag is a hyperlink, 
but doesn't go anywhere. 
Why not leave the href property blank? A blank href property is actually a hyperlink to the current page. 
In other words, it will cause a page refresh. As I discussed, href="#" is also a hyperlink, and causes scrolling. 
Therefore, the best solution for hyperlink placeholders is actually href="#!" 
The idea here is that there hopefully isn't an element on the page with id="!" 
(who does that!?) and the hyperlink therefore refers to nothing - so nothing happens.

About anchor tags:
Another question that you may be wondering is, 
"Why not just leave the href property off?". 
A common response I've heard is that the href property is required, 
so it "should" be present on anchors. 
This is FALSE! The href property is required only for an anchor to actually be a hyperlink! Read this from w3. 
So, why not just leave it off for placeholders? 
Browsers render default styles for elements and will change the default style of an anchor tag that doesn't have the href property. 
Instead, it will be considered like regular text. It even changes the browser's behavior regarding the element. 
The status bar (bottom of the screen) will not be displayed when hovering on an anchor without the href property. 
It is best to use a placeholder href value on an anchor to ensure it is treated as a hyperlink.