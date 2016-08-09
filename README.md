# CastleCSS Buttons Files
![CastleCSS logo @CastleCss.com](https://www.doordarius.nl/castlecss-logo-250.png)

## CastleCSS Framework
The buttons files are part of the [Full CastleCSS Package](https://github.com/CastleCSS/castlecss), you need this, the [castlecss-core](https://github.com/CastleCSS/castlecss) or create your own variables files in order to make castlecss-buttons work.


## How to install
- Install via [NPM](https://www.npmjs.com/): ```npm install castlecss-buttons```
- Require it in your own NPMJS package
- Download or clone the package

## Updating files
CastleCSS is built so it's easy to update, you can just download make it your own as long as you don't ovewrite the core files. 

```npm update castlecss-buttons```

## Documentation
We're currently writing the documentation. Hang on tight!

## Setup
Your project should have a setup similair to this (included in the [Full CastleCSS Package](https://github.com/CastleCSS/castlecss)):
With this you make sure your own variables overwrite the castle-core variables and your setup is still updatable.

```
| Your project/
|
|-- scss/ 
| |-- /* Custom project specific scss files here */
| |-- Main.scss
| |
|-- node_modules/
| | 
| | /*	CastleCSS files included automatically here */
| | castlecss-core/
| | castlecss-buttons/
| | castlecss-etc ;)/
```

### Main.scss
Your main.scss should have a setup similair to this (included in the [Full CastleCSS Package](https://github.com/CastleCSS/castlecss)):

```
/*  core variable files */
@import "path/to/castlecss-core/sass/variables";

/*  Your own variables so they overwrite the core */
@import "variables";

/*  rest of core files */
@import "node_modules/castlecss-core/sass/main";
@import "node_modules/castlecss-buttons/sass/main";

 
/*  Include your own files below this line
    --------------------------------------
*/
```
