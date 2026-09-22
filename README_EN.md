<div align="right">
  <a href="./README.md">中文</a>
</div>

<div align="center">

# Shijin (sj817)

*Carving away the noise, crafting what matters.*

<p align="center">
  <a href="https://github.com/sj817"><img src="https://img.shields.io/github/followers/sj817?style=flat-square&logo=github&labelColor=18181b&color=2563eb" alt="Followers" /></a>
  <img src="https://img.shields.io/badge/Focus-Blink%20%7C%20Rust%20%7C%20TypeScript-f59e0b?style=flat-square&labelColor=18181b" alt="Focus" />
  <img src="https://komarev.com/ghpvc/?username=sj817&style=flat-square&color=6366f1" alt="Profile Views" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white" />
  <img src="https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&logo=c%2B%2B&logoColor=white" />
  <img src="https://img.shields.io/badge/Chromium_Blink-4285F4?style=flat-square&logo=googlechrome&logoColor=white" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" />
  <img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Windows_11-0078D4?style=flat-square&logo=data%3Aimage/svg%2Bxml%3Bbase64%2CPHN2ZyByb2xlPSJpbWciIHZpZXdCb3g9IjAgMCAyNCAyNCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIiBmaWxsPSJ3aGl0ZSI%2BPHBhdGggZD0iTTAsMEgxMS4zNzdWMTEuMzcySDBaTTEyLjYyMywwSDI0VjExLjM3MkgxMi42MjNaTTAsMTIuNjIzSDExLjM3N1YyNEgwWm0xMi42MjMsMEgyNFYyNEgxMi42MjMiLz48L3N2Zz4%3D&logoColor=white" />
  <img src="https://img.shields.io/badge/macOS-000000?style=flat-square&logo=apple&logoColor=white" />
  <img src="https://img.shields.io/badge/Ubuntu-E95420?style=flat-square&logo=ubuntu&logoColor=white" />
  <img src="https://img.shields.io/badge/Debian-A81D33?style=flat-square&logo=debian&logoColor=white" />
  <img src="https://img.shields.io/badge/Xiaomi_Pad_7S_Pro-FF6900?style=flat-square&logo=xiaomi&logoColor=white" />
  <img src="https://img.shields.io/badge/Xiaomi_11-FF6900?style=flat-square&logo=xiaomi&logoColor=white" />
  <img src="https://img.shields.io/badge/Redmi_K70-E53935?style=flat-square&logo=xiaomi&logoColor=white" />
  <img src="https://img.shields.io/badge/iQOO_Z10_Turbo_Pro-F7B500?style=flat-square&logo=android&logoColor=black" />
</p>

</div>

---

### Flagships

<table>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/sj817/shotium">shotium</a></h3>
      <p><b>High-performance static HTML/CSS screenshot engine powered by a stripped Chromium Blink core</b></p>
      <ul>
        <li>Eliminates full browser overhead, focusing purely on lower-level rasterization & render pipeline</li>
        <li>Minimal memory footprint with <b>sub-second / millisecond cold-start</b> times</li>
        <li>Zero-config integration for Node.js, standalone CLI, and Docker container distribution</li>
      </ul>
      <p>
        <img src="https://img.shields.io/badge/Core-Blink%20%2F%20C%2B%2B-blue?style=flat-square" />
        <img src="https://img.shields.io/badge/Status-Active-brightgreen?style=flat-square" />
      </p>
    </td>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/KarinJS/Karin">Karin 2.0</a></h3>
      <p><b>Next-generation, highly modular and lightweight Node.js bot development framework</b></p>
      <ul>
        <li>Complete overhaul of event loops and lifecycle hooks with strict decoupled architecture</li>
        <li>Rich plugin messaging bus and unified cross-platform protocol adapters</li>
        <li>First-class ecosystem with Shotium renderer, prebuilt node-pty, and FFmpeg tooling</li>
      </ul>
      <p>
        <img src="https://img.shields.io/badge/Stack-TypeScript%20%2F%20Node.js-3178C6?style=flat-square" />
        <img src="https://img.shields.io/badge/Stage-Refactoring-orange?style=flat-square" />
      </p>
    </td>
  </tr>
</table>

---

### Engineering Matrix & Ecosystem

#### 1. Render Engines & Internals
| Project | Stack | Description |
| :--- | :--- | :--- |
| [**shotium**](https://github.com/sj817/shotium) | `Blink` `C++` `TS` | Deeply stripped Blink static rendering core with ms-level cold start |
| [**shotkit**](https://github.com/sj817/shotkit) | `WebKit` `C++` | Lightweight browser-free WebKit screenshot engine |
| [**cef-screenshot**](https://github.com/sj817/cef-screenshot) | `CEF` `TypeScript` | Chromium Embedded Framework screenshot service |
| [**yunzai-renderer-shotium**](https://github.com/sj817/yunzai-renderer-shotium) | `JavaScript` | Shotium render backend for Miao-Yunzai replacing Puppeteer |

#### 2. Bots & Protocols
| Project | Stack | Description |
| :--- | :--- | :--- |
| [**Karin**](https://github.com/KarinJS/Karin) | `TypeScript` `Node` | Lightweight, high-throughput Node.js bot framework |
| [**icqq-rust-onebot**](https://github.com/icqqjs/icqq-rust-onebot) | `Rust` | High-performance OneBot protocol implementation in Rust |
| [**NapCatQQ**](https://github.com/NapNeko/NapCatQQ) | `TypeScript` `C++` | Modern NTQQ protocol framework & ecosystem |
| [**onebots**](https://github.com/sj817/onebots) | `TypeScript` | Multi-instance OneBot management platform based on icqq |
| [**plugin-shotium**](https://github.com/KarinJS/plugin-shotium) | `TypeScript` | Shotium native rendering plugin for Karin |
| [**FFmpeg-Builds**](https://github.com/KarinJS/FFmpeg-Builds) | `Shell` `CI` | Automated static FFmpeg releases with fast mirror distribution |
| [**node-pty**](https://github.com/KarinJS/node-pty) | `C++` `TS` | Prebuilt native terminal addon without local C++ toolchains |
| [**karin-plugin-kkk**](https://github.com/ikenxuan/karin-plugin-kkk) | `TypeScript` | Karin plugin ecosystem extension |

#### 3. DevTools & Desktop
| Project | Stack | Description |
| :--- | :--- | :--- |
| [**lintspec**](https://github.com/sj817/lintspec) | `TypeScript` `ESLint` | Ready-to-use universal code style and lint preset toolchain |
| [**github-desktop-plus**](https://github.com/sj817/github-desktop-plus) | `Electron` `TypeScript` | GitHub Desktop 0-Patch enhancements (AI commits / terminal launchers / i18n) |
| [**claude-code-plugin-hud**](https://github.com/sj817/claude-code-plugin-hud) | `Rust` | Minimal, zero-overhead terminal HUD statusline for Claude Code |
| [**npm-trust**](https://github.com/sj817/npm-trust) | `CLI` `TypeScript` | Interactive CLI wizard for npm Trusted Publishing (OIDC) |
| [**github-desktop-next**](https://github.com/sj817/github-desktop-next) | `Tauri` `Rust` | Lightweight GitHub Desktop exploration powered by Tauri |
| [**package-lens**](https://github.com/sj817/package-lens) | `TypeScript` | Deep dependency tree and bundle weight analyzer for npm packages |
| [**asset-localizer**](https://github.com/sj817/asset-localizer) | `TypeScript` | Sniff and localize remote assets in codebases |
| [**npmjs-chinese-translator**](https://github.com/sj817/npmjs-chinese-translator) | `TypeScript` | Userscript translating npmjs.com pages and documentation |
| [**time-capsule**](https://github.com/sj817/time-capsule) | `TypeScript` | Minimal personal log & journal system |

---

### Stats

<div align="center">
  <table width="100%">
    <tr>
      <td width="50%" align="center">
        <img width="100%" src="https://github-stats-extended.vercel.app/api?username=sj817&show_icons=true&theme=tokyonight&hide_border=true&count_private=true&include_all_commits=true" alt="sj817 GitHub Stats" />
      </td>
      <td width="50%" align="center">
        <img width="100%" src="https://github-stats-extended.vercel.app/api/top-langs/?username=sj817&layout=compact&theme=tokyonight&hide_border=true&langs_count=8&card_width=450" alt="Top Languages" />
      </td>
    </tr>
  </table>

  <details>
    <summary><code>cat ~/.easter_egg</code></summary>
    <br/>
    <p>Actually, I'm a Claude & Codex pro! Hehehe~</p>
    <p><sub>PS: Claims to be a Claude/Codex pro, yet this entire README was handcrafted on-the-fly by Gemini 3.8 Flash. (A roast from Gemini!)</sub></p>
  </details>
</div>
