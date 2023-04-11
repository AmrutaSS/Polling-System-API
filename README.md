# Api-Polling-System

## Introduction

Creating a **Polling System API** where anyone can create questions with options and also add votes to it. It is built
using Express, Nodejs, MongoDB.

<br/>

## Features

- Users can create questions (you can add as many questions as you want).
- Users can add options to a question.
- Users can add a vote to an option of question.
- Users can delete a question -> A question can't be deleted if one of it's options has votes.
- Users can delete an option -> An option can't be deleted if it has even one vote given to it.
- Users can view a question with it's options and all the votes given to it.

<br/>

## Requirements

For development, you will only need Node.js and a node global package installed in your environement and mongodb for database.

### Node

- Node Installtion on Windows
  Go on to the [official Node.js website](https://nodejs.org/en/) and download the installer. Also, be sure to have `.git` available in your PATH,
  `npm` might need it (You can find [git](https://git-scm.com/)).
- Other operating System
  You can find more information about the installation on the official [Node.js website](https://nodejs.org/en/) and the official [NPM website](https://www.npmjs.com/).

If the installation was successful, you should be able to run the following command.

```
$ node --version
v16.13.0

$ npm --version
8.2.0
```

If you need to update `npm`, you can make it using `npm`! Cool right? After running the following command, just open again the command line and be happy.

```
$ npm install npm -g

```

<br/>

## To run the project on your local machine:

1. Open terminal.

2. Change the current working directory to the location where you want the cloned directory.

   ```
   $ git clone https://github.com/AmrutaSS/Polling-System-API

   ```

3. Install all the dependencies by running :

   ```
   npm install

   ```

4. Run npm start to run the project at local host, port 8000:

   ```
   $ npm start

   ```

<br/>

## Configuration

Open `a/nice/path/to/a.file` then edit it with your settings. You will need:

- A setting
- one more setting
- Another one more setting
