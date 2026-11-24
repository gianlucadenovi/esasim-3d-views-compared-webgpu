<!-- esasim: cover -->
![3D views compared · WebGPU](assets/cover.svg)
<!-- /esasim: cover -->

# 3D views compared · WebGPU

The same two models, side by side, in EsaSim's 3D view and in the new **3D view (WebGPU)**, so the difference shows at a glance.

## What to look at

- **Paint and clear coat.** The toy car's body has a glossy coat over its colour: watch the reflections slide over it as you turn the view.
- **Glass.** The car's windows are see-through and bend what is behind them.
- **Fabric.** The chair's cloth has a soft sheen at grazing angles.
- **Shadows and contact.** Soft shadows on the floor, and darker creases where parts touch (ambient occlusion).
- **The badge** in the corner of each WebGPU view: the renderer (WebGPU, or WebGL 2 where WebGPU is missing), the quality it picked (high, medium or low) and your graphics card. It steps down by itself when frames run slow; the Quality setting forces one.

The two WebGPU views differ only in lighting: **studio** (a soft room) and **sky** (sun and sky).

## How to run it

1. Open the flow **Compare the views** and press **Run**. A worker downloads the two models from the Khronos glTF sample collection (a few seconds) and keeps them in the project's assets, under `models/`.
2. Open the **View** tab: the three views show the same models. Drag to turn, scroll to zoom, right-drag to pan.

Any worker with internet access will do; the views draw on the graphics card of whoever looks at them, not on the worker.

## Credits

Both models are in the public domain (CC0 1.0), from the [Khronos glTF Sample Assets](https://github.com/KhronosGroup/glTF-Sample-Assets):

- **Toy Car**, initial model by Guido Odendahl.
- **Sheen Chair**, by Wayfair, LLC.

<!-- esasim: files of the project -->

---

An [EsaSim](https://esacode.com/) project of the workspace Gianluca De Novi's workspace (visualization).

### Blueprints in this repository

- [Compare the renderers](blueprints/compare-the-renderers.json) · 5 blocks · version 1

### Assets

The files the project's views draw with (3D models, textures, sounds), in [assets/](assets/):

- [models/LICENCE-AND-CREDIT.txt](assets/models/LICENCE-AND-CREDIT.txt) · 391 B
- [models/SheenChair.glb](assets/models/SheenChair.glb) · 3.9 MB
- [models/ToyCar.glb](assets/models/ToyCar.glb) · 5.2 MB
- [textures/esacode-logo.png](assets/textures/esacode-logo.png) · 25 KB

Keys pasted in blocks (secret settings) are not saved here, nor are the team and the results of runs.
