---
layout: default
title: Critique, Rights, and Provenance
permalink: /en/topics/critique-rights-provenance/
lang: en
---

[← Field Map]({{ '/en/survey-map/' | relative_url }}) · [Open Questions]({{ '/en/open-questions/' | relative_url }})

# Critique, Rights, and Provenance

<div class="topic-lead" markdown="1">
## Conclusion

What is technically possible in machine-learning creation is not necessarily socially acceptable. Consent to training data, artistic labor, style imitation, copyright, and provenance are conditions of production, not footnotes outside the artwork. Critical projects, artist studies, defensive tools, technical standards, and law address different stages, so no one intervention should be presented as a complete solution.
</div>

## Three Points to Keep in Mind

- **The problem is not only whether an output is AI-generated.** Collection, training, selection, editing, publication, and reuse carry distinct rights and responsibilities.
- **Technical and institutional responses complement one another.** Glaze resists style mimicry and C2PA records provenance, but neither alone guarantees consent or compensation.
- **Jurisdiction and date must be explicit.** Copyright decisions, regulation, standards, and platform terms change and differ across regions.

## Map of Problems and Responses

| Problem | Core question | Response | Limitation |
|---|---|---|---|
| Classification and bias | How do labels represent people? | Dataset-critical work such as ImageNet Roulette | Critique itself still requires factual and consent review |
| Artistic voice and labor | What do artists find useful or threatening? | Foregrounding Artist Opinions | Regional and occupational sampling limits |
| Unauthorized style learning | How can published work be protected? | Defensive tools such as Glaze | Continuing adaptation between defenses and models |
| Origin and edit history | How can generation and modification be traced? | C2PA | Metadata removal, adoption, confusion with truth |
| Copyright | How is human creative contribution judged? | Copyright offices, courts, policy | Jurisdiction, individual facts, continuing change |

## How the Problem Was Framed

### 1. Making dataset classification visible

ImageNet Roulette showed a broad public that a classifier's labels are political acts that position people, not neutral descriptions. Critical exhibitions, however, also require scrutiny of image use, consent, and historical claims.

### 2. Treating artists as participants in the debate

Artists are often represented as a uniform pro- or anti-AI group. Foregrounding Artist Opinions instead records varied positions on transparency, ownership, compensation, usefulness, and threat.

### 3. Separating protection, provenance, and copyright

Glaze aims to resist style learning; C2PA records media history; copyright evaluates human creative contribution. They operate at different stages and cannot be collapsed into a general certificate of "ethical AI art."

## Key Cases and Institutions

### ImageNet Roulette

<p class="item-meta">2019 · artwork/critical project · Important · Confidence: Medium</p>

> **Key point:** A web and exhibition project that made the social and political force of machine-learning taxonomies visible.

**What it did.** Trevor Paglen and Kate Crawford applied a classifier with person categories derived from ImageNet, connected to the *Training Humans* and *Excavating AI* contexts.

**How to read it.** Labeling appears as a cultural act that determines how people are seen rather than as a neutral preprocessing step.

**Caution.** Criticism by Michael J. Lyons and others disputes aspects of image consent and historical framing. The project's critical contribution and critiques of it should be recorded together.

**Source:** [Excavating AI](https://excavating.ai/)

**Related:** ImageNet, LAION-5B, dataset critique

### Foregrounding Artist Opinions

<p class="item-meta">2024 · paper/artist survey · Important · Confidence: High</p>

> **Key point:** A study of artists as people with their own expectations, fears, and demands rather than objects of an AI debate.

**What it did.** Juniper Lovato and colleagues surveyed 459 artists about transparency, ownership, compensation, and the usefulness and threat of generative AI.

**How to read it.** It grounds arguments about post-Stable Diffusion labor, datasets, and fairness in reported responses.

**Caution.** Recruitment, region, occupation, and medium shape the respondent pool; it is not a universal artistic consensus.

**Source:** [arXiv](https://arxiv.org/abs/2401.15497)

**Related:** Glaze, LAION-5B, Copyright and AI

### Glaze

<p class="item-meta">2023 · software/paper · Emerging · Confidence: High</p>

> **Key point:** A practical attempt to let artists publish images while resisting unauthorized style mimicry.

**What it did.** Shawn Shan and colleagues add visually subtle perturbations intended to misdirect style representations learned by text-to-image systems.

**How to read it.** It is significant as a rights response implemented as a tool artists can use directly, not only as policy advocacy.

**Caution.** Effectiveness depends on target models and evolving circumvention. Glaze is not permanent protection and should be evaluated beside consent, compensation, and regulation.

**Sources:** [Glaze](https://glaze.cs.uchicago.edu/) · [paper](https://arxiv.org/abs/2302.04222)

**Related:** Foregrounding Artist Opinions, LAION-5B, Stable Diffusion

### C2PA / Copyright and Artificial Intelligence

<p class="item-meta">2021-2025 · standard/policy · Important/Emerging · Confidence: High</p>

> **Key point:** C2PA records media origin and edit history, while copyright policy examines human creative contribution in AI-assisted work.

**What it did.** C2PA specifies cryptographically signed provenance metadata. The U.S. Copyright Office's AI reports address digital replicas, copyrightability, and training in separate stages.

**How to read it.** A circulation standard and legal evaluation of individual human contribution are different mechanisms; neither is a universal detector of AI generation.

**Caution.** C2PA depends on retained metadata and widespread verification. Copyright outcomes vary by jurisdiction and facts, and require current checking.

**Sources:** [C2PA](https://c2pa.org/) · [U.S. Copyright Office: Copyright and Artificial Intelligence](https://www.copyright.gov/policy/artificial-intelligence/)

**Related:** DALL-E, Stable Diffusion, Glaze, Foregrounding Artist Opinions

## Rights and Transparency Infrastructure, 2023-2026

The University of Chicago Glaze Project's Nightshade uses prompt-specific poisoning to raise the cost of non-consensual training. It requires affected images to enter training, does not retroactively change existing models, and is not effective for every model type. [Official explanation](https://nightshade.cs.uchicago.edu/whatis.html) · [Research record](https://nightshade.cs.uchicago.edu/aboutus.html)

Spawning's Have I Been Trained? supports searching selected public training data and recording Do Not Train preferences. It cannot search every private dataset, and compliance depends on developers and legal frameworks. [Service](https://haveibeentrained.com/) · [Spawning](https://spawning.ai/)

The [Data Provenance Initiative](https://www.dataprovenance.org/) audits origins, licenses, creators, languages, geographies, and derivation chains. It is infrastructure for supply-chain analysis, not automatic proof of consent for each work.

The U.S. Copyright Office released reports on digital replicas, copyrightability, and generative-AI training. Part 2 recognizes protection where humans determine sufficient expressive elements while treating prompts alone as generally insufficient. Part 3 analyzes training, fair use, market effects, and licensing. These are U.S. administrative reports, not case-specific judgments or global law. [Official study](https://www.copyright.gov/policy/artificial-intelligence/)

The EU AI Act requires general-purpose AI providers to implement copyright policies and publish training-content summaries. The Commission's mandatory template applied from 2 August 2025 and requests information across public datasets, scraping, private data, user data, and synthetic data. It is a transparency baseline rather than a complete item list. [Commission FAQ](https://digital-strategy.ec.europa.eu/en/faqs/template-general-purpose-ai-model-providers-summarise-their-training-content)

C2PA 2.2 carries signed creation and editing provenance. It does not determine truth, aesthetic value, or copyright, and absence of a manifest is not proof of falsity. [Specification](https://spec.c2pa.org/specifications/specifications/2.2/index.html)

| Mechanism | Main purpose | Does not solve |
|---|---|---|
| Glaze | Defense against style mimicry | Legal consent or universal protection |
| Nightshade | Technical deterrence to training | Deletion from existing models |
| Opt-out registry | Expressing preferences | Universal compliance |
| Data provenance | Supply-chain audit | Complete rights clearance |
| C2PA | Signed edit history | Truth or copyright judgment |
| Law and regulation | Rights, duties, remedies | Automatic technical tracing |

## Questions Across the Topic

- Is consent a one-time act at collection, or an ongoing relationship that can be withdrawn or revised?
- How should interests in style, voice, face, and bodily motion be protected when copyright fits poorly?
- How can provenance information be clearly distinguished from claims that a work is fair, authentic, or true?

## Read Next

- [Datasets, Art History, and Machine Vision]({{ '/en/topics/datasets-art-history-machine-vision/' | relative_url }}) - the infrastructure where these issues enter
- [Regional, Cultural, and Critical Practices]({{ '/en/topics/global-critical-practices/' | relative_url }}) - works about rights, representation, and memory
- [Open Questions]({{ '/en/open-questions/' | relative_url }}) - remaining legal, preservation, evaluation, and geographic gaps
