# claremont-rebuild
Home of the Claremont Rug Rebuild

## dependencies
1. NodeJS

## installation
1. clone this repo
2. open terminal and navigate to project root
3. run "npm install"
4. run "gulp watch"
5. make the internet

## files breakdown
### CSS
SASS files are using the SCSS file format and are automatically compiled in to CSS while running the gulp watch command. CSS files will be automatically prefixed for backwards compatibility. SASS files are located in /src/sass/

### JavaScript
The only JavaScript used in this are two plugins
* Tooltipster for custom tooltips on non text based buttons
* jQuery-SelectBox for custom select/option boxes

The plugins are located in /webapp/static/js/vendor/
Plugins are initialized in /webapp/static/js/scripts.js

### Image Sprites
It didn't look like the design intended for the icons to be font bases, so I went ahead and made sprite files for the icons. I've included the psds for easy addition or modification.
PSDS for sprites are located in /src/sprites.






