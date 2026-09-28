# Opus 5.5 Pixel Character Action Benchmark

Side-by-side comparison of one young fantasy alchemist adventurer rendered as a game-ready pixel-art character at three logical frame sizes. Each size used its own fresh Kiro CLI process, conversation, and working directory. Sprite size was the only benchmark variant.

## Model and reasoning effort

- CLI: Kiro CLI 2.24.1
- Exact model ID: `claude-opus-5.5`
- Reasoning effort: `high`

## Variants

| Variant | Logical frame size | Intended tier |
|---|---:|---|
| S | 48×64 | Compact action sprite |
| M | 64×96 | Balanced action sprite |
| L | 80×112 | Roomy detailed action sprite |

## Animation set

- Idle: 2 frames
- Run: 6 looping frames
- Attack A: 6-frame short-sword slash
- Attack B: 6-frame potion or alchemy cast

Every variant includes live animation previews, the full contact sheet, a native-size sample, and a nearest-neighbor enlarged sample with a 384 px display height. The page does not declare an automatic winner.

## Exact prompts

The comparison page shows each submitted prompt under its matching variant. The original prompt text is also available here:

- [S — 48×64 prompt](prompts/S-48x64.txt)
- [M — 64×96 prompt](prompts/M-64x96.txt)
- [L — 80×112 prompt](prompts/L-80x112.txt)

Open [the comparison page](index.html) to view the outputs and expand each prompt.
