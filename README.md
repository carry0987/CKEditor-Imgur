# CKEditor-Imgur
A plugin for ckeditor to upload image to Imgur<br>
`Imgur` is a photo storage service for free

## Demo
[Demo](https://carry0987.github.io/CKEditor-Imgur/)

## Usage 
You must install [CKEditor](https://github.com/galetahub/ckeditor) first and do following:<br>
1. Download this plugin [here](https://github.com/carry0987/CKEditor-Imgur/releases/)<br>
2. Unzip the file and put **[imgur](https://github.com/carry0987/CKEditor-Imgur/tree/master/plugins/)** folder to `/ckeditor/plugins/` <br>
3. Add plugin setting to your CKEditor `/ckeditor/config.js`:

```
CKEDITOR.editorConfig = function (config) {
    ...
    config.extraPlugins = 'imgur';
    // Get your client-id from https://api.imgur.com/oauth2/addclient
    config.imgurClientID = '24d8ba56326ec77'; //You need to change this key with your's
    ...
};
```

That's all. Your CKEditor have a imgur button in insert group.

![Imgur](https://i.imgur.com/lUQQCVC.gif)


