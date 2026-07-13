---
layout: default
title: ニューラル画像生成
permalink: /ja/topics/neural-image-generation/
lang: ja
---

[← 分野地図]({{ '/ja/survey-map/' | relative_url }}) ・ [作品・アーカイブ]({{ '/ja/resources/works-archive/' | relative_url }})

# ニューラル画像生成

<div class="topic-lead" markdown="1">
## このページの結論

ニューラル画像生成の歴史は、単純な「画質向上」の物語ではありません。2015年前後には認識ネットワークの内部表現を画像変換へ転用し、2010年代後半にはGANがデータ分布を学ぶ生成を普及させ、2020年代にはテキストと画像を結ぶ拡散モデルが制作インターフェースと流通環境を変えました。各段階で、作品の見た目だけでなく、作者の役割、データセット、アクセス方法、権利問題も変化しています。
</div>

## まず押さえる3点

- **研究手法が、そのまま視覚文化になりました。** DeepDreamやスタイル変換は、可視化・画像処理研究からミーム、アプリ、作品へ広がりました。
- **生成の仕組みごとに、美学と制約が異なります。** GANの潜在空間、スタイル分類を利用するCAN、言語で操作する拡散モデルを同じ「AI画像」として一括りにしないことが重要です。
- **2020年代の転換はインターフェースと規模にもあります。** テキスト入力、ウェブサービス、オープンウェイト、巨大画像テキストデータが利用者と論争の範囲を拡大しました。

## 見取り図

| 時期 | 主な操作 | 典型的な入力 | 代表項目 |
|---|---|---|---|
| 2015年前後 | 認識ネットワークの特徴を増幅・再結合 | 既存画像、参照様式 | DeepDream、ニューラルスタイル変換 |
| 2014-2019 | 画像分布や潜在空間を敵対的に学習 | 画像データセット、潜在ベクトル | GAN、CAN、ArtGAN |
| 2021以降 | 言語と画像を結び、反復的に生成 | テキスト、画像、マスク | DALL-E、Stable Diffusion |

## 発展の流れ

### 1. 「見る」ネットワークを画像制作へ転用する

DeepDreamは分類ネットワークが反応する特徴を増幅し、ネットワークの内部表現を幻視的な画像として可視化しました。ニューラルスタイル変換は、CNNの中間表現を使って「内容」と「様式」を分けて最適化しました。どちらも本来の認識機能を反転させ、機械の見方を創作操作へ変えた事例です。

### 2. データ分布から新しい画像を作る

GANは生成器と識別器の競合によって訓練データの分布を学びます。CANは既存の芸術様式に属しながら分類しにくい出力を目指し、ArtGANは美術画像の条件付き生成を扱いました。ここでデータセットの選択と「創造性」の評価方法が制作の中心へ入ります。

### 3. 言葉が制作インターフェースになる

DALL-EやStable Diffusionでは、テキストプロンプトが画像生成への一般的な入口になりました。生成画像の利用は美術から広告、ゲーム、教育、SNSへ広がる一方、訓練データの同意、スタイル模倣、著作権、プラットフォーム依存が前景化しました。

## 代表事例

### DeepDream / Inceptionism

<p class="item-meta">2015 ・ 手法／ソフトウェア ・ 基礎的 ・ 確信度: 高</p>

> **要点:** ニューラルネットワークの内部表現を可視化する研究手法が、新しい画像表現とインターネット文化へ転じた事例です。

**内容。** Alexander Mordvintsev、Christopher Olah、Mike Tykaらは、CNNが検出した特徴を勾配上昇で増幅し、動物や建築のような形が反復的に浮かぶ画像を生成しました。

**読みどころ。** 解釈可能性研究、技術デモ、作家による利用、オンライン上のミームが連続しており、研究成果がどの時点で作品や様式になるのかを考えられます。

**注意。** DeepDreamそのものと、それを利用した個々の作品は区別して評価する必要があります。

**資料:** [Google Research: Inceptionism](https://research.googleblog.com/2015/06/inceptionism-going-deeper-into-neural.html)

**関連:** ニューラルスタイル変換、ImageNet、Learning to See

### A Neural Algorithm of Artistic Style

<p class="item-meta">2015 ・ 論文／手法 ・ 基礎的 ・ 確信度: 高</p>

> **要点:** 画像の「内容」と「様式」をニューラル表現として分離・再結合する考え方を広く普及させました。

**内容。** Leon A. Gatys、Alexander S. Ecker、Matthias Bethgeは、VGG系CNNの中間特徴とGram行列を使い、写真の構成と絵画の統計的特徴を組み合わせる最適化手法を提示しました。

**読みどころ。** スマートフォンアプリやウェブサービスを通じ、AI画像処理が一般利用者へ広がる契機になりました。同時に、美術史上の様式を計算可能な特徴へ還元することの意味を問います。

**注意。** 統計的な「様式表現」は、文化的・歴史的に形成された美術様式そのものと同一ではありません。

**資料:** [arXiv](https://arxiv.org/abs/1508.06576)

**関連:** DeepDream、WikiArt、CAN

### GAN / CAN / ArtGAN

<p class="item-meta">2014-2017 ・ 論文／手法群 ・ 基礎的／重要 ・ 確信度: 高</p>

> **要点:** 2010年代後半のAIアートを支えた生成技術と、「既存様式からの逸脱」を計算的創造性へ結びつけた研究群です。

**内容。** GANは生成器と識別器の競合で画像分布を学びます。CANは芸術分布に留まりつつ既存様式へ分類されにくい出力を目指し、ArtGANは美術画像の条件付き生成を扱いました。

**読みどころ。** 技術論文と、Anna Ridler、Mario Klingemann、Obviousなどの作品・市場現象を接続して読むと、モデル、データ、作家の介入、展示制度の役割を分けて考えられます。

**注意。** 「創造性」の実験的主張は、データセット、評価者、比較条件に依存します。GAN作品すべてがCANやArtGANを使っているわけでもありません。

**資料:** [GAN](https://arxiv.org/abs/1406.2661) ・ [CAN](https://arxiv.org/abs/1706.07068) ・ [ArtGAN](https://arxiv.org/abs/1702.03410)

**関連:** Mosaic Virus、Edmond de Belamy、Memories of Passersby I

### DALL-E / Stable Diffusion

<p class="item-meta">2021-2022以降 ・ モデル群／ソフトウェア ・ 基礎的 ・ 確信度: 高</p>

> **要点:** テキストを創作インターフェースにし、画像生成を大規模な一般利用と産業的ワークフローへ移したモデル群です。

**内容。** DALL-Eは自然言語から多様な画像を生成する能力を示しました。Stable Diffusionは潜在拡散と公開モデルを核に、多数の派生ツール、追加学習、ローカル実行を含むエコシステムを形成しました。

**読みどころ。** 作品だけでなく、プロンプト、モデル提供者、UI、コミュニティ拡張、計算資源、配布ライセンスが制作環境を構成しています。

**注意。** モデルの版、訓練データ、利用規約、出力の権利は変化します。特定時点の情報とモデル群全体を混同しない確認が必要です。

**資料:** [OpenAI: DALL-E](https://openai.com/index/dall-e/) ・ [CompVis: Stable Diffusion](https://github.com/CompVis/stable-diffusion)

**関連:** LAION-5B、Glaze、C2PA、Foregrounding Artist Opinions

## 技術系譜を細分化する

### 画像から画像へ: pix2pixとCycleGAN

pix2pix（2017）は対応する入力・出力の組を学び、線画から写真、ラベルから街景などの変換を一般化しました。CycleGAN（2017）は対応画像がない二つの領域を循環整合性で結び、馬／シマウマの例に象徴される変換を普及させました。芸術利用では便利な「様式変換」に見えますが、学習領域が持つ文化差を表面的な質感へ還元する危険もあります。

- [pix2pix論文](https://arxiv.org/abs/1611.07004) ・ [コード](https://github.com/phillipi/pix2pix)
- [CycleGAN論文](https://openaccess.thecvf.com/content_ICCV_2017/papers/Zhu_Unpaired_Image-To-Image_Translation_ICCV_2017_paper.pdf)

### 高解像度GAN: BigGANとStyleGAN

BigGANは大規模計算とImageNetのクラス条件付き生成を結び、品質と多様性の調整を可視化しました。StyleGANは潜在変数を中間表現へ写像し、顔や限定された画像領域で高品質かつ操作しやすい生成を実現しました。Artbreederのようなサービスは、潜在空間の交配と共有を一般利用者の制作行為へ変えています。

- [BigGAN](https://openreview.net/forum?id=B1xsqj09Fm)
- [StyleGAN](https://arxiv.org/abs/1812.04948) ・ [StyleGAN2](https://arxiv.org/abs/1912.04958)
- [Artbreederの技術・沿革](https://www.artbreeder.com/about)

### 言語と画像を接続する: CLIPとVQGAN+CLIP

CLIPは大規模な画像・テキスト対から両者の共有表現を学び、自然言語で画像を評価・探索する基盤になりました。2021年のVQGAN+CLIPは、既存モデルを組み合わせてテキストに合う画像を反復最適化するコミュニティ実践として広がりました。単一企業の製品史だけでなく、ノートブック、チュートリアル、Discord、SNSを通じた再結合の文化史が必要です。

- [OpenAI CLIP](https://openai.com/index/clip/) ・ [論文](https://arxiv.org/abs/2103.00020)
- [Taming Transformers / VQGAN](https://openaccess.thecvf.com/content/CVPR2021/html/Esser_Taming_Transformers_for_High-Resolution_Image_Synthesis_CVPR_2021_paper.html)
- [VQGAN+CLIPの同時代チュートリアル](https://minimaxir.com/2021/08/vqgan-clip/)

### 拡散モデル: DDPMから潜在拡散へ

DDPM（2020）は段階的にノイズを除去する生成を高品質画像へ展開しました。Latent Diffusion Models（2022）は画素空間ではなく圧縮された潜在空間で拡散を行い、計算量を抑えながらテキストなどの条件付けを可能にしました。Stable Diffusionはこの研究、LAION系データ、公開重み、周辺UIが組み合わさったエコシステムとして読む必要があります。

- [DDPM](https://proceedings.neurips.cc/paper/2020/hash/4c5bcfec8584af0d967f1ab10179ca4b-Abstract.html)
- [Latent Diffusion Models](https://openaccess.thecvf.com/content/CVPR2022/html/Rombach_High-Resolution_Image_Synthesis_With_Latent_Diffusion_Models_CVPR_2022_paper.html)

### 制作インターフェース: GauGANとArtbreeder

NVIDIAのGauGAN/GauGAN2は、セマンティックな描画や語句を風景画像へ変換し、モデル能力を制作UIとして提示しました。Artbreederは生成画像を個人の最終成果ではなく、他者が交配・派生できる共有資源として扱います。どちらも「モデル」だけでなく、選択可能な操作と公開範囲が美学を規定する例です。[GauGAN2](https://blogs.nvidia.com/blog/gaugan2-ai-art-demo/) ・ [Artbreeder](https://www.artbreeder.com/about)

## 横断して考える問い

- 「様式」を特徴量やプロンプトで扱うとき、美術史的文脈の何が失われるか。
- モデル、データ、プロンプト、選択・編集のどこに作者性を認めるか。
- 公開モデルと商用サービスでは、透明性、アクセス、再現性、責任はどう異なるか。

## 次に読む

- [データセット、美術史、機械知覚]({{ '/ja/topics/datasets-art-history-machine-vision/' | relative_url }}) - 生成を支える画像収集と分類体系
- [制作ツール、教育、プラットフォーム]({{ '/ja/topics/creative-tools-platforms/' | relative_url }}) - モデルが制作環境へ組み込まれる過程
- [批評、権利、来歴]({{ '/ja/topics/critique-rights-provenance/' | relative_url }}) - 同意、模倣、著作権、来歴表示
