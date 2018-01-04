#Sparky
##Bootstrap 3 Starter Project Folder
By: Jacob Lett of https://bootstrapcreative.com/

Bootstrap Sass + Custom scripts and styles + Grunt

This starter project folder uses the Bootstrap 3 Sass files to create a custom theme.

Demo: https://jacoblett.github.io/Sparky/

##Use this if
You need to support IE9 and below

###Get Started

npm install

npm run watch

update package.json with Bootstrap version

npm install bootstrap@4.0.0-beta.3 --save-dev

npm run build
OR
npm run-script build


https://github.com/damonbauer/npm-build-boilerplate


"uglify": "mkdirp dist/js -p && uglifyjs src/js/*.js -m -o dist/js/scripts.js && uglifyjs src/js/*.js -m -c -o dist/js/scripts.min.js && uglifyjs src/js/*.js -m -c -o dist/js/scripts.min.js",



"uglify": "mkdirp dist/js -p && src/js/plugins.js src/js/main.js \ -m -c -o dist/js/scripts.min.js",



"uglify": "mkdirp dist/js -p && uglifyjs src/js/plugins.js src/js/main.js > -m -c -o --comments dist/js/scripts.min.js && uglifyjs src/js/defer.js > -m -c -o --comments dist/js/defer.min.js && uglifyjs src/js/jquery.js > -m -c -o --comments dist/js/jquery.min.js",
