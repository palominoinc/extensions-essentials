Getting started
===============

Please refer to our \[WebPal Developer Guide\](https://www.gitbook.com/book/palomino/webpaldev/details) for more information on how to use WebPal extensions

- Writing and extension
- GitHub integration

NOTE: 'extensions-essentials' is required for all WebPal extensions

Extensions-essentials 
======================

Includes resources relevant, such as Bootstrap, FontAwesome, Jquery, etc. for all WebPal extensions.

Remember to add `<xsl:call-template name="include-extension-styles"/>` and `<xsl:call-template name="include-extension-scripts"/>` to your template so all your resource-links from all your extension will be included.