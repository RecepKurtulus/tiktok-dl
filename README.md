# tiktok-dl

tiktok-dl is a npm package for downloading TikTok videos highest bitrate and without watermark.

## Installation

Use the package manager [npm](https://www.npmjs.com/) to install tiktok-dl.

```bash
npm i @deiutr/tiktok-dl
```

## Usage (NodeJS)

```javascript
const tiktokdl=require(tiktok-dl)

const url="ur video link"
//Required

const filePath="./Downloads"
//Required

tiktok-dl.downloadTiktokVideo(
url,
filePath
)
//Return stream files in filePath

```

## Contributing

Pull requests are welcome. For major changes, please open an issue first
to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License

[MIT](https://choosealicense.com/licenses/mit/)