# qkCryptoJS [![Build Status](https://travis-ci.org/Jakehp/qkCryptoJS.svg?branch=master)](https://travis-ci.org/Jakehp/qkCryptoJS) [![Coverage Status](https://coveralls.io/repos/Jakehp/qkCryptoJS/badge.svg?branch=master&service=github)](https://coveralls.io/github/Jakehp/qkCryptoJS?branch=master) [![Dependency Status](https://david-dm.org/Jakehp/qkCryptoJS.svg)](https://david-dm.org/Jakehp/qkCryptoJS)
A Quantum Key Distribution system, based on BB84, using emulated photons and channels.

# Project Roadmap
1. Bit & Basis Generation :white_check_mark:
2. Sending & Receiving Of Basis :white_check_mark:
3. Shared Key Generation :white_check_mark:
4. Key Reconciliation :white_medium_small_square:
5. Sending & Receiving Of Decision :white_check_mark:

# Build Steps
* Install [nodejs](http://nodejs.org/).
* git clone https://github.com/yeswici/qkCryptoJS.git
* Open terminal and navigate to source code directory
* Command ```npm install```
* Command ```gulp test```
* Command ```npm start```
* Command ```node sample.compiled.js```

# See test coverage in editor
* Install [wallaby](http://wallabyjs.com/) for your edtior; I recommend [Atom](https://atom.io/).
* ```Control + Shift + P```, command ```Wallaby: Focus Panel```
* Click Start button

## Tech Used
[browserify](http://browserify.org/) - CommonJS Loader/Bundler  
[watchify](https://github.com/substack/watchify) - Browserify watcher  
[babel/babelify](https://babeljs.io/) - es6 transpiler  
[mocha](https://mochajs.org/) - JS test framework  
[chai](http://chaijs.com/) - Assertion library
