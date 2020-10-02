<p align="center">
  <a href="http://gulpjs.com">
    <img height="257" width="114" src="https://raw.githubusercontent.com/gulpjs/artwork/master/gulp-2x.png">
  </a>
</p>

[![NPM version][npm-image]][npm-url] [![Downloads][downloads-image]][npm-url] [![Gitter chat][gitter-image]][gitter-url]


# Gulp Combine Files

> This plugin will allow you to combine multiple JS files using (@gulp-append / @gulp-prepend / @gulp-inline)

## Getting Started
If you haven't used [Gulp](http://gulpjs.com/) Once you're familiar with that process, you may install this plugin with this command:

```shell
npm install gulp-combine-files --save-dev
```

Once the plugin has been installed, it may be enabled inside your Gulpfile with this line of JavaScript:

```js
var combine_files = require('gulp-combine-files');
```


### Usage

```js
var gulp = require('gulp'),
    combineFiles = require('gulp-combine-files');

gulp.task('combine:test',function(){
	return gulp.src("path_to_your_script_file")
	.pipe(combineFiles({
	    append:'gulp-append',
	    prepend:'gulp-prepend',
	    inline:'gulp-inline',
	})).pipe(gulp.dest('path_to_dist'));
});
```

### Options

#### options.append
Type: `String|Bool`
Default value: `'gulp-append'`

A string value that is used to do something with whatever.

#### options.prepend
Type: `String|false`
Default value: `'gulp-prepend'`

A string value that is used to do something else with whatever else.

#### options.inline
Type: `String|false`
Default value: `'gulp-inline'`

A string value that is used to do something else with whatever else.

--- 

## 📝 Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

[Checkout CHANGELOG.md](/CHANGELOG.md)

## 🤝 Contributing
If you would like to help, please take a look at the list of [issues](issues/).

## 💰 Sponsor
[I][twitter] fell in love with open-source in 2013 and there has been no looking back since! You can read more about me [here][website].
If you, or your company, use any of my projects or like what I’m doing, kindly consider backing me. I'm in this for the long run.

- ☕ How about we get to know each other over coffee? Buy me a cup for just [**$9.99**][buymeacoffee]
- ☕️☕️ How about buying me just 2 cups of coffee each month? You can do that for as little as [**$9.99**][buymeacoffee]
- 🔰         We love bettering open-source projects. Support 1-hour of open-source maintenance for [**$24.99 one-time?**][paypal]
- 🚀         Love open-source tools? Me too! How about supporting one hour of open-source development for just [**$49.99 one-time ?**][paypal]

## 📜  License & Conduct
- [**General Public License v3.0 license**](LICENSE) © [Varun Sridharan](website)
- [Code of Conduct](code-of-conduct.md)

## 📣 Feedback
- ⭐ This repository if this project helped you! :wink:
- Create An [🔧 Issue](issues/) if you need help / found a bug

## Connect & Say 👋
- **Follow** me on [👨‍💻 Github][github] and stay updated on free and open-source software
- **Follow** me on [🐦 Twitter][twitter] to get updates on my latest open source projects
- **Message** me on [📠 Telegram][telegram]
- **Follow** my pet on [Instagram][sofythelabrador] for some _dog-tastic_ updates!

---

<p align="center">
<i>Built With ♥ By <a href="https://sva.onl/twitter"  target="_blank" rel="noopener noreferrer">Varun Sridharan</a> 🇮🇳 </i>
</p>

---

<!-- Personl Links -->
[paypal]: https://sva.onl/paypal
[buymeacoffee]: https://sva.onl/buymeacoffee
[sofythelabrador]: https://www.instagram.com/sofythelabrador/
[github]: https://sva.onl/github/
[twitter]: https://sva.onl/twitter/
[telegram]: https://sva.onl/telegram/
[email]: https://sva.onl/email
[website]: https://sva.onl/website/

<!-- Poser -->
[latest-stable-version-img]: https://poser.pugx.org/varunsridharan/php-autoloader/version
[latest-Unstable-version-img]: https://poser.pugx.org/varunsridharan/php-autoloader/v/unstable
[total-downloads-img]: https://poser.pugx.org/varunsridharan/php-autoloader/downloads
[Latest-Unstable-version-img]: https://poser.pugx.org/varunsridharan/php-autoloader/v/unstable
[license-img]: https://poser.pugx.org/varunsridharan/php-autoloader/license
[composerlock-img]: https://poser.pugx.org/varunsridharan/php-autoloader/composerlock
[wpcs-img]: https://img.shields.io/badge/WordPress-Standar-1abc9c.svg

[downloads-image]: http://img.shields.io/npm/dm/gulp-combine-files.svg
[npm-url]: https://www.npmjs.com/package/gulp-combine-files
[npm-image]: http://img.shields.io/npm/v/gulp-combine-files.svg
[gitter-url]: https://gitter.im/gulpjs/gulp
[gitter-image]: https://badges.gitter.im/gulpjs/gulp.svg