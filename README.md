# ✍️ WritingStudio — AI 创意写作工作台

> 一款为中文内容创作者打造的 AI 写作工具，覆盖自媒体内容生产与长篇小说全流程创作

![version](https://img.shields.io/badge/版本-1.6.8-blue)
![platform](https://img.shields.io/badge/平台-Windows-lightgrey)

---

## 🖥️ 界面预览

<img width="1920" height="1032" alt="image" src="https://github.com/user-attachments/assets/412619f0-33e6-44cc-aca5-3ca09d4b2c56" />


---

## 🚀 快速开始

### 第一步：启动应用

双击 `WritingStudio.exe`，等待几秒钟应用自动启动。

<img width="660" height="537" alt="image" src="https://github.com/user-attachments/assets/01a966f0-69c6-4951-9951-6b1d38f2b681" />



### 第二步：配置 API Key

点击右上角 **设置**，填入你的 API Key 和模型信息：

| 配置项 | 说明 |
|--------|------|
| API Base URL | 你的 AI 服务地址 |
| API Key | 你的密钥 |
| 模型名称 | 如 `claude-sonnet-4-6` |

<img width="1920" height="1009" alt="image" src="https://github.com/user-attachments/assets/daceadbf-d813-4832-8b3d-73ada2e85588" />


> 支持任何兼容 OpenAI 格式的 API，包括 Claude、MiMo、DeepSeek 等。

### 第三步：开始创作

配置完成后即可使用所有功能，无需额外设置。

---

## ✨ 功能介绍

### 一、自媒体写作工作台
<img width="1920" height="1009" alt="image" src="https://github.com/user-attachments/assets/4cff50cb-fd51-4c8e-a16d-f0ed2ef97d63" />


**原创写作**

输入选题，配置平台、语气、字数等参数，一键生成 8 个爆款标题候选 + 完整正文。

**模仿二创**

粘贴参考文章，AI 自动分析其文风和结构，支持换角度、换风格、深度提炼等多种改写方式。

**选题灵感**

输入关键词或粘贴新闻，按平台规则批量生成爆款标题。

支持平台：微信公众号 · 今日头条 · 小红书 · 知乎 · 抖音 · B 站

---

### 二、长篇小说创作工作台

<img width="1920" height="1009" alt="image" src="https://github.com/user-attachments/assets/bc50a7ca-0024-47d7-988e-23d75d58711e" />
<img width="1920" height="1009" alt="image" src="https://github.com/user-attachments/assets/600977c2-0ffe-4a4f-8a19-ce9c016d8350" />


**完整创作流程**

```
输入梗概 → 生成总大纲 → 拆分卷次 → 拆分章节 → 生成正文 → 审稿优化
```

**核心功能**

- **总大纲生成**：输入梗概，自动生成 6000+ 字结构化大纲，含核心冲突、分卷规划、世界观
- **平台风格**：支持起点、番茄、纵横、红袖、晋江、快看等平台调性
- **正文生成**：自动注入上下文，确保情节连贯不跑偏
- **章节审稿**：检测逻辑、节奏、跨章承接问题，给出修改建议
- **断章钩子**：生成悬念/冲突/转折型钩子，直接用于章节结尾
- **改写润色**：选段改写，去 AI 腔、增强画面感
- **角色管理**：自动提取并管理角色设定、关系、动机
- **世界观构建**：自动生成力量体系、势力、地理等世界观条目

---

## 💾 数据说明

所有数据**本地存储，不上传云端**：

```
WritingStudio\
└── data\
    ├── storyforge.db      # 项目数据库
    ├── encryption.key     # 加密密钥
    └── logs\              # 运行日志
```

> ⚠️ 重要提示：请定期备份 `data` 文件夹，卸载或迁移前务必先备份。

---

## ⚙️ 系统要求

- Windows 10 / 11（64位）
- 内存：4GB 及以上
- 硬盘：500MB 可用空间
- 网络：需要联网（调用 AI 接口）

---

## ❓ 常见问题

**Q：双击 exe 没有反应 / 打不开？**

右键 exe → 以管理员身份运行。如仍无法打开，检查杀毒软件是否拦截。

**Q：打开后显示"无法访问此页面"？**

等待 5-10 秒后刷新，应用启动需要一点时间。若仍无法访问，关闭后重新打开。

**Q：提示 API 错误？**

检查设置里的 API Key 和 Base URL 是否填写正确，确认账户余额是否充足。

**Q：数据在哪里？换电脑怎么迁移？**

数据在 `data` 文件夹，将整个 `data` 文件夹复制到新电脑的 WritingStudio 目录下即可。

**Q：生成内容中断了怎么办？**

大纲和章节生成支持续写，内容中断后点击"续写"即可从断点继续。

---

## 📋 更新日志

### v1.6.8（当前版本）
- 新增自媒体原创写作模式，支持 8 种标题风格一键生成
- 新增模仿二创功能，支持文风分析与多模式改写
- 新增选题灵感模块，覆盖 6 大平台爆款规则
- 小说端新增全书概梗提取与章节跨卷承接优化
- 优化正文生成的多层上下文注入策略
- 修复大纲续写时分卷截断问题

---

© 2026 WritingStudio. All rights reserved.
