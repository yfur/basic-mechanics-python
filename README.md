# basic-mechanics-python

This repository contains python programs for computing basic mechanics in physics.

## About

This is private study repository. The document in this repository is mainly in Japanese.

## Environment
Bulit on March 3, 2017 through [Anaconda](https://www.continuum.io).

* Python 3.6.0 :: Anaconda c ustom (x86_64)
  * numpy (1.11.3)
  * sympy (1.0)
  * scipy (0.18.1)
  * matplotlib (2.0.0)

As is well known, Python series 2.\* and 3.\* are quite different and running a code in python series 2.\* should occur an error.

Concerned with [Matplotlib](http://matplotlib.org/index.html), big update from 1.\* to 2.\* was done on January 17, 2017, which makes a differences of appearance about graphs and animations, though it is not a big matter in this project.


# Python による機械力学の基本

本リポジトリは機械力学の基本に関する Python プログラムを含んでいます．


## このレポジトリについて

個人的な機械力学の勉強用のレポジトリです．言葉遣いや数式への理解は未熟ではありますが，文章を書く力をつける練習のため色々書いてます．


## 環境

[Anaconda](https://www.continuum.io) で2017年3月3日に構築した環境です．

* Python 3.6.0 :: Anaconda custom (x86_64)
  * numpy (1.11.3)
  * sympy (1.0)
  * scipy (0.18.1)
  * matplotlib (2.0.0)

よく知られているように，Python の2系と3系は大きく異なっていますので，本レポジトリのプログラムは2系ではおおよそコンパイルできません．

[Matplotlib](http://matplotlib.org/index.html) に関しては，2017年1月17日に行われた1系から2系への大型アップデートにより，グラフやアニメーションの外観が変化しています．しかし，本レポジトリで扱う内容に関しては，これはあまり大きな問題ではないでしょう．

## 内容

* [0_quickstart](https://github.com/yfur/basic-mechanics-python/blob/master/0_quickstart/0_quickstart.ipynb): 単振り子の運動のシミュレーション．最低限の簡単なプログラム．
* [1_modeling](https://github.com/yfur/basic-mechanics-python/blob/master/1_modeling/1_modeling.ipynb): Lagrange の運動方程式を　Python で計算する方法など．
* [2_numerical_solver](https://github.com/yfur/basic-mechanics-python/blob/master/2_numerical_solver/2_numerical_solver.ipynb): 常微分方程式の数値計算法について．
