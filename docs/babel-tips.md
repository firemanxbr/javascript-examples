# using babel step-by-step

1. into directory babel-quickstart check a sample:

    index.html => simple code load a converted code: 
        <script src="dist/main.js"></script>

    src/main.js => code in ES6 

    dist/main.js & main.js.map => code converted from babel-cli 

2. install babel-cli:
$ npm install -g babel-cli

3. command for convert the ES6 code into babel-quickstart/ 
$ babel src --out-dir dist --source-maps

4. if don't have serve npm please install:
$ npm install -g serve

5. run the local serve into babel-quickstart/
$ serve .