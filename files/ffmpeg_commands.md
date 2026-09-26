# ffmpeg crop/convert commands

## MAFish_behavior — arena crop, mp4 → gif (360 wide @ 10 fps)

```bash
ffmpeg -y -i MAFish_behavior_20251003_094741_collision-25_nobots_0.mp4 \
  -vf "crop=720:730:140:60,scale=360:-1:flags=lanczos,split[s0][s1];[s0]palettegen=max_colors=128[p];[s1][p]paletteuse=dither=bayer:bayer_scale=5" \
  -loop 0 MAFish_behavior_20251003_094741_collision-25_nobots_0_arena.gif
```

## zf4 — crop only

```bash
ffmpeg -y -i zf4.gif \
  -vf "crop=430:430:250:220,split[s0][s1];[s0]palettegen[p];[s1][p]paletteuse" \
  -loop 0 zf4_cropped.gif
```

## wef3d_nose_yaw_demo_sensors — crop, 2× stretch, 1.5× brighten

```bash
ffmpeg -y -i wef3d_nose_yaw_demo_sensors.gif \
  -vf "crop=120:50:100:100,scale=240:100:flags=lanczos,lutrgb=r='clip(val*1.5,0,255)':g='clip(val*1.5,0,255)':b='clip(val*1.5,0,255)',split[s0][s1];[s0]palettegen[p];[s1][p]paletteuse" \
  -loop 0 wef3d_nose_yaw_demo_sensors_cropped.gif
```

## wef3d_swim_forward_side — crop, trim to 2.5 s, scale to 240 wide

```bash
ffmpeg -y -t 2.5 -i wef3d_swim_forward_side.gif \
  -vf "crop=400:240:100:100,scale=240:-1:flags=lanczos,split[s0][s1];[s0]palettegen=max_colors=128[p];[s1][p]paletteuse=dither=bayer:bayer_scale=5" \
  -loop 0 wef3d_swim_forward_side_cropped.gif
```

## wef3d_turns_learned — crop, scale to 270 wide

```bash
ffmpeg -y -i wef3d_turns_learned.gif \
  -vf "crop=450:270:150:80,scale=270:-1:flags=lanczos,split[s0][s1];[s0]palettegen=max_colors=128[p];[s1][p]paletteuse=dither=bayer:bayer_scale=5" \
  -loop 0 wef3d_turns_learned_cropped.gif
```
