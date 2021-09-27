# Netflix clone

This is a simple clone of the Netflix's browser page. In the future an implementation it might have a login page.

Initially it will only be front-end, there will not be backend, and the images will all come from the public folder.

### Stack
I will use React + Typescript, and styled components for the styling.


### Components
The page will have the following components:

+ Navbar
+ Front image / video
+ carrousel with movies/series
+ infinite scroll
+ more info about the movie (only a modal)

### Project Structure
[Source](https://dev.to/chrisachard/tips-for-organizing-react-projects-191)

+ **Capitalize files that default export a React component**
+ **Use absolute imports**

1. src: components
2. public: static assets
    Images that you're going to import inside of components should be in src, not public
3. src/components or shared: shared components, group by function
4. src/images and src/styles
5. src/helpers: generalized helper code centralized
6. src/pages: entire route endpoints
7. src/action or reducers

### Bitacora
Installing styled components: 
    
    + [Source](https://developer.okta.com/blog/2020/03/16/react-styled-components)