# Your Own OS — Web Edition

The Pocket gizmo **"your own OS in a picture"** by Andres Diaz, recreated as a web page:
a 3D computer room where the machine on the desk actually runs.

**Live page:** GitHub Pages serves `index.html` from this repository.

## What works

- The 3D room: drag to look around; the monitor shows the machine's screen.
- **Engine install rite:** the ScummVM engine arrives as two pictures — the same
  PNG carriers the Pocket gizmo uses. Download both files from the
  [`engine/`](engine/) folder, then drag them onto the page (or use
  **Load carrier**). When the set completes, the screen says
  **ENGINE INSTALLED** and the engine serves the page locally — no network
  needed afterwards.
- **Games:** click **Load CD** and choose files from your own disc
  (an ISO image, or the extracted files of a game). Games are staged in
  your browser only — nothing is uploaded anywhere.
- AmnesiaOS disks (PNG disks made for the gizmo) insert the same way,
  through **Load carrier**.

## The engine build

ScummVM 2026.4.1git, slim Emscripten build with the `scumm` and `he`
(HE71+) engines enabled — enough for the Humongous Entertainment
catalogue, including Backyard Baseball (1997). ScummVM is free software
under the GNU GPL; see https://www.scummvm.org and the ScummVM source
repository for the corresponding source.

## Credits

- Computer model: "Old Computer" by YieldingMist206
  (https://skfb.ly/oDt7x), CC-BY 4.0
- CD model: "CD 3d Model" by ARComputerFundamentals
  (https://skfb.ly/oLWE9), CC-BY 4.0
- Engine: ScummVM (GPL)
- Room: three.js

Everything here was built for the Pocket gizmo first; this page is its
web edition.
