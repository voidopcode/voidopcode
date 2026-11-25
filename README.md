<h2 align="center">hey, I'm void</h2>

<p align="center">
  Low-level developer. I take consoles apart in software:<br>
  system libraries, GPU code, file formats.
</p>

<p align="center">
  <img alt="Rust" src="https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white">
  <img alt="Direct3D 12" src="https://img.shields.io/badge/Direct3D%2012-7c5cff?style=flat-square">
  <img alt="DXIL / HLSL" src="https://img.shields.io/badge/DXIL%20%2F%20HLSL-1fb9d8?style=flat-square">
  <img alt="Windows internals" src="https://img.shields.io/badge/Windows%20internals-2f80ed?style=flat-square">
  <img alt="Reverse engineering" src="https://img.shields.io/badge/Reverse%20engineering-3ddc84?style=flat-square&logoColor=black">
</p>

---

<img align="left" width="110" src="vilocity-logo.svg" alt="Vilocity logo">

### Vilocity

Xbox Series X|S games running natively on Windows. No CPU emulation: the
game's x64 code runs as-is, the console's system libraries are re-implemented,
and its RDNA2 GPU code is recompiled to Direct3D 12 shaders.

<br clear="left">

**First target: GTA VI.** Not playable yet. Repo is private for now.

| Stage | Status |
|-------|--------|
| Boot, menus, intro video, saves | ✅ works, menus at 30 fps |
| Loading into the world | ✅ works |
| The world renders | 🟡 0.6-4.9 fps |
| The world keeps running | 🔴 GPU device lost 2-3 min in |
| Playable at 30 fps | 🔴 not yet |

<sub>Measured on Windows 11 Pro · RTX 5080 · Ryzen 9 9950X3D · 64 GB</sub>

---

<p align="center">
  <img height="150" src="https://github-readme-stats.vercel.app/api?username=voidopcode&show_icons=true&hide_border=true&theme=tokyonight&count_private=true" alt="GitHub stats">
</p>
