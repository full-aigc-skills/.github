# Full-AIGC-Skills

<div align="center">

<img src="./assets/banner.svg" alt="Full-AIGC-Skills Banner" width="100%" />

# 🎨 面向 AI Coding Agent 的全栈 AIGC 技能生态

[![Repos](https://img.shields.io/badge/Repos-0-blue?style=flat-square)](#)
[![SKILL.md](https://img.shields.io/badge/SKILL.md-0+-green?style=flat-square)](#)
[![License](https://img.shields.io/badge/License-Apache%202.0-orange?style=flat-square)](LICENSE)
[![Spec](https://img.shields.io/badge/Spec-Agent_Skills-purple?style=flat-square)](https://agentskills.io/)

</div>

---

## 🧭 关于本组织

**Full-AIGC-Skills** 是一个面向 AI Coding Agent 的全栈 AIGC（AI Generated Content）技能生态，涵盖**文本生成、图像生成、音频合成、视频创作、3D 建模、多模态融合**等 AIGC 核心领域。

每个 Skill 遵循 [Agent Skills 规范](https://agentskills.io/)，以 `SKILL.md` 为载体，覆盖从**提示词工程**到**内容生成**到**后期处理**的完整 AIGC 工作流。

### 核心理念

> **Skills 标准化封装（SKILL.md） · Skills 跨平台发现与复用 · Skills 提示工程**

---

## 📦 技能分类

| 分类 | 仓库数 | 说明 |
|------|--------|------|
| 🎨 **图像生成** | - | Stable Diffusion, Midjourney, DALL·E, ComfyUI, SDXL 等 |
| ✍️ **文本创作** | - | LLM 写作、翻译、摘要、文案、代码生成等 |
| 🎵 **音频合成** | - | TTS、音乐生成、音效合成、语音克隆等 |
| 🎬 **视频创作** | - | 视频生成、数字人、动画制作、视频编辑等 |
| 🏗️ **3D 生成** | - | 3D 模型生成、纹理合成、场景构建等 |
| 🎭 **多模态融合** | - | 图生文、文生图、跨模态检索、多模态对话等 |
| 🔧 **工具与平台** | - | HuggingFace, Replicate, Runway, Civitai 等平台技能 |
| 📐 **工程化交付** | - | AIGC Pipeline、模型部署、推理优化、质量评估等 |

---

## 🚀 快速开始

```bash
# 克隆技能仓库
git clone https://github.com/full-aigc-skills/<skill-repo>.git

# 将技能目录添加到你的 AI Coding Agent 配置中
# Claude Code 示例：
# 设置 → Skills → 添加技能目录
```

> 支持 **Claude Code、Cursor、Codex、Antigravity、CodeBuddy、Qoder、Windsurf、Trae** 等主流 AI Coding 平台。

---

## 📁 Skill 结构规范

```
skills/<group>-skills/<skill>/
├── SKILL.md      # 必需：技能定义文件
├── examples/     # 可选：示例
├── references/   # 可选：参考资料
├── scripts/      # 可选：辅助脚本
└── assets/       # 可选：资源文件
```

---

## 🤝 贡献指南

欢迎贡献 AIGC 技能！请遵循以下流程：

1. **Fork** 对应的技能仓库
2. 创建新的 Skill 或改进现有 Skill
3. 确保 `SKILL.md` 符合规范
4. 提交 **Pull Request**

> 新技能提案请在 [Discussions](https://github.com/orgs/full-aigc-skills/discussions) 中发起。

---

## 📄 许可协议

本组织下所有项目均采用 [Apache 2.0](LICENSE) 开源许可协议。

---

<div align="center">

**Made with ❤️ by AIGC Skills Community**

</div>
