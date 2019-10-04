### git使用入门
> git配置

```
1、查看配置列表     git config --list
2、邮箱用户名配置   git config --global user.name/email "值"
```
> git的状态与添加

```
1、git有三个区，分别是：工作区、暂存区、历史记录区
2、将文件添加到暂存区  git add 文件名/.(.表示添加当前目录)
3、提交到仓库   git commit -m "注释"
4、版本回退     git reset --hard HEAD^(^有几个回退几次)
   查看版本id   git reflog
                git reset --hard 查到的版本id
```
> git的分支与合并

```
1、查看所有分支      git branch
2、创建分支          git branch 分支名
3、切换分支          git checkout 分支名
4、推送分支到远程仓库  git push origin 分支名
5、合并分支          git merge 分支名
6、解决冲突
```
> git与github

```
1、查看有没有ssh      cd ~/.ssh
2、生成ssh           ssh-keygen -t rsa -C 邮箱
3、把公钥复制到GitHub上
4、检查连接是否成功    ssh -T git@github.com
5、克隆远程仓库到本地   git clone 需要克隆的地址
6、推送本地仓库到GitHub   git remote add origin https://github.com/dreams-liu/lzz.git
git push -u origin master（推送分支名）
7、把远程仓库拉到本地仓库  git pull
```
