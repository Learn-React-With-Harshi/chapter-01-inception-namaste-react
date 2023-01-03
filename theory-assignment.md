# `Learn React With Harshi 👩🏻‍💻 Series`
   Documenting my learning journey of [Namaste React Live Course](https://learn.namastedev.com/) conducted by Akshay Saini
   
## Theory Assignment: `Chapter - 01 Inception` (24/12/2022)

### 1. What is Emmet ?
Emmet is a plug-in for many popular text editors which greatly improves HTML & CSS. Emmet short hand expression can be used to generate HTML markup and css.
Most useful emmet abbreviations are :

`HTML`
1. `html:5` - generates html5 boilerplate
2. `ui>li` - nested elements
3. `h1.#heading.container.con` - create h1 element with id heading and classes container and con
4. `div[data-name=harshi]` - Custom attribute <div data-name="Harshi"></div>
5. `header+div+footer` - generate siblings <header></header> <div></div> <footer></footer>

`CSS`
1. `m10-10-10-10` -  Margin on all sides margin: 10px 10px 10px 10px;

### 2. Difference between library and framework ? 

 `Library` - collection of pre-defined helper functions, objects, classes, modules that can be used in code to boost the development.
   By using a library, you can control the flow of the application and call the library.
   `Eg: React, JQuery, Lodash`

 `Framework` - Foundation upon which applications are built.
   In contrast, when you use a framework, the control is inverted, i.e., the framework controls the flow and calls your code.
   `Eg: Node JS, Angular, Spring` 

### 3. What is CDN ? Why do we use it ?
A CDN also called a content distribution network, is a group of geographically distributed and interconnected servers. They provide cached internet content from a network location closest to a user to speed up its delivery.

### 4. Why is `React` known as React ?
`React` was developed for applications (Facebook) that have constantly changing data. Since React is a front-end framework or the `View` in MVC, this means that as the user clicks around and changes the app's data, 
the view should `react` or change with those user events.

### 5. What is cross-origin in script tag ?
The crossorigin attribute provides support for `CORS` , defining how the element handles cross-origin requests. CORS stands for Cross-Origin Resource Sharing. If cross-origin is set to "user-credential", then user authentication is required to access the file.

### 6. What is difference between React and ReactDOM?
`React` library contains functionality utilised in web and mobile apps (react native). `ReactDOM` library contains functionality utilised in web browser. It contains DOM manipulation utilities.

### 7.What is the difference between react.production.js and react.development.js ?
`react.production.js` - production code of react library that is minified and production ready.
`react.development.js` - More readable and developer friendly react library code that can be used to debug.


### 8.What is async and defer - check Akshay Saini's Youtube channel ?

  `Without async/defer` : Browser stops the html parsing once script tag is encountered.
  It resumes parsing only after script is fetched and executed. 

  `Async` : Html parsing is done in parallel while scripts are being fetched from the network and executed.
  Once the script is done with execution, html parsing is resumed. This can be used for external scripts like google analytics. 
  It is better to avoid async for scripts that are dependent on other scripts since we dont know in which order script will be executed.

  `Defer` : Similar to async, Html parsing is done in parallel while scripts are being fetched from the network. But scripts are executed only after the 
  html parsing is done.
