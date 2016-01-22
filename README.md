# DevDocsDesktop
This is a desktop app wrapper for [Thibaut](https://github.com/Thibaut/)'s excellent API documentation site [DevDocs.io](http://devdocs.io).

Built using [Electron](http://electron.atom.io/) and packaged with [Electron-Packager](https://github.com/maxogden/electron-packager).

## How to Build Locally

```
git clone https://github.com/lexander/DevDocsDesktop.git
cd DevDocsDesktop
npm i
npm run-script buildOSX
```

This will create a directory named DevDocsDesktop-darwin-x64, inside that directory there will be an OS X executable named DevDocsDesktop and all of the licenses for included open source code in the Chromium project.

Enjoy running [DevDocs.io](http://devdocs.io) in a desktop app!
