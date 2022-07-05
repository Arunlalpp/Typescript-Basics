# Typescript-Bascis


* Typescript is an It is a strict syntactical superset of JavaScript and adds optional static typing to the language
* Basically typescript is essentially javascript with type checking with typescript
* Which means set the type of variables 
* The greate feature is that  ```TypeChecking```
* This will boost the features like code completion and refactoring
## Benefints of typescript
- static typing
- code completion 
- refactoring 
- ```shorthand notation```
    
    Shorthand notations are a part of the Wolfram Language's rich syntax system that allows multiple ways to feed arguments to functions.
## Drawbacks

1. completion
  In this time browser don understand the typescript code, So we created the sepparate identifiers like ```.ts``` and ```.js```
- Where the typescript ompiler is compiled and translate to javascript.
  The process is alled as ```Transpilation```
2. Dicsipline in coding
-  Transpilies to javascript      
## Setting up the Development Environment

- Need  node package manager to compile typescripte cimbiler
- For ubuntu user use ```sudo npm i -g typescript ```
- To display typescript version ```tsc -v ```
- To use visual studio code or any other 

## Start Programming
- Create  app
- Create an index.ts file and compile them using ```tsc index.ts```
- After this will create a ```index.js``` file

## Configure the typescript compiler

- To init Typescript  ```tsc --init```
- after the json cofig is created then create an folder called src 
- Move the ```.ts``` to that src 
## tsc.config structures

- Set the path for the modules ```./src``` 
- Also set the directory to the ```Emit```  section ```outdir``` add dist 
  :-  When we compiled the typescript the files are stored in the dust folder
- remove comments ```removeComments``` 
  :-  It will remove the comments that we add in our typescript file it helps to shorter the javascript file.
-  ```noEmitOnError```   :- Defauklt when we compile our code it will help to not to generate when there exist an error in the ts file 
-   




