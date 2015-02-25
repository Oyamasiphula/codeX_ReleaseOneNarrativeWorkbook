# codeX_Feb2015NarrativeWorkbook

This is a companion workbook that will assist you to work through the codeX Narrative that is to be provided. Resources and references provided will assist you in your journey will be published in the repository.

Note:

* This is a living document, it will change over time
* please contribute to this workbook by pull requests
* check back here regularly for new information

## Javascript on the command line

So far all the Javascript you wrote ran in a web browser. That don't need to be the case, one can run Javascript on the command line and use it to program much more than buttons, fields and elements in the browser. A world of programming Web Servers, Robots and Databases to name but a few options awaits.

##Installing Node

On Ubuntu you can install Node JS from the command line using ```apt-get```.

You should already have it installed on your laptop if you completed the codeX February 2015 intro.

The installation instructions are as follows:

* ```sudo apt-get install node-legacy``` 
* ```sudo apt-get install npm```

Open a terminal window:

* type ```nodejs``` and press enter - you should now be in a Node JS console - you should get no errors. (on a non Ubuntu machine the command is called ```node```). Use ctrl-C to get out of it
* type ```npm``` you should see some information about npm on the console

Now you are ready to use Javascript from the command line. 

##Node JS Javascript from the command line

Let's run a simple javascript script from the command line:

	* Create a file called ```hello.js``` 
	* copy this text into the file: ```console.log('hello world!');```
	* Save the file
	* now run it using ```nodejs hello.js```
	* what happens?

So what just happend? You liberated your Javascript knowledge from the command line. 

Now proof this to yourself and write some Javascript that use:
* an ```if``` statement
* a ```for``` loop
* write a simple function
* what else you need to get comfortable

If you can create about 5 different javascript file (.js) files to get more comfortable with Javascript on the command line.

## Asyncronous

One thing to note is that Node JS is asyncronous by nature and a concept using call backs is used heavily.


	
##Introduce the Node API

Over and above the normal capabilities of Javascript Node JS can do loads more things like:

* reading and creating files on disk
* making HTTP calls
* host a HTTP/TCP server

If you are curious about what is possible have a look here: http://nodejs.org/api/

But don't get bogged down in the details to much at this stage.

##modules

To reuse Javascript code in the Web browser is easy one just need to reference the code in the right order using using a script tag.

In Node things are different and it use the CommonJS module pattern, which handle dependencies between your different pieces of Javascript code.

>   http://nodejs.org/api/modules.html
  
One of the major things of Node is that there are loads of third party libraries out there that you can reuse. These libraries allows you to access databases, create API's or even create a Robot.

The central library of libraries is called, http://npmjs.org, you use the ```npm``` command to install libraries from there.
  
A few usefull npm commands to look into are:

  * ```npm install <library name>```
  * ```npm install -g <library name>```
  * ```npm init package.json```
  * ```install --save``

## Need to wrap your head around Node js

Try these quick code challanges to wrap you head around node JS 

### Guess the number:

Write a simple number guessing game as you did in Codecademy using these modules:
 
 * https://www.npmjs.com/package/readline-sync
 * https://www.npmjs.com/package/chalk

### TestMyCode in Node JS

Convert the TestMyCode framework to run in node js.


### Install some modules

Here are some modules that you can install to get use to ```npm``.

Remember that you install modules using npm like this : ```npm install < module_name >```

* https://www.npmjs.com/package/text-animation
* https://www.npmjs.com/package/figlet

* https://www.npmjs.com/package/bash-color
* https://www.npmjs.com/package/commander
* https://www.npmjs.com/package/chalk


## modules

parameters from the command line

## create a module
module.function name = function(){}
module.export = <constructor function>

use the module just created

some basic javascript on the command line a module called utilities:
  * makeUpper - take a sentence and the index of the word in the sentence to make uppercase
  * makeLower - take a sentence and the index of the word in the sentence to make lowercase
  * capitalize - take a sentence and the index of the word in the sentence to capitalize

	
## Intro to JQuery
* Do Codecademy if you are not confortable with JQuery
* Do Red & Green using JQuery
* Animate the red & green transissions
* Feedback ? How is it different from what you did previously

## File handling
* Reading
* Writing
* Sync vs Async

##Processing the data:
* Basic data modelling
* Control Breaks - reports with subheaders
      http://en.wikipedia.org/wiki/Control_break	
* Sorting data

## Create reports:
* Plain HTML & CSS
* Responsive design basics
* Bootstrap - getbootstrap.com
* Foundation - http://foundation.zurb.com/

## Setup a basic web server:
* Setup
* Routes
* Parameters
* Rendering

## Templating: 
* Use basic template
* Use handlebars

