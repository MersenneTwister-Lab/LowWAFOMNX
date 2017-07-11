R package: Low WAFOM Sequences based on Niederreiter-Xing sequences
===================================================================

Low WAFOM Sequences based on Niederreiter-Xing sequences
are searched using an algorithm described in Shinsuke Mori's
master thesis.

##Caution
Currently, this project is very experimental.

##Link
- [Japanese Version](index-ja.html)
- [vignettes](lowWAFOMNX.html)
- [GitHub Page](https://github.com/MersenneTwister-Lab/LowWAFOMNX/)
- [This Page](https://mersennetwister-lab.github.io/LowWAFOMNX/)

##Install
You can install the packeage in R like this:

```
install.packages('devtools')
library('devtools')
install_github("MersenneTwister-Lab/LowWAFOMNX")
```

##Recovery
If fail, try old good style, download and install.

- Source Package: [LowWAFOMNX_1.0.tar.gz](LowWAFOMNX_1.0.tar.gz)
- OS X Binary Package: [LowWAFOMNX_1.0.tgz](LowWAFOMNX_1.0.tgz)
- Windows Binary Package: [LowWAFOMNX_1.0.zip](LowWAFOMNX_1.0.zip)

##Reference
* Shinsuke Mori,
  "Suuchi Sekibun no tameno QMC Ten Shuugou no Sekkei, Tansaku,
  oyobi sono Yuukousei",
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
