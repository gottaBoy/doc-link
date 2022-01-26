### AOP 最后一块拼图 | AST 抽象语法树 —— 最轻量级的AOP方法
https://juejin.cn/post/6844903764982235150

https://houbb.github.io/2020/05/29/java-ast-00-overview
https://juejin.cn/post/6844904035271573511
https://www.kancloud.cn/freya001/haoke/1664762


https://www.zhihu.com/question/268622554
https://github.com/gottaBoy/js-code-to-svg-flowchart
https://lisperator.net/pltut/

https://github.com/chai2010/go-ast-book
https://github.com/gottaBoy/ugo-compiler-book
https://github.com/gottaBoy/astexplorer
https://astexplorer.net/

https://golangrepo.com/repo/chai2010-go-ast-book
https://llvm-tutorial-cn.readthedocs.io/en/latest/chapter-2.html

https://www.jianshu.com/p/4c23298d9a34
https://blog.csdn.net/weixin_33768153/article/details/85130411
https://zhuanlan.zhihu.com/p/266697614

https://zhuanlan.zhihu.com/p/266697614
https://www.jianshu.com/p/6cccabe91228
https://blogz.gitee.io/ast/

## Git 合并多个 commit，保持历史简洁
https://cloud.tencent.com/developer/article/1690638


git rebase
合并步骤
查看 log
编辑要合并版本
查看合并后的 log
推送远程
冲突解决
```
git log
git rebase -i commitid
s
:wq
# 查看冲突
$ git status

# 解决冲突之后，本地提交
$ git add .

# rebase 继续
$ git rebase --continue
git log
git push --force origin mybranch
```
git 使用详解
https://www.cnblogs.com/kevingrace/p/5896706.html
https://www.jianshu.com/p/c92f552da60c
