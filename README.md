# Shade

Simple dark theme for [Ghost](http://github.com/tryghost/ghost/) 1.x.

## Features

- Fully hackable
- Offcanvas sidebar
- [Flexgrid](https://github.com/moso/flexgrid)
- Bootstrap 4 components
- Websafe fonts: [Roboto Slab](https://fonts.google.com/specimen/Roboto+Slab) for headings and [Roboto](https://fonts.google.com/specimen/Roboto) for main text
- Syntax highlighting with [PrismJS](https://github.com/PrismJS/prism) and selfmade theme inspired by [Predawn](https://github.com/jamiewilson/predawn)
- Source included

DEMO: You can find a live example here: [shade.moso.io](https://shade.moso.io).

## Editing the source
Install the node modules:
`npm install` or `yarn install`

Do your edits, and then compile the Sass to CSS and bundle the JS with webpack:
```
npm run dev
```

To get watch running:
```
npm run watch
```

To compile for production which includes minification of both CSS and JS:
```
npm run production
```

## Issues?
Please report any issues and missing stuff.
