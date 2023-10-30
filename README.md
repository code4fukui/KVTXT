# KVTXT
 
- キー名はコロンで表現
- コロン後にスペースがなければ、その後のテキストデータが値となります

## example

```
key1: value1
key2:
value2-1
value2-2
key3: value3
```

## Usage

```js
import { KVTXT } from "https://code4fukui.github.io/KVTXT/KVTXT.js";

const data = KVTXT.decode("key1: value1");
console.log(data);
```
