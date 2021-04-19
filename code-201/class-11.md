# Images
## Controlling sizes of images in CSS
#### You can control the size of an image using the width and height properties in CSS, just like you can for any other box. Specifying image sizes helps pages to load more smoothly because the HTML and CSS code will often load before the images, and telling the browser how much space to leave for an image allows it to render the rest of the page without waiting for the image to download.You might think that your site is likely to have images of all different sizes, but a lot of sites use the same sized image across many of their pages. 

## Centering images Using CSS
#### By default, images are inline elements. This means that they flow within the surrounding text. In order to center an image, it should be turned into a blocklevel element using the displayproperty with a value of block. Once it has been made into a block-level element, there are two common ways in which you can horizontally center an image:
1. On the containing element, you can use the text-alignproperty with a value of center.
2. On the image itself, you can use the use the margin property and set the values of the left and right margins to auto.

## Background Images
#### The background-imageproperty allows you to place an image behind any HTML element. This could be the entire page or just part of the page. By default, a background image will repeat to fill the entire box.The path to the image follows the letters url, and it is put inside parentheses and quotes.

## Repeating Images
#### The background-repeat property can have four values:
1. repeatThe background image is repeated both horizontally and vertically (the default way it is shown if the backgroundrepeat property isn't used).
2. repeat-xThe image is repeated horizontally only (as shown in the first example on the left).
3. repeat-yThe image is repeated vertically only.
4. no-repeat The image is only shown once.

## Background Position
#### When an image is not being repeated, you can use the background-position property to specify where in the browser window the background image should be placed. This property usually has a pair of values. The first represents the horizontal position and the second represents the vertical.

## shorthand
#### The background property acts like a shorthand for all of the other background properties you have just seen, and also the background-color property. The properties must be specified in the following order, but you can miss any value if you do not want to specify it.
1. background-color
2. background-image
3. background-repeat
4. background-attachment
5. background-position

## Image Rollovers & Sprites
#### Using CSS, it is possible to create a link or button that changes to a second style when a user moves their mouse over it (known as a rollover) and a third style when they click on it. This is achieved by setting a background image for the link or button that has three different styles of the same button (but only allows enough space to show one of them at a time). You can see the image we are using in this example on the right. It actually features two buttons on the one image.When the user moves their mouse over the element, or clicks on it, the position of the background image is moved to show the relevant image.

## CSS3: Gradients
#### CSS3 is going to introduce the ability to specify a gradient for the background of a box. The gradient is created using the background-image property and, at the time of writing, different browsers required a different syntax.Since it is not supported by all browsers, it is possible to specify a background image for the box first (which would represent the gradient) and then provide the CSS alternatives for browsers that support gradients.

##### To learn more about images, read duckett html book, ch16.

# Practical Information

## Search Engine Optimization (SEO)
#### SEO is a huge topic and several books have been written on the subject. The following pages will help you understand the key concepts so you can improve your website's visibility on search engines.

## On-Page SEO
#### In every page of your website there are seven key places where keywords (the words people might search on to find your site) can appear in order to improve its findability.
1. Page Title
2. URL / Web Address
3. Headings
4. Text
5. Link Text
6. Image Alt Text
7. Page Descriptions

## How to Identify Keywords and Phrases
#### Determining which keywords to use on your site can be one of the hardest tasks when you start to think about SEO. Here are six steps that will help you identify the right keywords and phrases for your site.
1. Brainstorm
2. Organize
3. Research
4. Compare
5. Refine
6. Map

## Analytics: Learning about your Visitors
#### As soon as people start coming to your site, you can start analyzing how they found it, what they were looking at and at what point they are leaving. One of the best tools for doing this is a free service offered by Google called Google Analytics.





