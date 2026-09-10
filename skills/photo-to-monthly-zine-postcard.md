# Photo to Monthly Zine Postcard

[← Back to the English directory](../README_EN.md) · [Source repository](https://github.com/shenchangyi/photo-to-monthly-zine-postcard) · [Author](https://github.com/shenchangyi)

Photo to Monthly Zine Postcard turns one photograph into a portrait 3:4 monthly record. It keeps the complete photo in a proportion-safe upper region and builds a compact lower page with a source-specific watercolor, month, literature, music, footer, and bookmark-like editorial column.

## Preview

<p align="center"><img src="../assets/previews/monthly-zine-postcard.jpg" width="480" alt="Photo to Monthly Zine Postcard official bridge example"></p>

The official example is a finished composite with the original photo preserved in its upper region.

## Installation

Clone the repository and copy only the installable Skill folder:

```bash
git clone https://github.com/shenchangyi/photo-to-monthly-zine-postcard.git
mkdir -p ~/.codex/skills
cp -R photo-to-monthly-zine-postcard/skills/photo-to-monthly-zine-postcard \
  ~/.codex/skills/
```

The Skill becomes available on the next agent turn as `$photo-to-monthly-zine-postcard`.

## Example request

```text
Use $photo-to-monthly-zine-postcard to make this photo into an August Zine postcard.
Keep the complete photograph and leave the music field blank if no reliable source can be verified.
```

## Safety and privacy

- Use an original or licensed photograph and obtain consent before publishing identifiable people.
- The image provider may receive the photo; review its privacy, retention, and training settings.
- The workflow may research books, quotations, and songs. Verify every attribution and use short, legally permitted excerpts rather than fabricated or lengthy copyrighted text.
- The repository contains instruction and reference files without required executable scripts; inspect them before installation.

## License and preview provenance

The repository is published under the [MIT License](https://github.com/shenchangyi/photo-to-monthly-zine-postcard/blob/main/LICENSE). Copyright and privacy rights in the input photo, quoted text, and other selected media remain separate.

Preview source: [`examples/bridge-blue-hour.png`](https://github.com/shenchangyi/photo-to-monthly-zine-postcard/blob/main/examples/bridge-blue-hour.png). The file was resized and re-encoded without compositional alteration.
