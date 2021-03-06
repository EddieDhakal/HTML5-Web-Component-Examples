# HTML5 Web Component Examples #

This is how I would create HTML5 web components from scratch inspired by [QtQuick QML components](http://doc.qt.io/qt-5/qml-qtqml-component.html).

Creating web components from scratch is not as difficult as you might think it is.
Also it is a fantastic way to learn I suppose.

### Features and Ideal Goals ###
* Easy peasy lemon squeezy to use with no learning curve.
* Uses attributes rather than innerHTML to describe the properties of web components.
* Uses innerHTML to describe the [delegate](http://doc.qt.io/qt-5/qtquick-modelviewsdata-modelview.html#view-delegates) if the web component has one.
* Model driven views.
* Is completely self contained.
* Works out of the box without any complicated setups, external dependencies, build tools, nodejs, npm, bower, gulp, grunt, webpack, browserify, transpilers and all the front end complexities. Life was simple back in old days of web programming and so are web components.
* Works seamlessly with or without any Javascript frameworks.
* No unintended style leakage. Thanks to Shadow DOM.
* No Javascript global namespace pollution.

### What this is not ###
* This is not a framework or going to be a framework like Polymer, XTag, Angular, React etc, however, should work seamlessly with any frameworks out there.
* I will not be supporting the browsers that do not support native web components. If it does not work for your browser, please feel free to include the polyfills.

### Usage ###
Just copy the web component file and use it like shown below.
```
<!doctype html>
<html>
<head>
    <link rel="import" href="signature-pad-0.1.0.html">
</head>
<body>
    <signature-pad></signature-pad>
</body>
</html>
```
It is as simple as that. Done.

**Note**
Please make sure to test it via a `http/https` protocol.
If you have python installed `python -m http.server` will do the job.
Or feel free to use any web server.

### Contribution guidelines ###
You are more than welcome to contribute so long as you don't over engineer and make simple things complicated.