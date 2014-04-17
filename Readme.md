*This repository is a mirror of the [component](http://component.io) module [anthonyshort/dom-walk](http://github.com/anthonyshort/dom-walk). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/anthonyshort-dom-walk`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*

# dom-walk

  Walk down a DOM tree

## Installation

  Install with [component(1)](http://component.io):

    $ component install anthonyshort/dom-walk

## API

    var walk = require('walk');

    walk(document.body, function(el, attrs, next){
      // Process the node
      next(); // Next node
    }, function(){
      // Walked all nodes
    });

## License

  MIT
