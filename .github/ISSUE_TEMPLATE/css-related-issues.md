---
name: CSS related Issues
about: issues for those tasks with the appropriate labels and assignee (myself)
title: "[CSS]"
labels: ''
assignees: KristinShuyiHan

---

## CSS checklist:
### 1. General CSS Topics:
 - Comment /* write down comments to make css easier to read */


-   Color /* apply colors to your HTML elements */
    - [ ]  rgb(r, g, b) or rgba(r, g, b, a) /* red, green, blue, alpha values */
    - [ ] #FFF or #FFFFFF /* hex codes */
    - [ ]  hsl(h, s, l) or hsla(h, s, l, a) /* hue, saturation, lightness, alpha values */
    -  [ ] Color name (i.e ‘orange’)

-   [Background Links to an external site.](https://developer.mozilla.org/en-US/docs/Learn/CSS/Building_blocks/Backgrounds_and_borders#styling_backgrounds_in_css)/* apply background styles to your elements */
    - [ ]  background-color

-   [UnitLinks to an external site.](https://developer.mozilla.org/en-US/docs/Learn/CSS/Building_blocks/Values_and_units)  /* units of measurement for sizing and spacing your elements */
    - [ ]  Use 3 unique relative units total      
    - [ ]  Use 3 unique absolute units total

-   [Box ModelLinks to an external site.](https://developer.mozilla.org/en-US/docs/Learn/CSS/Building_blocks/The_box_model) /* configure the containers that holds your HTML content */  
    (“long” and “short” refer to longhand and shorthand syntax and should give the same results. They’re simply different ways to declare your style rules, use at least one of each syntax. Y**ou must use both long and short hand notations for each of the following: margin, padding, border**)
    -   Margin /* spacing between html elements */
        - [ ]  Long (margin-top, margin-bottom, margin-left, margin-right)
        - [ ]  Short ( margin: <top,> <right,> <bottom,> <left,>)
        - [ ]  Auto margins:  margin: auto
    -   Padding /* spacing within html elements */
        - [ ]  Long (padding-top, padding-bottom, padding-left, padding-right)
        - [ ]  Short (padding: <top,> <right, > <bottom,> <left,>)
     -   [BordersLinks to an external site.](https://developer.mozilla.org/en-US/docs/Learn/CSS/Building_blocks/Backgrounds_and_borders#borders)  /* borders around html elements, hint: apply borders before testing out padding and margin to better understand the difference between the two */
         - [ ]  border-style
         - [ ]  border-color
         - [ ] border-width
         - [ ]  border-radius

-   Text /* style your text */
    - [ ]  color
    - [ ]  text-decoration
    - [ ] text-align

-   [DisplayLinks to an external site.](https://developer.mozilla.org/en-US/docs/Web/CSS/display)
    - [ ]  Experiment with these values: none, block, inline-block, inline. Include at least two of them in your page.
    - [ ]  Apply these values to the display property
-   Sizing /* set the height and width for an element */ 
    - [ ]  height
    - [ ]  width
    - [ ]  max-width
    - [ ]  min-width
-   [PositionLinks to an external site.](https://developer.mozilla.org/en-US/docs/Web/CSS/position)  /* element positioning on  page */
    -   2 of the following values: static, relative, fixed, absolute, sticky
        -  [ ] Apply these values to the position property
-   [Pseudo-classLinks to an external site.](https://developer.mozilla.org/en-US/docs/Web/CSS/Pseudo-classes)  /* elements that exist in your document conditionally */
    - [ ]  :hover
    - [ ] :active
-   Layouts
    -   -   [FlexboxLinks to an external site.](https://css-tricks.com/snippets/css/a-guide-to-flexbox/) /* allow your elements to lay themselves out automatically */
            - [ ]  apply flex to the display property
            -  [ ] Must have more than two children within the element that is using flexbox. Must use minimum three of the flexbox related attributes
        -   [Grid Links to an external site.](https://css-tricks.com/snippets/css/complete-guide-grid/) /* instantiate a grid for your layouts */
            -  [ ] apply grid to the display property
            - [ ]  Must have more than two children within the element that is using the grid. Must use a minimum of three of the grid related attributes
-   Responsiveness /* make your website friendly for multiple devices */
    -   At least one query based on the screen width
        -  [ ] [Media QueryLinks to an external site.](https://developer.mozilla.org/en-US/docs/Web/CSS/Media_Queries/Using_media_queries)
-   [FontsLinks to an external site.](https://developer.mozilla.org/en-US/docs/Learn/CSS/Styling_text/Web_fonts)  /* pick varying font styles to make your text fun to read */
    - [ ]  Include and use a 3rd party font ([https://fonts.google.com/Links to an external site.](https://fonts.google.com/)). You can load the font in either your HTML or your CSS
  
    
### 2. CSS selectors:
CSS selectors allow you to select the HTML element you want to style. Each type of selector targets a different identifier on your HTML element. For this lab you must use at least one of every bulleted selector method.

- [ ]  Class Selector (.class)
- [ ]  ID Selector (#id)
- [ ]  Universal Selector (*)
- [ ]  Element Selector (element)
- [ ]  Attribute Selector (e.g. [attribute=foo])  
    
-  [ ] Pseudo-class Selector (e.g.  p:hover)
-  [ ] Selector List (element, element) /* select multiple elements */
- [ ]  Combinators (you must use one of each) /* specify selections based on element positioning in the DOM tree */  
    - [ ]  Descendant Combinator (element element)
    - [ ]  Child Combinator (element > element)
    -  [ ] General sibling combinator (element ~ element)
    - [ ]  Adjacent sibling combinator (element + element)
    - [ ]  Combining Two Selectors (element.class)






## Meeting Minute checklist:

- [ ]  a title (e.g. "Pomodoro Timer First Brainstorm")
- [ ]  subtitle for the meeting section/the topic of the meeting (e.g. "brainstorming", "check-ins", "documentation")
- [ ]   subtitle for the date  
    
- [ ]  attendance list
- [ ]  agenda  of what the meeting will cover
- [ ]  things that were unfinished business from last meeting
- [ ]  things that are new business that need to be talked about
- [ ]   any miscellaneous comments / questions / concerns that anyone would like to bring up
- [ ]  pictures  of any diagrams / architecture / things that were presented
    - [ ]  SWE meetings often have people diagram things on a whiteboard so we want those captured as well
- [ ]  For the following two, you can simply take a 30 second pretend audio recording & video recording to use, we are just trying to get you familiar with the <audio> and <video> elements. Yes, you must have **both**  audio and video elements, and yes, you can use the audio from the video you took for the audio element, it just has to be in a separate audio file.
    - [ ]  audio recording the meeting
    - [ ]  video recording of the meeting
