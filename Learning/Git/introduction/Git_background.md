###Git————Linus的第二个伟大作品
####Git出现背景
Linux之父Linus是坚定的CVS反对者，它同样地也反对SVN。这就是为什么在1991-2002这是与年之间，Linus宁可手工修补文件的方式维护代码，也迟迟不愿使用CVS的原因。

>2002年至2005年Linus顶着开源社区精英们口诛笔伐的压力，选择了一个商业版本控制系统Bikeeper作为Linux内核的代码管理工具（http://en.wikipedia.org/wiki/BitKeeper）。Bikeeper不同于CVS和SVN等集中式版本控制工具，而是一款分布式版本控制工具。

分布式版本控制系统最大的反传统之处在于，可以不需要集中式的版本库，每个人都工作在通过克隆建立的本地版本库中。也就是说每个人都拥有一个完整的版本库，查看提交日志、提交、创建里程碑和分支、合并分支、回退等所有操作都直接在本地完成而不需要网络连接。每个人都是本地版本库的主人，不再有谁能提交谁不能提交的限制，加上多样的协同工作模型（版本库间推送、拉回，以及补丁文件传送等）让开源项目的参与度有爆发式增长。