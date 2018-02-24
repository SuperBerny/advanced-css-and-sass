In the package.json file add a start script to "scripts"

"scripts" : {
   "compile:sass": "node-sass sass/main.css css/style.css"
}

#Anatomy:
"compile:sass": "node-sass sass/main.scss css/style.css"

First argument after node-sass is the input file
   .scss file will come first because Sass needs to be read first and compiled to CSS file.

Second argument after sass/main.scss is the output file
   after the .scss file is read it will then be compiled into the specified css file.

#important for file paths
   remember that node will start looking from the package.json file.
