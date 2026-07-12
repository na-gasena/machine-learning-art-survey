# Machine Learning Art Survey

## 日本語

このリポジトリは、「機械学習に関連したアート・パフォーマンス・創作活動など」を対象にした公開可能なサーベイです。AIアートをひとつの固定ジャンルとして扱うのではなく、調査から見えてきた複数の流れ、つまり記号的AIとコンピュータアート、ニューラルネットワークによる画像生成、音楽・パフォーマンスのインタラクティブ機械学習、データセットと美術史、批評的データセット実践、著作権・来歴・同意の制度的課題を整理しています。

調査では、一次情報や信頼できる研究資料を優先し、確認が弱い項目は `confidence` を Medium または Low として扱う方針にしました。作品、論文、データセット、ソフトウェア、展覧会、標準、組織は `_data/items.yml` に item として記録しています。

## English Overview

This repository is a GitHub Pages-ready survey on machine-learning-related art, performance, and creative practice. Rather than assuming that "AI art" is a single stable category, the survey organizes what emerged from research: symbolic AI and computer art histories, neural image generation, interactive machine learning for music and performance, datasets and computational art history, critical dataset practice, and institutional questions around copyright, consent, provenance, and labor.

The survey prioritizes primary sources and reliable research materials. Items with weaker verification are marked with lower confidence. Papers, artworks, datasets, tools, exhibitions, standards, organizations, and concepts are recorded as structured items in `_data/items.yml`.

## Survey Scope

The survey includes:

- Research papers and surveys on computational creativity, generative models, style transfer, datasets, and artist opinions.
- Artworks and projects using AI or machine learning as medium, collaborator, instrument, dataset critique, or institutional question.
- Creative tools and datasets such as Wekinator, Magenta, NSynth, ImageNet, WikiArt, LAION-5B, and ArtEmis.
- Institutions and venues including Ars Electronica, SIGGRAPH, NIME, Barbican, MoMA, Whitney, and related labs.
- Open questions around authorship, consent, style mimicry, provenance, public trust, environmental cost, and evaluation.

The survey does not claim completeness. It is a structured starting point that preserves source URLs and flags uncertain areas.

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
