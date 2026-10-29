# Sources and evidence-to-rule mapping

Version 0.1.0. Prepared 29 October 2026 from the supplied PDF versions. Relevant methods, findings, taxonomy and lighting sections were read; this is not a claim of exhaustive line-by-line review. Only original summaries and source links are distributed. No source PDF or illustration is bundled.

## S1 - Naturalness framework

Zijian Chen et al. *Exploring the Naturalness of AI-Generated Images*. Supplied arXiv:2312.05476v3, 4 March 2024 (initial submission 2023).
https://arxiv.org/abs/2312.05476v3

Locations: PDF pp. 2-3, 6-8, especially section 3.2. The study separates technical and rationality perspectives. Technical factors cover luminance, contrast, detail, blur and artifacts; rationality factors cover existence, color, layout, context and sensory clarity. The dataset has 6,049 images and 30 participants.

Applied here: assess technical finish and scene plausibility separately. Do not assume more sharpness/detail automatically means more naturalness. The parameter map is our operational adaptation. The study's fitted relationships are dataset-specific, not editing weights or guarantees.

## S2 - Illustrated artifact guide

Negar Kamali, Karyn Nakamura, Angelos Chatzimparmpas, Jessica Hullman and Matthew Groh. *How to Distinguish AI-Generated Images from Authentic Photographs*. June 2024, arXiv:2406.08651v1.
https://arxiv.org/abs/2406.08651v1

Locations: PDF p. 6; pp. 15-22 anatomy, 23-27 style, 28-35 function, 36-43 physics, 44-48 sociocultural context. Its categories guide inspection of anatomy, style, object use, physical coherence and context. The guide cautions that real photos can also look implausible.

Applied here: inspect specific visual relationships; never infer provenance from appearance alone. Correct only actual issues, accounting for occlusion, physical diversity and intended style. The source is a detection/visual-literacy guide, not a validated image-editing prompt method.

## S3 - Photorealism study

Negar Kamali, Karyn Nakamura, Aakriti Kumar, Angelos Chatzimparmpas, Jessica Hullman and Matthew Groh. *Characterizing Photorealism and Artifacts in Diffusion Model-Generated Images*. Supplied arXiv:2502.11989v1, 2025; CHI 2025. DOI: 10.1145/3706598.3713962.
https://arxiv.org/abs/2502.11989v1

Locations: section 4 (taxonomy), section 5.8 (curation), and section 6 (discussion/limitations). The study reports 749,828 observations from 50,444 participants across its phases. It examines 450 generated and 149 real images. Artifact type, scene complexity, display time and human curation affected discrimination performance.

Applied here: use a structured inspection and result-selection loop rather than promising that prompt wording alone guarantees realism. Findings concern model capabilities in 2024 and the study's stimuli; they do not establish universal current failure frequencies. This guide and S2 are related work by overlapping authors, not independent replications. Automated self-review is an editorial practice here, not equivalent to the study's human evaluation.

## S4 - Photographic lighting

Fil Hunter, Steven Biver, Paul Fuqua and Robin Reid. *Light - Science & Magic: An Introduction to Photographic Lighting*, 6th ed., Routledge, 2021. ISBN 9780367860271.
https://www.routledge.com/p/book/9780367860271

Locations use printed pages; supplied PDF pages are generally printed page +17: ch. 2 (particularly pp. 18-22), ch. 3 (pp. 31-40), ch. 6 (metal), ch. 7 (glass), ch. 8 (portraits; p. 177 skin texture). Selected material/portrait sections and contents were consulted.

Applied here: apparent source size informs shadow softness; reflection geometry controls highlight appearance; metal and glass require different treatment; skin texture interacts with light. Applying these principles to generative prompts is our recommendation, not a claim that the book studied AI generation.

## What is authored rather than empirically validated here

Identity and asset locks come from the user's requirements. Poster hierarchy, typography, export checks, prompt format, severity ordering and revision limits are editorial workflow choices. None of the four sources supplies a universal humanizer prompt, fixed sliders, detector-evasion recipe, or quantified guarantee. The package has not yet been validated with real image-generation trials.

## Redistribution

Source copyright and licenses remain with the respective owners. This repository includes neither the books nor paper PDFs, copied figures or substantial excerpts. UI UX Pro Max is an optional external skill, not bundled. Any license added to this repository covers only its original authored content, not cited works or future user assets.
