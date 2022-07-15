<p align="center">
  <a href="https://cdn.itwcreativeworks.com/assets/playlisteer/images/logo/playlisteer-brandmark-black-x.svg">
    <img src="https://cdn.itwcreativeworks.com/assets/playlisteer/images/logo/playlisteer-brandmark-black-x.svg" width="100px">
  </a>
</p>

<p align="center">
  <img src="https://img.shields.io/github/package-json/v/playlisteer/playlisteer.svg">
  <br>
  <img src="https://img.shields.io/librariesio/release/npm/playlisteer.svg">
  <img src="https://img.shields.io/bundlephobia/min/playlisteer.svg">
  <img src="https://img.shields.io/codeclimate/maintainability-percentage/playlisteer/playlisteer.svg">
  <img src="https://img.shields.io/npm/dm/playlisteer.svg">
  <img src="https://img.shields.io/node/v/playlisteer.svg">
  <img src="https://img.shields.io/website/https/playlisteer.com.svg">
  <img src="https://img.shields.io/github/license/playlisteer/playlisteer.svg">
  <img src="https://img.shields.io/github/contributors/playlisteer/playlisteer.svg">
  <img src="https://img.shields.io/github/last-commit/playlisteer/playlisteer.svg">
  <br>
  <br>
  <a href="https://playlisteer.com">Site</a> | <a href="https://www.npmjs.com/package/playlisteer">NPM Module</a> | <a href="https://github.com/playlisteer/playlisteer">GitHub Repo</a>
  <br>
  <br>
  <strong>playlisteer</strong> is the official npm module of <a href="https://playlisteer.com">Playlisteer</a>, a service that pitches your music to trending Spotify playlists & large SoundCloud channels
</p>

## Playlisteer Works in Node AND browser environments
Yes, this module works in both Node and browser environments, including compatibility with [Webpack](https://www.npmjs.com/package/webpack) and [Browserify](https://www.npmjs.com/package/browserify)!

## Features
* Getting proxy lists

### Getting an API key
You can use so much of `playlisteer` for free, but if you want to do some advanced stuff, you'll need an API key. You can get one by [signing up for a Playlisteer account](https://playlisteer.com/authentication/signup).

## Install Playlisteer
### Install via npm
Install with npm if you plan to use `playlisteer` in a Node project or in the browser.
```shell
npm install playlisteer
```
If you plan to use `playlisteer` in a browser environment, you will probably need to use [Webpack](https://www.npmjs.com/package/webpack), [Browserify](https://www.npmjs.com/package/browserify), or a similar service to compile it.

```js
const playlisteer = new (require('playlisteer'))({
  // Not required, but having one removes limits (get your key at https://playlisteer.com).
  apiKey: 'api_test_key'
});
```

### Install via CDN
Install with CDN if you plan to use Playlisteer only in a browser environment.
```html
<script src="https://cdn.jsdelivr.net/npm/playlisteer@latest/dist/index.min.js"></script>
<script type="text/javascript">
  var playlisteer = new Playlisteer({
    // Not required, but having one removes limits (get your key at https://playlisteer.com).
    apiKey: 'api_test_Key'
  });
</script>
```

### Use without installation
You can use `playlisteer` in a variety of ways that require no installation, such as `curl` in terminal/shell. See the **Use without installation** section below.

## Using Playlisteer
After you have followed the install step, you can start using `playlisteer` to pitch your music to multiple major music channels

For a more in-depth documentation of this library and the Playlisteer service, please visit the official Playlisteer website.

## Use without installation
### Use Playlisteer with `curl`
```shell
# Standard
curl -X POST https://api.playlisteer.com
```

## What Can Playlisteer do?
Playlisteer is a service that pitches your music to trending Spotify playlists & large SoundCloud channels. Use this amazing [Spotify playlist pitching service](https://playlisteer.com/spotify-promotion)

## Final Words
If you are still having difficulty, we would love for you to post
a question to [the Playlisteer issues page](https://github.com/playlisteer/playlisteer/issues). It is much easier to answer questions that include your code and relevant files! So if you can provide them, we'd be extremely grateful (and more likely to help you find the answer!)

## Projects Using this Library
* coming soon!

Ask us to have your project listed! :)
