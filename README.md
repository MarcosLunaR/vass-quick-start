# Vass Qquick Start

## Stencil: A Compiler for Web Components and PWAs

```bash
npm init stencil
```

[Stencil](https://stenciljs.com/) is a simple compiler for generating Web Components and progressive web apps (PWA). Stencil was built by the [Ionic Framework](http://ionicframework.com/) team for its next generation of performant mobile and desktop Web Components.

Stencil combines the best concepts of the most popular frontend frameworks into a compile-time rather than run-time tool. It takes TypeScript, JSX, a tiny virtual DOM layer, efficient one-way data binding, an asynchronous rendering pipeline (similar to React Fiber), and lazy-loading out of the box, and generates 100% standards-based Web Components that run on both [modern browsers and legacy browsers](#browser-support) back to Internet Explorer 11.

Stencil components are just Web Components, so they work in any major framework or with no framework at all. In many cases, Stencil can be used as a drop in replacement for traditional frontend frameworks given the capabilities now available in the browser, though using it as such is certainly not required.

Stencil also enables a number of key capabilities on top of Web Components, in particular Server Side Rendering (SSR) without the need to run a headless browser, pre-rendering, and objects-as-properties (instead of just strings).

*Note: Stencil and [Ionic](https://ionicframework.com/) are completely independent projects. Stencil does not prescribe any specific UI framework, but Ionic is the largest user of Stencil (today!)*


## Why Stencil?

Stencil is a new approach to a popular idea: building fast and feature-rich apps in the browser. Stencil was created to take advantage of major new capabilities available natively in the browser, such as Custom Elements v1, enabling developers to ship far less code and build faster apps that are compatible with any and all frameworks.

Stencil is also a solution to organizations and library authors struggling to build reusable components across a diverse spectrum of frontend frameworks, each with their own component system. Stencil components work in Angular, React, Ember, and Vue as well as they work with jQuery or with no framework at all, because they are just plain HTML elements.

Compared to using Custom Elements directly, inside of every Stencil component is an efficient Virtual DOM rendering system, JSX rendering capabilities, asynchronous rendering pipeline (like React Fiber), and more. This makes Stencil components more performant while maintaining full compatibility with plain Custom Elements. Think of Stencil as creating pre-baked Custom Elements as if you wrote in those features yourself.


## Getting Started

To create a new project using an interactive cli, run:

```bash
npm init stencil
```

To start developing your new Stencil project, run:

```bash
npm install & npm start
```

To go to the Vass Stencil project [click here](https://github.com/MarcosLunaR/vass-stencil-components)
