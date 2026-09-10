# Photo Story

[← Back to the English directory](../README_EN.md) · [Source Skill](https://github.com/LeviQin/photo-agent-skills/tree/main/skills/photo-story) · [Author](https://github.com/LeviQin)

Photo Story writes a compact story grounded in visible details from one image and can render the text with the photograph as a shareable story card. The workflow explicitly separates visible facts from fictional interpretation.

## Preview

<p align="center"><img src="../assets/previews/heytea-source.jpg" width="235" alt="CC BY food photograph used as the source"> <img src="../assets/previews/photo-story-result.png" width="235" alt="Photo Story rendered result"><br><sub>Licensed source · locally rendered result</sub></p>

The result was created for this directory with the repository's local `render_story_card.py` helper.

## Best for

- diary fragments, micro-fiction, cinematic captions, and memory cards;
- keeping text visibly separate from the photograph;
- workflows that must label invention instead of presenting it as private fact.

## Installation

```bash
git clone https://github.com/LeviQin/photo-agent-skills.git
cd photo-agent-skills
./install.sh --agents codex --scope user
```

## Example request

```text
Use $photo-story to write a short fictional story grounded in visible details from this photo,
then render it as a story card. Clearly separate observation from invention.
```

## Safety and privacy

- Do not invent damaging motives, relationships, diagnoses, identities, or events about real people.
- Treat readable signs, documents, and location details as sensitive unless the user wants them included.
- Rendering is local, but image analysis may be remote depending on the host; choose an offline route for confidential photos.

## License and preview provenance

The collection is released under the [MIT License](https://github.com/LeviQin/photo-agent-skills/blob/main/LICENSE).

Source preview: Hchen1218's [`source-food.jpg`](https://github.com/Hchen1218/heytea-style/blob/main/assets/examples/poster/source-food.jpg), released by that repository under CC BY 4.0. Result preview: an adaptation created by this directory with LeviQin's MIT-licensed `render_story_card.py` helper and original catalog copy.
