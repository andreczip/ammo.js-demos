ammo.js-demos
=============

--- Code structure ---
src/
   Contains code for the demo framework, which makes ammo.js collaborate with a WebGL scenegraph.
demos/
   The actual demos in their own subfolders.
other/
   External libs such as ammo.js, jquery, scenegraph libs

--- Howto: Add a new Demo ---
Create a folder with a unique name in demos/, eg. MyDemo. Copy js and html files from some other demo into your new folder and use as a template.

--- Todo ---
Template demo with explanations
Make SceneJS_ShapeDrawer support more shapes
Support for more WebGL scenegraphs - Three.js? Extend the ShapeDrawer class (see SceneJS_ShapeDrawer for reference)