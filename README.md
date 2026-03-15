# KVTXT

> 日本語のREADMEはこちらです: [README.ja.md](README.ja.md)

A simple key-value text format.

## Features
- Keys are expressed with a colon
- If there is no space after the colon, the following text is the value
- Supports multi-line values

## Usage

```js
import { KVTXT } from "https://code4fukui.github.io/KVTXT/KVTXT.js";

const data = KVTXT.decode("key1: value1");
console.log(data);
```

## License
MIT License