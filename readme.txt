Git is a distributed version control system.
Git is free software distributed under the GPL.
Git has a mutable index called stage.

Git tracks changes.
执行上面的命令，没有任何显示，这就对了，Unix的哲学是“没有消息就是好消息”，说明添加成功
git commit -m "wrote a readme file"
简单解释一下git commit命令，-m后面输入的是本次提交的说明，可以输入任意内容，当然最好是有意义的，这样你就能从历史记录里方便地找到改动记录
git commit命令执行成功后会告诉你，1 file changed：1个文件被改动（我们新添加的readme.txt文件）；2 insertions：插入了两行内容（readme.txt有两行内容）。
My stupid boss still prefers SVN.
git checkout -- readme.txt
hello git