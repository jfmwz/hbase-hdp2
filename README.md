hbase-hdp2
==========

Connect hbase with hdp2.



Basic configuration to connect to hdp2



conf.set("hbase.zookeeper.quorum", "sandbox.hortonworks.com");
conf.set("hbase.zookeeper.property.clientPort", "2181");
conf.set("zookeeper.znode.parent", "/hbase-unsecure");

change in the local machine

add this line to /etc/hosts

127.0.0.1  sandbox.hortonworks.com


