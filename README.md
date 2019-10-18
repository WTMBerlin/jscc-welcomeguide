# JavaScript Crash Course &nbsp;<img src="https://raw.githubusercontent.com/WTMBerlin/WTM-Website/master/img/favicons/favicon-32x32.png" alt="wtm-logo" width="30"/>&nbsp; Welcome Guide

- [Intro](#intro)
- [Chrome](#chrome)
- [Slack](#slack)
- [Visual Studio Code](#visual-studio-code)
- [Terminal](#terminal)
- [Git and Github](#git-and-github)
- [Node.js](#nodejs)
- [MongoDB and Mongo Hub](#mongodb-and-mongo-hub)
- [Docker](#docker)
- [Problem Solving](#problem-solving)
- [Checklist](#checklist)

## Intro

First of all, welcome to the 3rd Edition of our Javascript Crash Course! This is going to be a challenging but exciting journey for getting started in the programming world.

In this guide we will go through all the steps and tools you will need to get ready for the classes. Please, make sure that you have all the tools installed and ready to go before starting the course.

> You might feel a bit overwhelmed sometimes, especially if it is the first time you are hearing about some of these tools and concepts. Please bear with us! :bear: Just try to get the main concept, and contact us with any doubts or problems you encounter during the process (later we will explain how to get in touch with us during the course).

We will provide information about tools for macOS and Windows in this guide. If you use another systems like Linux, and you don't find the download links or enough information, please get in touch with us.

## Chrome

[Chrome](https://www.google.com/chrome/) will be the browser of choice, due to its complete developer integrated tools. Make sure that you have the latest version installed on your computer.

## Slack

[Slack](https://slack.com/intl/en-de/) is the messaging tool that we use to communicate during the course:  [macOS Download](https://slack.com/intl/en-de/downloads/mac) | [Windows download](https://slack.com/intl/en-de/downloads/windows).

Important :speaker:: Get your personal invite to our WTM slack workspace by typing your email [here](https://slack.wtmberlin.com/).

On our `#js-crash-course` channel you will be able to ask questions, get support and share the link of your homework so we can review it and give you feedback. If you cannot see it on the left menu of the slack app under **Channels**, you can search for it after clicking on the title.

## Visual Studio Code

[Visual Studio Code](https://code.visualstudio.com/) is the IDE (Integrated Development Environment) we will use during the course. In simpler words, is the tool that we'll use to write code.

## Terminal

**Terminal**, also known as command line or console, allows us to accomplish and automate tasks on a computer without the use of a GUI or [graphical user interface](https://www.computerhope.com/jargon/g/gui.htm). Even if many tasks can be done by interacting with the GUI (for example deleting or creating folders), there are some actions which are easier and faster to perform through the terminal, especially when working with Git (which we explore in our next point).

On the course we will mainly use the [integrated Terminal in Visual Studio Code](https://code.visualstudio.com/docs/editor/integrated-terminal), but it is basically the same as the one you can find on your computer (macOS). We recommend you to have a basic understanding of how it works. You can take a look to this complete and fun-to-read [guide](https://medium.com/@grace.m.nolan/terminal-for-beginners-e492ba10902a).

**Windows users**: We will mostly be using the integrated terminal of Visual Studio Code. Depending on your Windows version, this will be either `powershell` or `cmd.exe`. Some commands will be a little different to those on macOS and Linux, but you can find helpful info in [this guide](https://www.makeuseof.com/tag/a-beginners-guide-to-the-windows-command-line/).
If you *really* want to use a [bash](https://en.wikipedia.org/wiki/Bash_(Unix_shell)) Terminal (the default macOS and Linux one), you can follow the instructions referenced in the [guide](https://medium.com/@grace.m.nolan/terminal-for-beginners-e492ba10902a) above to enable one. 

## Git and Github

[Git](https://git-scm.com/) is a version control system, which allows us to understand the history of a file and how it has progressed (a well-known example would be the Revision History of Google Drive documents).

[Github](https://github.com/) is the tool we use to share and upload our projects. You will need a Github account and a basic knowledge of how to use it.

:raising_hand: Feel free to check our [short intro](https://www.youtube.com/watch?v=NHwiSlz4Bi4&list=PLNBb8OktVDKvAbiQIeQqSo0YFYtn3wLAI&index=2&t=4s) for start getting familiarized with Git.

We recommend you to also go through [this guide](https://towardsdatascience.com/getting-started-with-git-and-github-6fcd0f2d4ac6) to learn how to work with both of them. It is a bit long but very complete, and you will get a good understanding on how to use them from scratch, and be able to use them during the course.

Now is time to prove your git learnings playing a little! :point_right: [https://learngitbranching.js.org/](https://learngitbranching.js.org/)

#### :innocent: This is the basic set up you will need for the first lesson. Continue to get the tools for the rest of the course.


## Node.js

Node.js is an open-source, cross-platform, JavaScript run-time environment that executes JavaScript code outside of a browser. In an easier to understand explanation, Node.js is a JavaScript runtime environment that includes everything you need to execute a program written in JavaScript, and is what we will use to create our applications on this course.

On [this website](https://nodejs.org/en/) you can find the links for installing the latest version of Node.js on your machine.

On macOS or Linux you can also install it via [Homebrew](https://brew.sh/).
First run the following command to install Homebrew in your machine (copy and paste it on a Terminal window and click enter):
```
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```

Once Homebrew is installed, run:
```
brew install node
```

To check that it was properly installed, type the following command on the terminal:
```
node -v
```
If you receive the version number (e.G: `v10.16.3`), everything is ok.

## MongoDB and Mongo Hub

On our 5th. lesson we will learn how to use [MongoDB](https://www.mongodb.com/), an open-source document database. [Here](https://docs.mongodb.com/manual/installation/) you can find the download links for every platform.

To install it using Homebrew (check on the Node.js point how to install it), submit on the terminal the following commands (one after the other):
```
brew tap mongodb/brew
```
```
brew install mongodb-community@4.2
```

We will also use a MongoDB GUI application (an interactive program where we can easily see and manage the items of our database).

They all work very similarly, but for this course we recommend MongoHub (only macOS, [download link](https://mongohub.s3.amazonaws.com/MongoHub.zip)) or Robomongo (both platforms, [download links](https://studio3t.com/download-now/)).

The most important conmmands are `mongod` or `service mongodb start` for connecting to the database, and `brew services stop mongodb` to disconnect from it.


## Docker

In our last class we will learn how to deploy our application using [Docker](https://www.docker.com/). Docker is a tool designed to make it easier to create, deploy, and run applications by using containers. Containers allow a developer to package up an application with all of the parts it needs, such as libraries and other dependencies, and ship it all out as one package.
[Source](https://opensource.com/resources/what-docker).

On [this site](https://www.docker.com/products/docker-desktop) you can find the download links for Mac and Windows and all the steps to follow.

If you don't manage to follow all the steps of that guide, don't worry. We will explore it more deeply in our class. You will just need to download and install Docker on your machine, and
make sure before the class that is running (On Mac it should appear the little whale on the top menu bar, and if you click on it should indicate that is running. On Windows it will appear on the notifications area, bottom-right of the screen).

**Windows 10 Home Edition users** (or other editions that doesn't support current Docker version): There is a workaround to make it work -> [Docker Toolbox](https://docs.docker.com/toolbox/toolbox_install_windows/). You can start from Step 2. If after finishing Step 3 you run `docker run hello-world` and get the response showed on the guide, you should be good to go for the class! Anyhow, if you can come a bit before the class we can check it together.

## Problem solving

> The following info will be useful for when you are studying/working on your own. On the class, please raise your hand in the moment you get stuck! There will be several teacher assistants there to help you immediately so you can continue following the class.

One of the skills a developer has to master, and also one of the most difficult to achieve at the beginning, is to find the correct answer for the problem they are facing. You are following the steps, everything seems to be fine and boom, you are receiving a weird error on the console or on VSCode. You have no idea why this is happening! You tried everything... So frustrating. But actually, this problem is faced for experienced programmers on their daily basis. And the solution is... to [Google](https://www.google.com/) it!

You will master this skill with time (what to actually type on google to find the answer you need), but at first you could try to just copy and paste on the google search the error you are receiving (try to only take the meaningful part of the error, for example: `Uncaught SyntaxError: Unexpected identifier`. You will probably get as first result a link to Stack overflow.

[Stack overflow](https://stackoverflow.com/questions) is a community made by and for developers in which someone asks a question, and other developers answer it. If it's a good answer it gets upvotes, and if it's the answer that solved the problem, the OP (original poster) marks it with a green check. This is very useful for the developer community, because the problem we are currently facing most of the times someone else had it already, therefore here we can find many possible solutions to help with our coding struggles. Take a look [to some of the most entertaining questions](https://tutorialzine.com/2015/12/the-10-most-entertaining-stackoverflow-questions-of-all-time). :smiley:

If you are practising at home, and after researching you are more than 20-30 minutes stuck on a problem, is time to ask for help on our channel!

----------

#### And that's it! :tada: Please contact us anytime you have doubts or any step of the guide was unclear or didn't work for you. It will also help us make it better for the following students.
#### Enjoy the course! :school_satchel:


## Checklist

#### Have you everything ready to go? :eyes:

- [x] Read the Welcome Guide
- [x] Chrome
- [x] Slack and join #js-crash-course
- [x] Terminal basic learning
- [x] Git and Github setup
- [x] Node.js
- [x] Mongo Hub and MongoDB
- [x] Docker



