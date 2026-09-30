# 鹈鹕骑自行车 · Pelican Rides a Bicycle

A single-file, fully procedural WebGL scene: a pelican pedalling a bicycle through an endless
coastal landscape. **No external assets** — every mesh, texture and sound is generated at runtime
from primitives, parametric surfaces and `<canvas>` drawing.

## Highlights

- Pelican: egg-deformed sphere body, tapered-tube neck (custom sweep along a spline), extruded
  wings with splayed primaries, sagging gular pouch built as a parametric surface, scarf ribbon
  deformed per frame, cycling helmet, and a fish that did not get away.
- Bike: tubular frame, spoked wheels, crank + chainring, full drivetrain.
- Two-bone analytic IK drives the legs, so the feet track the pedals exactly through every
  crank revolution.
- Endless world: scrolling road/props/hills/clouds, drifting dust particles, gull flock.
- Custom bloom pass (the stock `UnrealBloomPass` breaks on some ANGLE/D3D drivers), colour grade
  with vignette, grain and chromatic aberration.
- Time-of-day slider driving a real sky model, sun/moon, fog and star field.
- Six camera modes, WebAudio wind + bicycle bell, PNG screenshot, fullscreen, keyboard shortcuts.

## Controls

Drag to orbit · scroll to zoom
`H` panel · `S` screenshot · `F` fullscreen · `Space` pause · `1`-`6` camera · `←` `→` time · `N` day/night

Built with [Three.js](https://threejs.org/) r170.
