三、git基本操作

　　1. $ git add "文件名" ----添加文件至缓存区

　　2. $ git commit -m "注释"----提交之前add的文件至版本库

　　3. $ git status----显示当前的版本库状态

　　4. $ git diff “文件名”----显示更改的细节

　　4. $ git log-----查看更改的历史记录（是文件更改的记录，与下面的reflog不同）

　　5. $ git reset --hard HEAD~x -----回退到之前的x个版本

　　6. $ git reflog----输入命令的历史记录