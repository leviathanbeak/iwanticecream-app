# I want ice cream app
### made with Ionic 2 and ApiAI

simple messaging app, that connects to Api.AI and [NodeJS Server](https://github.com/leviathan88/icecream-server) and talks to the chatbot

#### to run it on your device: 
(make sure you have [Android SDK](https://developer.android.com/studio/index.html) installed)
(plug in your mobile phone and add developer options and allow the device for debugging and to be connected with your PC)
```sh
$ npm install -g cordova (if not already installed)
$ npm install -g ionic (if not already installed)
$ git clone https://github.com/leviathan88/iwanticecream-app.git
$ cd iwanticecream-app
$ npm install
$ ionic serve (in order for ionic to create /www folder, then just ctrl+c to end it)
$ ionic platform add android (to add android platform)
$ cordova plugin add https://github.com/vijtad/SpeechRecognizer (additionally install this plugin for Speech Recognition)
$ ionic run android
```
order some ice cream!