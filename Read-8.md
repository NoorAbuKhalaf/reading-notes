# how to make your web pages more attractive, controlling the design of them using CSS.
CSS allows you to create rules that specify how the content of an element should appear.

CSS allows you to create rules that control the
way that each individual box (and the contents of that box) is presented.

## Example Styles
1. boxes - width, height ... etc
2. text - typeface, color ... etc
3. specific - lists, tabels ...etc

# CSS works by associating rules with HTML elements.
A CSS rule contains two parts: 
1. a selector:  indicate which
element the rule applies to.
2. a declaration: sit inside curly brackets and each is made up of two
parts: a property and a value,

![radingn-notes](https://puzzleweb.ru/en/images/css/1_1.png)

# example code for external CSS 
<!DOCTYPE html>
<html>
<head>
<title>Using External CSS</title>
<link href="css/styles.css" type="text/css"
rel="stylesheet" />
</head>

## CSS rules usually appear in a separate document, although they may appear within an HTML page.

# color
Color can really bring your pages to life.
The color property allows you
to specify the color of text inside
an element. You can specify any
color in CSS in one of three ways:
1. rgb values
2. hex codes
3. color names
 
 like this example code 
 /* color name */
h1 {
color: DarkCyan;}
/* hex code */
h2 {
color: #ee3e80;}
/* rgb value */
p {
color: rgb(100,100,90);}

# background-color
You can specify your choice of background color in the same three ways you can specify foreground colors

## Understanding Color
Every color on a computer screen is created by mixing amounts of red,
green, and blue. To find the color you want, you can use a color picker.

## CSS 3: HSL Colors
1. hue 
2. saturation 
3. lightness

## hsla (a it's related to alpha which means opacity )

CSS3 has introduced an extra value for RGB colors to
indicate opacity. It is known as RGBA.

CSS3 also allows you to specify colors as HSL values,
with an optional opacity value. It is known as HSLA.




