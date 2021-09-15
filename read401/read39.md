# Read38

## Assets, Metadata, and CSS
```
npx create-next-app nextjs-blog --use-npm --example "https://github.com/vercel/next-learn/tree/master/basics/assets-metadata-css-starter"
```

### Metadata 

like html tag <head> has been instead of <Head> , which is React component in Next.js. We can add <Head> into our first-post.js

### CSS

    Next.js use styled-jsx which is a CSS in JS, we can write the CSS only for the specific component. Besides, Next.js allows to import .css and .scss files. 

    We can also create the _app.js for the global entry point, then import CSS file for the global CSS styling.

* Layout Component:

    Create the folder components and styles in the top level.

    Create layout.js and layout.module.css in the components folder.

    Create the folder in the top level

    Create a utility CSS classes utils.module.css in styles folder for reuse css style.

    Now we can easy use the layout.js in our first-post.js

### Assets

When we put static files like images and video under top-level ‘public’ folder. Files in the public folder can be referenced by pages.

So we can use the picture vercel.svg into our first-post page.

<img src="/vercel.svg" alt="Vercel Logo" className="logo" />

## React Context for Beginners – The Complete Guide (2021)

React context allows us to pass down and use (consume) data in whatever component we need in our React app without using props.

These types of data include:

1. Theme data (like dark or light mode)
2.  User data (the currently authenticated user)
3.  Location-specific data (like user language or locale)

React context helps us avoid the problem of props drilling.

Props drilling is a term to describe when you pass props down multiple levels to a nested component, through components that don't need it.

There are four steps to using React context:

* Create context using the createContext method.
* Take your created context and wrap the context provider around your component tree.
* Put any value you like on your context provider using the value prop.
* Read that value within any component by using the context consumer.