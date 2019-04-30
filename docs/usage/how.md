name:   inverse
layout: true
class:  center, middle, inverse
---
# **スライド.md**の書き方

---
layout: false
## スライドのmarkdown記法の注意点

1. github.comのmarkdown記法で書くだけですが、 
1. 相違点が少しあります
    - スライドページの切れ目は --- です
    - 先頭に github.io への指示を書きまする name: ...
    - 表紙(ページ1)は layout: true、ページ2からは layout: false
    - (スライド固有の問題ではないですが)
      github.ioではgithub.comの絵文字が使えない…

---
## スライド表示のカスタマイズ

remark.js の設計思想はシンプルで、次のような使い方だそうです
- remakr.js はスライド操作を提供のみ
- レイアウトとかは、各自、CSS で調整


---
## 参考文献

[remark.js](https://remarkjs.com)


