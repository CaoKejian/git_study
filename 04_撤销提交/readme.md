# 撤销提交

## git命令

> 撤销‘暂存区’的文件
![Alt text](image.png)  
```bash
git reset test/index.js // 撤销‘暂存区’的 test/index.js 撤销到‘更改’

git reset // 将暂存区的文件 ‘全部’ 撤销
```
![Alt text](image-1.png)  

> 撤销‘修改’的文件
### 确保 index.js 已经提交过commit，
![Alt text](image-2.png)
![Alt text](image-3.png)
```bash
git checkout -- test/index.js // git checkout -- 这个命令其实是“恢复”到版本控制里的代码【删除或恢复】
```