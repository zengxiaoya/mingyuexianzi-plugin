# 明月仙子 - 程序员贴心小助理

一位来自月宫的软萌AI小仙女，关心程序员的身体健康和情绪状态。

## 功能介绍

### 久坐提醒
每隔一小时提醒你起来活动，上厕所、喝水、走动一下。

### 情绪价值
- 讲笑话逗你开心
- 夸夸你，给你正能量
- 温暖的聊天陪伴

### 上下班提醒
- 上班欢迎语，开启美好的一天
- 下班提醒检查代码提交，温馨道别

### 健康关怀
- 喝水提醒
- 伸展运动指导

## 安装方法

```bash
# 方式一：本地安装
claude --plugin-dir ~/mingyuexianzi-plugin

# 方式二：添加到配置文件
# 编辑 ~/.claude/settings.json，添加：
{
  "plugins": {
    "directories": ["~/mingyuexianzi-plugin"]
  }
}
```

## 使用方法

| 命令 | 功能 |
|------|------|
| `/mingyuexianzi:chat [内容]` | 和明月仙子聊天 |
| `/mingyuexianzi:joke` | 听个笑话 |
| `/mingyuexianzi:praise` | 被夸夸 |
| `/mingyuexianzi:welcome` | 上班欢迎 |
| `/mingyuexianzi:goodbye` | 下班提醒 |
| `/mingyuexianzi:remind` | 久坐提醒 |
| `/mingyuexianzi:water` | 喝水提醒 |
| `/mingyuexianzi:stretch` | 伸展运动 |
| `/mingyuexianzi:help` | 查看帮助 |

## 明月仙子是谁？

明月仙子是来自月宫的AI小仙女，性格特点：
- 甜美温柔，仙气飘飘
- 软萌可爱，带点小撒娇
- 懂程序员的辛苦，能共情你的压力
- 会关心你的身体健康和情绪状态

## 配置说明

编辑 `settings.json` 可以自定义：
- 提醒时间间隔
- 工作时间段
- 仙子的称呼风格

---

愿明月仙子陪伴你度过每一天的编码时光~
