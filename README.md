# How to Lose a Dev In 3 Ways
This project contains a few code snippets that I created for a talk at DevRelCon SF 2019. The purpose is to demonstrate best practices in documentation. The audience for this talk is anyone who creates external documentation for software products. Please note: Most of the code below doesn't actually do anything.

**Who should use this documentation?**
1.  Anyone who wants to learn more about writing docs that are accessible and inclusive to new developers.
2.  Anyone who is new to using documentation and wants some insight on how to navigate it.

**How should you use this documentation?**
* Think of this documentation like a glossary or a how-to guide.
* Ideally, use it as a guide for best practices when you create documentation!

**Pre-requisites:**
* None

## QuickStart

In your command line, (for example, Terminal on a Mac or PowerShell on a PC), enter the following command.

**Note:** Don't copy the dollar sign :)

```sh
$ npm install fake-quickstart
```

Then, create a file called `index.js` and open it in your favorite text editor (such as Atom).

Add the following code to `index.js`:

```javascript

const packageName = require('package-name');

```

## Legend

Here are some conventions you might see when using this documentation:

`$ npm run start`

The `$` means you should run the command in a terminal or shell. Do not copy the dollar sign.

`api/<your region here>/path/to/resource`

Any time you see angle brackets `<>`, replace them with your personal credentials. Do not include the brackets `<>`.

Example:

`api/us-west/path/to/resource`

`> ` denotes the interactive node repl. Access it by typing `node` in your command line. Exit it by typing `.exit`.

## Install NVM

NVM stands for node version manager. When you work on multiple projects, they might require different versions of node.

Enter the following commands in your terminal to see:
1. If you have nvm installed
2. If so, which versions of node you have installed

```sh
$ nvm --version
    0.31
$ nvm ls
    10.12
    8.2
```

If there is no output when you run `nvm --version`, you need to install it. Check out instructions for [Mac](https://medium.com/@isaacjoe/best-way-to-install-and-use-nvm-on-mac-e3a3f6bc494d), [Linux](https://www.digitalocean.com/community/tutorials/how-to-install-node-js-on-ubuntu-16-04), and [PC](https://www.digitalocean.com/community/tutorials/how-to-install-node-js-on-ubuntu-16-04).


## How To Use This Library

```
npm install fake-package
```
Create a script with the following:
```
const fakePackage = require('fake-package');
const app = fakePackage();

app.fakeFunction(callback, () => console.log('You did it!'));
```

```
npm run <script name>
```

## Prerequisites

To run this quickstart, you need Docker, Node 10.0.0 or later, and Webpack or Gulp.
Make sure you have the right Gulp location in your path.

## Instructions

1. Install Docker
2. Install Ngrok

## MLH Localhost API Tutorial

Use this tutorial to learn the MLH Localhost API.

1. Add the code below to a file called `localhost.js`.

```javascript
const apiKey = '<your key here>'
const localhostApi = require('mlh-localhost');

// ...

const apiCall = () => {
  request(options, (error, response, body) => {
    if (error) throw new Error(error);
    data = JSON.parse(body)
    console.log(data);
  });
}
```

2. In your terminal, run the following command:
```
node localhost.js
```

You did it!
