# ICT 580 - IPP  CSS Assignment 2 (CSS)

## Learning Objectives

The purpose of this assignment is to create two different looking versions of this
website using CSS rules only. Thus, the file *index.html* is not to be edited. 

The primary learning will using CSS to position elements and 


## Note About Measurements

When you are specifying `margin` or `padding` in CSS, the `rem` unit is usually preferred. `font-size` and 
`line-height` may also use `rem`. Widths based on the width of the browser window or device are often given as 
percent (e.g. `max-width: 100%;`). 

When a measurement value is zero, no unit is needed (e.g. `margin: 0;`).


## Note About Verion Control

It is recommended to **save frequently**.  This can be done by downloading
the files from GitPod to your computer by **right clicking** on the file/folder and selecting
download. 

OR

The preferred was is to commit your changes to your GitHub account, see [instructions/git](instructions/git.md) 

## Part 1 - Flex version

In this version flex is used to create a version that adapts to changes in the view, a version that 
is appropriate for a tablet, and with a change in the header would also suite mobile devices.

The focus for this version is on margins, padding, proper usage of CSS selectors, and of course flex
properties.

All changes to be made will be in main.css


### Steps for part 1

1. Specify background colors for the three `article` elements, using the IDs that are 
in the HTML. Each `article` must have a different background color. 

2. Use the `max-width` property to control the width of the paragraph lines.  Note that
`max-width` allows the width of the text areas to shrink as needed. 

3. Assign a white background color to all sections with the `text` class.

4. Make suitable adjustments to `padding`, `font-size` and `line-height` for all sections with the `text` class. 

5. Center the `h2` text in all sections that have the `text` class. Do not use any flex properties to do this. 

6. Make the `article` elements act as flex container, i.e. each `article` will be a flex container. 
Use CSS flex properties to center all the child elements that are inside the container. The paragraph
text is not to be centered. 

7. Style the `footer` and `footer p`

8. Make the `header` element act as a flex container. 

9. Adjust or add `margin` and `padding` values as needed to make the spacing on your page simlar to
   the examples. 

10. Assign suitable text colors and link pseudo class colors for good contrast and legibility *as needed* 
in the articles and sections.

You DO NOT need to use all five pseudo classes. Look at the *main.css* file provided. Those pseudo classes are enough.


### Part 1 notes and tips

Reminder: ** The HTML provided in index.html is **NOT** to be changed.

**Note that a color palette has been provided for you in *main.css*.** it is the expected colour palatte to be used,
the only variation would be for step 10 where colours may need to be adapted for good constrast.

**TIP:** Don't fail to use `box-sizing: border-box` correctly!

**FINISH Part 1 before starting Part 2!** 


## Part 2

A completely different page layout, a version more suitable for a desktop monitor.  Be 
sure to save a copy before starting the second part and that part 1 is completed.

### Preparation

* Copy the file *main.css* and name the new copy *tablet_version.css*. 


### Steps for part 2

1. Edit the `article` rule in your CSS so that the flex container now places the two `section` elements side by side. This is a **horizontal** flex arrangement. You will have to change, remove, and add various flex properties to make this work. You will not need more than two or three different flex properties in this rule.

2. Edit the `section` rule or rules in your CSS so that the two sides are of equal width. This might require adding a flex property you had not used before. This is for you to figure out. Consult the Robbins book.

3. Remove the white background color from all sections with the `text` class.

4. Un-center the `h2` text in all sections that have the `text` class. make sure your `h2` headings look similar to those in the video for the second "Sea Mammals" example.

5. Adjust `margin` and `padding` values as needed to make the spacing on your second "Big Cats" page look as close as possible to the second "Sea Mammals" example. In particular, without the white background on the text section, you will not need the same `padding`.

6. Assign suitable text colors and link pseudo class colors for good contrast and legibility *as needed* in the articles and sections. See step 10 under part 1, above.

**DO NOT USE any CSS layout properties we have not covered,** such as `float`, `position` or `display: grid`.


## Part 3 - Responsiveness

This section adds to the responsiveness into the application.  

Note, we will be making a small change to *index.html* in this part of the assignment.
If no changes were made in Part 1 & 2, this part will go smoothly.

### Preparation

*Copy the file *main.css* and name the new copy *desktop_version.css*. 

## Steps for Part 3

1. Use the code to include *main.css* as a reference to include both 
*tablet_version.css* and *desktop_version.css*

2. In *index.html* remove where *main.css* is being loaded.

3. Add @media queries to *tablet_version.css* and *desktop_version.css* such that
the transition from desktop to the tablet version occurs at 700px


## Part 4 - GitHub

When you have finished, you must **commit and push** to GitHub. **If you have trouble doing this,** a likely reason is that you did not **clone** correctly at the beginning. If you cloned from *my* GitHub.com repo and not *your own,* you'll need to clone all over again. Before doing so, copy your two CSS files into a safe other folder (OUTSIDE your repo) beforehand so you don't lose them.


### Using Git

For more information on how to use [check the git overview](git.md)

## Check the RUBRIC and submit in Canvas

Be sure to [check the rubric](rubric.md) and **SUBMIT THE URL of your GitHub repo in D2L ** to complete this assignment!

The repo URL (at github.com), NOT the github.io URL.
