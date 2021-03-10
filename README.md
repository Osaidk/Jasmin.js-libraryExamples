
<h1> Installation and Setups </h1>

<h3> To Install Locally: </h3>

  * npm install --save-dev jasmine (installing)

  * npx jasmine init (init a project)

  * jasmine examples (generating examples)

<h3> To Install Globally: </h3>

  * npm install -g jasmine (installing)

  * jasmine init (init a project)

  * jasmine examples (generating examples)


<h3> Setup: </h3>

  * The first step in setting up jasmine, is to create the project folder and navigate inside it.
  
  ```
  $ mkdir jasmine-project
  ```
  ```
 $ cd jasmine-project
  ```
  * Then you need to initialize your project for jasmine, this will create the required spec directory, using this command:
  
  ```
 $ jasmine init
  ```
  
  * You also need to initialize node for your project to populate the package.json file with default information, using this command:
  
   ```
 $ npm init
  ```
  
Now the library is ready to test your code. Create index.js, where you will have the code to be tested, in the project folder.

Create MyJSUtilities.js inside the spec folder, this is where you will include your test code. 
