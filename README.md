Browserified version of [pdfmake](http://pdfmake.org/) last 0.1.32 version

## Installation
```console
npm install pdfmake-browserified-mainlevel
```

## Node Usage

```javascript
var pdf = require('pdfmake-browserified-mainlevel');
var dd = { content: "This is a sample PDF printed with pdfMake" };
pdf.createPdf(dd).open();

## Note

I did this for fun. Contributions from people with a more solid node background are welcome!

## License

MIT
