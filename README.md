# Photo Humanizer

Version **0.2.0**. Create informative posters from transcripts/notes, event posters, product photos, and photographic composites.

**Alur:** baca bahan dan lihat gambar -> maksimal lima pertanyaan penting jika diperlukan -> setelah dijawab langsung eksekusi -> periksa dan kirim visual. Brief lengkap langsung dikerjakan. Prompt bukan keluaran rutin.

## Scope and reference groups

| Group | Role | Main resources |
|---|---|---|
| General | Shared purpose, content fidelity, composition, space, contrast, color, review | GENERAL.md; selected Graphic Design School sections |
| Photo | Lighting, materials, geometry, texture, integration | PHOTOGRAPHY.md; S1-S4 |
| Poster | Transcript summary, editorial copy, typography, layout, expressive exploration | COMPOSITES-POSTERS.md, TYPOGRAPHY.md, FUSE.md; S5-S7 |

Style is broad. FUSE is an optional source of experimentation, not a compulsory look. Informative posters may rewrite and summarize source wording while preserving meaning and facts. Specific user requests update default fidelity constraints.

## Files

- [SKILL.md](SKILL.md): entrypoint, questions, priorities, execution, review.
- [GENERAL.md](GENERAL.md): common standards.
- [COMPOSITES-POSTERS.md](COMPOSITES-POSTERS.md): poster content/layout and asset assembly.
- [TYPOGRAPHY.md](TYPOGRAPHY.md): practical typography from selected Lupton sections.
- [FUSE.md](FUSE.md): optional directions derived from selected works.
- [PHOTOGRAPHY.md](PHOTOGRAPHY.md): photographic guidance.
- [PARAMETERS.md](PARAMETERS.md): diagnosis and severity.
- [SOURCES.md](SOURCES.md): bibliography, evidence boundaries, review coverage.
- [references/SOURCE-MAP.md](references/SOURCE-MAP.md): principle -> page -> application -> boundary.
- [EXAMPLES.md](EXAMPLES.md): manual scenario checks.
- [VALIDATION.md](VALIDATION.md): completed checks and remaining limitations.
- [PHOTO-HUMANIZER-CHAT.md](PHOTO-HUMANIZER-CHAT.md): generated standalone chat guidance.
- `scripts/build_chat.py`: rebuild/check standalone guidance; no third-party dependencies.

## Usage

Keep SKILL.md and its linked guidance together in a folder named photo-humanizer and use the host's supported skill workflow. If a host cannot load a folder, attach PHOTO-HUMANIZER-CHAT.md with the task sources as ordinary task guidance. This does not prove persistent installation. Actual image editing requires suitable tools in that host; the skill does not supply an image engine.

Example: "Gunakan Photo Humanizer. Ringkas transkrip ini menjadi poster informatif. Tanyakan maksimal lima hal penting bila perlu, lalu langsung buat posternya. Gaya bebas sesuai isinya."

If execution is unavailable, the assistant should explain the limitation rather than silently substitute a prompt. A specifically requested prompt-only task remains possible.

## Development

Run `python3 scripts/build_chat.py` after changing source guidance; use `--check` to detect drift. The fallback is generated from an explicit source list with internal anchors.

The book map uses selected supplied PDF pages and visual examples; it is not an exhaustive review or empirically validated recipe. No source books, scans, or source-page screenshots are included in this repository. Private study previews can be kept separately from the distributable. Optional design skills are neither bundled nor required.

## Changes in 0.2.0

- Execute by default after at most five necessary questions.
- Support transcript -> summary -> informative poster, with free wording and faithful facts.
- Separate General / Photo / Poster references; add page-level mapping for three design books.
- Clarify explicit changes, ambiguous marks, grain matching, and graphic/photographic planes.
- Keep tools and measurements conditional; do not claim color or pixel fidelity from a simplistic metric.
- Rebuild standalone guidance automatically. Claude's proposed 0.2.0 package was reviewed, not imported wholesale.
