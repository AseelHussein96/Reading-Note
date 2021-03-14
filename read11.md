# image in html 
The <img> tag is used to embed an image in an HTML page. Images are not technically inserted into a web page; images are linked to web pages. ... src - Specifies the path to the image. alt - Specifies an alternate text for the image, if the image for some reason cannot be displayed.
In HTML, you can add images in a webpage using the <img> tag. The <img> is an empty tag which means it does not have a closing tag. This tag requires some set of attributes to specify the size, alignment, and other properties of an image.
### Making CSS Set Background Image
The CSS background-image adds images as backgrounds of HTML elements. Such backgrounds can either be images. The background image url() lets you set any image as the background.
### Adding Multiple Pictures
One element can have multiple background images in CSS. You need to separate them by commas and remember that the images stack on one another. The first image is the main layer, meaning that other pictures are behind it.Another option is to apply the background shorthand and include all styling properties for the background in one declaration
### Setting background-size
The background-size styling property has three possible values:
- auto: the default value which tells the browser to decide the best size for the background image.
- cover: this value guarantees that the background image always covers the whole container (even if the image needs to be stretched or cut).
- contain: this value indicates that the actual image size needs to be shown even if it does not fill the container.
### Sizes of Multiple Pictures
The background-size property accepts multiple values to set the sizes for several background images. The sizes apply according to the position of background images in the declaration list.
### Full-Size Website Background
Sometimes it is necessary to make the background image in CSS to always cover the whole browser window.

The following example aims to do the following things:

- Images fill the whole page and leave no whitespace.
- Images are scaled if necessary.
- The image is centered on the page.
- Images do not trigger a scroll bar.
- Images keep their proportions.
> This example follows these steps:
1- Use the <html>.
2 -Center the background image and set a fixed position for it.
3 -Set the background-size to cover.
4- However, this technique has issues in Internet Explorer. Therefore, we offer you an alternative of making CSS set a centered background image and keeping its aspect ratio even though the image covers the whole page.
  
### Positioning Background Images
The background-origin property allows us to position the CSS background image according to the content, borders, or padding.
This property accepts three values:
. border-box: positions the image to be relative to the border box.
. padding-box: (the default value) positions the image to be relative to the padding box.
. content-box: positions the image to be relative to the content box.

![ Image ](https://i.pinimg.com/originals/03/9f/02/039f0200ea6f073df03027a955184dc8.jpg)

# Practical Information 
