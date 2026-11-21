# Hello +陈祥豪

提交流程：

#【仅首次使用Git执行一次】配置提交作者信息

git config --global user.name "你的名字"
git config --global user.email "你的邮箱@example.com"

 进入仓库目录

cd /d/study/git-demo

 创建 hello.md 文件

echo "# Hello 张三" > hello.md

查看仓库状态（修改文件后检查）

git status

 添加文件到暂存区（二选一，推荐指定文件，避免误提交）

git add hello.md

 再次查看状态，确认文件已经成功进入暂存区

git status

 提交到本地仓库，使用规范提交注释

git commit -m "docs: add hello.md"

git remote add origin https://github.com/你的用户名/仓库名.git

 git remote add origin git@github.com:你的用户名/仓库名.git

#第一次推送加 -u 绑定分支跟踪关系；后续推送直接 git push

git push -u origin main



==我认为：**新手阶段用 Git Bash 命令行提交比较麻烦**，需要记住多条命令、不能输错，容易忘记 `git add`、`git push` 顺序，输错参数还会报错。
但是命令行的好处：通用、所有环境都能用，适合理解 Git 底层原理，考试、学习原理时必须掌握。==




