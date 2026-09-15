# cam_rig

An orbit camera rig for Cinema 4D (Redshift) driven from one control null — height, distance, orbit, tilt, focus and shake, all in the Attribute Manager. Drop it in, point **Target Object** at your subject, animate.

![Rig in the viewport](docs/viewport.png)

## Use

1. Merge `CAM_RIG.c4d` into your scene.
2. Select the **CAM_RIG** null → Attribute Manager → **User Data**.
3. Set **Target Object** to follow a subject; keyframe **Rotate From Center**, **Camera Height**, **Camera Distance** for moves.

## Controls

| POSITION | CAMERA SHAKE |
|---|---|
| ![](docs/panel_position.png) | ![](docs/panel_shake.png) |

- **POSITION** — orbit, height, distance, shift, tilt, focal length, target + aim offset.
- **DEPTH OF FIELD** — aperture, blades, aspect, focus object (defaults to the rig's FOCUS null).
- **CAMERA SHAKE** — real handheld shake via baked [Camera Shakify](https://github.com/EatTheFuture/camera_shakify) data (9 shakes, type / influence / scale / speed / offset).

## Credits

Shake data from **Camera Shakify** by Ian Hubert & Nathan Vegdahl, [CC0](https://creativecommons.org/publicdomain/zero/1.0/).

## Requirements

Cinema 4D 2026 · Redshift (RS Camera).
