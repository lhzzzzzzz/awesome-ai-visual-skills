# Photo to Zine Postcard

[← Back to the English directory](../README_EN.md) · [Source repository](https://github.com/Whiplashzeb/photo-to-zine-postcard) · [Author](https://github.com/Whiplashzeb)

Photo to Zine Postcard turns one source photograph into a coordinated minimal postcard. The front keeps the photo intact and proportion-safe, then adds a source-derived hand-drawn motif, sparse metadata, and three sampled color swatches. The Skill can also create a matching functional postcard back.

## Preview

<p align="center"><img src="../assets/previews/photo-to-zine-postcard.jpg" width="480" alt="Photo to Zine Postcard official Forest Homestead example"></p>

The official example is a finished composite with the source photograph already embedded in the upper region.

## Best for

- personal travel and landscape photography;
- quiet editorial postcards with large areas of whitespace;
- a coordinated front and functional mailing back.

## Installation

Clone the root Skill into the Codex Skills directory:

```bash
mkdir -p ~/.codex/skills
git clone https://github.com/Whiplashzeb/photo-to-zine-postcard.git \
  ~/.codex/skills/photo-to-zine-postcard
```

Alternatively, upload the repository's `SKILL.md` together with your image and ask the agent to follow it as the design specification.

## Example request

```text
Use $photo-to-zine-postcard to create a coordinated postcard front and back from this photo.
Keep the original photograph intact and preserve its aspect ratio.
```

## Safety and privacy

- Prefer photographs you took yourself; do not assume an image found online is reusable.
- Check the image provider's upload, retention, and training policy before using private photos.
- Inspect the `SKILL.md` before installation. This repository does not include a required executable runtime or API key, but the host still needs image-generation or editing capability.
- Verify postal marks, addresses, dates, and other factual text before printing or sharing.

## License and preview provenance

The repository is published under the [MIT License](https://github.com/Whiplashzeb/photo-to-zine-postcard/blob/main/LICENSE). Rights in a source photograph may still belong to its photographer or subjects independently of the workflow license.

Preview source: [`assets/forest-homestead.png`](https://github.com/Whiplashzeb/photo-to-zine-postcard/blob/main/assets/forest-homestead.png). The file was resized and re-encoded for this directory; its composition was not changed.
