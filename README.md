# shikharuniyal

Hi — I'm Shikhar. I build procedural graphics, interactive demos, and game-tech tools using Raylib and C++.

Quick profile

- 🔭 Currently: procedural leaf venation demos, visual tools, and reproducible Docker builds.
- 🛠️ Primary tech: C++, Raylib, Docker, WebAssembly (for web builds), GitHub Actions.
- 📫 GitHub: https://github.com/shikharuniyal

Portfolio highlights (workspace: E:\#EditorCodes)

- `procedural-leaf-venation` — procedural leaf venation demos, Dockerfile, and demo recordings (MP4).
- `leaf/` — interactive demos and source for running visualizations locally with Raylib.
- `raylib/` — Raylib sources and examples used as references and build targets.
- `rotat_sq/` and `flowing/` — smaller experiments and simulation code (rotations, particle flows).

What to expect here

- Code examples and runnable demos (native builds + Dockerfiles).
- Recorded demos and short MP4 walkthroughs for each project.
- Notes on building locally and running demos (Windows + Docker).

Suggested README sections to add per project

- **Overview:** short description and demo screenshots or GIFs.
- **Try it:** one-line commands to build/run (native and Docker), and links to any live web demos.
- **Controls:** keyboard/mouse controls for interactive demos.
- **Build matrix / CI:** GitHub Actions workflow to build native binaries and web (WASM) artifacts.

Interactive ideas & feature suggestions

- Web builds (WASM): compile Raylib demos to WebAssembly and host on GitHub Pages for instant demos.
- Live parameter controls: add UI sliders to tweak generation parameters in real time and export presets.
- Shader variants: implement fragment/vertex shader modes (noise, color maps) with toggleable presets.
- Export & share: allow saving snapshots (PNG) or short GIF recordings from within the app.
- Remote control: simple WebSocket or HTTP endpoint to update parameters remotely for live demos.
- Small web UI wrapper: embed the WASM demo with interactive controls and a permalink for each preset.

Practical repo improvements

- Move large media (MP4) to Git LFS or host on a CDN; keep source code light.
- Convert `raylib/` to a submodule or document how to fetch it separately (avoid embedding full third-party history).
- Add CI to build releases and publish artifacts (Windows portable exe, Linux binary, WASM zip).
- Add badges: build status, license, top language, and LFS usage.

Next steps I can take for you

- Add these sections to individual project READMEs and auto-generate badges.
- Set up GitHub Actions to build native + WASM artifacts and deploy to GitHub Pages.
- Migrate `leaf/demo_sim.mp4` to Git LFS and rewrite history (optional; I will explain implications).

If you'd like, I can implement any of the interactive ideas above — tell me which one to start with and I will scaffold it.

Thanks for sharing your work — happy to help make these demos easy to explore and share.

