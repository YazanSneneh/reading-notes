# CSS
  CSS allows you to create rules that specify how the content of
  an element should appear. For example, you can specify that
  the background of the page is cream and the color of text is wite.

## HOW CSS WORKS
   * CSS works by associating rules with HTML elements.
   * Type the name of the element I want to change.
   * These rules govern how the content of specified elements should be displayed.
   * A CSS rule contains two parts: a selector and a declaration.
   * CSS declarations sit inside curly brackets.
   * Each rule is made up of two parts.
   * A property and a value separated by a colon. 
   * You can specify several properties in one declaration, each separated by a    semi-colon.

## WHERE I WRITE CSS
   1. internal: in heading tag create <style> </style> tag and write styles inside.
   2. inline: 
      * target the element i want to apply style on it.
      * add style='' property.
      * write css rules.
   1. external: associate a seperate file.
      * a benefit of external is when i have multi website i apply 1 css to all elements share the same style.
      * seperate file with extention .css e.g. style.css.
      * <link rel='stylesheet' href="style.css">
      * write css inside the style.css.

## BLOCK & INLINE ELEMENTS 
   1. Block level elements look like they start on a new line Examples include the <h1>-
    <h6>, <p> and <div> elements.
    * it take full width of it's parent element.
    * it prevent any element from stacking on the same row before and after.
    * height depends on the content of the element.
    * if you specify dimention style you can customize the above.
   
   2. Inline elements flow within the text and do not start on a new line. Examples 
    include <b>, <i>, <img>, <em> and <span>.
    * it takes the conent width and height.
    * i can't apply margin and padding top or bottom.
    * can't edit hight and width.
    * it take margin and padding right and left only.
    * to customize it flexibaly i must change the display from inline.
    * 
# COLOR
  The color property allows you to specify the color of text inside an element.
  exmaple  element{ color:red;}
## three common ways in which you can indicate your choice of colors
     You can specify any color in CSS in one of three ways:
     1. rgb values.
        These express colors in terms of how much red, green and blue are used to make it up. For example: rgb(100,100,90)
     2. hex codes. 
        hex codes These are six-digit codes that represent the amount of red, green and blue in a color. preceded by a pound or hash # sign. For example: #ee3e80
     3. color names.
        There are 147 predefined color names that are recognized by browsers. For example: DarkCyan.
# background color
  * CSS treats each HTML element as if it appears in a box, and the background-color  property sets the color of the background for that box.
  * You can specify your choice of background color in the same three ways you can specify foreground colors.
# opacity
   * CSS3 introduces the opacity property which allows you to specify the opacity of an element and any of its child elements. and any of its child elements. The value is a number between 0.0 and 1.0.

# SUMMARY
   * Color not only brings your site to life, but also helps convey the mood and evokes reactions.
   * There are three ways to specify colors in CSS: RGB values, hex codes, and color names.
   * Color pickers can help you find the color you want.
   * It is important to ensure that there is enough contrast between any text and the background color (otherwise people will not be able to read your content).
   * CSS3 has introduced an extra value for RGB colors to indicate opacity. It is known as RGBA.
