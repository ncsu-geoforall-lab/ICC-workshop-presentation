<div class="reveal">

<div class="slides">

<section>

### Analytics and visualization with

## GRASS GIS, Blender and Tangible Landscape

#### Vaclav Petras, Anna Petrasova, Payam Tabrizian, Brendan Harmon, Helena Mitasova

[NCSU](http://www.ncsu.edu/ "North Carolina State University") [OSGeoREL](http://geospatial.ncsu.edu/osgeorel/ "NCSU OSGeo Research and Education Laboratory") at [Center for Geospatial Analytics](http://geospatial.ncsu.edu/ "Center for Geospatial Analytics")

July, 2017

</section>

<section>

## What to expect?

*   Intro to GRASS GIS, Blender, Tangible Landscape
*   Visualizing landscapes with GRASS GIS

*   batch visualization

*   Enhance your visualizations with 3D modeling in Blender
*   Tangibly explore landscapes

</section>

<section>

## GRASS GIS

</section>

<section>

## GRASS GIS

*   developed since 1984 as open source
*   runs everywhere (from Raspberry Pie to supercomputers, 32/64bit)
*   highly interoperable (Python, R, GDAL, QGIS)

![](img/modeler_skyview.png)</section>

<section>

## GRASS GIS: functionality

*   raster and 3D raster (volume) processing
*   vector topological processing and network analysis
*   imagery processing
*   spatio-temporal data handling

![](img/hexagons_python_editor.png)</section>

<section>

## GRASS GIS as geospatial development platform

*   user-contributed addons in Python, C, C++
*   specialized analyses in the fields of geomorphology, hydrology, landscape ecology, land change modeling, object segmentation, ...

![](img/geomorphons.jpg) <small>Landform classification with addon [r.geomorphon](https://grass.osgeo.org/grass72/manuals/addons/r.geomorphon.html)</small></section>

<section>

## Blender

</section>

<section>

## Blender

*   Free and open source 3D modeling and game engine software

![](img/blender.jpg)</section>

<section>

<div style="text-align:left">

*   Easy scripting with Python

</div>

![](img/interface.JPG)</section>

<section>

<div style="text-align:left">

*   Addons for importing and publishing Geospatial data

</div>

![](img/blendergis.JPG) ![](img/sketchfab.JPG)

<div style="text-align:left"><p2>                   BlenderGIS addon                                             Sketchfab addon</p2>
</div>

</section>

<section>

<div style="text-align:left">

*   Real-time realistic rendering and Immersion at the viewport

</div>

![](img/ive.jpg) ![](img/realism.JPG)

<div style="text-align:left"><p3>   Virtual-reality addon with Oculus Dk2                  Real-time Cycles rendering</p3>
</div>

</section>

<section>

## Tangible Landscape

</section>

<section>

### Tangible Landscape: real-time coupling with GIS

<iframe data-autoplay="" <iframe="" width="560" height="315" src="https://www.youtube.com/embed/Cd3cCQTGer4?rel=0&amp;showinfo=0;loop=1&amp;playlist=Cd3cCQTGer4" frameborder="0" allowfullscreen=""></iframe>![](img/system_schema.png)

Tangible Landscape couples a digital and a physical model through a continuous cycle of 3D scanning, geospatial modeling, and projection.

</section>

<section>

## Applications

![](img/applications_summary.png)</section>

<section>

### Immersive Tangible Landscape Modeling

![](img/planting.jpg)

Real-time updating a georeferenced 3D model of the landscape based on user interaction with Tangible Landscape

</section>

<section>

### Software Architecture

![](img/coupling_diagram.jpg)</section>

</div>

</div>

<div class="parent-page">[![](img/home.svg)](https://github.com/ncsu-osgeorel/lecture-slides-template "Go to the repository")</div>

<script>// Full list of configuration options available here: // https://github.com/hakimel/reveal.js#configuration Reveal.initialize({ // Display controls in the bottom right corner controls: false, // Display a presentation progress bar progress: true, center: true, // Display the page number of the current slide slideNumber: false, // Enable the slide overview mode overview: true, // Turns fragments on and off globally fragments: true, // The "normal" size of the presentation, aspect ratio will be preserved // when the presentation is scaled to fit different resolutions. Can be // specified using percentage units. // width: 960, // height: 700, // Factor of the display size that should remain empty around the content margin: 0.05, // increase? // Bounds for smallest/largest possible scale to apply to content minScale: 0.5, maxScale: 5.0, theme: Reveal.getQueryHash().theme, // available themes are in /css/theme transition: Reveal.getQueryHash().transition || 'none', // default/cube/page/concave/zoom/linear/fade/none // Push each slide change to the browser history history: true, // Enable keyboard shortcuts for navigation keyboard: true, // Vertical centering of slides center: true, // Enables touch navigation on devices with touch input touch: true, // Loop the presentation loop: false, // Flags if the presentation is running in an embedded mode, // i.e. contained within a limited portion of the screen embedded: false, // Number of milliseconds between automatically proceeding to the // next slide, disabled when set to 0, this value can be overwritten // by using a data-autoslide attribute on your slides autoSlide: 0, // Stop auto-sliding after user input autoSlideStoppable: true, // Enable slide navigation via mouse wheel mouseWheel: false, // Hides the address bar on mobile devices hideAddressBar: true, // Opens links in an iframe preview overlay previewLinks: false, // Transition speed transitionSpeed: 'default', // default/fast/slow // Transition style for full page slide backgrounds backgroundTransition: 'none', // default/none/slide/concave/convex/zoom // Number of slides away from the current that are visible viewDistance: 3, // Parallax background image //parallaxBackgroundImage: '', // e.g. "'https://s3.amazonaws.com/hakim-static/reveal-js/reveal-parallax-1.jpg'" // Parallax background size //parallaxBackgroundSize: '' // CSS syntax, e.g. "2100px 900px" // Optional libraries used to extend on reveal.js dependencies: [ { src: 'lib/js/classList.js', condition: function() { return !document.body.classList; } }, ] });</script>
