---
layout: default
title: ニューラル画像生成
permalink: /ja/topics/neural-image-generation/
---

# ニューラル画像生成

## 位置づけ

2010年代以降、深層学習は画像生成を大きく変えました。DeepDream、ニューラルスタイル変換、GAN、CAN、ArtGAN、拡散モデル、DALL-E、Stable Diffusionは、研究成果であると同時に創作のインターフェース、流通環境、論争の焦点でもあります。

## Item Notes

## DeepDream / Inceptionism

- Type: software / method
- Creator / Author: Alexander Mordvintsev, Christopher Olah, Mike Tyka, Google Research
- Year: 2015
- Context / Venue: Google Research
- Links: https://research.googleblog.com/2015/06/inceptionism-going-deeper-into-neural.html
- Category: ニューラル画像生成
- Importance: Foundational
- Confidence: High

### Why It Matters

DeepDreamは、ニューラルネットワークの内部表現を可視化する手法が、そのまま新しい視覚文化として流通しうることを示しました。

### Description

画像認識ネットワークが検出した特徴を増幅することで、動物や建築のような形が反復的に浮かび上がる幻視的画像を生みます。

### Method / Medium / Approach

CNNの特徴可視化、勾配上昇、画像変換。

### Historical or Research Context

解釈可能性研究とAIアートの境界をまたぐ事例です。

### Limitations / Open Questions

作品としての評価は、技術デモ、インターネット文化、作家による使用の区別が必要です。

### Related Items

ニューラルスタイル変換、DALL-E、Stable Diffusion。

## A Neural Algorithm of Artistic Style

- Type: paper
- Creator / Author: Leon A. Gatys, Alexander S. Ecker, Matthias Bethge
- Year: 2015
- Context / Venue: arXiv / CVPR-era neural style transfer research
- Links: https://arxiv.org/abs/1508.06576
- Category: ニューラル画像生成
- Importance: Foundational
- Confidence: High

### Why It Matters

画像の「内容」と「様式」をニューラル表現として分離・再結合する考え方を広く普及させました。

### Description

VGG系CNNの中間特徴とGram行列を使い、写真と絵画様式を合成する画像を生成します。

### Method / Medium / Approach

畳み込みニューラルネットワーク、特徴表現、最適化。

### Historical or Research Context

スマートフォンアプリやウェブサービスを通じて、AI画像処理が一般ユーザーに拡散する契機になりました。

### Limitations / Open Questions

「様式」を統計的特徴として扱うことが、美術史的・文化的な様式理解と同じではない点に注意が必要です。

### Related Items

DeepDream、WikiArt、CAN。

## GAN / CAN / ArtGAN

- Type: papers / methods
- Creator / Author: Ian Goodfellow et al.; Ahmed Elgammal et al.; Wei Ren Tan et al.
- Year: 2014-2017
- Context / Venue: Generative model research and artwork synthesis
- Links: https://arxiv.org/abs/1406.2661 / https://arxiv.org/abs/1706.07068 / https://arxiv.org/abs/1702.03410
- Category: ニューラル画像生成
- Importance: Foundational / Important
- Confidence: High

### Why It Matters

GANは、2010年代後半のAIアートを視覚的にも言説的にも支えました。CANは、既存様式からの逸脱を創造性の条件として組み込み、ArtGANは美術画像生成に特化しました。

### Description

GANは生成器と識別器の競合でデータ分布を学習します。CANは芸術分布に留まりつつ既存様式から逸脱するよう設計され、ArtGANは美術画像の条件付き生成を扱いました。

### Method / Medium / Approach

敵対的学習、様式分類、WikiArt系データ、画像生成。

### Historical or Research Context

Edmond de Belamy、Mario Klingemann、Anna Ridlerなどの実践と接続します。

### Limitations / Open Questions

人間評価や「創造性」の主張は、実験設定、データセット、評価者の背景に依存します。

### Related Items

Mosaic Virus、Edmond de Belamy、Memories of Passersby I。

## DALL-E and Stable Diffusion

- Type: software / model families
- Creator / Author: OpenAI; Stability AI, CompVis, Runway
- Year: 2021-2022
- Context / Venue: Text-to-image generation
- Links: https://openai.com/index/dall-e/ / https://github.com/CompVis/stable-diffusion
- Category: ニューラル画像生成
- Importance: Foundational
- Confidence: High

### Why It Matters

テキストプロンプトを創作インターフェースにし、専門家以外にも画像生成AIを広く開きました。同時に、著作権、同意、スタイル模倣、訓練データの問題を前景化しました。

### Description

DALL-Eは自然言語から画像を生成する能力を示し、Stable Diffusionはオープンウェイト系のエコシステムを通じて創作実験を急拡大させました。

### Method / Medium / Approach

Transformer、CLIP、拡散モデル、潜在拡散、プロンプト、コミュニティツール。

### Historical or Research Context

2020年代の生成AIブームの中心にあり、美術、デザイン、広告、ゲーム、教育、SNSに波及しました。

### Limitations / Open Questions

モデルバージョン、訓練データ、ライセンス、出力権利は変化するため、個別に確認が必要です。

### Related Items

LAION-5B、Glaze、C2PA、Foregrounding Artist Opinions。
