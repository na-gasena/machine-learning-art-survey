---
layout: default
title: Creative Tools, Education, and Platforms
permalink: /en/topics/creative-tools-platforms/
lang: en
---

[← Field Map]({{ '/en/survey-map/' | relative_url }}) · [Datasets and Resources]({{ '/en/resources/datasets-and-resources/' | relative_url }})

# Creative Tools, Education, and Platforms

<div class="topic-lead" markdown="1">
## Conclusion

The relationship between machine learning and creative practice cannot be explained through papers and museum works alone. Libraries, no-code teaching tools, public courses, and commercial services determine who can make what. They can widen access while hiding model and data internals or making production dependent on company pricing, policy, and interfaces.
</div>

## Three Points to Keep in Mind

- **Ease of use is a technical and cultural design choice.** APIs, examples, supported languages, and browser execution change who can participate.
- **Teaching tools and production systems form a continuum.** A classifier trained in Teachable Machine can become part of work made with browser code or external tools.
- **Commercial platforms are creative institutions.** Services such as Runway shape pricing, storage, distribution, and evaluation as well as model access.

## At a Glance

| Entry point | Required skill | Main use | Key item |
|---|---|---|---|
| No-code | Browser interaction | Classification, teaching, prototyping | Teachable Machine |
| Creative coding | JavaScript / p5.js | Interactive work and workshops | ml5.js |
| Self-directed archive | Code and course materials | Learning creative deep learning | Machine Learning for Artists |
| Commercial production | Web interface / API | Generative video, editing, production | Runway |

## How the Creative Environment Changed

### 1. Making "teaching the machine" accessible

Teachable Machine lets users collect image, sound, or pose examples and see classification training in the browser. Like Wekinator, it makes selection and example building part of the activity.

### 2. Integrating machine learning with creative coding

ml5.js connects TensorFlow.js capabilities to p5.js culture. Machine Learning for Artists records how artists learned and applied the technologies surrounding DeepDream, style transfer, and GANs.

### 3. Turning production into a service

Runway moved from a general model-running interface toward generative video and editing. AI now enters production stages, occupations, distribution, and institutions such as AI film festivals.

## Key Tools

### ml5.js

<p class="item-meta">2018- · software · Important · Confidence: High</p>

> **Key point:** A library that brought machine learning closer to browser-based creative coding rather than specialist model development.

**What it did.** Developed through NYU ITP/IMA and its community, ml5.js exposes approachable JavaScript APIs for pose, hand, face, image and sound classification, and trainable neural networks.

**How to read it.** It connects machine learning with p5.js, Processing, education, and workshop practice.

**Caution.** Simple APIs still carry pretrained-data bias, misrecognition, camera and microphone privacy, and accessibility concerns.

**Source:** [ml5.js](https://ml5js.org/)

**Related:** Teachable Machine, Wekinator, ml4a

### Teachable Machine

<p class="item-meta">2017- · software/educational tool · Important · Confidence: High</p>

> **Key point:** A no-code route to image, sound, and pose classifiers that opened machine teaching to classrooms and prototypes.

**What it did.** Users gather examples, define classes, train a model in the browser, and export it to web or external tools.

**How to read it.** AI literacy becomes an experience of collection, misclassification, and retraining rather than explanation alone.

**Caution.** Not every creative problem should be forced into classes, and users need to ask whom their examples represent.

**Source:** [Teachable Machine](https://teachablemachine.withgoogle.com/)

**Related:** ml5.js, Wekinator, machine teaching

### Machine Learning for Artists

<p class="item-meta">2016- · educational project/archive · Important · Confidence: High</p>

> **Key point:** A major public learning resource from the period when deep learning first entered artists' workflows.

**What it did.** Gene Kogan and contributors assembled an online book, guides, interactive demos, code, and lecture videos; the site now remains as an archive.

**How to read it.** It records what and how artists learned during the DeepDream, style-transfer, and GAN period.

**Caution.** Some technical material is outdated and should be read beside current software, licensing, and ethical guidance.

**Source:** [Machine Learning for Artists](https://ml4a.github.io/)

**Related:** ml5.js, Magenta, Runway

### Runway

<p class="item-meta">2018- · commercial software/platform · Important · Confidence: High</p>

> **Key point:** A representative platform connecting machine learning to video production, advertising, film, and post-production.

**What it did.** Initially known as a model-running environment for non-engineers, Runway developed into a service for generative video, image and video editing, and APIs.

**How to read it.** Its relationship to Stable Diffusion and the AI Film Festival shows technical, commercial, and evaluative institutions forming together.

**Caution.** Training data, licensing, pricing, storage, model updates, and effects on production labor can be difficult to inspect in a commercial service.

**Source:** [Runway](https://runwayml.com/)

**Related:** Stable Diffusion, DALL-E, AI Film Festival, C2PA

## Comparing Tools by Production Stage

| Stage | Tools | Strength | Caution |
|---|---|---|---|
| Learning from gestures | Wekinator | Small data and immediate feedback | Users must understand features and errors |
| Browser education | Teachable Machine, ml5.js | Accessible and shareable | UI can hide model limits |
| Sound analysis | FluCoMa | Artist-owned corpora; Max/Pd/SC | Requires analytical design |
| Music co-production | Flow Machines | Candidate generation in DAWs | Cloud, region, and terms |
| Latent exploration | Artbreeder | Mixing, derivation, sharing | Provenance of public derivatives |
| Generative media | Runway | Integrated video workflows | Model changes, pricing, cloud dependence |
| Local image pipelines | Stable Diffusion interfaces | Reproducible graphs and extensions | GPU, licenses, security |

[FluCoMa](https://www.flucoma.org/about) offers segmentation, description, reduction, clustering, classification, and retrieval for Max, Pure Data, and SuperCollider. It supports artist-collected sound corpora rather than only general-purpose generation.

[Flow Machines](https://www.sony.com/en/SonyInfo/design/stories/flow-machines/) proposes melodies and related material through Style Palettes for editing in DAWs. Official availability has varied by region.

[Artbreeder](https://www.artbreeder.com/about) developed from Ganbreeder and used BigGAN and StyleGAN to turn latent mixing and public derivation into an interface.

Cloud tools change models, defaults, filters, prices, and output sizes. Records should include access date, product version, model, input, seed, settings, and editing. Education should cover data authorship, measurable features, errors, local versus server processing, licenses, deletion, and preservation after a service ends.

## Questions Across the Topic

- How much should beginner tools explain model limitations and data provenance?
- How can obsolete code and web demos be preserved as technical-history sources and made executable again?
- What exactly should be preserved when a platform update breaks an artwork's workflow?

## Read Next

- [Music, Performance, and Interactive Machine Learning]({{ '/en/topics/music-performance-interactive-ml/' | relative_url }}) - training tools through demonstration
- [Neural Image Generation]({{ '/en/topics/neural-image-generation/' | relative_url }}) - the model lineages wrapped by tools
- [Critique, Rights, and Provenance]({{ '/en/topics/critique-rights-provenance/' | relative_url }}) - terms, labor, and transparency
