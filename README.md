## 1.关于 JitPack 
 JitPack实际上是一个自定义的Maven仓库，不过它的流程极度简化，只需要输入Github项目地址就可发布项目，大大方便了像我这种懒得配置环境的人。
 
## 2.使用总结
关于如何配置和使用，请参考这篇文章：
http://blog.csdn.net/user11223344abc/article/details/78403537

本文就使用之后,进行一点简单的总结：
- 一般来说，用到这个东西，一般是要写自己的库分享到github，那么就牵涉到如何用正确的姿势来编写自己的lib
- 个人觉得，正确编写一个lib工程的步骤是，先建一个正常工程 xxx-master-sample，再在正常工程内new moudle，取名为xxxLib
- 当xxxLib在sample项目内测试完毕准备发布之后，单拷该lib出来，提交到github
- 最后说一嘴，当提交的库，进行迭代时候，需要重新在jitPack网站进行get（这一点个人感觉不太智能，如果有更好的方法应对，望请告知，谢谢）
