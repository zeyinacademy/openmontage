# Montage skills added to this fork (2026-11-26)

Copied unchanged (no demos, sites or tests) so the agent can use them from inside OpenMontage.
Claude Code sees them through symlinks in `.claude/skills/`.

| Skill | Use it for | Source @ commit | License |
|---|---|---|---|
| `motionmaxxing` | directing a motion-graphics film; gates `scripts/look.py` (G0, G2, G3) and `scripts/lint.mjs` (G5); measured eases in `runtime/motion.js` | github.com/Tejashmakwana/motionmaxxing @ `8c8ec0f` | Apache-2.0 (`LICENSE`, `NOTICE` kept) |
| `business-motion-film` | the independent-critic review loop, 16 motion mechanisms, quality bar, audio rules, measuring scripts | github.com/echris6/motion-video-kit @ `e4b1c00` | MIT |
| `huashu-motion` | code-built motion and composed music (`om sound`, ABC score); CLI via `npx huashu-motion` | github.com/alchaincyf/huashu-motion @ `f4f38bf` (`skills/huashu-motion` only) | MIT; GSAP and fonts in `THIRD_PARTY.md` |
| `ffmpeg-skill` | editing shot footage: cut, 9:16 reframe, silence removal, captions, loudness, checks (stdlib + ffmpeg) | github.com/kajisho5/ffmpeg-skill @ `2617bf0` | MIT |

Scripts that reach the network: `motionmaxxing/scripts/brand.mjs`, `fetch_logo.mjs`, `voice.py` (ElevenLabs key), `imagegen.py`.

Not added, by licence: `anything2explainer`, `video-talkcraft` (non-commercial), `lemo-opuscar` (style docs may not be redistributed).
To update: clone the source, copy the same folders again, and change the commit here.
