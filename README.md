# Machine Learning Art Survey

## 日本語

このリポジトリは、「機械学習に関連したアート・パフォーマンス・創作活動など」を対象にした公開サーベイです。AIアートをひとつの固定ジャンルや「画像生成AIによる絵」に限定せず、作品、研究、制作技術、ソフトウェア、データセット、展覧会、人物、組織、政策、保存問題を相互に参照できる形で整理しています。

調査では、作家・美術館・研究機関・標準化団体・政府の一次資料と査読論文を優先し、確認が弱い項目は `confidence` を Medium または Low として扱います。検索結果の見出しだけで内容を決めず、可能な範囲で作品ページ、映像、論文本文、データ配布ページ、展覧会記録を確認しました。作品、論文、データセット、ソフトウェア、展覧会、標準、歴史的事例は `_data/items.yml` に共通のitemとして記録しています。

## 現在の分野構成

初期分類を固定せずに調査した結果、現在は次の11領域で整理しています。

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

この分類は排他的ではありません。たとえばLiving Archiveは、ダンス、身体アーカイブ、共同制作、保存、データ権利にまたがります。各項目を一つの箱へ閉じ込めるのではなく、[日本語の分野地図](ja/survey-map.md)でカテゴリ間の接続と境界領域を説明しています。

## 調査範囲

このサーベイは、次の対象を含みます。

- 計算論的創造性、生成モデル、スタイル変換、データセット、作家意識、著作権、来歴に関する研究論文とサーベイ。
- AIまたは機械学習を、媒体、共同制作者、楽器、批評対象、展示システム、アーカイブ装置として扱う作品やプロジェクト。
- Wekinator、Magenta、NSynth、ml5.js、Teachable Machine、Runway、Stable Diffusion、Glaze、C2PAなどの創作ツール・技術・標準。
- ImageNet、WikiArt、LAION-5B、ArtEmis、ArtBench、BAM、NSynthなどのデータセット。
- OmniArt、SemArt、ArtGraph、Met、Rijksmuseum、Smithsonian、MoMAなどの研究・美術館データ基盤と、その配布停止・版管理・権利問題。
- Ars Electronica、SIGGRAPH、NIME、ICCC、Barbican、MoMA、Whitney、Serpentine、DATALANDなど、研究・展示・制作コミュニティをつなぐ組織や会場。
- Love Letters、Illiac Suite、Cybernetic Serendipityから、AI文学、CG映画、ゲーム的シミュレーション、ダンス、ロボット音楽、オンライン展覧会、ソフトウェア保存までの歴史。
- 作者性、同意、補償、スタイル模倣、文化的偏り、環境負荷、AI生成表示、データ主権、公共性に関する未解決問題。

このサーベイは完全なリストではありません。日本語・英語資料に加えて、チェコ語・フランス語・ポルトガル語の制度資料や、東アジア、東南アジア、南アジア、アフリカ、トルコ、ラテンアメリカ、先住民・ディアスポラの実践へ範囲を広げました。ただし現地語の口頭資料、短命なSNSアーカイブ、中東・アフリカ諸言語の一次資料は依然として不足しています。未確認情報は断定せず、監査報告と未解決問題へ残します。

## リポジトリ構成

```text
README.md
index.md
_config.yml
LICENSE
references.bib
_data/
ja/
en/
templates/
assets/css/style.css
audit-report.md
```

日本語ページは `ja/`、英語ページは `en/` に置いています。両言語版は、できるだけ対応するファイル名と見出し構造にしています。公開サイトでは、日英を1行ずつ交互に併記せず、ページまたはセクション単位で分けています。

## 読み方

まず次のページから読むと全体像をつかみやすいです。

- [日本語版トップ](ja/)
- [English overview](en/)
- [日本語の分野地図](ja/survey-map.md)
- [English survey map](en/survey-map.md)
- [作品アーカイブとメディアリンク](ja/resources/works-archive.md)

次に、関心のあるトピックページを読んでください。構造化データは `_data/items.yml`、`_data/sources.yml`、`_data/people.yml`、`_data/organizations.yml`、`_data/venues.yml`、`_data/datasets.yml`、`_data/keywords.yml` にあります。

各トピックページは、短い要約、読むための問い、系譜、比較表、重要項目、横断的論点、作品アーカイブの順に揃えています。作品の実物・映像・展示記録を先に見たい場合は、[作品アーカイブとメディアリンク](ja/resources/works-archive.md)から読むと効率的です。

## GitHub Pagesでの公開方法

このリポジトリは、GitHub Pagesの標準Jekyllビルドを前提にしています。

1. GitHubにpushします。
2. Repository settingsを開きます。
3. Pagesへ進みます。
4. "Deploy from a branch" を選びます。
5. ブランチを `main`、公開元をリポジトリルート `/` に設定します。

MkDocs、Docusaurus、Next.js、Vite、GitHub Pages非対応のJekyll plugin、`.nojekyll` は不要です。

## 参考文献とデータファイル

文献情報は `references.bib` に、構造化された調査記録は `_data/` にあります。各 item には、可能な範囲で一次情報または信頼できる情報源URLを残しています。作品画像は原則としてコピーせず、作家・美術館・プロジェクトが公開しているページや画像URLへリンクします。

## English Overview

This repository is a GitHub Pages-ready survey on machine-learning-related art, performance, and creative practice. Rather than assuming that "AI art" is a single stable category, the survey uses eleven research-derived areas: computer-art history; neural image generation; music and interactive ML; embodied collaboration; datasets and computational art history; critique, rights, and provenance; creative tools; regional and critical practice; language and narrative; moving image, games, and spatial media; and exhibitions, markets, institutions, and preservation.

The survey prioritizes primary sources and reliable research materials. Items with weaker verification are marked with lower confidence. Papers, artworks, datasets, tools, exhibitions, standards, organizations, and concepts are recorded as structured items in `_data/items.yml`.

The categories overlap by design. The survey map explains relations and boundary cases rather than forcing every work into one exclusive medium or method.

## Survey Scope

The survey includes:

- Research papers and surveys on computational creativity, generative models, style transfer, datasets, and artist opinions.
- Artworks and projects using AI or machine learning as medium, collaborator, instrument, dataset critique, or institutional question.
- Creative tools and datasets such as Wekinator, Magenta, NSynth, ImageNet, WikiArt, LAION-5B, and ArtEmis.
- Institutions and venues including Ars Electronica, SIGGRAPH, NIME, Barbican, MoMA, Whitney, Serpentine, DATALAND, and related labs.
- Open questions around authorship, consent, style mimicry, provenance, public trust, environmental cost, and evaluation.

The survey does not claim completeness. It is a structured starting point that preserves source URLs and flags uncertain areas while expanding beyond Japanese and English sources toward Chinese-language contexts, Korea, Europe, Turkey, Argentina, Senegal, Nigeria, Singapore, Mexico, African-diasporic practice, and queer/feminist AI critique.

## Repository Structure

```text
README.md
index.md
_config.yml
LICENSE
references.bib
_data/
ja/
en/
templates/
assets/css/style.css
audit-report.md
```

Japanese pages are under `ja/`; English pages are under `en/`. The two language trees use matching filenames and similar heading structures where possible.

## How to Read This Survey

Start with:

- [Japanese overview](ja/)
- [English overview](en/)
- [Japanese survey map](ja/survey-map.md)
- [English survey map](en/survey-map.md)
- [Works archive and media links](en/resources/works-archive.md)

Then read topic pages according to interest. Structured data can be inspected directly in `_data/items.yml`, `_data/sources.yml`, `_data/people.yml`, `_data/organizations.yml`, `_data/venues.yml`, `_data/datasets.yml`, and `_data/keywords.yml`.

## How to Publish with GitHub Pages

This repository is designed for the standard GitHub Pages Jekyll build.

1. Push this repository to GitHub.
2. Open repository settings.
3. Go to Pages.
4. Choose "Deploy from a branch."
5. Select the branch and repository root as the source.

No MkDocs, Docusaurus, Next.js, Vite, custom unsupported Jekyll plugins, or `.nojekyll` file are required.

## References and Data Files

Bibliographic entries are in `references.bib`. Structured survey records are in `_data/`. Source URLs are preserved in each item and source record. Unknown or weakly confirmed information is marked in notes or confidence fields rather than asserted as fact.
