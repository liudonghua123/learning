#一致性

若某节点故障，则其存储数据会移交给其他节点，而当它重新上线时，数据库会把变更后的数据交还此节点。这种技术叫“提示移交”，可以帮之故障节点更快恢复。