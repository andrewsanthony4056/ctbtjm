最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang 系统设计数据库扩容几种方式
简介：接口请求重试容错机制实现，封装请求重试逻辑，遇到临时网络故障自动重试，提升第三方调用稳定性。
 | 原文链接：http://book.2stzcr.asia/blog/674123.Doc

原标题：设计思考：分布式系统时钟同步带来的架构问题
简介：跨域偶现失败配置修复，解决跨域问题时而复现时而正常，定位配置漏配、请求头异常等隐性问题。
 | 原文链接：http://book.2stzcr.asia/blog/606339.Doc

原标题：golang 系统设计联合索引设计避坑要点
简介：golang defer 闭包变量捕获坑，defer 捕获循环变量引用，变量被复写，理解闭包变量捕获规则。
 | 原文链接：http://book.2stzcr.asia/blog/979594.Doc

原标题：批量异步处理系统业务落地
简介：golang 云存储 s3 协议对象存储，go s3 客户端，兼容 minio 阿里云 oss，实现文件上传下载签名访问。
 | 原文链接：http://book.2stzcr.asia/blog/946365.Doc

原标题：数据库 utf8mb4 支持 emoji 存储
简介：golang cgo 内存管理 C 与 Go 内存，区分 Go 内存 C 堆内存，防止 cgo 内存泄漏，正确释放 C 内存。
 | 原文链接：http://book.2stzcr.asia/blog/344593.Doc

原标题：设计思考：业务埋点架构日志埋点设计原则
简介：golang 本地消息表实现最终一致性，本地消息表 + 定时任务轮询，可靠消息实现分布式事务。
 | 原文链接：http://book.2stzcr.asia/blog/906686.Doc

原标题：golang 系统设计消息大小限制业务处理方案
简介：golang go‑zero 配置中心热更新，go‑zero 对接 etcd 配置中心，配置热更新无需重启服务。
 | 原文链接：http://book.2stzcr.asia/blog/614543.Doc

原标题：实战：Redis过期回调实现业务事件通知实践
简介：golang proto 可选字段处理方案，protobuf 可选字段正确判断，区分未赋值与零值，业务逻辑不出现偏差。
 | 原文链接：http://book.2stzcr.asia/blog/898047.Doc

原标题：坑点：Docker资源限制未设置导致宿主机卡死
简介：golang proto 可选字段处理方案，protobuf 可选字段正确判断，区分未赋值与零值，业务逻辑不出现偏差。
 | 原文链接：http://book.2stzcr.asia/blog/849760.Doc

原标题：golang 系统设计 protobuf json 性能对比
简介：golang json omitempty 零值坑，omitempty 会忽略零值，区分业务是否需要输出零值字段。
 | 原文链接：http://book.2stzcr.asia/blog/929694.Doc

原标题：安全笔记：GitHubAction密钥安全管理
简介：golang 工具函数库封装思路，Go 通用工具库封装思路，错误处理、类型转换，业务项目复用工具代码。
 | 原文链接：http://book.2stzcr.asia/blog/499035.Doc

原标题：golang 系统设计开源项目贡献指南 contributing
简介：极简 API 网关路由转发实现，开发极简网关服务，完成请求路由转发，理解网关基础实现原理。
 | 原文链接：http://book.2stzcr.asia/blog/497701.Doc

原标题：方案对比：定时任务框架选型与架构对比
简介：golang gin 中间件执行顺序讲解，理解 Gin 中间件注册顺序，区分前置后置逻辑，规避中间件顺序 bug。
 | 原文链接：http://book.2stzcr.asia/blog/869213.Doc

原标题：复盘总结：技术选型对比文档模板实践
简介：golang 高并发下锁优化减少竞争，减小锁粒度，读写锁替换互斥锁，无锁编程降低锁竞争开销。
 | 原文链接：http://book.2stzcr.asia/blog/125950.Doc

原标题：批量操作分批处理防止 OOM
简介：golang go mod tidy 依赖清理，go mod tidy 自动增删依赖，整理 go.mod go.sum 文件。
 | 原文链接：http://book.2stzcr.asia/blog/408212.Doc

原标题：分布式 ID 生成器高并发实现
简介：golang rate 令牌桶限流器源码理解，拆解令牌桶限流核心逻辑，理解令牌生成消耗，掌握限流底层原理。
 | 原文链接：http://book.2stzcr.asia/blog/602279.Doc

原标题：golang 系统设计一致性哈希原理讲解
简介：前端图片懒加载性能优化，实现图片懒加载，页面可视区域才加载图片，减少页面初始网络请求。
 | 原文链接：http://book.2stzcr.asia/blog/465915.Doc

原标题：Architecture：对象存储接入业务整体架构
简介：nestjs 全局返回格式统一处理，Nest 全局拦截器统一包装接口返回数据，对外输出标准化响应格式。
 | 原文链接：http://book.2stzcr.asia/blog/152968.Doc

原标题：golang jwt 鉴权中间件完整示例
简介：nodejs 全局异常捕获进程防护，捕获未捕获异常与 Promise 拒绝，尽量保护进程不因为异常直接退出。
 | 原文链接：http://book.2stzcr.asia/blog/014446.Doc

原标题：TCP 心跳检测清理僵死连接
简介：golang http 服务优雅关闭完整示例，接收终止信号，停止接收新请求，等待现有请求处理完毕后退出服务。
 | 原文链接：http://book.2stzcr.asia/blog/503618.Doc

原标题：调优方案：前端静态资源打包性能体积优化
简介：多环境配置中心灵活切换方案，简易配置中心实现，支持多套环境配置，动态下发无需重启服务。
 | 原文链接：http://book.2stzcr.asia/blog/647475.Doc

原标题：Debug：消息队列死信队列堆积无人处理业务阻塞
简介：golang context 上下文传参讲解，讲解 Context 使用场景，传递元数据、控制协程超时取消，规范协程控制。
 | 原文链接：http://book.2stzcr.asia/blog/387494.Doc

原标题：网络读取超时设置连接挂起防护
简介：golang sync.RWMutex 读写锁使用场景，读多写少场景读写锁，读共享写互斥，提升并发性能。
 | 原文链接：http://book.2stzcr.asia/blog/120105.Doc

原标题：新手教程：本地环境变量配置全流程
简介：golang arp 缓存读取操作，读取系统 arp 缓存表，获取 ip 对应的 mac 地址信息。
 | 原文链接：http://book.2stzcr.asia/blog/179572.Doc

原标题：Troubleshooting：Redis大key引发集群卡顿
简介：缓存穿透防护保护数据库，实现缓存穿透防护手段，拦截不存在的数据查询，避免请求直接打穿数据库。
 | 原文链接：http://book.2stzcr.asia/blog/821861.Doc

原标题：入门实践：简易进度条CLI工具实现demo
简介：数据库 utf8mb4 支持 emoji 存储，数据库字段设置 utf8mb4 字符集，完整支持 emoji 表情存储入库。
 | 原文链接：http://book.2stzcr.asia/blog/561986.Doc

原标题：golang 系统设计日志与 traceId 关联打印实现
简介：golang go 依赖漏洞检测 govulncheck，govulncheck 扫描依赖安全漏洞，发现项目供应链风险。
 | 原文链接：http://book.2stzcr.asia/blog/853838.Doc

原标题：快速上手简易网关转发逻辑模拟
简介：API 大版本不兼容平滑迁移，API 版本迭代不兼容旧接口，设计平滑迁移方案，逐步完成版本切换。
 | 原文链接：http://book.2stzcr.asia/blog/714107.Doc

原标题：golang 数据库批量更新性能优化
简介：业务错误码体系设计方案，设计项目统一错误码，区分不同业务异常，标准化错误返回，便于前端识别处理。
 | 原文链接：http://book.2stzcr.asia/blog/076732.Doc

原标题：golang k8s 日志收集 efk 简单架构
简介：golang sftp 文件上传下载操作，sftp 协议远程文件上传下载，实现服务器之间文件传输功能。
 | 原文链接：http://book.2stzcr.asia/blog/459057.Doc

原标题：坑点：Git工作区换行符CRLF/LF跨平台坑
简介：golang udp 服务端客户端开发示例，golang 实现 UDP 服务收发数据包，实现 udp 协议通信程序。
 | 原文链接：http://book.2stzcr.asia/blog/683290.Doc

原标题：Issue：Docker网络模式选择错误容器互通失败
简介：golang go 爬虫请求速率控制，爬虫限频、代理轮换，设置 UA，防止爬虫被目标站点封禁 IP。
 | 原文链接：http://book.2stzcr.asia/blog/155708.Doc

原标题：Nginx 丢失请求头配置修正
简介：OpenAPI 自动接口文档生成，集成 OpenAPI 工具，自动扫描代码生成接口文档，减少文档维护成本。
 | 原文链接：http://book.2stzcr.asia/blog/185361.Doc

原标题：实战项目：WSL开发环境完整配置实操
简介：golang clickhouse go 客户端数据写入，clickhouse‑go 客户端写入查询，海量时序数据分析业务。
 | 原文链接：http://book.2stzcr.asia/blog/551005.Doc

原标题：golang 系统设计开源项目贡献指南 contributing
简介：数值 key 浮点匹配异常规避，避免浮点数作为 Redis 等存储的 key，防止精度问题引发 key 匹配失败。
 | 原文链接：http://book.2stzcr.asia/blog/349854.Doc

原标题：前端 pdf 预览渲染方案对比
简介：golang grpc 客户端流上传数据，客户端流式请求，客户端分批上传数据到服务端，适合大文件传输。
 | 原文链接：http://book.2stzcr.asia/blog/348331.Doc

原标题：react 状态管理方案选型对比
简介：golang go 模板执行错误捕获，捕获模板执行错误，防止模板错误直接返回空白页面。
 | 原文链接：http://book.2stzcr.asia/blog/193676.Doc

原标题：运维笔记：服务器故障排查常用命令清单
简介：golang redis stream 消息队列实战，redis stream 实现可靠消息队列，消费组、ack 确认，消息不丢失。
 | 原文链接：http://book.2stzcr.asia/blog/866157.Doc

原标题：缓存穿透击穿雪崩全套防护
简介：golang bufio.Scanner 缓冲区调大，Scanner 默认缓冲区大小不够，读取超长行需要扩大缓冲区。
 | 原文链接：http://book.2stzcr.asia/blog/387110.Doc

原标题：golang http client 连接池调优
简介：golang go 并发模式 errgroup 使用，errgroup 结合 context，协程组，任意协程出错整体取消任务。
 | 原文链接：http://book.2stzcr.asia/blog/053367.Doc


二、踩坑排错｜Troubleshooting
原标题：实践：数据库回滚点业务调试实践
简介：从零编写简易 CLI 命令行工具，通过实战案例实现基础命令交互，理解命令行程序执行逻辑，产出可运行小工具。
 | 原文链接：http://book.2stzcr.asia/blog/155271.Doc

原标题：golang 系统设计故障预案编写模板参考示例
简介：golang 配置热更新不重启服务，实现配置热加载，监听配置变更，更新内存配置，无需重启服务实例。
 | 原文链接：http://book.2stzcr.asia/blog/088576.Doc

原标题：提交第一个开源 PR 完整流程
简介：文件分片上传断点续传功能，实现文件分片上传，记录上传进度，支持断点续传大文件上传。
 | 原文链接：http://book.2stzcr.asia/blog/310901.Doc

原标题：CI/CD 流水线自动构建部署落地
简介：golang bufio.Scanner 缓冲区调大，Scanner 默认缓冲区大小不够，读取超长行需要扩大缓冲区。
 | 原文链接：http://book.2stzcr.asia/blog/483786.Doc

原标题：从零搭建本地数据库开发环境
简介：golang httptest 模拟外部 http 服务，httptest.NewServer 模拟第三方 http 服务，单元测试 mock 外部接口。
 | 原文链接：http://book.2stzcr.asia/blog/297714.Doc

原标题：Redis 大 key 拆分集群卡顿解决
简介：golang https 客户端跳过证书校验，开发测试环境跳过 tls 证书校验，仅用于内网测试禁止生产使用。
 | 原文链接：http://book.2stzcr.asia/blog/179308.Doc

原标题：Issue：本地可以访问，容器内部网络不通
简介：golang go mod exclude 排除依赖版本，exclude 排除有问题依赖版本，规避有 bug 的第三方包。
 | 原文链接：http://book.2stzcr.asia/blog/265309.Doc

原标题：慢查询分析索引调优数据库实战
简介：golang cpu pprof 性能分析实操，使用 pprof 采集 CPU 性能数据，定位 CPU 高占用函数，做性能优化。
 | 原文链接：http://book.2stzcr.asia/blog/736058.Doc

原标题：nodejs jwt 登录鉴权完整示例
简介：golang embed 目录读取文件列表，embed 嵌入整个目录，读取目录下全部文件，做静态资源服务。
 | 原文链接：http://book.2stzcr.asia/blog/880511.Doc

原标题：实践：实现Redis分布式锁完整可运行代码
简介：golang go test 单元测试命令参数详解，gotest 参数覆盖率，指定测试用例，跳过测试，单元测试命令实操。
 | 原文链接：http://book.2stzcr.asia/blog/125622.Doc

原标题：golang 系统设计数据库基准压测简单思路
简介：Docker 容器网络不通排查，排查容器网络模式、端口映射、防火墙，解决容器之间、容器外部网络不通。
 | 原文链接：http://book.2stzcr.asia/blog/491015.Doc

原标题：项目脚手架模板生成工具
简介：golang json omitempty 零值坑，omitempty 会忽略零值，区分业务是否需要输出零值字段。
 | 原文链接：http://book.2stzcr.asia/blog/360188.Doc

原标题：架构复盘：慢查询治理架构层面优化手段
简介：golang strings.Builder 字符串高效拼接，strings.Builder 做字符串拼接，比 += 性能更高，减少内存拷贝。
 | 原文链接：http://book.2stzcr.asia/blog/317079.Doc

原标题：Practice：实现数据库连接池简易模拟实现
简介：golang raw socket 底层网络报文收发，raw socket 收发原始网络报文，做网络抓包数据包处理。
 | 原文链接：http://book.2stzcr.asia/blog/614884.Doc

原标题：入门实战：搭建简易静态网页项目
简介：golang 消息死信处理业务逻辑，Go 实现死信队列逻辑，消费失败消息转入死信，不阻塞正常消息队列。
 | 原文链接：http://book.2stzcr.asia/blog/073661.Doc

原标题：架构复盘：多实例部署业务状态无状态改造
简介：本地数据库开发环境搭建指南，讲解数据库安装配置、账号权限设置、连接测试，快速搭建用于开发调试的数据库实例。
 | 原文链接：http://book.2stzcr.asia/blog/684297.Doc

原标题：开源实践：Fork上游项目，持续同步更新代码
简介：golang gin 静态资源访问配置，Gin 配置静态资源目录，直接对外提供静态文件访问服务。
 | 原文链接：http://book.2stzcr.asia/blog/677294.Doc

原标题：磁盘占满服务不可用清理方案
简介：golang 限流器熔断降级组合使用，限流熔断降级组合架构，流量防护完整方案，保障服务稳定性。
 | 原文链接：http://book.2stzcr.asia/blog/769260.Doc

原标题：Debug：Websocket频繁断开重连根因分析
简介：gRPC 服务端客户端入门示例，搭建 gRPC 服务端与调用客户端，学习 protobuf 定义，掌握 RPC 基础开发流程。
 | 原文链接：http://book.2stzcr.asia/blog/293547.Doc

原标题：开发复盘：长轮询接口实现服务端消息推送
简介：golang go 测试文件命名规范，_test.go 测试文件，TestXxx 单元测试函数命名规范。
 | 原文链接：http://book.2stzcr.asia/blog/603694.Doc

原标题：Hands‑on：shell脚本批量自动化运维小工具
简介：开发代理服务网络限制解决，搭建本地代理服务，解决开发环境网络访问受限，实现外部接口正常调用。
 | 原文链接：http://book.2stzcr.asia/blog/076331.Doc

原标题：golang 系统设计网关灰度流量切分简单方案
简介：nodejs http 服务性能调优实战，调优 Node HTTP 服务内核参数，连接复用，提升接口并发处理能力。
 | 原文链接：http://book.2stzcr.asia/blog/303648.Doc

原标题：Debug：并发场景下数据覆盖丢失问题定位
简介：golang makefile 多平台编译脚本，makefile 一键交叉编译多平台二进制，打包镜像，执行测试。
 | 原文链接：http://book.2stzcr.asia/blog/206112.Doc

原标题：实战：搭建本地对象存储兼容S3协议demo
简介：golang go mod graph 可视化依赖图，可视化 go 依赖关系，直观看到包之间依赖，定位冲突。
 | 原文链接：http://book.2stzcr.asia/blog/785590.Doc

原标题：复盘总结：技术选型对比文档模板实践
简介：上传接口跨域配置特殊适配，针对文件上传接口，适配复杂请求，修复上传场景下跨域失效问题。
 | 原文链接：http://book.2stzcr.asia/blog/794598.Doc

原标题：踩坑记录：UTC时间与本地时间混用逻辑错乱
简介：服务健康检查监控接口开发，开发健康检查接口，反馈服务运行状态，供编排工具监控服务存活状态。
 | 原文链接：http://book.2stzcr.asia/blog/715140.Doc

原标题：性能笔记：服务CPU高负载定位分析完整步骤
简介：golang systemd 信号与优雅退出配合，systemd 停止服务发送 SIGTERM，go 程序捕获信号优雅关闭。
 | 原文链接：http://book.2stzcr.asia/blog/595790.Doc

原标题：golang 系统设计监控告警阈值设置思路
简介：golang 数据库分表策略按时间分片，按时间维度分表，历史数据拆分，单表数据量控制保证查询性能。
 | 原文链接：http://book.2stzcr.asia/blog/125540.Doc

原标题：实战项目：搭建本地Mock服务快速开发联调
简介：golang http 重定向策略自定义，CheckRedirect 自定义重定向逻辑，限制重定向次数，防止死循环。
 | 原文链接：http://book.2stzcr.asia/blog/418900.Doc

原标题：性能笔记：磁盘IO过高业务优化手段
简介：多线程线程安全脏数据规避，梳理多线程共享变量，做好同步控制，避免并发修改产生脏数据。
 | 原文链接：http://book.2stzcr.asia/blog/195109.Doc

原标题：golang k8s ingress 路由域名转发
简介：无用对象回收抑制内存上涨，优化对象生命周期，及时释放不再使用对象，抑制内存持续不断增长。
 | 原文链接：http://book.2stzcr.asia/blog/151516.Doc

原标题：开发复盘：大数据量分页避免offset性能问题
简介：golang goreleaser 自动版本发布打包，goreleaser 自动化打包发布，生成多平台二进制归档文件。
 | 原文链接：http://book.2stzcr.asia/blog/751974.Doc

原标题：运维笔记：服务器定时任务运维脚本编写
简介：消息队列生产消费模型入门，讲解消息队列生产、存储、消费流程，理解异步解耦、削峰，掌握消息队列基础概念。
 | 原文链接：http://book.2stzcr.asia/blog/536655.Doc

原标题：golang 消息队列 kafka 消费开发
简介：golang go 模块迁移从 GOPATH 到 GoMod，老项目从 GOPATH 迁移 go mod，解决依赖管理混乱问题。
 | 原文链接：http://book.2stzcr.asia/blog/126329.Doc

原标题：前端骨架屏提升页面体验
简介：golang 分布式锁 redis 实现，基于 Redis 实现 Go 分布式锁，解决多实例并发竞争资源问题。
 | 原文链接：http://book.2stzcr.asia/blog/866655.Doc

原标题：golang redis 缓存雪崩完整处理
简介：Git 标签版本标记发布管理，使用 Git 标签标记项目版本，打标签推送远程，用于版本发布、版本回溯。
 | 原文链接：http://book.2stzcr.asia/blog/557828.Doc

原标题：异步编程 Promise 执行流程解析
简介：golang go 错误包装 fmt.Errorf % w，使用 % w 包装错误，支持 errors.Is errors.As 判断错误类型。
 | 原文链接：http://book.2stzcr.asia/blog/072306.Doc

原标题：Troubleshoot：MySQL字符集utf8非utf8mb4emoji报错
简介：golang 负载均衡轮询加权轮询实现，手写负载均衡算法，轮询、加权轮询分发请求到后端节点。
 | 原文链接：http://book.2stzcr.asia/blog/865206.Doc

原标题：golang 系统设计定时任务分布式锁
简介：分布式 ID 生成器高并发实现，实现高性能分布式 ID 生成器，适配高并发业务，生成全局唯一 ID。
 | 原文链接：http://book.2stzcr.asia/blog/581570.Doc

原标题：golang 系统设计分布式锁不同场景选型对比
简介：golang os.Exit 退出程序注意 defer 不执行，os.Exit 会直接退出，不会执行 defer，优雅退出不要直接 os.Exit。
 | 原文链接：http://book.2stzcr.asia/blog/522837.Doc

三、实战开发｜Practice
原标题：RPC 接口字段增减兼容处理
简介：golang 半关闭 tcp 连接 shutdown，tcp 连接 shutdown 半关闭，单向关闭读或者写，理解 tcp 关闭流程。
 | 原文链接：http://book.2stzcr.asia/blog/133030.Doc

原标题：部署复盘：金丝雀发布流量切分实操方案
简介：golang proto 可选字段处理方案，protobuf 可选字段正确判断，区分未赋值与零值，业务逻辑不出现偏差。
 | 原文链接：http://book.2stzcr.asia/blog/498954.Doc

原标题：Hands‑on：简易配置热更新组件开发实践
简介：golang 消息队列 kafka 消费开发，Go 开发 Kafka 消费程序，消费消息执行业务，理解 Kafka 消费逻辑。
 | 原文链接：http://book.2stzcr.asia/blog/276458.Doc

原标题：开源实践：开源Issue沟通技巧如何有效提Bug
简介：golang context.WithTimeout 超时上下文，WithTimeout 设置超时时间，超时自动 cancel 释放协程。
 | 原文链接：http://book.2stzcr.asia/blog/333144.Doc

原标题：Troubleshooting：数据库索引失效，查询性能暴跌
简介：批量操作分批处理防止 OOM，大批量数据处理不一次性加载全部数据，分批循环处理，避免内存溢出。
 | 原文链接：http://book.2stzcr.asia/blog/507862.Doc

原标题：部署实践：内网开发环境代理配置实践
简介：golang go 服务日志输出 journald，systemd journald 接收程序 stdout 日志，统一管理服务日志。
 | 原文链接：http://book.2stzcr.asia/blog/131846.Doc

原标题：golang 单元测试 mock http 请求
简介：golang dns 自定义解析器实现，自定义 dns 解析，指定 dns 服务器，控制域名解析逻辑，适配内网环境。
 | 原文链接：http://book.2stzcr.asia/blog/260460.Doc

原标题：模拟登录鉴权权限判断示例
简介：golang rsa 公钥加密私钥解密，rsa 非对称加密，大文件分块加密，处理非对称加密长度限制。
 | 原文链接：http://book.2stzcr.asia/blog/903872.Doc

原标题：HelloGitWorkflow：理解简单主干开发流程
简介：缓存穿透防护保护数据库，实现缓存穿透防护手段，拦截不存在的数据查询，避免请求直接打穿数据库。
 | 原文链接：http://book.2stzcr.asia/blog/598431.Doc

原标题：入门实践：简单数据脱敏处理示例
简介：异步异常捕获避免进程崩溃，捕获异步代码内部抛出异常，防止未捕获异常直接导致整个进程退出。
 | 原文链接：http://book.2stzcr.asia/blog/595275.Doc

原标题：golang 系统设计限流服务架构讲解
简介：golang panic 崩溃日志完整收集，捕获所有 panic，打印堆栈，记录日志，方便定位崩溃根源。
 | 原文链接：http://book.2stzcr.asia/blog/855602.Doc

原标题：服务熔断防止故障级联传播
简介：浏览器内存泄漏排查前端页面，梳理前端页面内存泄漏场景，讲解排查手段，修复页面内存持续上涨。
 | 原文链接：http://book.2stzcr.asia/blog/863978.Doc

原标题：golang 系统设计故障演练简单思路
简介：golang redis geo 地理位置存储查询，Redis GEO 存储经纬度，查询附近点位，实现附近人业务功能。
 | 原文链接：http://book.2stzcr.asia/blog/314776.Doc

原标题：OpenSource：开源项目版本发布CHANGELOG编写
简介：Docker 容器时区错误修复方案，修复 Docker 容器内部时区偏差，解决容器内时间不对引发业务逻辑异常。
 | 原文链接：http://book.2stzcr.asia/blog/277203.Doc

原标题：安全笔记：JWT安全风险，签名泄露过期控制
简介：golang os.Exit 退出程序注意 defer 不执行，os.Exit 会直接退出，不会执行 defer，优雅退出不要直接 os.Exit。
 | 原文链接：http://book.2stzcr.asia/blog/195616.Doc

原标题：实战项目：Nginx限速、限流、防爬虫配置实践
简介：golang os 主机名内核版本读取，os 读取主机名，内核信息，操作系统版本，获取运行环境信息。
 | 原文链接：http://book.2stzcr.asia/blog/052350.Doc

原标题：异步任务堆积消费能力优化
简介：前端图片懒加载性能优化，实现图片懒加载，页面可视区域才加载图片，减少页面初始网络请求。
 | 原文链接：http://book.2stzcr.asia/blog/782983.Doc

原标题：Shell 脚本自动化命令编写
简介：GitHub 项目提交推送完整流程讲解，从仓库初始化到提交推送远程仓库，梳理全流程细节，避开新手高频错误。
 | 原文链接：http://book.2stzcr.asia/blog/417101.Doc

原标题：调优方案：JVM内存参数优化，降低GC频率
简介：Git 子模块更新代码不全修复，正确更新 Git 子模块，拉取子模块完整代码，解决子模块目录为空问题。
 | 原文链接：http://book.2stzcr.asia/blog/151762.Doc

原标题：golang 系统设计第三方接口 mock 单元测试
简介：数值类型溢出错乱问题修复，选择合适数值存储类型，处理数值溢出，避免数据存储错乱结果异常。
 | 原文链接：http://book.2stzcr.asia/blog/051453.Doc

原标题：架构笔记：分布式系统常见一致性模型梳理
简介：golang panic 崩溃日志完整收集，捕获所有 panic，打印堆栈，记录日志，方便定位崩溃根源。
 | 原文链接：http://book.2stzcr.asia/blog/259970.Doc

原标题：Architecture：大文件上传下载系统架构设计
简介：golang time 定时器重置 Reset 正确用法，Timer Reset 调用前提，避免 Reset 带来逻辑错误。
 | 原文链接：http://book.2stzcr.asia/blog/151570.Doc

原标题：golang 系统设计分布式会话方案对比
简介：golang go time 时区数据库内置，go 内置时区数据库，不用系统时区文件，容器时区不依赖系统。
 | 原文链接：http://book.2stzcr.asia/blog/908685.Doc

原标题：golang 系统设计缓存 key 命名规范最佳实践
简介：golang fasthttp 客户端连接池调优，fasthttp 客户端连接池配置，复用连接提升请求性能。
 | 原文链接：http://book.2stzcr.asia/blog/496465.Doc

原标题：实战项目：数据导出Excel百万级大数据导出方案
简介：前端错误监控上报系统搭建，搭建前端错误监控，捕获页面 JS 错误，上报后端，快速发现线上页面 bug。
 | 原文链接：http://book.2stzcr.asia/blog/756144.Doc

原标题：坑点：依赖包内部携带恶意代码供应链风险
简介：git cherry‑pick 规范操作防 bug，规范 cherry‑pick 使用流程，处理冲突，避免错误引入不兼容代码。
 | 原文链接：http://book.2stzcr.asia/blog/752448.Doc

原标题：坑点：gitrebase操作失误，代码提交丢失
简介：golang jwt jwk 公钥验证令牌，使用 jwk 公钥校验 jwt，非对称方式签发校验令牌，提升安全性。
 | 原文链接：http://book.2stzcr.asia/blog/159465.Doc

原标题：golang kafka 生产者参数调优
简介：golang nats jetstream 持久消息队列，nats jetstream 持久化消息，保证消息不丢失，实现可靠消费。
 | 原文链接：http://book.2stzcr.asia/blog/789224.Doc

原标题：开源实践：Fork上游项目，持续同步更新代码
简介：golang goroutine 池任务调度，实现 goroutine 池，复用协程，频繁任务场景减少协程创建销毁开销。
 | 原文链接：http://book.2stzcr.asia/blog/349997.Doc

原标题：部署复盘：配置不要硬编码进镜像最佳实践
简介：系统字符集统一乱码修复，统一数据库、程序、操作系统字符集，解决中文乱码显示异常问题。
 | 原文链接：http://book.2stzcr.asia/blog/557211.Doc

原标题：golang 系统设计 hot‑reload 热重载 go 开发工具
简介：golang snowflake 时钟回拨解决方案，雪花算法处理时钟回拨，防止生成重复 ID，保证 ID 全局唯一。
 | 原文链接：http://book.2stzcr.asia/blog/486636.Doc

原标题：开发复盘：实现定时任务调度服务支持动态任务
简介：golang http 文件下载断点续传服务，服务端实现断点续传，支持大文件分段下载，提升大文件下载稳定性。
 | 原文链接：http://book.2stzcr.asia/blog/662773.Doc

原标题：CI/CD 流水线自动构建部署落地
简介：golang toml 配置文件解析教程，Go 解析 Toml 格式配置，适用于项目配置管理场景。
 | 原文链接：http://book.2stzcr.asia/blog/585988.Doc

原标题：golang redis hyperloglog 基数统计
简介：开发生产环境资源路径统一，对齐开发环境与生产环境资源路径，防止本地正常上线后资源找不到。
 | 原文链接：http://book.2stzcr.asia/blog/733366.Doc

原标题：运维笔记：线上服务健康检查脚本编写
简介：golang bufio 缓冲读写性能优化，bufio 带缓冲读写，减少系统调用，提升文件网络 IO 性能。
 | 原文链接：http://book.2stzcr.asia/blog/229551.Doc

原标题：SourceMap 生成线上报错定位
简介：内存泄漏定位分析完整流程，分享内存泄漏排查步骤，定位没有释放的对象，解决内存持续上涨问题。
 | 原文链接：http://book.2stzcr.asia/blog/037966.Doc

原标题：入门实践：简易导出导入文件功能实现
简介：golang go 自定义错误类型实现，自定义 error 结构体，携带错误码、堆栈信息，统一业务错误。
 | 原文链接：http://book.2stzcr.asia/blog/378555.Doc

原标题：新手避坑：第一次提交GitHub项目完整流程
简介：golang cgo 内存管理 C 与 Go 内存，区分 Go 内存 C 堆内存，防止 cgo 内存泄漏，正确释放 C 内存。
 | 原文链接：http://book.2stzcr.asia/blog/564935.Doc

原标题：golang 系统设计回调异步处理防止超时阻塞
简介：正则表达式优化 CPU 占满问题，优化正则表达式写法，避免回溯，防止正则运算 CPU 占用 100%。
 | 原文链接：http://book.2stzcr.asia/blog/059988.Doc

原标题：定时任务重复执行分布式锁
简介：golang cpu pprof 性能分析实操，使用 pprof 采集 CPU 性能数据，定位 CPU 高占用函数，做性能优化。
 | 原文链接：http://book.2stzcr.asia/blog/741184.Doc

四、架构设计｜Architecture
原标题：golang 日志与链路 ID 关联打印
简介：golang 日志按日期切割实现方案，实现日志文件按天切割，自动归档旧日志，防止单个日志文件过大。
 | 原文链接：http://book.2stzcr.asia/blog/720691.Doc

原标题：操作系统内核版本适配服务
简介：golang go‑zero 分布式锁组件使用，go‑zero 内置 redis 分布式锁，业务直接调用实现并发控制。
 | 原文链接：http://book.2stzcr.asia/blog/599305.Doc

原标题：nodejs 跨域中间件配置细节
简介：容器软链接文件权限修复，修复容器内软链接文件权限，让程序能够正常读取软链接指向的文件。
 | 原文链接：http://book.2stzcr.asia/blog/629263.Doc

原标题：内存广播本地进程消息通知
简介：golang go1.18 + 泛型基础实操，go 泛型基础语法，泛型函数泛型类型，实现通用工具函数。
 | 原文链接：http://book.2stzcr.asia/blog/112444.Doc

原标题：特殊输入字符过滤解析防护
简介：golang gorm 索引设置与优化技巧，定义数据库索引，理解索引生效条件，避免索引失效慢查询。
 | 原文链接：http://book.2stzcr.asia/blog/645641.Doc

原标题：DevOps：WSL2生产环境使用风险提示
简介：golang wasm 性能优化与内存管理，wasm 内存分配释放，减少内存拷贝，优化浏览器端性能。
 | 原文链接：http://book.2stzcr.asia/blog/088075.Doc

原标题：golang k8s job 一次性任务执行
简介：Git 分支切换合并删除完整操作，实操分支全生命周期操作，包含切换、合并、删除，熟悉日常开发分支处理流程。
 | 原文链接：http://book.2stzcr.asia/blog/080977.Doc

原标题：golang 布隆过滤器实现去重
简介：golang 静态编译缩小镜像体积，Go 程序静态编译，不依赖系统库，产出单二进制文件，缩小镜像。
 | 原文链接：http://book.2stzcr.asia/blog/371758.Doc

原标题：实践：OpenAPI自动生成接口文档完整实践
简介：Git commit 钩子提交规范校验，配置 Git 提交钩子，提交代码自动校验提交信息格式，规范提交记录。
 | 原文链接：http://book.2stzcr.asia/blog/012958.Doc

原标题：开发复盘：百万数据批量导入数据库优化方案
简介：golang sync.Pool 对象池复用对象，sync.Pool 复用临时对象，减少内存分配，降低 GC 频率提升性能。
 | 原文链接：http://book.2stzcr.asia/blog/645322.Doc

原标题：golang 系统设计故障预案编写模板参考示例
简介：golang go 初始化顺序包变量 init 函数，包级变量初始化，init 执行顺序，理解包加载执行流程。
 | 原文链接：http://book.2stzcr.asia/blog/564784.Doc

原标题：golang 系统设计定时任务调度时间校准要点
简介：golang mysql 长连接检测保活设置，配置 mysql 连接保活检测，剔除失效连接，避免拿到断开无效数据库连接。
 | 原文链接：http://book.2stzcr.asia/blog/756571.Doc

原标题：新手指南：虚拟机WSL开发环境入门配置
简介：Git 混乱提交历史清理方法，针对杂乱的提交记录，使用 Git 工具整理，清理无效提交，还原整洁版本历史。
 | 原文链接：http://book.2stzcr.asia/blog/531348.Doc

原标题：方案对比：轮询长轮询WebSocket推送架构选型
简介：golang excel 简单读写操作示例，Go 实现 Excel 简单读写，业务数据导出 Excel 报表。
 | 原文链接：http://book.2stzcr.asia/blog/442699.Doc

原标题：golang redis bitmap 位图统计实现
简介：golang go 运行时获取编译信息，程序内部读取编译时间 git 版本，接口输出程序版本信息。
 | 原文链接：http://book.2stzcr.asia/blog/295581.Doc

原标题：HelloCI：理解持续集成基础工作流程
简介：Docker 网络模式容器互通设置，选择合适 Docker 网络模式，实现容器之间网络互相访问通信。
 | 原文链接：http://book.2stzcr.asia/blog/459588.Doc

原标题：OpenSource：开源项目版本发布CHANGELOG编写
简介：golang mysql 事务回滚异常处理，Go MySQL 事务异常捕获，正确回滚事务，保证异常场景数据回滚。
 | 原文链接：http://book.2stzcr.asia/blog/455026.Doc

原标题：架构笔记：分库分表中间件选型业务约束
简介：golang gif 图片帧处理操作，解析 gif 图片帧，压缩、拆分 gif 动图，处理动图业务。
 | 原文链接：http://book.2stzcr.asia/blog/640999.Doc

?
