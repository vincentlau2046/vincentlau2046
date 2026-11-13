<div align="center">

<img src="assets/atlas-logo.svg" width="72" alt="AtlasWork" />

# Atlas 全栈 AI 工作站

### 把智能建在自己的算力上

从推理底座到 Coding Agent，从昇腾工具链到本地与云端统一网关，一个产品家族全部打通。

[![atlaswork.cn](https://img.shields.io/badge/atlaswork.cn-1D6FE0?style=for-the-badge&labelColor=0F4FB3)](https://atlaswork.cn)
[![AtlasCode](https://img.shields.io/badge/AtlasCode-v0.1.87-0B7A62?style=for-the-badge)](https://github.com/vincentlau2046/AtlasCode)
[![InferFabric](https://img.shields.io/badge/InferFabric-v7.10.4-0B7A62?style=for-the-badge)](https://github.com/vincentlau2046/InferFabric)
[![MaaS](https://img.shields.io/badge/MaaS-一个_API_管所有模型-45566B?style=for-the-badge)](https://atlaswork.cn/maas/)

</div>

---

## 产品是壳，引擎是脑，算力是根

所有产品共享同一个 AtlasHarness 引擎，向下由 InferFabric 统一供给推理——自下而上打通算力、推理、技能、引擎与产品。**技能层单独成层，是 Atlas 区别于一般 Agent 框架的独有设计。**

| 层 | 成员 |
|---|---|
| **应用场景** | 编程开发 · 文档办公 · 漫画创作 · 本地推理 · Agent 编排 |
| **产品应用层** | **AtlasCode** · AtlasOffice（规划中）· AtlasComic（规划中） |
| **Agent 引擎层** | AtlasHarness 引擎 · 多智能体编排 · Skills 运行时 |
| **技能层** | 昇腾三总纲路由 · 39 条技能路径 · 官方 Marketplace 自动装配 |
| **推理网关层** | **InferFabric** · 9 引擎适配器 · OpenAI / Anthropic 双协议 · 三态 GPU 状态机 |
| **算力层** | NVIDIA Blackwell（RTX 5090 · NVFP4）· 昇腾 NPU 工具链 · 云端 9 预设 |

> 自上而下：场景驱动产品，产品建在同一个引擎上；技能按需装配，推理统一供给，算力本地与云端一体。

**技能层三总纲**：[ascend-doctor](https://atlaswork.cn/)（故障分诊路由）· ascend-optimism（性能优化路由）· ascend-opdev（算子开发路由）——三个总纲先分诊、再路由，39 条技能路径与官方 Marketplace 33 个技能包按需自动装配。

## 产品矩阵

| 产品 | 状态 | 一句话 |
|---|---|---|
| [**AtlasCode**](https://github.com/vincentlau2046/AtlasCode) | ✅ v0.1.87 | 面向国产计算生态的通用 Coding Agent：CLI + TUI，完整 AI 辅助编程能力，昇腾 NPU 域包可插拔叠加 |
| [**InferFabric**](https://github.com/vincentlau2046/InferFabric) | ✅ v7.10.4 | 为 Blackwell 单卡设计的本地推理平台 + 统一 Gateway：模型即插件，本地与云端统一，一个 API 管所有 |
| [**AtlasWork MaaS**](https://atlaswork.cn/maas/) | ✅ 已上线 | 一个 API，管所有模型：OpenAI 与 Anthropic 双协议同端口，云端大模型统一路由，一个密钥全部打通 |
| **AtlasOffice** | 🚧 规划中 | 文档办公产品，建在同一引擎之上 |
| **AtlasComic** | 🚧 规划中 | 漫画创作产品，建在同一引擎之上 |

## 硬指标

| **1981** | **9** | **600K+** | **91.7s → 9.77s** |
|:---:|:---:|:---:|:---:|
| 项测试全绿（全量回归） | 引擎适配器：vLLM / NInfer / SGLang / Ollama / ComfyUI 等 | token KV 池 · MTP 投机解码 · NVFP4 单卡 27B | 重启收养拒连时间（SIGTERM 有界排空 + 三态引擎收养） |

## 快速开始

```bash
# AtlasCode · Coding Agent（Node ≥ 20）
npm i -g @atlasharness/atlascode
```

- [InferFabric](https://github.com/vincentlau2046/InferFabric)：Python 单文件应用，OpenAI + Anthropic 双协议 `:8999/v1`，本地与云端同一路由
- [AtlasWork MaaS](https://atlaswork.cn/maas/)：登录控制台获取 `sk-atlas-` 密钥，任意 OpenAI SDK / Claude Code 直连

---

© 2026 AtlasWork · [atlaswork.cn](https://atlaswork.cn) · 产品是壳，引擎是脑，算力是根
