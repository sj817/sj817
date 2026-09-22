<div align="right">
  <a href="./README_EN.md">English</a>
</div>

<div align="center">

# 时瑾 (sj817)

*偷得浮生半日闲，裁尽繁芜自造轮*

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

### 核心项目

<table>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/sj817/shotium">shotium</a></h3>
      <p><b>基于 Chromium Blink 内核深度裁剪的高性能静态渲染引擎</b></p>
      <ul>
        <li>剔除无用组件与完整浏览器开销，专注底层光栅化与渲染管线</li>
        <li>极低内存驻留，实现<b>毫秒级冷启动</b>，告别臃肿的无头浏览器</li>
        <li>开箱支持 Node.js、原生 CLI 与 Docker 容器化分发</li>
      </ul>
      <p>
        <img src="https://img.shields.io/badge/Core-Blink%20%2F%20C%2B%2B-blue?style=flat-square" />
        <img src="https://img.shields.io/badge/Status-Active-brightgreen?style=flat-square" />
      </p>
    </td>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/KarinJS/Karin">Karin 2.0</a></h3>
      <p><b>面向下一代架构的高并发、轻量级 Node.js 机器人开发框架</b></p>
      <ul>
        <li>彻底重构核心事件循环与生命周期，极致的模块化解耦设计</li>
        <li>提供完备的插件通信机制、统一的跨平台协议适配层</li>
        <li>配套自研 Shotium 渲染扩展与跨平台 FFmpeg / node-pty 工具链</li>
      </ul>
      <p>
        <img src="https://img.shields.io/badge/Stack-TypeScript%20%2F%20Node.js-3178C6?style=flat-square" />
        <img src="https://img.shields.io/badge/Stage-Refactoring-orange?style=flat-square" />
      </p>
    </td>
  </tr>
</table>

---

### 技术矩阵与开源生态

#### 1. 渲染内核与底层探索
| 项目 | 技术栈 | 描述 |
| :--- | :--- | :--- |
| [**shotium**](https://github.com/sj817/shotium) | `Blink` `C++` `TS` | 深度裁剪的轻量 Blink 静态渲染核心，毫秒级冷启动 |
| [**shotkit**](https://github.com/sj817/shotkit) | `WebKit` `C++` | 基于 WebKit 打造的无浏览器截图内核 |
| [**cef-screenshot**](https://github.com/sj817/cef-screenshot) | `CEF` `TypeScript` | 基于 Chromium Embedded Framework 的截图服务 |
| [**yunzai-renderer-shotium**](https://github.com/sj817/yunzai-renderer-shotium) | `JavaScript` | Miao-Yunzai 的 Shotium 渲染后端，替代 Puppeteer |

#### 2. 即时通讯与协议基建
| 项目 | 技术栈 | 描述 |
| :--- | :--- | :--- |
| [**Karin**](https://github.com/KarinJS/Karin) | `TypeScript` `Node` | 轻量高效的 Node.js 机器人应用框架 |
| [**icqq-rust-onebot**](https://github.com/icqqjs/icqq-rust-onebot) | `Rust` | 基于 Rust 构建的高吞吐 OneBot 协议端 |
| [**NapCatQQ**](https://github.com/NapNeko/NapCatQQ) | `TypeScript` `C++` | 现代 NTQQ 协议端框架与生态 |
| [**onebots**](https://github.com/sj817/onebots) | `TypeScript` | 基于 icqq 的多实例统一协议管理服务 |
| [**plugin-shotium**](https://github.com/KarinJS/plugin-shotium) | `TypeScript` | Karin 框架的 Shotium 原生渲染扩展插件 |
| [**FFmpeg-Builds**](https://github.com/KarinJS/FFmpeg-Builds) | `Shell` `CI` | 跨平台静态 FFmpeg 自动构建与国内快速镜像分发 |
| [**node-pty**](https://github.com/KarinJS/node-pty) | `C++` `TS` | 免本地编译工具链的预构建原生终端扩展 |
| [**karin-plugin-kkk**](https://github.com/ikenxuan/karin-plugin-kkk) | `TypeScript` | Karin 插件生态扩展 |

#### 3. 开发者体验与桌面增强
| 项目 | 技术栈 | 描述 |
| :--- | :--- | :--- |
| [**lintspec**](https://github.com/sj817/lintspec) | `TypeScript` `ESLint` | 开箱即用的全场景通用代码规范与配置预设 |
| [**github-desktop-plus**](https://github.com/sj817/github-desktop-plus) | `Electron` `TypeScript` | GitHub Desktop 0-Patch 增强套件（AI 提交 / 终端快速唤起 / 汉化） |
| [**claude-code-plugin-hud**](https://github.com/sj817/claude-code-plugin-hud) | `Rust` | 极低系统开销的 Claude Code 终端 HUD 状态栏 |
| [**npm-trust**](https://github.com/sj817/npm-trust) | `CLI` `TypeScript` | npm Trusted Publishing (OIDC) 交互式向导与客户端 |
| [**github-desktop-next**](https://github.com/sj817/github-desktop-next) | `Tauri` `Rust` | 基于 Tauri 替代 Electron 的轻量化桌面端探索 |
| [**package-lens**](https://github.com/sj817/package-lens) | `TypeScript` | npm 依赖层级与体积深度分析工具 |
| [**asset-localizer**](https://github.com/sj817/asset-localizer) | `TypeScript` | 本地工程远程资源嗅探与本地化重写工具 |
| [**npmjs-chinese-translator**](https://github.com/sj817/npmjs-chinese-translator) | `TypeScript` | npmjs.com 官方文档与包页面中文汉化油猴脚本 |
| [**time-capsule**](https://github.com/sj817/time-capsule) | `TypeScript` | 极简个人日记与记录系统 |

---

### 数据统计

<div align="center">
  <table border="0">
    <tr>
      <td>
        <img height="165em" src="https://github-readme-stats.vercel.app/api?username=sj817&show_icons=true&theme=tokyonight&hide_border=true&count_private=true&include_all_commits=true" alt="GitHub 统计" />
      </td>
      <td>
        <img height="165em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=sj817&layout=compact&theme=tokyonight&hide_border=true&langs_count=8" alt="常用语言统计" />
      </td>
    </tr>
  </table>

  <details>
    <summary><code>cat ~/.easter_egg</code></summary>
    <br/>
    <p>其实我是 Claude、Codex 糕手！嘿嘿嘿~</p>
    <p><sub>PS: 嘴上说是 Claude/Codex 糕手，其实这页 README 是抓 Gemini 3.8 Flash 现场打工生成的。（来自 Gemini 的吐槽！）</sub></p>
  </details>
</div>
