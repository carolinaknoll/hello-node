### Hello World in NodeJS!
:sparkles: Just another hello world, this time with NodeJS (and some helpful comments!)
****

#### 01/Hello, world!

This exercise's focus quotes ([from Glitch's tutorial](https://glitch.com/edit/#!/node-beginner?path=README.md:1:0)):
> The first incarnations of JavaScript lived in browsers. But this is just the context. It defines what you can do with the language, but it doesn't say much about what the language itself can do.

> JavaScript is a "complete" language: you can use it in many contexts and achieve everything with it you can achieve with any other "complete" language.

> Node.js really is just another context: it allows you to run JavaScript code in the backend, outside a browser.
***
For this first part, we want to show a friendly 'Hello world!' inside our console by using Node.js.

First, we create a file `helloworld.js`. Inside this file, we can write `console.log('Hello, world!');` so we can display this message in the console.

Then, we want to execute the contents of our `helloworld.js` file through Node.js.

We can execute it by typing `node helloworld.js` in the console.

Alternatively, we can do the same by referencing this command as the main file, and even as a npm script in our `package.json`, like this:
```javascript
  "main": "helloworld.js",
  "scripts": {
    "start": "node helloworld.js"
  },
```
and then accessing it by typing `npm run start`.

Great! Now, if we check our console, it will greet us with a friendly `Hello, world!` message. We can even change our `console.log` message to display something like `Hi node! It's nice to meet you!` :smile:
