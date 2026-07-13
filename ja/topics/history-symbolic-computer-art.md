---
layout: default
title: 歴史、記号的AI、コンピュータアート
permalink: /ja/topics/history-symbolic-computer-art/
lang: ja
---

[← 分野地図]({{ '/ja/survey-map/' | relative_url }}) ・ [作品・アーカイブ]({{ '/ja/resources/works-archive/' | relative_url }})

# 歴史、記号的AI、コンピュータアート

<div class="topic-lead" markdown="1">
## このページの結論

機械学習アートは、2010年代の深層学習から始まった分野ではありません。その前には、作家の知識を規則として記述する試み、描画機械、アルゴリズム芸術、そして「機械に創造性を帰属できるか」を検討する計算論的創造性研究がありました。現在との重要な違いは、外部の巨大データから様式を学ぶのではなく、作者が規則・知識・評価基準を比較的明示的に設計していた点です。
</div>

## まず押さえる3点

- **技術の連続性より、問いの連続性が重要です。** AARONは現在の意味での機械学習ではありませんが、作者性、自律性、身体性という今日の論点を先取りしました。
- **「生成できること」と「創造的であること」は別です。** The Painting Foolは、意図、評価、文脈、自己批評を創造性の条件として扱いました。
- **歴史を一本の進歩物語にしないことが必要です。** 記号的AI、進化的芸術、ニューラル生成は置き換え関係ではなく、異なる設計思想として併存しています。

## 見取り図

| 時期 | 中心的な考え方 | 作者が設計するもの | 代表項目 |
|---|---|---|---|
| 1960年代後半以降 | 芸術知識を規則として記述する | 構図、線、対象知識、描画手順 | AARON |
| 2000年代以降 | システムを創造的主体として評価する | 生成・評価・文脈化の仕組み | The Painting Fool |
| 2010年代以降 | 複数のAI技術と創造性理論を統合する | モデル、データ、評価方法 | *Creativity and Machine Learning: A Survey* |

## 発展の流れ

### 1. 規則を書くことが、絵を描くことになる

初期のコンピュータアートでは、作家は完成画像だけでなく、画像を生み出す手続きそのものを制作しました。AARONではHarold Cohenの描画知識が長年にわたりプログラムへ組み込まれ、プロッタ、描画機械、プリンタなど出力装置も変化しました。ここでは「学習済みモデルに指示する」よりも、「どの知識を機械が使える形にするか」が中心課題です。

### 2. 生成能力から、創造性の条件へ

The Painting Foolに代表される計算論的創造性研究は、画像の見栄えだけでなく、システムが意図を持つように見えるか、結果を評価できるか、文脈に応答できるかを問います。この視点は、生成モデルの性能比較だけでは捉えにくい芸術的主体性を検討する枠組みを与えます。

### 3. 深層学習後も残る問い

大規模モデルは規則の手書きを減らしましたが、作者性や評価の問題を解消したわけではありません。むしろ、規則がデータセット、損失関数、モデル設計、プラットフォーム規約へ分散したことで、誰が何を決めているのかは見えにくくなりました。

## 代表事例

### AARON

<p class="item-meta">1968-2016 ・ 作品／ソフトウェア ・ 基礎的 ・ 確信度: 高</p>

> **要点:** 機械が自律的に画像を作るとは何かを、約半世紀にわたり作品と研究の両方として問い続けたシステムです。

**内容。** Harold Cohenは、自身の描画知識をプログラムに落とし込み、AARONに線画や彩色作品を生成させました。AARONは外部画像から新しい様式を学ぶモデルではなく、Cohenが設計した知識と規則の体系として発展しました。

**読みどころ。** 記号的AI、プロッタや描画機械、後期のプリンタやデジタル彩色が一つの制作実践に結びついています。作者を「絵を直接描く人」から「描画知識と生成条件を設計する人」へ広げた点が重要です。

**注意。** 現在の意味での機械学習ではないため、生成AIの直接の技術祖先と断定すべきではありません。問題設定と制作思想の前史として位置づけます。

**資料:** [AARON公式アーカイブ](http://aaronshome.com/) ・ [Whitney Museum: Harold Cohen - AARON](https://whitney.org/exhibitions/harold-cohen-aaron)

**関連:** The Painting Fool、SIGGRAPH、computational creativity

### The Painting Fool

<p class="item-meta">2001- ・ ソフトウェア／研究プロジェクト ・ 重要 ・ 確信度: 中</p>

> **要点:** 絵を作るソフトウェアを道具としてだけでなく、創造的主体として見なせる条件を研究するプロジェクトです。

**内容。** Simon Coltonが主導し、生成、外部情報の利用、評価機構など複数のAI手法を組み合わせてきました。焦点は画像生成の性能だけでなく、意図、自己批評、感情、文脈をシステムにどう持たせるかにあります。

**読みどころ。** ICCCなどの計算論的創造性コミュニティが、創造性を作品の外観ではなく制作過程と評価の関係として研究してきたことが分かります。

**注意。** 現代の大規模生成モデルとの比較では、視覚的性能より概念的・評価論的な意義を中心に読む必要があります。

**資料:** [ICCC 2015論文（作品画像・実践記録を含む）](https://computationalcreativity.net/iccc2015/proceedings/8_2Colton.pdf)

**関連:** AARON、ICCC、計算論的創造性

### Creativity and Machine Learning: A Survey

<p class="item-meta">2021 ・ 論文／文献レビュー ・ 重要 ・ 確信度: 高</p>

> **要点:** 創造性理論、機械学習技術、評価手法を横断し、作品調査だけでは見落としやすい研究側の地図を与えるサーベイです。

**内容。** Giorgio FranceschelliとMirco Musolesiが、計算論的創造性の理論、生成深層学習、評価方法、未解決課題を整理しています。

**読みどころ。** AIアートを一時的なメディア現象ではなく、創造性研究の長期的な問題として位置づけるための入口になります。

**注意。** アート制度、市場、作家労働、地域差は主題の中心ではないため、権利・制度やグローバルな実践を扱うページと組み合わせて読む必要があります。

**資料:** [arXiv](https://arxiv.org/abs/2104.02726)

**関連:** The Painting Fool、Foregrounding Artist Opinions

## 追加調査: 見落とせない系譜

### Love LettersとILLIAC Suite

1952年のChristopher StracheyによるLove Lettersは、語彙表と定型文の組合せから親密な言語を生成しました。1956-1957年のLejaren HillerとLeonard Isaacsonによる*ILLIAC Suite*は、規則と確率的選択を作曲へ使った初期例です。どちらも現在の機械学習ではありませんが、規則、選択、出力、人間による作品化を分解して考える基準になります。

- Love Letters: [Bodleian Archives](https://archives.bodleian.ox.ac.uk/repositories/2/archival_objects/28661)
- ILLIAC Suite: [University of Illinois Computer Music](https://computermusic.web.illinois.edu/Notes/CaC2.html)

### Cybernetic Serendipity

Jasia ReichardtがICA Londonで企画した1968年の展覧会は、コンピュータ生成図像、音楽、詩、機械、サイバネティクスを同じ場へ置きました。130組以上が参加し、約6万人が来場したとICAは記録しています。ここでは「AIアート」という後代の名称を遡及的に当てるより、芸術家、技術者、数学者、作曲家の活動がどのように同じ展覧会へ編成されたかを読むべきです。[ICAの文書・写真・映像アーカイブ](https://archive.ica.art/whats-on/cybernetic-serendipity-documentation/)

### Mutatorと進化的美学

William LathamとStephen Toddは1980年代末から、形態を突然変異させ、人間が美的選択を繰り返すMutator系の制作を展開しました。進化計算は「最良の画像」を自動決定するのではなく、探索空間と選択者の関係を作品化します。1992年の書籍*Evolutionary Art and Computers*は、この系譜の技術と制作思想をまとめた重要資料です。

- [Goldsmithsの作家・文献記録](https://www.gold.ac.uk/computing/people/w-latham/)
- [Mutator 1 + 2解説](https://www.gold.ac.uk/news/w-latham---mutator-1-and-2/)
- [Mutator VR](https://www.gold.ac.uk/research/case-studies/mutator-vr/)

### Interactive Plant GrowingとA-Volve

Christa SommererとLaurent Mignonneauは、*Interactive Plant Growing*（1992）で実在植物への接触を仮想植物の成長へ接続し、*A-Volve*では観客が描いた形から人工生命を生み出しました。学習モデル以前の作品ですが、身体入力、予測不能性、人工生命、生態系的展示という、後のAIインスタレーションに続く問題を明確にしています。

- [NTT ICC: Interactive Plant Growing](https://www.ntticc.or.jp/en/exhibitions/1994/interactive-plant-growing-christa-sommerer-laurent-mignonneau/)
- [作家公式アーカイブ](https://interface.ufg.ac.at/christa-laurent/)
- [Archive of Digital Art](https://www.archive-digitalart.eu/database/general/work/interactive-plant-growing.html)

### Karl Sims: 形態だけでなく運動を進化させる

既収録の*Galápagos*に加え、Simsの*Evolved Virtual Creatures*（1994）は、仮想生物の身体構造と制御を進化させました。進化芸術を「奇妙な形の生成」に限定せず、環境における行動、適応、観察者が評価するスペクタクルまで含めて理解できます。[Karl Sims公式アーカイブ](https://www.karlsims.com/)

## 横断して考える問い

- 明示的な規則と、データから獲得された統計的パターンは、作者の責任をどう変えるか。
- 自律性は技術的性質なのか、それとも展示・言説・観客によって帰属される性質なのか。
- 見栄え、意外性、意図、過程、社会的影響のうち、何を創造性評価の中心に置くべきか。

## 次に読む

- [ニューラル画像生成]({{ '/ja/topics/neural-image-generation/' | relative_url }}) - 規則中心の生成から学習中心の生成への変化
- [人間・機械協働と身体的実践]({{ '/ja/topics/human-machine-collaboration/' | relative_url }}) - 自律した作者ではなく共演者としての機械
- [批評、権利、来歴]({{ '/ja/topics/critique-rights-provenance/' | relative_url }}) - 作者性を法・労働・流通から捉え直す
