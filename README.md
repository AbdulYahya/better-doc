<p align="center"><img width="12.5%" src="assets/images/Better-Doc_ico.png"></p>
<p align="center"><img width="60%" src="assets/images/BetterDoc_logo.png"></p>

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
[![Project Version](https://img.shields.io/badge/Ver.-0.1.0-brightgreen.svg?style=for-the-badge)](https://github.com/AbdulYahya/js-gulp-gen)
&nbsp;&nbsp;&nbsp;&nbsp;
[![GitHub issues](https://img.shields.io/github/issues/AbdulYahya/js-gulp-gen.svg?style=for-the-badge)](https://github.com/AbdulYahya/js-gulp-gen/issues)
&nbsp;&nbsp;&nbsp;&nbsp;
[![GitHub license](https://img.shields.io/github/license/AbdulYahya/gulp-boilerplate-gen.svg?style=for-the-badge)](https://ayahya.mit-license.org)


## Basic Overview


<!-- ******NOTES******
  Move betterDoc.request('name', input).then(function(response) { } from
   betterDoc-interface to betterDoc and make the submit event listener ASYNC to make it wait for the promise
   to return
 -->


<!-- TO-DO's
    * Brief Overview
    * Refactor JS (Further separate UI from Backend Logic)
-->

## BetterDoctor API Key

First and foremost, you will need a BetterDoctor API key. Sign up for an account [here](https://developer.betterdoctor.com/signup). <br />

Once you are signed up, your API key will be located on the top right corner of your [dashboard](https://developer.betterdoctor.com/). <br />

## Install

To clone this repo:

```sh
$ git clone https://github.com/AbdulYahya/better-doc.git
```

From your terminal, cd into the directory you just cloned:

> :children_crossing: Path below is just an example an likely doesn't exist, unless of course you cloned into you desktop.

```sh
$ cd ~/Desktop/better-doc
```

Install all npm and bower package:

```sh
$ npm install && bower install
```

Please find and open the '.env' file located under the project's root directory. You will need to edit this file and replace the placeholder text `YOUR_API_KEY_GOES_HERE` with your new BetterDoctor API key:

> If you didn't signup for an API key, please follow the steps from 'BetterDoctor API Key' section above.<br />
> :bangbang: Place your key *inside* of the quotes

```js
exports.apiKey="YOUR_API_KEY_GOES_HERE"
```


Now, just run this gulp task:

```sh
$ gulp serve --prod
```

## License

[MIT License][Arbitrary case-insensitive reference text]

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the “Software”), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED “AS IS”, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

###### Copyright (c) 2018 Abdullah Yahya

[arbitrary case-insensitive reference text]: https://ayahya.mit-license.org
