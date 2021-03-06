#### 项目说明
该项目是一个典型的由springcloud管理的微服务项目，主要包括如下模块

|服务名|父级依赖|模块说明|  
|--    |-------      |--      |
|thoth|无|为微服务提供统一的pom管理，以及通用组件|
|thoth-registry-server|无|注册中心|
|thoth-config-server| 无|微服务统一配置管理|
|thoth-robot-ms|无|springcloud中的一个微服务|


#### To Do List
* 1.thoth基础组件的管理，后面会对pom中jar的版本管理做细粒度的切分和管理
* 2.网关以及熔断器等项目的更新
* 3.配置中心以及注册中心的使用
* 4.微服务之间的RPC通信，会有FeignClient和RestTemplate以及Grpc的整合。
* 5.项目部署方案，安全，授权等通用模块的更新。
* 6、项目中使用到的技术，包括es，kafaka，mongo，redis等集群模式的搭建及使用文档。
* 


### Most import
*  文档：  
这一点我想很多同学跟我一样深受其害，就像github一样，很多项目拿下来不能用，没有文档和环境的说明，然后需要花费大量的时间去看代码。  
希望看到的小伙伴多给我提issue，我会尽量回复并文档化和规范化。


#### End
相关的技术说明会写在如下三个地方：  
* [简书](http://www.jianshu.com/u/13c5fab7db82)
* [个人博客](http://sunliangliang.com/)
* [公众号：阿亮私语]  
 


![](http://ovheeg7ro.bkt.clouddn.com/aLiangcode.jpg)



    