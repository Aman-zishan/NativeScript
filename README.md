<p align="center">
  <a href="http://www.nativescript.org">
    <img alt="NativeScript" src="https://i.imgur.com/YmNIMqS.png" />
  </a>
</p>

<h1 align="center"> 
NativeScript 
</h1>

[![Build Status](https://travis-ci.org/NativeScript/NativeScript.svg?branch=master)](https://travis-ci.org/NativeScript/NativeScript)


[NativeScript](http://www.nativescript.org) empowers you to access native api's from JavaScript directly. The framework currently provides iOS and Android runtimes for rich mobile development and can be utilized in a number of diverse use cases.

# Develop

```bash
# setup workspace for development
$ npm run setup
# list all available commands to run
$ npm start
```

# Packages

* [@nativescript/core](https://www.npmjs.com/package/@nativescript/core)
  * Core iOS/Android for NativeScript
* [@nativescript/types](https://www.npmjs.com/package/@nativescript/types)
  * Types for both iOS/Android below wrapped up as a convenience. *Most commonly used.*
* @nativescript/types-ios
  * Types for iOS
* @nativescript/types-android
  * Types for Android
* @nativescript/ui-mobile-base
  * UI mobile base native classes used by core
* [@nativescript/webpack](https://www.npmjs.com/package/@nativescript/webpack)
  * Webpack build utilities and configs used by NativeScript apps

## Getting Started and Installation

Our Getting Started Guides are hands-on tutorials that walk you through installing NativeScript and building a real iOS and Android application.

* [Get started with JavaScript](http://docs.nativescript.org/tutorial/chapter-0)
* [Get started with TypeScript and Angular](http://docs.nativescript.org/angular/tutorial/ng-chapter-0)

## Quick Links

- [NativeScript home page](https://nativescript.org)
- [Install NativeScript demo mobile app](https://www.nativescript.org/nativescript-example-application)
- [NativeScript playground](https://play.nativescript.org)
- [NativeScript and Angular](https://play.nativescript.org/?template=play-ng&tutorial=getting-started-ng)
- [@NativeScript on Twitter](http://twitter.com/NativeScript)
- [NativeScript community Slack channel](https://www.nativescript.org/slack-invitation-form)
- [NativeScript on Stack Overflow](http://stackoverflow.com/questions/tagged/nativescript)
- [NativeScript documentation](https://docs.nativescript.org/)
- [NativeScript marketplace](https://market.nativescript.org/)
- [NativeScript roadmap](https://www.nativescript.org/roadmap)

## Other framework source repos

Outside of the source centralized in this repo, the NativeScript framework consists of a number of components, all of which are open source and on GitHub. Here are the major ones:

- **[iOS runtime](https://github.com/NativeScript/ns-v8ios-runtime)**
    [![npm](https://img.shields.io/npm/dm/tns-ios.svg)](https://www.npmjs.com/package/@nativescript/ios) 
    - This repo contains the NativeScript iOS runtime — the code that hosts NativeScript iOS apps, and allows JavaScript code to be executed on iOS devices. The iOS runtime is written in a fun mix of C++, Objective-C, and more.
- **[Android runtime](//github.com/NativeScript/android-runtime)**
    [![npm](https://img.shields.io/npm/dm/tns-android.svg)](https://www.npmjs.com/package/tns-android) 
    - This repo contains the NativeScript Android — the code that hosts NativeScript Android apps, and allows JavaScript code to be executed on Android devices. The Android runtime is written in a fun mix of C++ and Java.
- **[CLI](//github.com/NativeScript/nativescript-cli)**
    [![npm](https://img.shields.io/npm/dm/nativescript.svg)](https://www.npmjs.com/package/nativescript) 
    - This repo contains the NativeScript command-line interface, which lets you create, build, and run apps using the NativeScript framework. The CLI is written in TypeScript.
- **[Docs](//github.com/NativeScript/docs)** [![Docs](https://img.shields.io/badge/Docs-NativeScript-brightgreen)](https://docs.nativescript.org/)
    - This repo contains the NativeScript framework documentation, which is available at <http://docs.nativescript.org/>. The docs are written in Markdown.

In addition to the code that makes up the NativeScript framework itself, we also provide a number of [open-source sample apps](https://www.nativescript.org/app-samples-with-code) that you can reference while building your NativeScript application.

## Contributing

We love PRs, and accept them for all of our repositories — even docs! Please follow our [contribution guide](https://github.com/NativeScript/NativeScript/blob/master/tools/notes/CONTRIBUTING.md) if you want to become part of the project.
