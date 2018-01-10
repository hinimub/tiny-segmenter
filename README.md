tiny-segmenter
==============

Mirror of [TinySegmenter](http://chasen.org/~taku/software/TinySegmenter/), the super compact Japanese tokenizer in Javascript.

For publishing it as an Google Apps Script Library.  
This repository is forked from https://github.com/leungwensen/tiny-segmenter.

## Setup
1. Select "Resources" > "Libraries..." in the Google Apps Script
editor.
2. Enter the project key `1I4lz41EgMqEpHuQK-TCec4J8gSUqWwTMBon2kYFRY7QEVC9r3NuPmc0N` in the "Find a Library" field, and choose "Select". 
3. Choose a version in the dropdown box, and choose TinySegmenter as the
identifier. 
4. Click the "Save" button.

## Usage

```javascript
// sample code from http://chasen.org/~taku/software/TinySegmenter/
var segmenter = new TinySegmenter.TinySegmenter(); // インスタンス生成
var segs = segmenter.segment("私の名前は中野です"); // 単語の配列が返る
Logger.log(segs.join(" | ")); // 表示
```
