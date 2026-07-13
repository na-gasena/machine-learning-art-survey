---
layout: default
title: 言語、文学、物語生成
permalink: /ja/topics/language-literature-narrative/
lang: ja
---

[← 分野地図]({{ '/ja/survey-map/' | relative_url }}) ・ [作品・アーカイブ]({{ '/ja/resources/works-archive/' | relative_url }})

# 言語、文学、物語生成

<div class="topic-lead" markdown="1">
## このページの結論

機械による言語創作は、大規模言語モデルから始まったのではありません。1950年代の組合せ生成、1980年代の商用テキスト生成、2010年代の再帰型ニューラルネットワーク、2020年代の大規模言語モデルへと、生成規則、学習資料、人間による編集、上演方法が変化してきました。重要なのは「機械が書いたか」という二択ではなく、誰がコーパスを選び、出力を選別し、語り手や身体や出版物へ変換したかを追うことです。
</div>

## まず押さえる3点

- **生成と作品化は別の工程です。** 出力の選択、配列、翻訳、演技、編集、装丁、会場設計が作品の意味を作ります。
- **対話性と物語の持続性は別です。** 一文の応答が自然でも、登場人物、因果関係、長期記憶を維持できるとは限りません。
- **コーパスは文学的・政治的な装置です。** 19世紀詩、映画字幕、ロードノベル、既刊小説など、何を学習資料にするかが語彙、価値観、権利問題を決めます。

## 見取り図

| 時期 | 主な仕組み | 作品化の方法 | 代表項目 |
|---|---|---|---|
| 1950s-1980s | 組合せ規則、テンプレート、確率 | 印刷、実演、会話ソフト | Love Letters、Racter |
| 2015-2020 | RNN/LSTM、文字・単語予測 | 映画、旅行記、公共彫刻、即興劇 | word.camera、Sunspring、1 the Road、Improbotics |
| 2020以降 | Transformer、GPT系モデル | 戯曲、共同執筆、ライブ生成 | THEaiTRE、AI: When a Robot Writes a Play |

## 発展の流れ

### 1. 規則と組合せから「作者」を演出する

Christopher StracheyのLove Lettersは、Manchester Mark 1向けの語彙表と定型文を組み合わせました。Racterはテンプレートや文法処理を使いながら、出版物ではコンピュータを作者として前面化しました。後世の検証が示す通り、宣伝上の自律性と実際の人間労働は区別して読む必要があります。

### 2. ニューラル予測を映画、旅、公共空間へ運ぶ

Ross Goodwinの実践は、ニューラル言語モデルの出力をスクリーン、車載カメラ、感熱紙、公共彫刻へ接続しました。ここではモデル単体より、移動、センサー、印刷、俳優、観客入力が物語の条件になります。Improboticsでは機械生成文をイヤホンで俳優へ送り、身体的な正当化そのものを上演します。

### 3. LLM時代に編集と上演の責任を問い直す

THEaiTREはGPT-2を用いた戯曲生成を研究として文書化し、Švanda Theatreの上演へ接続しました。大規模言語モデルで流暢さが上がっても、構成、事実性、差別的出力、著作物との類似、翻訳、キャスティングの責任は消えません。むしろ人間の編集判断を記録する必要が増えます。

## 主要事例

### Love Letters program

<p class="item-meta">1952 ・ ソフトウェア／歴史的事例 ・ 基礎的 ・ 確信度: 高</p>

> **要点:** コンピュータ生成文学の初期例として、語彙と文型の組合せが親密さの言語を模倣しました。

**内容。** Christopher StracheyがManchester Mark 1向けに作成したプログラムで、定型句と語彙を組み合わせて恋文を生成しました。Bodleian Librariesには1952年のノート、計算、ルーチンが保存されています。

**読みどころ。** 「意味を理解する機械」より先に、形式の反復だけで作者らしさや感情らしさが生じることを示します。

**資料:** [Bodleian Archives](https://archives.bodleian.ox.ac.uk/repositories/2/archival_objects/28661)

### Racter / The Policeman's Beard Is Half Constructed

<p class="item-meta">1983-1984 ・ ソフトウェア／書籍 ・ 基礎的 ・ 確信度: 中</p>

> **要点:** 「コンピュータが書いた本」という市場上の語りと、テンプレート、未公開版、人間の編集の関係を検証できる事例です。

**内容。** William ChamberlainとThomas Etterが開発したRacterに帰属する散文・詩集です。市販版Racterと書籍生成に使われた版は同一ではなく、生成コードも完全には保存されていません。

**注意。** 「全てコンピュータが書いた」という宣伝文句を、そのまま技術的事実として扱わないようにします。

**資料:** [Electronic Book Reviewの検証](https://electronicbookreview.com/publications/constructing-the-other-half-of-the-policemans-beard/) ・ [WorldCat](https://search.worldcat.org/title/311319022)

### word.camera

<p class="item-meta">2015- ・ プロジェクト ・ 重要 ・ 確信度: 高</p>

> **要点:** 写真を撮る行為を、画像認識とニューラル言語生成による記述へ置き換えました。

**内容。** Ross Goodwinによる「言葉のカメラ」で、視覚入力を認識結果と生成文へ変換します。生成文学を画面上の文章だけでなく、撮影装置と知覚の問題へ広げました。

**資料:** [Ross Goodwin公式アーカイブ](https://rossgoodwin.com/)

### Sunspring

<p class="item-meta">2016 ・ 短編映画 ・ 重要 ・ 確信度: 高</p>

> **要点:** ニューラルネットワーク生成脚本を俳優と制作チームが解釈し、映像作品へ変換しました。

**内容。** Ross Goodwinのモデルが生成した脚本をOscar Sharpが監督し、俳優が演じました。文章の不整合を、演技、編集、音楽が意味のある出来事へ変える過程が作品の中心です。

**資料:** [Ross Goodwin公式](https://rossgoodwin.com/)

### 1 the Road

<p class="item-meta">2017-2018 ・ 書籍／プロジェクト ・ 重要 ・ 確信度: 高</p>

> **要点:** 車載センサー、GPS、カメラ、時刻を入力とし、移動しながら生成・印刷されたロードノベルです。

**内容。** Goodwinはニューヨークからニューオーリンズへの移動中、車両に取り付けた装置から得たデータをモデルへ送り、感熱紙へ文章を出力しました。文学作品の「場所」を、事後的な描写ではなく生成条件にします。

**資料:** [Jean Boîte Éditions](https://www.jbe-books.com/products/1-the-road-by-an-artificial-neural) ・ [Ross Goodwin](https://rossgoodwin.com/)

### Please Feed the Lions

<p class="item-meta">2018 ・ 公共インスタレーション ・ 重要 ・ 確信度: 高</p>

> **要点:** 観客が与えた一語を、機械学習モデルが公共空間の集合詩へ展開しました。

**内容。** Es DevlinとGoogle Arts & CultureによるTrafalgar Squareの作品です。Ross Goodwinのモデルは19世紀詩2500万語で訓練され、観客入力から詩行を生成し、彫刻とNelson's Columnへ投影しました。

**資料:** [作品アーカイブ](https://artsandculture.google.com/project/please-feed-the-lions) ・ [Google公式解説](https://blog.google/company-news/outreach-and-initiatives/arts-culture/please-feed-lions/)

### Improbotics

<p class="item-meta">2016- ・ 即興演劇／研究 ・ 重要 ・ 確信度: 高</p>

> **要点:** AIの台詞を俳優が身体と感情で正当化し、観客と演者が人間／機械を推測するライブ実験です。

**内容。** Piotr MirowskiとKory Mathewsonらが共同制作し、映画字幕で学習したモデルからGPT系モデルまで更新してきました。生成文はイヤホンで「Cyborg」役へ送られます。

**限界。** モデルの流暢さだけでなく、演者の技量、選別、会場、観客の期待が結果を大きく左右します。

**資料:** [Improbotics公式](https://improbotics.org/) ・ [AIIDE論文](https://doi.org/10.1609/aiide.v14i1.13030)

### The Day a Computer Writes a Novel

<p class="item-meta">2016 ・ 文学プロジェクト ・ 文脈的 ・ 確信度: 中</p>

> **要点:** 日本語小説生成を文学賞応募という制度的な場へ持ち込んだプロジェクトです。

**内容。** 佐藤理史らの「気まぐれ人工知能プロジェクト 作家ですのよ」により制作されました。人間が筋、語彙、生成規則、選択へ深く関与しており、自律的な長編執筆の達成として単純化できません。

**資料:** [集英社インタビュー](https://shinsho-plus.shueisha.co.jp/interview/%E4%BD%90%E8%97%A4%E7%90%86%E5%8F%B2%E3%82%A4%E3%83%B3%E3%82%BF%E3%83%93%E3%83%A5%E3%83%BC/2134)

### THEaiTRE / AI: When a Robot Writes a Play

<p class="item-meta">2020-2021 ・ 研究プロジェクト／演劇 ・ 重要 ・ 確信度: 高</p>

> **要点:** 戯曲生成の研究プロトタイプを、チェコ語への機械翻訳と劇場上演まで接続しました。

**内容。** GPT-2を用いて生成された脚本を、Karel Čapekの『R.U.R.』初演100周年に合わせŠvanda Theatreが上演しました。研究論文、プロジェクト、上演記録を相互に照合できます。

**資料:** [Švanda Theatre](https://www.svandovodivadlo.cz/inscenace/673/ai-kdyz-robot-pise-hru) ・ [THEaiTRE論文](https://arxiv.org/abs/2006.14668) ・ [THEaiTRE 1.0](https://arxiv.org/abs/2102.08892)

## 比較して読むための質問

- 生成された全出力のうち、誰が何を捨て、何を残したか。
- 学習コーパスの時代、言語、ジャンル、権利状態は記録されているか。
- モデルの誤りや不整合は欠陥として隠されたか、演技や編集の素材になったか。
- 翻訳、音声合成、演者の身体を経たとき、作者性はどこへ分配されるか。
- 観客入力は参加と呼べるのか、それとも生成装置の無料データ提供なのか。

## 境界と不足

電子文学、ボット文学、ゲーム内物語、チャットボット、一般的なLLM小説を全て収録することはしていません。機械学習と作品化の工程が確認でき、一次資料または信頼できる研究資料へ到達できる事例を優先しています。ReRitesなど重要な詩の実践は、安定した一次アーカイブの追加確認を継続します。

## 次に読む

- [音楽、パフォーマンス、インタラクティブ機械学習]({{ '/ja/topics/music-performance-interactive-ml/' | relative_url }}) - 即興、ライブ性、音声
- [映像、ゲーム、空間的メディア]({{ '/ja/topics/moving-image-games-spatial-media/' | relative_url }}) - 物語を世界とシミュレーションへ拡張
- [批評、権利、来歴]({{ '/ja/topics/critique-rights-provenance/' | relative_url }}) - コーパス、著作権、帰属
