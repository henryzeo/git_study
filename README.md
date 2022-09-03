# git_study
git相关的学习

# 两种场景
## 场景一、 已有项目，已有远程仓库
1. git clone xxxx(项目地址)
2. 学习/开发项目
3. git add .
4. git commit -m ""
5. git pull  (防止仓库其他成员在你clone之后push)
6. git push

## 场景二、 自己创建全新项目
### 方案一
1. 在远程仓库创建项目
2. git clone xxxx(项目地址)
3. 搭建环境
4. git add .
5. git commit -m ""
6. git push



### 方案二
1. 在远程仓库创建项目
2. 在本地初始化 git init
3. 搭建环境
4. git remote add origin xxxx(项目地址)
5. git branch --set-upstream-to=origin/main(master)
6. git fetch
7. git merge --allow-unrelated-histories
8. git push