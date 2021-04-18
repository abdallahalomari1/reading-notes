# introduction
# How javascript makes web pages more interactive?
1. Access content : 
**You can use JavaScript to select any 
element, attribute, or text from an 
HTML page.**
* example: the content of the page
2. MODIFY CONTENT:
**You can use JavaScript to add 
elements, attributes, and text to the 
page, or remove them.**
* example: the content of the page
3. PROGRAM RULES:
**You can specify a set of steps for 
the browser to follow (like a recipe), 
which allows it to access or change the 
content of a page**
* example:  rules or instructions the browser can follow
4. REACT TO EVENTS:
**You can specify that a script should run 
when a specific event has occurred**

# HTML and css
**Html element** 
* <tagname>Content goes here...</tagname>
1. opening tagname
2. closing tagname
3. property value
4. property name 
# expreesion
**An expression evaluates into (results in) a single value. Broadly speakingthere are two types of expressions**
1. EXPRESSIONS THAT JUST ASSIGN A VALUE TO A VARIABLE
* example:var color = 'beige'; 
**The value of color is now beige**
2. EXPRESSIONS THAT USE TWO OR MORE VALUES TO RETURN a SINGLE VALUE.
**example:var area = 3 * 2;** 
**The value of area is now 6**
# CSS Associates Style rules with HTML elements
* cSS works by associating rules with HTML elements. These rules govern how the content of specified elements should be displayed. A CSS rule contains two parts: a selector and a declaration p {font-family: Arial;}
# Here you can see a simple web page that is styled using CSS
1. * <link> chapter-10/using-external-css.html HTML
The <link> element can be used 
in an HTML document to tell the 
browser where to find the CSS 
file used to style the page. It is an 
empty element (meaning it does 
not need a closing tag), and it 
lives inside the <head> element. 
It should use three attributes
2. * href This specifies the path to the CSS file (which is often placed in a folder called css or styles)
3. * typeThis attribute specifies the type of document being linked to. The value should be text/css
4. * relThis specifies the relationship between the HTML page and the file it is linked to. The value should bestylesheet when linking to a CSS file
# Using Internal CSS
* <style>You can also include CSS rules within an HTML page by placing them inside a <style> element, which usually sits inside the <head> element of the page. 

#  Why use ExternalStyle Sheets
1. * All of your web pages can share the same style sheet
2. * Therefore, once the user has downloaded the CSS stylesheet, the rest of the site will load faster

# ch11(color)
# Foreground Color
**The color property allows you to specify the color of text inside an element. You can specify any color in CSS in one of three ways**
1. rgb values
**These express colors in terms of how much red, green and 
blue are used to make it up**
2. hex codes
**These are six-digit codes that represent the amount of red, green and blue in a color, preceded by a pound or hash # sign**
3.color names
**There are 147 predefined color names that are recognized 
by browsers**
# Background Color
**CSS treats each HTML element as if it appears in a box, and thebackground-color property sets the color of the background for that box.**