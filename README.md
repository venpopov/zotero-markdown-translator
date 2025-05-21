# zotero-markdown-translator
A simple Zotero translator that creates a Markdown Link when exporting

## Fork info

This fork update the URI scheme to one that is supported by both the desktop and iOS zotero application. The origianl fork uses a scheme that has been apparently replaced in 2014: https://forums.zotero.org/discussion/124371/the-uri-deeplink-you-get-from-desktop-app-is-not-the-same-that-works-on-ios#latest

## Demo 
![](demo.gif)
## How to Install
1. Download **Markdown.Item.URI.js** from [Github](https://github.com/silentdot/zotero-markdown-translator/releases)
2. Place file inside the "translators" directory in your [Zotero data folder](http://www.zotero.org/support/zotero_data#locating_your_zotero_library)
3. Restart Zotero
4. In the Zotero Preferences go to the “Export” and set the Default Output Format to “Markdown Item URI” (this will be towards the bottom of the list)
![](install.png)

You can now take advantage of Zotero’s [quick copy](http://www.zotero.org/support/creating_bibliographies#quick_copy) functionality and drag&drop links from the item in your client right into Obsidian.
