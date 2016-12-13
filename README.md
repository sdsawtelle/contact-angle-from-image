#contact-angle-from-image
\*\* You will need the Image Analysis Toolbox for Matlab \*\*

Change the ‘path’ string to reflect the folder where your image files
are located (possibly on Mac you need to change from ‘\\’ to ‘/’ .

Change the ‘imtype’ string to the correct extension for the type of
image files you have

Run the program – it will loop through your images and for each image it
will pop up a clickable figure where **you need to carefully click three
points in a SPECIFIC ORDER on the contact angle image:**

-   First point: leftmost reflection point of the drop as it meets the
    surface

-   Second point: anywhere on the circumference of the drop (I usually
    do the very top point)

-   Third point: rightmost reflection point of the drop as it meets the
    surface

![](example_pic.png)

Gathering the location of each point first begins by allowing you to
zoom in on the appropriate region by clicking the image as many times as
desired. Once the zoom is appropriate, press ‘Enter’ to turn the zoom
functionality off. The cursor then turns into a cross-hair which you use
to click on the correct point. The image then is reset to fully zoomed
out, the cursor again becomes a zoom-in tool until you press the ‘Enter’
button etc. This occurs until you have input the three necessary points.
The accuracy of the calculation depends on how closely your clicks align
to the correct position on the image.

After you click these three points on an image the program will do the
calculation and draw the chord and tangent lines on the image along with
the extracted angle, so you can visually verify that it isn’t doing
something stupid.

After looping through all the images you are prompted with, the program
will output a .csv containing the filenames and contact angles in
degrees. The program will also plot all the contact angles by Sample \#
for visual inspection.
