# 使用Feature分支

## git命令
```bash
git switch -c <分支名> // 创建并切换分支
git add .
git commit -m 'feat: feature update'
git switch master // 切换回master分支，准备合并feature分支修改的内容
```
> 这时我们恰巧不需要此次修改了，则需要删除feature分支

```bash
git branch -d feature
提示： error: The branch 'feature' is not fully merged.
提示： If you are sure you want to delete it, run 'git branch -D feature'.
```
> d 参数已经不行了，提示我们强行删掉需要'D'
```bash
git branch -D feature
提示： Deleted branch feature (was b8c442f).
```