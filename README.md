# JavaScript Crash Course &nbsp;<img src="https://raw.githubusercontent.com/WTMBerlin/WTM-Website/master/img/favicons/favicon-32x32.png" alt="wtm-logo" width="30"/>&nbsp; Welcome Guide

- [Intro](#intro)
- [Chrome](#chrome)
- [Slack](#slack)
- [Visual Studio Code](#visual-studio-code)
- [Terminal](#terminal)
- [Git and Github](#git-and-github)
- [Node.js](#nodejs)
- [MongoDB and Robo3T](#mongodb-and-mongo-hub)
- [Vue](#vue)
- [Docker](#docker)
- [Heroku](#heroku)
- [Problem Solving](#problem-solving)
- [Checklist](#checklist)

## Intro

First of all, welcome to the 3rd Edition of our JavaScript Crash Course! This is going to be a challenging but exciting journey for getting started in the programming world.

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

We recommend you to go through [this guide](https://towardsdatascience.com/getting-started-with-git-and-github-6fcd0f2d4ac6) or [this other one](https://product.hubspot.com/blog/git-and-github-tutorial-for-beginners) to learn how to work with both of them. They are a bit long but very complete, and you will get a good understanding on how to use them from scratch. This is important because we will ask you to upload your homeworks on your Github account and share the link with us so we can review it easily.

:raising_hand: Feel free to check our [short intro](https://www.youtube.com/watch?v=NHwiSlz4Bi4&list=PLNBb8OktVDKvAbiQIeQqSo0YFYtn3wLAI&index=2&t=4s) for start getting familiarized with Git.

Now is time to prove your git learnings playing a little! :point_right: [https://learngitbranching.js.org/](https://learngitbranching.js.org/)

#### :innocent: This is the basic set up you will need for the first lesson. Continue to get the tools for the rest of the course.


## Node.js

Node.js is an open-source, cross-platform, JavaScript run-time environment that executes JavaScript code outside of a browser. In an easier to understand explanation, Node.js is a JavaScript runtime environment that includes everything you need to execute a program written in JavaScript, and is what we will use to create our applications on this course.

On [this website](https://nodejs.org/en/) you can find the links for installing the latest version of Node.js on your Windows or macOS machine.

On macOS you can also install it via [Homebrew](https://brew.sh/).
First run the following command to install Homebrew in your machine (copy and paste it on a Terminal window and click enter):
```
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```

Once Homebrew is installed, run:
```
brew install node
```

For Linux users check out [this link](https://nodejs.org/en/download/package-manager/). Or use the following code snippet directly for Debian and Ubuntu based distributions:
```
# Using Ubuntu
curl -sL https://deb.nodesource.com/setup_12.x | sudo -E bash -
sudo apt-get install -y nodejs

# Using Debian, as root
curl -sL https://deb.nodesource.com/setup_12.x | bash -
apt-get install -y nodejs
```

### Confirm that Node.js was properly installed (all platforms)

After you installed your Node.js on your machine (Windows, macOS or Linux), check that it was properly installed typing the following command on the terminal:
```
node -v
```
If you receive the version number (e.g: `v10.16.3`), everything is ok. If not, try the previous steps again or ask on the #js-crash-course channel for help.

## MongoDB and Robo3T

### MongoDB

On our 5th lesson we will learn how to use [MongoDB](https://www.mongodb.com/), an open-source document database. [Here](https://docs.mongodb.com/manual/installation/) you can find the download links for every platform.

If you are a macOS user, we recommend to install it through Homebrew (check on the Node.js point how to install it if you haven't done so). Once you have Homebrew on your machine, submit on the terminal the following commands (one after the other):
```
brew tap mongodb/brew
```
```
brew install mongodb-community@4.2
```

**Important** :speaker:: Make sure that you have MongoDB properly installed typing on the terminal:
```
mongo --version
```

If you see a message starting with something like _MongoDB shell version v4.0.3_, you are good to go :)

The most important commands are `brew services start mongodb-community@4.2` for connecting to the database, and `brew services stop mongodb-community@4.2` to disconnect from it. If you didn't use homebrew, `mongod` for starting it, and CTRL+C one or two times for stopping it. You can also consider `brew services restart mongodb-community@4.2` if you'd like to restart your connection. But we will see all these commands more in depth during the class. 

_Note: You might need to use `mongodb-community` instead of `mongodb-community@4.2`, depending on which one you used when installing it_.


### Robo3T

We will also use a MongoDB GUI application (an interactive program where we can easily see and manage the items of our database).

They all work very similarly, but in this course we will use Robo3T ([download link](https://robomongo.org/download). Go to right side of the website, click on the button **Download Robo 3T**, and choose your platform).


## Vue

To quickly setup a [Vue](https://vuejs.org/) application we will use [Vue-CLI tool](https://cli.vuejs.org/).

Please follow [this guide](https://cli.vuejs.org/guide/installation.html) for installation.
Run following command to install Vue-CLI globally:
```
npm install -g @vue/cli
```
You can check if you have the right version with this command:
```
vue --version
```
After that go to your project folder and type:
```
vue create frontend
```
For Windows users:
```
winpty vue.cmd create hello-world
```
If for some reasons you are not able to install global packages, please use following commands:
```
npm install @vue/cli -D
npx vue --version
npx vue create frontend
```

You will be prompted to pick a preset.\ Select "Manually select features" and select following options: "Babel", "Router", "Vuex", "Linter / Formatter".\
Use history mode for router? "Y"\
Pick a linter / formatter config: "ESLint with error prevention only"\
Pick additional lint features: "Lint and fix on commit"\
Where do you prefer placing config for Babel, PostCSS, ESLint, etc.? "In dedicated config files"\
Save this as a preset for future projects? "N"

When installation is complete run following commands:
```
cd frontend
npm run serve
npm install -D pug pug-plain-loader
```


## Docker

In our last class we will learn how to deploy our application using [Docker](https://www.docker.com/). Docker is a tool designed to make it easier to create, deploy, and run applications by using containers. Containers allow a developer to package up an application with all of the parts it needs, such as libraries and other dependencies, and ship it all out as one package.
[Source](https://opensource.com/resources/what-docker).

On [this site](https://www.docker.com/products/docker-desktop) you can find the download links for Mac and Windows and all the steps to follow.

If you don't manage to follow all the steps of that guide, don't worry. We will explore it more deeply in our class. You will just need to download and install Docker on your machine, and
make sure before the class that it is running (On Mac it should appear the little whale on the top menu bar, and if you click on it should indicate that is running. On Windows it will appear on the notifications area, bottom-right of the screen).

**Windows 10 Home Edition users** (or other editions that doesn't support current Docker version): There is a workaround to make it work -> [Docker Toolbox](https://docs.docker.com/toolbox/toolbox_install_windows/). You can start from Step 2. If after finishing Step 3 you run `docker run hello-world` and get the response showed on the guide, you should be good to go for the class! Anyhow, if you can come a bit before the class we can check it together.

## Heroku

After we create our containers with docker, we will deploy them to Heroku. When we deploy our apps, they will be accessible from anywhere in the world.

To install Heroku CLI, please follow instructions on [Heroku Dev Center here](https://devcenter.heroku.com/articles/heroku-cli#download-and-install).

Please also create a free Heroku account before coming to the class. Here you can create it: <https://signup.heroku.com/>

## Problem solving

> The following info will be useful for when you are studying/working on your own. On the class, please raise your hand in the moment you get stuck! There will be several teacher assistants there to help you immediately so you can continue following the class.

One of the skills a developer has to master, and also one of the most difficult to achieve at the beginning, is to find the correct answer for the problem they are facing. You are following the steps, everything seems to be fine and boom, you are receiving a weird error on the console or in VSCode. You have no idea why this is happening! You tried everything... So frustrating. But actually, this problem is faced by experienced programmers on a daily basis. And the solution is... to [Google](https://www.google.com/) it!

You will master this skill with time (what to actually type in google to find the answer you need), but at first you could try to just copy and paste on the google search the error you are receiving (try to only take the meaningful part of the error, for example: `Uncaught SyntaxError: Unexpected identifier`. You will probably get as first result a link to Stack Overflow.

[Stack overflow](https://stackoverflow.com/questions) is a community made by and for developers in which someone asks a question, and other developers answer it. If it's a good answer it gets upvotes, and if it's the answer that solved the problem, the OP (original poster) marks it with a green check. This is very useful for the developer community, because the problem we are currently facing most of the times someone else had it already, therefore here we can find many possible solutions to help with our coding struggles. Take a look [to some of the most entertaining questions](https://tutorialzine.com/2015/12/the-10-most-entertaining-stackoverflow-questions-of-all-time). :smiley:

If you are practising at home, and after researching you are stuck on a problem for more than 20-30 minutes, is time to ask for help in our channel!

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
- [x] MongoDB and Robo 3T
- [x] Docker
- [x] Heroku Account & CLI
