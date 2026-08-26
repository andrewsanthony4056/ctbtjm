最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang 系统设计短链接服务实现思路
简介：程序日志分级输出规范实践，区分日志等级，规范日志打印内容，合理输出日志，方便线上问题排查定位。
 | 原文链接：http://book.wgbnko.asia/blog/586418.Doc

原标题：部署复盘：GitHubActions完整自动化配置
简介：golang 容器时区设置镜像构建处理，镜像内部设置正确时区，解决容器时间与宿主机不一致。
 | 原文链接：http://book.wgbnko.asia/blog/799735.Doc

原标题：golang 系统设计开源项目安全漏洞处理流程
简介：golang redis scan 遍历 key 避免阻塞，使用 scan 迭代遍历 redis 键，不用 keys 命令，防止阻塞 redis 服务。
 | 原文链接：http://book.wgbnko.asia/blog/260429.Doc

原标题：golang 系统设计线上日志快速检索技巧
简介：序列化版本不一致解析失败，保证序列化对象版本对齐，修复版本不匹配导致对象反序列化失败。
 | 原文链接：http://book.wgbnko.asia/blog/234498.Doc

原标题：Hands‑on：简易连接池原型实现理解原理
简介：golang nats jetstream 持久消息队列，nats jetstream 持久化消息，保证消息不丢失，实现可靠消费。
 | 原文链接：http://book.wgbnko.asia/blog/948441.Doc

原标题：golang 系统设计开源项目依赖版本升级维护
简介：golang http 服务并发连接数限制，自定义 listener 统计连接数量，限制最大并发连接数保护服务。
 | 原文链接：http://book.wgbnko.asia/blog/779377.Doc

原标题：Architecture：CI/CD流水线架构完整设计思考
简介：golang go 服务蓝绿发布实践思路，蓝绿两套实例，流量一键切换，回滚快速降低发布风险。
 | 原文链接：http://book.wgbnko.asia/blog/765930.Doc

原标题：安全复盘：Redis未授权访问漏洞防护
简介：golang bufio.Scanner 缓冲区调大，Scanner 默认缓冲区大小不够，读取超长行需要扩大缓冲区。
 | 原文链接：http://book.wgbnko.asia/blog/628930.Doc

原标题：Debug：并发场景下数据覆盖丢失问题定位
简介：HTTP 状态码请求头完整梳理，汇总常用 HTTP 状态码与请求头含义，帮助快速看懂网络请求，排查接口通信问题。
 | 原文链接：http://book.wgbnko.asia/blog/101614.Doc

原标题：golang consul 服务发现简单示例
简介：时间精度统一业务判断修复，统一业务使用时间戳精度，毫秒秒区分清楚，修复时间判断逻辑错误。
 | 原文链接：http://book.wgbnko.asia/blog/756915.Doc

原标题：Practice：实现文件监控自动重启开发服务工具
简介：新手参与开源社区贡献指南，介绍开源社区基础规则，讲解阅读 issue、提交 PR 流程，指导开发者参与开源贡献。
 | 原文链接：http://book.wgbnko.asia/blog/069012.Doc

原标题：golang 系统设计日志规范结构化日志落地
简介：golang grpc 负载均衡客户端实现，grpc 客户端负载均衡，轮询随机权重，分发请求到多个服务实例。
 | 原文链接：http://book.wgbnko.asia/blog/472502.Doc

原标题：AI实践：大模型生成测试用例实践与校验
简介：Spring 事务传播机制配置生效，理解事务传播行为，正确配置，修复事务不生效、事务失效的业务 bug。
 | 原文链接：http://book.wgbnko.asia/blog/825905.Doc

原标题：一次JWT令牌过期时间异常问题复盘
简介：golang 分库分表简单路由实现，简易分表路由逻辑实现，根据分片 key 计算分片位置，数据路由写入。
 | 原文链接：http://book.wgbnko.asia/blog/711727.Doc

原标题：golang 系统设计 rest 版本管理几种方案对比
简介：golang html 模板防 xss 自动转义，理解 go html/template 自动转义，防止 XSS 攻击，处理不需要转义场景。
 | 原文链接：http://book.wgbnko.asia/blog/796249.Doc

原标题：本地运行正常线上报错排查
简介：Git 分支切换合并删除完整操作，实操分支全生命周期操作，包含切换、合并、删除，熟悉日常开发分支处理流程。
 | 原文链接：http://book.wgbnko.asia/blog/229914.Doc

原标题：Practice：模拟网络抖动验证服务容错能力
简介：分布式任务调度集群原型开发，开发简易分布式调度原型，集群多节点运行，保证任务只执行一次。
 | 原文链接：http://book.wgbnko.asia/blog/216275.Doc

原标题：前端工程化 webpack 打包优化
简介：golang go http 服务器优雅关闭完整代码，http.Server Shutdown，等待现有请求处理完成关闭服务。
 | 原文链接：http://book.wgbnko.asia/blog/258168.Doc

原标题：Security：密码存储哈希加盐最佳实践
简介：golang gorm select 指定查询字段，指定查询字段，避免查询全部字段，减少数据传输，提升查询性能。
 | 原文链接：http://book.wgbnko.asia/blog/593755.Doc

原标题：GC 垃圾回收优化降低 CPU 占用
简介：GET POST 接口请求参数处理，讲解两种请求方式参数传递区别，演示参数接收、解析、校验，适配不同接口调用场景。
 | 原文链接：http://book.wgbnko.asia/blog/014729.Doc

原标题：线上故障：慢查询拖垮整个数据库服务
简介：golang httptest 模拟外部 http 服务，httptest.NewServer 模拟第三方 http 服务，单元测试 mock 外部接口。
 | 原文链接：http://book.wgbnko.asia/blog/878038.Doc

原标题：CI 流水线构建失败日志排查
简介：golang go 测试文件命名规范，_test.go 测试文件，TestXxx 单元测试函数命名规范。
 | 原文链接：http://book.wgbnko.asia/blog/729889.Doc

原标题：golang 系统设计告警升级通知策略配置思路
简介：跨域偶现失败配置修复，解决跨域问题时而复现时而正常，定位配置漏配、请求头异常等隐性问题。
 | 原文链接：http://book.wgbnko.asia/blog/651858.Doc

原标题：Issue：文件编码混合GBKUTF‑8乱码随机出现
简介：golang hmac 签名生成校验示例，hmac 生成消息签名，做接口请求签名，校验数据不被篡改。
 | 原文链接：http://book.wgbnko.asia/blog/087763.Doc

原标题：Nginx 静态代理负载均衡全套配置
简介：数据库排序规则统一结果一致，统一数据库表排序规则，解决不同环境查询排序结果不一致问题。
 | 原文链接：http://book.wgbnko.asia/blog/755641.Doc

原标题：部署复盘：数据库主从备份恢复演练实践
简介：golang panic 崩溃日志完整收集，捕获所有 panic，打印堆栈，记录日志，方便定位崩溃根源。
 | 原文链接：http://book.wgbnko.asia/blog/567627.Doc

原标题：golang es bool 查询条件组合技巧
简介：golang tcp keepalive 参数程序配置，go 程序设置 tcp keepalive，操作系统 tcp 保活参数，清理僵死连接。
 | 原文链接：http://book.wgbnko.asia/blog/012067.Doc

原标题：坑点：限流计数器重置时机错误，绕过限流规则
简介：golang netlink 系统信息获取，netlink 获取系统网络信息，网卡地址，内核网络状态读取。
 | 原文链接：http://book.wgbnko.asia/blog/892496.Doc

原标题：踩坑：幂等键生成逻辑错误造成重复业务
简介：SDK 版本兼容线上崩溃修复，处理 SDK 版本升级之后线上崩溃，定位 API 变更，做版本兼容适配改造。
 | 原文链接：http://book.wgbnko.asia/blog/193991.Doc

原标题：golang 分布式 ID 雪花算法实现
简介：golang 重试退避机制代码实现，Go 实现请求重试与指数退避，处理临时故障，提升调用稳定性。
 | 原文链接：http://book.wgbnko.asia/blog/339025.Doc

原标题：golang 系统设计数据库扩容几种方式
简介：golang redis geo 地理位置存储查询，Redis GEO 存储经纬度，查询附近点位，实现附近人业务功能。
 | 原文链接：http://book.wgbnko.asia/blog/738093.Doc

原标题：golang 系统设计日志采样降低存储开销方案
简介：golang go 网络编程 net 包基础，net 包 tcp udp socket 编程，监听接收连接，读写数据。
 | 原文链接：http://book.wgbnko.asia/blog/308335.Doc

原标题：golang 系统设计消息 key 选择保证顺序性方案
简介：golang tidb 数据库 go 项目适配，go 程序适配 tidb，兼容 mysql 协议，分布式数据库业务开发。
 | 原文链接：http://book.wgbnko.asia/blog/185741.Doc

原标题：golang kafka 批量发送消费优化
简介：nodejs redis 缓存业务实战，Node 对接 Redis 实现业务缓存，缓存热点查询结果，减轻数据库压力。
 | 原文链接：http://book.wgbnko.asia/blog/871226.Doc

原标题：Debug：表单提交特殊字符造成接口解析失败
简介：golang go 线上故障排查完整流程，CPU 高、内存上涨、接口超时、goroutine 泄露一套排查处理流程。
 | 原文链接：http://book.wgbnko.asia/blog/854675.Doc

原标题：golang 系统设计索引设计通用方法论汇总
简介：服务器 Swap 关闭提升响应速度，关闭服务器 Swap 交换分区，避免内存交换磁盘拖慢程序响应性能。
 | 原文链接：http://book.wgbnko.asia/blog/603561.Doc

原标题：复盘总结：线上故障完整复盘报告模板示例
简介：代码模块化组件化拆分思路，讲解代码拆分原则，将大业务拆分为独立模块组件，提升代码复用与维护能力。
 | 原文链接：http://book.wgbnko.asia/blog/644331.Doc

原标题：Hands‑on：简易导出PDF后端生成demo实践
简介：golang rabbitmq go 客户端生产消费，streadway/amqp 实现 rabbitmq 生产者消费者，队列交换机绑定。
 | 原文链接：http://book.wgbnko.asia/blog/820317.Doc

原标题：后端登录鉴权模块完整开发
简介：nodejs 多进程任务分发处理，多进程拆分处理 CPU 密集任务，主进程分发任务，利用多核提升处理速度。
 | 原文链接：http://book.wgbnko.asia/blog/921507.Doc

原标题：golang docker 镜像体积优化技巧
简介：golang go 程序 CPU 占用高定位步骤，pprof 定位热点函数，分析 CPU 高占用，优化耗时代码逻辑。
 | 原文链接：http://book.wgbnko.asia/blog/778918.Doc


二、踩坑排错｜Troubleshooting
原标题：多环境配置中心灵活切换方案
简介：全平台系统环境变量配置，汇总多操作系统环境变量配置方法，统一项目读取逻辑，适配不同运行平台。
 | 原文链接：http://book.wgbnko.asia/blog/508807.Doc

原标题：性能笔记：连接池参数调优数据库RPC连接池
简介：Nginx 缓冲区调优大文件上传，调大 Nginx 请求缓冲区，支持客户端上传大体积文件，避免上传被截断。
 | 原文链接：http://book.wgbnko.asia/blog/707014.Doc

原标题：golang k8s 镜像拉取密钥配置
简介：golang redis stream 消息队列实战，redis stream 实现可靠消息队列，消费组、ack 确认，消息不丢失。
 | 原文链接：http://book.wgbnko.asia/blog/642591.Doc

原标题：从零搭建简单定时任务demo
简介：golang 空接口 interface {} 类型处理，interface {} 存储任意类型，类型转换，处理泛型之前通用数据。
 | 原文链接：http://book.wgbnko.asia/blog/823600.Doc

原标题：项目实践：搭建监控大盘查看系统关键指标
简介：golang prometheus client 业务埋点实操，prometheus client‑go 业务埋点，计数器、仪表盘、直方图指标开发。
 | 原文链接：http://book.wgbnko.asia/blog/522355.Doc

原标题：数据库索引重建提升查询速度
简介：golang wasm webassembly go 编译，go 编译为 wasm，浏览器执行 go 代码，拓展 go 运行场景。
 | 原文链接：http://book.wgbnko.asia/blog/861425.Doc

原标题：golang 系统设计分布式锁选型对比
简介：golang go‑zero 配置中心热更新，go‑zero 对接 etcd 配置中心，配置热更新无需重启服务。
 | 原文链接：http://book.wgbnko.asia/blog/307685.Doc

原标题：设计思考：消息队列重复消费架构层防御手段
简介：移动端适配 rem vw 方案对比，对比 rem 与 vw 移动端适配方案，分析优缺点，给出选型建议。
 | 原文链接：http://book.wgbnko.asia/blog/722106.Doc

原标题：性能笔记：TCP参数内核调优服务高并发场景
简介：golang go mod replace 本地模块替换，replace 替换模块为本地目录，修改第三方库本地调试。
 | 原文链接：http://book.wgbnko.asia/blog/489807.Doc

原标题：express 中间件开发业务实践
简介：rebase 操作防止代码丢失，讲解 rebase 风险点，操作前做好备份，规避错误操作造成代码提交丢失。
 | 原文链接：http://book.wgbnko.asia/blog/525874.Doc

原标题：踩坑：大报文传输，RPC消息超过大小限制
简介：golang 模板函数自定义拓展，自定义 template 模板函数，在 html 模板调用自定义逻辑处理数据。
 | 原文链接：http://book.wgbnko.asia/blog/075244.Doc

原标题：golang 系统设计传输加密 tls 配置要点
简介：golang 半关闭 tcp 连接 shutdown，tcp 连接 shutdown 半关闭，单向关闭读或者写，理解 tcp 关闭流程。
 | 原文链接：http://book.wgbnko.asia/blog/040617.Doc

原标题：业务接口幂等完整落地案例
简介：golang 静态文件服务搭建教程，Go 搭建静态文件服务，托管静态资源，实现文件直接对外访问。
 | 原文链接：http://book.wgbnko.asia/blog/787733.Doc

原标题：golang mongodb 聚合管道实操案例
简介：golang 单元测试 mock http 请求，mock HTTP 外部接口，单元测试不依赖外部网络，保证用例稳定运行。
 | 原文链接：http://book.wgbnko.asia/blog/901740.Doc

原标题：定时任务重复执行分布式锁
简介：golang time 时间格式化参考时间牢记，2006‑01‑02T15:04:05Z07:00，掌握 go 时间格式化关键点。
 | 原文链接：http://book.wgbnko.asia/blog/275452.Doc

原标题：设计思考：容器化业务应用架构改造要点
简介：Docker 网络模式容器互通设置，选择合适 Docker 网络模式，实现容器之间网络互相访问通信。
 | 原文链接：http://book.wgbnko.asia/blog/208199.Doc

原标题：golang 系统设计令牌桶漏桶算法对比
简介：golang 限流器熔断降级组合使用，限流熔断降级组合架构，流量防护完整方案，保障服务稳定性。
 | 原文链接：http://book.wgbnko.asia/blog/999867.Doc

原标题：golang k8s 网络策略网络隔离设置
简介：静态站点自动部署发布方案，配置流水线，代码更新自动构建静态站点并且部署上线，简化发布。
 | 原文链接：http://book.wgbnko.asia/blog/082226.Doc

原标题：golang 系统设计 api 接口兼容性设计原则
简介：golang 限制 multipart 内存大小，设置 MaxMemory，大文件写入磁盘临时文件防止内存暴涨。
 | 原文链接：http://book.wgbnko.asia/blog/484173.Doc

原标题：Performance：JSON序列化性能优化实践
简介：golang panic 崩溃日志完整收集，捕获所有 panic，打印堆栈，记录日志，方便定位崩溃根源。
 | 原文链接：http://book.wgbnko.asia/blog/785151.Doc

原标题：Issue：文件句柄耗尽，服务缓慢卡死复盘
简介：nodejs 读取大文件 csv 处理方案，Node 流式读取超大 CSV 文件，逐行解析，避免一次性加载全部文件。
 | 原文链接：http://book.wgbnko.asia/blog/132852.Doc

原标题：前端下载导出文件功能实现
简介：golang sort 切片排序自定义 less，sort.Slice 切片快速排序，自定义 less 函数实现业务排序。
 | 原文链接：http://book.wgbnko.asia/blog/596993.Doc

原标题：Issue：操作系统最大打开文件数限制导致报错
简介：golang strconv 字符串类型转换，字符串转数字布尔，处理转换失败 error，避免 panic。
 | 原文链接：http://book.wgbnko.asia/blog/537538.Doc

原标题：golang minio 预签名 url 临时访问
简介：golang grpc keepalive 保活配置，grpc keepalive 参数调优，检测断开僵死连接，释放无效连接资源。
 | 原文链接：http://book.wgbnko.asia/blog/839526.Doc

原标题：Security：服务器最小权限账号运维实践
简介：﻿从零搭建本地开发环境完整教程，手把手完成环境配置，梳理踩坑点，帮助开发者快速搭建可用的本地开发环境，降低上手成本。
 | 原文链接：http://book.wgbnko.asia/blog/449582.Doc

原标题：golang 系统设计降级策略开关配置方案
简介：项目依赖安全扫描漏洞防范，扫描项目第三方依赖包，修复存在安全漏洞依赖，防范供应链攻击。
 | 原文链接：http://book.wgbnko.asia/blog/671068.Doc

原标题：golang 系统设计本地消息表可靠消息最终一致性
简介：接口幂等性防重复请求实现，实现接口幂等逻辑，避免重复提交请求产生多条脏数据，保障业务数据安全。
 | 原文链接：http://book.wgbnko.asia/blog/637087.Doc

原标题：快速入门Nginx基础配置，反向代理示例
简介：异步编程 Promise 执行流程解析，拆解异步执行顺序，理解回调与 Promise 差异，理清异步场景下代码执行逻辑。
 | 原文链接：http://book.wgbnko.asia/blog/993534.Doc

原标题：程序性能指标 CPU 内存监控
简介：golang http cookie jar 会话处理，客户端 cookie jar 自动管理 cookie，处理登录态会话。
 | 原文链接：http://book.wgbnko.asia/blog/566331.Doc

原标题：golang docker 镜像体积优化技巧
简介：golang grpc 客户端流上传数据，客户端流式请求，客户端分批上传数据到服务端，适合大文件传输。
 | 原文链接：http://book.wgbnko.asia/blog/933099.Doc

原标题：Hands‑on：简易频率统计组件Redis实现
简介：golang http MaxHeaderBytes 限制请求头，设置 http 最大请求头大小，防止超大 header 攻击。
 | 原文链接：http://book.wgbnko.asia/blog/477816.Doc

原标题：入门实践：简单重试逻辑封装实现
简介：golang sort 稳定排序 Stable，稳定排序保留相等元素原有顺序，业务需要稳定排序场景。
 | 原文链接：http://book.wgbnko.asia/blog/507913.Doc

原标题：golang 系统设计定时任务调度时间校准要点
简介：SSH 密钥配置 GitHub 免密登录，分步生成配置 SSH 密钥，实现 GitHub 免密推送拉取，免去重复输入账号密码的麻烦。
 | 原文链接：http://book.wgbnko.asia/blog/601357.Doc

原标题：实践：Git工作流主干开发团队协作实践
简介：golang 分布式锁 redis 实现，基于 Redis 实现 Go 分布式锁，解决多实例并发竞争资源问题。
 | 原文链接：http://book.wgbnko.asia/blog/010644.Doc

原标题：CDN 缓存刷新获取最新静态资源
简介：golang 信号量 semaphore 并发限制，基于 semaphore 实现并发数量控制，保护数据库、第三方接口不被打满。
 | 原文链接：http://book.wgbnko.asia/blog/748689.Doc

原标题：golang 系统设计唯一索引业务使用场景
简介：golang uuid 生成多种版本实现，生成 uuid v1 v4，生成唯一标识，业务用于单据编号场景。
 | 原文链接：http://book.wgbnko.asia/blog/523843.Doc

原标题：golang jaeger 链路追踪 go 接入
简介：golang gorm 事务手动回滚提交，手动控制事务流程，业务异常主动回滚，保障数据操作原子性。
 | 原文链接：http://book.wgbnko.asia/blog/074358.Doc

原标题：设计思考：分布式系统时钟同步带来的架构问题
简介：nodejs 内存溢出问题排查修复，Node.js 程序 OOM 排查流程，定位内存泄露，调整内存限制修复崩溃。
 | 原文链接：http://book.wgbnko.asia/blog/567972.Doc

原标题：golang 系统设计日志脱敏敏感字段过滤处理
简介：批量异步处理系统业务落地，构建批量异步处理系统，把耗时业务异步化，提升接口响应速度。
 | 原文链接：http://book.wgbnko.asia/blog/014211.Doc

原标题：golang prometheus histogram 指标
简介：依赖安装失败全方位排错，从网络、镜像源、权限、版本多角度，定位依赖安装失败，给出对应修复手段。
 | 原文链接：http://book.wgbnko.asia/blog/724652.Doc

三、实战开发｜Practice
原标题：YAML 配置文件语法快速上手
简介：WebSocket 双向通信 demo 开发，搭建简易 WebSocket 服务，实现客户端服务端双向消息推送，理解实时通信原理。
 | 原文链接：http://book.wgbnko.asia/blog/010136.Doc

原标题：Hands‑on：简易的事件订阅发布组件开发实践
简介：golang delve 远程调试 go 线上程序，delve 远程调试，线上环境附加进程调试排查线上 bug。
 | 原文链接：http://book.wgbnko.asia/blog/494255.Doc

原标题：单元测试用例编写入门实操
简介：golang influxdb 时序数据库读写操作，influxdb 存储时序指标，业务指标监控数据存取。
 | 原文链接：http://book.wgbnko.asia/blog/293576.Doc

原标题：定时任务重复执行分布式锁
简介：golang sync.Once 只执行一次，sync.Once 做单例初始化，保证代码只执行一次，并发安全。
 | 原文链接：http://book.wgbnko.asia/blog/826513.Doc

原标题：golang 系统设计第三方调用超时重试熔断
简介：golang 任务失败重试与死信队列，异步任务失败自动重试，超过重试次数进入死信队列人工处理。
 | 原文链接：http://book.wgbnko.asia/blog/152618.Doc

原标题：依赖版本冲突兼容修复方案
简介：防火墙 IP 白名单回调接口放行，配置防火墙白名单，放行第三方回调服务器 IP，接收回调请求正常。
 | 原文链接：http://book.wgbnko.asia/blog/076900.Doc

原标题：golang 系统设计主键 id 选型雪花自增对比
简介：序列化版本不一致解析失败，保证序列化对象版本对齐，修复版本不匹配导致对象反序列化失败。
 | 原文链接：http://book.wgbnko.asia/blog/743028.Doc

原标题：Debug：长连接未设置心跳，连接僵死不回收
简介：移动端适配 rem vw 方案对比，对比 rem 与 vw 移动端适配方案，分析优缺点，给出选型建议。
 | 原文链接：http://book.wgbnko.asia/blog/311330.Doc

原标题：数据库死锁成因规避方案
简介：前端权限路由动态生成实现，根据后端返回权限，动态生成前端路由菜单，实现页面权限控制。
 | 原文链接：http://book.wgbnko.asia/blog/742924.Doc

原标题：开发复盘：消息队列消息顺序性业务落地实践
简介：golang go 逃逸分析实操查看，go build‑gcflags=-m 查看逃逸分析，减少堆分配优化程序性能。
 | 原文链接：http://book.wgbnko.asia/blog/687955.Doc

原标题：项目实践：实现统一接口返回封装与全局异常处理
简介：请求重试组件退避策略实现，封装重试组件，实现指数退避策略，避免大量请求同时重试压垮下游。
 | 原文链接：http://book.wgbnko.asia/blog/777248.Doc

原标题：坑点：环境配置被打包进镜像引发安全泄露
简介：golang tcp_NODELAY 关闭延迟发送，设置 tcp_NODELAY，关闭 Nagle 算法，降低小包请求延迟。
 | 原文链接：http://book.wgbnko.asia/blog/718352.Doc

原标题：Hands‑on：模拟RPC超时重试业务异常场景
简介：golang go race 竞态检测工具，‑race 检测数据竞争，编译运行检测并发读写数据竞争 bug。
 | 原文链接：http://book.wgbnko.asia/blog/156321.Doc

原标题：Troubleshoot：跨库关联查询，性能急剧恶化
简介：golang go 无锁并发编程技巧，原子操作 sync/atomic，简单场景替换锁，提升并发性能。
 | 原文链接：http://book.wgbnko.asia/blog/789583.Doc

原标题：实践：多配置文件合并加载组件实现
简介：golang interface 接口使用避坑，interface 判 nil 坑点，理解接口底层结构，避免判空逻辑失效。
 | 原文链接：http://book.wgbnko.asia/blog/712185.Doc

原标题：Git 标签版本标记发布管理
简介：golang gin 中间件执行顺序讲解，理解 Gin 中间件注册顺序，区分前置后置逻辑，规避中间件顺序 bug。
 | 原文链接：http://book.wgbnko.asia/blog/379887.Doc

原标题：golang 内存缓存简单实现方案
简介：nestjs 框架模块化项目搭建，从零搭建 NestJS 项目，模块化拆分业务，搭建规范后端项目骨架。
 | 原文链接：http://book.wgbnko.asia/blog/537912.Doc

原标题：部署实践：HTTPS证书自动续期配置实践
简介：golang 图片处理 go 图片裁剪压缩，golang 图像处理库，图片缩放裁剪水印，服务端图片处理。
 | 原文链接：http://book.wgbnko.asia/blog/679239.Doc

原标题：Hands‑on：简易代理服务器开发实践
简介：前端防抖节流高频事件处理，封装防抖节流工具，处理滚动、输入框输入等高频触发事件减少执行次数。
 | 原文链接：http://book.wgbnko.asia/blog/155192.Doc

原标题：golang 布隆过滤器实现去重
简介：golang mqtt 客户端 go 开发物联网，paho.mqtt.golang 实现 mqtt 客户端，物联网设备消息收发。
 | 原文链接：http://book.wgbnko.asia/blog/678352.Doc

原标题：复盘总结：技术方案文档模板架构设计文档
简介：服务器 Swap 关闭提升响应速度，关闭服务器 Swap 交换分区，避免内存交换磁盘拖慢程序响应性能。
 | 原文链接：http://book.wgbnko.asia/blog/301039.Doc

原标题：golang 系统设计网关 ssl 证书配置更新实操
简介：golang nilnil interface 陷阱复现，interface 包含类型不为 nil 值为 nil，判 ==nil 返回 false 经典坑。
 | 原文链接：http://book.wgbnko.asia/blog/226979.Doc

原标题：排错：反向代理后获取真实IP全部变成内网IP
简介：内网测试服务搭建团队调试，配置本地服务内网可访问，团队成员能够访问调试，方便前后端联调与内部演示。
 | 原文链接：http://book.wgbnko.asia/blog/421657.Doc

原标题：golang 系统设计缓存优化落地实操指南
简介：灰度发布策略服务平滑升级，实现灰度发布逻辑，流量逐步切到新版本，出现问题快速回滚旧版本。
 | 原文链接：http://book.wgbnko.asia/blog/733226.Doc

原标题：语义化版本依赖管理防错乱
简介：golang time 定时器重置 Reset 正确用法，Timer Reset 调用前提，避免 Reset 带来逻辑错误。
 | 原文链接：http://book.wgbnko.asia/blog/757065.Doc

原标题：golang 协程 panic 捕获防止崩溃
简介：golang 静态文件服务搭建教程，Go 搭建静态文件服务，托管静态资源，实现文件直接对外访问。
 | 原文链接：http://book.wgbnko.asia/blog/792860.Doc

原标题：零基础理解幂等性基础概念与场景
简介：golang 数据库连接池参数调优详解，最大连接空闲连接最大生命周期，结合业务合理配置避免资源浪费。
 | 原文链接：http://book.wgbnko.asia/blog/611034.Doc

原标题：开发记录：长连接连接管理自动清理僵死连接
简介：golang context.WithValue 传递元数据，WithValue 只传 traceId 鉴权元数据，不要传业务大对象。
 | 原文链接：http://book.wgbnko.asia/blog/202502.Doc

原标题：golang 系统设计分布式锁超时业务防死锁处理
简介：golang elasticsearch 客户端 golang 实操，es 客户端文档增删改查，条件搜索聚合统计对接搜索引擎。
 | 原文链接：http://book.wgbnko.asia/blog/435440.Doc

原标题：Security：接口鉴权越权漏洞检测与修复
简介：golang panic 崩溃日志完整收集，捕获所有 panic，打印堆栈，记录日志，方便定位崩溃根源。
 | 原文链接：http://book.wgbnko.asia/blog/895141.Doc

原标题：golang 系统设计 rest 版本管理几种方案对比
简介：程序日志分级输出规范实践，区分日志等级，规范日志打印内容，合理输出日志，方便线上问题排查定位。
 | 原文链接：http://book.wgbnko.asia/blog/720287.Doc

原标题：golang 系统设计依赖漏洞扫描修复流程
简介：nodejs 消息队列消费服务开发，Node 开发消息队列消费端，监听队列消息执行业务逻辑，异步解耦业务。
 | 原文链接：http://book.wgbnko.asia/blog/107736.Doc

原标题：踩坑：大事务引发数据库连接池耗尽
简介：golang raw socket 底层网络报文收发，raw socket 收发原始网络报文，做网络抓包数据包处理。
 | 原文链接：http://book.wgbnko.asia/blog/286586.Doc

原标题：从零搭建本地数据库开发环境
简介：golang multipart 表单文件上传解析，服务端解析 multipart 表单，获取上传文件与表单字段。
 | 原文链接：http://book.wgbnko.asia/blog/462393.Doc

原标题：Security：文件路径穿越漏洞完整防护
简介：Git 分支管理多人协作实战教程，详解分支创建、合并、冲突处理，适配团队开发场景，规范多人协同代码工作流。
 | 原文链接：http://book.wgbnko.asia/blog/929394.Doc

原标题：golang 系统设计技术文档编写最佳实践
简介：golang grpc protobuf 开发实操，Go gRPC 开发，编写 Protobuf 定义，服务端客户端完整示例。
 | 原文链接：http://book.wgbnko.asia/blog/676879.Doc

原标题：golang 系统设计熔断降级架构讲解
简介：浏览器本地存储安全使用技巧，讲解 localStorage、sessionStorage 使用边界，规避 XSS 泄露存储数据。
 | 原文链接：http://book.wgbnko.asia/blog/600405.Doc

原标题：golang 系统设计缓存空值防止缓存穿透实现
简介：golang go 程序守护进程实现思路，go 程序不做 daemon 化，依靠 systemd pm2 k8s 实现进程守护。
 | 原文链接：http://book.wgbnko.asia/blog/726442.Doc

原标题：CI 持续集成自动构建流程
简介：golang consul 服务发现简单示例，对接 Consul 实现服务注册发现，微服务实例自动感知。
 | 原文链接：http://book.wgbnko.asia/blog/046408.Doc

原标题：Mock 接口服务快速搭建实操
简介：全局本地依赖隔离冲突规避，区分全局依赖与项目本地依赖，隔离环境，防止全局包干扰项目运行。
 | 原文链接：http://book.wgbnko.asia/blog/034526.Doc

四、架构设计｜Architecture
原标题：实践：实现Redis分布式锁完整可运行代码
简介：golang gorm 索引设置与优化技巧，定义数据库索引，理解索引生效条件，避免索引失效慢查询。
 | 原文链接：http://book.wgbnko.asia/blog/595258.Doc

原标题：css 变量主题切换方案实现
简介：缓存过期策略优化防业务故障，合理设置缓存过期策略，规避集中过期，减少缓存失效带来业务抖动。
 | 原文链接：http://book.wgbnko.asia/blog/014216.Doc

原标题：开发记录：服务优雅关闭释放资源完整实现
简介：golang go 时间 time.Timer time.Ticker，定时器与周期定时器，Stop Reset 正确使用，防止资源泄漏。
 | 原文链接：http://book.wgbnko.asia/blog/096501.Doc

原标题：数值 key 浮点匹配异常规避
简介：WebSocket 断线重连稳定优化，增加 WebSocket 断线自动重连逻辑，处理网络抖动，维持长连接稳定。
 | 原文链接：http://book.wgbnko.asia/blog/923712.Doc

原标题：golang 系统设计采样策略降低链路存储开销
简介：数据库死锁成因规避方案，讲解数据库死锁产生条件，给出业务层面规避手段，减少死锁事件发生。
 | 原文链接：http://book.wgbnko.asia/blog/881783.Doc

原标题：项目实践：定时任务防重复执行落地实践
简介：golang redis list 队列简易消息队列，利用 Redis List 实现简易队列，完成任务入队消费基础能力。
 | 原文链接：http://book.wgbnko.asia/blog/410859.Doc

原标题：方案对比：轮询长轮询WebSocket推送架构选型
简介：golang 配置文件多环境加载，Go 多环境配置加载实现，读取配置文件环境变量，适配多套运行环境。
 | 原文链接：http://book.wgbnko.asia/blog/228736.Doc

原标题：golang 系统设计技术债务识别登记治理思路
简介：golang go http 文件服务器自定义，http.FileServer 自定义 FileSystem，拦截访问，增加鉴权逻辑。
 | 原文链接：http://book.wgbnko.asia/blog/870913.Doc

原标题：一次数据库死锁现场分析与解决方案记录
简介：分布式 ID 全局唯一生成方案，讲解分布式 ID 生成思路，实现全局唯一 ID，满足分布式系统主键生成需求。
 | 原文链接：http://book.wgbnko.asia/blog/553925.Doc

原标题：实战：单元测试+集成测试完整项目落地实践
简介：Git 误提交撤销回退实操教程，演示多种撤销提交方式，区分已经推送远程和本地未提交场景，处理误提交代码。
 | 原文链接：http://book.wgbnko.asia/blog/229128.Doc

原标题：性能笔记：锁优化减少竞争提升并发吞吐
简介：跨平台 uniapp 多端开发实操，uniapp 开发一套代码，编译多端，梳理多端差异处理与适配技巧。
 | 原文链接：http://book.wgbnko.asia/blog/262075.Doc

原标题：Issue：本地数据库与线上数据库排序规则差异
简介：golang 设置 net.Conn 读写超时，每次读写设置超时，防止连接永久阻塞挂起不返回。
 | 原文链接：http://book.wgbnko.asia/blog/484763.Doc

原标题：线上故障：热点Key打满RedisCPU节点过载
简介：golang bytes.Buffer 字节缓冲区使用，bytes.Buffer 字节内存缓冲区，拼接字节，避免频繁内存分配。
 | 原文链接：http://book.wgbnko.asia/blog/663846.Doc

原标题：Nginx 透传真实客户端 IP 配置
简介：golang 内存碎片问题识别与规避，大量小对象频繁分配产生内存碎片，通过对象池减少碎片。
 | 原文链接：http://book.wgbnko.asia/blog/630140.Doc

原标题：golang 系统设计代码安全审计简单思路
简介：布隆过滤器误判问题修正，调整布隆过滤器参数，降低误判概率，保证业务去重逻辑准确。
 | 原文链接：http://book.wgbnko.asia/blog/882005.Doc

原标题：服务器 Swap 关闭提升响应速度
简介：golang 配置中心 apollo go 客户端，apollo go sdk 读取配置，配置变更自动热更新无需重启服务。
 | 原文链接：http://book.wgbnko.asia/blog/944299.Doc

原标题：部署复盘：静态资源版本哈希缓存策略
简介：正则表达式优化 CPU 占满问题，优化正则表达式写法，避免回溯，防止正则运算 CPU 占用 100%。
 | 原文链接：http://book.wgbnko.asia/blog/827958.Doc

原标题：快速入门：API接口调试完整实操步骤
简介：异步异常捕获避免进程崩溃，捕获异步代码内部抛出异常，防止未捕获异常直接导致整个进程退出。
 | 原文链接：http://book.wgbnko.asia/blog/184517.Doc

?
