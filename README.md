# HadoopDemo
>Hadoop简单应用案例，包括MapReduce、单词统计、HDFS基本操作、web日志分析、Zookeeper基本使用等  

运行环境：  
java 1.8  
hadoop1.1.2  
zookeeper3.4.5  
采用伪分布模式下eclipse工具进行开发的java project。    

>org.conan.myhadoop.hdfs    
该包下是HDFS类的基本操作。包括文件的创建，复制，删除， 查看数据，文件重命名，从hdfs下载文件到本地系统等  

>org.conan.myhadoop.mr  
该包下是一个单词统计的MapReduce任务类。  
完成对文件中单词的统计。  

>org.conan.myhadoop.mr.kpi  
该包下是一个web日志的分析的四个MapReduce任务类。  
完成对一天中[粉丝日志](http://blog.fens.me/)网站的web日志的分析。包括独立IP统计、资源访问次数统计、每小时访问量统计、客户端类型统计。  

>org.conan.myzk  
该包下是对zookeeper工具的简单使用。  
需要安装zookeeper。代码中使用的是zookeeper3.4.5版本。  



