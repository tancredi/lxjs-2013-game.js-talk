
## LXJS 2013 - A web dive into game development

**Talk slides and resources**

> This repo contains the slides for my LXJS 2013 talk and a list of useful resources (Frameworks, tools, etc..) for HTML5 game development.


### Slides intructions

The slides are built using [Reveal.js](http://lab.hakim.se/reveal-js/#/) and need a few steps to run

#### Global dependencies

* **[Grunt](gruntjs.com)** - `sudo npm install -g grunt-cli`

1. Clone the repo - `git clone git@github.com:tancredi/lxjs-slides.git`
2. `cd lxjs-slides`
3. Run the server - `grunt serve`

Now you can see the slideshow by opening your browser at [localhost:8000](http://localhost:8000)


## Resources

### Frameworks & Game Engines

A list of HTML5 game frameworks, with brief descriptions and feature sets

#### [ImpactJS](http://impactjs.com/)

One of the most popular game frameworks, really simple to setup and use - perfect for 2D platformers.
Costs $99 and includes the Weltmeister level editor.

It has a large community and selection of plugins, extensions, etc..

* Features a level editor
* Large community, adoption and support
* Integrates basic physics
* 2D graphics support
* Renders with Canvas

#### [Turbulenz](https://turbulenz.com/)

Free and open-source framework, especially great for 3D games, inclusive of HTML5 SDK and easy-to-use social features.

Hosts and publishes your game in a developer-friendly environment and allows to easily monetise your game.

It also include a large variety of tools for pretty much anything you need (Physics, sound, etc..)

* Complete abstraction between game logic and rendering engine
* Large bundle of ready-to-use tools
* Integrated 2D and 3D physics engines
* 2D & 3D graphics support
* Renders using Canvas or WebGL

#### [Quintus](http://html5quintus.com/)

Open-source, modular, light-weight and easy-to-use engine for 2D HTML5 games.

Renders using Canvas.

* Easy to use
* Support for [Tiled](http://www.mapeditor.org/) map editor
* 2D graphics support
* Renders using Canvas

#### [Phaser](http://www.photonstorm.com/phaser)

Open-source game engine with support for canvas

* Develop using Javascript or Typescript
* Based on Flixel, Flash framework
* Integrates a light-weight and hi-performance platformer physics engine
* 2D graphics support
* Renders using [Pixi](https://github.com/GoodBoyDigital/pixi.js/) with either Canvas or WebGL


### Physics Engines

#### [Box2DWeb](https://code.google.com/p/box2dweb/)

Self-contained JavaScript Box2DFlash 2.1a ported from ActionScript with a custom compiler.

My personal choice when it comes to Box2D ports.

#### [Box2DJS](http://box2d-js.sourceforge.net/)

Box2DFlashAS3 1.4.3.1 ported to JavaScript in automated fashion.

Modular, but ported from an old version of Box2D

#### [Ammo.js](https://github.com/kripken/ammo.js/)

A [Bullet]](http://bulletphysics.org/wordpress/) automated port from C++ to JavaScript.

Ideal for 3D physics

### [Cannon.js](https://github.com/schteppe/cannon.js)

A JavaScript native physics engine inspired by Ammo.js and Three.js.

Ideal for 3D games, although still at an early stage.

#### [Verlet-js](http://subprotocol.com/verlet-js/)

A light-weight JavaScript physics engine.

One of the few native JavaScript physics engines, ideal for 2D physics.

### Rendering Engines & Other Libraries

#### [Pixi](https://github.com/GoodBoyDigital/pixi.js/)

Open-source highly-optimised and performant 2D rendering library inclusive on WebGL and Canvas renderers and a really simple unified API.

#### [CreateJS](http://www.createjs.com/):

A suite of JavaScript libraries to take care of rendering and animating with Canvas and DOM, handle assets loading and audio.

#### [Three.js](http://threejs.org/)

Open-source library for 3D rendering that takes the pain away from WebGL.

Easy-to-use, widely adopted, well documented and rich of examples.


### Utilities

#### [Tiled](http://www.mapeditor.org/)

A free map editor, flexible and easy to use, with support for orthogonal and isometric maps.

Great for top-down games, platformers, isometric games and more.

#### [ShoeBox](http://renderhjs.net/shoebox/)

A free Adobe Air app offering a variety of small tools for game development.

Includes utilities to handle spritesheets, tilemaps, bitmap fonts, stretchable sprites, split and export PSD files and more.
