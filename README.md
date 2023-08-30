# Project 1: HTML and CSS[^1]

## Problem 1

Create a single HTML docment that presents two different appearances, determined by the document's CSS stylesheet. Your HTML file should be called ```index.html``` and the document's title should be “Project #1”. Along with this HTML document, you should also create two stylesheets called ```styleA.css``` and ```styleB.css```.

If the HTML file links to ```styleA.css``` then it should appear like this ("Version A"):

![](https://github.com/btdobbs/WA/blob/main/Project/01/p1vA.png)

If the HTML file links to styleB.css then it should appear like this ("Version B"):

**Note: The D in the screenshot is highlighted to show you what space the text should occupy. Your solution should not style the D with a blue background.**

![](https://github.com/btdobbs/WA/blob/main/Project/01/p1vB.png)

### Style A Specifications

- There should be six box elements, lined up vertically.
- All boxes are centered horizontally and equally spaced vertically. When the browser window is resized, the spacing between the boxes should change (they should be equally spaced vertically across the page). However, the boxes themselves should never overlap or change size.
- Each box is 100x100 pixels, with a 1px line (color: #687291) on top. Text is centered horizontally.
- Boxes alternate colors (colors: #dfe1e7, #eeeff2).
- The final element (color: #687291) has a 4px, black border and the text is centered vertically.
- The font in all elements is Tahoma, 40 pixels.

### Style B Specifications

- Five box elements, lined up horizontally in the top left corner.
- Boxes do not wrap with window resizing (i.e. Boxes A through E should stay on the same line even if your browser window is too small to display them all).
- The last box is positioned in the bottom right corner of the window and stays there even when the window resizes.
- Each box is 100x150 pixels (color: #eeeff2), with a 10px dotted line (color: #D0D0FF) on the left. Boxes are separated by 10 pixels of space.
- When hovering over a box, the cursor changes to a hand and the box and font colors change (colors: yellow, goldenrod, respectively).
- The font in all elements is Tahoma, 40 pixels.
- There are 10 pixels of space between the letters and the edge of the box.

If a property is not outlined in these specifications (e.g. space between elements in style B and edge of window) you should choose something reasonable.

## Style

Your HTML file must be a valid XHTML 1.0 document that passes validation at [http://validator.w3.org](http://validator.w3.org). In addition, your HTML and CSS must be clean, readable, properly indented, and well-structured.

## Extra Credit

Create a third stylesheet ```styleC.css``` that utilizes 2 of the following:

- gradients
- transitions
- animations
- web fonts
- shadows

## Resources

- Use the Chrome browser for this project, and for all projects in this class. This will eliminate browser compatibility issues.
- You may need basic knowledge of Unix in order to submit your assignments. Click [here](https://github.com/btdobbs/AI/blob/main/Project/Terminal.md) for an introduction to browsing and manipulating the UNIX file system.
- You may **not** use any JavaScript or external libraries/stylesheets. You must write your own code.

## Hints

- You may find some of the following CSS style attributes useful for this project (do a Google search for the documentation for exact usage details):
  ```css
  display: inline-block;
  height: 100%;
  white-space: nowrap;
  ```
- You will need to use the [CSS Flexbox layout](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Flexible_Box_Layout) for at least one portion of the assignment.

## Submision

Use the submission guidelines from [project 0](https://github.com/btdobbs/WA/tree/main/Project/00) to submit.  

Your respository should include the following updated files.

- ```index.html```
- ```styleA.css```
- ```styleB.css```
- (optional) ```styleC.css```

[^1]: [Stanford Computer Science](https://cs.stanford.edu)
