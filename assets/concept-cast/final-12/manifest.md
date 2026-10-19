# BookVizion v6 — final 12 (CONCEPT SAMPLES) — manifest

Assembled 2026-10-18 late evening PT by Ravyn on Jon's FINISH directive. Every image is a CONCEPT SAMPLE. Nothing here ships before Jon's word. Awaiting ONE consolidated Folio blocking-only pass.

## Render lane and its limits (stated plainly)

- Scenes rendered by Ravyn with the GenerateImage tool (Ravyn's image lane), reference images attached. Ravyn cannot confirm which underlying model that tool runs, so it is NOT claimed as the gpt-image line.
- The tool returns a fixed 1280x720 (16:9) JPEG regardless of the 4:3 request. So the scene NATIVE size is 1280x720, and the true 4:3 crop (x 160-1120, full height, no resampling) is 960x720. That is BELOW the 1600x1200 target. No 2400x1800 export was made; any future one would be a 2.5x upscale and must be labelled upscaled.
- Framing still misses Pixel's rev-4 blocks even with the sketch attached (padded to 16:9): on the 4:3 crop Maya's puff top sits ~4% (target 20), eye line ~29% (target 40), Biscuit's ear tips ~41% (target 57-61), Biscuit ~0.52x Maya (target 0.35-0.40x). The generator would not pull the camera back. The five style scenes copy the control's composition, so all six match each other.
- Finish (control): whole-frame dark-edge 1.06% (hero 1.07% native / 1.82% at half size; v2 was 6.4% on the same measure); figure boxes Maya 2.15%, Biscuit 3.19% (gate 3.0%). Measure: 7x7 closing minus image, threshold 40, PIL — close to but not identical to Folio's OpenCV blackhat.

## Scenes (6) — Backyard at Dusk, same composition in every style

| Style | File | md5 | Size | Source / note |
|---|---|---|---|---|
| Polished Cartoon (CONTROL, pass 2 = re-roll 1 of 1) | scenes/native/scene-polished-cartoon-native-1280x720.jpg | fdcd3b95a4953e30d7b22393144f8b04 | 1280x720 | native as delivered (JPEG); pc-v3 attempt 2 (attempt 1 rejected: Biscuit on same plank, ~0.55x) |
| Polished Cartoon (CONTROL, pass 2 = re-roll 1 of 1) | scenes/scene-polished-cartoon-43-960x720.png | 547cea80bacd675724d24f7d07a67d10 | 960x720 | true 4:3 crop of native, no resample; pc-v3 attempt 2 (attempt 1 rejected: Biscuit on same plank, ~0.55x) |
| Polished Cartoon (CONTROL, pass 2 = re-roll 1 of 1) | scenes/scene-polished-cartoon-600.webp | b1aa41c25c863b1d122a0b11b7b0066a | 600x450 | 600 WebP from the 4:3 crop (downscale); pc-v3 attempt 2 (attempt 1 rejected: Biscuit on same plank, ~0.55x) |
| Polished Cartoon (CONTROL, pass 2 = re-roll 1 of 1) | scenes/scene-polished-cartoon-300.webp | eb36d2c3653fcd328f783acd3642c1d5 | 300x225 | 300 WebP from the 4:3 crop (downscale); pc-v3 attempt 2 (attempt 1 rejected: Biscuit on same plank, ~0.55x) |
| Watercolor (Kit A) | scenes/native/scene-watercolor-native-1280x720.jpg | 487b9c349c02f4d4f2bdb17bb1c0da5c | 1280x720 | native as delivered (JPEG); render 1 kept (re-roll rendered a golden sunset sky, rejected) |
| Watercolor (Kit A) | scenes/scene-watercolor-43-960x720.png | d73fec9c2971feb0e0a9514ca01ba62d | 960x720 | true 4:3 crop of native, no resample; render 1 kept (re-roll rendered a golden sunset sky, rejected) |
| Watercolor (Kit A) | scenes/scene-watercolor-600.webp | e7f73b8aa754029f33f1aee2874313c0 | 600x450 | 600 WebP from the 4:3 crop (downscale); render 1 kept (re-roll rendered a golden sunset sky, rejected) |
| Watercolor (Kit A) | scenes/scene-watercolor-300.webp | a44c4f9985931cc2284be0aa5302bbe1 | 300x225 | 300 WebP from the 4:3 crop (downscale); render 1 kept (re-roll rendered a golden sunset sky, rejected) |
| Bold Comic (Kit B) | scenes/native/scene-bold-comic-native-1280x720.jpg | f14537da646d4bd14e157b83e558d876 | 1280x720 | native as delivered (JPEG); re-roll 1 of 1 (render 1 rejected: not flat cel, read as the control) |
| Bold Comic (Kit B) | scenes/scene-bold-comic-43-960x720.png | 3959299331785ff46e2a302d60ee43a0 | 960x720 | true 4:3 crop of native, no resample; re-roll 1 of 1 (render 1 rejected: not flat cel, read as the control) |
| Bold Comic (Kit B) | scenes/scene-bold-comic-600.webp | bb86763e73166b8bd62e16c06726bd97 | 600x450 | 600 WebP from the 4:3 crop (downscale); re-roll 1 of 1 (render 1 rejected: not flat cel, read as the control) |
| Bold Comic (Kit B) | scenes/scene-bold-comic-300.webp | e907cc87ec03ea9309414992c135afbe | 300x225 | 300 WebP from the 4:3 crop (downscale); re-roll 1 of 1 (render 1 rejected: not flat cel, read as the control) |
| 3D Animated (Kit C) | scenes/native/scene-3d-animated-native-1280x720.jpg | 99613a46dd94bd894ed74741e6e8a6a8 | 1280x720 | native as delivered (JPEG); re-roll 1 of 1 (render 1 rejected: read as 2D painting) |
| 3D Animated (Kit C) | scenes/scene-3d-animated-43-960x720.png | 0dcb4ba5d3ad2ac6822ed2b639944d72 | 960x720 | true 4:3 crop of native, no resample; re-roll 1 of 1 (render 1 rejected: read as 2D painting) |
| 3D Animated (Kit C) | scenes/scene-3d-animated-600.webp | 810ae17281e5809e801df5e00a20fa18 | 600x450 | 600 WebP from the 4:3 crop (downscale); re-roll 1 of 1 (render 1 rejected: read as 2D painting) |
| 3D Animated (Kit C) | scenes/scene-3d-animated-300.webp | e207f5de6f59991ad062516337e84808 | 300x225 | 300 WebP from the 4:3 crop (downscale); re-roll 1 of 1 (render 1 rejected: read as 2D painting) |
| Semi-Real Painterly (Kit D) | scenes/native/scene-semi-real-native-1280x720.jpg | d1a1dda1de638e416c2e39c54db92818 | 1280x720 | native as delivered (JPEG); re-roll 1 of 1 (render 1 rejected: ~16 fireflies) |
| Semi-Real Painterly (Kit D) | scenes/scene-semi-real-43-960x720.png | 1c2e78ec5198d72db0666d7373f42c72 | 960x720 | true 4:3 crop of native, no resample; re-roll 1 of 1 (render 1 rejected: ~16 fireflies) |
| Semi-Real Painterly (Kit D) | scenes/scene-semi-real-600.webp | c84a69b11239a19949164e6892db4476 | 600x450 | 600 WebP from the 4:3 crop (downscale); re-roll 1 of 1 (render 1 rejected: ~16 fireflies) |
| Semi-Real Painterly (Kit D) | scenes/scene-semi-real-300.webp | 16c7a6e9826847bca031ad52e6315cb2 | 300x225 | 300 WebP from the 4:3 crop (downscale); re-roll 1 of 1 (render 1 rejected: ~16 fireflies) |
| Classic Storybook (Kit E) | scenes/native/scene-classic-storybook-native-1280x720.jpg | b0592e690aed47a1485c01700b8be9a0 | 1280x720 | native as delivered (JPEG); render 1 kept |
| Classic Storybook (Kit E) | scenes/scene-classic-storybook-43-960x720.png | 949957d947203337603aa0032354f1d2 | 960x720 | true 4:3 crop of native, no resample; render 1 kept |
| Classic Storybook (Kit E) | scenes/scene-classic-storybook-600.webp | 049869889022f98935aacd92dca2a832 | 600x450 | 600 WebP from the 4:3 crop (downscale); render 1 kept |
| Classic Storybook (Kit E) | scenes/scene-classic-storybook-300.webp | 606543e88c0168322ae415d1b71524bb | 300x225 | 300 WebP from the 4:3 crop (downscale); render 1 kept |

References attached to every scene render: blocking-sketch-scene-rev4.png (md5 c9d8af6f44c8325e1cadc1a730085e9f; padded to 16:9 for the control), maya-reference-portrait-v4.png (6d7d9fa2c956a48be145fbd841432497), biscuit-reference-portrait.png (18253d7b03ce1d5edeb8d8aa8599e02a), harlow-hero.png finish-only for the control (b7455e6041831687b42af411043fa7f0, from the box copy of Drive Character Art; it is NOT in the repo). The five style scenes used the control render as the composition reference plus that kit's banked Harlow master as finish-only reference.

## Harlow style row tiles (6) — 600 and 300 WebP, downscaled from the banked tiles (each an exact crop of its native master)

| Style | File | md5 | Size | Source tile (md5) / master (md5) / status |
|---|---|---|---|---|
| Watercolor | tiles/harlow-watercolor-tile-600.webp | f647dd1ecb0def1df414067a77d95bec | 600x600 | harlow-test-watercolor-tile-v6.png 1610x1610 (468c2cc6a8532da982dde970b4a786bf) / harlow-test-watercolor-master-v5.png (ea98d17186801ba4d824dd6a4ea0a896) / PASS (master v5 / tile v6) |
| Watercolor | tiles/harlow-watercolor-tile-300.webp | 6fcf7b1a001b5f7f4788cb549594f6da | 300x300 | harlow-test-watercolor-tile-v6.png 1610x1610 (468c2cc6a8532da982dde970b4a786bf) / harlow-test-watercolor-master-v5.png (ea98d17186801ba4d824dd6a4ea0a896) / PASS (master v5 / tile v6) |
| 3D Animated | tiles/harlow-3d-animated-tile-600.webp | 201b37e3f05b5821e4580195db672ad1 | 600x600 | harlow-test-3d-animated-tile-v5.png 1730x1730 (e5cc42472d546989ae09a4ca12e0a858) / harlow-test-3d-animated-master-v5.png (993e6f8822b74dbdcad78704ae368350) / OK TO USE — kept by Jon's override (Folio strict FAIL on record; if shown >300px, darken left-eye white ring first) |
| 3D Animated | tiles/harlow-3d-animated-tile-300.webp | 7e212205f4b064e943126d072f2acd38 | 300x300 | harlow-test-3d-animated-tile-v5.png 1730x1730 (e5cc42472d546989ae09a4ca12e0a858) / harlow-test-3d-animated-master-v5.png (993e6f8822b74dbdcad78704ae368350) / OK TO USE — kept by Jon's override (Folio strict FAIL on record; if shown >300px, darken left-eye white ring first) |
| Polished Cartoon | tiles/harlow-polished-cartoon-tile-600.webp | 175e703b70e0e3c1532bd92423588173 | 600x600 | harlow-test-polished-cartoon-tile-v3.png 1610x1610 (076bce76615839a0089de2845ac1434b) / harlow-test-polished-cartoon-master-v3.png (2c353b2d534310cda089d72f3bcfa0ef) / CONTROL (v3). Per the gate record the PC master derives from the 1206px harlow-hero, so the 2400 master is upscaled |
| Polished Cartoon | tiles/harlow-polished-cartoon-tile-300.webp | 56d930983043e1c5a15990c99f4ad1aa | 300x300 | harlow-test-polished-cartoon-tile-v3.png 1610x1610 (076bce76615839a0089de2845ac1434b) / harlow-test-polished-cartoon-master-v3.png (2c353b2d534310cda089d72f3bcfa0ef) / CONTROL (v3). Per the gate record the PC master derives from the 1206px harlow-hero, so the 2400 master is upscaled |
| Classic Storybook | tiles/harlow-classic-storybook-tile-600.webp | 99bdfe4f0ae6de3ee72d327fe319879c | 600x600 | harlow-test-classic-storybook-tile-v4.png 1680x1680 (3c6693ac38ce2bd209e9fa8cd9843f16) / harlow-test-classic-storybook-master-v4.png (285c4c6098906569832b65e04dcbb3fd) / PASS (v4) |
| Classic Storybook | tiles/harlow-classic-storybook-tile-300.webp | a5371cb8b83d0e540e50c9c4ab881f66 | 300x300 | harlow-test-classic-storybook-tile-v4.png 1680x1680 (3c6693ac38ce2bd209e9fa8cd9843f16) / harlow-test-classic-storybook-master-v4.png (285c4c6098906569832b65e04dcbb3fd) / PASS (v4) |
| Bold Comic | tiles/harlow-bold-comic-tile-600.webp | 6fe84a84ccebaa9ba4b5ca5b67a49dc5 | 600x600 | harlow-test-bold-comic-tile-v4.png 1660x1660 (b796d4a2622aaffe383244ce73fddb78) / harlow-test-bold-comic-master-v4.png (4ff9fed012d670c8db67116aba801005) / PASS (v4) |
| Bold Comic | tiles/harlow-bold-comic-tile-300.webp | aa50de675fdc147ef04570f7eb864b9c | 300x300 | harlow-test-bold-comic-tile-v4.png 1660x1660 (b796d4a2622aaffe383244ce73fddb78) / harlow-test-bold-comic-master-v4.png (4ff9fed012d670c8db67116aba801005) / PASS (v4) |
| Semi-Real Painterly | tiles/harlow-semi-real-tile-600.webp | 232e54c814b9a28ee7049a158ca0aa54 | 600x600 | harlow-test-semi-real-tile-v4.png 1660x1660 (7ff568f4d7296f14a945f91b71f4ba6a) / harlow-test-semi-real-master-v4.png (e303072c21e12174342200f749b85a42) / PASS (v4) |
| Semi-Real Painterly | tiles/harlow-semi-real-tile-300.webp | 378131cd7ca8dc77713c0f87bed09777 | 300x300 | harlow-test-semi-real-tile-v4.png 1660x1660 (7ff568f4d7296f14a945f91b71f4ba6a) / harlow-test-semi-real-master-v4.png (e303072c21e12174342200f749b85a42) / PASS (v4) |

Drive scratch copies of every raw render, including the rejected ones, are in My Drive root as bv6-scratch-scene-*.jpg (used only to move the files onto the box).
