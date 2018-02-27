# Do This First

Once complete delete the ReadME from your project folder

## Install Node-Sass as a dev dependency

[node-sass](https://www.npmjs.com/package/node-sass)

or run the code:

```
npm install node-sass --save-dev
```

### Add Script to package.json

```
"scripts": {
                  <!-- Input file --><!-- Output file -->
   "sass": "node-sass sass/main.scss css/style.css"
}
```

*Remember that package.json will start looking out from the directory that it is in.
