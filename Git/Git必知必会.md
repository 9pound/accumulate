

分支操作

新建分支

git branch verify_v4

分支切换

git checkout verify_v4



新建并切换到分支

git checkout -b verify_v4 



删除分支

git branch -d  verify_v4



看每一个分支的最后一次提

交，可以运行 git branch -v



分支合并

git checkout master

git merge verify_v4

当你试图合并两个分支

时， 如果顺着一个分支走下去能够到达另一个分支，那么 Git 在合并两者的时候， 只会简单的将指针向前推进

（指针右移），因为这种情况下的合并操作没有需要解决的分歧——这就叫做 “快进（fast-forward）”