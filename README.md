# Ray bench

A 2D optical bench in one self-contained HTML file. Open `ray-bench.html` in Chrome or Edge; there is nothing to install or build.

## What it simulates

- **Rays:** reflection, refraction (Snell's law), Fresnel reflectance and polarization (Jones vectors), total internal reflection, and dispersion from measured Sellmeier equations for real glasses, water, sapphire, diamond and more.
- **Light sources:** white light, single wavelengths, gas-discharge lamps (hydrogen, neon, sodium and others), colours, and sunlight from a 5772 K blackbody filtered by the atmosphere.
- **Interference:** coherent ray-tube sums on screens, thin-film colours with coherence length, and colour-tinted beams.
- **Waves:** double-slit scenes shown as a true wave field, from the Huygens–Fresnel integral over each opening, on the GPU (WebGPU).
- **Space:** Earth's atmosphere (refraction and extinction, so lunar eclipses turn red), and gravitational lensing by black holes and massive bodies.
- **Parts:** lenses, prisms, mirrors, slits, screens, polarizers, everyday objects, geometric shapes (glass, mirror, wall, matte or slits, solid or hollow), a shape builder, and notes held on springs.

## Running it

- **Chrome or Edge** run everything: WebGPU (Wave View and GPU physics), WebGL 2 rendering, and Web Workers.
- **Saved scenes** go to a folder you choose (this repository's `scenes` folder works), or to browser storage.
- **On launch,** a short intro plays with synthesized music. The music can be switched off in Settings.
