#Flint
##Bootstrap 3 Starter Template

This starter project folder uses the Bootstrap 3 less files to create a custom theme. 

Learn more: https://bootstrapcreative.com/

###Prerequisites for use
- Familiar with Grunt and compiling LESS and javascript
- jQuery basics
- Bootstrap 3 Framework classes


####styles.less
```
// The core bootstrap styles
@import "bootstrap/bootstrap.less";

// Bootstrap default overrides - settings and mixins
@import "my-variables.less";
@import "my-mixins.less";

// Add any javascript plugin styles here
@import "plugins.less";

// Custom fonts
@import "fonts.less";

// Helper classes
@import "helper.less";

// Your main core theme styles
@import "main.less";

```

bower install fontawesome --save
bower install bootstrap-sass --save

https://www.npmjs.com/package/grunt-postcss

start grunt watch