```
├── acceptance 验收测试
├── base 多个层 全局共享数据结构：配置，常量
├── bench 性能测试
├── blobs node本地二进制文件读写等接口，会在cloud包中使用，会在server_sql注册为rpc
├── build node构建信息,日志输出会用到
├── ccl  社区协议代码 通过import _使用，还可以构建没有ccl的二进制版本
├── cli  cobra命令行
├── clusterversion 查询集群功能版本是否支持
├── cmd 调用cli，打包命令行二进制
├── col 数据结构 SQL包用
├── compose docker-compose测试启动代码
├── config zone配置
├── docs 文档URL，用于打印日志
├── featureflag util函数，检查feature是否可用
├── geo 地理位置相关，为实现就近存储
├── gossip 🏁
├── internal 一些内部工具，batcher在别的包有用
├── jobs 任务相关
├── keys 聚合kvstore使用读key常量
├── kv ⚠️ kvserver核心很多
├── migration 迁移启动是 会使用
├── release release命令使用
├── roachpb protobuffer数据共享的数据结构
├── rpc grpc server创建来源
├── scheduledjobs job在用 ，job运行环境及配置对象
├── security 安全权限相关
├── server rpc服务postgres接入服务
├── settings 配置项
├── sql 🏆SQL层
├── sqlmigrations
├── storage 🏆 存储层
├── testutils 测试工具
├── ts time-series 时序数据库用于存Metres监控数据
├── ui 控制台react前端项目
├── util 挺多关键的工具
└── workload 负载情况，通过cli查询
``` 
