# Awesome lit-html [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of awesome lit-html resources.

[lit-html](https://polymer.github.io/lit-html/) — an efficient, expressive, extensible HTML templating library for JavaScript.

## Contents

- [General resources](#general-resources)
- [Community](#community)
- [Implementations](#implementations)
  - [LitElement Extensions](#litelement-extensions)
- [Components](#components)
- [Starter Templates](#starter-templates)
- [IDE Plugins](#ide-plugins)
- [Tools](#tools)
- [Tutorials](#tutorials)
- [Videos](#videos)
- [Podcasts](#podcasts)
- [Blogs](#blogs)
- [Inspired Solutions](#inspired-solutions)
- [Other awesome resources](#other-awesome-resources)

## General resources

- [Documentation](https://polymer.github.io/lit-html/)
- [GitHub repository](https://github.com/Polymer/lit-html)

## Community

- [lit-html Twitter](https://twitter.com/lit_html)
- [#lit-html](https://polymer.slack.com/archives/lit-html) - Channel in [Polymer Slack](https://polymer-slack.herokuapp.com)

## Implementations

Sorted by creation date (oldest first).

- [@polymer/lit-element](https://github.com/Polymer/lit-element) - Ultra-light base class for creating custom elements rendered with lit-html.
- [@gluon/gluon](https://github.com/ruphin/gluonjs) - Lightweight library for building Web Components and applications.
- [@moleculejs/molecule](https://github.com/Molecule-JS/MoleculeJS) - Library for creating fast and reactive Custom Elements.
- [lit-html-element](https://github.com/kenchris/lit-element) - Base class for creating Web Components using lit-html.
- [fit-html](https://github.com/Festify/fit-html) - Combination of lit-html, Web Components and Redux.
- [lit-html-brackets](https://github.com/bgotink/lit-html-brackets) - A lit-html extension that uses a bracket syntax similar to Angular's template syntax.
- [fabys-lit-element](https://github.com/fabysdev/fabys-lit-element) - Base class for creating Web Components using TypeScript and lit-html.
- [@littleq/element-lite](https://github.com/tjmonsi/element-lite) - A take on using lit-html and Polymer's property mixin.
- [@corpuscule/element](https://github.com/corpusculejs/corpuscule) - Small framework based on Web Components and lit-html.
- [@popeindustries/lit-html-server](https://github.com/popeindustries/lit-html-server) - Render lit-html templates on the server as Node.js streams.

### LitElement Extensions

These are not implementations of lit-html itself but rather community extensions of the official LitElement base class.

- [@dabolus/localized-lit-element](https://github.com/Dabolus/localized-lit-element) - LitElement extension that provides easy l10n out of the box.
- [lit-apollo](https://github.com/bennypowers/lit-apollo) - Set of base classes to help create custom elements connected to an ApolloClient cache.
- [@morbidick/lit-element-notify](https://github.com/morbidick/lit-element-notify) - Small mixin for LitElement to get easy change events via the properties getter.

## Components

- [Material Web Components](https://github.com/material-components/material-components-web-components) - Material Design implemented as Web Components.
- [Wired Elements](https://github.com/wiredjs/wired-elements) - Collection of elements that appear hand drawn.

## Starter Templates

- [PWA Starter Kit](https://github.com/Polymer/pwa-starter-kit) - Starter template by the Polymer team.
- [Create-lit-app](https://github.com/thepassle/create-lit-app) - Create lit-html apps with no build configuration.

## IDE Plugins

- [VSCode lit-html plugin](https://github.com/mjbvz/vscode-lit-html) - Syntax highlighting and IntelliSense for lit-html template strings.
- [vim-html-template-literals](https://github.com/jonsmithers/vim-html-template-literals) - Syntax highlighting and indentation for lit-html.
- [TypeScript lit-html Plugin](https://github.com/Microsoft/typescript-lit-html-plugin) - TypeScript server plugin that adds IntelliSense for lit-html template strings.

## Tools

- [babel-plugin-template-html-minifier](https://github.com/goto-bus-stop/babel-plugin-template-html-minifier) - Babel plugin for minifying HTML in tagged template strings.
- [eslint-plugin-lit](https://github.com/43081j/eslint-plugin-lit) - ESLint plugin for lit-html template strings.
- [rollup-plugin-minify-html-literals](https://github.com/asyncLiz/rollup-plugin-minify-html-literals) - Rollup plugin to minify HTML in tagged template strings.
- [lit-loader](https://github.com/PolymerX/lit-loader) - LitElement Single File Component loader for Webpack.
- [generator-lit-element](https://github.com/sebs/generator-lit-element) - Yeoman generator for creating LitElement based Custom Elements.
- [Nutmeg](https://github.com/abraham/nutmeg-cli) - CLI tool to build, test, and publish vanilla Web Components with a little spice.

## Tutorials
- [Efficient Template Rendering Using lit-html](https://alligator.io/web-components/lit-html/)
- [lit-html examples](https://github.com/LarsDenBakker/lit-html-examples)

## Videos
- [Efficient, Expressive, and Extensible HTML Templates (Polymer Summit 2017)](https://www.youtube.com/watch?v=ruql541T7gc)
- [lit-HTML (Chrome Dev Summit 2017)](https://www.youtube.com/watch?v=Io6JjgckHbg)
- [VDOM vs lit-html - HTTP203](https://www.youtube.com/watch?v=uCHZJy2n8Qs)

## Podcasts
- [The Web Platform Podcast 159: lit-html - HTML Templates via JavaScript Template Literals](https://thewebplatformpodcast.com/159-lithtml-html-templates-via-javascript-template-literals) -
An episode with the lit-html creator Justin Fagnani.

## Blogs
- [A bit about lit-html rendering](https://medium.com/@kennethrohde/a-bit-about-lit-html-rendering-2964c50ee56c)
- [Building a chat with Twilio, lit-html, Parcel and TypeScript](https://dev.to/dkundel/building-a-chat-with-twilio-lit-html-parcel-and-typescript-1jo1)
- [Making a fullstack CRUD app with LitHTML, Redux, Express, and Webpack](https://medium.com/@pascalschilp/making-a-fullstack-crud-app-with-lithtml-redux-express-and-webpack-fe7e5cf8b3ef)
- [The future of Polymer & lit-html](https://43081j.com/2018/08/future-of-polymer)
- [A night experimenting with Lit-HTML](https://lucamezzalira.com/2018/08/14/a-night-experimenting-with-lit-html/)

## Inspired Solutions

These libraries do not depend on lit-html, but are inspired by some of its concepts. They also use `html` tagged
template literal, and leverage the benefits of the same [IDE Plugins](#ide-plugins) for syntax highlighting.

- [hybrids](https://github.com/hybridsjs/hybrids) - UI library for creating Web Components with simple and functional API.
- [lit-ntml](https://github.com/motss/lit-ntml) - Lightweight and modern templating for SSR in Node.js, inspired by lit-html.
- [lite-html](https://github.com/ruphin/lite-html) - A modern replacement for VirtualDOM rendering engines.

## Other awesome resources
**If you want more awesome resources, check the [awesome](https://github.com/sindresorhus/awesome) list!**

---

## License

[![CC0](https://upload.wikimedia.org/wikipedia/commons/6/69/CC0_button.svg)](http://creativecommons.org/publicdomain/zero/1.0/)
