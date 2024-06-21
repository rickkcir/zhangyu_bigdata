# zhangyu_bigdata
#!/bin/bash
mkdir -p '集群搭建之主节点'
cd '集群搭建之主节点' && wget http://192.168.1.150:60000/hadoop-2.6.0-cdh5.4.5.tar.gz
cd -
cd '集群搭建之主节点' && wget http://192.168.1.150:60000/jdk-7u75-linux-x64.tar.gz
cd -
cd '集群搭建之主节点' && wget http://192.168.1.150:60000/word.txt
cd -
mkdir -p 'Spark local模式安装'
cd 'Spark local模式安装' && wget http://192.168.1.150:60000/allfiles/spark1/scala-2.12.8.tgz
cd -
cd 'Spark local模式安装' && wget http://192.168.1.150:60000/allfiles/spark1/spark-2.4.3-bin-hadoop2.7.tgz
cd -
mkdir -p 'stand alone伪分布式安装'
cd 'stand alone伪分布式安装' && wget http://192.168.1.150:60000/allfiles/hadoop3/scala-2.12.8.tgz
cd -
cd 'stand alone伪分布式安装' && wget http://192.168.1.150:60000/allfiles/hadoop3/spark-2.4.3-bin-hadoop2.7.tgz
cd -
mkdir -p 'Spark shell操作'
cd 'Spark shell操作' && wget http://192.168.1.150:60000/allfiles/spark3/wordcount/buyer_favorite
cd -
cd 'Spark shell操作' && wget http://192.168.1.150:60000/allfiles/spark3/distinct/buyer_favorite
cd -
cd 'Spark shell操作' && wget http://192.168.1.150:60000/allfiles/spark3/sort/goods_visit
cd -
cd 'Spark shell操作' && wget http://192.168.1.150:60000/allfiles/spark3/join/order_items
cd -
cd 'Spark shell操作' && wget http://192.168.1.150:60000/allfiles/spark3/join/orders
cd -
cd 'Spark shell操作' && wget http://192.168.1.150:60000/allfiles/spark3/avg/goods
cd -
cd 'Spark shell操作' && wget http://192.168.1.150:60000/allfiles/spark3/avg/goods_visit
cd -
mkdir -p 'Spark Java API & Spark Scala API 操作'
cd 'Spark Java API & Spark Scala API 操作' && wget http://192.168.1.150:60000/allfiles/spark4/buyer_favorite1
cd -
cd 'Spark Java API & Spark Scala API 操作' && wget http://192.168.1.150:60000/allfiles/spark4/spark-assembly-1.6.0-hadoop2.6.0.jar
cd -
mkdir -p 'Spark SQL 创建表 查询数据'
cd 'Spark SQL 创建表 查询数据' && wget http://192.168.1.150:60000/allfiles/spark5/orders
cd -
cd 'Spark SQL 创建表 查询数据' && wget http://192.168.1.150:60000/allfiles/spark5/order_items
cd -
mkdir -p 'Spark SQL 加载文件，处理文件，存储文件'
cd 'Spark SQL 加载文件，处理文件，存储文件' && wget http://192.168.1.150:60000/allfiles/spark6/goods_visit.json
cd -
mkdir -p 'Spark Streaming WordCount'
cd 'Spark Streaming WordCount' && wget http://192.168.1.150:60000/allfiles/spark7/spark-assembly-1.6.0-hadoop2.6.0.jar
cd -
mkdir -p 'Kafka 传输数据到 Spark Streaming 进行数据处理'
cd 'Kafka 传输数据到 Spark Streaming 进行数据处理' && wget http://192.168.1.150:60000/allfiles/case6/buyer_favorite1
cd -
cd 'Kafka 传输数据到 Spark Streaming 进行数据处理' && wget http://192.168.1.150:60000/allfiles/case6/jar.tar.gz
cd -
mkdir -p 'Spark ML Pipeline 机器学习流程处理二元分类问题'
cd 'Spark ML Pipeline 机器学习流程处理二元分类问题' && wget http://192.168.1.150:60000/allfiles/pyspark9/train.tsv
cd -
cd 'Spark ML Pipeline 机器学习流程处理二元分类问题' && wget http://192.168.1.150:60000/allfiles/pyspark9/test.tsv
cd -
mkdir -p 'PySpark SQL 文件处理 （Hadoop3.0）'
cd 'PySpark SQL 文件处理 （Hadoop3.0）' && wget http://192.168.1.150:60000/allfiles/pyspark2/goods_visit.json
cd -
mkdir -p 'PySpark WordCount（Hadoop3.0）'
cd 'PySpark WordCount（Hadoop3.0）' && wget http://192.168.1.150:60000/allfiles/mapreduce1/buyer_favorite1
cd -
mkdir -p 'PySpark 处理数据并进行图表分析（Hadoop3.0）'
cd 'PySpark 处理数据并进行图表分析（Hadoop3.0）' && wget http://192.168.1.150:60000/allfiles/pyspark1/ml-100k.zip
cd -
mkdir -p 'PySpark 安装（Hadoop3.0）'
cd 'PySpark 安装（Hadoop3.0）' && wget http://192.168.1.150:60000/allfiles/spark1/spark-2.4.3-bin-hadoop2.7.tgz
cd -
cd 'PySpark 安装（Hadoop3.0）' && wget http://192.168.1.150:60000/allfiles/hadoop3/jdk-8u191-linux-x64.tar.gz
cd -
mkdir -p 'PySpark 推荐引擎（Hadoop3.0）'
cd 'PySpark 推荐引擎（Hadoop3.0）' && wget http://192.168.1.150:60000/allfiles/pyspark8/ml-100k.zip
cd -
cd 'PySpark 推荐引擎（Hadoop3.0）' && wget http://192.168.1.150:60000/allfiles/pyspark8/ml-latest.zip
cd -
mkdir -p 'PySpark SQL、DataFrame、RDD（Hadoop3.0）'
cd 'PySpark SQL、DataFrame、RDD（Hadoop3.0）' && wget http://192.168.1.150:60000/allfiles/mapreduce1/buyer_favorite1
cd -
cd 'PySpark SQL、DataFrame、RDD（Hadoop3.0）' && wget http://192.168.1.150:60000/allfiles/pyspark7/buyer_log
cd -
mkdir -p 'PySpark MLlib 逻辑回归（Hadoop3.0）'
cd 'PySpark MLlib 逻辑回归（Hadoop3.0）' && wget http://192.168.1.150:60000/allfiles/pyspark6/a1a.txt
cd -
mkdir -p 'PySpark MLlib 随机森林（Hadoop3.0）'
cd 'PySpark MLlib 随机森林（Hadoop3.0）' && wget http://192.168.1.150:60000/allfiles/pyspark5/colon-cancer
cd -
mkdir -p 'PySpark MLlib 决策树二元分类（Hadoop3.0）'
cd 'PySpark MLlib 决策树二元分类（Hadoop3.0）' && wget http://192.168.1.150:60000/allfiles/pyspark9/train.tsv
cd -
cd 'PySpark MLlib 决策树二元分类（Hadoop3.0）' && wget http://192.168.1.150:60000/allfiles/pyspark9/test.tsv
cd -
mkdir -p 'PySpark MLlib 决策树回归分析：Bike Sharing（Hadoop3.0）'
cd 'PySpark MLlib 决策树回归分析：Bike Sharing（Hadoop3.0）' && wget http://192.168.1.150:60000/allfiles/pyspark10/Bike-Sharing-Dataset.zip
cd -
mkdir -p 'Sparklyr - dplyr 包基本操作（Hadoop3.0）'
cd 'Sparklyr - dplyr 包基本操作（Hadoop3.0）' && wget http://192.168.1.150:60000/allfiles/sparkr3/flights.csv
cd -
cd 'Sparklyr - dplyr 包基本操作（Hadoop3.0）' && wget http://192.168.1.150:60000/allfiles/sparkr3/airlines.csv
cd -
mkdir -p 'Sparklyr 安装（Hadoop3.0）'
cd 'Sparklyr 安装（Hadoop3.0）' && wget http://192.168.1.150:60000/allfiles/sparkr1/rstudio-server
cd -
cd 'Sparklyr 安装（Hadoop3.0）' && wget http://192.168.1.150:60000/allfiles/sparkr1/rstudio-1.2.1335-amd64.deb
cd -
cd 'Sparklyr 安装（Hadoop3.0）' && wget http://192.168.1.150:60000/allfiles/sparkr1/rstudio-server-1.2.1335-amd64.deb
cd -
cd 'Sparklyr 安装（Hadoop3.0）' && wget http://192.168.1.150:60000/allfiles/openssl1.0/libssl1.0.0_1.0.2n-1ubuntu5.10_amd64.deb
cd -
mkdir -p 'Sparklyr - K-means 聚类（Hadoop3.0）'
cd 'Sparklyr - K-means 聚类（Hadoop3.0）' && wget http://192.168.1.150:60000/allfiles/sparkr5/iris.csv
cd -
mkdir -p 'Sparklyr - 主成分分析（Hadoop3.0）'
cd 'Sparklyr - 主成分分析（Hadoop3.0）' && wget http://192.168.1.150:60000/allfiles/sparkr7/physique.csv
cd -
mkdir -p 'Sparklyr - 分类算法（Hadoop3.0）'
cd 'Sparklyr - 分类算法（Hadoop3.0）' && wget http://192.168.1.150:60000/allfiles/sparkr9/titanic.csv
cd -
mkdir -p 'Sparklyr - 方差分析（Hadoop3.0）'
cd 'Sparklyr - 方差分析（Hadoop3.0）' && wget http://192.168.1.150:60000/allfiles/sparkr10/account.csv
cd -
mkdir -p 'Sparklyr - 因子分析（Hadoop3.0）'
cd 'Sparklyr - 因子分析（Hadoop3.0）' && wget http://192.168.1.150:60000/allfiles/sparkr8/General_ability.csv
cd -
mkdir -p 'Sparklyr - 逻辑回归（Hadoop3.0）'
cd 'Sparklyr - 逻辑回归（Hadoop3.0）' && wget http://192.168.1.150:60000/allfiles/sparkr6/accident.csv
cd -
mkdir -p 'Sparklyr - 线性回归分析（Hadoop3.0）'
cd 'Sparklyr - 线性回归分析（Hadoop3.0）' && wget http://192.168.1.150:60000/allfiles/sparkr4/metal.csv
cd -
cd 'Sparklyr - 线性回归分析（Hadoop3.0）' && wget http://192.168.1.150:60000/allfiles/sparkr4/health_index.csv
cd -
mkdir -p 'Sparklyr - Spark DataFrame 读写操作（Hadoop3.0）'
cd 'Sparklyr - Spark DataFrame 读写操作（Hadoop3.0）' && wget http://192.168.1.150:60000/allfiles/sparkr2/buyer_favorite.csv
cd -
cd 'Sparklyr - Spark DataFrame 读写操作（Hadoop3.0）' && wget http://192.168.1.150:60000/allfiles/sparkr2/people.json
cd -
cd 'Sparklyr - Spark DataFrame 读写操作（Hadoop3.0）' && wget http://192.168.1.150:60000/allfiles/sparkr2/users.parquet
cd -
cd 'Sparklyr - Spark DataFrame 读写操作（Hadoop3.0）' && wget http://192.168.1.150:60000/allfiles/sparkr2/iris.csv
cd -
mkdir -p '一、采集新闻网页分类并进行数据训练（局域网）'
cd '一、采集新闻网页分类并进行数据训练（局域网）' && wget http://192.168.1.150:60000/allfiles/second/edu1/webmagic-0.7-libs.tar.gz
cd -
mkdir -p '三、将新闻分类进行测试应用及展示'
cd '三、将新闻分类进行测试应用及展示' && wget http://192.168.1.150:60000/allfiles/classify/PageClassify.tar.gz
cd -
cd '三、将新闻分类进行测试应用及展示' && wget http://192.168.1.150:60000/allfiles/classify/trainSpecial.tar.gz
cd -
mkdir -p '二、对新闻网页进行模型训练生成训练集'
cd '二、对新闻网页进行模型训练生成训练集' && wget http://192.168.1.150:60000/allfiles/classify/classifydata.tar.gz
cd -
cd '二、对新闻网页进行模型训练生成训练集' && wget http://192.168.1.150:60000/allfiles/classify/pzwj.tar.gz
cd -
mkdir -p 'MapReduce 实例：ChainMapReduce（Hadoop3.0）'
cd 'MapReduce 实例：ChainMapReduce（Hadoop3.0）' && wget http://192.168.1.150:60000/allfiles/mapreduce10/goods_0
cd -
cd 'MapReduce 实例：ChainMapReduce（Hadoop3.0）' && wget http://192.168.1.150:60000/allfiles/mapreduce10/hadoop2lib.tar.gz
cd -
mkdir -p 'MapReduce 实例：MapReduce 自定义输入格式（Hadoop3.0）'
cd 'MapReduce 实例：MapReduce 自定义输入格式（Hadoop3.0）' && wget http://192.168.1.150:60000/allfiles/mapreduce11/cat1
cd -
cd 'MapReduce 实例：MapReduce 自定义输入格式（Hadoop3.0）' && wget http://192.168.1.150:60000/allfiles/mapreduce11/hadoop2lib.tar.gz
cd -
mkdir -p 'MapReduce 实例：MapReduce 自定义输出格式（Hadoop3.0）'
cd 'MapReduce 实例：MapReduce 自定义输出格式（Hadoop3.0）' && wget http://192.168.1.150:60000/allfiles/mapreduce12/cat_group1
cd -
cd 'MapReduce 实例：MapReduce 自定义输出格式（Hadoop3.0）' && wget http://192.168.1.150:60000/allfiles/mapreduce12/hadoop2lib.tar.gz
cd -
mkdir -p 'MapReduce 实例：Map端join（Hadoop3.0）'
cd 'MapReduce 实例：Map端join（Hadoop3.0）' && wget http://192.168.1.150:60000/allfiles/mapreduce5/orders1
cd -
cd 'MapReduce 实例：Map端join（Hadoop3.0）' && wget http://192.168.1.150:60000/allfiles/mapreduce5/order_items1
cd -
cd 'MapReduce 实例：Map端join（Hadoop3.0）' && wget http://192.168.1.150:60000/allfiles/mapreduce5/hadoop2lib.tar.gz
cd -
mkdir -p 'MapReduce 实例：Reduce端join（Hadoop3.0）'
cd 'MapReduce 实例：Reduce端join（Hadoop3.0）' && wget http://192.168.1.150:60000/allfiles/mapreduce6/orders1
cd -
cd 'MapReduce 实例：Reduce端join（Hadoop3.0）' && wget http://192.168.1.150:60000/allfiles/mapreduce6/order_items1
cd -
cd 'MapReduce 实例：Reduce端join（Hadoop3.0）' && wget http://192.168.1.150:60000/allfiles/mapreduce6/hadoop2lib.tar.gz
cd -
mkdir -p 'MapReduce 实例：WordCount（Hadoop3.0）'
cd 'MapReduce 实例：WordCount（Hadoop3.0）' && wget http://192.168.1.150:60000/allfiles/mapreduce1/buyer_favorite1
cd -
cd 'MapReduce 实例：WordCount（Hadoop3.0）' && wget http://192.168.1.150:60000/allfiles/mapreduce1/hadoop2lib.tar.gz
cd -
mkdir -p 'MapReduce 实例：二次排序（Hadoop3.0）'
cd 'MapReduce 实例：二次排序（Hadoop3.0）' && wget http://192.168.1.150:60000/allfiles/mapreduce8/goods_visit2
cd -
cd 'MapReduce 实例：二次排序（Hadoop3.0）' && wget http://192.168.1.150:60000/allfiles/mapreduce8/hadoop2lib.tar.gz
cd -
mkdir -p 'MapReduce 实例：倒排索引（Hadoop3.0）'
cd 'MapReduce 实例：倒排索引（Hadoop3.0）' && wget http://192.168.1.150:60000/allfiles/mapreduce9/goods3
cd -
cd 'MapReduce 实例：倒排索引（Hadoop3.0）' && wget http://192.168.1.150:60000/allfiles/mapreduce9/goods_visit3
cd -
cd 'MapReduce 实例：倒排索引（Hadoop3.0）' && wget http://192.168.1.150:60000/allfiles/mapreduce9/order_items3
cd -
cd 'MapReduce 实例：倒排索引（Hadoop3.0）' && wget http://192.168.1.150:60000/allfiles/mapreduce9/hadoop2lib.tar.gz
cd -
mkdir -p 'MapReduce 实例：单表join（Hadoop3.0）'
cd 'MapReduce 实例：单表join（Hadoop3.0）' && wget http://192.168.1.150:60000/allfiles/mapreduce7/buyer1
cd -
cd 'MapReduce 实例：单表join（Hadoop3.0）' && wget http://192.168.1.150:60000/allfiles/mapreduce7/hadoop2lib.tar.gz
cd -
mkdir -p 'MapReduce 实例：去重（Hadoop3.0）'
cd 'MapReduce 实例：去重（Hadoop3.0）' && wget http://192.168.1.150:60000/allfiles/mapreduce2/buyer_favorite1
cd -
cd 'MapReduce 实例：去重（Hadoop3.0）' && wget http://192.168.1.150:60000/allfiles/mapreduce2/hadoop2lib.tar.gz
cd -
mkdir -p 'MapReduce 实例：排序（Hadoop3.0）'
cd 'MapReduce 实例：排序（Hadoop3.0）' && wget http://192.168.1.150:60000/allfiles/mapreduce3/goods_visit1
cd -
cd 'MapReduce 实例：排序（Hadoop3.0）' && wget http://192.168.1.150:60000/allfiles/mapreduce3/hadoop2lib.tar.gz
cd -
mkdir -p 'MapReduce 实例：最高温度排序（Hadoop3.0）'
cd 'MapReduce 实例：最高温度排序（Hadoop3.0）' && wget http://192.168.1.150:60000/allfiles/mapreduce13/data.txt
cd -
cd 'MapReduce 实例：最高温度排序（Hadoop3.0）' && wget http://192.168.1.150:60000/allfiles/mapreduce13/hadoop2lib.tar.gz
cd -
mkdir -p 'MapReduce 实例：求平均值（Hadoop3.0）'
cd 'MapReduce 实例：求平均值（Hadoop3.0）' && wget http://192.168.1.150:60000/allfiles/mapreduce4/goods_click
cd -
cd 'MapReduce 实例：求平均值（Hadoop3.0）' && wget http://192.168.1.150:60000/allfiles/mapreduce4/hadoop2lib.tar.gz
cd -
mkdir -p 'MapReduce 实例：行统计（Hadoop3.0）'
cd 'MapReduce 实例：行统计（Hadoop3.0）' && wget http://192.168.1.150:60000/allfiles/mapreduce14/buyer_favorite1
cd -
cd 'MapReduce 实例：行统计（Hadoop3.0）' && wget http://192.168.1.150:60000/allfiles/mapreduce14/hadoop2lib.tar.gz
cd -
mkdir -p 'MapReduce 实战：PageRank算法（Hadoop3.0）'
cd 'MapReduce 实战：PageRank算法（Hadoop3.0）' && wget http://192.168.1.150:60000/allfiles/mr_sf/hadoop2lib.tar.gz
cd -
mkdir -p 'MapReduce 实战：互联网精准广告推送算法（Hadoop3.0）'
cd 'MapReduce 实战：互联网精准广告推送算法（Hadoop3.0）' && wget http://192.168.1.150:60000/allfiles/mr_sf/tj_data.txt
cd -
cd 'MapReduce 实战：互联网精准广告推送算法（Hadoop3.0）' && wget http://192.168.1.150:60000/allfiles/mr_sf/IKAnalyzer2012_u6.jar
cd -
cd 'MapReduce 实战：互联网精准广告推送算法（Hadoop3.0）' && wget http://192.168.1.150:60000/allfiles/mapreduce1/hadoop2lib.tar.gz
cd -
mkdir -p 'MapReduce 实战：最优路径算法（Hadoop3.0）'
cd 'MapReduce 实战：最优路径算法（Hadoop3.0）' && wget http://192.168.1.150:60000/allfiles/mapreduce1/hadoop2lib.tar.gz
cd -
mkdir -p 'MapReduce 实战：社交好友推荐算法（Hadoop3.0）'
cd 'MapReduce 实战：社交好友推荐算法（Hadoop3.0）' && wget http://192.168.1.150:60000/allfiles/mr_sf/hadoop2lib.tar.gz
cd -
mkdir -p 'Hadoop 伪分布模式安装（Hadoop3.0）'
cd 'Hadoop 伪分布模式安装（Hadoop3.0）' && wget http://192.168.1.150:60000/allfiles/hadoop3/jdk-8u191-linux-x64.tar.gz
cd -
cd 'Hadoop 伪分布模式安装（Hadoop3.0）' && wget http://192.168.1.150:60000/allfiles/hadoop3/hadoop-3.0.0.tar.gz
cd -
mkdir -p 'Hadoop 开发插件安装（Hadoop3.0）'
cd 'Hadoop 开发插件安装（Hadoop3.0）' && wget http://192.168.1.150:60000/allfiles/hadoop3/hadoop-eclipse-plugin-2.6.0.jar
cd -
mkdir -p 'HDFS JAVA API（Hadoop3.0）'
cd 'HDFS JAVA API（Hadoop3.0）' && wget http://192.168.1.150:60000/allfiles/hadoop4/hadoop2lib.tar.gz
cd -
mkdir -p '开发 YARN 客户端应用（Hadoop3.0）'
cd '开发 YARN 客户端应用（Hadoop3.0）' && wget http://192.168.1.150:60000/allfiles/yarn/hadoop2lib.tar.gz
cd -
mkdir -p '综合案例：MapReduce 写入 HBase（Hadoop3.0）'
cd '综合案例：MapReduce 写入 HBase（Hadoop3.0）' && wget http://192.168.1.150:60000/allfiles/case2/hbaselib.tar.gz
cd -
cd '综合案例：MapReduce 写入 HBase（Hadoop3.0）' && wget http://192.168.1.150:60000/allfiles/case2/mywritehbase
cd -
mkdir -p '综合案例：MapReduce 读取 HBase 并写入 HBase（Hadoop3.0）'
cd '综合案例：MapReduce 读取 HBase 并写入 HBase（Hadoop3.0）' && wget http://192.168.1.150:60000/allfiles/case3/hbaselib.tar.gz
cd -
mkdir -p '综合案例：MapReduce 读取 HBase（Hadoop3.0）'
cd '综合案例：MapReduce 读取 HBase（Hadoop3.0）' && wget http://192.168.1.150:60000/allfiles/case1/hbasereadlib.tar.gz
cd -
mkdir -p '综合案例：大数据平台（Hadoop3.0）'
cd '综合案例：大数据平台（Hadoop3.0）' && wget http://192.168.1.150:60000/allfiles/case7/buyer_favorite
cd -
cd '综合案例：大数据平台（Hadoop3.0）' && wget http://192.168.1.150:60000/allfiles/case7/mymrlib.tar.gz
cd -
cd '综合案例：大数据平台（Hadoop3.0）' && wget http://192.168.1.150:60000/allfiles/case7/sparklib.tar.gz
cd -
mkdir -p '基于大数据的网站用户购物行为分析'
cd '基于大数据的网站用户购物行为分析' && wget http://192.168.1.150:60000/allfiles/hadoop3.0_examples/user.zip
cd -
mkdir -p 'Hadoop伪分布模式安装'
cd 'Hadoop伪分布模式安装' && wget http://192.168.1.150:60000/allfiles/hadoop3.0_examples/jdk-8u162-linux-x64.tar.gz
cd -
cd 'Hadoop伪分布模式安装' && wget http://192.168.1.150:60000/allfiles/hadoop3.0_examples/hadoop-3.1.3.tar.gz
cd -
mkdir -p 'Hadoop单机模式安装'
cd 'Hadoop单机模式安装' && wget http://192.168.1.150:60000/allfiles/hadoop3.0_examples/jdk-8u162-linux-x64.tar.gz
cd -
cd 'Hadoop单机模式安装' && wget http://192.168.1.150:60000/allfiles/hadoop3.0_examples/hadoop-3.1.3.tar.gz
cd -
mkdir -p 'HBase伪分布模式安装'
cd 'HBase伪分布模式安装' && wget http://192.168.1.150:60000/allfiles/hadoop3.0_examples/hbase-2.2.2-bin.tar.gz
cd -
mkdir -p 'HBase单机模式安装'
cd 'HBase单机模式安装' && wget http://192.168.1.150:60000/allfiles/hadoop3.0_examples/hbase-2.2.2-bin.tar.gz
cd -
mkdir -p 'MongoDB Java API编程实践'
cd 'MongoDB Java API编程实践' && wget http://192.168.1.150:60000/allfiles/hadoop3.0_examples/mongo-java-driver-3.12.1.jar
cd -
mkdir -p 'Redis安装和使用'
cd 'Redis安装和使用' && wget http://192.168.1.150:60000/allfiles/hadoop3.0_examples/redis-5.0.5.tar.gz
cd -
mkdir -p 'Hive的安装'
cd 'Hive的安装' && wget http://192.168.1.150:60000/allfiles/hadoop3.0_examples/apache-hive-3.1.2-bin.tar.gz
cd -
cd 'Hive的安装' && wget http://192.168.1.150:60000/allfiles/hadoop3.0_examples/mysql-connector-java-5.1.40.tar.gz
cd -
mkdir -p 'Kafka的安装及使用'
cd 'Kafka的安装及使用' && wget http://192.168.1.150:60000/allfiles/hadoop3.0_examples/kafka_2.11-0.10.2.0.tgz
cd -
mkdir -p 'Spark安装'
cd 'Spark安装' && wget http://192.168.1.150:60000/allfiles/hadoop3.0_examples/spark-2.4.0-bin-without-hadoop.tgz
cd -
mkdir -p '编写Spark独立应用程序（Java）'
cd '编写Spark独立应用程序（Java）' && wget http://192.168.1.150:60000/allfiles/hadoop3.0_examples/apache-maven-3.6.3-bin.zip
cd -
mkdir -p '编写Spark独立应用程序（Scala）'
cd '编写Spark独立应用程序（Scala）' && wget http://192.168.1.150:60000/allfiles/hadoop3.0_examples/sbt-1.3.8.tgz
cd -
mkdir -p '编写Spark程序使用Kafka数据源'
cd '编写Spark程序使用Kafka数据源' && wget http://192.168.1.150:60000/allfiles/hadoop3.0_examples/spark-streaming-kafka-0-8_2.11-2.4.0.jar
cd -
mkdir -p 'Flink安装'
cd 'Flink安装' && wget http://192.168.1.150:60000/allfiles/hadoop3.0_examples/flink-1.9.1-bin-scala_2.11.tgz
cd -
mkdir -p '使用Flink编程实现WordCount程序'
cd '使用Flink编程实现WordCount程序' && wget http://192.168.1.150:60000/allfiles/hadoop3.0_examples/apache-maven-3.6.3-bin.zip
cd -
mkdir -p '使用ECharts图表制作'
cd '使用ECharts图表制作' && wget http://192.168.1.150:60000/allfiles/hadoop3.0_examples/echarts.js
cd -
mkdir -p '三、使用PySpark对智联数据进行分析'
cd '三、使用PySpark对智联数据进行分析' && wget http://192.168.1.150:60000/allfiles/python_pj/bigdata
cd -
mkdir -p '二、使用BeautifulSoup清洗职位信息网页'
cd '二、使用BeautifulSoup清洗职位信息网页' && wget http://192.168.1.150:60000/allfiles/python_pj2/jobs.zhaopin.com.tgz
cd -
mkdir -p '五、使用结巴分词对岗位描述进行分词并将关键词统计-DESKTOP-FT6A1MG'
cd '五、使用结巴分词对岗位描述进行分词并将关键词统计-DESKTOP-FT6A1MG' && wget http://192.168.1.150:60000/allfiles/python_pj4/stopword
cd -
cd '五、使用结巴分词对岗位描述进行分词并将关键词统计-DESKTOP-FT6A1MG' && wget http://192.168.1.150:60000/allfiles/python_pj4/bigdata
cd -
mkdir -p '五、使用结巴分词对岗位描述进行分词并将关键词统计'
cd '五、使用结巴分词对岗位描述进行分词并将关键词统计' && wget http://192.168.1.150:60000/allfiles/python_pj4/stopword
cd -
cd '五、使用结巴分词对岗位描述进行分词并将关键词统计' && wget http://192.168.1.150:60000/allfiles/python_pj4/bigdata
cd -
mkdir -p '六、利用Django Echarts将职位分析结果进行可视化'
cd '六、利用Django Echarts将职位分析结果进行可视化' && wget http://192.168.1.150:60000/allfiles/python_pj5/word.tar.gz
cd -
mkdir -p '四、对招聘职位信息进行探索分析'
cd '四、对招聘职位信息进行探索分析' && wget http://192.168.1.150:60000/allfiles/python_pj3/bigdata
cd -
cd '四、对招聘职位信息进行探索分析' && wget http://192.168.1.150:60000/allfiles/python_pj3/explore_analysis.py
cd -
cd '四、对招聘职位信息进行探索分析' && wget http://192.168.1.150:60000/allfiles/python_pj3/explore_analysis1.py
cd -
mkdir -p '三、使用PyHive对股票数据进行分析'
cd '三、使用PyHive对股票数据进行分析' && wget http://192.168.1.150:60000/allfiles/stock3/data.tar.gz
cd -
mkdir -p '二、数据清洗并上传至HDFS'
cd '二、数据清洗并上传至HDFS' && wget http://192.168.1.150:60000/allfiles/stock2/stock.tar.gz
cd -
mkdir -p '五、Python数据分析--量化交易'
cd '五、Python数据分析--量化交易' && wget http://192.168.1.150:60000/allfiles/python_stock/data.csv
cd -
mkdir -p '四、使用Django Echarts对分析数据进行可视化'
cd '四、使用Django Echarts对分析数据进行可视化' && wget http://192.168.1.150:60000/allfiles/python_echarts/stock_lib.tar.gz
cd -
cd '四、使用Django Echarts对分析数据进行可视化' && wget http://192.168.1.150:60000/allfiles/python_echarts/stockdb.sql
cd -
cd '四、使用Django Echarts对分析数据进行可视化' && wget http://192.168.1.150:60000/allfiles/python_echarts/stock_web.tar.gz
cd -
