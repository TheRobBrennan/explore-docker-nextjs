# Welcome

This example focuses on experimenting with [Next.js](https://nextjs.org) and [GraphQL](https://graphql.org) - specifically using [Apollo](https://www.apollographql.com)

## Getting started

All you need to do to run this application is:

```sh
$ npm start
```

Notice that this example contains:

+ A Next.js page wrapped in the Apollo higher order component (HOC)
+ A static page that does not need to be wrapped by the Apollo higher order component (HOC)

If you want to create this example from scratch, please follow the steps below.

### Create a new Next.js application using Apollo client and Apollo server

Here is an abbreviated set of commands detailing how this example was created:

```sh
# Use create-next-app to bootstrap the example
$ npx create-next-app --example api-routes-apollo-server-and-client api-routes-apollo-server-and-client-app

```
