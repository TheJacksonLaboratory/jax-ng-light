# jax-ng-light
Light Angular Material Theme for The Jackson Laboratory

# How To Install

## Make sure your Angular project is setup to use Sass
If it isn't:
1. Either do `ng config defaults.styleExt=scss` or manually edit the `style` property in your angular.json file
2. Rename your global styles.css file to styles.scss 

## Install Package
From your Angular project directory,  
`npm install jax-ng-light`  
This will also install the `jax-theme` package, a dependency

## Import the Sass file
To the end of your global styles.scss file, append this line:  
`@import '~jax-ng-light/jax-light';`

