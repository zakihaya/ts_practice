## 実行内容

package.json初期化

```
npm init --yes
```

package.json更新

```
-  "main": "index.js",
+  "main": "index.js",
+  "type": "module",
```

typescriptインストール

```
npm install --save-dev typescript @types/node 
```

tsconfig.jsonの準備

```
npx tsc --init
```

src/index.tsファイル追加

コンパイル

```
npx tsc
```

作成されたファイルを実行

```
node disc/index.js
```

ファイルの変更を検知してコンパイルを実行する

```
npx tsc --watch
```
