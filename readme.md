## About this template
This is a new template that features Foundation-Apps Offcanvas component and uses top, left, right, and bottom offcanvas.

PLEASE NOTE:
1). The new offcavass is different from the one we are used to in Foundation Sites but is considerably easier to impliment (Thank you Zurb Gods). However that said, it is much more boilerplate and (unless i'm missing something) lacks alot of styling sexyness.
2). _Settings file allows you to use these for horizontal and vertical scrolling. However I have manually disabled the horizontal scrolling (I dont see it working well with right and left canvas). Also to make this demo pretty. I may later add some sort of horizontal scrolling to the bottom and top canvas...
3). I am also importing icon-bar from FoundationForSites because frankly it works better for APPS then it does for just web. 


 that the new offcanvas has what I consider a padding issue when you will see if you remove the inline style on line 56 in the offcanvas-right.


# Foundation for Apps Template

This is the default template project for Foundation for Apps. It's powered by Node, Gulp, Angular, and libsass. It provides you with a basic template to get started with Angular and Foundation for Apps. If you're already an Angular developer, you may instead want to install the components into your own stack using Bower: `bower install foundation-apps`

## Requirements

You'll need the following software installed to get started.

  * [Node.js](http://nodejs.org): Use the installer provided on the NodeJS website.
  * [Git](http://git-scm.com/downloads): Use the installer for your OS.
    * Windows users can also try [Git for Windows](http://git-for-windows.github.io/).
  * [Ruby](https://www.ruby-lang.org/en/): Use the installer for your OS. For Windows users, [JRuby](http://jruby.org/) is a popular alternative.
    * With Ruby installed, run `gem install bundler sass`.
  * [Gulp](http://gulpjs.com/) and [Bower](http://bower.io): Run `[sudo] npm install -g gulp bower`

## Get Started

Clone this repository, where `app` is the name of your app.

```bash
git clone https://github.com/zurb/foundation-apps-template.git app
```

Change into the directory.

```bash
cd app
```

Install the dependencies. Running `npm install` will also automatically run `bower install` after. If you're running Mac OS or Linux, you may need to run `sudo npm install` instead, depending on how your machine is configured. Running `bundle` will install the correct version of Sass for the template.

```bash
npm install
bower install
bundle
```

While you're working on your project, run:

```bash
npm start
```

This will compile the Sass and assemble your Angular app. **Now go to `localhost:8080` in your browser to see it in action.**

To run the compiling process once, without watching any files:

```bash
npm start build
```