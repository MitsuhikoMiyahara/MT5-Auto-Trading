# FX-Auto-Trading
I am independently researching automated forex trading.

# 自動売買プログラム: Bollinger_BTCJPY & Bollinger_USDJPY

このリポジトリには、`Bollinger_BTCJPY` と `Bollinger_USDJPY` という2つの自動売買プログラムが含まれています。どちらもボリンジャーバンドを参考にして、BTCJPY または USDJPY の取引を自動で行います。

## 概要

- **Bollinger_BTCJPY**:
  - BTCJPYの1分足データを使用して、ボリンジャーバンドを計算し、自動で取引を行います。価格がボリンジャーバンドの上限を超えた場合は売り、下限を下回った場合は買いの注文を出します。

- **Bollinger_USDJPY**:
  - USDJPYの1分足データを使用して、ボリンジャーバンドを計算し、自動で取引を行います。BTCJPYと同様に、上限を超えた場合は売り、下限を下回った場合は買いの注文を出します。

両方のプログラムはMetaTrader5 (MT5) を使用し、Pythonで書かれています。ボリンジャーバンドを使用した取引戦略に基づいて、リアルタイムで自動売買を行います。