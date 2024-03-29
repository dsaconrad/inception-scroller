#Tilted Page Scroll
Create a beautilful 3D tilted scrolling effect for your website with jQuery Tilted Page Scroll.

[![Tilted Page Scroll](http://www.thepetedesign.com/images/tiltedpage_scroll_image.png "Tilted Page Scroll")](http://iconrad.website/projects/inception/)

## Demo
[View demo](http://iconrad.website/projects/inception/)

## Compatibility
Modern browsers such as Chrome, Firefox, and Safari on both desktop and smartphones have been tested. I have not tested this on IE.

## Basic Usage

With this plugin, you can create a beautiful scrolling effect and turn a simple layout website into something surprising. 

To do this, first you have to include the latest jQuery library together with `jquery.tiltedpage_scroll.js` and `tiltedpage_scroll.css` into your document's `<head>`. Now lay out your HTML markup as follows:


````html
<div class="main">
  <section class="page1">
    ...
  </section>
  <section class="page2">
    ...
  </section>
  ...
  <section class="last-page">
    ...
  </section>
</div>
````

That's it for the HTML part. Isn't that easy? Now, you can just call the function like this, and watch the magic happens:

````javascript
  $(".main").tiltedpage_scroll({
    sectionContainer: "> section",     // In case you don't want to use <section> tag, you can define your won CSS selector here
    angle: 50,                         // You can define the angle of the tilted section here. Change this to false if you want to disable the tilted effect. The default value is 50 degrees.
    opacity: true,                     // You can toggle the opacity effect with this option. The default value is true
    scale: true,                       // You can toggle the scaling effect here as well. The default value is true.
    outAnimation: true                 // In case you do not want the out animation, you can toggle this to false. The defaul value is true.
  });
````

Now you will have another cool way to showcase your website to your viewers. I hope you find this free plugin useful.
## Other Resources
- Tutorial (Coming Soon)
