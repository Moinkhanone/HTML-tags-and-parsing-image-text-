# HTML-tags-and-parsing-image-text-
Andriod App
Input: http://www.ndtv.com/
Output: ndtv.mp4       

A video is made up of a number of pictures (called frames), rendered one after another.He wants that you parse the HTML page of the website and create frames out of it. Here's what you need to do:

- Parse the html page to extract out images and save them locally
- Parse the html page to extract out some text and convert it to image (Here's an example:http://stackoverflow.com/questions/18800717/convert-text-content-to-image)

After these two steps, you'll now have a set of images. You just have to create a video out of these images.
Here's an example of a java library xuggler, that helps you create video out of images - http://examples.javacodegeeks.com/desktop-java/xuggler/create-video-from-image-frames-with-xuggler/


