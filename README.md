# ember-animated-headline [![Build Status](https://travis-ci.org/mariogintili/ember-animated-headline.svg?branch=master)](https://travis-ci.org/mariogintili/ember-animated-headline) [![Ember Observer Score](http://emberobserver.com/badges/ember-animated-headline.svg)](http://emberobserver.com/addons/ember-animated-headline)

A small component that animates a list of words :unicorn_face: :sun_with_face:

![](http://i.imgur.com/1VJe1G8.gif)

# Installation

`$ ember install ember-animated-headline`

And don't forget to add the stylesheet to your `app.scss`

```scss
@import "ember-animated-headline";
```

# Usage

| parameter | value            | usage                                   |
|:---------:|------------------|-----------------------------------------|
| `options` | `['one', 'two']` | the collection of values to be rendered |
| `delay`   | `2000`           | The animation delay in ms               |

```handlebars
{{ember-animated-headline options=options delay=delay}}
```

## Installation

* `git clone` this repository
* `npm install`
* `bower install`

## Running

* `ember server`
* Visit `http://localhost:4200`

## Running Tests

* `ember test`
