# Sparky

## Bootstrap 3 Starter Project Folder
By: Jacob Lett of https://bootstrapcreative.com/

Bootstrap Sass + Custom scripts and styles + Grunt 

This starter project folder uses the Bootstrap 3 Sass files to create a custom theme. 

## Demo
https://jacoblett.github.io/Sparky/

## Use this if
You need to support IE9 and below

### Get Started

- Create a new repo in your GitHub account and copy this repo clone URL https://github.com/JacobLett/Sparky.git

- In your new repo on GitHub.com Click the "+" next to your profile image and select "import respository" and paste in the clone url

- Once the new repo is created click on the green button that says "open in desktop"

- In your windows GitHub application right click on the new repo and select "open in explorer"

- Open up git shell and enter the following commands

    npm install

    bower install

    grunt watch

- Commit your changes and sync to your new repo

#### To test the site using GitHub pages
Go to your repo settings on GitHub.com and choose your master branch for github pages.

## Are you new to Node.js and Grunt projects?
I created a 7-part video series to show you how to get setup and then customize Sparky.

[![Bootstrap 3 Sass Customization Tutorial](http://img.youtube.com/vi/hJV-4rhjK4Q/0.jpg)](https://www.youtube.com/watch?v=FsIPmDe-3KU&lc=z13owlkayn3iyfeqw04cg1yzan2dsjnbec0)

## Common Questions

### Where is the Css compiled , i can not see where it compiles the sparky variables?
It is compiled in the dist or distribution folder. This folder will contain anything processed or compiled by Grunt - https://github.com/JacobLett/Sparky/tree/master/dist/css

### Can you add more scss files in sass folder like _buttons.scss?
You sure can. Just add the underscore prefix and then reference it the style.scss file so it is imported in https://github.com/JacobLett/Sparky/blob/master/sass/styles.scss

### When you upload the site or page to the server which are the files you have to upload?
All you need is the compiled files in the dist folder. The readme file helps a future developer find the source code in a public/private repo

- dist
- README.md
- humans.txt
- index.html
- robots.txt

## How do you get grunt to stop watching the file?
All you have to do is close the shell window. If you enter the command "start grunt watch" it will open two shell windows. One watching and the other for new commands. I usually just do "grunt watch" and leave it watching all day as I go in and out of the day. Then when I go home I commit my changes to github and close the command shell.

## What chrome extension does the auto refresh?
I use https://chrome.google.com/webstore/detail/livejs/fnenjmjepccoionjgdgimlnppidghbbg﻿
