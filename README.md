# Browser Extension Template

## Description 

Starting point for a browser extension. This is a template to build a browser extension using TypeScript and React.
For most projects will probably need to modify the `webpack` config files and which `npm` packages are installed

## How to use as is

- `npm i`
- everything should be built in the `src` directory
- `npm start` or `npm build` will build everything in `src` and the bundles will go to the `dist` directory
- from the `dist` directory you can either use `web-ext run` if installed for development
- or you can manually install by loading the `manifest.json` in `dist` into firefox or chrome if built for that

## plans

- Setup for easier develpment to target multiple browsers at once. Chrome first, then investigate Safari.
