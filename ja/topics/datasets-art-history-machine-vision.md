---
layout: default
title: データセット、美術史、機械知覚
permalink: /ja/topics/datasets-art-history-machine-vision/
---

# データセット、美術史、機械知覚

## 位置づけ

機械学習アートでは、データセットは単なる素材ではありません。分類体系、収集方法、権利、労働、偏り、歴史観を含む制度です。

## Item Notes

## ImageNet

- Type: dataset
- Creator / Author: Jia Deng et al.; Li Fei-Fei and collaborators
- Year: 2009
- Context / Venue: Large-scale visual recognition
- Links: https://www.image-net.org/
- Category: データセット、美術史、機械知覚
- Importance: Foundational
- Confidence: High

### Why It Matters

ImageNetは深層学習による視覚認識の発展に大きく寄与しました。同時に、分類語彙、人物カテゴリ、偏りをめぐる批評的作品の対象にもなりました。

### Description

多数の画像URLとカテゴリラベルを持つ大規模データセットで、ImageNet Large Scale Visual Recognition Challengeを通じて画像認識研究を加速しました。

### Method / Medium / Approach

画像収集、クラウドソーシング、WordNet由来カテゴリ、分類ベンチマーク。

### Historical or Research Context

AlexNet以降の深層学習ブームと、ImageNet Rouletteなどのデータセット批評の両方に関係します。

### Limitations / Open Questions

人物カテゴリやラベルの問題は後に見直しが進みました。時期を区別して記述する必要があります。

### Related Items

ImageNet Roulette、DeepDream、LAION-5B。

## WikiArt

- Type: dataset / online art encyclopedia
- Creator / Author: WikiArt community
- Year: 2010-
- Context / Venue: Art-image data source for ML research
- Links: https://www.wikiart.org/
- Category: データセット、美術史、機械知覚
- Importance: Important
- Confidence: High

### Why It Matters

WikiArtは、美術様式分類、CAN、ArtGAN、GAN肖像生成など、多くの研究・作品で実質的な訓練データ源になりました。

### Description

美術作品画像とメタデータを集めたオンライン百科事典で、研究者はそこから派生データセットを作ることがあります。

### Method / Medium / Approach

作品画像、作家名、様式、ジャンル、時代のメタデータ。

### Historical or Research Context

機械による美術史理解と美術画像生成の基盤として使われています。

### Limitations / Open Questions

作品画像の権利、メタデータ品質、地域・時代の偏りを確認する必要があります。

### Related Items

CAN、ArtGAN、Edmond de Belamy。

## LAION-5B and ArtEmis

- Type: datasets
- Creator / Author: LAION; Panos Achlioptas et al.
- Year: 2021-2022
- Context / Venue: Image-text scale and affective art-language dataset
- Links: https://arxiv.org/abs/2210.08402 / https://www.artemisdataset.org/
- Category: データセット、美術史、機械知覚
- Importance: Foundational / Contextual
- Confidence: High

### Why It Matters

LAION-5Bは大規模画像テキスト生成モデルの基盤として重要ですが、同意、プライバシー、有害コンテンツの論争を伴います。ArtEmisは、美術鑑賞における感情と言語説明を扱う別種のデータセットです。

### Description

LAION-5BはCLIPでフィルタされた大規模画像テキストペア群です。ArtEmisは作品に対する感情ラベルと説明文を結びつけます。

### Method / Medium / Approach

ウェブスケールデータ収集、マルチモーダル学習、感情アノテーション。

### Historical or Research Context

2020年代の生成AIと、鑑賞・感性理解の機械学習研究の両方を示します。

### Limitations / Open Questions

LAION-5Bはデータ倫理の中心的事例です。ArtEmisもアノテーション文化や作品権利の問題を検討する必要があります。

### Related Items

Stable Diffusion、Foregrounding Artist Opinions、C2PA。
