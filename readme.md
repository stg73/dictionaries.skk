## 概要

日本語入力方式SKKのための辞書群

## 仕様

[specification.md](specification.md)

### 動作環境

動作確認は [CorvusSKK](https://github.com/nathancorvussolis/corvusskk) で行なっている

## 各辞書の説明

- [bamboo-copter](bamboo-copter.skk)

  竹とんぼ

- [horticulture](horticulture.skk)

  園芸

- [idiom](idiom.skk)

  慣用句

  文脈を考慮した変換ができないSKKの欠点を補うことができる

- [box-drawing-character](box-drawing-character.skk)

  罫線素片

- [lisp](lisp.skk)

  CorvusSKK 用のプログラム実行変換

- [slang](slang.skk)

  俗語

- [succulents](succulents)

  多肉植物に関する辞書群

  - `succulents/term.skk` 以外

    https://supersabotentime.com/12578/ の [多肉植物ユーザー辞書A](https://supersabotentime.com/wp/wp-content/uploads/2022/02/2bbe09974e83aa8860c20437bee1b7d8.txt) をもとに作成

    正確性はまだ不十分

  - [genus-name](succulents/genus-name.skk)

    属名

  - [japanese-name](succulents/japanese-name.skk)

    和名

  - [scientific-name](succulents/scientific-name.skk)

    学名

  - [term](succulents/term.skk)

    用語

- [website](website.skk)

  ウェブサイト

- [wrong](wrong.skk)

  "はこびる"などの誤りを補正し 正しい形を示してくれる辞書 たとえば `はこびr /蔓延;[誤]はびこr/`

- [ゆる学徒系](ゆる学徒系)

  ゆる学徒系ラジオに関する辞書群

  - [name](ゆる学徒系/name.skk)

    パーソナリティの名前

  - [youtube-channel](ゆる学徒系/youtube-channel.skk)

    チャンネル名

- [ボカロ](ボカロ)

  広義のボカロに関する辞書群

  - [character](ボカロ/character.skk)

    キャラクター

  - [song](ボカロ/song.skk)

    曲

  - [ボカロP](ボカロ/ボカロP.skk)

    ボカロP
