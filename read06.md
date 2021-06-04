# css
CSS stands for Cascading Style Sheets
## Three Ways to Insert CSS
- External CSS
- Internal CSS
- Inline CSS
### External CSS
With an external style sheet, you can change the look of an entire website by changing just one file!

Each HTML page must include a reference to the external style sheet file inside the <link> element
 <link rel="stylesheet" href="mystyle.css">

### Internal CSS
An internal style sheet may be used if one single HTML page has a unique style.

The internal style is defined inside the <style> element 
<style>
body {background-color: linen;}
</style>
### Inline CSS
An inline style may be used to apply a unique style for a single element.

To use inline styles, add the style attribute to the relevant element. The style attribute can contain any CSS property.
<h1 style="color:blue;text-align:center;">This is a heading</h1>