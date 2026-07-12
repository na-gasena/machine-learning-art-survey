---
layout: default
title: 音楽、パフォーマンス、インタラクティブ機械学習
permalink: /ja/topics/music-performance-interactive-ml/
---

# 音楽、パフォーマンス、インタラクティブ機械学習

## 位置づけ

音楽・パフォーマンスでは、機械学習は完成品を生成する装置であるだけでなく、演奏中に応答する楽器、身体ジェスチャを写像するインターフェース、訓練プロセスそのものを含む創作環境になります。

## Item Notes

## Wekinator

- Type: software
- Creator / Author: Rebecca Fiebrink
- Year: 2009
- Context / Venue: Real-time interactive machine learning for artists and musicians
- Links: https://doc.gold.ac.uk/~mas01rf/Wekinator/
- Category: 音楽、パフォーマンス、インタラクティブ機械学習
- Importance: Important
- Confidence: High

### Why It Matters

Wekinatorは、プログラムを書く代わりに実演で機械学習システムを訓練できるようにした点で重要です。音楽、身体、センサー、ゲーム、映像の間に柔軟な写像を作れます。

### Description

ユーザーが入力例と出力例を示し、システムがその関係を学習します。OSCを介してProcessing、openFrameworks、Unity、Abletonなどと接続できます。

### Method / Medium / Approach

インタラクティブ機械学習、教師あり学習、リアルタイム入出力、創作ツール。

### Historical or Research Context

NIMEやHCI、音楽情報処理、クリエイティブコーディングと関係します。

### Limitations / Open Questions

モデル性能よりも、訓練のしやすさ、反復、演奏者の理解可能性が重要になります。

### Related Items

The Machine Learning Algorithm as Creative Musical Tool、NIME。

## Magenta and NSynth

- Type: project / dataset / software
- Creator / Author: Google Magenta, Google Brain, DeepMind
- Year: 2016-2017
- Context / Venue: Creative ML for music and art
- Links: https://magenta.tensorflow.org/ / https://magenta.tensorflow.org/nsynth
- Category: 音楽、パフォーマンス、インタラクティブ機械学習
- Importance: Important
- Confidence: High

### Why It Matters

Magentaは、機械学習を音楽制作の実験的な道具として広く公開しました。NSynthは音色の潜在空間を扱うことで、楽器設計と機械学習を結びつけました。

### Description

NSynthは、約30万の注釈付き単音サンプルとWaveNet系オートエンコーダを使い、楽器音の特徴を学習します。

### Method / Medium / Approach

ニューラル音声合成、データセット、潜在表現、DAWプラグイン、オープンソース。

### Historical or Research Context

音楽生成、音色合成、機械学習を使う作曲支援の重要な入口です。

### Limitations / Open Questions

単音データセットは多声・長期構造・演奏文脈を十分には扱えません。

### Related Items

Wekinator、Holly+、PROTO/Spawn。

## The Machine Learning Algorithm as Creative Musical Tool

- Type: paper
- Creator / Author: Rebecca Fiebrink, Baptiste Caramiaux
- Year: 2016
- Context / Venue: Music, ML, HCI
- Links: https://arxiv.org/abs/1611.00379
- Category: 音楽、パフォーマンス、インタラクティブ機械学習
- Importance: Important
- Confidence: High

### Why It Matters

この論文は、機械学習アルゴリズムを自動作曲器ではなく、人間とコンピュータのインターフェースとして捉えます。

### Description

音楽家が自分のスタイルや例外をシステムに教え、モデルの反応から新しい可能性を探るという人間中心の見方を提示します。

### Method / Medium / Approach

HCI、音楽表現、インタラクティブ機械学習の理論整理。

### Historical or Research Context

Wekinatorの思想的背景を理解するための重要文献です。

### Limitations / Open Questions

最新の大規模生成音楽モデルについては、別途追跡が必要です。

### Related Items

Wekinator、Magenta、NIME。
