# jquery.anchor.js
jQuery plugin to scrol from one anchor to the other on key up/down/rigth/left
----

#### Author : Jean-Philippe Beaudet
#### Version: 1.0

#### Usage : 

You have to place anchor html tags in your html document
add script call for jquery.anchor.js AFTER jquery

````
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>jQuery.anchors.js</title>
  </head>
  <body>
    <h1>jquery.anchor.js - jquery plugin </h1>
    <div id="container" class="col">
      <p>focus 1</p>
      <anchor id="1" ></anchor>
      <p>jQuery plugin to scrol from one anchor to the other on key up/down/rigth/left </p>
    </div>
    <div id="container" class="col">
      <p>focus 2</p>
      <anchor id="2" ></anchor>
      <p>jQuery plugin to scrol from one anchor to the other on key up/down/rigth/left focus 2</p>
    </div>
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.2.1/jquery.min.js"></script>
    <script src="js/jquery.anchors.js"></script>
  </body>
</html>

````
