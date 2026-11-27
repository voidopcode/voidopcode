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

<a href="https://github.com/voidopcode/vilocity"><img src="https://raw.githubusercontent.com/voidopcode/vilocity/main/assets/discord-banner.png" alt="Vilocity: GTA VI on Windows, open source"></a>

### [Vilocity](https://github.com/voidopcode/vilocity)

Xbox Series X|S games running natively on Windows. No CPU emulation: the
game's x64 code runs as-is, the console's system libraries are re-implemented,
and its RDNA2 GPU code is recompiled to Direct3D 12 shaders.

**[Repository](https://github.com/voidopcode/vilocity)** · **[Quick start](https://github.com/voidopcode/vilocity#quick-start-from-nothing-to-gta-vi)** · **[Discord](https://discord.gg/PzxCF9UDP)** · **[Credits](https://github.com/voidopcode/vilocity#credits)**

**First target: GTA VI.** Not playable start to finish yet, but the open world runs.

| Stage | Status |
|-------|--------|
| Boot, menus, intro video, saves | ✅ works |
| Loading into the world | ✅ works |
| The world renders | 🟢 the saved game loads into the open world and plays |
| The picture | 🟢 shade, faces, skin, water and sky look right |
| DLSS (NVIDIA RTX) | ✅ works, with in-game settings on F1 |
| The world keeps running | 🟢 12 minutes in the open world without a crash |
| Frame rate | 🟡 25-33 fps (target 30) |
| Missions start to finish | 🔴 not yet |

<sub>Measured on Windows 11 Pro · RTX 5080 · Ryzen 9 9950X3D · 64 GB, as a Series S · live numbers in the
<a href="https://github.com/voidopcode/vilocity#gta-vi-progress">project README</a></sub>

<sub>Built on the work of <a href="https://github.com/Marvisak/VIctory">VIctory</a>, cool_fox and
<a href="https://github.com/xcl-dev/xcl">XCL</a>, with fixes from many forks:
<a href="https://github.com/voidopcode/vilocity#credits">full credits</a>.</sub>

---

<p align="center">
  <img height="150" src="https://github-readme-stats.vercel.app/api?username=voidopcode&show_icons=true&hide_border=true&theme=tokyonight&count_private=true" alt="GitHub stats">
</p>
