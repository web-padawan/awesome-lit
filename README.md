# Awesome lit-html [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of awesome lit-html resources.

[lit-html](https://lit-html.polymer-project.org) — an efficient, expressive, extensible HTML templating library for JavaScript.

## Contents

- [General resources](#general-resources)
- [Community](#community)
- [Overview](#overview)
- [Implementations](#implementations)
  - [Renderers](#renderers)
  - [LitElement Extensions](#litelement-extensions)
- [Components](#components)
- [Starter Templates](#starter-templates)
- [IDE Plugins](#ide-plugins)
- [Tools](#tools)
- [Examples](#examples)
- [Videos](#videos)
- [Podcasts](#podcasts)
- [Blogs](#blogs)
- [Inspired Solutions](#inspired-solutions)
- [Other awesome resources](#other-awesome-resources)

## General resources

- [Documentation](https://lit-html.polymer-project.org/guide)
- [GitHub repository](https://github.com/Polymer/lit-html)

## Community

- [lit-html Twitter](https://twitter.com/lit_html)
- [#lit-html](https://polymer.slack.com/archives/lit-html) - Channel in [Polymer Slack](https://polymer-slack.herokuapp.com)

## Overview

- [Lightning-fast templates & Web Components: lit-html & LitElement](https://developers.google.com/web/updates/2019/02/lit-element-and-lit-html)

## Implementations

Sorted by creation date (oldest first).

- [lit-element](https://www.npmjs.com/package/lit-element) - Simple base class for creating fast, lightweight Web Components.
- [@gluon/gluon](https://www.npmjs.com/package/@gluon/gluon) - Lightweight library for building Web Components and applications.
- [lit-any](https://github.com/wikibus/lit-any) - Partials library, which uses lit-html to compose views and forms from smaller templates.
- [lit-html-element](https://www.npmjs.com/package/lit-html-element) - Base class for creating Web Components using lit-html.
- [fit-html](https://www.npmjs.com/package/fit-html) - Combination of lit-html, Web Components and Redux.
- [lit-html-brackets](https://www.npmjs.com/package/lit-html-brackets) - A lit-html extension that uses a bracket syntax similar to Angular's template syntax.
- [@littleq/element-lite](https://www.npmjs.com/package/@littleq/element-lite) - A take on using lit-html and Polymer's property mixin.
- [@popeindustries/lit-html-server](https://www.npmjs.com/package/@popeindustries/lit-html-server) - Render lit-html templates on the server as Node.js streams.
- [ullr](https://github.com/aggre/ullr) - Building Web Components with Functional Programming Using lit-html.
- [@appnest/lit-translate](https://www.npmjs.com/package/@appnest/lit-translate) - Lightweight i18n library providing a lit-html directive.

### Renderers

The following libraries allow using lit-html as a renderer, while also providing alternatives such as [HyperHTML](https://github.com/WebReflection/hyperHTML) or JSX.

- [@corpuscule/lit-html-renderer](https://www.npmjs.com/package/@corpuscule/lit-html-renderer) - lit-html based renderer for [Corpuscule](https://github.com/corpusculejs/corpuscule).
- [@moleculejs/molecule-lit](https://www.npmjs.com/package/@moleculejs/molecule-lit) - lit-html based renderer for [Molecule](https://github.com/Molecule-JS/MoleculeJS).
- [@skatejs/element-lit-html](https://www.npmjs.com/package/@skatejs/element-lit-html) - lit-html based renderer for [SkateJS](https://github.com/skatejs/skatejs).
- [icomponent-lit](https://www.npmjs.com/package/icomponent-lit) - lit-html based renderer for [icomponent](https://github.com/prasannavl/icomponent).

### LitElement Extensions

These are not implementations of lit-html itself but rather community extensions of the official LitElement base class.

- [@dabolus/localized-lit-element](https://www.npmjs.com/package/@dabolus/localized-lit-element) - LitElement extension that provides easy l10n out of the box.
- [@apollo-elements/lit-apollo](https://www.npmjs.com/package/@apollo-elements/lit-apollo) - LitElement integrations with Apollo GraphQL.
- [@morbidick/lit-element-notify](https://www.npmjs.com/package/@morbidick/lit-element-notify) - Small mixin for LitElement to get easy change events via the properties getter.
- [styled-lit-element](https://www.npmjs.com/package/styled-lit-element) - Provides the lit-css integration with LitElement base class.

## Components

- [Material Web Components](https://github.com/material-components/material-components-web-components) - Material Design implemented as Web Components.
- [UI5 Web Components](https://github.com/SAP/ui5-webcomponents) - Enterprise-flavored sugar on top of native APIs!
- [Wired Elements](https://github.com/wiredjs/wired-elements) - Collection of elements that appear hand drawn.
- [Chartjs Web Components](https://github.com/fsx950223/chartjs-web-components) - Web components for chartjs.

## Starter Templates

- [PWA Starter Kit](https://github.com/Polymer/pwa-starter-kit) - Starter template by the Polymer team.
- [open-wc-starter-app](https://github.com/open-wc/open-wc-starter-app) - Starter app based on Open Web Components Recommendations.
- [generator-lit-element-next](https://github.com/motss/generator-lit-element-next) - Generator for developing your next custom element with latest LitElement.

## IDE Plugins

- [VSCode lit-html plugin](https://github.com/mjbvz/vscode-lit-html) - Syntax highlighting and IntelliSense for lit-html template strings.
- [es6-string-html](https://github.com/mydesireiscoma/es6-string-html) - Another VSCode extension which adds syntax highlighting support for HTML in ES6 multiline strings.
- [vim-html-template-literals](https://github.com/jonsmithers/vim-html-template-literals) - Syntax highlighting and indentation for lit-html.
- [TypeScript lit-html Plugin](https://github.com/Microsoft/typescript-lit-html-plugin) - TypeScript server plugin that adds IntelliSense for lit-html template strings.

## Tools

- [babel-plugin-template-html-minifier](https://github.com/cfware/babel-plugin-template-html-minifier) - Babel plugin for minifying HTML in tagged template strings.
- [eslint-plugin-lit](https://github.com/43081j/eslint-plugin-lit) - ESLint plugin for lit-html template strings.
- [rollup-plugin-minify-html-literals](https://github.com/asyncLiz/rollup-plugin-minify-html-literals) - Rollup plugin to minify HTML in tagged template strings.
- [rollup-plugin-lit-css](https://github.com/bennypowers/rollup-plugin-lit-css) - Rollup plugin to import CSS files as LitElement tagged `css` template strings.
- [lit-loader](https://github.com/PolymerX/lit-loader) - LitElement Single File Component loader for Webpack.
- [generator-lit-element](https://github.com/sebs/generator-lit-element) - Yeoman generator for creating LitElement based Custom Elements.
- [Nutmeg](https://github.com/abraham/nutmeg-cli) - CLI tool to build, test, and publish vanilla Web Components with a little spice.
- [open-wc](https://github.com/open-wc) - Set of recommendations to help you generate, test, lint, demo, and publish Web Components.

## Examples

- [lit-demos](https://github.com/open-wc/lit-demos) - Examples for using the lit-html library and LitElement base class.
- [lit-html workshop](https://github.com/LarsDenBakker/lit-html-workshop)

## Videos

- [Efficient, Expressive, and Extensible HTML Templates (Polymer Summit 2017)](https://www.youtube.com/watch?v=ruql541T7gc)
- [lit-HTML (Chrome Dev Summit 2017)](https://www.youtube.com/watch?v=Io6JjgckHbg)
- [VDOM vs lit-html - HTTP203](https://www.youtube.com/watch?v=uCHZJy2n8Qs)

## Podcasts

- [The Web Platform Podcast 159: lit-html - HTML Templates via JavaScript Template Literals](https://thewebplatformpodcast.com/159-lithtml-html-templates-via-javascript-template-literals) -
An episode with the lit-html creator Justin Fagnani.

## Blogs

- [Building a chat with Twilio, lit-html, Parcel and TypeScript](https://dev.to/dkundel/building-a-chat-with-twilio-lit-html-parcel-and-typescript-1jo1)
- [Making a fullstack CRUD app with LitHTML, Redux, Express, and Webpack](https://medium.com/@pascalschilp/making-a-fullstack-crud-app-with-lithtml-redux-express-and-webpack-fe7e5cf8b3ef)
- [The future of Polymer & lit-html](https://43081j.com/2018/08/future-of-polymer)
- [A night experimenting with Lit-HTML](https://lucamezzalira.com/2018/08/14/a-night-experimenting-with-lit-html/)
- [LitElement To Do App](https://medium.com/@westbrook/litelement-to-do-app-1e08a31707a4)
- [A new, lean way of creating web apps](https://medium.com/@kennethrohde/a-new-lean-way-of-creating-web-apps-88a49c5b87ec)
- [LitElement with Rollup, Babel & Karma](https://43081j.com/2018/09/polymer-lit-with-rollup)
- [Let's Build Web Components! Part 5: LitElement](https://dev.to/bennypowers/lets-build-web-components-part-5-litelement-906)

## Inspired Solutions

These libraries do not depend on lit-html, but are inspired by some of its concepts. They use `html` and `css` tagged
template literals, and leverage the benefits of the same or similar [IDE Plugins](#ide-plugins) for syntax highlighting.

- [hybrids](https://github.com/hybridsjs/hybrids) - UI library for creating Web Components with simple and functional API.
- [lit-ntml](https://github.com/motss/lit-ntml) - Lightweight and modern templating for SSR in Node.js, inspired by lit-html.
- [htm](https://github.com/developit/htm) - Hyperscript Tagged Markup: JSX alternative using standard tagged templates, with compiler support.
- [lite-html](https://github.com/ruphin/lite-html) - A modern replacement for VirtualDOM rendering engines.
- [lit-css](https://github.com/lit-styles/lit-styles/tree/master/packages/lit-css#readme) - A tool to distribute styles via ES modules.

## Other awesome resources

**If you want more awesome resources, check the [awesome](https://github.com/sindresorhus/awesome) list!**

---

## License

[![CC0](https://upload.wikimedia.org/wikipedia/commons/6/69/CC0_button.svg)](http://creativecommons.org/publicdomain/zero/1.0/)
