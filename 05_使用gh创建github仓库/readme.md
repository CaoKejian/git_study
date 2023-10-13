# 创建一个 github 仓库

## 命令行
```bash
gh repo create test --public // 创建一个公共的名字为“test”的github仓库
echo "# test" >> README.md // 添加一行代码到README.md文件
git init // 初始化git
git add README.md // 提交 README.md 文件带暂存区
git commit -m "first commit" // 将暂存区的文件提交到本地的git仓库
git branch -M master // 重命名活动分支，也可以用main
git remote add origin https://github.com/<你的Github名称>/<刚创建的文件名>.git // 将本文件添加远程仓库
git push -u origin master // 推送并更改到GitHub
```

> 到此为止 你已经成功创建并链接到Github 👍