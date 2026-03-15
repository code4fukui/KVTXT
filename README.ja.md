# KVTXT

キーと値のテキストデータ形式。キー名はコロンで表現し、コロン後にスペースがなければ、その後のテキストデータが値となります。

## デモ

なし

## 機能

- キー-値形式のテキストデータの解析
- 複数行の値に対応

## 必要環境

なし

## 使い方

```js
import { KVTXT } from "https://code4fukui.github.io/KVTXT/KVTXT.js";

const data = KVTXT.decode("key1: value1");
console.log(data);
```

## ライセンス

MIT License