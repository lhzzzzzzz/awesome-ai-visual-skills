# Gathered Scenes Zine

[← Back to the English directory](../README_EN.md) · [Source repository](https://github.com/Zeejay0/gathered-scenes-zine-skill) · [Author website](https://zeejayzine.com/) · [Author](https://github.com/Zeejay0)

Gathered Scenes Zine is a collection of Codex image-generation Skills that first read a photograph's subject, space, color, movement, and emotional residue. Its two main paths either keep the scene as a truthful photographic anchor or distill it into an independent paper artwork.

## Preview

| Source photograph | Finished Gathered Scenes work |
| :---: | :---: |
| <img src="../assets/previews/gathered-scenes-source.jpg" width="360" alt="City and church source photograph"> | <img src="../assets/previews/gathered-scenes-result.jpg" width="360" alt="Where Stone Meets Sky finished work"> |

## Included creative paths

- `scenes-gathered-zine-v1-3` keeps the real photograph and extends it with simplified forms, structural color, negative space, and a fibrous torn-paper edge.
- `scene-distillation-zine-v1-3` uses the source only as semantic and emotional evidence; no source pixels remain in the final illustration.

The repository now also contains optional experimental Skills. Install only the folders you intend to use.

## Installation

```bash
git clone https://github.com/Zeejay0/gathered-scenes-zine-skill.git
mkdir -p ~/.codex/skills
cp -R gathered-scenes-zine-skill/skills/scenes-gathered-zine-v1-3 ~/.codex/skills/
cp -R gathered-scenes-zine-skill/skills/scene-distillation-zine-v1-3 ~/.codex/skills/
```

Restart Codex if the Skills do not appear immediately.

## Example requests

```text
Use $scenes-gathered-zine-v1-3 to turn this photo into a Gathered Scenes poster.
Preserve the relationship between the figure and the shoreline.
```

```text
Use $scene-distillation-zine-v1-3 to reinterpret this photo.
Do not preserve the photograph itself; express “approaching and missing.”
```

### Source-aware, no-text variation

Community prompt contributed by [@Frrrank](https://github.com/Frrrank). This variation deliberately overrides the Skill's default micro-text and broad cream-paper tendencies while keeping its source-derived composition, structural color, and torn-fiber transition.

```text
Use $scenes-gathered-zine-v1-3.
保留人物身份、姿态、透视和真实光色，以源图色彩重构纸面，不使用大面积白色，手撕纤维边缘与场景结构自然衔接，每张只使用一种高饱和结构色，加入克制、断续的素描与干刻线条，无新增文字、贴纸感和模板化装饰，根据每张照片的空间与情绪采用不同构图语言
```

## Safety and privacy

- The source photo may be sent to the image provider selected by the host application. Check its privacy and retention terms.
- Do not browse, save, or republish another person's uploaded source photo without explicit permission.
- The repository includes an optional macOS Live Photo importer and executable binary inside a separate live-flow Skill. It is not required for the two core Skills above; audit it before running or omit that folder.
- Use original or licensed photos and obtain consent before publishing identifiable people.

## License and preview provenance

The repository uses the [Gathered Scenes Zine Personal Non-Commercial License](https://github.com/Zeejay0/gathered-scenes-zine-skill/blob/main/LICENSE). Commercial work, paid generation, monetized content, company or client projects, and related uses require the author's prior written permission. Permitted sharing must remain free, retain notices, identify modifications, and use the same terms.

Preview sources: [`source.jpg`](https://github.com/Zeejay0/gathered-scenes-zine-skill/blob/main/examples/real-scene-collage/01-where-stone-meets-sky/source.jpg) and [`result.jpg`](https://github.com/Zeejay0/gathered-scenes-zine-skill/blob/main/examples/real-scene-collage/01-where-stone-meets-sky/result.jpg), from the official “Where Stone Meets Sky” case. They were resized and re-encoded without compositional alteration.
