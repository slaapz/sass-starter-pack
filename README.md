#Sass Starter Pack
This project was a follow-along from Traversy Media's YouTube channel (@bradtraversy). It is a boiler plate template for developing with Sass. It uses Gulp and BrowserSync to automate the process so you can focus on coding rather than compiling and refreshing your browser...this does it for you

#Module versions used for this project:

*gulp 3.9.1
*gulp-sass 3.1.0
\*browser-sync 2.18.13

#Important note
I ran into an issue when trying to start gulp. I was getting an error pointing to the watch and serve task in gulpfile.js:

`AssertionError: Task function must be specified`

The issue was that I was using gulp 4.0.0 and the manner in which a task is used was changed.

Below is a link to an article that shows how to use gulp 4.0.0. I haven't tried it yet; maybe in a later project:

https://codeburst.io/switching-to-gulp-4-0-271ae63530c0
