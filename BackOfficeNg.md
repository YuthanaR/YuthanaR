# Angular Projects

## BackOffice NG

1. create Angular version 17 workspace named: backofficeweb with this command
   ng new BackOfficeWeb --skip-install --skip-tests --routing --ssr false --style scss
2. install Angular Material and Angular CDK with following steps:
   reference: <https://v5.material.angular.io/guide/getting-started#step-1-install-angular-material-and-angular-cdk>
   2.1 npm install --save @angular/material @angular/cdk
   2.1 npm install --save @angular/animations
   2.3 include material theme by importing css file into styles.css
3. add Gesture support by imporing hammerjs
   3.1 npm install --save hammerjs
   3.2 import the hammerjs into src/main.ts
4. Add Material Icons by adding link to index.html
   link href="<https://fonts.googleapis.com/icon?family=Material+Icons>" rel="stylesheet"
5. Set Material theme by adding prebuilt theme to styles [] in angular.json like this
   ...
   "styles": [
   {
   "input": "node_modules/@angular/material/prebuilt-themes/indigo-pink.css"
   },
   "src/styles.scss"
   ]
   ...
