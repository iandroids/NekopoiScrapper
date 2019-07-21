# Nekopoi Scrapper

*Scrapper for nekopoi*
# [Nekopoi](https://aapks.com/apk/nekopoi-lite-anti-ipo-99/)
## Installation

```sh
$ npm install
```

## Usage

```sh
const NekopoiScrapper = require('./NekopoiScrapper');

// Latest Release
NekopoiScrapper.getLatest()
    .then((data) => console.log(data));

// Get Page Info
NekopoiScrapper.getInfo("http://nekopoi.cash/dokidoki-little-ooyasan-episode-4-subtitle-indonesia")
    .then((data) => console.log(data));
```

## Credit

Moe Poi ~ / [@moepoi](https://github.com/moepoi)
