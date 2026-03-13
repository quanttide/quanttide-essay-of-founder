# 量潮创始人札记

本项目是创始人实时思考的切片记录，以 Markdown 格式编写，使用 Jupyter Book 构建。

## 为什么叫"札记"？

这里没有完美的商业教科书，只有一家创业公司在进化路上的实时切片。
写下来，是为了不遗忘；公开，是为了接受世界的审计。

## 许可证

本项目采用 [CC BY 4.0](LICENSE) 许可证。

## 构建命令

```bash
# 构建 HTML
jupyter-book build index.md --site

# 清理构建
jupyter-book clean .
```

## 目录结构

```
essay/
├── README.md       # 本文件
├── CONTRIBUTING.md # 贡献指南
├── AGENTS.md       # Agent 工作指南
├── CHANGELOG.md    # 版本记录
├── work/           # 工作札记
│   ├── workflow/   # 工作流
│   └── delivery/   # 交付
└── *.md            # 主题文档
```
