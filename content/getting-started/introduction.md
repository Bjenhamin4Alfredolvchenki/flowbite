---
layout: home
title: Flowbite - Tailwind CSS component library
description: Get started with an open-source set of UI components and elements built with the utility classes from Tailwind CSS
group: getting-started
toc: true
cleanTitle: true

next: Quickstart
nextLink: getting-started/quickstart/
---

## What is Flowbite?

Flowbite is an open-source library of UI elements based on the utility-first CSS framework Tailwind designed and coded by <a href="https://themesberg.com" target="_blank">Themesberg</a> available in Figma and as web components.

It includes all of the commonly used components that a website requires, such as buttons, dropdowns, navigation bars, modals, but also some more advanced interactive elements such as datepickers. 

All of the elements are built using the utility classes from Tailwind CSS and vanilla JavaScript.

<iframe width="100%" class="my-8 rounded-lg shadow-lg yt-video" src="https://www.youtube.com/embed/4bnJG2UDr9A" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

Here's a quick overview of the Flowbite ecosystem including the open source Tailwind components library, the Figma design files, and the pro version.

<div class="lg:grid lg:grid-cols-2 lg:gap-8 mt-10">
    <a href="{{< ref "getting-started/quickstart" >}}" class="p-6 block bg-white dark:bg-gray-800 dark:hover:bg-gray-700 hover:bg-gray-100 shadow-md border border-gray-200 dark:border-gray-700 rounded-lg mb-6 lg:mb-0">
        <h3 class="text-gray-900 dark:text-white font-bold text-2xl tracking-tight mb-2">Quickstart</h3>
        <p class="font-normal text-gray-700 dark:text-gray-400">Learn how to get started by downloading and configuring Flowbite locally on your machine and start developing.</p>
    </a>
    <a href="{{< ref "components/alerts" >}}" class="p-6 block bg-white dark:bg-gray-800 dark:hover:bg-gray-700 hover:bg-gray-100 shadow-md border border-gray-200 dark:border-gray-700 rounded-lg mb-6 lg:mb-0">
        <h3 class="text-gray-900 dark:text-white font-bold text-2xl tracking-tight mb-2">Components</h3>
        <p class="font-normal text-gray-700 dark:text-gray-400">Explore the Tailwind CSS elements such as buttons, navbars, alerts, dropdowns and use them to build your website.</p>
    </a>
    <a href="https://flowbite.com/figma/" class="p-6 block bg-white dark:bg-gray-800 dark:hover:bg-gray-700 hover:bg-gray-100 shadow-md border border-gray-200 dark:border-gray-700 rounded-lg mb-6 lg:mb-0">
        <h3 class="text-gray-900 dark:text-white font-bold text-2xl tracking-tight mb-2">Figma design files</h3>
        <p class="font-normal text-gray-700 dark:text-gray-400">Prototype and design your website before coding with the Flowbite Figma file which is based on the Tailwind CSS classes.</p>
    </a>
    <a href="https://flowbite.com/pro/" class="p-6 block bg-white dark:bg-gray-800 dark:hover:bg-gray-700 hover:bg-gray-100 shadow-md border border-gray-200 dark:border-gray-700 rounded-lg mb-6 lg:mb-0">
        <h3 class="text-gray-900 dark:text-white font-bold text-2xl tracking-tight mb-2">Upgrade to Pro</h3>
        <p class="font-normal text-gray-700 dark:text-gray-400">Take your Figma and Tailwind CSS development to the next level with thousands more elements and pages with Flowbite Pro.</p>
    </a>
</div>

## Why use Flowbite?

One of the disadvantages of Tailwind CSS compared to other frameworks is that it doesn't have a base set of components. This makes it really hard to quickly prototype a user interface. 

<span class="font-semibold dark:text-gray-200 text-gray-700">This is where Flowbite comes into play</span>: it's basically Tailwind CSS, but you get all of the components that you would normally get with a classic CSS framework like Bootstrap or Bulma.

There are at least 15 types of components including buttons, alerts, breadcrumbs, pagination, and navbars. Flowbite also includes some custom JavaScript that enables interactive components, such as dropdowns, modals, tooltips, and many more.

## Getting started

Flowbite is technically a plugin that can be included into any existing Tailwind CSS project. To get started, you first need to make sure that you have a working Tailwind CSS project installed and that you also have Node and NPM installed on your machine.

### Require via NPM

1. Install the latest version of Flowbite using NPM:

```bash
npm i @themesberg/flowbite
```

2. Include Flowbite as a plugin inside the `tailwind.config.js` file:

```javascript
module.exports = {

    plugins: [
        require('@themesberg/flowbite/plugin')
    ]

}
```

3. Require the JavaScript code that powers the interactive elements before the end of your `<body>` tag:

```html
<script src="../path/to/@themesberg/flowbite/dist/flowbite.bundle.js"></script>
```

If you use Webpack or other bundlers you can also import it like this:

```javascript
import '@themesberg/flowbite';
```

### Tailwind CSS v2.x

Flowbite is fully compatible with the 2.x versions of Tailwind CSS.

### Tailwind CSS v3.x

Feel free to upgrade to version 3 of Tailwind CSS as there are no breaking changes when using the components from Flowbite.

### Include via CDN

If you want to quickly test out Flowbite you can easily include the following CSS and JavaScript files.

Require the following minified stylesheet inside the `head` tag:

```html
<link rel="stylesheet" href="https://unpkg.com/@themesberg/flowbite@{{< current_version >}}/dist/flowbite.min.css" />
```

And include the following javascript file before the end of the `body` element:

```html
<script src="https://unpkg.com/@themesberg/flowbite@{{< current_version >}}/dist/flowbite.bundle.js"></script>
```

Please remember that the best way to work with Tailwind CSS and Flowbite is by purging the CSS classes.

## Figma design files

The components from Flowbite are first conceptualized and designed in Figma using the latest features such as variants, auto-layout, grids, responsive layouts, and more.

Learn more by checking out <a href="https://flowbite.com/figma/" target="_blank">Flowbite's Figma design files</a> and start designing your Tailwind CSS projects before actually coding them.

## Upgrade to Pro

If you want to take your Tailwind development workflow to the next level you can check out the [pro version of Flowbite](https://flowbite.com/pro/) which includes fully coded pages and layouts for application, marketing, and e-commerce user interfaces.

## Licensing

The library of components from Flowbite is open source under the [MIT License]({{< ref "getting-started/license" >}}).

## Contributions

Flowbite is an open source library under the MIT license and anyone who would like to contribute to the codebase or design is welcome to do so. 

Please reach out to us via the <a href="https://github.com/themesberg/flowbite" target="_blank">official Github repository</a> and the main development team will get in touch as soon as possible.

## Discord community

Feel free to join our <a href="https://discord.gg/qAbMDYbE" target="_blank" rel="nofollow">community on Discord</a> to receive help, contribute to the project, or just discuss about Flowbite, Tailwind CSS, and web development in general.

## Authors

- <a href="https://twitter.com/zoltanszogyenyi" target="_blank" rel="nofollow">Zoltán Szőgyényi</a> (web developer)
- <a href="https://twitter.com/RobertTanislav" target="_blank" rel="nofollow">Robert Tanislav</a> (web designer)
- <a href="https://twitter.com/victorcordos" target="_blank" rel="nofollow">Victor Cordos</a> (web developer)