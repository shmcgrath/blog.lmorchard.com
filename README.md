# blog.lmorchard.com

[![Build Status](https://travis-ci.org/lmorchard/blog.lmorchard.com.svg?branch=master)](https://travis-ci.org/lmorchard/blog.lmorchard.com)

This is my blog. There are many others like it, some of them mine. This one is
also mine.

## Setup
```
npm install
cp config.js-dist config.js
vim config.js
gulp indexes
gulp build
gulp deploy
```

## Writing and previews
```
gulp server
```

## TODO

* Genericize this stuff into a reusable package?

* Auto-generate scaled images from thumbnails identified in posts

* Consider versioning & long-expiring CSS & JS
  * https://github.com/sindresorhus/gulp-rev

* Use awspublish-router for more per-file-type handling?
  * https://www.npmjs.com/package/gulp-awspublish-router

* Replace Font Awesome with SVG icons for top tags

* Switch to Browserify & Babel if/when I want some JS enhancements again

* Revive the comments archiver to preserve closed Disqus threads

* Quick gulp task to produce a new boilerplated post

* Switch from Swig to [Nunjucks](http://mozilla.github.io/nunjucks/) because it's a Mozilla project hooray

* Prev / next nav links for posts?
