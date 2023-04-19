# Vite Plugin Lib Inject Styles

This plugin injects styles into the document head.

## Installation

```bash
npm i -D vite-plugin-lib-inject-styles
```

or

```bash
yarn add -D vite-plugin-lib-inject-styles
```

## Usage

To use the plugin, import it in your Vite config file and add it to the plugins array. Here is an example:

```js
// vite.config.js
import injectStyles from 'vite-plugin-lib-inject-styles'

export default {
  plugins: [
    injectStyles(),
  ],
}
```
The plugin will automatically look for CSS files with a .css extension in your project and inject them into your library bundle.

## License

This plugin is licensed under the ISC License. See the LICENSE file for more information.