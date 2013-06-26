Video.js Zoom Rotate
=======================
A plugin that allows you to set the Zoom level and a rotation for video with [Video.js](https://github.com/videojs/video.js/).

Using the Plugin
----------------
The plugin automatically registers itself when you include video.zoomrotate.js in your page:

    <script src='videojs.zoomrotate.js'></script>

Once you have your video element created, you can activate the zoomrotate plugin. There is 2 possible options rotate and zoom.
It use the CSS scale property and the rotate property.

    video.zoomrotate({
      rotate: 90,
      zoom: 1
      }
    });

Known Issues
------------
It won't work when using the flash fallback.
