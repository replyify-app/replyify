<p align="center">
  <a href="https://replyify.app">
    <img src="https://cdn.itwcreativeworks.com/assets/replyify/images/logo/replyify-brandmark-black-x.svg" width="100px">
  </a>
</p>

<p align="center">
  <img src="https://img.shields.io/github/package-json/v/replyify/replyify.svg">
  <br>
  <img src="https://img.shields.io/librariesio/release/npm/replyify.svg">
  <img src="https://img.shields.io/bundlephobia/min/replyify.svg">
  <img src="https://img.shields.io/codeclimate/maintainability-percentage/replyify/replyify.svg">
  <img src="https://img.shields.io/npm/dm/replyify.svg">
  <img src="https://img.shields.io/node/v/replyify.svg">
  <img src="https://img.shields.io/website/https/replyify.app.svg">
  <img src="https://img.shields.io/github/license/replyify/replyify.svg">
  <img src="https://img.shields.io/github/contributors/replyify/replyify.svg">
  <img src="https://img.shields.io/github/last-commit/replyify/replyify.svg">
  <br>
  <br>
  <a href="https://replyify.app">Site</a> | <a href="https://www.npmjs.com/package/replyify">NPM Module</a> | <a href="https://github.com/replyify/replyify">GitHub Repo</a>
  <br>
  <br>
  <strong>replyify</strong> is the official npm module of <a href="https://replyify.app">Replyify</a>, a free Gmail auto-reply app with follow-up emails!
</p>

## 🌐 Replyify Works in Node AND browser environments
Yes, this module works in both Node and browser environments, including compatibility with [Webpack](https://www.npmjs.com/package/webpack) and [Browserify](https://www.npmjs.com/package/browserify)!

## 🦄 Features
* Getting proxy lists

### 🔑 Getting an API key
You can use so much of `replyify` for free, but if you want to do some advanced stuff, you'll need an API key. You can get one by [signing up for a Replyify account](https://replyify.app/signup).

## 📦 Install Replyify
### Option 1: Install via npm
Install with npm if you plan to use `replyify` in a Node project or in the browser.
```shell
npm install replyify
```
If you plan to use `replyify` in a browser environment, you will probably need to use [Webpack](https://www.npmjs.com/package/webpack), [Browserify](https://www.npmjs.com/package/browserify), or a similar service to compile it.

```js
const replyify = new (require('replyify'))({
  // Not required, but having one removes limits (get your key at https://replyify.app).
  apiKey: 'api_test_key'
});
```

### Option 2: Install via CDN
Install with CDN if you plan to use Replyify only in a browser environment.
```html
<script src="https://cdn.jsdelivr.net/npm/replyify@latest/dist/index.min.js"></script>
<script type="text/javascript">
  var replyify = new Replyify({
    // Not required, but having one removes limits (get your key at https://replyify.app).
    apiKey: 'api_test_Key'
  });
</script>
```

### Option 3: Use without installation
You can use `replyify` in a variety of ways that require no installation, such as `curl` in terminal/shell. See the **Use without installation** section below.

## ⚡️ Using Replyify
After you have followed the install step, you can start using `replyify` to setup automatic Gmail replies and follow-up emails!

For a more in-depth documentation of this library and the Replyify service, please visit the official Replyify website.

## 🔧 Use without installation
### Use Replyify with `curl`
```shell
# Standard
curl -X POST https://api.replyify.app
```

## 📝 What Can Replyify do?
Replyify is a [free Gmail auto-reply](https://replyify.app) app with follow-up emails!

## 🗨️ Final Words
If you are still having difficulty, we would love for you to post
a question to [the Replyify issues page](https://github.com/replyify/replyify/issues). It is much easier to answer questions that include your code and relevant files! So if you can provide them, we'd be extremely grateful (and more likely to help you find the answer!)

## 📚 Projects Using this Library
* coming soon!

Ask us to have your project listed! :)
