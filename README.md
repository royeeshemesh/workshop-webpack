npm init

npm install webpack

add to package.json -> scripts -> 
    "build": "webpack --entry ./src/app.js --output-filename ./dist/bundle.js"
    
import {myList} from './magic-button';

export var myList = document.getElementById("list");

<script src="dist/bundle.js"></script> 
