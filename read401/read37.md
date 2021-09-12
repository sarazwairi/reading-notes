#  React 1


React is a JavaScript library created for building fast and interactive user interfaces for web and mobile applications. 

## JSX - JavaScript Syntax Extension

It is used with React to describe what the user interface should look like. By using JSX, we can write HTML structures in the same file that contains JavaScript code. This makes the code easier to understand and debug, as it avoids the usage of complex JavaScript DOM structures.

## Components, State, and Props

Components are the building blocks of any React application, and a single app usually consists of multiple components. A component is essentially a piece of the user interface. React splits the UI into independent, reusable parts that can be processed separately.

The state is a built-in React object that is used to contain data or information about the component. A component’s state can change over time; whenever it changes, the component re-renders. The change in state can happen as a response to user action or system-generated events, and these changes determine the behavior of the component and how it will render.  

Props are short for properties. It is a React built-in object which stores the value of a tag’s attributes and works similar to the HTML attributes. It provides a way to pass data from one component to other components in the same way as arguments are passed in a function.

## Create a Next.js App

To build a complete web application with React from scratch, there are many important details you need to consider:

    Code has to be bundled using a bundler like webpack and transformed using a compiler like Babel. 

    You need to do production optimizations such as code splitting.

    You might want to statically pre-render some pages for performance and SEO. You might also want to use server-side rendering or client-side rendering.

    You might have to write some server-side code to connect your React app to your data store.


Next.js aims to have best-in-class developer experience and many built-in features, such as:

    An intuitive page-based routing system (with support for dynamic routes) 

    Pre-rendering, both static generation (SSG) and server-side rendering (SSR) are supported on a per-page basis

    Automatic code splitting for faster page loads

    Client-side routing with optimized prefetching

    Built-in CSS and Sass support, and support for any CSS-in-JS library

    Development environment with Fast Refresh support
    
    API routes to build API endpoints with Serverless Functions
    Fully extendable