# AI OSS Intern Project

AI 开源实习计划 · 想开了 (OpenTalk) · OSS Investment Scorecard

三个互联项目的主 context 层，每周自动更新。

## 目录结构

```
context/
  🗺️ 项目全景图 — AI开源实习+想开了.md   ← 主 context 文件（每周自动更新）
updates/
  YYYY-MM-DD.md                            ← 每次自动更新的变更记录
```

## 三个项目

| 项目 | 定位 | 链接 |
|------|------|------|
| **r2cn.dev** | AI 开源实习平台，连接学生与开源项目 | r2cn.dev |
| **想开了 OpenTalk** | 微信公众号，采访开源项目 founder | 微信搜索「想开了」 |
| **OSS Investment Scorecard** | 5维度 VC 评估框架 | [GitHub](https://github.com/lucy-cxy/oss-investment-scorecard) |

## 自动更新

每周日 22:00（台北时间）由 Claude remote agent 自动运行，扫描：
- GitHub 上三个相关 repo 的新动态（Issue、PR、Star）
- 更新主 context 文件，并在 `updates/` 目录留下变更记录

## Obsidian 同步

本 repo 与本地 Obsidian vault 同步：
`/Users/lucycxy/Lucy's Ideas/AI 开源实习计划/`

安装 [Obsidian Git](https://github.com/denolehov/obsidian-git) 插件后，每次打开 Obsidian 自动 pull 最新内容。
