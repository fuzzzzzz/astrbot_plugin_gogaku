# 日语学习助手 AstrBot 插件 (astrbot_plugin_gogaku)

> 🇯🇵 一个面向日语学习者的互动型群组学习插件，集签到、刷题、背词与积分系统于一体，让学习更有动力、更有趣、更社交化。

## 功能特性

- ✅ **每日签到** — 每天打卡记录学习进度，养成学习习惯
- 📝 **JLPT 刷题** — 按级别分类的模拟练习题 (N5-N1)
- 📖 **词汇背诵** — 互动式单词记忆与复习功能
- 🏆 **积分排行** — 学习积分与排行榜激励，让学习更有竞争感

## 安装

1. 将本仓库克隆到 AstrBot 的插件目录：
   ```bash
   cd AstrBot/data/plugins
   git clone https://github.com/fuzzzzzz/astrbot_plugin_gogaku.git
   ```
2. 安装依赖：
   ```bash
   pip install -r requirements.txt
   ```
3. 重启 AstrBot 或在 WebUI 中重载插件

## 使用

| 命令 | 说明 |
|------|------|
| `签到` | 每日学习签到 |
| `刷题` | JLPT 练习题 |
| `背词` | 词汇记忆 |
| `排行` | 查看积分排行榜 |

## 开发状态

🚧 本插件正在积极开发中，核心功能逐步完善。欢迎提交 Issue 和 Pull Request！

## 配置

编辑 `metadata.yaml` 可修改插件元信息。

## 开发指南

请参考 [AstrBot 插件开发文档](https://docs.astrbot.app/dev/star/plugin-new.html) 了解插件开发规范。

## License

MIT License — 详见 [LICENSE](LICENSE) 文件。

## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=fuzzzzzz/astrbot_plugin_gogaku&type=Date)](https://star-history.com/#fuzzzzzz/astrbot_plugin_gogaku&Date)
