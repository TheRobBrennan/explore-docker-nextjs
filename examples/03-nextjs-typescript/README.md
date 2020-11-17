# Getting started

For this project, we are going to be creating a Next.js app that will use `create-next-app` to generate a Next.js app that uses TypeScript.

## Create a Next.js app using TypeScript

We will use the latest version of `create-next-app` to generate our Next.js app with TypeScript automatically configured for us:

```sh
$ cd 03-nextjs-typescript
$ npx create-next-app nextjs-with-typescript --example with-typescript
```

Let's verify that our app runs by starting Next.js in development mode:

```sh
$ cd nextjs-with-typescript
$ npm run dev
```

## Visual Studio Code

If you are using [VS Code](https://code.visualstudio.com), launch configurations have been defined for you to debug the client-side and server-side Next.js code.

### Debugging

The following launch configurations for [VS Code](https://code.visualstudio.com) are defined in `.vscode/launch.json`:

- `Example 03 - [LOCAL] Next.js server` - This debug configuration will allow you to test the server-side code (API endpoints, libraries, utilities, etc)
- `Example 03 - Launch Chrome` - This debug configuration will allow you to test the client-side code (pages, components, etc)

`Example 03 - [LOCAL] Server and Client` will launch both of the debug configurations in one command 🤓
