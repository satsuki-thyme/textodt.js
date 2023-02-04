# textodt.js
テキストファイルを odt 形式に変換する JavaScript のライブラリです。

## 目次
* textodt.js  
  ライブラリ本体。
* textodt.min.js  
  ライブラリ本体。圧縮版。
* sample.html  
  使い方のサンプル。
* textodt.html  
  応用した使い方のサンプル。

## 説明
* テキストファイルを odt 形式にい変換します
* ウェブ小説のルビ記法を解釈して odt のルビに変換します
* 第 2 引数にファイル名を与えると生成されるファイル名がそれになります。拡張子を odt と指定してください
* HTML でスクリプトを読み込む際には下のように charset="utf16" をしていしてください  
  `<script src="..." charset="utf-16">`

## 動作
* odt のマークアップを行い odt に必要なファイルを付加して圧縮して odt ファイルにします
* 外部のライブラリとして [JSZip](https://stuk.github.io/jszip/) を利用しています
