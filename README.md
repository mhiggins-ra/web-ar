# web-ar
The purpose of this repository is to demonstrate some different approaches to browser based augmented reality and to provide some basic demos to help get others up to speed quickly.

## Directory structure
<pre>
.
├── demos  
    ├── marker-based        # Demos that require the use of a marker to display ar elements in the browser
        └── ...
    ├── markerless          # Demos that run in the browser without the need for markers
        └── ...
    ├── resources           # Assets/resources shared among the demos
        ├── markers         # Contains markers to be used with the marker-based demos
            └── ...
        ├── models          # 3d models shared among the demos
            └── ...
</pre>

**To view the markerless demos you need to use one of Google's experimental browsers that support ARCore or ARKit. Follow instructions for ARCore ([here](https://github.com/google-ar/WebARonARCore)) and ARKit ([here](https://github.com/google-ar/WebARonARKit)).**
