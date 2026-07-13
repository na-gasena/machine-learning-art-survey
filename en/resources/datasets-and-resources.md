---
layout: default
title: Datasets, Tools, and Resources
permalink: /en/resources/datasets-and-resources/
---

# Datasets, Tools, and Resources

## Datasets

### Art Images, Art History, and Description

- **WikiArt**: Frequently used for style classification and GAN/CAN research. Rights vary by work; public aggregation is not equivalent to reuse permission. https://www.wikiart.org/
- **OmniArt**: Connects art images to artist, period, style, and other attributes. Its official page says distribution has been unavailable since 2025. https://isis-data.science.uva.nl/strezoski/
- **SemArt**: Pairs fine-art images with descriptions. Aston University's record provides DOI, files, and metadata. https://researchdata.aston.ac.uk/id/eprint/380/
- **ArtGraph**: Represents relations among artworks, artists, styles, and genres as a knowledge graph. https://zenodo.org/records/6337958
- **ArtEmis**: Connects artworks with emotion categories and natural-language explanations; annotator and cultural context matter. https://www.artemisdataset.org/
- **ArtBench-10**: A ten-class art-image generation benchmark. The authors' fair-use rationale does not replace downstream rights review. https://github.com/liaopeiyuan/artbench
- **BAM! Behance Artistic Media Dataset**: Media, content, and emotion labels derived from Behance portfolios. https://arxiv.org/abs/1704.08614

### Museum Open Data

- **The Met Collection API**: Official metadata and public-domain images; check object-level rights and image fields. https://metmuseum.github.io/
- **Rijksmuseum Data Services**: APIs, Linked Open Data, downloads, and IIIF. https://data.rijksmuseum.nl/
- **Smithsonian Open Access**: Cross-domain collections in art, history, science, and culture; open status does not erase cultural sensitivity or Indigenous data governance. https://www.si.edu/OpenAccess
- **MoMA Collection Data**: Official artwork and artist metadata on GitHub; it is neither a complete collection digitization nor an image license. https://github.com/MuseumofModernArt/collection
- **National Gallery of Art Open Data**: Official collection and constituent exports. https://github.com/NationalGalleryOfArt/opendata

### Recognition, Faces, and Bodies

- **ImageNet**: A foundation of visual recognition and an object of classification critique. People categories, vocabulary, and collection history require context. https://www.image-net.org/
- **People-Art / Human-Art**: People detection and pose tasks across artworks and artificial scenes. https://arxiv.org/abs/1610.08871 / https://arxiv.org/abs/2303.02760
- **FFHQ**: Important to GAN/deepfake history; biometric data, consent, Flickr sourcing, and derivatives require review. https://github.com/NVlabs/ffhq-dataset

### Image-Text and Audio

- **LAION-5B**: Large-scale image-text index central to questions of URLs, captions, filtering, consent, privacy, harmful content, and model derivatives. https://arxiv.org/abs/2210.08402
- **NSynth**: Annotated musical notes for timbre and audio generation; check the dataset license and source sample-library context. https://magenta.tensorflow.org/datasets/nsynth

## Tools

### Train From Your Own Examples

- **Wekinator**: Interactive learning from demonstrated gesture, sound, sensor input, and output mappings. https://doc.gold.ac.uk/~mas01rf/Wekinator/
- **ml5.js**: Browser and p5.js library for creative ML education and production. https://ml5js.org/
- **Teachable Machine**: No-code prototyping for image, sound, and pose classification. https://teachablemachine.withgoogle.com/
- **ml4a**: Artist-facing lessons and code examples; dependency compatibility should be checked. https://ml4a.github.io/

### Sound, Music, and Live Production

- **Magenta**: A historically important creative ML research and tools project; maintenance status differs by component. https://magenta.tensorflow.org/
- **FluCoMa**: Max, Pure Data, and SuperCollider tools for analyzing, decomposing, clustering, and retrieving personal sound corpora. https://www.flucoma.org/
- **Flow Machines**: AI-assisted composition and production; availability varies by product and region. https://www.sony.com/en/SonyInfo/design/stories/flow-machines/

### Image and Moving-Image Production

- **Stable Diffusion**: A key open-weight text-to-image ecosystem; track model card, license, derivative checkpoint, and training-data claims by version. https://github.com/CompVis/stable-diffusion
- **Artbreeder**: Browser-based image mixing, parameters, and derivative lineages. https://www.artbreeder.com/about
- **Runway**: Commercial generative-video platform; models, pricing, cloud storage, and terms change. https://runwayml.com/

### Rights, Consent, and Provenance

- **Glaze**: Defensive tool intended to inhibit style mimicry. https://glaze.cs.uchicago.edu/
- **Nightshade**: Data-poisoning tool intended to disrupt unauthorized training; distinguish its goal and evaluation from Glaze. https://nightshade.cs.uchicago.edu/whatis.html
- **Have I Been Trained?**: Dataset search and creator preference interface. https://haveibeentrained.com/
- **C2PA 2.2**: Signed manifests for creation and editing history; not an automatic truth detector. https://spec.c2pa.org/specifications/specifications/2.2/index.html

## Key Resources

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
- Works archive and media links: {{ '/en/resources/works-archive/' | relative_url }}

## Usage Notes

Before reusing datasets or models, check licenses, source rights, consent for human data, local law, and disclosure requirements. LAION-5B, WikiArt-derived data, and datasets containing human images require particular ethical and rights review.
