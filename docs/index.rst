.. Pynquino documentation master file, created by
   sphinx-quickstart on Sun Jun 17 13:19:24 2018.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

=====================
Pynquinoプロジェクトとは
=====================


.. toctree::
  :hidden:

  getting_started
  blockly
  developers
  showcases
  development_plan


---------------------
課題：PYNQとArduinoの統合
---------------------
本プロジェクトはPYNQプロジェクトでみられた以下の課題の解決に着目する。

1) PYNQプロジェクトはARMプロセッサ上のLinux OS、MicroBlazeマイクロコントローラ上のベアメタルアプリケーション、FPGAファブリック上のハードウェアアクセラレータを統合的にPythonで開発できる
2) 一方でPYNQ-MicroBlazeはArduino APIに対応しておらず、OSとの通信にコードを書き換える必要があるため、Arduinoプロジェクトのソースコードをそのまま使うことはできない
3) Jupyter notebookでの開発は敷居を下げたが、ソフトウェアエンジニアでないユーザがPythonを使いこなすのは依然として困難が伴う

---------------------
目標：本プロジェクトが提供するもの
---------------------
PynquinoプロジェクトはArduinoとPYNQの統合および開発の効率を上げるために以下のソフトウェアを開発する。

1) Pynquinoコンパイラ: ArduinoのソースコードをPYNQ-Microblazeにポーティングする
2) Blocklyエディタ: Jupyter notebookのラッパーとしてのビジュアルプログラミング環境

---------------------
アプリケーション
---------------------
1) 異種のロボットおよびセンサを統合する
2) 画像処理及び機械学習計算のアクセラレーション

