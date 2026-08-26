最新前沿技术资讯

一、入门教程｜Getting Started
原标题：Architecture：安全防护架构XSSCSRFSQL注入防御
简介：golang sync.WaitGroup 协程等待控制，WaitGroup 控制一组协程等待全部执行完成，完成批量协程任务调度。
 | 原文链接：http://wiki.z26bb9.asia/arts/400210.Doc

原标题：golang 系统设计埋点数据上报方案
简介：golang 雪花 id 重复问题排查，排查雪花算法 ID 重复问题，时钟回拨、机器 ID 冲突，给出修复方案。
 | 原文链接：http://wiki.z26bb9.asia/arts/429784.Doc

原标题：Docker 多阶段构建镜像瘦身
简介：golang go http 静态文件禁止目录遍历，http.FileServer 防止../ 路径穿越，了解底层安全实现。
 | 原文链接：http://wiki.z26bb9.asia/arts/723583.Doc

原标题：语义化版本依赖管理防错乱
简介：golang GC 调优 GOGC 参数调整，调整 GOGC 阈值，控制 GC 触发时机，权衡内存占用与 CPU 开销。
 | 原文链接：http://wiki.z26bb9.asia/arts/926125.Doc

原标题：golang es 分词器选型业务适配
简介：golang 内存持续上涨定位思路，区分内存泄漏、缓存占用、GC 参数不合理，分步定位内存持续走高。
 | 原文链接：http://wiki.z26bb9.asia/arts/745476.Doc

原标题：golang ci 流水线单元测试集成测试
简介：文件分片上传断点续传功能，实现文件分片上传，记录上传进度，支持断点续传大文件上传。
 | 原文链接：http://wiki.z26bb9.asia/arts/388457.Doc

原标题：内网 DNS 不稳定随机报错排查
简介：GET POST 接口请求参数处理，讲解两种请求方式参数传递区别，演示参数接收、解析、校验，适配不同接口调用场景。
 | 原文链接：http://wiki.z26bb9.asia/arts/537289.Doc

原标题：Issue：定时任务并发执行未加锁重复执行业务
简介：前端下载导出文件功能实现，前端实现文件流下载导出，处理异常，适配浏览器不同下载行为。
 | 原文链接：http://wiki.z26bb9.asia/arts/453186.Doc

原标题：从零搭建本地数据库开发环境
简介：开发环境变量配置全平台教程，区分 Windows、macOS、Linux 系统，讲解环境变量配置、加载优先级与常见失效原因。
 | 原文链接：http://wiki.z26bb9.asia/arts/025918.Doc

原标题：记一次分布式锁失效引发的数据错乱问题
简介：golang ctx 关闭之后资源释放，context 取消后，监听 Done ()，释放 goroutine 网络 IO 资源。
 | 原文链接：http://wiki.z26bb9.asia/arts/161541.Doc

原标题：JWT 令牌过期异常处理
简介：golang 系统 IO 阻塞 goroutine 场景，理解系统调用阻塞 M，P 会调度其他 M，掌握 go 调度行为。
 | 原文链接：http://wiki.z26bb9.asia/arts/401614.Doc

原标题：实战：数据库索引设计，复合索引最佳实践
简介：服务器时钟同步任务错乱修复，配置服务器 NTP 时间同步，保证集群所有机器时间保持一致。
 | 原文链接：http://wiki.z26bb9.asia/arts/799529.Doc

原标题：golang mysql 读写分离简单实现
简介：超大数据集分页性能优化方案，对比不同分页方案，针对海量数据集做分页性能优化，解决越翻越慢。
 | 原文链接：http://wiki.z26bb9.asia/arts/123286.Doc

原标题：架构笔记：分布式系统常见一致性模型梳理
简介：跨库查询性能优化处理，减少跨库关联查询，做数据冗余或者中间表，规避跨库查询性能低下。
 | 原文链接：http://wiki.z26bb9.asia/arts/057241.Doc

原标题：设计思考：系统幂等性整体架构层面保障
简介：golang 日志脱敏敏感字段过滤，日志打印自动脱敏敏感字段，避免日志输出手机号身份证泄露隐私。
 | 原文链接：http://wiki.z26bb9.asia/arts/372522.Doc

原标题：golang redis 五种数据结构实战
简介：golang 项目 makefile 脚本编写，编写 Makefile 脚本，封装编译、测试、构建命令，简化项目操作。
 | 原文链接：http://wiki.z26bb9.asia/arts/748553.Doc

原标题：实战：Nginx配置静态站点、反向代理、负载均衡
简介：WSL 搭建 Windows Linux 开发环境，配置 WSL 环境，在 Windows 系统使用 Linux 工具链，适配 Linux 开发项目。
 | 原文链接：http://wiki.z26bb9.asia/arts/343742.Doc

原标题：实战项目：容器资源限制配置压力测试实践
简介：大事务拆分回滚日志暴涨解决，拆分大型数据库事务，减少回滚日志生成量，避免磁盘被回滚日志占满。
 | 原文链接：http://wiki.z26bb9.asia/arts/598333.Doc

原标题：零基础理解进程、线程基础概念区别
简介：Docker 多阶段构建镜像瘦身，使用 Docker 多阶段构建，剔除编译阶段依赖，产出体积更小运行镜像。
 | 原文链接：http://wiki.z26bb9.asia/arts/314654.Doc

原标题：日志输出规范防止磁盘爆满
简介：golang go 零停机升级实践要点，socket 继承，流量无损，旧连接处理完毕后旧进程退出。
 | 原文链接：http://wiki.z26bb9.asia/arts/400807.Doc

原标题：坑点：gitrebase操作失误，代码提交丢失
简介：golang rabbitmq go 客户端生产消费，streadway/amqp 实现 rabbitmq 生产者消费者，队列交换机绑定。
 | 原文链接：http://wiki.z26bb9.asia/arts/326880.Doc

原标题：实战：Redis集群本地搭建与功能验证
简介：golang regexp 正则捕获分组提取数据，正则捕获分组提取子匹配内容，拿到需要业务字段。
 | 原文链接：http://wiki.z26bb9.asia/arts/123266.Doc

原标题：Practice：实现接口幂等性多种方案对比实践
简介：golang 异步任务队列 worker 池开发，任务入数据库或 redis，worker 池消费执行，异步处理耗时业务。
 | 原文链接：http://wiki.z26bb9.asia/arts/308982.Doc

原标题：golang gorm 批量插入性能调优
简介：golang net.Conn 包装自定义连接，包装 net.Conn，统计读写字节，日志打印，超时控制。
 | 原文链接：http://wiki.z26bb9.asia/arts/072876.Doc

原标题：DNS TTL 配置域名切换生效
简介：golang go 爬虫 robots 协议遵守，解析 robots.txt 规则，控制爬虫抓取范围，合规采集网页数据。
 | 原文链接：http://wiki.z26bb9.asia/arts/584339.Doc

原标题：从零学习基础的接口请求与参数处理
简介：数据库分表存储大表优化方案，对超大数据表做分表，拆分数据，降低单表数据量提升查询性能。
 | 原文链接：http://wiki.z26bb9.asia/arts/293553.Doc

原标题：golang 系统设计日志规范结构化日志落地
简介：golang sort 稳定排序 Stable，稳定排序保留相等元素原有顺序，业务需要稳定排序场景。
 | 原文链接：http://wiki.z26bb9.asia/arts/185034.Doc

原标题：golang proto 默认值坑点梳理
简介：golang docker 镜像构建最佳实践，Go 项目 Docker 镜像构建最佳实践，减小镜像体积，安全构建。
 | 原文链接：http://wiki.z26bb9.asia/arts/606217.Doc

原标题：踩坑：分布式事务状态不一致数据两边不一致
简介：golang 文件上传下载接口开发，Go 开发文件上传下载接口，校验文件，处理文件读写存储逻辑。
 | 原文链接：http://wiki.z26bb9.asia/arts/122486.Doc

原标题：golang 集成测试启动测试数据库
简介：golang 环境变量读取与类型转换，读取系统环境变量，做类型转换默认值处理，适配多环境部署。
 | 原文链接：http://wiki.z26bb9.asia/arts/047286.Doc

原标题：K8s 镜像拉取网络故障修复
简介：Dockerfile 编写容器打包实战，讲解 Dockerfile 指令含义，编写镜像构建脚本，将本地项目打包成可分发容器镜像。
 | 原文链接：http://wiki.z26bb9.asia/arts/181471.Doc

原标题：golang 系统设计监控告警体系搭建思路
简介：简易日志收集集中管理方案，搭建轻量日志收集方案，把多服务日志汇总，集中检索查看日志信息。
 | 原文链接：http://wiki.z26bb9.asia/arts/819366.Doc

原标题：golang 系统设计数据库查询优化完整流程
简介：程序预加载加快服务启动速度，把高频使用资源提前预加载，减少请求阶段初始化，加快服务启动。
 | 原文链接：http://wiki.z26bb9.asia/arts/544791.Doc

原标题：golang 接口限流中间件开发
简介：golang go mod graph 可视化依赖图，可视化 go 依赖关系，直观看到包之间依赖，定位冲突。
 | 原文链接：http://wiki.z26bb9.asia/arts/012510.Doc

原标题：踩坑记录：分页逻辑错误造成数据重复输出
简介：golang math 包常用数学函数，绝对值取整平方根三角函数，业务数学计算工具。
 | 原文链接：http://wiki.z26bb9.asia/arts/075283.Doc

原标题：golang mysql 主从同步延迟兼容
简介：定时任务周期调度 demo 开发，实现简单定时调度程序，按时间周期执行业务逻辑，理解定时任务运行机制。
 | 原文链接：http://wiki.z26bb9.asia/arts/191403.Doc

原标题：echarts 大数据渲染性能调优
简介：nodejs 读取大文件 csv 处理方案，Node 流式读取超大 CSV 文件，逐行解析，避免一次性加载全部文件。
 | 原文链接：http://wiki.z26bb9.asia/arts/391103.Doc

原标题：静态网页 HTML CSS 快速入门实战
简介：golang systemd 配置 go 服务部署，编写 systemd unit 文件管理 go 服务，开机自启、崩溃自动重启。
 | 原文链接：http://wiki.z26bb9.asia/arts/196681.Doc

原标题：快速入门YAML配置文件语法与示例
简介：Shell 运维脚本服务器效率提升，编写常用运维 Shell 脚本，自动化服务器运维操作，减少手工重复工作。
 | 原文链接：http://wiki.z26bb9.asia/arts/441129.Doc

原标题：golang 系统设计本地缓存更新失效方案实现
简介：golang go‑zero api 接口开发与路由，go‑zero 编写 api 定义文件，生成代码开发 http 接口。
 | 原文链接：http://wiki.z26bb9.asia/arts/896119.Doc


二、踩坑排错｜Troubleshooting
原标题：避坑：CookieSecure属性造成测试环境登录失败
简介：hosts 配置本地回环访问修复，修改 hosts 配置，修复 127.0.0.1 解析异常，本地服务访问失败问题。
 | 原文链接：http://wiki.z26bb9.asia/arts/295872.Doc

原标题：golang 系统设计分库分表 id 全局生成策略
简介：golang contract 契约测试微服务，微服务契约测试，保证接口变更不破坏调用方，提前发现兼容性问题。
 | 原文链接：http://wiki.z26bb9.asia/arts/537709.Doc

原标题：零基础理解版本控制核心概念与工作流
简介：数据库索引重建提升查询速度，针对碎片化索引，重建数据库索引，恢复 SQL 查询执行性能。
 | 原文链接：http://wiki.z26bb9.asia/arts/630723.Doc

原标题：接口限流逻辑简单模拟实现
简介：golang go 错误包装 fmt.Errorf % w，使用 % w 包装错误，支持 errors.Is errors.As 判断错误类型。
 | 原文链接：http://wiki.z26bb9.asia/arts/383515.Doc

原标题：架构复盘：业务系统中如何合理使用分库分表
简介：批量异步处理系统业务落地，构建批量异步处理系统，把耗时业务异步化，提升接口响应速度。
 | 原文链接：http://wiki.z26bb9.asia/arts/419648.Doc

原标题：Cookie 跨环境登录配置调整
简介：golang go 依赖漏洞检测 govulncheck，govulncheck 扫描依赖安全漏洞，发现项目供应链风险。
 | 原文链接：http://wiki.z26bb9.asia/arts/485410.Doc

原标题：golang mysql 时间类型选型避坑
简介：批量数据处理脚本编写技巧，编写脚本批量处理大量业务数据，循环处理、分批执行，提升数据处理效率。
 | 原文链接：http://wiki.z26bb9.asia/arts/337420.Doc

原标题：安全复盘：Redis未授权访问漏洞防护
简介：golang go json 序列化自定义字段，json 标签控制字段名称、忽略字段、omitempty 空值忽略。
 | 原文链接：http://wiki.z26bb9.asia/arts/757331.Doc

原标题：golang es 索引生命周期管理思路
简介：golang 数据库分表策略按时间分片，按时间维度分表，历史数据拆分，单表数据量控制保证查询性能。
 | 原文链接：http://wiki.z26bb9.asia/arts/228696.Doc

原标题：golang 系统设计开源项目 release 发布流程
简介：golang channel 缓冲无缓冲区别，缓冲 channel 与无缓冲 channel，底层行为差异业务选型参考。
 | 原文链接：http://wiki.z26bb9.asia/arts/850343.Doc

原标题：golang 系统设计消息消费 offset 管理策略
简介：重复提交幂等防护再次讲解，梳理前端重复点击、网络重试场景，落地接口幂等，杜绝重复业务。
 | 原文链接：http://wiki.z26bb9.asia/arts/860349.Doc

原标题：DevOps：环境配置管理区分开发测试生产
简介：golang go 初始化顺序包变量 init 函数，包级变量初始化，init 执行顺序，理解包加载执行流程。
 | 原文链接：http://wiki.z26bb9.asia/arts/211761.Doc

原标题：架构复盘：热点数据防护架构防止节点过载
简介：golang go 程序敏感信息禁止打印日志，密钥密码禁止输出日志，防止敏感信息日志泄露。
 | 原文链接：http://wiki.z26bb9.asia/arts/264576.Doc

原标题：架构复盘：多实例部署业务状态无状态改造
简介：golang mongodb go 驱动实操教程，mongo‑go‑driver 操作 mongodb，文档增删改查聚合查询。
 | 原文链接：http://wiki.z26bb9.asia/arts/233112.Doc

原标题：golang 系统设计消息幂等消费去重实现方案
简介：golang 消息队列 kafka 消费开发，Go 开发 Kafka 消费程序，消费消息执行业务，理解 Kafka 消费逻辑。
 | 原文链接：http://wiki.z26bb9.asia/arts/301334.Doc

原标题：入门实践：简易进度条CLI工具实现demo
简介：golang nats jetstream 持久消息队列，nats jetstream 持久化消息，保证消息不丢失，实现可靠消费。
 | 原文链接：http://wiki.z26bb9.asia/arts/937990.Doc

原标题：golang 灰度权重流量分发简单实现
简介：DNS TTL 配置域名切换生效，调整 DNS 解析 TTL，缩短缓存时间，域名变更后可以快速全网生效。
 | 原文链接：http://wiki.z26bb9.asia/arts/189380.Doc

原标题：OpenSource：开源项目许可证License选型指南
简介：golang k8s go 服务 yaml 资源编写，k8s 部署 go 应用 deployment service，健康检查资源限制配置。
 | 原文链接：http://wiki.z26bb9.asia/arts/630990.Doc

原标题：架构笔记：事件驱动架构适用场景与坑点
简介：golang go 调用动态链接库 so 文件，go 加载 so 动态库调用函数，复用编译好的 C 动态库。
 | 原文链接：http://wiki.z26bb9.asia/arts/872289.Doc

原标题：全局时间标准统一逻辑错乱修复
简介：项目目录结构规范化最佳实践，梳理源码、配置、静态资源目录划分，规范项目布局，提升代码可读性和可维护性。
 | 原文链接：http://wiki.z26bb9.asia/arts/199449.Doc

原标题：排错：多实例部署session共享失效登录失效
简介：数据库连接池参数调优，调整连接池最大最小连接数，空闲超时，避免连接耗尽或者资源浪费。
 | 原文链接：http://wiki.z26bb9.asia/arts/081919.Doc

原标题：设计思考：缓存分层架构设计与失效处理策略
简介：Mock 接口服务快速搭建实操，搭建模拟后端接口，自定义返回数据、延迟响应，前端开发阶段无需依赖真实后端服务。
 | 原文链接：http://wiki.z26bb9.asia/arts/077416.Doc

原标题：端口占用访问失败排查方案
简介：golang sync.Map 高并发 map 使用场景，sync.Map 适用场景，读写实操，对比普通 map 加锁性能差异。
 | 原文链接：http://wiki.z26bb9.asia/arts/414038.Doc

原标题：记一次GC频繁，服务CPU持续高负载排查
简介：开源项目本地运行排错完整清单，汇总开源项目拉取后运行失败各类问题，给出排查思路，快速解决本地启动异常。
 | 原文链接：http://wiki.z26bb9.asia/arts/192270.Doc

原标题：golang 系统设计网络 io 模型 epoll 原理讲解
简介：golang proto 默认值坑点梳理，梳理 Protobuf 默认值坑，零值字段区分未赋值，避免业务逻辑错误。
 | 原文链接：http://wiki.z26bb9.asia/arts/493525.Doc

原标题：项目实践：搭建个人API网关最小实现版本
简介：Docker 多阶段构建镜像瘦身，使用 Docker 多阶段构建，剔除编译阶段依赖，产出体积更小运行镜像。
 | 原文链接：http://wiki.z26bb9.asia/arts/754333.Doc

原标题：快速入门简单签名校验实现思路
简介：golang gorm 批量插入性能调优，GORM 批量插入优化，调整批次大小，提升大量数据插入数据库速度。
 | 原文链接：http://wiki.z26bb9.asia/arts/927023.Doc

原标题：部署实践：服务器防火墙安全组配置实践
简介：nodejs 脚手架工具开发完整教程，从零开发 Node 命令行脚手架，实现项目模板生成，理解 CLI 开发。
 | 原文链接：http://wiki.z26bb9.asia/arts/741282.Doc

原标题：大文件导出内存溢出防护
简介：Docker 容器网络不通排查，排查容器网络模式、端口映射、防火墙，解决容器之间、容器外部网络不通。
 | 原文链接：http://wiki.z26bb9.asia/arts/308147.Doc

原标题：golang es 查询语句 DSL 实操
简介：golang 协程数量监控统计方案，统计运行中 goroutine 数量，监控协程泄露，协程数量异常及时告警。
 | 原文链接：http://wiki.z26bb9.asia/arts/534006.Doc

原标题：golang 系统设计字符串拼接性能优化技巧
简介：前端图片懒加载性能优化，实现图片懒加载，页面可视区域才加载图片，减少页面初始网络请求。
 | 原文链接：http://wiki.z26bb9.asia/arts/330814.Doc

原标题：golang redis set 集合去重业务
简介：缓存穿透击穿雪崩全套防护，完整梳理缓存三大问题，落地全套防护策略，保障缓存层稳定运行。
 | 原文链接：http://wiki.z26bb9.asia/arts/405173.Doc

原标题：golang 系统设计定时任务调度时间校准要点
简介：项目构建脚本编译打包解析，解读项目构建脚本，理清编译、压缩、资源复制流程，理解打包后产物如何生成。
 | 原文链接：http://wiki.z26bb9.asia/arts/418331.Doc

原标题：golang 系统设计技术方案评审关注点清单参考
简介：前端 pdf 预览渲染方案对比，对比前端 PDF 预览库，分析性能、兼容性，给出业务选型参考。
 | 原文链接：http://wiki.z26bb9.asia/arts/733412.Doc

原标题：golang 系统设计定时任务分片执行分布式思路
简介：前端 pdf 预览渲染方案对比，对比前端 PDF 预览库，分析性能、兼容性，给出业务选型参考。
 | 原文链接：http://wiki.z26bb9.asia/arts/488296.Doc

原标题：Performance：数据库索引优化常见错误案例
简介：golang clickhouse go 客户端数据写入，clickhouse‑go 客户端写入查询，海量时序数据分析业务。
 | 原文链接：http://wiki.z26bb9.asia/arts/860959.Doc

原标题：实战：搭建日志收集分析简易完整演示环境
简介：golang testing.TB Helper 标记辅助函数，t.Helper 标记辅助函数，报错打印真实调用位置。
 | 原文链接：http://wiki.z26bb9.asia/arts/730787.Doc

原标题：golang 系统设计内部服务熔断降级配置思路
简介：Mock 接口服务快速搭建实操，搭建模拟后端接口，自定义返回数据、延迟响应，前端开发阶段无需依赖真实后端服务。
 | 原文链接：http://wiki.z26bb9.asia/arts/487844.Doc

原标题：性能复盘：消息队列大量小消息性能问题优化
简介：golang io.LimitReader 限制读取字节数，LimitReader 限制最大读取，防止读取超大数据。
 | 原文链接：http://wiki.z26bb9.asia/arts/334188.Doc

原标题：ORM 隐式慢查询问题规避
简介：golang tcp_NODELAY 关闭延迟发送，设置 tcp_NODELAY，关闭 Nagle 算法，降低小包请求延迟。
 | 原文链接：http://wiki.z26bb9.asia/arts/974961.Doc

三、实战开发｜Practice
原标题：SDK 版本兼容线上崩溃修复
简介：golang go 程序 CPU 占用高定位步骤，pprof 定位热点函数，分析 CPU 高占用，优化耗时代码逻辑。
 | 原文链接：http://wiki.z26bb9.asia/arts/510165.Doc

原标题：安全复盘：环境变量密钥泄露风险与防护
简介：golang grpc keepalive 保活配置，grpc keepalive 参数调优，检测断开僵死连接，释放无效连接资源。
 | 原文链接：http://wiki.z26bb9.asia/arts/950348.Doc

原标题：入门实战：搭建简易静态网页项目
简介：golang jwt 鉴权中间件完整示例，Gin JWT 鉴权中间件，令牌校验，解析用户信息，接口鉴权拦截。
 | 原文链接：http://wiki.z26bb9.asia/arts/717783.Doc

原标题：golang 静态编译缩小镜像体积
简介：CLI 工具进度条交互效果开发，在命令行工具增加进度条展示，直观反馈任务执行进度，优化命令行体验。
 | 原文链接：http://wiki.z26bb9.asia/arts/377444.Doc

原标题：golang docker 多阶段构建 go 镜像
简介：golang gitlab ci go 项目流水线编写，gitlab ci 流水线执行单元测试、静态检查、构建推送镜像。
 | 原文链接：http://wiki.z26bb9.asia/arts/752380.Doc

原标题：开发记录：表单文件类型校验后端安全校验实践
简介：golang go sum 校验失败处理方案，go sum 校验不匹配，排查网络代理，清理缓存解决校验报错。
 | 原文链接：http://wiki.z26bb9.asia/arts/180146.Doc

原标题：nodejs 单元测试 jest 实操教程
简介：golang go 自定义错误类型实现，自定义 error 结构体，携带错误码、堆栈信息，统一业务错误。
 | 原文链接：http://wiki.z26bb9.asia/arts/508897.Doc

原标题：排错：HTTPS证书过期导致接口调用失败
简介：golang select 随机分支执行特性，多个 channel 就绪 select 随机选择，理解 select 行为特性。
 | 原文链接：http://wiki.z26bb9.asia/arts/895668.Doc

原标题：实战项目：数据导出Excel百万级大数据导出方案
简介：golang 换行符统一处理，文本文件读写统一换行符，规避不同系统换行符带来解析异常。
 | 原文链接：http://wiki.z26bb9.asia/arts/738726.Doc

原标题：避坑：版本升级之后项目直接无法启动
简介：前后端会话登录状态持久化，实现登录状态持久存储，重启服务登录状态不丢失，保障会话稳定性。
 | 原文链接：http://wiki.z26bb9.asia/arts/205436.Doc

原标题：从零搭建本地开发环境完整教程
简介：golang html 模板渲染简单示例，Go HTML 模板渲染，服务端渲染页面，填充数据输出 HTML 页面。
 | 原文链接：http://wiki.z26bb9.asia/arts/678789.Doc

原标题：golang 系统设计代码评审关注点 checklist 清单
简介：golang go‑zero rpc 微服务开发，go‑zero 定义 proto，生成 rpc 服务代码，实现微服务调用。
 | 原文链接：http://wiki.z26bb9.asia/arts/773691.Doc

原标题：golang 系统设计架构图绘制规范简单建议
简介：前端下载导出文件功能实现，前端实现文件流下载导出，处理异常，适配浏览器不同下载行为。
 | 原文链接：http://wiki.z26bb9.asia/arts/748011.Doc

原标题：记一次分布式锁失效引发的数据错乱问题
简介：golang runtime.Gosched 主动让出调度，长计算循环主动 Gosched，让出调度权，防止其他协程饥饿。
 | 原文链接：http://wiki.z26bb9.asia/arts/351470.Doc

原标题：开发记录：服务优雅关闭释放资源完整实现
简介：文件监控服务自动重启开发，监控项目文件变更，代码修改自动重启服务，提升本地开发调试效率。
 | 原文链接：http://wiki.z26bb9.asia/arts/864280.Doc

原标题：运维笔记：服务器故障排查常用命令清单
简介：限流规则误拦截正常请求修复，修正限流规则阈值，避免合法用户被限流拦截，兼顾防护与可用性。
 | 原文链接：http://wiki.z26bb9.asia/arts/168276.Doc

原标题：golang mysql 主从同步延迟兼容
简介：golang cgo 性能开销避坑指南，cgo 调用开销，减少频繁 cgo 调用，规避 cgo 带来内存泄漏风险。
 | 原文链接：http://wiki.z26bb9.asia/arts/276947.Doc

原标题：浏览器内存泄漏排查前端页面
简介：golang go 程序版本号内置编译注入，编译时注入 git commit 版本号，程序运行输出版本便于排查。
 | 原文链接：http://wiki.z26bb9.asia/arts/808551.Doc

原标题：golang 系统设计多级缓存架构落地
简介：内网测试服务搭建团队调试，配置本地服务内网可访问，团队成员能够访问调试，方便前后端联调与内部演示。
 | 原文链接：http://wiki.z26bb9.asia/arts/626269.Doc

原标题：golang elasticsearch 索引设计思路
简介：golang go 初始化顺序包变量 init 函数，包级变量初始化，init 执行顺序，理解包加载执行流程。
 | 原文链接：http://wiki.z26bb9.asia/arts/896605.Doc

原标题：排错：DockerCompose依赖顺序启动顺序坑
简介：golang bytes.Buffer 字节缓冲区使用，bytes.Buffer 字节内存缓冲区，拼接字节，避免频繁内存分配。
 | 原文链接：http://wiki.z26bb9.asia/arts/800236.Doc

原标题：前端防抖节流高频事件处理
简介：golang 命令行参数解析开发，解析命令行入参，开发自定义 CLI 程序，读取启动参数配置服务。
 | 原文链接：http://wiki.z26bb9.asia/arts/909319.Doc

原标题：Docker 多阶段构建镜像瘦身
简介：读懂开源项目 README 实用技巧，教你快速解析开源项目说明文档，提取安装、运行、配置关键信息，快速上手项目。
 | 原文链接：http://wiki.z26bb9.asia/arts/933921.Doc

原标题：golang 系统设计 git 钩子自动化校验实现
简介：Cookie Session 会话状态管理，讲解 Cookie 与 Session 原理，理解登录状态保存，实现服务端会话管理逻辑。
 | 原文链接：http://wiki.z26bb9.asia/arts/144299.Doc

原标题：golang 系统设计埋点数据上报方案
简介：golang 子进程执行命令标准流处理，exec.Command 执行外部命令，处理 stdout stderr，防止缓冲区阻塞卡死。
 | 原文链接：http://wiki.z26bb9.asia/arts/805435.Doc

原标题：记一次字符集编码不一致乱码问题全排查
简介：静态站点自动部署发布方案，配置流水线，代码更新自动构建静态站点并且部署上线，简化发布。
 | 原文链接：http://wiki.z26bb9.asia/arts/304526.Doc

原标题：golang 系统设计消息堆积排查扩容完整步骤
简介：golang sftp 文件上传下载操作，sftp 协议远程文件上传下载，实现服务器之间文件传输功能。
 | 原文链接：http://wiki.z26bb9.asia/arts/062273.Doc

原标题：方案对比：同步事务vs事务消息最终一致性
简介：nodejs 定时任务生产环境避坑，Node 定时任务线上踩坑汇总，集群重复执行、任务阻塞等问题解决方案。
 | 原文链接：http://wiki.z26bb9.asia/arts/360687.Doc

原标题：golang 系统设计开源项目贡献指南 contributing
简介：golang go mod why 查询依赖引入原因，go mod why 查询为什么引入某个包，理清依赖来源。
 | 原文链接：http://wiki.z26bb9.asia/arts/976407.Doc

原标题：golang 系统设计分库分表中间件思路
简介：本地数据库开发环境搭建指南，讲解数据库安装配置、账号权限设置、连接测试，快速搭建用于开发调试的数据库实例。
 | 原文链接：http://wiki.z26bb9.asia/arts/751952.Doc

原标题：golang k8s service 服务暴露几种类型
简介：后端登录鉴权模块完整开发，实现完整登录模块，包含账号校验、令牌发放、接口鉴权整套能力。
 | 原文链接：http://wiki.z26bb9.asia/arts/393476.Doc

原标题：golang 系统设计线上问题复现思路简单讲解
简介：golang 负载均衡轮询加权轮询实现，手写负载均衡算法，轮询、加权轮询分发请求到后端节点。
 | 原文链接：http://wiki.z26bb9.asia/arts/071118.Doc

原标题：时间精度统一业务判断修复
简介：axios 二次封装请求拦截处理，对 axios 做二次封装，统一请求拦截响应拦截，处理错误、token 自动刷新。
 | 原文链接：http://wiki.z26bb9.asia/arts/461504.Doc

原标题：开发记录：业务错误告警邮件通知组件实践
简介：golang redis list 队列简易消息队列，利用 Redis List 实现简易队列，完成任务入队消费基础能力。
 | 原文链接：http://wiki.z26bb9.asia/arts/089627.Doc

原标题：性能复盘：接口响应从800ms优化到50ms全过程
简介：golang 集成测试测试数据库回滚，集成测试结束自动回滚数据库，不污染测试环境数据。
 | 原文链接：http://wiki.z26bb9.asia/arts/508051.Doc

原标题：golang 系统设计监控缺失指标补全完整流程
简介：golang base64 大文件流式编解码，大文件流式 base64 转换，不用一次性加载全部文件进入内存。
 | 原文链接：http://wiki.z26bb9.asia/arts/635398.Doc

原标题：快速入门YAML配置文件语法与示例
简介：golang go 代码覆盖率线上统计，单元测试覆盖率统计，找出未测试代码分支，提升测试质量。
 | 原文链接：http://wiki.z26bb9.asia/arts/318948.Doc

原标题：Architecture：文件处理服务架构大文件内存规避
简介：golang gin 框架接口开发实战，Gin 框架搭建 HTTP 服务，开发增删改查接口，快速完成后端接口开发。
 | 原文链接：http://wiki.z26bb9.asia/arts/744545.Doc

原标题：实战项目：实现分布式任务调度最小原型
简介：开发生产环境资源路径统一，对齐开发环境与生产环境资源路径，防止本地正常上线后资源找不到。
 | 原文链接：http://wiki.z26bb9.asia/arts/432621.Doc

原标题：golang 系统设计故障演练简单思路
简介：git rebase 整理提交历史实操，使用 rebase 整理杂乱提交记录，将多条提交合并，保持 git 提交历史干净线性。
 | 原文链接：http://wiki.z26bb9.asia/arts/602223.Doc

四、架构设计｜Architecture
原标题：开发记录：敏感数据加密存储解密业务实践
简介：golang go 版本管理 go install 安装工具，go install 安装指定版本 go 工具，管理本地 go 工具版本。
 | 原文链接：http://wiki.z26bb9.asia/arts/103877.Doc

原标题：安全笔记：GitHubAction密钥安全管理
简介：golang context.WithValue 传递元数据，WithValue 只传 traceId 鉴权元数据，不要传业务大对象。
 | 原文链接：http://wiki.z26bb9.asia/arts/731640.Doc

原标题：异步任务堆积消费能力优化
简介：golang 半关闭 tcp 连接 shutdown，tcp 连接 shutdown 半关闭，单向关闭读或者写，理解 tcp 关闭流程。
 | 原文链接：http://wiki.z26bb9.asia/arts/096828.Doc

原标题：性能笔记：DNS缓存优化减少域名解析开销
简介：golang kitex 字节微服务框架入门，kitex 开发 rpc 微服务，代码生成，服务注册发现完整流程。
 | 原文链接：http://wiki.z26bb9.asia/arts/177407.Doc

原标题：golang 系统设计分布式锁超时业务防死锁处理
简介：golang go mod graph 可视化依赖图，可视化 go 依赖关系，直观看到包之间依赖，定位冲突。
 | 原文链接：http://wiki.z26bb9.asia/arts/237529.Doc

原标题：Architecture：日志、监控、告警整套可观测架构
简介：golang go 服务蓝绿发布实践思路，蓝绿两套实例，流量一键切换，回滚快速降低发布风险。
 | 原文链接：http://wiki.z26bb9.asia/arts/573034.Doc

原标题：golang 系统设计测试环境预发环境生产环境隔离
简介：golang grpc 客户端流上传数据，客户端流式请求，客户端分批上传数据到服务端，适合大文件传输。
 | 原文链接：http://wiki.z26bb9.asia/arts/113758.Doc

原标题：css 变量主题切换方案实现
简介：golang panic 崩溃日志完整收集，捕获所有 panic，打印堆栈，记录日志，方便定位崩溃根源。
 | 原文链接：http://wiki.z26bb9.asia/arts/597385.Doc

原标题：golang 系统设计压测指标 qps rt 错误率讲解
简介：golang time 时间格式化参考时间牢记，2006‑01‑02T15:04:05Z07:00，掌握 go 时间格式化关键点。
 | 原文链接：http://wiki.z26bb9.asia/arts/435225.Doc

原标题：golang mongodb 索引优化查询速度
简介：golang go 项目 CI github actions 配置，github actions 实现 go 项目 ci，自动测试、代码检查、编译打包镜像。
 | 原文链接：http://wiki.z26bb9.asia/arts/244555.Doc

原标题：golang 系统设计 monorepo 仓库管理方案
简介：网关超时时间调优后端等待，调大网关向后端转发请求超时时间，给后端业务充足处理时间。
 | 原文链接：http://wiki.z26bb9.asia/arts/540439.Doc

原标题：调试工具断点调试变量查看技巧
简介：CI 流水线构建失败日志排查，阅读 CI 流水线输出日志，定位构建脚本、依赖、环境导致流水线失败问题。
 | 原文链接：http://wiki.z26bb9.asia/arts/263573.Doc

原标题：DevOps：Docker镜像优化，减小镜像体积实践
简介：前端图片懒加载性能优化，实现图片懒加载，页面可视区域才加载图片，减少页面初始网络请求。
 | 原文链接：http://wiki.z26bb9.asia/arts/341281.Doc

原标题：golang 参数校验业务接口处理
简介：golang excel 大文件读取流式解析，流式读取大 excel 文件，逐行解析数据，不加载全部内容进内存。
 | 原文链接：http://wiki.z26bb9.asia/arts/056096.Doc

原标题：golang 系统设计网关灰度流量切分简单方案
简介：golang grpc 拦截器开发鉴权日志，开发 grpc 服务端拦截器，统一做鉴权、日志打印、异常捕获处理。
 | 原文链接：http://wiki.z26bb9.asia/arts/421420.Doc

原标题：golang 系统设计 protobuf oneof 类型业务场景
简介：golang nacos go 客户端配置服务发现，nacos‑go 对接 nacos，配置管理、微服务注册发现。
 | 原文链接：http://wiki.z26bb9.asia/arts/285378.Doc

原标题：对象存储上传下载权限实操
简介：Nginx 缓冲区调优大文件上传，调大 Nginx 请求缓冲区，支持客户端上传大体积文件，避免上传被截断。
 | 原文链接：http://wiki.z26bb9.asia/arts/001046.Doc

原标题：golang 系统设计技术文档维护更新最佳实践
简介：golang go 运行时获取编译信息，程序内部读取编译时间 git 版本，接口输出程序版本信息。
 | 原文链接：http://wiki.z26bb9.asia/arts/196552.Doc

?
