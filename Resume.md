 <center>
     <h1>陈锦涛</h1>
     <div>
         <span>
             <img src="assets/phone-solid.svg" width="18px">
             13124982536
         </span>
         ·
         <span>
             <img src="assets/envelope-solid.svg" width="18px">
             1095337270@qq.com
         </span>
     </div>
 </center>
 ## <img src="assets/info-circle-solid.svg" width="30px"> 个人信息 

 - 男   27
 - 工作经验：3年
 - 学历：本科
 - 专业：电子信息工程  (2015-2019)
 - 院校：岭南师范学院 



## <img src="assets/stack-of-papers.png" width="30px"> 求职意向

- 期望职位：Java 研发工程师
- 工作城市：广州
- 求职状态：离职，随时到岗
- 期望薪资：14~16 K

​	

## <img src="assets/tools-solid.svg" width="30px"> 技能清单

- 熟练掌握JAVA基础知识，熟悉常用集合、锁、多线程等相关技术
- 熟悉JVM，内存模型、类加载、垃圾回收等知识
- 熟练掌握Spring、Spring Boot、Spring Cloud、MyBatis、Netty等开发框架
- 熟练使用Oracle、MySQL、DB2数据库，有SQL优化经验
- 熟练使用Redis、Zookeeper、Elastic-Job、Nginx等中间件
- 熟练使用Docker、Kubernetes和Linux等运维技术
- 熟练使用Hadoop、Hive、Spark SQL、Dolphinscheduler、DataX 等大数据组件



## <img src="assets/briefcase-solid.svg" width="30px"> 工作经历

- **软通动力广州科技有限公司**  			**2019-07 ~ 2022-09**

   工作职位：Java开发工程师、数据开发工程师

   工作描述：

   ​				1、参与项目方案设计、评审，编写开发详细设计文档，实现需求功能交付

   ​				2、编写项目部署实施指导文档，支撑项目上载以及排查解决生产问题

   ​				3、负责项目组代码检视，培养新员工



## <img src="assets/project-diagram-solid.svg" width="30px"> 项目经历

- **新结算中心建设**									**2021-12 ~ 2022-07**

  项目简介：结算中心是移动BOSS针对不同业务完成相关网内结算和网间结算的子系统，新系统基于Dolphinscheduler、DataX建设数据中台服务，具备数据同步、任务调度，并按客户要求下线DB2，数据割接到Oracle数据库一体机，为系统结算对账业务提速。

  
  
  职责描述：
  
  ​				1、负责旧的数仓脚本代码改造，将DB2 SQL语法转换为Oracle SQL，以及 hive转Spark SQL
  
  ​				2、环境搭建，基于Dolphinscheduler二次开发，兼容适配华为FI Hadoop组件，新增环境配置、父子工作流参数传递等功能，参考datax-web开发数据同步管理功能，可通过界面可视化构建DataX Json
  
  ​				3、开发结算中心工作台页面接口，开发、编排DAG 工作流，配置相关工作流调度配置、依赖参数
  
  
  
  项目亮点：
  
  ​				1、自研python脚本完成95%代码（SQL语法）转换，减少重复性劳动，提高团队的工作效率
  
  ​				2、对账SQL中含有大量的case when语句，通过编写 Spark UDF精简SQL 
  
  ​				3、开发通用审计日志功能的Mybatis插件，减少重复代码，降低对业务代码侵入性
  
  ​				4、使用EasyExcel重构 Excel数据导入程序，减少内存占用提升开发效率，并使用MyBatis Batch模式优化批量插入，原本导入10w数据需要7分钟，优化后38s
  
  



-  **WEB容器化**											**2020-08 ~ 2021-06**

  项目简介：csp功能模块拆分、重构，分为订单、充值、产商品、路由、权限、BME等多个微服务。使用Spring Boot + k8s 分布式微服务架构设计，利用K8S的Service、ComfigMap实现服务发现、配置管理功能，OpenFeign实现各服务调用。

  

  项目职责：

  ​				1、作为项目的RDPM，负责整个项目的管理，参与了项目的全流程，包括项目预研、

  ​					  方案设计、开发、UAT集成测试，保证项目割接上线

  ​				2、负责portal网关服务、充值中心服务开发

  ​				3、编写Dockerfile构建镜像，编写流量网关Ingress Controller Chart，自研开发工具，

  ​					  通过配置化生成华为DF应用部署包
  
  ​				4、性能压测，制定调优方案及扩容策略
  
  
  
  项目亮点：
  
  ​				1、使用Netty重写充值服务模块解决socket端口不足和服务超时失败问题，统一开启keepalive长连接，并使用Promise包装异步接收响应。
  
  ​				2、基于AbstractRoutingDataSource开发路由组件，实现多数据源切换，并支持RSA加解密。
  
  ​				3、二次开发redis-ha Helm Chart包规避redis sentinel集群不能正常地故障转移问题。
  
  ​				4、优化docker、kubelet配置，规避DiskPressure 发生pod硬驱逐问题。



- **ESOP政企客户综合运营支撑系统**			**2020-01 ~ 2020-06**

  项目简介：ESOP是广东移动对政企、集团业务的运营需求支撑平台，专注于集团客户管理和集团业务。通过界面集成、数据集成、服务集成的方式实现BOSS系统的集成，如业务办理、产品管理、订单管理、信控管理、资源管理等；管理功能上ESOP通过自身能力建设实现，如集团客户资料管理、统一工作台、集团客户统一视图、预警管理、商机管理等。

  

  职责描述：

  ​				1、负责平台服务接口开发，与OA外围接口联调

  ​				2、线上的Bug问题定位与修改

  

  项目亮点：

  ​				1、开发信控需求，其中审批等级由多个审批因子和关联条件判定，灵活使用策略、组合设计模式解决复杂逻辑，降低代码圈复杂度，确保代码具备健壮性与扩展性
  
  ​				2、引入ElasticJob-Lite分布式调度框架，开发工单处理程序，对ID取模进行数据分片，有效提升程序并行处理能力，降低工单堆积
  
  ​				3、重构文件上传接口，使用线程池异步处理耗时的批量业务，并使用TransmitThreadLocal解决线程间上下文传递问题
  
  ​				4、线上出现exists语句导致的长事务问题，数据库连接被强制回收，后通过改写为join方式将执行时间从13s降到600ms
  
  



## <img src="assets/edit-list.png" width="30px"> 个人评价	

- 有较强的学习和解决问题能力，善于通过一些系统问题总结分析原因，对技术有追求。
- 在工作中可以独立承担相关职责，可以承受较强的工作压力并愿意不断地提升自我。
- 性格开朗、积极乐观，有良好的团队协作能力和责任心。