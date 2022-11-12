### What is a Chakra UI?
Chakra UI is a simple, modular and accessible component library that gives you the building blocks you need to build your React applications.It is built on top of styled-system, a utility library that allows you to style your components quickly and easily.

### Is Chakra UI better than material UI?
Chakra UI is best known for having:
- Fewer classes for each HTML tag;
- Easy manual manipulation in CSS classes;
- A robust, layout-focused library;
- Easier-to-pick-up controls (since it's new);
- Composable, flexible, and scalable code;
- Built-in support (fewer code changes);
- Good documentation; and a level of performance that is good for small- to medium-sized, uniquely designed apps.

Material UI is best known for having:
- A large variety of pre-styled UI components;
- More classes for individual HTML tags;
- More CSS classes with more components;
- Less facility for the creation of custom components;
- Robust documentation (slightly better than Chakra UI);
- More mature and active community; and
- Level of performance that is great for large, data-driven apps.

### How to use Chakra UI?
to use Chakra UI in your application, you first need to install it using

```npm i @chakra-ui/react @emotion/react @emotion/styled framer-motion```

or crate a react app with the Chakra UI template:

``` npx create-react-app my-app --template @chakra-ui ```

then wrap the whole app tree in Chakra provider component

``` import * as React from 'react'

import { ChakraProvider } from '@chakra-ui/react'

function App() {
  return (
    <ChakraProvider>
      <App />
    </ChakraProvider>
  )
}
```
