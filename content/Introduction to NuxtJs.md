+++
title = "Introduction to Nuxt.js"
date = 2020-01-30
tags = ['JavaScript', 'Vue', 'Nuxt', 'Node']
description = 'Nuxt is a progressive framework based on Vue.js to create modern web applications. It is based on Vue.js official libraries (vue, vue-router and vuex) and powerful development tools (webpack, Babel and PostCSS). Incrementally adoptable, it can be used to create from static landing pages to complex enterprise ready web applications'
+++

### What is NuxtJs?

> _Nuxt is a progressive framework based on Vue.js to create modern web applications. It is based on Vue.js official libraries (vue, vue-router and vuex) and powerful development tools (webpack, Babel and PostCSS). Incrementally adoptable, it can be used to create from static landing pages to complex enterprise ready web applications._

---

### Why Nuxt?

- Write Vue Files (\*.vue)
- Server-Side Rendering
- Improved Routing System
- Managing <head> elements like (<title>, <meta>, <link>, etc)
- Pre-processor for Sass, Less, ...

Nuxt.js includes the following in order to create a rich web application development environment:

- Vue 2
- Vue Router
- Vuex (only when using the store option)
- Vue Server Renderer (excluded when using 'SPA mode')
- Vue Meta

Nuxt.js can be used in two different ways (**_Server Rendering_** and **_Single Page Applications_**):

### <u>Server-Side Rendering (Universal SSR)</u>

In _SSR_, components are _rendered_ into HTML strings on the _server_, _sent_ to the browser, and finally "hydrate" the static markup into a fully interactive app on the client.

In **SSR** majority of your app's code runs on both the _server_ and the _client_.

### <u>Single Page Applications (SPA)</u>

A single-page application is an app that works inside a browser and does not require page reloading during use. These are, for instance: Gmail, Google Maps, Facebook or GitHub.

### <u>Static Generated (Pre Rendering)</u>

The big innovation of Nuxt.js comes with the `nuxt generate` command.

When building your application, it will generate the HTML for every one of your routes and store it in a file in preparation for a web crawler to see it. This is mostly used to boost SEO on your web application.

## Installing NuxtJs

Nuxt.js is very easy to get started with. A new nuxt project only needs the **nuxt** dependency.

The Nuxt.js team has created a scaffolding tool (**_create-nuxt-app_**) that makes creating nuxt.js project a breeze.

Make sure you have npx installed. However, npx is installed automatically since NPM 5.2.0. So if you have npm version 5.20 >, you are good to go.

Using `npm -v` command to check the version you have installed.

```bash
$ npx create nuxt-app <project-name>
```

Or with [yarn](https://yarnpkg.com/en/):

```bash
$ yarn create nuxt-app <project-name>
```

It will ask you some questions

1. Choose between integrated server-side frameworks.
2. Choose your favourite UI framework.
3. Choose your favourite testing framework.
4. The Nuxt mode you want (Universal or SPA).
5. Add axios module to make HTTP request easily into your application.
6. Add EsLint to Lint your code on save.
7. Add Prettier to pretiffy your code on save.

All dependencies will be installed, then navigate to the project folder and launch it with

```bash
$ cd <project-name>
$ npm run dev
```

The application is now running on http://localhost:3000.
