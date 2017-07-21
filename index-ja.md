R package: Sobol sequence に基づくLow WAFOM Sequence
==================================================

森信輔による修士論文「数値積分のためのQMC点集合の設計,探索およびその有効性」において
述べられた方法で探索された「Sobol sequence に基づくLow WAFOM Sequence」を
Rに移植したもの。

##お知らせ
このパッケージはCRANに登録されました。

##リンク

- [英語版](index.html)
- [ビニエット](lowWAFOMNX-ja.html)
- [GitHub Page](https://github.com/MersenneTwister-Lab/LowWAFOMNX/)
- [このページ](https://mersennetwister-lab.github.io/LowWAFOMNX/)

##インストール
リリース版はCRANからインストールできます。

### 開発版のインストール
まず、

- Windows利用者は[Rtools](https://cran.r-project.org/bin/windows/Rtools/)を
インストールしておく必要がある。
- Mac 利用者はXcodeをインストールしておく必要があるかもしれない。

その後、以下のようにしてこのパッケージをRにインストールすることができる。

```
install.packages('devtools')
library('devtools')
install_github('MersenneTwister-Lab/LowWAFOMNX', ref='develop')
```

##ダウンロード
###リリース版

- Source Package: [LowWAFOMNX_1.0.tar.gz](LowWAFOMNX_1.0.tar.gz)
- OS X Binary Package: [LowWAFOMNX_1.0.tgz](LowWAFOMNX_1.0.tgz)
- Windows Binary Package: [LowWAFOMNX_1.0.zip](LowWAFOMNX_1.0.zip)

###開発版

- Source Package: [LowWAFOMNX_1.0.1.tar.gz](LowWAFOMNX_1.0.1.tar.gz)
- OS X Binary Package: [LowWAFOMNX_1.0.1.tgz](LowWAFOMNX_1.0.1.tgz)
- Windows Binary Package: [LowWAFOMNX_1.0.1.zip](LowWAFOMNX_1.0.1.zip)
- [vignettes](v1_0_1/lowWAFOMNX-ja.html)

##参照
* 森 信輔,
  "数値積分のための QMC 点集合の設計, 探索およびその有効性",
  Master's Thesis, 2017.
* Ryuichi Ohori,
  "Efficient Quasi Monte Carlo Integration by Adjusting the
  Derivation-sensitivity Parameter of Walsh Figure of Merit",
  Master's Thesis, 2015.
* S. Harase and R. Ohori,
  "A search for extensible low-WAFOM point sets",
  arXiv preprint, arXiv:1309.7828, (2013),
  https://arxiv.org/abs/1309.7828.
* M. Matsumoto and R. Ohori,
  "Walsh Figure of Merit for Digital Nets: An Easy Measure
  for Higher Order Convergent QMC",
  Springer International Publishing, Cham, 2016, pp. 143-160.
* M. Matsumoto, M. Saito, and K. Matoba,
  "A computable figure of merit for quasi-Monte Carlo point sets",
  Mathematics of Computation, 83 (2014), pp. 1233-1250.
* G. Pirsic,
  "A software implementation of Niederreiter-Xing sequences",
  in Monte Carlo and Quasi-Monte Carlo Methods 2000,
  Springer, 2002, pp. 434-445.
  https://sites.google.com/site/isabelpirsic/nxlegacy.
* C. P. Xing and H. Niederreiter,
  "A construction of low-discrepancy sequences using global
  function fields",
  ACTA ARITHMETICA, 73 (1995), pp. 87-102.
