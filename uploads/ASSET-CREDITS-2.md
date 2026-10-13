# Open Range asset research

The selector is based on open 3D horse releases found across OpenGameArt, Poly Pizza, BlendSwap, Sketchfab, and Mesh2Motion.

The runtime scene uses the supplied local `uploads/horse.glb`, which provides named `body`, eye, `main`, `tail`, `hooves`, and `snout` materials plus named Walk/Run clips. The previous Mesh2Motion horse remains documented below as the original asset research reference. No procedural or voxel stand-in is used.

- [Horse by Quaternius / Poly Pizza](https://poly.pizza/m/qvTrSG9pZF) — CC0 1.0, animated, 1,874 triangles.
- [Horse of Spring by lancelot_gao / OpenGameArt](https://opengameart.org/content/horse-of-spring-0) — CC BY 3.0, rigged and animated, downloadable FBX export.
- [Horse Rigged All Gaits by fdoss001 / BlendSwap](https://blendswap.com/blend/28627) — CC0, full rig with walk, trot, canter, and gallop actions.
- [Toon Horse with Saddle by flairetic / Sketchfab](https://sketchfab.com/3d-models/toon-horse-with-saddle-rigged-animated-db8fe38f93cb48e7a5c9df446a105f7a) — CC BY, rigged with walk, trot, and gallop animations.
- [Horse rig and animations by Mesh2Motion](https://github.com/Mesh2Motion/mesh2motion-assets/tree/main/rigs/horse) — CC0 source files; the public app ships the browser-ready horse animation GLB used here.

The active local browser-ready file in `assets/` is checked at load time for a real animation clip, a changing pose, and a repeating action before it is accepted into the scene.
