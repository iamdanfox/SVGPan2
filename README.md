SVGPan2
=======

Zoom, pan and drag svg elements, no jQuery required.
Demo: <http://iamdanfox.github.io/SVGPan2/>

Normal Usage
------------
Add the `SVGPan.js` file to your page.
```javascript
elem = document.getElementsByTagName('svg')[0]
var svgPan = SVGPan(elem)
```
Customise Options
-----------------
```javascript
var svgPan = SVGPan(elem, {
  enablePan: true,
  enableZoom: true,
  enableDrag: false,
  zoomScale: 0.2
})
```
You can even adjust options on the fly:
```javascript
svgPan.enablePan = false
```

Remove Capabilities
-------------------
```javascript
svgPan.removeHandlers()
```
Credit
------
Based on work by Andrea Leofreddi
