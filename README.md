# hello-world

此仓库用于练习GitHub工作流程
li 软件工程

## 项目目的

通过小步修改和提交，熟悉 Git 版本管理与 GitHub 协作流程，记录学习过程。

## 当前练习内容

- 编写和完善 README，练习 Markdown 基本语法。
- 创建分支、提交修改，并通过 Pull Request（PR）查看和讨论变更。
- 阅读提交历史，理解每次修改的目的。

## 建议的 Git 工作流

1. 切换到 `main`，使用 `git pull --ff-only` 同步最新内容。
2. 使用 `git switch -c docs/update-readme` 创建练习分支；每次任务使用清晰且不同的分支名。
3. 完成一项小修改，用 `git status` 和 `git diff` 检查变更。
4. 使用 `git add README.md` 暂存文件，再用 `git commit -m "docs: 完善 README"` 提交。
5. 使用 `git push -u origin docs/update-readme` 推送分支，并在 GitHub 创建面向 `main` 的 PR，说明修改内容和原因。
6. 检查 PR 差异并处理反馈，确认后合并；回到 `main` 拉取最新内容，清理已合并的练习分支。

## 后续可练习的任务

- [ ] 创建一个 Issue，描述学习目标和完成标准。
- [ ] 添加一份学习笔记，通过 PR 完成一次文档更新。
- [ ] 在练习分支中制造并解决一次简单的合并冲突。
- [ ] 在练习分支中使用 `git revert` 撤销一次提交，观察历史变化。
- [ ] 添加一个简单示例程序，练习代码修改与评审。
