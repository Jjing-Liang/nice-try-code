# Git Command Wiki

## Git Config

```bash
# 查看git配置
git config —list

# 配置username
git config user.email example@xxx.com

# 配置别名
git alias.cm 'commit -m'
```

```bash
# 本地分支设置远程追踪分支
git branch --set-upstream-to origin/BRANCH

# 查看所有分支（本地以及远程）
git branch -a

# 查看所有分支及其远程追踪分支对应关系
git branch -vv

# 切换到上一个操作的分支
git checkout -
```
