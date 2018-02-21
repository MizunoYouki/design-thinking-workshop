# design-thinking-workshop（デザイン思考ワークショップ）

## 概要

「プログラミング体験」および「デザイン思考による発明体験」のワークショップを開催するための資料です。

### ワークショップ概要
- 目的
  - プログラミングを体験してもらうこと
  - 課題解決志向を持ってもらうこと
- 時間配分
  - 最低でも90分を要します。135分を確保できることが理想です。
  - 前半はプログラミング体験、後半はデザイン思考の手法による発明を行います
    - 135分確保できる場合、プログラミング体験に90分を配分します
    - 90分確保できる場合、プログラミング体験に45分を配分します
    - 発明に45分を配分します

## 対象

ワークショップ受講者は、10才程度以上のプログラミング未経験者を想定しています。

講師を務める人は、コンピュータの専門家である必要はありません。

## 要求

- ワークショップ受講者 2名以上
- ワークショップ講師 1名以上
- ふせん
- ふせんを貼る場所（黒板, ホワイトボード）など
- 画用紙
- 筆記用具
- [アーテック](http://www.artec-kk.co.jp/)の教材(\*)
  - 093861プログラミングスターターセット 信号機B
  - 094761プログラミングモーターセット
  - Studuino Softwareが動作するコンピュータ（PCやタブレットなど）


  \* アーテックの教材がない場合は、[Hour of Code](https://hourofcode.com/jp)を実施します。その場合も適当なコンピュータとインターネット環境を用意してください。

## ワークショップ実施方法

受講者向けに、[テキスト.docx](/テキスト.docx)を配布してください。

講師は[テキスト.md](/テキスト.md)を参照して実施してください。
テキスト.md には、講師向けのヒントがコメントで記されています。

## テキスト編集方法

（差分を管理しやすくするため、Wordファイルを直接編集するのではなく、Markdown形式のファイルからWordファイルを生成しています）

あらかじめ[Pandoc](https://pandoc.org/)をインストールしておいてください。

1. [テキスト.md](/テキスト.md) を編集する
1. コマンドラインやターミナルなどから ` pandoc -s テキスト.md -o テキスト.docx --reference-doc reference.docx` を実行すると、[テキスト.docx](/テキスト.docx)が生成される
1. テキスト.docxを編集する（スタイル自動適用が不完全なため）
    1. 適宜空行を削除する
    1. 適宜改ページする
    1. 5ページあたりにある表の罫線を実線にする
