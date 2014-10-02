![Quantum Colors Logo](https://dl.dropboxusercontent.com/u/3106750/github/quantum-colors-logo.png)
==============

Use the color palette from Google's [Material Design](http://www.google.com/design/spec/style/color.html#color-ui-color-palette) spec in your Sass projects.

## Installation
* Install via [Bower](http://bower.io)
* [Download](https://github.com/nickpfisterer/quantum-colors) and add to your project manually

## Usage
Import Quantum Colors at the top of your Sass files.

```@import "quantum-colors";
```

With the exception of ```$black``` and ```$white```, all colors use the naming convention presented in the Material Design spec. For example, to use Red 500 as a background color:

```.my-red-thing {
    background-color: $red-500;
}
```

That's all there is to it. If you find any bugs or have suggestions for a future version, please feel free to submit an issue.

## Changelog
**v1.0.0** (10-01-2014):
* First version
* Bower support
* Discoverable on [Sache](http://sache.in)