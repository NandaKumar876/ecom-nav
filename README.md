This project provides a minimal and efficient setup for building modern React applications using Vite. It includes support for Hot Module Replacement (HMR) and a preconfigured ESLint setup to help maintain code quality and consistency during development.

Available React Plugins

This template supports two official plugins for enabling Fast Refresh:

@vitejs/plugin-react
Utilizes Babel (or OXC when used with Rolldown-Vite) to support Fast Refresh and modern React transformations.

@vitejs/plugin-react-swc
Uses SWC, a high-performance compiler, to provide faster development builds and refresh performance.

React Compiler

The React Compiler is not enabled by default due to its impact on development and build performance. To integrate it into your project, refer to the official documentation:

https://react.dev/learn/react-compiler/installation

ESLint Configuration for Production

For production applications, it is recommended to:

Use TypeScript for improved scalability and type safety

Enable type-aware linting rules using typescript-eslint

Refer to the official Vite React TypeScript template for integration details:

https://github.com/vitejs/vite/tree/main/packages/create-vite/template-react-ts


Key Features

Fast development environment powered by Vite

Instant module updates using Hot Module Replacement

Preconfigured ESLint setup for consistent code quality

Flexible plugin options for different performance needs

Scalable structure suitable for production applications
