# yan.github.io

张宇栋的个人工作与学习文档库。

## 项目简介

本项目基于 [MkDocs](https://www.mkdocs.org/) 构建，用于存储和展示个人工作记录与学习笔记。

## 目录结构

```
docs/
├── index.md          # 首页
├── work/
│   ├── index.md      # 工作文档概览
│   ├── projects.md   # 项目记录
│   └── meetings.md   # 会议纪要
└── study/
    ├── index.md      # 学习笔记概览
    ├── tech.md       # 技术学习笔记
    └── reading.md    # 读书笔记
```

## 本地运行

```bash
pip install mkdocs-material
mkdocs serve
```

访问 http://localhost:8000 预览站点。

## 部署

```bash
mkdocs gh-deploy
```
