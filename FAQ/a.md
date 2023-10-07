# Q: 提交一次commit以后，发现还有一次小修改需要合并进去

````
git add . # 或者指定文件
git commit --amend --no-edit
git rebase -i 也可以，但是没这个方便
````
一点小修改11
