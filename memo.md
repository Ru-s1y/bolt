# メモ
- header

- nav
HTML の <nav> 要素は、現在の文書内の他の部分や他の文書へのナビゲーションリンクを提供するためのセクションを表します。ナビゲーションセクションの一般的な例としてメニュー、目次、索引などがあります。
nav > ul > li

- main
    -> article -> section

- article
  sectionよりも独立性の高い構成の場合使用する。

- section
  articleよりも独立していない場合に使い、テーマごとに使用する。

- figure
  キャプション付きの画像。
```
  <figure>
    <img src="****.jpg" alt="xxx">
    <figcaption>#######</figcaption>
  </figure>
```
- footer

header > nav > ul > li
  |
main > article > section > div/figure
  |
footer