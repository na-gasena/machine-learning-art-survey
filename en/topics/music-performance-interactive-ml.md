---
layout: default
title: Music, Performance, and Interactive Machine Learning
permalink: /en/topics/music-performance-interactive-ml/
lang: en
---

[← Field Map]({{ '/en/survey-map/' | relative_url }}) · [Works and Archives]({{ '/en/resources/works-archive/' | relative_url }})

# Music, Performance, and Interactive Machine Learning

<div class="topic-lead" markdown="1">
## Conclusion

In music and performance, machine learning is more than a device for automatically generating finished work. It can function as an instrument trained through demonstration, a live mapping between body, sound, and image, or an environment for exploring new timbres. The key is to treat training and iteration as part of the creative process rather than judging only the output.
</div>

## Three Points to Keep in Mind

- **Building a model can become performance.** Data collection, demonstration, and correction are embodied creative actions in interactive machine learning.
- **Music AI works at different time scales.** Live gesture response, timbre generation, and long-form musical structure are distinct problems.
- **Automatic composition is only one branch.** NIME and HCI research emphasizes relationships that performers can understand, adjust, and play.

## At a Glance

| Creative layer | Role of machine learning | Key item | Main criterion |
|---|---|---|---|
| Body and control | Learn mappings between gesture, sound, and image | Wekinator | Responsiveness, teachability, playability |
| Timbre and material | Learn sound features and support timbre exploration | NSynth / Magenta | Diversity and controllability |
| Design philosophy | Treat algorithms as interactive interfaces | Fiebrink & Caramiaux | Interpretability, iteration, discovery |

## How the Field Developed

### 1. Teaching through demonstration

Wekinator lets a user present input examples and desired outputs, then train a model in place. Rather than specifying every mapping in code, artists shape behavior through bodily and sonic examples.

### 2. Exploring timbre as a data space

Magenta released research, code, and demonstrations for creative use. NSynth learned features from individual notes, connecting machine learning to instrument and sound-material design rather than only complete composition.

### 3. Evaluating the quality of interaction

Creative tools are not valuable only when they maximize accuracy. Artists also need to understand a model's tendencies, correct it through short iterations, and turn unexpected responses into discoveries.

## Key Cases

### Wekinator

<p class="item-meta">2009- · software · Important · Confidence: High</p>

> **Key point:** A creative tool for training models through demonstration and designing real-time relationships among body, sound, and image.

**What it did.** Developed by Rebecca Fiebrink, Wekinator learns from input-output examples and connects through OSC to environments including Processing, openFrameworks, Unity, and Ableton.

**How to read it.** Training data becomes material made by the performer in the moment. The project connects NIME, HCI, music information research, and creative coding.

**Caution.** Evaluation should include teachability, iteration speed, and intelligibility of errors, not only predictive accuracy.

**Source:** [Wekinator](https://doc.gold.ac.uk/~mas01rf/Wekinator/)

**Related:** *The Machine Learning Algorithm as Creative Musical Tool*, NIME

### Magenta / NSynth

<p class="item-meta">2016-2017 onward · project/dataset/software · Important · Confidence: High</p>

> **Key point:** An open research and production environment that connected machine learning, musical experimentation, and latent representations of timbre.

**What it did.** Magenta released models, code, demos, and creative tools. NSynth used roughly 300,000 annotated single-note samples and a WaveNet-related approach to learn and explore instrumental timbre.

**How to read it.** Dataset, model, DAW integration, and open-source distribution combine into a creative ecosystem.

**Caution.** A single-note dataset cannot fully represent polyphony, long-term musical structure, or performance context.

**Sources:** [Magenta](https://magenta.tensorflow.org/) · [NSynth](https://magenta.tensorflow.org/nsynth)

**Related:** Wekinator, Holly+, PROTO / Spawn

### The Machine Learning Algorithm as Creative Musical Tool

<p class="item-meta">2016 · paper/theoretical synthesis · Important · Confidence: High</p>

> **Key point:** The paper treats machine-learning algorithms as interfaces between human and computer rather than as autonomous composers.

**What it did.** Rebecca Fiebrink and Baptiste Caramiaux describe musicians teaching systems with personal examples and exceptions, then exploring possibilities through model response.

**How to read it.** It explains Wekinator as part of a broader design philosophy centered on training, iteration, and embodied knowledge.

**Caution.** Recent large music models, voice cloning, and their rights questions require separate follow-up.

**Source:** [arXiv](https://arxiv.org/abs/1611.00379)

**Related:** Wekinator, Magenta, NIME

## Additional Survey: Composition, Improvisation, Timbre, and Bodies

François Pachet's Continuator (2002) learned a performer's style online and returned musical continuations, placing turn-taking and control before autonomous finished composition. [Paper](https://www.francoispachet.fr/wp-content/uploads/2021/01/pachet-02-icmai-final.pdf)

DeepBach generated Bach-style chorales while allowing users to constrain notes, rhythms, and cadences. [Paper](https://arxiv.org/abs/1612.01010)

Sony CSL's Flow Machines developed from research into FM Pro and an app that proposes melodies, chords, and basslines inside production workflows. Public discussion of *Daddy's Car* should retain the human roles in arrangement, lyrics, performance, and production. [Sony](https://www.sony.com/en/SonyInfo/design/stories/flow-machines/)

Georgia Tech's Shimon connects music generation to a marimba-playing robot, where reach, timing, and visible interaction constrain composition. [Official project](https://gtcmt.gatech.edu/shimon)

Dadabots used neural audio generation for metal and experimental music, presenting *Relentless Doppelganger* as an ongoing stream rather than a bounded album. [Project archive](https://dadabots.com/music)

FluCoMa provides analysis, reduction, clustering, and classification tools for Max, Pure Data, and SuperCollider. It supports artist-owned small corpora and live workflows. [Official site](https://www.flucoma.org/about)

Dance and theatre extend the field: [Living Archive](https://waynemcgregor.com/productions/living-archive/) turns a choreographic video archive into movement suggestions; [discrete figures](https://research.rhizomatiks.com/s/works/discrete_figures) combines machine perception and virtual dancers; [Improbotics](https://improbotics.org/) sends generated dialogue to human improvisers.

Research communities include [NIME](https://www.nime.org/), [AIMC](https://aimusiccreativity.org/), and [ISMIR](https://ismir.net/).

## Questions Across the Topic

- Does a performer understand a model by knowing its internals, or by being able to play it bodily?
- How can live data collection and training be documented and re-performed?
- How should consent and cultural attribution work when models learn timbre, voice, or performance style?

## Read Next

- [Human-Machine Collaboration]({{ '/en/topics/human-machine-collaboration/' | relative_url }}) - co-performance through voice, robots, and bodies
- [Creative Tools, Education, and Platforms]({{ '/en/topics/creative-tools-platforms/' | relative_url }}) - access to creative machine-learning tools
- [Critique, Rights, and Provenance]({{ '/en/topics/critique-rights-provenance/' | relative_url }}) - consent and rights in voice and style
