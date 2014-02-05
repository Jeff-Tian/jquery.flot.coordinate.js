jquery.flot.coordinate.js
=========================

Flot plugin that adds some extra coordinate axes to flot chart.
---------------------------------------------------------------

**Usage:**

Inside the `<head></head>` area of your html page, add the following lines:
    
```html
<script type="text/javascript" src="http://zizhujy.com/Scripts/flot/jquery.flot.coordinate.js"></script>
```

Now you are all set. This plugin will draw a default coordinate axes for you.

**Online examples:**

http://zizhujy.com/Plotter is using it, you can take a look to get the first impression about what this plugin can do.

**Dependencies:**

- jquery.js
- jquery.flot.js

**Customizations:**

The coordinate type are accessed as strings separated by pipe line '|' through the coordinate option:

```javascript
options{
    coordinate: {
        type: 'rectangular|default', // or 'auto' to make the coordinate auto switch according the current view port.
		ratioXY: 1					// or <null> / undefined
    }
}
```

**Online demos:**

- [Online plotter](http://zizhujy.com/plotter "Online plotter")
- [Online Function Grapher](http://zizhujy.com/functiongrapher "Online Function Grapher")
- [Basic Usage](examples/FlotCoordinate.html "Basic Usage")
- [Auto switch coordinate](examples/FlotCoordinate (auto mode).html "Auto switch coordinate")
- [Keep axes ratio](examples/FlotCoordinate (Keep axes ratio).html "Keep axes ratio")

**Screenshots:**

![Screenshot for jquery.flot.coordinate.js usage](images/jquery.flot.coordinate.png "Screenshot for jquery.flot.coordinate.js usage")