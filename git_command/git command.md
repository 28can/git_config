## 第一次上传（尽量不添加readme.md文件）

#test README.md

- 在README.md同目录下——**open git bash here**
- 建立.git文件——**git init**；
- 将文件的修改加入暂存区——**git add** （文件）；
- 将暂存区的文件修改提交到版本库——**git commit -m "message"**

message :用来简要说明这次提交的语句,每次都要提交，即备注信息

- 将当前分支名“-M：移动”到main——**git branch -M main**

- 将本地git仓库与远程的git仓库建立联系——**git remote add origin https://github.com/28can/（仓库）.git**
- 推送文件到远程git仓库——**git push -u origin main**

## 第N>1次后的上传

- **git add (文件)**
- **git status**
- **git commit -m "任意字段"**
- **git push**

## 提交其他文件

- 添加文件将之前的仓库pull 下来之后合并之后在提交——git pull https://github.com/28can/（仓库）.git
- 之后重复**第一次上传**

报错：

1. nothing to commit, working tree clean——**改变内容，空格也行**
1. [如何git上传代码避免出现! [rejected\] main -＞ main (non-fast-forward)_! [rejected] main -> main (non-fast-forward)-CSDN博客](https://blog.csdn.net/practical_sharp/article/details/131907980?ops_request_misc=%7B%22request%5Fid%22%3A%22170672588516800186571489%22%2C%22scm%22%3A%2220140713.130102334..%22%7D&request_id=170672588516800186571489&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~sobaiduend~default-1-131907980-null-null.142^v99^pc_search_result_base2&utm_term= ! [rejected]        main -> main (non-fast-forward)&spm=1018.2226.3001.4187)
1. 'git pull' before pushing again.——**git push origin main -f**

## 其他指令

Your branch is ahead of 'origin/main' by **x** commits.——**git reset --hard HEAD~x**
