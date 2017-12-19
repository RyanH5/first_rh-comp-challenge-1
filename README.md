Created one main section to contain everything on the page. Linked CSS, the google font I chose, and the meta tag for Media query smooth operation. 

Inside main section created all articles using percentages to fill the viewable height/width and scale in size with the size of the users device. Used h1 and h4 for my text in top left box.

For styling, used complementary color pallete to match the image of Sly. The section of the image is 100vh and 40% width, leaving 60%x100% height for the other articles. This matched the remaining boxes so that each square could be 20% width, and 33.33% height. 

Put a flex display on the .square class so that I could easily center the icons vertically and horizontally. The arrows use absolute positioning and used percentages from the right side to keep them in the same location, so that the user isn't looking around on the page for the Fwd/Prev buttons. 

Used float left for all the articles except the large image. This tactic combined with placing the images in the right order or changing the color pattern to match the static comp worked well. 

Created a media query at 800px. For smaller devices, you scroll through the images. And created a vertical media query just so the text in box #oneOne isn't lost.

-Ryan  # rh-comp-challenge-1
