# git命令

# git使用

## git 安装

- 百度搜索git,傻瓜式安装
- next -> next  -> next



## 配置git远程ssh 

- 创建密钥键，在win10 poweshell下执行

  ```shell
  ssh-keygen -t rsa –C “youremail@example.com”
  ```

- 在用户目录下的.ssh目录下生成密钥键值
- 将公钥 id_rsa.pub 内容拷贝到 github中ssh设置
- 

## git 命令

| 命令                              | 说明                                     |                                                              |
| --------------------------------- | ---------------------------------------- | ------------------------------------------------------------ |
| git  config  --global  user.name  | 配置git用户名                            | git  config  --global  user.name “fily”                      |
| git  config  --global  user.email | 配置git用户邮箱                          | git  config  --global  user.email “12345@qq.com”             |
| git  init                         | 创建一个仓库                             | git  init                                                    |
| git add                           | 添加文件到版本库                         | git add  1.txt 2.txt                                         |
| git commit -m                     | 将git add内容，提交到仓库                | git commit -m  "第一次提交(我是注释)"                        |
| git status                        | 查看哪些文件被修改                       | git status                                                   |
| git diff  文件名                  | 显示具体不同                             | git diff 1.txt                                               |
| git log                           | 查看提交版本历史                         | git log    \|   git log –pretty=oneline                      |
| git  reset --hard HEAD^           | 回退到上一个版本                         | git reset --hardd HEAD~100 （回退最早版本，也可以通过版本号恢复） |
| git  reflog                       | 获取所有版本号                           | git  reflog                                                  |
| git checkout                      | 撤销修改                                 | git checkout --readme.txt                                    |
| git remote add origin             | 与远程仓库关联                           | git remote add origin https://fily/cmd.git                   |
| git push origin master            | 把本地master分支的最新修改推送到github上 | git push origin master                                       |
| git clone                         | 克隆远程仓库                             | git clone https://fily/cmd.git                               |
| git checkout -b dev               | 创建dev分支，然后切换到dev分支上         | git checkout -b dev                                          |
| git branch                        | 查看分支                                 | git branch                                                   |
| git merge dev                     | 合并当前与dev分支                        | git merge dev                                                |
|                                   |                                          |                                                              |
|                                   |                                          |                                                              |

