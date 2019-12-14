# Welcome

This project is meant to serve as a starting point for exploring [Next.js](https://nextjs.org) using [Docker](https://www.docker.com).

## Initial setup

### Docker

The easiest way to use this repo is to have [Docker Desktop](https://www.docker.com/products/docker-desktop) installed and configured on your development machine.

### Development environment

Once you have Docker installed, verify that you have a recent version of [Node.js](https://nodejs.org/en/) and npm installed on your development machine:

```sh
# Verify that you have Node.js v10.9.0 or later installed (https://nodejs.org)
$ node -v
v12.13.1

# Verify that the npm package manager has been installed
$ npm -v
6.13.3
```

## Examples

The following scripts have been added to this repo in `./package.json`:

+ `start:example:##` - Starts a Dockerized version of the example using the latest build
+ `start:example:##:clean` - Builds a Dockerized version of the app using the latest updates to Docker files
+ `start:example:##` - Spins down the Dockerized version of the app
+ `docker:nuke` - CAUTION! This will prompt you before destroying **ALL** Docker containers, images, volumes, etc on your development machine

By default, `npm start` will run example 01 in this repo.

### Example 01: Getting started with NextJS

To run a specific example - such as `01-get-started-with-next-js` - you can run:

```sh
$ npm run start:example:01
```

Your application should be available at [http://localhost:3000](http://localhost:3000).

To verify this is working as expected, try making a change to the text in `examples/01-get-started-with-next-js/front-end/components/hello/index.tsx` and watch the hot reloading work automatically.
