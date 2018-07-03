# Gitbook plugin download-book

GitBook Plugin to add a link on every page to download PDF.

To use this plugin, you have to modify your book.json configuration file.

```js
{
  "plugins": ["download-book"],
  "pluginsConfig": {
    "download-book": {
      "url": "URL_TO_BOOK.PDF",
      "label": "Download PDF"
    }
  }
}
```
