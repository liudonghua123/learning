# 简便的管理

* MongoDB尽量让服务器自治来简化数据库的管理
* 除了启动数据库服务器之外，几乎没有什么必要的管理操作
* 如果主服务器挂掉了，MongoDB会自动切换到备份服务器上，并且将备份服务器提升为活跃服务器
* 在分布式环境下，集群只需要知道有新增加的节点，就会自动集成和配置新节点