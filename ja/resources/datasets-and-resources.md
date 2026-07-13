---
layout: default
title: データセット・ツール・資料
permalink: /ja/resources/datasets-and-resources/
---

# データセット・ツール・資料

## データセット

### 美術画像・美術史・意味記述

- **WikiArt**: 様式分類やGAN/CAN研究で多用される集約サイト。作品ごとに権利状況が異なるため、「データセット名が公開されている」ことと再利用許諾を分けて確認する。https://www.wikiart.org/
- **OmniArt**: 作品画像と作者、年代、様式など複数属性を結ぶ。公式ページは2025年以降データセットを配布していないと表示しており、論文の再現性に影響する。https://isis-data.science.uva.nl/strezoski/
- **SemArt**: 美術画像と説明テキストを結ぶデータセット。Aston UniversityのリポジトリにDOI、ファイル、メタデータがある。https://researchdata.aston.ac.uk/id/eprint/380/
- **ArtGraph**: 作品、作家、様式、ジャンルなどを知識グラフとして表現する。Zenodoに版とライセンスを伴う記録がある。https://zenodo.org/records/6337958
- **ArtEmis**: 美術作品と感情カテゴリ・自然言語説明を結びつける。感情ラベルを普遍的反応とみなさず、注釈者と文化的文脈を確認する。https://www.artemisdataset.org/
- **ArtBench-10**: 美術画像生成モデルを比較する10クラスのベンチマーク。著者のFair Use説明と、下流利用者自身の権利判断を区別する。https://github.com/liaopeiyuan/artbench
- **BAM! Behance Artistic Media Dataset**: Behance由来の作品を用いた媒体・内容・感情ラベル。作家ポートフォリオの再利用条件を確認する。https://arxiv.org/abs/1704.08614

### 美術館オープンデータ

- **The Met Collection API**: 作品メタデータとパブリックドメイン画像の公式API。オブジェクトごとの `isPublicDomain` と画像有無を確認する。https://metmuseum.github.io/
- **Rijksmuseum Data Services**: API、Linked Open Data、ダウンロード、IIIFを提供。https://data.rijksmuseum.nl/
- **Smithsonian Open Access**: 美術、歴史、科学、文化を横断する大規模資源。オープンアクセスでも文化的機微や先住民データ主権は別途検討する。https://www.si.edu/OpenAccess
- **MoMA Collection Data**: 作品・作家メタデータをGitHubで公開。画像の再利用許諾とは別であり、収蔵全体の完全な記録でもない。https://github.com/MuseumofModernArt/collection
- **National Gallery of Art Open Data**: コレクションと関係者の公式データ出力。版、項目定義、画像権利を保持して利用する。https://github.com/NationalGalleryOfArt/opendata

### 視覚認識、顔、身体

- **ImageNet**: 視覚認識研究の基盤であり、ImageNet Rouletteなど分類批評の対象でもある。人物カテゴリの歴史、語彙、画像収集方法を確認する。https://www.image-net.org/
- **People-Art / Human-Art**: 絵画・人工シーンにおける人物検出や姿勢推定に関わる。https://arxiv.org/abs/1610.08871 / https://arxiv.org/abs/2303.02760
- **FFHQ**: 顔生成・GAN史で重要な顔画像データセット。生体情報、同意、Flickrからの再利用、派生モデルを追跡する。https://github.com/NVlabs/ffhq-dataset

### 画像テキストと音響

- **LAION-5B**: 大規模画像テキスト索引。URL、キャプション、フィルタリング、同意、プライバシー、有害コンテンツ、削除後の派生モデルが中心課題になる。https://arxiv.org/abs/2210.08402
- **NSynth**: 注釈付き音楽単音データセット。音色補間・音響生成の基礎資源だが、元の商用サンプルライブラリと配布ライセンスを確認する。https://magenta.tensorflow.org/datasets/nsynth

## ツール

### 入力例から自分のモデルを作る

- **Wekinator**: ジェスチャー、音、センサー入力と出力の対応を実演しながら学習するインタラクティブ機械学習。https://doc.gold.ac.uk/~mas01rf/Wekinator/
- **ml5.js**: ブラウザとp5.jsで機械学習を扱う教育・制作ライブラリ。https://ml5js.org/
- **Teachable Machine**: コードなしで画像、音、姿勢の分類モデルを試作できる。https://teachablemachine.withgoogle.com/
- **ml4a**: Gene Koganによるアーティスト向け教材とコード例。更新時期と依存ライブラリの互換性を確認する。https://ml4a.github.io/

### 音、音楽、ライブ制作

- **Magenta**: 音楽・アート向け研究・ツールの歴史的プロジェクト。個別ツールの保守状況は別々に確認する。https://magenta.tensorflow.org/
- **FluCoMa**: 自分の音素材を分析、分解、クラスタリング、検索するMax/Pure Data/SuperCollider向けツール群。https://www.flucoma.org/
- **Flow Machines**: AI支援作曲・制作環境。提供地域や製品状態が変化するため公式情報を確認する。https://www.sony.com/en/SonyInfo/design/stories/flow-machines/

### 画像・映像の生成と編集

- **Stable Diffusion**: オープンウェイト系テキスト画像生成エコシステムの基点。モデルカード、ライセンス、派生チェックポイント、使用データを版ごとに確認する。https://github.com/CompVis/stable-diffusion
- **Artbreeder**: 画像混合、パラメータ操作、派生関係を扱うウェブ環境。https://www.artbreeder.com/about
- **Runway**: 生成動画・映像制作向け商用プラットフォーム。モデル版、料金、クラウド保存、利用規約は変更される。https://runwayml.com/

### 権利、同意、来歴

- **Glaze**: 作家のスタイル模倣を難しくする防御ツール。https://glaze.cs.uchicago.edu/
- **Nightshade**: 無断訓練を妨げることを目指すデータポイズニング型ツール。Glazeと目的・評価条件を分ける。https://nightshade.cs.uchicago.edu/whatis.html
- **Have I Been Trained?**: 訓練データセットの検索と利用方針表明。https://haveibeentrained.com/
- **C2PA 2.2**: 生成・編集・配布履歴を署名付きマニフェストで扱う仕様。真偽判定器ではない。https://spec.c2pa.org/specifications/specifications/2.2/index.html

## 主要資料

- Creativity and Machine Learning: A Survey: https://arxiv.org/abs/2104.02726
- The Machine Learning Algorithm as Creative Musical Tool: https://arxiv.org/abs/1611.00379
- Foregrounding Artist Opinions: https://arxiv.org/abs/2401.15497
- U.S. Copyright Office AI reports: https://www.copyright.gov/policy/artificial-intelligence/
- Understanding and Creating Art with AI: https://arxiv.org/abs/2102.09109
- Art and the science of generative AI: https://arxiv.org/abs/2306.04141
- Can Computers Create Art?: https://arxiv.org/abs/1801.04486
- EU AI Act overview: https://digital-strategy.ec.europa.eu/en/policies/regulatory-framework-ai
- EU AI Act training-content summary template: https://digital-strategy.ec.europa.eu/en/faqs/template-general-purpose-ai-model-providers-summarise-their-training-content
- Data Provenance Initiative: https://www.dataprovenance.org/
- SIGGRAPH Digital Art Archive: https://digitalartarchive.siggraph.org/
- Guggenheim Conserving Computer-Based Art Initiative: https://www.guggenheim.org/conservation/the-conserving-computer-based-art-initiative
- 作品アーカイブとメディアリンク: {{ '/ja/resources/works-archive/' | relative_url }}

## 利用上の注意

データセットやモデルを再利用する場合は、ライセンス、対象画像・音声の権利、人物データの同意、地域法、公開時の表示義務を個別に確認してください。とくにLAION-5B、WikiArt派生データ、人物画像を含むデータセットは、研究利用であっても倫理・権利上の検討が必要です。
