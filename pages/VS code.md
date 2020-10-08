---
title: VS code
---

## 小説執筆用のカスタマイズ　
### テキストファイルの[[文字コード]]の種類を自動判別するようにした。[[September 13th, 2020]]
#### ^^((bdd827a2-9d4c-49fe-8863-2a55cdb7f7bc))^^

### ミニマップを非表示にした。

### 指定した文字数で折り返すように設定。
#### 例によって、文字数は適当とする。枚数を把握するためには、20とか40というキリが良い数字がいいのだけれど、なんか微妙にずれてしまってうまくいかない。日本語入力にそこまで特化していないせいかね。

### 文字数をリアルタイムでカウントできるように設定。
#### [[CharacterCount]]という拡張機能。

### [[VS code]]で[[文字コード]]の種類を自動判別する方法を調べた。
:PROPERTIES:
:CUSTOM_ID:bdd827a2-9d4c-49fe-8863-2a55cdb7f7bc
:END:
#### https://www.atmarkit.co.jp/ait/articles/1806/01/news051.html　を参考に。

#### ![](https://firebasestorage.googleapis.com/v0/b/firescript-577a2.appspot.com/o/imgs%2Fapp%2FSetaKs-Brain%2FskOp63jjP7.png?alt=media&token=cbb1c893-0d85-4092-89fa-565b94ac950f)

### [[テキスト校正君]]という拡張機能を入れた。

### [[git]]と自動に連携していた。これでバージョン管理が簡単にできる。

## 機能についてメモ
### 文字数カウントについて
#### https://scrapbox.io/rashitamemo/Roam_Research%E3%81%AEcharacter_count

#### {{{character-count null}}} 
##### これを使うことで、この拡張機能のあるレベルから下の文字数を数えてくれるらしい。

##### ただし、この機能の文字自体も数えてしまうという何とも言いづらい特徴が。
