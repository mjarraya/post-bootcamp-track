# Node.js

## Built-in modules

Node.js comes with [modules that are built-in](https://nodejs.org/docs/latest-v12.x/api/) (that we didn't need to install from npm). Some of those we used already, related to writing a server (`http`) or working with file paths (`path`) and even to print in the terminal using `console`.  

### readline

[Accept input from the command line in Node](https://flaviocopes.com/node-input-from-cli/)  

### fs

[Introduction to the fs Module in Node.js](https://alligator.io/nodejs/intro-to-fs-module/)  

### Exercise

There are a lot more modules, for all sorts of different use cases. I suggest you look into [this series of exercises](https://github.com/workshopper/learnyounode) to get some practice.

## PM2

PM2 is a process manager for node.js applications. It allows to monitor the memory usage of a node.js app, to run multiple instances of an application on the same server, and also to handle auto-restarting if the app was to crash.

[PM2 Quick Start](https://pm2.keymetrics.io/docs/usage/quick-start/)

## More server frameworks

In order to run a server, we have used `express` which is by far the most popular framework, but you might also encounter other frameworks that aim to help node.js developers to write server code, with different approaches.

[koa](https://koajs.com)  
[hapi](https://hapi.dev/)

## Publish your own package

Whether it is to solve a problem that other developers face (and give back to the community), or to share code (building a library of functions) with other team members, you can also create your own package and publish it on the npm registry.

[Creating (and publishing) your first npm package](https://dev.to/therealdanvega/creating-your-first-npm-package-2ehf)  
[Contributing packages to the registry on docs.npmjs.com](https://docs.npmjs.com/packages-and-modules/contributing-packages-to-the-registry)
