---
layout: default
title: 制作ツール、教育、プラットフォーム
permalink: /ja/topics/creative-tools-platforms/
---

# 制作ツール、教育、プラットフォーム

## 位置づけ

機械学習と創作活動の関係は、論文や美術館作品だけでは説明できません。多くの作家は、公開ライブラリ、教育用ツール、商用プラットフォーム、DAWプラグイン、ブラウザ上の実験環境を通じて機械学習に触れています。このカテゴリでは、制作の入口を作ったツールと、それが創作コミュニティをどう変えたかを扱います。

## 主要な流れ

Wekinatorのようなインタラクティブ機械学習は、作家が例示によってモデルを訓練する方法を開きました。ml5.jsやTeachable Machineは、コードや数学の障壁を下げ、教育やワークショップでAIを扱いやすくしました。MagentaやNSynthは音楽制作の実験環境を作り、Runwayは生成動画とプロダクションワークフローをつなぎました。

## Item Notes

## ml5.js

- Type: software
- Creator / Author: NYU ITP/IMA, NYU Shanghai IMA, ml5.js community
- Year: 2018-
- Context / Venue: Browser-based creative machine learning library
- Links: https://ml5js.org/
- Category: 制作ツール、教育、プラットフォーム
- Importance: Important
- Confidence: High

### Why It Matters

ml5.jsは、機械学習を「専門家だけのモデル開発」から「ブラウザ上で試せる創作素材」へ近づけました。p5.jsやクリエイティブコーディングの文化と相性がよく、授業、ワークショップ、インタラクティブ作品で使われます。

### Description

ml5.jsはTensorFlow.jsの上に構築され、身体姿勢、手、顔、画像分類、音分類、ニューラルネットワーク訓練などの機能を扱いやすいAPIで提供します。

### Method / Medium / Approach

ブラウザ上のJavaScript、TensorFlow.js、事前学習モデル、学習可能なニューラルネットワーク。

### Historical or Research Context

Processing、p5.js、creative coding、教育用AIリテラシーの流れに接続します。

### Limitations / Open Questions

簡単に使えることは重要ですが、モデルやデータセットの偏り、誤認識、プライバシー、アクセシビリティの説明も必要です。

### Related Items

Teachable Machine、Wekinator、ml4a。

## Teachable Machine

- Type: software
- Creator / Author: Google
- Year: 2017-
- Context / Venue: No-code ML training/prototyping tool
- Links: https://teachablemachine.withgoogle.com/
- Category: 制作ツール、教育、プラットフォーム
- Importance: Important
- Confidence: High

### Why It Matters

Teachable Machineは、画像、音声、ポーズの分類器をコードなしで作れるため、学校教育、ワークショップ、プロトタイピング、アート実験に広く使われます。

### Description

ブラウザ上でサンプルを集め、クラスを定義し、簡易モデルを訓練して、Webや外部ツールへ組み込めます。

### Method / Medium / Approach

ノーコード学習、画像/音声/ポーズ分類、ブラウザベースのインターフェース。

### Historical or Research Context

「機械に教える」体験を一般化し、AIリテラシーを創作活動に接続します。

### Limitations / Open Questions

モデルがなぜ間違うのか、学習データが誰を代表しているのか、分類タスクにできない創作的問題をどう扱うかが課題です。

### Related Items

ml5.js、Wekinator、Machine Teaching。

## Machine Learning for Artists

- Type: project / educational archive
- Creator / Author: Gene Kogan and contributors
- Year: 2016-
- Context / Venue: Free educational resources
- Links: https://ml4a.github.io/
- Category: 制作ツール、教育、プラットフォーム
- Importance: Important
- Confidence: High

### Why It Matters

ml4aは、深層学習がアーティストの制作に入り始めた時期に、コード、講義、デモ、概念説明をまとめた重要な教育資源でした。

### Description

オンラインブック、ガイド、インタラクティブデモ、講義動画などからなるリソース集です。現在のサイトはアーカイブとして残されています。

### Method / Medium / Approach

教育資料、サンプルコード、デモ、コミュニティ学習。

### Historical or Research Context

DeepDream、スタイル変換、GANの時代に、作家が機械学習を学ぶための入口になりました。

### Limitations / Open Questions

一部の技術情報は古くなっているため、現行モデルやライセンス、倫理的論点と組み合わせて読む必要があります。

### Related Items

ml5.js、Magenta、Runway。

## Runway

- Type: software / platform
- Creator / Author: Runway AI, Inc.
- Year: 2018-
- Context / Venue: Generative video and creative AI production platform
- Links: https://runwayml.com/
- Category: 制作ツール、教育、プラットフォーム
- Importance: Important
- Confidence: High

### Why It Matters

Runwayは、機械学習を映像制作、広告、映画、ポストプロダクションの実務へ接続した代表的プラットフォームです。AIアートが作品展示だけでなく、産業的ワークフローへ組み込まれる過程を示します。

### Description

初期には非エンジニア向けの機械学習モデル実行環境として注目され、その後は生成動画やワールドモデルを中心に展開しています。

### Method / Medium / Approach

生成動画、画像/動画編集、モデルAPI、クリエイティブ制作ワークフロー。

### Historical or Research Context

Stable Diffusionの共同開発文脈や、AI Film Festivalなどの制度形成とも関係します。

### Limitations / Open Questions

商用プラットフォームでは、訓練データ、ライセンス、制作労働、映像産業への影響が不透明になりやすいです。

### Related Items

Stable Diffusion、DALL-E、AI Film Festival、C2PA。

## 境界領域

制作ツールは、作家を支援する一方で、商業制作の自動化、労働代替、出力の均質化、権利不明な素材の再利用にもつながります。ツールの評価では、生成品質だけでなく、誰が使えるのか、誰のデータで動くのか、誰が利益を得るのかを問う必要があります。
