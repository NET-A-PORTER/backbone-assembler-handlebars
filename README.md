# Backbone.Assembler

Handlebars](http://handlebarsjs.com) mixin for [Backbone.Assembler](https://github.com/NET-A-PORTER/backbone-assembler). 


## Dependencies

* [Handlebars](http://handlebarsjs.com) (>= 1.0)
* [Backbone.Assembler](https://github.com/NET-A-PORTER/backbone-assembler) (>= 0.1)


## Install

Download: [Latest release](https://github.com/NET-A-PORTER/backbone-assembler-handlebars/releases)

Or install using npm:

    $ npm install backbone-assembler-handlebars

Or install using bower:

    $ bower install backbone-assembler-handlebars


## Usage

Browser:

```javascript
_.extend(Assembler.View.prototype, Assembler.HandlebarsMixin);
```

Node:

```javascript
var Assembler = require('backbone-assembler'),
    HandlebarsMixin = require('backbone-assembler-handlebars');
_.extend(Assembler.View.prototype, HandlebarsMixin);
```
