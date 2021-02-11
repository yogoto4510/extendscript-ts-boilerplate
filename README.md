# extendscript-ts-boilerplate

## 概要

VSCode & Typescript での ExtendScript 開発環境のオレオレ流テンプレ

## 特徴

- ESlint & Prettier 環境（必要かはさておき）
- ts ファイルの保存時に自動 Fix & Format（必要かはさておき）

## 事前準備

1. Node.js, Yarn, Git を用意
2. VSCode で EditorConfig と ESlint と Prettier の拡張機能を導入

## 導入

### GitHub にユーザー登録している場合

ログインして`Use this template`からリポジトリを作成

```bash
$ git clone [あなたのリポジトリ]
$ cd ./[あなたのリポジトリ名]
$ yarn install
```

### ユーザー登録していない場合

```bash
$ git clone https://github.com/yogoto4510/extendscript-ts-boilerplate.git
$ cd ./extendscript-ts-boilerplate
$ yarn install
```

## 使い方

```bash
// トランスパイル
$ yarn tsc
```

dist/\*.js を開いて「デバックの開始（F5）」
