# Welcome

This example is meant to demonstrate how you might get started working with [Next.js](https://nextjs.org) and [Docker](https://www.docker.com).

## Getting started

All you need to do to run this application is:

```sh
$ npm start
```

If you want to create this example from scratch, please follow the steps below.

### Create the Next.js application

To create our application:

```sh
# Make a directory for our NextJS application
$ mkdir front-end

# Navigate to the new app directory and use npm init
$ cd front-end
$ npm init

# Install dependencies for Next.js, React, and for working with CSS
$ npm install --save next react react-dom @zeit/next-css

# Add TypeScript dependencies
$ npm install --save-dev @types/node @types/react @types/react-dom typescript

# Create a TypeScript config file (./front-end/tsconfig.json)
# Create a NextJS config file (./frontend/next.config.js)
# Create a TypeScript file to reference Next.js types used in our project (./frontend/next-env.d.ts)

# Create a simple Next.js app
# We have a simple page that will render a Hello component at the / route
#
# Please refer to:
# + .front-end/components/hello/index.tsx
# + .front-end/pages/index.tsx

# Docker
# Create a Dockerfile for our front-end app (./front-end/Dockerfile)
# Create a Docker compose file for our project (./docker-compose.yml)

# OPTIONAL: Follow the pattern to add your example to the project level package.json
```
