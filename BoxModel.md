Box Model:

the box model has worked like this by default:

width + padding + border = actual visible/rendered width of an element’s box

height + padding + border = actual visible/rendered height of an element’s box

This can be a little counter-intuitive, since the width and height you set for an element both go out the window as soon as you start adding padding and borders to the element.

As responsive design (or, as it was once known, “fluid” or “liquid” layout) started to gain popularity, developers and designers wished for an update to the box model.

Those wishes were granted when the box-sizing property was introduced in CSS3. Though box-sizing has three possible values (content-box, padding-box, and border-box), the most popular value is border-box.

Today, the current versions of all browsers use the original “width or height + padding + border = actual width or height” box model. With box-sizing: border-box;, we can change the box model to what was once the “quirky” way, where an element’s specified width and height aren’t affected by padding or borders. This has proven so useful in responsive design that it’s found its way into reset styles.