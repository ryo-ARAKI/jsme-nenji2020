# jsme-nenji2020

日本機械学会 2020年度年次大会 講演原稿の非公式LaTeXテンプレート

公式のWordテンプレートは[このページ](https://jsmempd.com/conference/jsme_annual/2020/manuscript/)より入手可能です．

## 未修正の問題

- geometryが微妙に異なるのを修正する．
  > 本文の文字数は, 1 ページ当たり, 50 文字× 46 行× 1 段組で 2300 字とする.
- `[No.20-1] 日本機械学会 2020 年度年次大会 講演論文集 〔2020.9.13-16,名古屋〕` というフッターを全ページに追加する
- 節タイトルなどの太字がMS-Gothicと異なるのをどうにかする．
- 表のタイトルにおける `Table 1:` などからコロンを除去する．
- 表において `×10^3` などの要素のみを右揃えにする．
- `\supercite{a, b}` のように連続して文献を引用するとき，出力をカンマで区切らない．
