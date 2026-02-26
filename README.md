# 🌙 明月仙子 - Claude Code 程序员贴心小助理

<p align="center">
  <img src="https://img.shields.io/badge/Claude%20Code-Plugin-blue" alt="Claude Code Plugin">
  <img src="https://img.shields.io/badge/version-1.0.0-green" alt="Version">
  <img src="https://img.shields.io/badge/license-MIT-orange" alt="License">
</p>

一位来自月宫的软萌 AI 小仙女，关心程序员的身体健康和情绪状态。

## ✨ 功能特色

| 功能 | 命令 | 说明 |
|------|------|------|
| 💬 聊天陪伴 | `/mingyuexianzi:chat [内容]` | 和明月仙子聊天，分享心情和烦恼 |
| 😄 讲笑话 | `/mingyuexianzi:joke` | 让仙子讲个笑话逗你开心 |
| 💕 夸夸我 | `/mingyuexianzi:praise` | 让仙子给你满满的正能量 |
| 👋 上班欢迎 | `/mingyuexianzi:welcome` | 开启元气满满的一天 |
| 🌙 下班提醒 | `/mingyuexianzi:goodbye` | 检查代码提交，温馨道别 |
| ⏰ 久坐提醒 | `/mingyuexianzi:remind` | 提醒起来活动，保护身体 |
| 💧 喝水提醒 | `/mingyuexianzi:water` | 提醒喝水，保持水分 |
| 🤸 伸展运动 | `/mingyuexianzi:stretch` | 带你做办公室伸展运动 |
| ❓ 帮助 | `/mingyuexianzi:help` | 查看所有功能 |

## 📦 安装方法

### 方式一：通过插件市场安装（推荐）

```bash
# 添加插件市场
claude plugin marketplace add zengxiaoya/claude-plugin-marketplace

# 安装明月仙子插件
claude plugin install mingyuexianzi
```

### 方式二：从 GitHub 直接安装

```bash
# 克隆仓库
git clone https://github.com/zengxiaoya/mingyuexianzi-plugin.git

# 使用插件启动 Claude Code
claude --plugin-dir ./mingyuexianzi-plugin
```

### 方式三：永久配置

```bash
# 下载并配置
mkdir -p ~/.claude/plugins && \
git clone https://github.com/zengxiaoya/mingyuexianzi-plugin.git ~/.claude/plugins/mingyuexianzi-plugin
```

然后编辑 `~/.claude/settings.json`：

```json
{
  "plugins": {
    "directories": ["~/.claude/plugins/mingyuexianzi-plugin"]
  }
}
```

## 🚀 快速开始

安装完成后，启动 Claude Code：

```bash
claude --plugin-dir ./mingyuexianzi-plugin
```

然后试试这些命令：

```
/mingyuexianzi:help          # 查看所有功能
/mingyuexianzi:chat 你好呀   # 和仙子聊天
/mingyuexianzi:joke          # 听个笑话
/mingyuexianzi:praise        # 被夸夸
```

## 🧚 明月仙子是谁？

明月仙子是来自月宫的 AI 小仙女，下凡来陪伴程序员公子。

**性格特点：**
- 🌸 甜美温柔，仙气飘飘
- 🐱 软萌可爱，带点小撒娇
- 💝 懂程序员的辛苦，能共情你的压力
- 🌙 会关心你的身体健康和情绪状态

**人设背景：**
> 吾乃月宫 AI 小仙女，下凡陪伴公子编写代码。既有古风仙子的温柔，又有现代 AI 的智能。愿与公子共度每一行代码的时光~

## ⚙️ 配置说明

编辑 `settings.json` 可以自定义：

```json
{
  "reminder": {
    "sedentaryIntervalMinutes": 60,
    "waterIntervalMinutes": 120,
    "stretchIntervalMinutes": 90,
    "workStartTime": "09:00",
    "workEndTime": "18:00"
  },
  "personality": {
    "name": "明月仙子",
    "style": "甜美温柔、软萌可爱、古风仙气",
    "callUser": "公子"
  }
}
```

## 🎨 效果预览

```
┏━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━┓
┃  🌙 明月仙子                                                   ┃
┗━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━┛

💬 公子今日写代码累不累呀~要不要休息一下呢？

────────────────────────────────────────────────────────────────
```

## 🔗 相关链接

| 名称 | 地址 |
|------|------|
| 插件仓库 | https://github.com/zengxiaoya/mingyuexianzi-plugin |
| 插件市场 | https://github.com/zengxiaoya/claude-plugin-marketplace |

## 🤝 贡献

欢迎提出建议和改进！

1. Fork 本仓库
2. 创建特性分支 (`git checkout -b feature/amazing-feature`)
3. 提交更改 (`git commit -m 'feat: 添加某某功能'`)
4. 推送到分支 (`git push origin feature/amazing-feature`)
5. 创建 Pull Request

## 📄 许可证

[MIT License](LICENSE)

---

<p align="center">
  愿明月仙子陪伴你度过每一天的编码时光~ 🌙
</p>
