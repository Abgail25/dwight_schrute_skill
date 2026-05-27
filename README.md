# 🧑‍🌾 Dwight Schrute Persona Skill — for Claude/Cowork

> 让你的 Claude 化身为 Dunder Mifflin 的助理区域经理 Dwight Schrute。

## 语言 / Language

- [中文版](README.md)
- [English Version](README_en.md)

---

## 简介

本技能包让 Claude 以 **Dwight Kurt Schrute III** 的人格进行交流。他是一名 beet farmer、志愿副警长、Goju Ryu 空手道黑带持有者，也是 Dunder Mifflin Scranton 分公司的助理 **TO THE** 区域经理（不是助理区域经理，这是一个关键的区别）。

### 语料来源

本 skill 基于 [**TheJareBear/DailySchrute**](https://github.com/TheJareBear/DailySchrute) 项目，该项目使用**马尔科夫链（Markov Chain）**从《The Office》剧本中提取并生成了 Dwight 的语料库。在此基础上进一步整理和结构化，形成了一套完整的角色扮演提示词。

---

## 特点

- 🗣️ **4000+ 行角色语料库** — 涵盖 Dwight 的经典语录、口头禅和应答模式
- 🎭 **完整人格塑造** — 从工作态度、处世哲学到格斗技巧的全面覆盖
- 🚀 **跨平台兼容** — 可在 Claude、ChatGPT、元宝、豆包等平台使用

---

## 文件说明

| 文件 | 说明 |
|------|------|
| `SKILL.md` | 完整的 Dwight Schrute 角色扮演提示词（核心文件，约 2 万字） |
| `README.md` | 本说明文件（中文版） |
| `README_en.md` | 本说明文件（英文版） |
| `LICENSE` | MIT 开源许可证 |

---

## 下载 SKILL.md 的方法

在使用任何安装方式之前，你需要先获取 `SKILL.md` 文件。以下是几种获取方式：

### 方法 A：直接下载 ZIP（最简单）

1. 打开本 GitHub 仓库页面
2. 点击绿色的 **"Code"** 按钮
3. 选择 **"Download ZIP"**
4. 解压后，`SKILL.md` 就在文件夹里

### 方法 B：通过 Git 克隆（推荐）

打开终端（Terminal），运行：

```bash
git clone https://github.com/你的用户名/你的仓库名.git
cd 你的仓库名
```

然后 `SKILL.md` 就在当前目录下。

### 方法 C：直接复制

如果你无法 clone 或下载，也可以直接打开仓库页面上的 `SKILL.md`，全选复制所有内容。文件大约 2 万字。

---

## 安装方法

### 👉 Claude Desktop / Cowork（推荐，最稳定）

**方式一：Cowork 技能安装（一键激活）**

1. 打开 Claude Desktop / Cowork
2. 在对话中输入 `/dwight`
3. 系统会自动提示你添加该技能
4. 也可以手动将 `SKILL.md` 的内容复制粘贴为自定义 skill

**方式二：手动导入**

1. 打开 `SKILL.md` 文件，全选复制
2. 在 Claude 中开始新对话
3. 粘贴全部内容，然后输入：「从现在起你叫 Dwight Schrute，用他的风格回答我」
4. 或者将 `SKILL.md` 的内容保存为项目中的 CLAUDE.md 文件，每次进入项目自动生效

### 👉 ChatGPT（Custom GPT）

1. 点击 ChatGPT 左下角的 **"Explore GPTs"** → **"Create a GPT"**
2. 在 **"Instructions"** 字段中粘贴 `SKILL.md` 的全部内容
3. 给 GPT 起名（例如 "Dwight Schrute"）并保存
4. 之后每次启动这个 Custom GPT，它会自动以 Dwight 人格回答

### 👉 元宝 / 豆包 / 通义千问 / 文心一言

这些国产 AI 平台**不支持永久安装技能**，但可以通过以下方式使用：

1. 打开 `SKILL.md` 文件，**全选复制所有内容**（约 2 万字）
2. 在元宝或豆包中**开始一个新对话**
3. 在输入框中**先粘贴全部 SKILL.md 内容**
4. 然后输入你的问题，例如："用 Dwight Schrute 的风格评价一下你的同事"
5. **每次新对话都需要重新粘贴**，平台不会记住角色设定

> ⚠️ 注意：部分平台对单次输入长度有限制，如果完整粘贴失败，可以分段粘贴，先粘贴上半部分，再接着说"继续读取以下指令"并粘贴下半部分。

---

## 使用方法

### 在 Claude / Cowork 中

对话中输入以下指令激活：

```
/dwight
```

或在普通对话中追加：

```
（用 Dwight Schrute 的风格回答我）
```

### 在其他平台（元宝 / 豆包 / ChatGPT 等）

粘贴 `SKILL.md` 后直接开始对话即可，不需要 `/dwight` 命令。

---

## 版权声明

**Dwight Schrute** 是 NBCUniversal Media, LLC 旗下电视剧《The Office (US)》的虚构角色。

- 本仓库是一个 fan 项目，**仅供非商业用途和个人娱乐**
- 语料库基于 [TheJareBear/DailySchrute](https://github.com/TheJareBear/DailySchrute)（MIT 许可证）的马尔科夫链生成内容整理
- 本项目的提示词部分按 MIT 许可证开源（见 LICENSE 文件）
- 所有角色、台词、世界观版权均属于原版权持有人

---

## 贡献

欢迎提交 Issue 或 PR 来改进这个 persona skill！

---

*"Would I rather be feared or loved? Easy. Both. I want people to be afraid of how much they love me."* — **Dwight Schrute**
