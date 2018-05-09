<a href="https://www.npmjs.com/package/switchbox"><img src="https://img.shields.io/npm/dt/switchbox.svg" alt="Total Downloads"></a>
<a href="https://github.com/alexjoffroy/switchbox/releases"><img src="https://img.shields.io/npm/v/switchbox.svg" alt="Latest Release"></a>
<a href="https://github.com/alexjoffroy/switchbox/blob/master/LICENSE"><img src="https://img.shields.io/npm/l/switchbox.svg" alt="License"></a>

# Switchbox
> It's like a checkbox, but more like a switch !

Switchbox replaces your checkboxes with some pretty switches. As written with Sass, you can easily customize them...

## Demo
[http://alexjoffroy.github.io/switchbox/demo/](http://alexjoffroy.github.io/switchbox/demo/)

## Install
```
npm install --save switchbox
```

## Usage
### CSS
```html
<link rel="stylesheet" href="switchbox.css">
<!-- Or minify -->
<link rel="stylesheet" href="switchbox.min.css">
```

### Sass
```scss
// Define variables
$switch-primary-color: blue;
$slider-height: 6px;
// Then import
@import "node_modules/switchbox/src/switchbox";
```

## Development
Clone the repo:
```
git clone https://github.com/alexjoffroy/switchbox.git
```
Install dependencies:
```
cd switchbox && npm install
```
Commands:
```shell
npm run watch     # watches src and build the dist
npm run build 	  # builds the dist
```
