# selectCircular
Select element with a circular design

## Installation

Use bower to install package select-circular.
``bash
  bower install select-circular --save
``

Then in your page add the following references:
``html
  <link rel="stylesheet" type="text/css" href="lib/select-circular/selectCircular.css">
  <script src="lib/select-circular/selectCircular.js"></script>
``

## How to Use

In your html page add a select element with the number of options you need.
For example 5 elements:

``html
<select class="cs-select cs-skin-circular">
  <option value="" disabled selected>Select an activity</option>
  <option value="1">1</option>
  <option value="2">2</option>
  <option value="3">3</option>
  <option value="4">4</option>
  <option value="5">5</option>
</select>
``

Then, in your javascript file you will need to initialize the circular element with the images in an array for each option.
For example an array of 5 elements that match with the select element created before.
Also we can indicate the radio of the circle in pixels. This value is optional. By default will be 100px.

``javascript
var images = ['img/smiley/happy_1.png',
            'img/smiley/happy_2.png',
            'img/smiley/happy_3.png',
            'img/smiley/happy_4.png',
            'img/smiley/happy_5.png'];
SelectCircular(images,100);
``

Thanks
