# 3D Capability Showcase

Six real-time WebGL demos. Each one was built by a separate AI subagent working in parallel, then tested in a real browser. Every demo tests a different 3D skill, and each has its own interface design.

**Live:** https://ysohaarsh.github.io/3d-capability-showcase/

| Demo | Tests | Interface design |
|---|---|---|
| [The Orrery](demos/solar-system.html) | Scene graph, nested transforms, orbits | Brass observatory instrument |
| [Survey of an Island](demos/terrain.html) | Noise-generated terrain, custom GLSL water, fog, day/night | Cartographer's field journal |
| [Physics Playground](demos/physics.html) | Rigid bodies, collisions, raycasting | Bauhaus toy lab |
| [Unit-07](demos/robot.html) | Modelling from basic shapes, joint hierarchy, procedural animation | Retro handheld game HUD |
| [Spiral Galaxy](demos/galaxy.html) | 150k GPU particles, custom shaders, performance | Deep-space research console |
| [Atelier PBR](demos/showroom.html) | PBR materials, environment lighting, bloom | Luxury product configurator |

## Run locally

No build step. Each demo is one self-contained HTML file and loads its libraries from jsDelivr.

```sh
python3 -m http.server 8000
# open http://localhost:8000
```

## Stack

- [Three.js](https://threejs.org) r160
- [cannon-es](https://github.com/pmndrs/cannon-es) 0.20 (physics demo)
- Fonts from Google Fonts

Requires a browser with WebGL2 and an internet connection.
