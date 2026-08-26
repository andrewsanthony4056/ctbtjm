最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang 系统设计故障复盘模板 postmortem 参考
简介：golang httptest 模拟 http 请求单元测试，httptest 模拟 http 请求，测试 http handler 逻辑不用启动服务。
 | 原文链接：http://book.h9039l.asia/blog/293795.Doc

原标题：文件锁正确使用避免死锁
简介：golang 大文件 HTTP 流式上传接收，服务端流式接收上传文件，不全部加载内存，防止大文件 OOM 崩溃。
 | 原文链接：http://book.h9039l.asia/blog/308948.Doc

原标题：前端水印防信息泄露实现
简介：golang go 模块迁移从 GOPATH 到 GoMod，老项目从 GOPATH 迁移 go mod，解决依赖管理混乱问题。
 | 原文链接：http://book.h9039l.asia/blog/489599.Doc

原标题：golang 系统设计埋点数据上报方案
简介：golang go url url.Values 参数编码，url.Values 构建 url 查询参数，自动处理参数 url 编码。
 | 原文链接：http://book.h9039l.asia/blog/483544.Doc

原标题：HelloEnv：多操作系统环境变量配置汇总
简介：Nginx 缓冲区调优大文件上传，调大 Nginx 请求缓冲区，支持客户端上传大体积文件，避免上传被截断。
 | 原文链接：http://book.h9039l.asia/blog/414410.Doc

原标题：安全复盘：OAuth2授权流程安全坑点汇总
简介：golang go 程序权限最小化运行，容器内使用普通用户运行程序，拒绝 root 运行提升安全等级。
 | 原文链接：http://book.h9039l.asia/blog/991683.Doc

原标题：架构笔记：分库分表中间件选型业务约束
简介：golang redis geo 地理位置存储查询，Redis GEO 存储经纬度，查询附近点位，实现附近人业务功能。
 | 原文链接：http://book.h9039l.asia/blog/349184.Doc

原标题：golang 系统设计重试退避策略业务落地
简介：golang go 错误包装 fmt.Errorf % w，使用 % w 包装错误，支持 errors.Is errors.As 判断错误类型。
 | 原文链接：http://book.h9039l.asia/blog/565581.Doc

原标题：避坑：文件锁处理不当多进程竞争死锁
简介：接口限流逻辑简单模拟实现，编写简易限流逻辑，限制接口访问频次，保护服务，避免短时间大量请求压垮系统。
 | 原文链接：http://book.h9039l.asia/blog/970918.Doc

原标题：优化实践：接口返回字段裁剪减少报文大小
简介：golang mongodb 索引优化慢查询处理，mongodb 创建索引，分析慢查询，优化聚合查询执行性能。
 | 原文链接：http://book.h9039l.asia/blog/008369.Doc

原标题：效率笔记：调试网络请求curl命令高级用法
简介：gRPC 服务端客户端入门示例，搭建 gRPC 服务端与调用客户端，学习 protobuf 定义，掌握 RPC 基础开发流程。
 | 原文链接：http://book.h9039l.asia/blog/196403.Doc

原标题：Hands‑on：简易代理服务器开发实践
简介：TLS 版本兼容 HTTPS 握手失败，兼容老旧 TLS 协议版本，修复部分客户端 HTTPS 握手失败无法访问。
 | 原文链接：http://book.h9039l.asia/blog/762119.Doc

原标题：运维笔记：磁盘inode耗尽故障排查处理
简介：开源项目构建失败排查步骤，梳理构建报错排查流程，从依赖、网络、权限、脚本多角度定位项目构建失败原因。
 | 原文链接：http://book.h9039l.asia/blog/648416.Doc

原标题：优化实践：读写分离分担主库查询压力
简介：Redis 内存淘汰策略数据防丢失，合理配置 Redis 内存淘汰策略，防止内存满后误删除业务重要数据。
 | 原文链接：http://book.h9039l.asia/blog/601739.Doc

原标题：Architecture：BFF后端聚合层架构适用场景
简介：空指针异常判空容错处理，讲解空指针产生场景，规范判空逻辑，增加容错，避免空指针直接造成程序崩溃。
 | 原文链接：http://book.h9039l.asia/blog/061126.Doc

原标题：Practice：实现业务id生成不连续有序ID方案
简介：golang 分布式唯一 id 多种方案对比，雪花、redis、uuid 对比各方案优缺点，指导业务选型使用。
 | 原文链接：http://book.h9039l.asia/blog/342142.Doc

原标题：Architecture：API设计RESTful最佳实践与反模式
简介：nodejs jwt 登录鉴权完整示例，Node 实现 JWT 登录鉴权，登录签发令牌，接口校验令牌身份。
 | 原文链接：http://book.h9039l.asia/blog/350296.Doc

原标题：WebSocket 断线重连稳定优化
简介：GC 垃圾回收优化降低 CPU 占用，调整 GC 参数，优化对象创建销毁，降低垃圾回收带来 CPU 开销。
 | 原文链接：http://book.h9039l.asia/blog/568739.Doc

原标题：golang 系统设计告警风暴抑制方案实现
简介：golang go time 时区数据库内置，go 内置时区数据库，不用系统时区文件，容器时区不依赖系统。
 | 原文链接：http://book.h9039l.asia/blog/750251.Doc

原标题：golang 系统设计大文件上传架构
简介：golang os 进程 pid 获取父进程 pid，os.Getpid 获取进程 id，获取父进程 pid，进程间识别。
 | 原文链接：http://book.h9039l.asia/blog/825766.Doc

原标题：项目实践：实现数据脱敏组件支持多种脱敏规则
简介：golang jwt 令牌刷新逻辑实现，实现 JWT 双令牌机制，access 短期有效 refresh 刷新令牌，实现无感续期登录。
 | 原文链接：http://book.h9039l.asia/blog/832733.Doc

原标题：golang 系统设计接口返回格式统一规范
简介：golang 容器内读取 k8s 配置 configmap，程序读取 k8s configmap 配置，配置与镜像分离便于运维。
 | 原文链接：http://book.h9039l.asia/blog/597954.Doc

原标题：golang goroutine 协程基础实操
简介：SourceMap 生成线上报错定位，项目打包生成 SourceMap 文件，线上报错可以还原源码，快速定位报错位置。
 | 原文链接：http://book.h9039l.asia/blog/583808.Doc

原标题：CDN 缓存刷新获取最新静态资源
简介：golang tcp 四次挥手 go 程序行为，理解 tcp 四次挥手，处理连接关闭、重置、RST 包异常场景。
 | 原文链接：http://book.h9039l.asia/blog/047335.Doc

原标题：项目构建脚本编译打包解析
简介：分布式任务调度集群原型开发，开发简易分布式调度原型，集群多节点运行，保证任务只执行一次。
 | 原文链接：http://book.h9039l.asia/blog/793778.Doc

原标题：排坑：Git提交历史混乱，如何清理错误提交
简介：开源源码阅读拆解学习思路，分享阅读大型开源项目方法，从入口文件逐层拆解模块，降低源码学习门槛。
 | 原文链接：http://book.h9039l.asia/blog/015344.Doc

原标题：HelloMarkdown：GitHubMarkdown完整语法速查
简介：golang 微服务网关简易实现，http 反向代理、路由匹配、鉴权限流，理解网关核心原理。
 | 原文链接：http://book.h9039l.asia/blog/901069.Doc

原标题：golang ci 流水线代码质量扫描集成
简介：golang multipart 表单文件上传解析，服务端解析 multipart 表单，获取上传文件与表单字段。
 | 原文链接：http://book.h9039l.asia/blog/144265.Doc

原标题：实践：Git工作流主干开发团队协作实践
简介：nodejs redis 缓存业务实战，Node 对接 Redis 实现业务缓存，缓存热点查询结果，减轻数据库压力。
 | 原文链接：http://book.h9039l.asia/blog/867537.Doc

原标题：安全复盘：环境变量密钥泄露风险与防护
简介：golang go 服务蓝绿发布实践思路，蓝绿两套实例，流量一键切换，回滚快速降低发布风险。
 | 原文链接：http://book.h9039l.asia/blog/252994.Doc

原标题：设计思考：分布式会话架构选型对比
简介：正则表达式优化 CPU 占满问题，优化正则表达式写法，避免回溯，防止正则运算 CPU 占用 100%。
 | 原文链接：http://book.h9039l.asia/blog/124136.Doc

原标题：TCP 心跳检测清理僵死连接
简介：golang 命令行交互 cobra 开发 cli，cobra 库开发功能完善命令行工具，子命令参数标志解析。
 | 原文链接：http://book.h9039l.asia/blog/294314.Doc

原标题：实战：单元测试+集成测试完整项目落地实践
简介：golang defer panic 异常处理，理解 defer 延迟执行，panic 恐慌捕获，实现函数资源释放异常保护。
 | 原文链接：http://book.h9039l.asia/blog/856136.Doc

原标题：golang 系统设计消息消费 offset 管理策略
简介：golang 钉钉企业微信告警消息推送，go 调用企业微信钉钉接口，推送告警通知、业务消息。
 | 原文链接：http://book.h9039l.asia/blog/772088.Doc

原标题：部署实践：HTTPS证书自动续期配置实践
简介：golang go 爬虫异步并发抓取，协程池控制并发抓取网页，多协程采集，提升爬虫采集速度。
 | 原文链接：http://book.h9039l.asia/blog/011073.Doc

原标题：golang kafka 重试机制配置实操
简介：日志输出规范防止磁盘爆满，控制日志输出量，配置日志切割轮转，避免日志文件无限增长占满磁盘。
 | 原文链接：http://book.h9039l.asia/blog/957443.Doc

原标题：golang 系统设计内部服务链路 trace 传递实现
简介：K8s 镜像拉取网络故障修复，排查 K8s 集群镜像拉取网络问题，配置镜像源，恢复镜像正常拉取。
 | 原文链接：http://book.h9039l.asia/blog/677736.Doc

原标题：SourceMap 生成线上报错定位
简介：golang redis 事务 multi exec 使用，Redis 事务 multi exec 实现批量命令原子执行，理解 redis 事务隔离特性。
 | 原文链接：http://book.h9039l.asia/blog/807133.Doc

原标题：无用对象回收抑制内存上涨
简介：golang 错误栈捕获打印方案，捕获错误完整调用堆栈，线上日志输出堆栈，快速定位错误发生代码位置。
 | 原文链接：http://book.h9039l.asia/blog/173366.Doc

原标题：golang 系统设计集成测试数据库回滚重置方案
简介：golang init 函数合理使用边界，少用 init，优先显式调用初始化，便于控制初始化时机。
 | 原文链接：http://book.h9039l.asia/blog/131866.Doc


二、踩坑排错｜Troubleshooting
原标题：文件编码统一随机乱码修复
简介：Shell 运维脚本服务器效率提升，编写常用运维 Shell 脚本，自动化服务器运维操作，减少手工重复工作。
 | 原文链接：http://book.h9039l.asia/blog/775646.Doc

原标题：调试工具断点调试变量查看技巧
简介：golang 读写分离 gorm 实现主从切换，gorm 配置主库写入从库查询，读写分离分担数据库查询压力。
 | 原文链接：http://book.h9039l.asia/blog/301879.Doc

原标题：开发复盘：内存缓存LRU淘汰策略实现实践
简介：golang 灰度发布流量权重路由实现，根据权重切分流量，部分流量访问新版本服务，实现灰度发布。
 | 原文链接：http://book.h9039l.asia/blog/851160.Doc

原标题：golang 系统设计异步化改造业务流程思路
简介：golang 任务失败重试与死信队列，异步任务失败自动重试，超过重试次数进入死信队列人工处理。
 | 原文链接：http://book.h9039l.asia/blog/962511.Doc

原标题：AI实践：大模型生成测试用例实践与校验
简介：多套环境灵活切换配置方案，实现配置动态切换，通过环境变量、配置文件，快速切换开发测试生产环境。
 | 原文链接：http://book.h9039l.asia/blog/829878.Doc

原标题：开发记录：业务错误告警邮件通知组件实践
简介：golang word 文档生成处理 go 方案，go 生成 word 文档报表，填充文本表格，输出 docx 文件。
 | 原文链接：http://book.h9039l.asia/blog/445467.Doc

原标题：golang 系统设计 README 开源文档模板
简介：golang rabbitmq go 客户端生产消费，streadway/amqp 实现 rabbitmq 生产者消费者，队列交换机绑定。
 | 原文链接：http://book.h9039l.asia/blog/566957.Doc

原标题：Troubleshooting：防火墙安全组拦截访问请求
简介：端口占用释放资源重启服务，查找占用端口进程，结束占用进程，释放端口，让服务能够正常启动监听。
 | 原文链接：http://book.h9039l.asia/blog/022100.Doc

原标题：Hands‑on：简易网关路由转发组件开发
简介：golang 结构体 json 序列化坑点，梳理 Go 结构体 JSON 序列化高频坑点，字段大小写、零值处理问题。
 | 原文链接：http://book.h9039l.asia/blog/429107.Doc

原标题：Debug：消息队列死信队列堆积无人处理业务阻塞
简介：Nginx 静态代理负载均衡全套配置，一套 Nginx 配置示例，覆盖静态资源、反向代理、负载均衡场景。
 | 原文链接：http://book.h9039l.asia/blog/360092.Doc

原标题：开发记录：接口请求日志记录完整中间件实现
简介：golang go‑zero rpc 微服务开发，go‑zero 定义 proto，生成 rpc 服务代码，实现微服务调用。
 | 原文链接：http://book.h9039l.asia/blog/978984.Doc

原标题：golang 系统设计 go benchmark 性能测试实操
简介：golang 雪花 id 重复问题排查，排查雪花算法 ID 重复问题，时钟回拨、机器 ID 冲突，给出修复方案。
 | 原文链接：http://book.h9039l.asia/blog/059536.Doc

原标题：设计思考：分布式ID系统架构选型对比
简介：golang 分布式事务 seata go 客户端，seata‑go 实现分布式事务，保证跨库业务数据最终一致性。
 | 原文链接：http://book.h9039l.asia/blog/108036.Doc

原标题：实践：代码提交前自动格式化校验配置实践
简介：golang aes 对称加密解密示例，AES 对称加密解密实现，业务敏感数据加密存储传输。
 | 原文链接：http://book.h9039l.asia/blog/278750.Doc

原标题：golang 系统设计延迟队列业务实现
简介：golang tar gz 压缩解压处理，tar.gz 归档压缩解压，服务端日志备份、文件打包场景使用。
 | 原文链接：http://book.h9039l.asia/blog/120303.Doc

原标题：OpenSource：开源项目README高质量编写指南
简介：golang go toml 配置注释保留，toml 解析保留注释，修改配置后写回保留原有注释。
 | 原文链接：http://book.h9039l.asia/blog/257170.Doc

原标题：golang prometheus 指标暴露实现
简介：golang 跨平台系统差异处理方案，处理 windows linux mac 路径、信号、文件权限差异，代码跨平台兼容。
 | 原文链接：http://book.h9039l.asia/blog/078852.Doc

原标题：新手指南：如何读懂开源项目报错日志
简介：golang go 并发模式 errgroup 使用，errgroup 结合 context，协程组，任意协程出错整体取消任务。
 | 原文链接：http://book.h9039l.asia/blog/720555.Doc

原标题：golang 系统设计埋点数据上报方案
简介：接口签名校验防篡改实现，实现请求签名验签逻辑，校验请求参数未被篡改，提升接口调用安全性。
 | 原文链接：http://book.h9039l.asia/blog/117638.Doc

原标题：golang rate‑limiter 限流组件
简介：golang rsa 非对称加密签名验签，RSA 非对称加密与签名验签，实现非对称安全通信。
 | 原文链接：http://book.h9039l.asia/blog/452235.Doc

原标题：开发记录：批量接口请求并发控制实践
简介：包管理器依赖缓存清理，清理本地依赖缓存，解决缓存旧包引发问题，拉取最新版本依赖包。
 | 原文链接：http://book.h9039l.asia/blog/852682.Doc

原标题：golang docker 部署 kafka 本地调试
简介：golang sftp 文件上传下载操作，sftp 协议远程文件上传下载，实现服务器之间文件传输功能。
 | 原文链接：http://book.h9039l.asia/blog/891571.Doc

原标题：Hands‑on：手写简易ORM框架理解底层原理
简介：TCP 心跳检测清理僵死连接，开启 TCP 心跳机制，自动清理僵死无效连接，释放连接资源。
 | 原文链接：http://book.h9039l.asia/blog/224462.Doc

原标题：实战项目：百万日志文件解析处理脚本实践
简介：开发生产环境资源路径统一，对齐开发环境与生产环境资源路径，防止本地正常上线后资源找不到。
 | 原文链接：http://book.h9039l.asia/blog/453351.Doc

原标题：golang 系统设计代码评审 checklist 清单
简介：静态站点自动部署发布方案，配置流水线，代码更新自动构建静态站点并且部署上线，简化发布。
 | 原文链接：http://book.h9039l.asia/blog/872693.Doc

原标题：golang mysql 避免 select * 查询
简介：golang goroutine 泄露检测告警实现，监控 goroutine 数量，突增触发告警，提早发现协程泄露。
 | 原文链接：http://book.h9039l.asia/blog/208228.Doc

原标题：Security：文件路径穿越漏洞完整防护
简介：golang redis pipeline 批量操作，使用 Redis Pipeline 批量执行多条命令，减少网络往返，提升批量操作性能。
 | 原文链接：http://book.h9039l.asia/blog/042699.Doc

原标题：Performance：数据库join优化，大表join规避
简介：前端错误监控上报系统搭建，搭建前端错误监控，捕获页面 JS 错误，上报后端，快速发现线上页面 bug。
 | 原文链接：http://book.h9039l.asia/blog/161684.Doc

原标题：golang kafka 同步异步消费对比
简介：golang redis hyperloglog 基数统计，hyperloglog 统计 UV 基数，海量数据去重统计，极低内存开销。
 | 原文链接：http://book.h9039l.asia/blog/936354.Doc

原标题：HelloTest：理解集成测试基础编写思路
简介：Redis 分布式锁高并发安全实现，基于 Redis 实现分布式锁，处理锁过期、续期，保障集群并发安全。
 | 原文链接：http://book.h9039l.asia/blog/625284.Doc

原标题：golang 时间时区处理避坑指南
简介：跨域偶现失败配置修复，解决跨域问题时而复现时而正常，定位配置漏配、请求头异常等隐性问题。
 | 原文链接：http://book.h9039l.asia/blog/357199.Doc

原标题：项目实践：本地模拟缓存失效风暴验证防护
简介：WSL 搭建 Windows Linux 开发环境，配置 WSL 环境，在 Windows 系统使用 Linux 工具链，适配 Linux 开发项目。
 | 原文链接：http://book.h9039l.asia/blog/616300.Doc

原标题：Practice：实现文件监控自动重启开发服务工具
简介：golang gorm 软删除实现逻辑，Gorm 开启软删除，删除数据仅标记，数据保留可恢复，满足业务数据留存。
 | 原文链接：http://book.h9039l.asia/blog/349858.Doc

原标题：golang redis zset 延时队列实现
简介：golang go 泛型约束与类型集合，泛型 type set 约束，限制泛型支持类型，写出安全泛型代码。
 | 原文链接：http://book.h9039l.asia/blog/893307.Doc

原标题：设计思考：分布式ID系统架构选型对比
简介：本地简易配置中心动态管理，搭建轻量本地配置中心，业务动态读取配置，修改配置不重启服务。
 | 原文链接：http://book.h9039l.asia/blog/300553.Doc

原标题：golang redis 缓存预热实现思路
简介：golang validator 自定义校验规则，Gin Validator 自定义校验器，实现业务特殊参数校验逻辑。
 | 原文链接：http://book.h9039l.asia/blog/237239.Doc

原标题：golang 系统设计业务指标系统指标定义思路
简介：golang os.Exit 退出程序注意 defer 不执行，os.Exit 会直接退出，不会执行 defer，优雅退出不要直接 os.Exit。
 | 原文链接：http://book.h9039l.asia/blog/489487.Doc

原标题：部署复盘：配置热更新不用重启服务方案
简介：文件句柄耗尽资源泄露处理，定位文件句柄泄露，修复文件忘记关闭问题，解决句柄耗尽服务报错。
 | 原文链接：http://book.h9039l.asia/blog/923631.Doc

原标题：nodejs 定时任务生产环境避坑
简介：golang ip 限流黑名单实现方案，基于 IP 做限流与黑名单，拦截恶意 IP 访问，保护接口服务。
 | 原文链接：http://book.h9039l.asia/blog/273408.Doc

原标题：部署复盘：静态站点部署CDN完整流程
简介：文件句柄上限调整上传随机失败，调高系统文件句柄上限，解决高并发上传场景随机打开文件失败。
 | 原文链接：http://book.h9039l.asia/blog/147280.Doc

三、实战开发｜Practice
原标题：跨域偶现失败配置修复
简介：golang nats 轻量消息队列 go 开发，nats 高性能轻量消息系统，发布订阅模式异步解耦业务。
 | 原文链接：http://book.h9039l.asia/blog/935723.Doc

原标题：OpenSource：开源项目风险评估依赖安全检查
简介：golang redis pipeline 批量操作，使用 Redis Pipeline 批量执行多条命令，减少网络往返，提升批量操作性能。
 | 原文链接：http://book.h9039l.asia/blog/965613.Doc

原标题：设计实践：如何设计可扩展业务数据库表结构
简介：golang url 参数编码处理方案，Go URL 参数编码解码，处理特殊字符，避免 URL 参数错乱。
 | 原文链接：http://book.h9039l.asia/blog/866929.Doc

原标题：Hands‑on：简易邮件发送服务封装实践
简介：golang cpu pprof 性能分析实操，使用 pprof 采集 CPU 性能数据，定位 CPU 高占用函数，做性能优化。
 | 原文链接：http://book.h9039l.asia/blog/196628.Doc

原标题：项目实践：幂等表实现接口幂等业务实践
简介：特殊输入字符过滤解析防护，过滤用户输入特殊字符，防止解析报错，规避恶意字符带来业务异常。
 | 原文链接：http://book.h9039l.asia/blog/535469.Doc

原标题：golang 系统设计网关限流熔断降级配置思路
简介：手写简易 ORM 理解对象映射，手写极简 ORM 示例，理解对象与数据库表字段映射底层原理。
 | 原文链接：http://book.h9039l.asia/blog/070508.Doc

原标题：项目实践：实现统一接口返回封装与全局异常处理
简介：golang os 进程 pid 获取父进程 pid，os.Getpid 获取进程 id，获取父进程 pid，进程间识别。
 | 原文链接：http://book.h9039l.asia/blog/591526.Doc

原标题：golang toml 配置文件解析教程
简介：golang go 第三方库选型评估要点，评估库活跃度维护情况、性能、依赖数量，选择合适开源库。
 | 原文链接：http://book.h9039l.asia/blog/012818.Doc

原标题：静态博客部署 GitHub Pages 教程
简介：用户敏感数据脱敏代码实现，编写数据脱敏工具，对手机号、身份证做脱敏处理，防止敏感信息直接泄露。
 | 原文链接：http://book.h9039l.asia/blog/431626.Doc

原标题：DevOps：容器健康探针livenessreadiness配置
简介：golang 速率限制令牌桶实现，Go 实现令牌桶限流算法，可复用限流器，控制业务调用速率。
 | 原文链接：http://book.h9039l.asia/blog/971594.Doc

原标题：复盘总结：接口重构兼容旧版本改造复盘
简介：golang raw socket 底层网络报文收发，raw socket 收发原始网络报文，做网络抓包数据包处理。
 | 原文链接：http://book.h9039l.asia/blog/370934.Doc

原标题：SSH 密钥配置 GitHub 免密登录
简介：静态网页 HTML CSS 快速入门实战，通过简单页面案例讲解标签、样式布局，从零编写页面，理解网页基础渲染原理。
 | 原文链接：http://book.h9039l.asia/blog/717070.Doc

原标题：golang kafka 消息顺序性保证方案
简介：axios 二次封装请求拦截处理，对 axios 做二次封装，统一请求拦截响应拦截，处理错误、token 自动刷新。
 | 原文链接：http://book.h9039l.asia/blog/648602.Doc

原标题：golang 系统设计 e2e 端到端测试简单落地思路
简介：golang redis stream 消息队列实战，redis stream 实现可靠消息队列，消费组、ack 确认，消息不丢失。
 | 原文链接：http://book.h9039l.asia/blog/531078.Doc

原标题：golang mysql 读写分离简单实现
简介：消息队列生产消费模型入门，讲解消息队列生产、存储、消费流程，理解异步解耦、削峰，掌握消息队列基础概念。
 | 原文链接：http://book.h9039l.asia/blog/859679.Doc

原标题：部署实践：内网开发环境代理配置实践
简介：golang go 爬虫请求速率控制，爬虫限频、代理轮换，设置 UA，防止爬虫被目标站点封禁 IP。
 | 原文链接：http://book.h9039l.asia/blog/537840.Doc

原标题：golang docker volume 数据持久化
简介：golang jwt 令牌刷新逻辑实现，实现 JWT 双令牌机制，access 短期有效 refresh 刷新令牌，实现无感续期登录。
 | 原文链接：http://book.h9039l.asia/blog/945561.Doc

原标题：golang docker 部署 es 本地开发
简介：service‑worker 离线缓存实践，使用 ServiceWorker 实现静态资源离线缓存，弱网环境页面依然可访问。
 | 原文链接：http://book.h9039l.asia/blog/566440.Doc

原标题：golang 静态编译缩小镜像体积
简介：react hooks 常见陷阱避坑指南，梳理 React Hooks 高频踩坑点，依赖数组、闭包陷阱，写出稳定组件。
 | 原文链接：http://book.h9039l.asia/blog/829735.Doc

原标题：golang 系统设计契约测试接口兼容性保障思路
简介：程序性能指标 CPU 内存监控，讲解基础性能指标含义，简单实现监控采集，初步定位程序运行性能瓶颈。
 | 原文链接：http://book.h9039l.asia/blog/411899.Doc

原标题：golang 系统设计分布式任务调度
简介：vue pinia 状态管理实战教程，Pinia 完整实战示例，实现状态定义修改，模块拆分替代 Vuex。
 | 原文链接：http://book.h9039l.asia/blog/019396.Doc

原标题：Practice：模拟缓存雪崩缓存击穿验证防护策略
简介：服务健康检查监控接口开发，开发健康检查接口，反馈服务运行状态，供编排工具监控服务存活状态。
 | 原文链接：http://book.h9039l.asia/blog/429514.Doc

原标题：golang es 批量 bulk 操作性能调优
简介：golang io.Reader io.Writer 接口理解，io 读写接口，各类数据源统一抽象，适配 io 复制函数。
 | 原文链接：http://book.h9039l.asia/blog/548369.Doc

原标题：实践：API错误统一捕获与告警通知实践
简介：golang go 基准测试 benchmark 编写，Benchmark 性能基准测试，测量函数执行耗时内存分配情况。
 | 原文链接：http://book.h9039l.asia/blog/747639.Doc

原标题：Troubleshoot：批量导入数据，事务过大回滚日志暴涨
简介：golang 命令行彩色输出终端，终端彩色文字输出，进度条交互，优化命令行工具用户体验。
 | 原文链接：http://book.h9039l.asia/blog/972535.Doc

原标题：golang gorm 批量插入性能调优
简介：golang go time 时区数据库内置，go 内置时区数据库，不用系统时区文件，容器时区不依赖系统。
 | 原文链接：http://book.h9039l.asia/blog/670016.Doc

原标题：golang 系统设计异步化改造业务流程思路
简介：golang bufio 缓冲读写性能优化，bufio 带缓冲读写，减少系统调用，提升文件网络 IO 性能。
 | 原文链接：http://book.h9039l.asia/blog/992745.Doc

原标题：新手向：配置项目eslint/prettier代码格式化
简介：开发生产环境资源路径统一，对齐开发环境与生产环境资源路径，防止本地正常上线后资源找不到。
 | 原文链接：http://book.h9039l.asia/blog/156147.Doc

原标题：golang docker 基础命令实操汇总
简介：golang prometheus client 业务埋点实操，prometheus client‑go 业务埋点，计数器、仪表盘、直方图指标开发。
 | 原文链接：http://book.h9039l.asia/blog/971677.Doc

原标题：优化实践：批量操作性能优化，减少数据库IO
简介：系统文件描述符上限调大，调高操作系统文件描述符上限，解决高并发场景打开文件报错。
 | 原文链接：http://book.h9039l.asia/blog/507982.Doc

原标题：golang redis 地理位置 geo 使用
简介：golang pprof 线上采集性能数据，线上环境采集 pprof 性能样本，不用停机，分析线上性能问题。
 | 原文链接：http://book.h9039l.asia/blog/160573.Doc

原标题：golang 系统设计监控大盘故障快速定位思路
简介：golang sort 搜索查找切片元素，sort.Search 二分查找有序切片，快速定位元素索引位置。
 | 原文链接：http://book.h9039l.asia/blog/978252.Doc

原标题：nodejs 脚手架工具开发完整教程
简介：golang redis scan 遍历 key 避免阻塞，使用 scan 迭代遍历 redis 键，不用 keys 命令，防止阻塞 redis 服务。
 | 原文链接：http://book.h9039l.asia/blog/171155.Doc

原标题：日志敏感信息脱敏泄露防护
简介：golang 进程信号捕获 SIGUSR 自定义信号，捕获用户自定义信号，实现线上不重启触发调试、日志切换。
 | 原文链接：http://book.h9039l.asia/blog/796917.Doc

原标题：golang 接口限流中间件开发
简介：编译打包产物依赖分析解读，分析打包之后产物组成，理清运行依赖文件，排查打包后缺失文件问题。
 | 原文链接：http://book.h9039l.asia/blog/323306.Doc

原标题：避坑：Spring事务传播行为理解错误事务失效
简介：hosts 配置本地回环访问修复，修改 hosts 配置，修复 127.0.0.1 解析异常，本地服务访问失败问题。
 | 原文链接：http://book.h9039l.asia/blog/504653.Doc

原标题：快速入门gRPC基础概念与简单示例
简介：分页逻辑错误数据漏查修复，修复分页查询逻辑漏洞，解决分页漏数据、重复返回数据等业务问题。
 | 原文链接：http://book.h9039l.asia/blog/087167.Doc

原标题：golang redis pipeline 原子性说明
简介：golang go 代码覆盖率线上统计，单元测试覆盖率统计，找出未测试代码分支，提升测试质量。
 | 原文链接：http://book.h9039l.asia/blog/018799.Doc

原标题：golang 系统设计配置回滚版本历史记录实现
简介：图片上传预览格式大小处理，实现图片上传接口，校验文件格式、大小，完成上传后预览处理。
 | 原文链接：http://book.h9039l.asia/blog/405362.Doc

原标题：nodejs 消息队列消费服务开发
简介：CLI 工具进度条交互效果开发，在命令行工具增加进度条展示，直观反馈任务执行进度，优化命令行体验。
 | 原文链接：http://book.h9039l.asia/blog/891870.Doc

四、架构设计｜Architecture
原标题：golang 系统设计接口频率限制业务落地
简介：nodejs 信号处理优雅关闭服务，监听系统信号，执行资源清理，实现 Node 服务优雅停机，拒绝粗暴杀死进程。
 | 原文链接：http://book.h9039l.asia/blog/503027.Doc

原标题：golang 系统设计 id 生成器选型对比
简介：开发代理服务网络限制解决，搭建本地代理服务，解决开发环境网络访问受限，实现外部接口正常调用。
 | 原文链接：http://book.h9039l.asia/blog/856395.Doc

原标题：SourceMap 生成线上报错定位
简介：react 状态管理方案选型对比，对比 Redux、Zustand 等 React 状态管理库，分析适用业务场景辅助选型。
 | 原文链接：http://book.h9039l.asia/blog/830805.Doc

原标题：axios 二次封装请求拦截处理
简介：golang go get 升级降级依赖版本，go get 指定版本升级降级依赖包，管理第三方库版本。
 | 原文链接：http://book.h9039l.asia/blog/531517.Doc

原标题：golang redis 网络超时参数调优
简介：golang go xml 解析生成 xml 文档，encoding/xml 解析 xml，结构体标签映射 xml 节点属性。
 | 原文链接：http://book.h9039l.asia/blog/707431.Doc

原标题：golang 系统设计内部服务契约测试简单思路
简介：golang mysql 长连接检测保活设置，配置 mysql 连接保活检测，剔除失效连接，避免拿到断开无效数据库连接。
 | 原文链接：http://book.h9039l.asia/blog/545048.Doc

原标题：Issue：日志输出包含敏感信息造成泄露风险
简介：eslint prettier 代码规范落地，配置 eslint 与 prettier，做代码检查格式化，统一前端团队代码风格。
 | 原文链接：http://book.h9039l.asia/blog/592526.Doc

原标题：效率笔记：Makefile项目构建脚本编写实践
简介：golang go‑zero 中间件鉴权限流，go‑zero 自定义中间件，实现鉴权、限流、日志打印通用能力。
 | 原文链接：http://book.h9039l.asia/blog/830615.Doc

原标题：实践：代码提交前自动格式化校验配置实践
简介：golang 表格驱动测试完整示例，表格驱动多组输入输出，批量执行测试用例，减少重复代码。
 | 原文链接：http://book.h9039l.asia/blog/088286.Doc

原标题：golang mysql 行锁表锁场景区分
简介：golang redis 锁超时业务处理，Redis 分布式锁超时问题处理，锁续期逻辑，防止业务未完成锁提前释放。
 | 原文链接：http://book.h9039l.asia/blog/748143.Doc

原标题：新手向：开源项目fork与同步上游代码
简介：golang go http 服务器优雅关闭完整代码，http.Server Shutdown，等待现有请求处理完成关闭服务。
 | 原文链接：http://book.h9039l.asia/blog/045527.Doc

原标题：Mock 接口服务快速搭建实操
简介：golang sync.RWMutex 读写锁使用场景，读多写少场景读写锁，读共享写互斥，提升并发性能。
 | 原文链接：http://book.h9039l.asia/blog/227057.Doc

原标题：golang 系统设计线上日志快速检索技巧
简介：vue3 组合式 API 业务开发实战，Vue3 组合式 API 业务实战示例，拆分业务逻辑组合复用，提升代码组织。
 | 原文链接：http://book.h9039l.asia/blog/188828.Doc

原标题：Performance：后端接口性能优化完整分析流程
简介：依赖安装失败全方位排错，从网络、镜像源、权限、版本多角度，定位依赖安装失败，给出对应修复手段。
 | 原文链接：http://book.h9039l.asia/blog/888542.Doc

原标题：调优方案：Web服务内核socket参数调优
简介：后端分页查询逻辑代码实现，编写后端分页接口，处理页码、每页条数参数，优化大数据量查询返回结果。
 | 原文链接：http://book.h9039l.asia/blog/431386.Doc

原标题：golang etcd 配置中心简单使用
简介：golang http.Server 配置参数详解，ReadTimeout WriteTimeout IdleTimeout，全方位防护慢请求攻击。
 | 原文链接：http://book.h9039l.asia/blog/071865.Doc

原标题：OpenSource：开源项目贡献者协作流程规范
简介：golang gorm 事务手动回滚提交，手动控制事务流程，业务异常主动回滚，保障数据操作原子性。
 | 原文链接：http://book.h9039l.asia/blog/528334.Doc

原标题：nestjs 拦截器过滤器管道实战
简介：golang 响应 body 流式返回大数据，http 流式输出数据，边生成边返回，无需在内存组装完整返回结果。
 | 原文链接：http://book.h9039l.asia/blog/205842.Doc

?
