- 👋 Hi, I’m @leisuze9967

``` javascript
    updateBrushOpacity = evt => {
    const updatedRadius = Number(evt.target.value);
    const brushRadius =  cornerstoneTools.getModule('segmentation').configuration.radius
    if (updatedRadius !== brushRadius) {
      const module = cornerstoneTools.getModule('segmentation');
      module.setters.radius(updatedRadius);
    }

```
