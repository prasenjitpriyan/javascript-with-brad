<div style="text-align: justify; color: yellow">

# JavaScript with Brad

## What is JavaScript?

JavaScript is one of the core technologies of the web alongside HTML, which is a markup language and is used to structure web page content as well as CSS, which is used to style that content. So JavaScript is what brings life to the front end or the user interface of a website or a web app and it allows us to make web pages dynamic. Not only that, but it can also be used on the server side to do things like interact with databases and work with the file system and this is with the help of the NodeJS runtime. So JavaScript is a high level interpreted programming language used to create interactive and dynamic website experiences and when I say interpreted, what I mean is that it's executed line by line rather than being compiled into machine code first. So the code is executed on the fly, making it a scripting language, hence the name JavaScript.

## What is JavaScript Used For?

- DOM (Document Object Model) Manipulation => It as a tree like structure of nodes and everything on the page is a node, including every HTML tag, every attribute, every piece of text and so on. So JavaScript provides methods for dynamically changing that structure or changing the content or the styles of the elements In the DOM.

- Event Handling => JavaScript gives us a way to handle events so we can respond to things like mouse clicks or drags or hovers, keyboard events, form submissions and just about anything you can think of that you can do in the browser window.

- So making asynchronous requests is one of the most powerful uses of JavaScript, and it's used to interact with back end servers, whether it's your own server that you created or a public API such as the GitHub or YouTube API. So we can make HTTP requests right from our code to fetch data or submit data and this happens all behind the scenes without having to refresh the page and this is often used in what are called single page applications or spas to dynamically load and update content without having to reload the entire page.

- Animations & Effects => So as far as animations and effects, there's many different ways that we can create these. Using JavaScript, we can use CSS transitions and animations. There's the request animation frame method, there's different libraries like animate CSS and gsap. So these methods allow developers to create a wide range, a wide range of animations such as fading.

- Data Manipulation (Sorting, filtering, etc) => Now data manipulation, which is the process of modifying or transforming data, can be done with JavaScript because it's a full featured language with data structures like arrays, and this allows us to sort filter and aggregate data. So there's all kinds of powerful array methods that we can use, such as map, filter, reduce etc.

- Storing Data (Cookies, Local Storage, etc) => So JavaScript can also be used to store data on the client or in the browser using things like local storage, session, storage and cookies.

- We can also create single page applications or SPA, and these are applications that load a single HTML page and dynamically update the content without having to reload the entire page and this provides a really seamless and responsive user experience. So no page reloading we can create different routes and so on.

- Creating APIs & Web Services (Node.js, Deno) => You can also use it on the server side with the Node.js runtime as well as Deno. So in addition to consuming APIs from the front end, we can also create APIs that interact with databases on the back end. And there's a ton of frameworks that you can use to help you with this, including Express.

## Console

Now what this is, is console is an object. And remember, an object has properties and methods. A method is a function. So log is the method that I'm using. And to execute a function or a method, you have to use parentheses. So I'm executing the log method that's on the console object and we use this dot syntax in JavaScript to access properties and methods.

```js
const styles = 'padding: 10px; background-color: white; color: green';
console.log('%Hello World', styles);
```

## Data Types

- Primitive types: Stored directly in the "stack", where it is accessed from.

- Reference types: Stored in the heap and accessed by reference.
