# PullnRefresh_Chrome_Extension

## Please make sure that `gulp` and `bower` was installed on your system using this command:
npm i -g gulp-cli bower

## Transform updated source written by ES2015 (default option)
gulp babel

## or Using watch to update source continuously
gulp watch

## Make a production version extension
gulp build


Visit chrome://extensions in your browser (or open up the Chrome menu by clicking the icon to the far right of the Omnibox:  The menu's icon is three horizontal bars. and select Extensions under the Tools menu to get to the same place).

Ensure that the Developer mode checkbox in the top right-hand corner is checked.

Click Load unpacked extension… to pop up a file-selection dialog.

Navigate to the directory in which your extension files live, and select it.

Alternatively, you can drag and drop the directory where your extension files live onto chrome://extensions in your browser to load it.

If the extension is valid, it'll be loaded up and active right away! If it's invalid, an error message will be displayed at the top of the page. Correct the error, and try again.

