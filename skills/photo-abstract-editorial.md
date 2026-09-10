# Photo Abstract Editorial

[← Back to the English directory](../README_EN.md) · [Source repository](https://github.com/ZzzLc0405/photo-abstract-editorial) · [Author](https://github.com/ZzzLc0405)

Photo Abstract Editorial turns one photograph into a vertical editorial composition that combines a truthful photo region with a source-derived abstract memory panel. It reads spatial relationships, rhythm, and color from the uploaded image instead of applying a generic filter or repainting the photograph.

## Preview

<p align="center"><img src="../assets/previews/photo-abstract-editorial.jpg" width="520" alt="Photo Abstract Editorial official composite example"></p>

The project publishes finished composites in which the source photograph and abstract result are already presented together. The preview above remains intact and has only been resized and re-encoded for this directory.

## Best for

- travel, architecture, landscape, and everyday photographs with a clear visual anchor;
- restrained editorial layouts with generous warm-white space;
- preserving the original photo while adding an interpretive visual panel.

## Installation

Clone the repository as one Codex Skill:

```bash
mkdir -p ~/.codex/skills
git clone https://github.com/ZzzLc0405/photo-abstract-editorial.git \
  ~/.codex/skills/photo-abstract-editorial
```

Restart Codex if the Skill is not listed immediately. The repository also includes standalone Chinese and English prompt documents under `references/`.

## Example request

```text
Use $photo-abstract-editorial to turn this photograph into a vertical editorial work.
Keep the photograph truthful and derive the abstract panel only from its real colors and spatial relationships.
```

## Safety and privacy

- Use a photo you own or have permission to transform and publish.
- The host image model may upload the photograph to a third-party service; review that provider's retention and training settings before using personal or sensitive images.
- Remove location metadata and avoid identifiable people when consent is unclear.
- The repository contains instructions and reference material rather than executable scripts, but still read the complete `SKILL.md` before installation.

## License and preview provenance

The repository's [`LICENSE.md`](https://github.com/ZzzLc0405/photo-abstract-editorial/blob/main/LICENSE.md) reserves copyright and permits personal, educational, research, and non-commercial use; commercial use and commercial redistribution require authorization. Its README badge names CC BY-NC-SA 4.0, while the linked license file contains custom terms, so consult the license file and ask the author when the distinction matters.

Preview source: [`assets/examples/case-10.jpg`](https://github.com/ZzzLc0405/photo-abstract-editorial/blob/main/assets/examples/case-10.jpg). The project states that its example source photographs were taken by the author. Inclusion here is for non-commercial cataloguing and does not imply endorsement.
