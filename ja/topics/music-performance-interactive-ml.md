---
layout: default
title: 音楽、パフォーマンス、インタラクティブ機械学習
permalink: /ja/topics/music-performance-interactive-ml/
lang: ja
---

[← 分野地図]({{ '/ja/survey-map/' | relative_url }}) ・ [作品・アーカイブ]({{ '/ja/resources/works-archive/' | relative_url }})

# 音楽、パフォーマンス、インタラクティブ機械学習

<div class="topic-lead" markdown="1">
## このページの結論

音楽とパフォーマンスでは、機械学習は完成品を自動生成する装置に限られません。演奏者が例を示してシステムを訓練し、身体・音・映像の対応関係を即興的に作る「楽器」や、未知の音色を探索する制作環境として使われます。この領域を理解する鍵は、出力の品質だけでなく、訓練と試行錯誤そのものを創作過程として見ることです。
</div>

## まず押さえる3点

- **モデルを作る行為が演奏になります。** インタラクティブ機械学習では、データ収集、例示、修正が身体的な制作行為です。
- **音楽AIには複数の時間尺度があります。** ジェスチャへの即時応答、音色の生成、楽曲構造の生成は別の問題です。
- **自動作曲だけを中心に置くと分野を見誤ります。** NIMEやHCIでは、人間が理解し、調整し、演奏できる関係が重視されます。

## 見取り図

| 制作の層 | 機械学習の役割 | 代表項目 | 主な評価軸 |
|---|---|---|---|
| 身体・操作 | ジェスチャと音・映像を学習して結ぶ | Wekinator | 応答性、教えやすさ、演奏可能性 |
| 音色・素材 | 音響特徴を学び、新しい音色を探索する | NSynth / Magenta | 音色の多様性、制御可能性 |
| 制作思想 | アルゴリズムを対話的インターフェースと捉える | Fiebrink & Caramiaux | 理解可能性、反復、創造的発見 |

## 発展の流れ

### 1. 実演によって機械へ教える

Wekinatorでは、利用者が入力と望ましい出力の例を示し、その場でモデルを訓練します。コードで写像を細かく指定する代わりに、身体動作や音の例示を通じてシステムの振る舞いを形づくります。

### 2. 音色をデータ空間として探索する

Magentaは音楽・アート向けの研究成果をコードやデモとして公開し、NSynthは単音サンプルから音色の特徴を学習しました。機械学習は曲を丸ごと作るだけでなく、楽器と音響素材の設計にも関わります。

### 3. 「正解」より、対話の質を評価する

創作ツールでは、分類精度だけが価値ではありません。演奏者がモデルの癖を理解できるか、短い試行で修正できるか、意図しなかった応答を発見へ変えられるかが重要です。

## 代表事例

### Wekinator

<p class="item-meta">2009- ・ ソフトウェア ・ 重要 ・ 確信度: 高</p>

> **要点:** プログラムを書く代わりに実演でモデルを訓練し、身体、音、映像の関係をリアルタイムに設計できる創作ツールです。

**内容。** Rebecca Fiebrinkが開発し、利用者が入力例と出力例を示すことで関係を学習させます。OSCを介してProcessing、openFrameworks、Unity、Abletonなどと接続できます。

**読みどころ。** 訓練データが制作前に固定された資源ではなく、演奏者がその場で作る素材になります。NIME、HCI、音楽情報処理、クリエイティブコーディングを結ぶ代表例です。

**注意。** 評価ではモデル精度だけでなく、訓練のしやすさ、反復速度、誤りの理解可能性を扱う必要があります。

**資料:** [Wekinator公式サイト](https://doc.gold.ac.uk/~mas01rf/Wekinator/)

**関連:** *The Machine Learning Algorithm as Creative Musical Tool*、NIME

### Magenta / NSynth

<p class="item-meta">2016-2017以降 ・ プロジェクト／データセット／ソフトウェア ・ 重要 ・ 確信度: 高</p>

> **要点:** 機械学習を音楽制作の実験的な道具として公開し、音色の潜在表現を楽器設計へ結びつけた研究・制作環境です。

**内容。** Magentaは研究コード、モデル、デモ、制作ツールを公開しました。NSynthは約30万の注釈付き単音サンプルとWaveNet系の手法を使い、楽器音の特徴を学習して新しい音色を探索します。

**読みどころ。** データセット、モデル、DAWプラグイン、オープンソース配布が一つの創作エコシステムを作る過程を確認できます。

**注意。** 単音データセットは、多声性、長期的な楽曲構造、演奏者と場の文脈を十分には表現しません。

**資料:** [Magenta](https://magenta.tensorflow.org/) ・ [NSynth](https://magenta.tensorflow.org/nsynth)

**関連:** Wekinator、Holly+、PROTO / Spawn

### The Machine Learning Algorithm as Creative Musical Tool

<p class="item-meta">2016 ・ 論文／理論整理 ・ 重要 ・ 確信度: 高</p>

> **要点:** 機械学習アルゴリズムを自動作曲器ではなく、人間とコンピュータの間を設計する創作インターフェースとして捉えます。

**内容。** Rebecca FiebrinkとBaptiste Caramiauxは、音楽家が自分の例や例外をシステムへ教え、モデルの反応を手掛かりに可能性を探る人間中心の見方を整理しました。

**読みどころ。** Wekinatorを単なる使いやすいソフトウェアではなく、訓練、反復、身体的知識を重視する制作思想として理解する助けになります。

**注意。** 2016年の論文であり、近年の大規模音楽生成モデル、音声クローン、権利問題は別に追跡する必要があります。

**資料:** [arXiv](https://arxiv.org/abs/1611.00379)

**関連:** Wekinator、Magenta、NIME

## 追加調査: 作曲、即興、音色、身体

### Continuator: 相手の様式をリアルタイムに学ぶ

François PachetのContinuator（2002）は、演奏者のフレーズから様式をオンライン学習し、続きを返す「対話する楽器」です。完成曲の自動生成より、入力、応答、間、主導権の往復を中心に置いた点で、インタラクティブ機械学習の重要な前史です。[ICMC論文](https://www.francoispachet.fr/wp-content/uploads/2021/01/pachet-02-icmai-final.pdf) ・ [研究者の出版物一覧](https://www.francoispachet.fr/publications/)

### DeepBach: 制約可能な様式生成

DeepBach（2016-2017）は、Bachコラールを対象に擬似Gibbsサンプリングを用い、音符、リズム、カデンツなどを利用者が固定できる生成を提示しました。「Bachらしさ」の模倣だけでなく、どの程度人間が局所制約を与えられるかが重要です。[論文](https://arxiv.org/abs/1612.01010)

### Flow Machines: 自動作曲から制作支援へ

Sony CSLのFlow Machinesは、2012年からの研究をFM Proやアプリへ展開し、Style Paletteに基づくメロディ、コード、ベースラインの提案をDAWへ統合しました。2016年の*Daddy's Car*は広報上の注目を集めましたが、編曲、作詞、演奏、制作を含む人間の役割を「AIが一曲作った」という表現で消さないことが必要です。[Sony公式解説](https://www.sony.com/en/SonyInfo/design/stories/flow-machines/) ・ [製品発表](https://www.sony.eu/presscentre/sony-computer-science-laboratories-launches-ai-assisted-music-production-app-flow-machines-in-europe)

### Shimon: ロボットの身体を持つ即興者

Georgia TechのShimonは、楽曲生成とロボットによるマリンバ演奏を接続します。音高列の生成だけでなく、打鍵可能範囲、腕の移動、視覚的な合図、共演者との時間合わせがシステムを制約します。[Georgia Tech公式](https://gtcmt.gatech.edu/shimon) ・ [深層学習版の解説](https://news.gatech.edu/news/2017/06/13/robot-uses-deep-learning-and-big-data-write-and-play-its-own-music)

### Dadabots: 終わらないストリーム

CJ CarrとZack ZukowskiのDadabotsは、ニューラル音声生成をメタル、パンク、実験音楽へ適用し、*Relentless Doppelganger*を継続的なライブストリームとして提示しました。アルバム単位ではなく、止まらない生成、配信プラットフォーム、ジャンル共同体の反応を作品条件にします。[Dadabots公式音源・配信一覧](https://dadabots.com/music)

### FluCoMa: 個々の音素材を分析するツール群

Fluid Corpus Manipulation（FluCoMa）は、Max、Pure Data、SuperCollider向けに音声分析、次元削減、クラスタリング、分類などを提供します。大規模生成モデルとは対照的に、作家自身の小さな音素材を分析・再編成し、ライブ制作へ組み込める点が重要です。[公式サイトと引用情報](https://www.flucoma.org/about)

### ダンスと演劇へ

Wayne McGregorの*Living Archive*は25年分の映像を振付提案へ変え、Rhizomatiks Research、ELEVENPLAY、Kyle McDonaldの*discrete figures*はOpenPoseなどの機械知覚と仮想ダンサーを舞台へ統合しました。Improboticsは生成台詞を人間の俳優へ送り、誤りを身体的な即興へ変えます。

- [Living Archive](https://waynemcgregor.com/productions/living-archive/) ・ [オンライン実験](https://experiments.withgoogle.com/living-archive-wayne-mcgregor)
- [discrete figures](https://research.rhizomatiks.com/s/works/discrete_figures)
- [Improbotics](https://improbotics.org/) ・ [AIIDE論文](https://doi.org/10.1609/aiide.v14i1.13030)

## 研究コミュニティと資料

- [NIME](https://www.nime.org/)は新しい音楽表現インターフェースと演奏システムを扱います。
- [AIMC](https://aimusiccreativity.org/)はAI音楽創造の研究・作品・ワークショップを接続します。
- [ISMIR](https://ismir.net/)は音楽情報検索の基盤研究を担い、生成、推薦、データセット研究と接点があります。
- [FluCoMa Learning Resources](https://learn.flucoma.org/)は小規模コーパスを用いた実践的学習の入口です。

## 横断して考える問い

- 演奏者がモデルを「理解した」といえるのは、内部構造を知るときか、身体で扱えるときか。
- データ収集と訓練を即興の一部として、どのように記録・再演できるか。
- 音色、声、演奏スタイルの学習では、本人の同意と文化的帰属をどう扱うか。

## 次に読む

- [人間・機械協働と身体的実践]({{ '/ja/topics/human-machine-collaboration/' | relative_url }}) - 声、ロボット、身体を介した共演
- [制作ツール、教育、プラットフォーム]({{ '/ja/topics/creative-tools-platforms/' | relative_url }}) - 創作ツールの普及とアクセス
- [批評、権利、来歴]({{ '/ja/topics/critique-rights-provenance/' | relative_url }}) - 声やスタイルの権利と同意
