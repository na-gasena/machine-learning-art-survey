---
layout: default
title: Audit Report
permalink: /audit-report/
---

# Audit Report

## Phase 1: Research / 調査

### 作成・更新したファイル

- `_data/items.yml`
- `_data/sources.yml`
- `_data/people.yml`
- `_data/organizations.yml`
- `_data/venues.yml`
- `_data/datasets.yml`
- `_data/keywords.yml`
- `references.bib`

### 発見したこと

広い検索語から、AI art、computational creativity、creative AI、neural style transfer、DeepDream、GAN、Creative Adversarial Networks、diffusion models、text-to-image、interactive machine learning、machine learning for artists and musicians、dataset politics、provenance、artist rights などの関連語が見つかった。

重要 item は、AARON、The Painting Fool、DeepDream、A Neural Algorithm of Artistic Style、GAN、CAN、ArtGAN、Latent Diffusion、DALL-E、Stable Diffusion、Wekinator、Magenta、NSynth、Learning to See、Mosaic Virus、Drawing Operations、Holly+、ImageNet、WikiArt、LAION-5B、ArtEmis、ImageNet Roulette、Glaze、C2PA、U.S. Copyright Office AI reports など。

### 不確かなこと

作品の技術詳細は、作家サイト・展示解説・報道で記述粒度が異なる。Holly+、PROTO/Spawn、Memories of Passersby I、Large Nature Model/Dataland などは、技術実装の詳細が限定的または更新中である。

### 次Phaseへの反映方針

技術中心、作品中心、制度中心の分類を最初から固定せず、集まった item の用途、媒体、歴史、社会的争点から分類を作った。

## Phase 2: Taxonomy / 分類

### 作成・更新したファイル

- `ja/survey-map.md`
- `en/survey-map.md`

### 発見したこと

自然な分類として、次の6カテゴリが安定した。

- 歴史、記号的AI、コンピュータアート
- ニューラル画像生成
- 音楽、パフォーマンス、インタラクティブ機械学習
- 人間・機械協働と身体的実践
- データセット、美術史、機械知覚
- 批評、権利、来歴、制度

### 不確かなこと

没入型AI展示は、作品、研究デモ、企業ブランディング、文化施設運営の境界にある。商業デザインやゲームアセット生成は、本サーベイの中心に入れるか今後判断が必要。

### 次Phaseへの反映方針

topicファイル名は、調査で安定した分類に合わせて決定した。

## Phase 3: Item Notes / 個別要約

### 作成・更新したファイル

- `ja/topics/history-symbolic-computer-art.md`
- `en/topics/history-symbolic-computer-art.md`
- `ja/topics/neural-image-generation.md`
- `en/topics/neural-image-generation.md`
- `ja/topics/music-performance-interactive-ml.md`
- `en/topics/music-performance-interactive-ml.md`
- `ja/topics/human-machine-collaboration.md`
- `en/topics/human-machine-collaboration.md`
- `ja/topics/datasets-art-history-machine-vision.md`
- `en/topics/datasets-art-history-machine-vision.md`
- `ja/topics/critique-rights-provenance.md`
- `en/topics/critique-rights-provenance.md`

### 発見したこと

重要 item は、作品単体よりも、技術・データ・制度・観客経験の組み合わせとして理解する方が正確である。たとえば Stable Diffusion はモデルであると同時に、コミュニティ、ライセンス、UI、派生モデル、データ論争を含むエコシステムである。

### 不確かなこと

最新のDataland関連情報、モデルの現行ライセンス、各プラットフォームのC2PA対応、AI著作権訴訟は変化しやすい。今後の更新が必要。

### 次Phaseへの反映方針

各 topic では、事実、重要性、手法、歴史的文脈、制限を分けて記述した。

## Phase 4: Synthesis and Publication / 統合と公開準備

### 作成・更新したファイル

- `README.md`
- `index.md`
- `_config.yml`
- `LICENSE`
- `templates/item-card.md`
- `templates/topic-page.md`
- `assets/css/style.css`
- `ja/index.md`
- `en/index.md`
- `ja/resources/datasets-and-resources.md`
- `en/resources/datasets-and-resources.md`
- `ja/open-questions.md`
- `en/open-questions.md`

### 発見したこと

GitHub Pagesの標準Jekyll構成では、ルートの `index.md` と `_config.yml` があれば公開入口を作れる。日本語と英語は、行単位で混在させず、ページ単位またはセクション単位で分けた。

### 不確かなこと

Minimaテーマで `assets/css/style.css` を自動読み込みするかはテーマバージョンに依存する。サイト本体はCSSに依存しない素朴なMarkdownとして読める。

### 次Phaseへの反映方針

公開不能な外部ビルドツール、未対応プラグイン、`.nojekyll` は使わない。

## Phase 5: Audit / 監査

### 監査結果

- 重要 item の抜け: 初期版として主要な歴史・技術・作品・制度は含めたが、地域的偏りが残る。
- 地域・言語・時代の偏り: 英語圏・欧米圏資料への偏りがある。日本語圏、東アジア、南アジア、アフリカ、ラテンアメリカの拡張が必要。
- カテゴリ名: Phase 1で発見した item のまとまりに基づく。
- タイトル、人物名、年、URL: 主要項目は一次情報または信頼できる資料で確認した。更新されやすい項目は notes に記録。
- README、index、ja、enの矛盾: 基本構造は一致。
- references.bib: 本文で扱う主要論文を含む。作品・標準・政策資料はBibTeX化していないものがある。
- `_data/items.yml` と本文: 代表 item は本文に対応。
- リンク切れ: 自動HTTP検査は未実施。URLは調査時に参照済み。
- 推測の断定: 不確実な項目は Medium confidence または notes に記録。
- 歴史と最新動向のバランス: AARONから2026年時点のDataland/C2PA論点まで含めた。
- 隣接分野との境界: survey map に境界領域を記載。
- 日英構造: 主要ページは対応するファイル名・見出し構造にした。
- GitHub Pages構成: ルートに `index.md` と `_config.yml` が存在し、外部静的サイトジェネレータに依存しない。
- 特殊plugin: 使用なし。

### 修正できない問題・残課題

- 非英語圏の作品・資料が不足している。
- AI映画、ダンス、舞台芸術、ファッション、建築、ゲーム制作の item が不足している。
- 作品の技術実装が非公開の場合、詳細は Unknown または Medium confidence にとどめた。
- 最新の訴訟、政策、モデルライセンス、データセット公開状況は継続監視が必要。
- 自動リンクチェッカーはネットワーク制約と時間のため未実施。

### 今後追加すべき item 候補

- Karl Sims, Galapagos
- Scott Draves, Electric Sheep
- Stephanie Dinkins, Conversations with Bina48
- Lauren Lee McCarthy, LAUREN and related AI/social performance work
- Lynn Hershman Leeson and earlier interactive agents
- Japanese and East Asian AI/media art exhibitions and artists
- Dance/performance projects using pose estimation or generative models
- AI film and animation production pipelines
- Nightshade and other artist-protection tools
- EU AI Act and non-U.S. copyright/policy developments
