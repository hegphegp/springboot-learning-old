# 各种开源软件

### [xxl-conf https://gitee.com/xuxueli0323/xxl-conf](https://gitee.com/xuxueli0323/xxl-conf)
* XXL-CONF 是一个分布式配置管理平台，拥有"强一致性、毫秒级动态推送、多环境、多语言、配置监听、权限控制、版本回滚"等特性。现已开放源代码，开箱即用。
```
1、简单: 部署简单、接入灵活方便，一分钟上手；
2、在线管理: 提供配置中心, 通过Web界面在线操作配置数据，直观高效；
3、多环境支持：单个配置中心集群，支持自定义多套环境，管理多个环境的的配置数据；环境之间相互隔离；
4、多数据类型配置：支持多种数据类型配置，如：String、Boolean、Short、Integer、Long、Float、Double 等；
5、多语言支持（配置中心Agent服务）：提供配置中心Agent服务，可据此通过Http（long-polling）获取配置数据并实时感知配置变更，从而实现多语言支持。
6、配置变更监听功能：可开发Listener逻辑，监听配置变更事件，可据此动态刷新JDBC连接池等高级功能；
7、毫秒级动态推送: 配置更新后, 实时推送配置信息, 项目中配置数据会实时更新并生效, 不需要重启线上机器;
8、强一致性：保障配置数据的强一致性，提高配置时效性；
9、配置中心HA：配置中心支持集群部署，提供系统可用性；
10、推送服务HA: 配置服务基于ZK集群, 只要集群节点保证存活数量大于N/2N+1, 就可保证服务稳定, 避免单点风险;
11、配置备份: 配置数据同时在ZK与MySQL中存储和备份， 提高配置数据的安全性;
12、多种获取配置方式：支持 "API、 注解、XML占位符" 等多种方式获取配置，可灵活选择使用；
13、兼容Spring原生配置：兼容Spring原生配置方式 "@Value"、"${}" 加载本地配置功能；与分布式配置获取方式隔离，互不干扰；
14、分布式: 支持多业务线接入并统一管理配置信息，支撑分布式业务场景;
15、项目隔离: 以项目为维度管理配置, 方便隔离不同业务线配置;
16、高性能: 通过Ehcache对配置数据做Local Cache, 提高性能;
17、客户端断线重连强化：设置守护线程，周期性检测客户端连接、配置同步，提高异常情况下配置稳定性和时效性；
18、空配置处理：主动缓存null或不存在类型配置，避免配置请求穿透到远程配置Server引发雪崩问题；
19、用户管理：支持在线添加和维护用户，包括普通用户和管理员两种类型用户；
20、配置权限控制；以项目为维度进行配置权限控制，管理员拥有全部项目权限，普通用户只有分配才拥有项目下配置的查看和管理权限；
21、历史版本回滚：记录配置变更历史，方便历史配置版本回溯，默认记录10个历史版本；
22、配置同步：全量检测未同步配置项，使用DB中配置备份数据覆盖ZK中配置数据并推送更新；在配置中心异常恢复、新配置中心集群初始化等场景中十分有效。
23、配置快照：客户端从配置中心获取到的配置数据后，会周期性缓存到本地快照文件中，当从配置中心获取配置失败时，将会使用使用本地快照文件中的配置数据；提高系统可用性；
```

### [BootDo https://gitee.com/lcg0124/bootdo](https://gitee.com/lcg0124/bootdo)
* BootDo是在SpringBoot基础上搭建的一个Java基础开发平台，ApacheShiro为权限授权层，Ehcahe对常用数据进行缓存。BootDo包括系统权限组件、数据权限组件、数据字典组件、核心工具组件、视图操作组件、工作流组件、代码生成等。采用分层设计、双重验证、提交数据安全编码、密码加密、访问验证、数据权限验证。包括以下四大模块，系统管理模块、 内容管理模块、在线办公模块、代码生成模块。 系统管理模块 ，包括企业组织架构（用户管理、机构管理、区域管理）、 菜单管理、角色权限管理、字典管理等功能。
```
用户管理：用户是系统操作者，该功能主要完成系统用户配置。
机构管理：配置系统组织机构（公司、部门、小组），树结构展现，可随意调整上下级。
区域管理：系统城市区域模型，如：国家、省市、地市、区县的维护。
菜单管理：配置系统菜单，操作权限，按钮权限标识等。
角色管理：角色菜单权限分配、设置角色按机构进行数据范围权限划分。
字典管理：对系统中经常使用的一些较为固定的数据进行维护，如：是否、男女、类别、级别等。
操作日志：系统正常操作日志记录和查询；系统异常信息日志记录和查询。
连接池监视：监视当期系统数据库连接池状态，可进行分析SQL找出系统性能瓶颈。
工作流引擎：实现业务工单流转、在线流程设计器。
```

### [bootshiro https://gitee.com/tomsun28/bootshiro](https://gitee.com/tomsun28/bootshiro)
* 基于springboot+ shiro+jwt的真正rest api资源无状态认证权限管理框架,开发人员无需关注权限问题
```
```

### []()
```
```

### []()
```
```

### []()
```
```

### []()
```
```

### []()
```
```

### []()
```
```

### []()
```
```

### []()
```
```

### []()
```
```

### []()
```
```

### []()
```
```

### []()
```
```

### []()
```
```

### []()
```
```

### []()
```
```

### []()
```
```

### []()
```
```

### []()
```
```

### []()
```
```

### []()
```
```

### []()
```
```

### []()
```
```

### []()
```
```

### []()
```
```

### []()
```
```

### []()
```
```

### []()
```
```

### []()
```
```

### []()
```
```

### []()
```
```

### []()
```
```

### []()
```
```

### []()
```
```

### []()
```
```

### []()
```
```

### []()
```
```

### []()
```
```

### []()
```
```

### []()
```
```

### []()
```
```

### []()
```
```

### []()
```
```

### []()
```
```

### []()
```
```

### []()
```
```

### []()
```
```

### []()
```
```

### []()
```
```

### []()
```
```

### []()
```
```

### []()
```
```

### []()
```
```

### []()
```
```

### []()
```
```

### []()
```
```

### []()
```
```

### []()
```
```

### []()
```
```

### []()
```
```

### []()
```
```

### []()
```
```

### []()
```
```

### []()
```
```

### []()
```
```

### []()
```
```

### []()
```
```

### []()
```
```

### []()
```
```

### []()
```
```

### []()
```
```

### []()
```
```

### []()
```
```

### []()
```
```

### []()
```
```

### []()
```
```

### []()
```
```

