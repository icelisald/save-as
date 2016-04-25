# save-as

[![NPM](https://nodei.co/npm/save-as.png?stars=true&downloads=true)](https://nodei.co/npm/save-as/)


**FileSaver.js window.saveAs API functionality rewritten for es6**


## Install

`npm i -S save-as`


## Usage

```js
import saveAs from 'save-as'

let blob = new Blob(['Hello, world!'], { type: 'text/plain;charset=utf-8' })
saveAs(blob, 'hello world.txt')
```
