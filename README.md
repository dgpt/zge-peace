# zge-peace

ZGameEditor visualization for "Peace" by dxdy. The scene grows a cherry tree from seed in sync with audio and keeps the full tree framed at all times. The tree is implemented with ZGE components: a Model with `Definitions` for a quad mesh, shader, and material, and an `OnRender` section that uses the material and renders the mesh while a Camera tracks the growth.

## Controls
1. **Rotation Speed** – orbit rate of the camera around the tree.
2. **Animation Speed** – base growth speed of the tree.
3. **Hue Offset** – global hue shift.
4. **Saturation** – scales scene saturation.
5. **Lightness** – scales scene lightness.
6. **Alpha** – overall scene transparency.
7. **Sensitivity** – how strongly audio accelerates growth.
8. **Smoothness** – smoothing factor for audio response and easing.
9. **Zoom** – camera distance to tree.
