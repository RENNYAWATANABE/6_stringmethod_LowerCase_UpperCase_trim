# String メソッドのテスト

このプロジェクトは、JavaScript の `String` メソッドである `toUpperCase()`、`toLowerCase()`、および `trim()` の基本的な使い方をテスト・確認するための簡単なスクリプトです。

## 内容

### 1. `toUpperCase()` メソッドのテスト

```javascript
let hello = "hello world!!";
console.log(hello);                // 元の文字列を出力
console.log(hello.toUpperCase()); // 大文字に変換して出力
```

**目的**: 小文字の文字列をすべて大文字に変換する方法を確認します。

---

### 2. `trim()` + `toLowerCase()` メソッドのテスト

```javascript
let test = "    TEST XXXXXX     ";
console.log(test);                            // 空白を含む元の文字列を出力
console.log(test.trim().toLowerCase());       // 空白を除去し、小文字に変換して出力
```

**目的**:  
- `trim()` を使って文字列の前後の空白を削除する方法を確認します。  
- `toLowerCase()` を使って文字列を小文字に変換する方法を確認します。

---

### 3. 練習１

このセクションは今後の練習用スペースとして用意されています。必要に応じてコードを追加してください。

---

## 実行方法

1. 任意の JavaScript 実行環境（例: ブラウザの開発者ツール、Node.js）でファイルを開きます。
2. コンソールに出力される結果を確認します。
