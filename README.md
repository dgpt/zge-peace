# zge-peace

ZGameEditor visualization for "Peace" by dxdy. The scene grows a cherry tree from seed to full bloom in sync with audio. A single GLSL shader ray-marches a procedural seed, roots, trunk and canopy and is drawn on a full-screen sprite following the `zge-oxygen` structure.

## Controls
1. **Rotation Speed** – orbit rate of the camera around the tree.
2. **Animation Speed** – base growth speed of the tree.
3. **Hue Offset** – rotates all colors 0–360°; 0 keeps the trunk brown and canopy pink.
4. **Saturation** – scales scene saturation (default vivid).
5. **Lightness** – scales scene lightness (min 10% to stay visible, default full).
6. **Alpha** – overall scene transparency (min 10% so the tree never disappears).
7. **Sensitivity** – how strongly audio accelerates growth.
8. **Smoothness** – smoothing factor for audio response and easing.
9. **Zoom** – camera distance to keep the tree framed.
