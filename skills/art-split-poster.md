# Art Split Poster

[← Back to the English directory](../README_EN.md) · [Source Skill](https://github.com/heycalvin/awesome-agent-skills/tree/main/skills/creative/art-split-poster) · [Author](https://github.com/heycalvin)

Art Split Poster creates one 3:4 editorial poster per input photo. The upper half preserves the photograph; the lower half becomes warm paper with a small source-derived drawing, a limited palette, ample negative space, and optional restrained typography.

## Preview

<p align="center"><img src="../assets/previews/art-split-source.jpg" width="235" alt="Art Split Poster source photo"> <img src="../assets/previews/art-split-result.jpg" width="235" alt="Art Split Poster result"><br><sub>Official before · after</sub></p>

## Best for

- family, pet, travel, and daily-life photos where the source must remain visible;
- a strict half-photo, half-paper cover system;
- processing several photos as separate, visually consistent posters.

## Installation

Use Codex's Skill installer with the specific folder URL:

```text
$skill-installer
Install this skill from GitHub:
https://github.com/heycalvin/awesome-agent-skills/tree/main/skills/creative/art-split-poster
```

The Skill uses a host-provided image-editing tool rather than bundling a renderer.

## Example request

```text
Use $art-split-poster on this photo. Keep the subject and pose unchanged in the upper half,
then create a tiny source-colored line illustration on warm paper below. No added text.
```

## Safety and privacy

- Do not batch unrelated people's photos without permission; the workflow sends each input to the active image editor.
- Check facial identity, people count, crop, and exact text after generation.
- If the output invents or changes a person, discard it instead of publishing it as a faithful edit.

## License and preview provenance

The parent repository is released under the [MIT License](https://github.com/heycalvin/awesome-agent-skills/blob/main/LICENSE). No separate media license is stated for these two files, so retain attribution and confirm rights before reusing them outside cataloguing or review.

Preview sources: [`sample-input.jpg`](https://github.com/heycalvin/awesome-agent-skills/blob/main/docs/assets/art-split-poster/sample-input.jpg) and [`sample-output.jpg`](https://github.com/heycalvin/awesome-agent-skills/blob/main/docs/assets/art-split-poster/sample-output.jpg).
