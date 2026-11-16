# 日本語形態素解析用 辞書データ（kuromoji.js 辞書ファイル）

本リポジトリでは、JavaScript向け形態素解析エンジン **kuromoji.js** で利用される辞書データ（`.dat.gz` 形式・全12ファイル）をホスティング・配布しています。

## 収録ファイル一覧（`dict/` フォルダ内）

* `base.dat.gz`
* `cc.dat.gz`
* `check.dat.gz`
* `tid.dat.gz`
* `tid_map.dat.gz`
* `tid_pos.dat.gz`
* `unk.dat.gz`
* `unk_char.dat.gz`
* `unk_compat.dat.gz`
* `unk_invoke.dat.gz`
* `unk_map.dat.gz`
* `unk_pos.dat.gz`

## ライセンス・著作権表示（License & Attribution）

本リポジトリで配布している辞書データは、**kuromoji.js**（[https://github.com/takuyaa/kuromoji.js](https://github.com/takuyaa/kuromoji.js)）に含まれる辞書ファイルをそのまま（無改変で）再配布しているものです。

* **Copyright (c) 2014 Takuya Asano**
* **Licensed under the Apache License, Version 2.0**

本データの利用・再配布にあたっては、同封の `LICENSE-2.0.txt` および `NOTICE.md` ファイルの条件が適用されます。ライセンスの全文は同梱の `LICENSE-2.0.txt` ファイル、および元となる辞書（MeCab / IPAdic）の帰属表示は `NOTICE.md` ファイルをご確認ください。

## 免責事項

本データは Apache License 2.0 第7条および第8条に基づき「現状有姿（AS IS）」で提供されており、動作や解析結果の正確性についていかなる保証も行いません。