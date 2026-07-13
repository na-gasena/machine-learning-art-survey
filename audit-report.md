---
layout: default
title: Audit Report
permalink: /audit-report/
---

# Audit Report

最終増補監査日: 2026-07-14

## 監査概要

本サーベイは、初期カテゴリを固定せず、検索語の拡張、一次資料の確認、項目比較、分類の再編、日英ページ作成、構造化データ同期、公開構成検査の順で作成した。今回の増補では、画像生成に偏っていた構成を見直し、計算文学、アルゴリズム作曲、進化芸術、人工生命、ダンス、演劇、ロボット、CG映画、ライブ・シミュレーション、展覧会史、市場、ソフトウェア保存、非英語圏・先住民・ディアスポラの実践を拡張した。

2026-07-14時点の構造化データ件数:

- items: 122
- sources: 81
- people: 98
- organizations: 99
- venues: 20
- datasets: 18
- keywords: 34
- BibTeX entries: 36
- 日英トピック: 各11ページ

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

### 検索語の拡張

広い検索語 `machine learning art`、`AI art`、`creative AI` から始め、発見した作品・研究・制度から次の語へ展開した。

- computer art, cybernetic art, algorithmic composition, computational literature
- evolutionary art, artificial life art, interactive installation, live simulation
- neural style transfer, GAN, image-to-image translation, CLIP, diffusion, latent space
- interactive machine learning, machine listening, robotic music, AI choreography, AI theatre
- computational art history, museum open data, multimodal art dataset, knowledge graph
- training data provenance, artist consent, style mimicry, data poisoning, content credentials
- Indigenous AI, colonial taxonomy, restitution, Sinofuturism, Afropean intelligence
- software-art conservation, AI exhibition history, auction, collection, emulation

### 主な発見

1. 機械学習アートは、画像生成の技術史だけでは説明できない。Love Letters、Illiac Suite、Cybernetic Serendipity、AARON、Mutator、Interactive Plant Growingは、言語、音楽、展示、進化、身体入力の別系譜を示す。
2. 音楽・舞台では完成物よりリアルタイムの応答、遅延、俳優・演奏家・ダンサーの修復労働が重要である。
3. AI文学・映像では「AIが書いた」という広報文言と、選択、編集、翻訳、演出、出演、撮影、出版の工程を分ける必要がある。
4. データセットは内容だけでなく配布状態も変化する。OmniArt公式ページは2025年以降の配布停止を記録しており、論文が残っても再現資源が消える問題を示す。
5. 権利問題は、訓練データ監査、作家のオプトアウト、防御ツール、著作権法、生成物来歴を別の段階として整理する必要がある。
6. 地域的実践は国籍別の付録ではない。Kite、Harshit Agrawal、Giselle Beiguelman、Lawrence Lek、Minne Atairu、Linda Dounia Rebeizらは、親族関係、植民地分類、返還、地域データ、言語、制度を技術設計と結びつける。

### 不確かなこと

- 作品ページが技術実装を公開していない場合、機械学習の具体的役割は `Unknown` または Medium confidenceにとどめた。
- Racterの生成範囲、編集、宣伝上の自律性主張には論争がある。
- 「コンピュータが小説を書く日」は詳細な日本語インタビューを確認したが、長期保存された一次プロジェクトサイトが見つかっていない。
- Niceaunties、Linda Dounia Rebeiz、Afropean Intelligenceなど進行中・SNS依存の実践は、安定した制度アーカイブが不足する。
- 最新の法、訴訟、モデル利用規約、クラウド機能は更新されるため、固定的結論として扱えない。

## Phase 2: Taxonomy / 分類

### 確定した11トピック

1. 歴史、記号的AI、コンピュータアート
2. ニューラル画像生成
3. 音楽、パフォーマンス、インタラクティブ機械学習
4. 人間・機械協働と身体的実践
5. データセット、美術史、機械知覚
6. 批評、権利、来歴
7. 制作ツール、教育、プラットフォーム
8. 地域・文化・批評的実践
9. 言語、文学、物語生成
10. 映像、ゲーム、空間的メディア
11. 展覧会史、制度、市場、保存

### 分類変更の根拠

旧版では8分類だったが、調査項目を増やすと次の三群を既存ページへ埋め込むだけでは比較しにくかったため、独立トピックにした。

- 言語・文学・物語: 出力テキスト、編集、翻訳、出版、上演の工程を画像生成と別に分析する必要がある。
- 映像・ゲーム・空間: 時間、状態、エージェント、観客入力、展示装置を静止画像と別に扱う必要がある。
- 展覧会・制度・市場・保存: 作品の権利問題と、分類・展示・収蔵・再演を行う機関の問題を分離する必要がある。

カテゴリは排他的ではない。Living Archiveはダンス、身体データ、共同制作、アーカイブ、保存にまたがり、BOBは人工生命、ゲーム的シミュレーション、展示、収蔵にまたがる。境界領域は `ja/survey-map.md` と `en/survey-map.md` に明記した。

## Phase 3: Item Notes / 個別要約

### ページ構造

日英11トピックを、次の順序へ統一した。

1. このページの結論 / Conclusion
2. 押さえる3点 / Three Points
3. 比較できる見取り図 / Comparison Map
4. 系譜または論点の流れ
5. 代表項目
6. 横断的な問い
7. 作品アーカイブ・次に読む

個別項目は、同じ長さのカードを縦に並べる形式をやめ、系譜と比較軸を先に示した。日本語版を主文として英語版より詳しくし、両言語でファイル名と見出しの役割を対応させた。

### 追加した主要項目

- 歴史: Love Letters、Illiac Suite、Cybernetic Serendipity、Mutator、Interactive Plant Growing、Evolved Virtual Creatures
- 画像: pix2pix、CycleGAN、StyleGAN、CLIP、VQGAN、DDPM、Latent Diffusion、Artbreeder、GauGAN
- 音・身体: Continuator、DeepBach、Flow Machines、Shimon、Dadabots、FluCoMa、Living Archive、discrete figures、Improbotics、Alter3、Android Opera
- 言語: Racter、Sunspring、1 the Road、Please Feed the Lions、コンピュータが小説を書く日、THEaiTRE
- 映像・空間: BOB、UUmwelt、AIDOL、This is the Future、In Love With the World、Zoom Pavilion、Archive Dreaming
- 地域: Kite、Harshit Agrawal、Botannica Tirannica、Lawrence Lek、Afropean Intelligence
- データ: OmniArt、SemArt、ArtGraph、Met、Rijksmuseum、Smithsonian、MoMA、National Gallery of Art
- 権利・制度: Nightshade、Have I Been Trained?、Data Provenance Initiative、米国著作権局報告、EU訓練内容サマリー、C2PA 2.2
- 展覧会・保存: SIGGRAPH Digital Art Archive、AI: More than Human、Ars Electronica 2019、Neurones、Uncanny Valley、Run the Code、Christie's 2018 auction、Guggenheim CCBA

## Phase 4: Synthesis and Publication / 統合と公開準備

### 公開構成

- ルートに `index.md` と `_config.yml` が存在する。
- `theme: minima` と `markdown: kramdown` を使用する。
- `.nojekyll`、外部静的サイトジェネレータ、GitHub Pages非対応pluginは使用しない。
- 日本語は `ja/`、英語は `en/` に分け、1行ごとの日英併記をしない。
- すべての公開MarkdownにYAML front matterと一意のpermalinkがある。
- 内部リンクにはJekyllの `relative_url` を使い、project siteのbase URLに対応する。

### 作品・資料へのアクセス

`ja/resources/works-archive.md` と英語対応ページを約70項目規模へ拡張した。作家、美術館、大学、劇場、フェスティバル、論文、公式コードへのURLを分け、オンライン画像・映像があるページを優先した。外部画像を本リポジトリへ無断複製せず、既存の公式画像参照と公式メディアページへのリンクを用いる。

`datasets-and-resources.md` は、美術画像、美術館オープンデータ、人物・身体、画像テキスト、音響、制作ツール、権利・来歴に再分類した。配布停止、商用サービス変更、画像権利、文化的機微を項目ごとに記載した。

## Phase 5: Audit / 監査

### 機械検査結果

- `_data/*.yml` の全ID重複検査: 重複2件を検出し、旧レコードを削除。修正後は全ファイルで一意。
- `items.yml` 必須21フィールド検査: 122件すべてに存在。
- `related_people` / `related_organizations` 参照検査: 未登録ID 0件。
- 公開Markdown検査: 33ファイルすべてにfront matterとpermalinkが存在。
- permalink重複: 0件。
- `relative_url` 内部リンク: 参照先不明0件。
- 日英トピックファイル対応: 11対11で一致。
- 日本語作品・資料ページ外部URL: 173件をHTTP検査。139件が200/300、6件がbot対策応答、28件が初回タイムアウトまたは失敗候補。実404 2件と旧QA URL等を再調査し、CycleGAN、Zizi、Linda Dounia Rebeiz、PROTOの安定した公式URLへ置換した。
- トピック本文固有URL: 差分28件を検査し、23件到達、3件bot対策、2件タイムアウト。Goldsmithsはブラウザ取得で確認し、到達しないThe Painting Fool公式サイトはICCCの機関保存論文へ置換した。
- 埋め込み外部画像: 8件すべてHTTP 200を確認した。
- 初回本番DOM監査で、Kramdownが作品・資料ページの裸URLを自動リンク化していないことを検出。日英4ページの348行を明示的なMarkdown自動リンクへ変換し、長いURLへ `overflow-wrap: anywhere` を適用した。既存閲覧者へ更新済みCSSを確実に配信するため、スタイルシートURLへ版クエリも追加した。
- YAML/Jekyll実ビルド: GitHub Pages Actions run `29267179058` でJekyll buildとdeployが成功。
- 公開permalink: 33ページを本番URLで順次取得し、33/33がHTTP 200。
- 公開DOM: 日本語トップに11トピックリンクを確認。作品アーカイブは78項目、外部リンク131本、画像8/8表示、横スクロールなしを確認。

### 15項目監査

1. **重要項目の抜け:** 初期版の画像偏重を大きく改善した。完全網羅ではなく、残課題を下記に記録する。
2. **地域・言語・時代の偏り:** 日本語・英語に加え、チェコ語、フランス語、ポルトガル語の公式資料を含めた。中東・アフリカ諸言語は不足する。
3. **カテゴリ根拠:** 122 itemの媒体、方法、時間性、制度文脈の比較から11分類へ更新した。
4. **タイトル・人物・年・URL:** 主要項目は一次資料または研究論文で確認。不確かなものはMedium confidenceまたはnotesへ記録した。
5. **README・index・日英整合:** 11分類へ同期した。
6. **BibTeX対応:** 主要技術論文、調査論文、政策資料を36件収録。作品・展覧会の一次ページは主にsources.ymlへ収録した。
7. **itemsと本文対応:** 代表事例と新規トピックの中心項目をitems.ymlへ追加した。
8. **リンク:** 内部リンク検査は合格。外部URLは調査時に閲覧したが、将来の永続性は保証できない。
9. **事実と推測:** 技術非公開、生成範囲に論争、進行中の事例を明示した。
10. **歴史と最新動向:** 1952年のLove Lettersから2026年時点の公開制度・保存課題まで含む。
11. **隣接分野:** 人工生命、HCI、計算文学、音楽情報検索、ゲームAI、博物館情報、保存科学との境界を説明した。
12. **日英構造:** ファイル名と主要見出しの役割を対応。日本語優先のため日本語本文は英語版より詳しい。
13. **Jekyll構成:** 標準GitHub Pages構成を維持。
14. **indexとconfig:** 両方存在。
15. **特殊依存:** なし。

## 修正できない問題・残課題

- 中東、北アフリカ、中央アジア、太平洋地域、アフリカ諸言語の一次資料と地域内展示アーカイブが不足する。
- ゲーム制作はライブ・シミュレーションと空間メディアから入口を作ったが、商用ゲームの制作工程、mod、プレイヤー共同制作、ゲーム保存は十分でない。
- ファッション、建築、工芸、障害のある作家によるアクセシビリティ実践は独立した比較が不足する。
- SNSのみで公開される作品、上演のみの舞台、閉鎖済みサイトは証拠の永続性が弱い。
- 外部画像は公式サイトの変更、ホットリンク制限、利用規約変更で表示されなくなる可能性がある。
- 法、訴訟、モデルライセンス、サービス機能、データセット公開状態は継続更新が必要である。

## 次回監査候補

- 日本のICC、YCAM、IAMAS、NTT ICC、文化庁メディア芸術祭のAI関連作品を年次・展覧会単位で再調査する。
- スペイン語、アラビア語、韓国語、中国語、アフリカ諸言語の現地語検索と制作者への聞き取りを行う。
- ゲーム、建築、ファッション、工芸、アクセシビリティを横断する独立セクションの必要性を再評価する。
- 外部URL、データセット配布状態、作品実行環境、法政策を定期検査する。
- 作品画像を追加する場合、安定したIIIF、Wikimedia Commons、明示的ライセンス付き機関画像を優先する。
