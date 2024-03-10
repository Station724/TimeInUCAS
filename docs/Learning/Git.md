# Getting Started with Git

### 1. Basic Commands [(link)](https://www.runoob.com/note/56524)

#### 1.1 创建版本库

```bash
git clone <url>
git init
```

#### 1.2 修改和提交

```bash
git status
git diff
git add .
git add <file>
git mv <old> <new>  # 改名
git rm <file> 
git rm --cached <file> 
git commit -m "commit message"
git commit --amend 
```

#### 1.3 查看提交历史

```bash
git log
git log -p <file>
```

#### 1.4 撤销

```bash
git reset --hard HEAD
git checkout HEAD <file>
git revert <commit>
```

#### 1.5 分支与标签

```bash
git branch
git checkout <branch/tag>
git branch <new-branch>
git branch -d <branch>
git tag
git tag <tagname>
git tag -d <tagname>
```

#### 1.6 合并与衍合

```bash
git merge <branch>
git rebase <branch>
```

#### 1.7 远程操作

```bash
git remote -v
git remote show <remote>
git remote add <remote> <url>
git fetch <remote>
git pull <remote> <branch>
git push <remote> <branch>
git push <remote> :<branch/tag-name>
git push --tags
```



### 2. Other Commands

#### 2.1 Build an empty branch [(link)](https://zhuanlan.zhihu.com/p/453126177)

```bash
git checkout --orphan branch_name 
git rm -rf . 
```



















