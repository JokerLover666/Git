# Git 练习仓库

这是我用来学习 / 练习 Git 的本地仓库。

## 环境

- Git for Windows `2.56.0.windows.1`（安装路径 `C:\Program Files\Git`）
- 默认分支：`main`
- 提交身份：`JokerQAQ <2750747619@qq.com>`（写在全局配置 `C:\Users\27507\.gitconfig`）

## 常用命令速查

```bash
git status              # 看当前状态（最常用，先看它再动手）
git add <文件>          # 把改动放进暂存区；git add . 表示当前目录全部
git commit -m "说明"    # 提交（务必带 -m，否则会打开 VS Code 编辑器）
git log --oneline       # 查看提交历史
git diff                # 看还没 add 的改动内容
git restore <文件>      # 丢弃工作区里未提交的改动
```

## 说明

`__pycache__`、虚拟环境 `.venv`、`.env` 等不需要版本管理的文件已在 `.gitignore` 中排除，
它们不会被 `git add .` 误加入仓库。
