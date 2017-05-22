# Jquery-drag-element
Lightweight jquery Drag() plugin

<h2>jQuery Drag()</h2>
A jQuery plugin that adds cross-browser dragging support.

In order to use the plugin, simply bind the "drag" event to an element. 

Here is an example:

// Basic dragging a div
<pre>
$("div").drag();
</pre>



// Restricting dragging to an x-axis
<pre>
$("div").drag({
  axis: 'x'
});
</pre>


// Restricting dragging to an y-axis
<pre>
$("div").drag({
  axis: 'y'
});
</pre>



// Restricting dragging to it's parent container (boundary)
<pre>
$("div").draggable({
  parentDiv: true
});
</pre>
