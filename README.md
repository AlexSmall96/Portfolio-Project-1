Website for a vegan fine dining restaurant based in Edinburgh, Scotland

1.After uploading the about image, I realised it wasn't in line with the hero image. (see issue_1.png)
I tried adjusting the margin on the hero image, and also styling the about section, but I realised the issue was due to the limit on the width of the hero image. As I wanted to use this picture as my hero image, I decided to wrap the body in a div that takes up a smaller percentage of the total width of the screen, and colour the remainder grey. 

2.I noticed the opening hours section and the contact section were spilling over the main body div into the grey background. (see issue_2.png) I realised this was because the links section above it was missing its closing tag.

3.After adding text to the about section, I checked to see if it would look good at a smaller window size. I noticed the text was spilling into the sections below, to fix this I added a scroll feature so the user can scroll down to read the remaining text when the browser window is resized.

4.I wanted the cover text box to be centered vertically and horizontally in the hero image, but also wanted this to be consistent with resizing the browser window. The below page provided code which provided a partial solution to this, as the code uses percentages to position the div.
https://blog.hubspot.com/website/center-div-css. However, the cover text was only aligned horizontally. The solution came from changing.
 
top: 50%;
transform: translate(0, -50%);
 
to
 
top: 50%;
left:50%;
transform: translate(-50%, -50%);
