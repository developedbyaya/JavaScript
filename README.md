# JavaScript
This repo contains notes on JavaScript (JS) as well as useful resources and best prcatices. For simplicity, JS refers to JavaScript, I will be using JS to reference JavaScript.

## Useful Websites

These are good reference websites for JavaScript:

1. [Mozilla Developer Network (MDN)](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference)
2. [W3 Schools](https://www.w3schools.com/js/DEFAULT.asp)
3. [StackOverflow](https://stackoverflow.com/)
4. [ChatGPT](https://chat.openai.com/auth/login)

## Code Editors 

A code editor is where developers write their code as well as debug it(look for and fix errors). Some of the most popular one's are:

1. [Visual Studio Code](https://code.visualstudio.com/) - This is a lightweight and fast text/source code editor, it is not the same thing as Visual Studio.
2. [Visual Studio](https://visualstudio.microsoft.com/) - This is a full fledged IDE(Intergrated Development Environment). For most people, the community version is enough to get started.
3. [Notepad++](https://notepad-plus-plus.org/)
4. [Sublime Text](https://www.sublimetext.com/)

## Web Broswers

Most JavaScript runs on the web, here are some of the most popular web browers. 

1. [Google Chrome](https://www.google.com/chrome/) - Has great developer tools.
2. [Firefox](https://www.mozilla.org/en-US/firefox/new/) _ Also has great developer tools.
3. [Safari](https://www.apple.com/safari/)
4. [Microsoft Edge](https://www.microsoft.com/en-us/edge)

## JavaScript Fundamentals

Our JS journey begins with understanding a few basic concepts:

### How to add JS Script to your HTML file:

N.B. HTML will be referenced, please make sure you know it's basics before continuing. 

We use the `<script></script>` tag to add JS to a webpage/HTML page. JS scripts can be added in the `head` or the `body` tag in our HTML files. The two examples below are examples of internal JS, this is JS that is written directly inside the webpage it will be used in. 

An example of adding internal JS in the `body` tag:

```
<body>
    <script>
        // Write your JS code here.
        // Note that this is a comment in JS ( // ), it will not be displayed anywhere on the browser.
        // It is useful for making notes for yourself or other developers that will be working on your source code. 
    </script>
</body>
```

An example of adding internal JS in the `head` tag:

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Webpage Title</title>

    <script>
      // Wtite your JS code here.
    </script>
</head>
```

The above method of writing JS is useful if you are writing small JS code blocks. As a **best practice**, when your JS code is very large, it is best to write it in an external script file and import your file into the projects or webpage you will be using it in. 

We use the `src` attribute to add external JS in our HTML files. 

An example of adding external JS in the `body` tag:

```
<body>
    <script src="/the/path/to/sctipt.js">
        // Any code written inside thsi block will be ignored if the src attribute is used. 
    </script>
</body>
```

An example of adding internal JS in the `head` tag:

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Webpage Title</title>

    <script src="/the/path/to/sctipt.js">
        // Any code written inside thsi block will be ignored if the src attribute is used. 
    </script>
</head>
```

Paths can be relative or absolute. A path is where your file is stored. 

Absolute paths refers to when you provide the full path of where your file is stored. Some examples are:

`src="C:/example/cwd/mydir/myscript.js"` 
or 
`src="https//www.somewebsite.com/directory/myotherscript.js"`

Relative paths refers to when you provide the path relative to the current folder you are working on. Some examples are:

`src="myscript.js"` // File is inside the folder we are working in. 
or
`src="./myscript.js"` // File is inside the folder we are working in. 

### JS Basics

How can we start a programming language lesson without writing the most famous programming line,I am talking about a "Hello World!" program in JS :).

`alert("Hello World!);` // This will display hello world inside a browser window. You are now officially a developer. 

The `alert()` keyword is JS is used to display messages or alerts as the word implies to the user. The message will appear like this:
![alertbox](https://github.com/developedbyaya/JavaScript/assets/135131214/ce3b51e0-cf5e-481e-a3b1-1873e3d8edf0)
