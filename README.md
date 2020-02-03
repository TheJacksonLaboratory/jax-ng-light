# jax-ng-light
Light Angular Material theme for The Jackson Laboratory

# How To Install

## 1. Make sure your Angular project is setup to use Sass
If it isn't:
1. Either do `ng config defaults.styleExt=scss` or manually edit the `style` property in your angular.json file
2. Rename your global styles.css file to styles.scss 

## 2. Make sure you have git installed

## 3. Install Package
From your Angular project directory,  
`npm install thejacksonlaboratory/jax-ng-light`  
This will also install the `jax-theme` package, a dependency

## 4. Import the Sass file
1. Remove any `@include mat-core();` at-rules from your styles.scss file
2. To the end of your styles.scss file, append this line:  
`@import '~jax-ng-light/theme';`
