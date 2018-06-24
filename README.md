# parceljs-posthtml-favicons
testing a bug with the [posthtml-favicons plugin](https://github.com/mohsen1/posthtml-favicons) and [parceljs](https://parceljs.org/)

# instructions

Run `npm install && npm start`

# result

![error message](https://raw.githubusercontent.com/jessehattabaugh/parceljs-posthtml-favicons/master/issue.png)

# expected

`posthtml-favicons` is installed, and the `.posthtmlrc` file specifies the plugin, so the module should be found, and the `<link rel="icon">` tag should be parsed and the `jesse.jpg` file should be transformed into various favicon files. 