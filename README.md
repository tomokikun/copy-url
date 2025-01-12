# copy-url

This is a Chrome extension that allows you to copy URLs in a convenient (shortener) way.

It copies the URL to the clipboard, excluding query strings and other parameters, from the following sites:

- [Amazon](https://www.amazon.co.jp/) [*Only compatible with amazon.co.jp]
- [YouTube](https://www.youtube.com/)
- [Stack Overflow](https://stackoverflow.com/)

## How to Use

1. (First time only) Download the latest zipped Chrome extension from [releases](https://github.com/tomokikun/copy-url/releases). (This chrome extension is not yet available in Chrome Web Store.)
1. (First time only) Unzip the downloaded zip file.
1. (First time only) Open chrome://extensions/ in Chrome and load the built Chrome extension.
1. Open the context menu (right-click or any other method to display the menu) while on the supported site mentioned above, and click on `いい感じでURLをコピー`.


## Contributing

```bash
# install packages
npm install

# build
npm run build
```

```bash
# hot-reload, but click the update button manually to reload the built extension on the browser
npm run dev
```

```bash
# lint and format
npm run fix
```

```bash
# test
npm run test
```
