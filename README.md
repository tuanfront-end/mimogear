#Mimogear

Mimogear is a simple static site generator and a development framework. It provides an environment for distributing html template files to the root of your site and a framework to help you write postcss/css and javascript with complete focus.

##Tools Used in Mimogear

The main goal of Mimogear is to strike a balance between simplicity and features, to secure quality and consistency, and to be as developer friendly as possible. To achieve those goals, there are a few tools under the hood. Mimogear uses [gulp](http://gulpjs.com/) as a task runner, [pug](https://pugjs.org/api/getting-started.html) as a HTML pre-processor, [postcss](http://postcss.org/) as a CSS post-processer, and standard javascript.

###[Gulp](http://gulpjs.com/) Features

* Pug to html compilation
* Postcss to css compilation with autoprefixing and minification
* JS concatenation and uglification
* Image optimization
* SVG Sprite Generation
* Browsersync auto reloading

###Javascript Features

* [Slideshow/Sail](http://codepen.io/mimoduo/pen/gabWmN)
* [Accordion/Harmonica](http://codepen.io/mimoduo/pen/epZaMq)
* [Lightbox/Lantern](http://codepen.io/mimoduo/pen/EPerjv)
* [classList](https://github.com/remy/polyfills) polyfill
* [html5shiv](https://github.com/aFarkas/html5shiv) polyfill

###[Postcss](http://postcss.org/) Features

* [Postcss-simple-grid](https://github.com/iamfrntdv/postcss-simple-grid) integration with flexbox
* Common helper utilities: clearfix, cover, font-face, media etc.
* Functions for calculating ems and rems
* [Idiomatic css](https://github.com/necolas/idiomatic-css) formatting

###[Pug](https://pugjs.org/api/getting-started.html) Features

* Starter template
* Well structured head element setup
* Several starter partials: address, article, table
* Accessibility measures added into pug partials from: (https://github.com/nhall/Accessible-Components)
* SVG symbol mixin to complement the svg sprite

##Browser Support

| Chrome | Firefox | Safari | IE* | Opera |
|--------|---------|--------|-----|-------|
| 29+    | 29+     | 6.2+   | 10+ | 16+   |

\* Excludes harmonica support

##Installation

Mimogear uses the node package manager to download all the required dependencies. By downloading and installing [node.js](https://nodejs.org/en/) onto your machine, you'll be able to run a set of commands we'll use to help setup Mimogear's environment. Now that you've installed node, let's enter in the following to get us started.

```sh
cd <folder-of-Mimogear> (drag the folder into your terminal)
npm install
gulp
```

##Optional Installation Steps

If you'd like to dive on the daring side and see some subtle task runner performance improvements, there is an alpha gulpfile that mirrors the tasks of the stable gulpfile. To use this new gulpfile, make sure to download the alpha version of gulp and the newly separated gulp-cli globally. Afterwards, rename the gulpfile-alpha.js to gulpfile.js and rename the original gulpfile to a name of your choice.

```sh
npm install gulpjs/gulp-cli -g
```

##Share Your Sites Using Mimogear

If you have used Mimogear and you'd love to share it here, feel free to create a pull request and add it to the list below.

* [mimogear](http://mimoduo.github.io/Mimogear/)

##Thank You, Everyone!

I hope you enjoy developing with Mimogear as much as I have enjoyed building it! Please share it if you love it! This static site generator framework wouldn't be possible without all the help of my friends. They've contributed to every single aspect of this without knowing it ^w^ Most notably [Nick Hall](https://github.com/nhall) for being the best mentor in the world!
