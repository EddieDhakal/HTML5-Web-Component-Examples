# HTML5 Web Component Examples #

This is how I would create HTML5 web components from scratch and yes Im inspired by [QtQuick QML components](http://doc.qt.io/qt-5/qml-qtqml-component.html).

Creating web components from scratch is not as difficult as you might think it is.
Also it is a fantastic way to learn I suppose.

### Features: ###
* Easy peasy lemon squeezy to use with a big fat Zero learning curve. Sometimes Lazy way is the best way.
* Uses attributes rather than innerHTML to describe the properties of web components.
* Uses innerHTML to describe the [delegate](http://doc.qt.io/qt-5/qtquick-modelviewsdata-modelview.html#view-delegates) if the web component has one.
* Model driven views.
* Is completely self contained.
* Works out of the box without any complicated setups, external dependencies, build tools, nodejs, npm, bower, gulp, grunt, webpack, browserify and transpilers. Life was simple back in old days of web programming and so are web components.
* No external dependencies (except a web browser).
* Works with or without any Javascript frameworks.
* No unintended style and script leakage. Thanks to Shadow DOM.

### Usage ###
**Just copy the web component file and use it like shown below.**
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
done.

### Contribution guidelines ###
You are more than welcome to contribute so long as you don't over engineer and make simple things complicated.