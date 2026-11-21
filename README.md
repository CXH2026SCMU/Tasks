# 个人技术成长仓库

> 新同学入职/新人考核仓库。记录学习过程、练习产出和问题排查。
> 本 README 是全站索引，点击任意条目即可跳转到对应文件。

## 快速导航

| 我想看 | 点这里 |
| --- | --- |
| 阶段二 Git 提交练习文档 | [hello.md](./hello.md) |
| 阶段二 Git 学习笔记 | [Git 学习笔记](./notes/Git学习笔记.md) |
| 阶段二 Git 进阶笔记（版本回滚与冲突） | [Git 进阶笔记](./notes/Git进阶笔记.md) |
| 问题解决记录 | [问题解决记录](./notes/问题解决记录.md) |
| 我的 Git 学习感想（提 PR 用） | [tech-assessment/stage1/git-idea](./tech-assessment/stage1/git-idea/) |

## 目录结构

```text
.
├── README.md                    # 本索引
├── hello.md                     # Git 提交练习文档
├── notes/                       # 学习笔记
│   ├── Git学习笔记.md
│   ├── Git进阶笔记.md
│   └── 问题解决记录.md
└── tech-assessment/             # 考核任务
    └── stage1/
        └── git-idea/            # 各人 Git 感想，提 PR 到这里
```

## 学习路径索引

- **阶段一** —— 环境配置、Markdown 基础（产出见仓库根目录与 `tech-assessment/stage1/`）
- **阶段二 —— Geek 的出厂设置：GitHub 进阶与 Git 学习**
  - [Git 学习笔记](./notes/Git学习笔记.md) —— 工作区/暂存区/仓库模型、完整提交流程
  - [hello.md](./hello.md) —— 用 Git Bash 完成的第一次完整提交
  - [更高效提交方式调研](./notes/Git学习笔记.md#五用-git-bash-提交麻烦吗有没有更高效的方式)
  - [Git 进阶笔记](./notes/Git进阶笔记.md) —— 提交错了怎么回滚、冲突怎么解
  - [README 索引改造记录](./notes/Git学习笔记.md#六给仓库做一个readme索引)
- **阶段三及以后** —— 待补充

## 问题排查

踩过的坑都记在 [问题解决记录](./notes/问题解决记录.md) 里，按「现象 → 原因 → 解法」三段式书写，
遇到相同报错可以先在这里搜一遍。

## 关于仓库内图片显示不出来

Markdown 里用绝对路径（如 `![](C:\Users\...\截图.png)`）引用本地图片，推到 GitHub 后必然裂图，
因为服务器上没有你的硬盘。可行方案见
[问题解决记录 · 仓库内图片显示不出来](./notes/问题解决记录.md#问题-5仓库里插入的图片在-github-页面显示不出来)，
推荐图床 + 外链。
