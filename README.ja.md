# KVTXT

シンプルなキー・バリュー型のテキストフォーマットです。

## 特徴
- キーはコロンで表現されます
- コロンの後にスペースがない場合、続くテキストが値になります
- 複数行の値をサポートしています

## 使い方

```js
import { KVTXT } from "https://code4fukui.github.io/KVTXT/KVTXT.js";

const data = KVTXT.decode("key1: value1");
console.log(data);
```

## ライセンス
MIT License — 詳細は [LICENSE](LICENSE) を参照してください。
