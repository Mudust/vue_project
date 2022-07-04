# Git的基本使用

## 1.Git的基本使用

### 1.1在你项目的根目录下初始化
```bash
git init

```
### 1.2将你的项目和远程项目创建连接
```bash
git remote add origin https://github.com/Mudust/vue_project.git

```
Github是一个代码仓库托管平台，gitee码云也是，而git是个工具，可以用于任何Git托管平台

### 1.3添加指定所有文件
. 在根目录添加所有文件
```bash
git add .

```

### 1.4提交文件入仓库并添加注释信息

```bash
git commit -m "msg 注释"

```

### 1.5创建并切换到主分支
main 是分支的名称

```bash
git branch -M main

```

### 1.6推送到远程仓库
```bash
git push -u origin main

```
