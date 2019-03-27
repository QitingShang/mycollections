## ElasticSearch 搜索技术 
- 官网：https://www.elastic.co/products/elasticsearch
- 启动 elasticSearch 
	- Linux或OS X： ./elasticsearch。
	- Windows： elasticsearch.bat。
- 访问 http://127.0.0.1:9200

- ik分词器 下载地址 
 https://github.com/medcl/elasticsearch-analysis-ik/tree/2.x

- 访问分词器 分词效果
- http://localhost:9200/_analyze?analyzer=ik&pretty=true&text=%E6%88%91%E6%98%AF%E4%B8%AD%E5%9B%BD%E4%BA%BA

- 安装es head 插件 
	- %elasticsearch%/bin/plugin.bat install mobz/elasticsearch-head
	- 访问 http://localhost:9200/_plugin/head/ 

## Jackson 引入
- 1.x 
```
    <dependency>
  		<groupId>org.codehaus.jackson</groupId>
  		<artifactId>jackson-core-asl</artifactId>
  		<version>1.9.13</version>
  	</dependency>
  	<dependency>
  		<groupId>org.codehaus.jackson</groupId>
  		<artifactId>jackson-mapper-asl</artifactId>
  		<version>1.9.13</version>
  	</dependency> 
``` 

- 2.x 
```
	<dependency>
  		<groupId>com.fasterxml.jackson.core</groupId>
  		<artifactId>jackson-core</artifactId>
  		<version>2.8.1</version>
  	</dependency>
  	<dependency>
  		<groupId>com.fasterxml.jackson.core</groupId>
  		<artifactId>jackson-databind</artifactId>
  		<version>2.8.1</version>
  	</dependency>
  	<dependency>
  		<groupId>com.fasterxml.jackson.core</groupId>
  		<artifactId>jackson-annotations</artifactId>
  		<version>2.8.1</version>
  	</dependency>
```
