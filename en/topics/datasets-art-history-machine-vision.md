---
layout: default
title: Datasets, Art History, and Machine Vision
permalink: /en/topics/datasets-art-history-machine-vision/
lang: en
---

[← Field Map]({{ '/en/survey-map/' | relative_url }}) · [Datasets and Resources]({{ '/en/resources/datasets-and-resources/' | relative_url }})

# Datasets, Art History, and Machine Vision

<div class="topic-lead" markdown="1">
## Conclusion

A dataset for machine-learning art is not a neutral storehouse of images. It embeds decisions about what counts as art, whose work is collected, how style and emotion are named, and under which rights images are used. Reading a model's outputs therefore requires attention to collection paths, taxonomies, annotators, omissions, and versions, not only scale.
</div>

## Three Points to Keep in Mind

- **Classification builds a worldview.** ImageNet categories and WikiArt style labels shape what a model is able to distinguish.
- **Scale and specialization are different axes.** Web-scale image-text pairs and art-specific datasets serve different purposes and create different risks.
- **Datasets have histories.** Distribution can stop, labels can change, image URLs can vanish, and licenses can be revised.

## At a Glance

| Dataset/resource | Main content | Typical use | Critical issue |
|---|---|---|---|
| ImageNet | General objects and people categories | Recognition and feature learning | WordNet taxonomy, person labels, image URLs |
| WikiArt | Artworks with style and genre metadata | Style classification and art generation | Geographic and period bias, rights, metadata |
| BAM / ArtBench | Artistic attributes and genre classes | Attribute learning and model evaluation | Label design and benchmark effects |
| LAION-5B | Web-derived image-text pairs | Large multimodal training | Consent, privacy, harmful content, versions |
| ArtEmis | Emotions and explanations attached to artworks | Affect modeling and language generation | Annotation culture and artwork rights |

## Reading the Data Pipeline

### 1. General-purpose recognition becomes an artistic substrate

ImageNet accelerated visual recognition, and its learned representations were reused in DeepDream and style transfer. Its taxonomy and person labels also became subjects of works such as ImageNet Roulette.

### 2. Art history becomes machine-readable labels

WikiArt, BAM, and ArtBench turn artist, style, genre, and visual attributes into learning targets. They support comparison while compressing disagreement and regional difference into fixed classes.

### 3. Web scale meets the language of viewers

LAION-5B supports large-scale learning of image-text relations. ArtEmis instead records emotional responses and explanations attached to art. Scale is the central issue for one; the meaning and cultural specificity of annotation for the other.

## Key Datasets

### ImageNet

<p class="item-meta">2009 · dataset · Foundational · Confidence: High</p>

> **Key point:** ImageNet helped transform visual recognition while also becoming a central case for criticism of classification and bias.

**What it contains.** Created by Jia Deng, Li Fei-Fei, and collaborators, it links large numbers of image URLs to WordNet-derived categories and supported the ImageNet Large Scale Visual Recognition Challenge.

**How to read it.** Reading AlexNet-era recognition, DeepDream, and ImageNet Roulette from the same data infrastructure shows that technical impact and social classification are intertwined.

**Caution.** Person categories and labels were later reviewed. Initial releases, the period of criticism, and current access should be distinguished.

**Source:** [ImageNet](https://www.image-net.org/)

**Related:** ImageNet Roulette, DeepDream, LAION-5B

### WikiArt

<p class="item-meta">2010- · online art encyclopedia/data source · Important · Confidence: High</p>

> **Key point:** A widely used source for style classification, CAN, ArtGAN, and related research that connects art-historical categories to machine learning.

**What it contains.** Artwork images and metadata such as artist, style, genre, and period; researchers often construct derivative datasets from it.

**How to read it.** WikiArt makes it possible to ask whose art history becomes the standard when style is converted into a prediction or generation label.

**Caution.** Rights, metadata quality, duplication, and geographic or period bias must be checked for each derivative dataset.

**Source:** [WikiArt](https://www.wikiart.org/)

**Related:** CAN, ArtGAN, Edmond de Belamy

### LAION-5B

<p class="item-meta">2022 · dataset · Foundational · Confidence: High</p>

> **Key point:** A major infrastructure for image-text models and a focal point for debates over consent, privacy, harmful content, and provenance.

**What it contains.** Web-derived image-text pairs filtered with CLIP similarity, associated with the training context of models including Stable Diffusion.

**How to read it.** It is better understood as an infrastructure of URLs, text, similarity, and filtering than as a single curated image archive.

**Caution.** Access, versions, and removal processes change. The dataset name alone does not establish the present contents or the training set of a specific model.

**Source:** [LAION-5B paper](https://arxiv.org/abs/2210.08402)

**Related:** Stable Diffusion, Glaze, C2PA

### ArtEmis

<p class="item-meta">2021 · dataset · Contextual · Confidence: High</p>

> **Key point:** A dataset that joins artworks to viewer emotion labels and explanations, turning reception rather than only visual content into data.

**What it contains.** Emotional responses to artworks and written explanations used for affect prediction and explanatory language generation.

**How to read it.** It models how people feel and speak about art, not simply what an image depicts.

**Caution.** Emotions and explanations depend on annotators' languages, cultures, and situations; they should not be treated as universal aesthetic responses.

**Source:** [ArtEmis](https://www.artemisdataset.org/)

**Related:** WikiArt, Foregrounding Artist Opinions, ArtBench

## Questions Across the Topic

- How can missing regions, periods, media, and communities be described as outcomes of collecting history rather than as simple absences?
- What becomes comparable, and what disappears, when contested art-historical concepts become fixed labels?
- How should deletion requests and license changes propagate through datasets after release?

## Read Next

- [Neural Image Generation]({{ '/en/topics/neural-image-generation/' | relative_url }}) - how data becomes generated imagery
- [Critique, Rights, and Provenance]({{ '/en/topics/critique-rights-provenance/' | relative_url }}) - consent, protection, and provenance
- [Regional, Cultural, and Critical Practices]({{ '/en/topics/global-critical-practices/' | relative_url }}) - responses to missing memories and regional representation
