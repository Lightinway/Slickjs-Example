# Slickjs Carousel Example

Slickjs Carousel is created by Ken Wheeler, the complete slick documentation can be found <a href="http://kenwheeler.github.io/slick/" target="_blank" >here</a>.
<br>
The Slickjs version I used in this example is <strong>1.8.1</strong>.
<br>
For your viewing convenience, I put my CSS and JS all in the HTML file.

<img src="https://github.com/Lightinway/Slickjs-Example/blob/master/img/Slick.png" />

Each object has a title, image, and a lower text for a name. This example is made with only Slickjs with no additional js scripts whatsoever. Most animations are made using CSS.
<dl>
  <h3>The carousel features the following:</h3>
  <dt>Animation</dt>
  <dd>Object focus - transforms when the object becomes the center focus</dd>
  <dd>Transition - carousel sliding animation made from slickjs attributes </dd>
  <dd>Text autoscroll - title element autoscrolls when the object becomes the focus</dd>
  <hr>
  <dt>Functions</dt>
  <dd>Infinite scroll - objects loops back to the first when the carousel gets to the end</dd>
  <dd>Timed autoscroll - carousel will scroll automatically by a selected time interval</dd>
  <dd>Hover to stop autoscroll - carousel will stop when the mouse is hovered over the carousel</dd>
  <dd>Click to select - click on any object and the carousel will make that object the focus</dd>
  <dd>Keyboard nav - Use the left and right arrow key to control the carousel when the carousel is selected</dd>
  <dd>Hide long text - Titles overflowed will be hiddden with ellipsis</dd>
  <hr>
  <dt>Responsive</dt>
  <dd>When screen width > 1200px - feature 5 object</dd>
  <dd>When screen width < 1200px - feature 3 object</dd>
  <dd>When screen width < 767px - feature 2 object</dd>
  <dd>When screen width < 480px - feature 1 object</dd>
</dl>

<h3>Bugs</h3>
<dl>
  <dt>Animation</dt>
  <dd>From what I noticed, it seems like when the object loops back (last object back to the first one), the .slick-center class selection breaks for ~300ms by selecting a wrong object. It fixes itself and refocuses to the correct object after that small time period. This slickjs bug causes my carousel to have a weird animation when it transitions from the last element back to the first. Please let me know if you have/found a fix for this.</dd>
</dl>
