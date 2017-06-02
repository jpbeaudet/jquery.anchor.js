# jquery.anchor.js
jQuery plugin to scrol from one anchor to the other on key up/down/rigth/left
----

#### Author : Jean-Philippe Beaudet
#### Version: 1.0.4

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

You can change the tags to scroll from by modifying the _tag global at the start of the script, 
you can also change the starting list index, you can pass multiple tags in an array to select 
more than one element type . 

by accesing the _tag and _status global , you can also user the $.fn nextTag and previousTag directly in jquery with any selector

````

$('selector').nextTag('#id', _status)
$('selector').previousTag('#id', _status)

````
