# Parameter map

This is an author-designed editing framework, informed by the sources. It is not a validated metric, model setting sheet, or AI detector. Parameter values are descriptive decisions, not arbitrary 1-10 sliders. Read it when establishing the brief and when diagnosing an image.

## Working brief

Capture only applicable fields; do not show a long form to the user.

| Field | Values / decision | How to resolve |
|---|---|---|
| Route | Generated-image repair / real-photo retouch / composite-poster | User brief and input roles; ask if unclear |
| Output | Platform, aspect ratio, pixel dimensions or print size | Ask if layout would change; do not invent print readiness |
| Art direction | User-described style; style reference with explicit role | Inherit the initial prompt; no compulsory candid aesthetic |
| Fidelity locks | Face, product, logo, exact text, specified surroundings | Default locks plus user-specific constraints |
| Change envelope | Background, wardrobe, pose, crop, lighting, cleanup | Broad edits allowed only outside locks and within intent |
| Input priority | Which reference governs identity, geometry, style, copy | Ask where references conflict |
| Delivery | Prompt only / prompt and requested execution | Default prompt; tools determine execution availability |
| Tool target | Named editor/generator or tool-neutral | Ask only when syntax/capability affects delivery |

## Diagnostic parameters

Record observation -> region -> action -> lock -> confidence. Use clear / issue / uncertain / not applicable internally. Prioritize identity, product and factual accuracy before optional polish.

| ID | Parameter | Look for | Action boundary | Basis |
|---|---|---|---|---|
| F1 | Face identity | Changed feature proportions or distinctive marks relative to references | Preserve individual identity; no generic beauty reconstruction | User requirement; S2/S3 anatomical category |
| F2 | Product/brand accuracy | Warped silhouette, altered finish/color, invented label/logo | Retouch presentation without redesigning product | User requirement; author adaptation of S2/S3 |
| F3 | Exact information | Wrong names, date/time, price, venue, missing sponsor, malformed glyphs | Use confirmed copy and source logos; typeset separately when needed | User requirement; S2/S3 functional category |
| R1 | Anatomy and contact | Fused limbs, incorrect visible fingers, grip/contact mismatch | Correct demonstrated defects; account for occlusion and normal variation | S2/S3 |
| R2 | Geometry and depth | Conflicting scale, perspective, overlaps, unstable support | Match the scene's camera geometry; preserve intentional graphic layers | S1 layout/existence; S2/S3 physics |
| L1 | Lighting structure | Direction, apparent source size, fill, contact/cast shadows | Multiple sources are valid when consistent; do not enforce a single shadow direction | S4 ch. 2-3; S2/S3 physics |
| L2 | Reflective/transmissive behavior | Highlights unrelated to surroundings, opaque glass, erased metal character | Match surface finish and reflection geometry; preserve deliberate studio highlights | S4 ch. 3, 6-7 |
| T1 | Exposure and tonal separation | Lost essential detail, clipped label, blocked silhouette | Recover essential detail without flattening intentional contrast | S1 technical; S4 ch. 9 |
| T2 | Color and grading | Unintended cast, inconsistent integration, inaccurate product hue | Preserve intentional grade and skin/product fidelity | S1 technical/rationality; author application |
| T3 | Texture and detail | Waxy smoothing, repeated detail, invented pores, smudges | Appropriate to material, lighting, scale and source detail | S1 detail/artifacts; S2/S3 style; S4 ch. 4/8 |
| T4 | Focus and motion | Arbitrary blur boundaries, sharpening halos, incompatible grain | Coherent depth/motion; no blur or grain as automatic realism filter | S1 blur/artifacts; author application |
| C1 | Composite integration | Cutout halo, spill, mismatched resolution, absent contact shadow | Match sharpness, lighting and edge treatment locally | S2/S3 style/physics; author workflow |
| D1 | Poster hierarchy | Unclear focal point, competing text, unreadable details | Follow brief and read at final viewing size | Author design practice, not validated by the four sources |
| B1 | Brief/context fit | Wrong sport/object use, wrong event details, unrequested style replacement | Respect intended culture/context; ask about ambiguity rather than stereotype | S1 context; S2/S3 context; author application |

## What is not a parameter

No universal pore amount, grain strength, asymmetry percentage, exposure offset, camera brand, realism score, or fixed research-weighted formula. Do not reuse AGIN's fitted coefficients as a universal editing rubric. Professional polish is compatible with naturalness.
