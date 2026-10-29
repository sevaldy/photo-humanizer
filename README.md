# Photo Humanizer

Version **0.1.0** - an evidence-informed skill for believable photographic elements, product retouching, and reference-faithful poster composites.

**Bahasa Indonesia:** skill ini membaca brief dan gambar, menanyakan hal penting yang belum jelas, lalu menghasilkan prompt edit siap pakai. Edit gambar dijalankan hanya jika diminta dan tool tersedia. Wajah, produk, logo, dan informasi acara dilindungi. Gaya mengikuti brief: foto studio yang rapi dan poster dramatis tetap diperbolehkan.

## What it does

- Repair visible problems in generated images without adding compulsory grain, blur or roughness.
- Retouch real product photos while preserving product accuracy.
- Plan multi-asset posters with identity preservation, coherent photo integration and exact event copy.
- Produce a prompt by default; use an available image tool only when execution is requested.

## Files

- `SKILL.md`: main instructions and workflow.
- `PARAMETERS.md`: brief fields and evidence-to-action parameters.
- `PHOTOGRAPHY.md`: photographic repair guidance.
- `COMPOSITES-POSTERS.md`: asset assembly and static poster guidance.
- `SOURCES.md`: citations, inspected sections, limitations and attribution.
- `EXAMPLES.md`: examples and text-based regression scenarios.
- `PHOTO-HUMANIZER-CHAT.md`: self-contained fallback for chat environments that cannot load a skill folder.
- `VALIDATION.md`: validation performed and limitations.

## Use as an installed skill

Download this repository as a ZIP and extract it. Keep `SKILL.md` and its linked Markdown files together in one folder named `photo-humanizer`. Use the host's supported skill installation/import workflow; installation locations and upload support depend on the application and account. In a host that supports local skill folders, install that folder in its documented skills location. This package has no required scripts, Python environment, API keys, or external skill dependencies.

A GitHub link or a ZIP attachment alone does not prove a host loaded the skill. Ask it to identify the workflow and source references it can actually access. If it cannot read the linked files, use the self-contained fallback below.

## Use in ChatGPT or Claude as ordinary chat guidance

When native skill import is unavailable, attach `PHOTO-HUMANIZER-CHAT.md` and the images. Explicitly ask the assistant to use it as the editing workflow for this task. This is uploaded task guidance, not a claim that it has become a persistent installed skill. Availability of image viewing, image generation and compositing depends on the host. If the host cannot view images, do not rely on its diagnosis; if it cannot edit images, use the resulting prompt in an image editor.

Example invocation:

> Gunakan Photo Humanizer untuk bahan yang saya lampirkan. Tanyakan dulu hal penting yang belum jelas, jaga wajah, produk, logo dan teks sesuai referensi, lalu buat prompt edit siap pakai. Gaya mengikuti brief saya. Jangan eksekusi edit dulu.

For execution, replace the final sentence with a request to edit after the brief is complete; the host must have suitable tools. Do not upload private source assets to a public repository just to use this skill.

## Optional UI UX Pro Max

It can contribute palette, typography and hierarchy suggestions when already available. It is not included or required. This skill does not apply web navigation, touch targets, framework or animation rules to a poster. No third-party database or script is redistributed.

## Evidence and limitations

The parameters are informed by three supplied research PDFs and selected sections of *Light - Science & Magic*, 6th edition; see [SOURCES.md](SOURCES.md). The research is not a tested prompt recipe. There is no guarantee of exact identity, accurate text, detector evasion or realism. No source PDFs, figures, user faces or private file paths are distributed. Version 0.1.0 has structural/manual scenario review; real image trials remain pending.

## Suggested first trial

Use one real product photo and its actual product master, or a basketball poster brief with a face photo, original logo, exact event information and desired canvas size. Compare the result against the references and improve the rules based on observed failures, rather than adding speculative rules.
