# mpe-puppeteer-header-footer-example

* markdown-preview-enhanced
* puppeteer
* Atom
* atom-image-resize

## puppeteer settings in front-matter

* front-matter
  * https://shd101wyy.github.io/markdown-preview-enhanced/#/puppeteer
* pdf settings
  * https://github.com/GoogleChrome/puppeteer/blob/v1.9.0/docs/api.md#pagepdfoptions
  * displayHeaderFooter: true
  * headerTemplate: html fragment
  * footerTemplate: html fragment
* **Only inline style supported (ignored css files)**
  * https://github.com/GoogleChrome/puppeteer/issues/4254
* **Only base64 image or online image supported**
  * https://github.com/GoogleChrome/puppeteer/issues/2443
  * https://atom.io/packages/atom-image-resize
