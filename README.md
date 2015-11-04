# Fannypack HTML Starter Kit

This starter kit is an example setup for using [Fannypack](https://github.com/lukeed/fannypack).

The demo content is an ES6 port of TodoMVC's [VanillaJS demo](http://todomvc.com/examples/vanillajs/)

## Installation
```bash
git clone https://github.com/lukeed/fannypack-starter-html.git MyApp
cd MyApp
npm install
```

## Development
Run all tasks, then initialize the BrowserSync live-reload server. This will watch file changes & auto-compile the changes.

```bash
npm run gulp
```

## Production
Prepare files for production-use by minifying and generating cache-busting filenames.

```bash
npm run production
```

## Production Server
After production assets have been compiled, you can start a production server (no BrowserSync) which will serve the new assets.

```bash
npm run gulp server
```
