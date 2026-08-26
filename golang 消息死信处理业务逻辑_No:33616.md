最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang 消息死信处理业务逻辑
简介：golang 僵尸进程处理 go 程序，正确等待子进程退出，避免产生僵尸进程，占用系统进程表。
 | 原文链接：http://wiki.2bhujh.asia/arts/998153.Doc

原标题：坑点：缓存穿透，大量无效请求打穿数据库
简介：golang tcp 连接泄露排查定位，netstat 查看连接状态，找出未正常关闭连接，定位连接泄漏代码。
 | 原文链接：http://wiki.2bhujh.asia/arts/170552.Doc

原标题：Practice：实现接口签名、验签完整示例代码
简介：接口幂等性防重复请求实现，实现接口幂等逻辑，避免重复提交请求产生多条脏数据，保障业务数据安全。
 | 原文链接：http://wiki.2bhujh.asia/arts/411516.Doc

原标题：golang 系统设计技术文档编写最佳实践
简介：golang 云存储 s3 协议对象存储，go s3 客户端，兼容 minio 阿里云 oss，实现文件上传下载签名访问。
 | 原文链接：http://wiki.2bhujh.asia/arts/739424.Doc

原标题：架构复盘：服务灰度发布架构设计与流量切分
简介：golang 速率限制令牌桶实现，Go 实现令牌桶限流算法，可复用限流器，控制业务调用速率。
 | 原文链接：http://wiki.2bhujh.asia/arts/031150.Doc

原标题：golang 系统设计故障预案编写模板参考示例
简介：开源项目本地运行排错完整清单，汇总开源项目拉取后运行失败各类问题，给出排查思路，快速解决本地启动异常。
 | 原文链接：http://wiki.2bhujh.asia/arts/731901.Doc

原标题：数据库排序规则统一结果一致
简介：webpack chunk 分包策略详解，讲解 webpack chunk 分包策略，拆分第三方包与业务代码，优化缓存复用。
 | 原文链接：http://wiki.2bhujh.asia/arts/827616.Doc

原标题：设计思考：业务系统如何设计优雅失败架构
简介：批量异步处理系统业务落地，构建批量异步处理系统，把耗时业务异步化，提升接口响应速度。
 | 原文链接：http://wiki.2bhujh.asia/arts/625337.Doc

原标题：golang http 请求重试封装工具
简介：golang go 值传递引用传递理解，go 全部为值传递，指针本质拷贝指针值，理清参数传递行为。
 | 原文链接：http://wiki.2bhujh.asia/arts/158432.Doc

原标题：golang 系统设计 gob msgpack 序列化对比
简介：golang http client 连接池调优，调优 Go HTTP Client 连接池参数，复用 TCP 连接，减少连接创建开销。
 | 原文链接：http://wiki.2bhujh.asia/arts/780269.Doc

原标题：性能复盘：磁盘Swap大量使用系统卡顿优化
简介：golang redis pipeline 与 txpipeline 区别，区分普通管道与事务管道，根据业务场景选择合适批量执行方案。
 | 原文链接：http://wiki.2bhujh.asia/arts/557364.Doc

原标题：golang 系统设计消息 key 选择保证顺序性方案
简介：golang 项目 go mod 依赖管理，Go Mod 管理项目依赖，下载、升级、清理依赖，解决依赖版本管理。
 | 原文链接：http://wiki.2bhujh.asia/arts/222473.Doc

原标题：nodejs 流处理大文件不占内存
简介：golang go 爬虫异步并发抓取，协程池控制并发抓取网页，多协程采集，提升爬虫采集速度。
 | 原文链接：http://wiki.2bhujh.asia/arts/228074.Doc

原标题：踩坑：环境变量未生效导致线上配置错乱
简介：分布式 ID 全局唯一生成方案，讲解分布式 ID 生成思路，实现全局唯一 ID，满足分布式系统主键生成需求。
 | 原文链接：http://wiki.2bhujh.asia/arts/927551.Doc

原标题：Nginx 丢失请求头配置修正
简介：golang go 变量逃逸场景汇总，切片、指针、返回局部变量引发逃逸，变量分配到堆影响 GC。
 | 原文链接：http://wiki.2bhujh.asia/arts/511902.Doc

原标题：Hands‑on：搭建OAuth2简易授权服务Demo
简介：golang 子进程超时杀死防止挂住，context 控制子进程超时，超时强制杀掉子进程，避免子进程僵尸。
 | 原文链接：http://wiki.2bhujh.asia/arts/986298.Doc

原标题：移动端适配 rem vw 方案对比
简介：数值 key 浮点匹配异常规避，避免浮点数作为 Redis 等存储的 key，防止精度问题引发 key 匹配失败。
 | 原文链接：http://wiki.2bhujh.asia/arts/447088.Doc

原标题：部署实践：服务器时间同步chrony配置
简介：文件描述符优化进程卡死修复，及时关闭文件句柄，控制打开文件数量，解决文件句柄耗尽进程卡死。
 | 原文链接：http://wiki.2bhujh.asia/arts/635776.Doc

原标题：DevOps：多环境镜像标签版本管理规范
简介：golang go panic 合理使用边界，panic 只用于不可恢复程序错误，业务逻辑禁止直接 panic。
 | 原文链接：http://wiki.2bhujh.asia/arts/818651.Doc

原标题：调优方案：Nginx性能参数调优高并发配置
简介：golang 协程数量监控统计方案，统计运行中 goroutine 数量，监控协程泄露，协程数量异常及时告警。
 | 原文链接：http://wiki.2bhujh.asia/arts/928724.Doc

原标题：golang 优雅停机服务关闭实现
简介：golang lru 缓存淘汰算法编写，手写 LRU 缓存淘汰算法，实现本地缓存，淘汰最久未使用数据。
 | 原文链接：http://wiki.2bhujh.asia/arts/475687.Doc

原标题：性能笔记：数据库表字段设计影响查询性能
简介：golang go 优雅处理信号丢失场景，处理信号丢失、信号被忽略，保障程序可以正常接收终止信号。
 | 原文链接：http://wiki.2bhujh.asia/arts/632854.Doc

原标题：Debug：表单自动转义特殊字符业务逻辑出错
简介：批量操作分批处理防止 OOM，大批量数据处理不一次性加载全部数据，分批循环处理，避免内存溢出。
 | 原文链接：http://wiki.2bhujh.asia/arts/963619.Doc

原标题：实战：对象存储断点续传下载实践
简介：Redis 大 key 拆分集群卡顿解决，拆分 Redis 超大 Key，避免大 key 操作造成 Redis 集群卡顿阻塞。
 | 原文链接：http://wiki.2bhujh.asia/arts/341711.Doc

原标题：调优方案：消息批量消费提升MQ处理吞吐量
简介：gRPC 服务端客户端入门示例，搭建 gRPC 服务端与调用客户端，学习 protobuf 定义，掌握 RPC 基础开发流程。
 | 原文链接：http://wiki.2bhujh.asia/arts/749245.Doc

原标题：golang 系统设计消息队列降级业务开关实现
简介：golang gin 框架接口开发实战，Gin 框架搭建 HTTP 服务，开发增删改查接口，快速完成后端接口开发。
 | 原文链接：http://wiki.2bhujh.asia/arts/217960.Doc

原标题：Hands‑on：实现服务健康检查与自动报警demo
简介：缓存穿透防护保护数据库，实现缓存穿透防护手段，拦截不存在的数据查询，避免请求直接打穿数据库。
 | 原文链接：http://wiki.2bhujh.asia/arts/842726.Doc

原标题：golang 系统设计限流服务架构讲解
简介：golang nilnil interface 陷阱复现，interface 包含类型不为 nil 值为 nil，判 ==nil 返回 false 经典坑。
 | 原文链接：http://wiki.2bhujh.asia/arts/917170.Doc

原标题：golang 系统设计单元测试 mock 外部依赖技巧
简介：golang goreleaser 自动版本发布打包，goreleaser 自动化打包发布，生成多平台二进制归档文件。
 | 原文链接：http://wiki.2bhujh.asia/arts/257070.Doc

原标题：零基础理解前后端简单交互流程
简介：service‑worker 离线缓存实践，使用 ServiceWorker 实现静态资源离线缓存，弱网环境页面依然可访问。
 | 原文链接：http://wiki.2bhujh.asia/arts/281886.Doc

原标题：零基础理解前后端简单交互流程
简介：golang go 优雅处理信号丢失场景，处理信号丢失、信号被忽略，保障程序可以正常接收终止信号。
 | 原文链接：http://wiki.2bhujh.asia/arts/893625.Doc

原标题：golang 系统设计技术方案评审关注点清单参考
简介：WebSocket 双向通信 demo 开发，搭建简易 WebSocket 服务，实现客户端服务端双向消息推送，理解实时通信原理。
 | 原文链接：http://wiki.2bhujh.asia/arts/063050.Doc

原标题：golang rate‑limiter 限流组件
简介：WebSocket 断线重连稳定优化，增加 WebSocket 断线自动重连逻辑，处理网络抖动，维持长连接稳定。
 | 原文链接：http://wiki.2bhujh.asia/arts/553036.Doc

原标题：golang 系统设计容器健康检查设计思路
简介：golang go 项目 CI github actions 配置，github actions 实现 go 项目 ci，自动测试、代码检查、编译打包镜像。
 | 原文链接：http://wiki.2bhujh.asia/arts/630262.Doc

原标题：Troubleshooting：K8sPodOOMKilled完整排查流程
简介：golang pprof 线上采集性能数据，线上环境采集 pprof 性能样本，不用停机，分析线上性能问题。
 | 原文链接：http://wiki.2bhujh.asia/arts/980698.Doc

原标题：golang 系统设计 grpc http2 多路复用讲解
简介：nodejs 集成测试业务流程编写，编写 Node 集成测试，调用真实接口，验证完整业务链路执行结果。
 | 原文链接：http://wiki.2bhujh.asia/arts/818216.Doc

原标题：实战：Nginx配置静态站点、反向代理、负载均衡
简介：golang bufio.Scanner 缓冲区调大，Scanner 默认缓冲区大小不够，读取超长行需要扩大缓冲区。
 | 原文链接：http://wiki.2bhujh.asia/arts/385043.Doc

原标题：跨库查询性能优化处理
简介：golang https 客户端跳过证书校验，开发测试环境跳过 tls 证书校验，仅用于内网测试禁止生产使用。
 | 原文链接：http://wiki.2bhujh.asia/arts/926688.Doc

原标题：项目实践：本地模拟多节点分布式系统实践
简介：golang golangci‑lint 静态代码检查配置，golangci‑lint 静态检查，代码规范检测，提前发现代码隐患。
 | 原文链接：http://wiki.2bhujh.asia/arts/358608.Doc

原标题：站内邮件消息通知功能开发
简介：golang 正则表达式 Go 实操案例，正则匹配提取替换，处理手机号邮箱校验，规避正则回溯 CPU 暴涨。
 | 原文链接：http://wiki.2bhujh.asia/arts/657972.Doc


二、踩坑排错｜Troubleshooting
原标题：架构笔记：海量日志处理架构选型与实践
简介：多线程线程安全脏数据规避，梳理多线程共享变量，做好同步控制，避免并发修改产生脏数据。
 | 原文链接：http://wiki.2bhujh.asia/arts/523506.Doc

原标题：golang mysql 死锁排查步骤讲解
简介：golang 限流熔断放在代理层实践，代理层统一限流熔断，对后端服务做流量保护。
 | 原文链接：http://wiki.2bhujh.asia/arts/000128.Doc

原标题：golang 系统设计内部服务链路 trace 传递实现
简介：golang yaml 解析配置加载实操，Go 解析 YAML 配置文件，读取配置参数，驱动业务运行。
 | 原文链接：http://wiki.2bhujh.asia/arts/323253.Doc

原标题：golang kafka 核心概念分区副本
简介：golang base64 大文件流式编解码，大文件流式 base64 转换，不用一次性加载全部文件进入内存。
 | 原文链接：http://wiki.2bhujh.asia/arts/950011.Doc

原标题：开发复盘：避免大报文导致服务OOM优化实践
简介：Fork 开源项目同步上游代码，Fork 开源仓库之后，配置上游源，同步官方最新代码，保持代码版本对齐。
 | 原文链接：http://wiki.2bhujh.asia/arts/308457.Doc

原标题：Fork 开源项目同步上游代码
简介：gitignore 文件编写过滤规则，讲解 gitignore 语法，编写过滤配置，忽略缓存、编译产物、密钥文件，保持仓库整洁。
 | 原文链接：http://wiki.2bhujh.asia/arts/656505.Doc

原标题：Debug：HTTPS握手失败TLS版本兼容问题
简介：图片上传预览格式大小处理，实现图片上传接口，校验文件格式、大小，完成上传后预览处理。
 | 原文链接：http://wiki.2bhujh.asia/arts/128011.Doc

原标题：golang 多协程任务池并发控制
简介：golang 多协程任务池并发控制，实现协程任务池，控制并发协程数量，防止无限制创建 goroutine。
 | 原文链接：http://wiki.2bhujh.asia/arts/661055.Doc

原标题：golang 系统设计 http1.1 http2 核心差异讲解
简介：golang 项目 go mod 依赖管理，Go Mod 管理项目依赖，下载、升级、清理依赖，解决依赖版本管理。
 | 原文链接：http://wiki.2bhujh.asia/arts/224499.Doc

原标题：避坑：文件锁处理不当多进程竞争死锁
简介：golang context.WithTimeout 超时上下文，WithTimeout 设置超时时间，超时自动 cancel 释放协程。
 | 原文链接：http://wiki.2bhujh.asia/arts/954975.Doc

原标题：golang websocket 消息广播实现
简介：golang 限制 multipart 内存大小，设置 MaxMemory，大文件写入磁盘临时文件防止内存暴涨。
 | 原文链接：http://wiki.2bhujh.asia/arts/704078.Doc

原标题：golang excel 简单读写操作示例
简介：文件批量导入导出功能实现，开发批量导入导出接口，处理大量文件数据，完成业务数据批量迁移与导出。
 | 原文链接：http://wiki.2bhujh.asia/arts/338705.Doc

原标题：golang 系统设计 saga 事务补偿模式实现思路
简介：容器软链接文件权限修复，修复容器内软链接文件权限，让程序能够正常读取软链接指向的文件。
 | 原文链接：http://wiki.2bhujh.asia/arts/008641.Doc

原标题：前端大文件分片上传完整方案
简介：golang 集成测试测试数据库回滚，集成测试结束自动回滚数据库，不污染测试环境数据。
 | 原文链接：http://wiki.2bhujh.asia/arts/280854.Doc

原标题：Architecture：中小型后端服务整体架构设计复盘
简介：golang csv 读写批量数据处理，Go 读写 CSV 文件，批量导入导出业务数据，处理 CSV 格式解析。
 | 原文链接：http://wiki.2bhujh.asia/arts/331271.Doc

原标题：golang es 分词器选型业务适配
简介：golang os 环境变量读取设置，os.Getenv os.Setenv os.Unsetenv 读写环境变量，环境变量多值处理。
 | 原文链接：http://wiki.2bhujh.asia/arts/479559.Doc

原标题：数据库连接池参数调优
简介：golang 命令行交互 cobra 开发 cli，cobra 库开发功能完善命令行工具，子命令参数标志解析。
 | 原文链接：http://wiki.2bhujh.asia/arts/410993.Doc

原标题：golang mysql innodb 事务隔离级别
简介：golang go‑fuzz 模糊测试开发，go fuzz 模糊测试，自动构造异常输入，发现代码隐藏 bug。
 | 原文链接：http://wiki.2bhujh.asia/arts/638392.Doc

原标题：批量操作分批处理防止 OOM
简介：前端工程化 webpack 打包优化，针对 webpack 项目做打包调优，分包、压缩、Tree‑Shaking，缩减包体积。
 | 原文链接：http://wiki.2bhujh.asia/arts/143920.Doc

原标题：复盘总结：接口重构兼容旧版本改造复盘
简介：golang 日志脱敏敏感字段过滤，日志打印自动脱敏敏感字段，避免日志输出手机号身份证泄露隐私。
 | 原文链接：http://wiki.2bhujh.asia/arts/455472.Doc

原标题：实践：灰度流量切分简易实现方案
简介：golang race 检测器性能开销，race 检测器有性能损耗，只用于测试环境，禁止生产开启 race。
 | 原文链接：http://wiki.2bhujh.asia/arts/028353.Doc

原标题：react 状态管理方案选型对比
简介：golang excel 生成导出高性能方案，excelize 流式生成 excel，百万行数据导出，规避内存溢出。
 | 原文链接：http://wiki.2bhujh.asia/arts/417504.Doc

原标题：golang 多协程任务池并发控制
简介：golang go list 双向链表使用，container/list 双向链表，频繁增删节点业务场景使用。
 | 原文链接：http://wiki.2bhujh.asia/arts/151266.Doc

原标题：程序日志分级输出规范实践
简介：golang pprof 线上采集性能数据，线上环境采集 pprof 性能样本，不用停机，分析线上性能问题。
 | 原文链接：http://wiki.2bhujh.asia/arts/002048.Doc

原标题：开发记录：表单文件类型校验后端安全校验实践
简介：golang 负载均衡轮询加权轮询实现，手写负载均衡算法，轮询、加权轮询分发请求到后端节点。
 | 原文链接：http://wiki.2bhujh.asia/arts/314006.Doc

原标题：Issue：文件句柄耗尽，服务缓慢卡死复盘
简介：golang 大文件 HTTP 流式上传接收，服务端流式接收上传文件，不全部加载内存，防止大文件 OOM 崩溃。
 | 原文链接：http://wiki.2bhujh.asia/arts/071341.Doc

原标题：灰度发布策略服务平滑升级
简介：多实例部署 Session 共享方案，多服务实例部署场景，实现 Session 共享，保证用户登录状态跨实例生效。
 | 原文链接：http://wiki.2bhujh.asia/arts/398323.Doc

原标题：入门实战：搭建简易静态网页项目
简介：golang 时间轮算法实现延时调度，手写简易时间轮，高并发大量延时任务，降低轮询 CPU 消耗。
 | 原文链接：http://wiki.2bhujh.asia/arts/857331.Doc

原标题：调优方案：消息队列消费速度优化处理堆积
简介：golang 数据库连接泄露排查，定位 Go 数据库连接泄露，连接没有归还池，导致连接耗尽报错。
 | 原文链接：http://wiki.2bhujh.asia/arts/181393.Doc

原标题：golang 系统设计 hot‑reload 热重载 go 开发工具
简介：golang viper 多源配置管理实操，viper 读取配置文件环境变量命令行参数，多源配置优先级管理。
 | 原文链接：http://wiki.2bhujh.asia/arts/046113.Doc

原标题：golang 系统设计定时任务分布式锁防重复执行
简介：golang go 项目安全检查漏洞扫描，扫描 go 项目依赖漏洞，代码安全审计，规避安全风险。
 | 原文链接：http://wiki.2bhujh.asia/arts/354376.Doc

原标题：安全复盘：日志打印敏感信息泄露治理
简介：RPC 报文大小上限调优大请求，调大 RPC 框架报文最大限制，支持传输大体积请求报文不被截断。
 | 原文链接：http://wiki.2bhujh.asia/arts/928787.Doc

原标题：golang 接口限流中间件开发
简介：golang goroutine 泄露检测告警实现，监控 goroutine 数量，突增触发告警，提早发现协程泄露。
 | 原文链接：http://wiki.2bhujh.asia/arts/401080.Doc

原标题：Debug：表单提交特殊字符造成接口解析失败
简介：GitHub Markdown 文档语法汇总，整理 Markdown 常用语法，编写仓库 README、文档，提升开源项目文档排版质量。
 | 原文链接：http://wiki.2bhujh.asia/arts/212369.Doc

原标题：排错：CI缓存策略错误，每次全量重新构建
简介：接口压测定位系统性能瓶颈，使用压测工具对接口施压，观察指标，定位系统性能瓶颈点。
 | 原文链接：http://wiki.2bhujh.asia/arts/826719.Doc

原标题：坑点：环境配置写死代码，上线忘记修改
简介：golang 配置文件多环境加载，Go 多环境配置加载实现，读取配置文件环境变量，适配多套运行环境。
 | 原文链接：http://wiki.2bhujh.asia/arts/655049.Doc

原标题：golang 系统设计日志轮转切割防止磁盘占满
简介：golang go 防止路径穿越攻击，文件操作校验路径，拒绝../ 路径穿越，禁止访问系统任意文件。
 | 原文链接：http://wiki.2bhujh.asia/arts/527755.Doc

原标题：golang zap 日志按日期切割方案
简介：golang gin 静态资源访问配置，Gin 配置静态资源目录，直接对外提供静态文件访问服务。
 | 原文链接：http://wiki.2bhujh.asia/arts/465868.Doc

原标题：golang 参数校验业务接口处理
简介：配置与镜像分离防止信息泄露，业务配置不打包进镜像，外部挂载配置，避免密钥配置随镜像泄露。
 | 原文链接：http://wiki.2bhujh.asia/arts/450550.Doc

原标题：安全实践：防止JSON解析漏洞恶意payload
简介：golang go‑pg postgres 客户端实操，go‑pg 操作 PostgreSQL 数据库，CRUD 关联查询业务开发。
 | 原文链接：http://wiki.2bhujh.asia/arts/550598.Doc

三、实战开发｜Practice
原标题：HelloGitWorkflow：理解简单主干开发流程
简介：OAuth2 第三方登录服务搭建，搭建 OAuth2 服务，支持第三方账号登录，实现授权登录能力。
 | 原文链接：http://wiki.2bhujh.asia/arts/734398.Doc

原标题：react hooks 常见陷阱避坑指南
简介：golang go ring 环形容器循环队列，ring 环形链表实现循环队列，环形缓冲区业务场景。
 | 原文链接：http://wiki.2bhujh.asia/arts/797049.Doc

原标题：架构复盘：数据库主从架构设计与延迟应对方案
简介：golang testify mock 模拟接口，mock 接口生成 mock 对象，单元测试模拟外部依赖行为。
 | 原文链接：http://wiki.2bhujh.asia/arts/886132.Doc

原标题：静态站点自动部署发布方案
简介：死信队列处理消息阻塞业务，配置死信队列，处理消费失败消息，避免失败消息阻塞整个队列业务。
 | 原文链接：http://wiki.2bhujh.asia/arts/457939.Doc

原标题：磁盘占满服务不可用清理方案
简介：golang json 自定义 MarshalJSON UnmarshalJSON，自定义 json 序列化反序列化逻辑，处理特殊格式字段。
 | 原文链接：http://wiki.2bhujh.asia/arts/330024.Doc

原标题：golang 系统设计 docker compose 本地开发环境搭建
简介：golang http.Server 配置参数详解，ReadTimeout WriteTimeout IdleTimeout，全方位防护慢请求攻击。
 | 原文链接：http://wiki.2bhujh.asia/arts/562168.Doc

原标题：部署复盘：配置热更新不用重启服务方案
简介：时间同步修复令牌提前过期，服务器时间不同步导致 JWT 令牌提前过期，同步系统时间解决异常。
 | 原文链接：http://wiki.2bhujh.asia/arts/816383.Doc

原标题：调试工具断点调试变量查看技巧
简介：golang clickhouse go 客户端数据写入，clickhouse‑go 客户端写入查询，海量时序数据分析业务。
 | 原文链接：http://wiki.2bhujh.asia/arts/073194.Doc

原标题：Troubleshooting：数据库主从延迟带来查询数据不一致
简介：golang 表格驱动测试完整示例，表格驱动多组输入输出，批量执行测试用例，减少重复代码。
 | 原文链接：http://wiki.2bhujh.asia/arts/586093.Doc

原标题：安全实践：请求输入校验防御恶意参数
简介：golang 字符串处理常用技巧汇总，字符串拼接、分割、替换、类型转换实操，规避字符串高频错误。
 | 原文链接：http://wiki.2bhujh.asia/arts/119781.Doc

原标题：Hands‑on：手写简易ORM框架理解底层原理
简介：nestjs 全局返回格式统一处理，Nest 全局拦截器统一包装接口返回数据，对外输出标准化响应格式。
 | 原文链接：http://wiki.2bhujh.asia/arts/939130.Doc

原标题：避坑：正则回溯引发CPU占满DoS风险
简介：golang 异步任务队列 worker 池开发，任务入数据库或 redis，worker 池消费执行，异步处理耗时业务。
 | 原文链接：http://wiki.2bhujh.asia/arts/307236.Doc

原标题：Practice：实现业务唯一流水号生成组件实践
简介：空指针异常判空容错处理，讲解空指针产生场景，规范判空逻辑，增加容错，避免空指针直接造成程序崩溃。
 | 原文链接：http://wiki.2bhujh.asia/arts/824716.Doc

原标题：golang 系统设计告警规则阈值设置方法论
简介：golang 多协程任务池并发控制，实现协程任务池，控制并发协程数量，防止无限制创建 goroutine。
 | 原文链接：http://wiki.2bhujh.asia/arts/502529.Doc

原标题：nodejs jwt 登录鉴权完整示例
简介：service‑worker 离线缓存实践，使用 ServiceWorker 实现静态资源离线缓存，弱网环境页面依然可访问。
 | 原文链接：http://wiki.2bhujh.asia/arts/668553.Doc

原标题：golang 单元测试 table‑driven
简介：golang go sum 校验失败处理方案，go sum 校验不匹配，排查网络代理，清理缓存解决校验报错。
 | 原文链接：http://wiki.2bhujh.asia/arts/776768.Doc

原标题：golang 系统设计内存高占用排查思路
简介：golang 反向代理 http 服务开发，手写简易 http 反向代理，转发请求，修改请求头响应头。
 | 原文链接：http://wiki.2bhujh.asia/arts/127943.Doc

原标题：golang 系统设计 rest api 接口设计最佳实践
简介：golang go‑zero rpc 微服务开发，go‑zero 定义 proto，生成 rpc 服务代码，实现微服务调用。
 | 原文链接：http://wiki.2bhujh.asia/arts/520931.Doc

原标题：golang 系统设计主键 id 选型雪花自增对比
简介：网关集成鉴权限流日志一体化，在网关层整合鉴权、限流、请求日志，统一对入口请求做管控处理。
 | 原文链接：http://wiki.2bhujh.asia/arts/474836.Doc

原标题：golang 简易埋点日志上报实现
简介：业务错误码完整落地实践，落地完整业务错误码，枚举全部业务异常，统一返回，配套文档说明。
 | 原文链接：http://wiki.2bhujh.asia/arts/635653.Doc

原标题：编译打包产物依赖分析解读
简介：依赖安装失败全方位排错，从网络、镜像源、权限、版本多角度，定位依赖安装失败，给出对应修复手段。
 | 原文链接：http://wiki.2bhujh.asia/arts/361139.Doc

原标题：golang 系统设计日志采样降低存储开销方案
简介：golang go 模板缓存预编译模板，预编译 html 模板，程序启动加载，避免每次请求解析模板损耗性能。
 | 原文链接：http://wiki.2bhujh.asia/arts/007099.Doc

原标题：nodejs 脚手架工具开发完整教程
简介：慢查询分析索引调优数据库实战，抓取慢查询，分析执行计划，优化索引，解决数据库慢查询拖慢业务。
 | 原文链接：http://wiki.2bhujh.asia/arts/679827.Doc

原标题：入门实践：Git分支创建切换合并完整演示
简介：golang go sum 校验失败处理方案，go sum 校验不匹配，排查网络代理，清理缓存解决校验报错。
 | 原文链接：http://wiki.2bhujh.asia/arts/564683.Doc

原标题：动态定时任务业务调度实现
简介：请求工具封装统一异常处理，对网络请求做二次封装，统一捕获各类请求异常，标准化接口返回格式。
 | 原文链接：http://wiki.2bhujh.asia/arts/995895.Doc

原标题：Practice：实现简单信号处理优雅停机实践
简介：并发数据覆盖加锁安全处理，多线程并发修改同一数据，增加锁机制，防止并发覆盖丢失更新数据。
 | 原文链接：http://wiki.2bhujh.asia/arts/669827.Doc

原标题：golang validator 自定义校验规则
简介：golang gorm 原生 SQL 执行处理，复杂场景执行原生 SQL，处理返回结果集，兼顾性能与灵活性。
 | 原文链接：http://wiki.2bhujh.asia/arts/155375.Doc

原标题：Debug：分布式会话时钟不同步令牌提前失效
简介：service‑worker 离线缓存实践，使用 ServiceWorker 实现静态资源离线缓存，弱网环境页面依然可访问。
 | 原文链接：http://wiki.2bhujh.asia/arts/966899.Doc

原标题：Git 误删提交代码恢复找回
简介：golang net.Conn 包装自定义连接，包装 net.Conn，统计读写字节，日志打印，超时控制。
 | 原文链接：http://wiki.2bhujh.asia/arts/903544.Doc

原标题：golang 系统设计读写穿透更新缓存几种方案
简介：CPU 亲和性配置负载均衡调度，配置进程 CPU 亲和，均衡利用多核 CPU，优化程序调度性能。
 | 原文链接：http://wiki.2bhujh.asia/arts/877976.Doc

原标题：程序信号中断退出处理逻辑
简介：golang 制品镜像版本号规范管理，镜像版本号结合 git commit，明确每个镜像对应代码版本便于追溯。
 | 原文链接：http://wiki.2bhujh.asia/arts/348013.Doc

原标题：golang docker 部署 mysql 注意事项
简介：golang channel 作为函数参数方向，声明 channel 入参方向，只读 channel 只写 channel 提升代码约束。
 | 原文链接：http://wiki.2bhujh.asia/arts/806820.Doc

原标题：安全复盘：OAuth2授权流程安全坑点汇总
简介：golang go 服务蓝绿发布实践思路，蓝绿两套实例，流量一键切换，回滚快速降低发布风险。
 | 原文链接：http://wiki.2bhujh.asia/arts/525000.Doc

原标题：日志敏感信息脱敏泄露防护
简介：分布式任务调度集群原型开发，开发简易分布式调度原型，集群多节点运行，保证任务只执行一次。
 | 原文链接：http://wiki.2bhujh.asia/arts/597606.Doc

原标题：Git 代码冲突正确处理方式
简介：golang 图片处理 go 图片裁剪压缩，golang 图像处理库，图片缩放裁剪水印，服务端图片处理。
 | 原文链接：http://wiki.2bhujh.asia/arts/039080.Doc

原标题：调优方案：数据库索引不要过度建立，权衡写性能
简介：主干开发团队代码合并策略，讲解主干开发模式，团队代码合并流程，适合高频迭代的团队协作模式。
 | 原文链接：http://wiki.2bhujh.asia/arts/708702.Doc

原标题：方案对比：同步调用vs异步消息业务选型
简介：golang 时间时区处理避坑指南，Go 时间时区常见坑，时区转换，时间比较，规避时间逻辑错误。
 | 原文链接：http://wiki.2bhujh.asia/arts/416091.Doc

原标题：优化实践：异步改造同步接口提升吞吐能力
简介：golang redis pipeline 批量操作，使用 Redis Pipeline 批量执行多条命令，减少网络往返，提升批量操作性能。
 | 原文链接：http://wiki.2bhujh.asia/arts/597979.Doc

原标题：开发复盘：大列表内存分批读取避免OOM实践
简介：JWT 工具封装令牌刷新过期，封装 JWT 工具类，实现令牌生成、校验、过期刷新整套令牌管理逻辑。
 | 原文链接：http://wiki.2bhujh.asia/arts/647281.Doc

原标题：开源实践：开源项目本地调试构建排坑经验
简介：golang go 多版本管理 gvm 使用，gvm 管理多个 go sdk 版本，快速切换不同 go 版本做项目开发。
 | 原文链接：http://wiki.2bhujh.asia/arts/258175.Doc

四、架构设计｜Architecture
原标题：golang 系统设计链路数据存储选型对比讲解
简介：eslint prettier 代码规范落地，配置 eslint 与 prettier，做代码检查格式化，统一前端团队代码风格。
 | 原文链接：http://wiki.2bhujh.asia/arts/926293.Doc

原标题：golang 系统设计内存高占用排查思路
简介：golang sync.Once 只执行一次，sync.Once 做单例初始化，保证代码只执行一次，并发安全。
 | 原文链接：http://wiki.2bhujh.asia/arts/295574.Doc

原标题：开发记录：网关实现接口鉴权、限流、日志打印
简介：golang channel 通道并发处理，讲解 Channel 用法，协程之间通过通道传递数据，做并发同步控制。
 | 原文链接：http://wiki.2bhujh.asia/arts/365266.Doc

原标题：快速上手搭建简易内网测试服务
简介：golang ip 限流黑名单实现方案，基于 IP 做限流与黑名单，拦截恶意 IP 访问，保护接口服务。
 | 原文链接：http://wiki.2bhujh.asia/arts/001820.Doc

原标题：Redis 热点 key 拆分降低集群压力
简介：配置与镜像分离防止信息泄露，业务配置不打包进镜像，外部挂载配置，避免密钥配置随镜像泄露。
 | 原文链接：http://wiki.2bhujh.asia/arts/637563.Doc

原标题：开发复盘：大事务拆分优化业务性能实践
简介：golang excel 生成导出高性能方案，excelize 流式生成 excel，百万行数据导出，规避内存溢出。
 | 原文链接：http://wiki.2bhujh.asia/arts/283478.Doc

原标题：方案对比：缓存更新策略Cache‑Aside读写模式
简介：golang 限流熔断放在代理层实践，代理层统一限流熔断，对后端服务做流量保护。
 | 原文链接：http://wiki.2bhujh.asia/arts/495564.Doc

原标题：gRPC 服务端客户端入门示例
简介：golang kafka 批量消费性能优化，开启批量拉取消息，调整批量大小，提升 kafka 消息消费吞吐量。
 | 原文链接：http://wiki.2bhujh.asia/arts/030897.Doc

原标题：Architecture：文件处理服务架构大文件内存规避
简介：Git 标签版本标记发布管理，使用 Git 标签标记项目版本，打标签推送远程，用于版本发布、版本回溯。
 | 原文链接：http://wiki.2bhujh.asia/arts/076183.Doc

原标题：golang es 聚合统计查询实现
简介：golang context.WithTimeout 超时上下文，WithTimeout 设置超时时间，超时自动 cancel 释放协程。
 | 原文链接：http://wiki.2bhujh.asia/arts/584987.Doc

原标题：业务错误码完整落地实践
简介：golang excel 大文件读取流式解析，流式读取大 excel 文件，逐行解析数据，不加载全部内容进内存。
 | 原文链接：http://wiki.2bhujh.asia/arts/666045.Doc

原标题：优化实践：Redis性能调优，避免大key热key
简介：网关超时时间调优后端等待，调大网关向后端转发请求超时时间，给后端业务充足处理时间。
 | 原文链接：http://wiki.2bhujh.asia/arts/655158.Doc

原标题：方案设计：分布式分页查询架构难点处理
简介：golang go 包循环导入报错解决，A 导入 B B 导入 A，循环导入报错，重构代码拆分包消除循环依赖。
 | 原文链接：http://wiki.2bhujh.asia/arts/239672.Doc

原标题：快速启动：本地运行开源项目排障清单
简介：前端权限路由动态生成实现，根据后端返回权限，动态生成前端路由菜单，实现页面权限控制。
 | 原文链接：http://wiki.2bhujh.asia/arts/623140.Doc

原标题：避坑：请求未设置read超时无限挂起连接
简介：游标分页大数据查询性能提升，使用游标分页替代偏移分页，解决大数据 offset 分页性能越来越差问题。
 | 原文链接：http://wiki.2bhujh.asia/arts/399553.Doc

原标题：golang redis 客户端业务使用
简介：golang go‑zero 框架项目快速搭建，go‑zero 脚手架生成微服务项目，api rpc 服务快速开发。
 | 原文链接：http://wiki.2bhujh.asia/arts/682137.Doc

原标题：golang redis 热点 key 业务规避
简介：vite 项目配置与构建提速技巧，讲解 vite 配置优化手段，提升开发热更新速度与生产构建打包效率。
 | 原文链接：http://wiki.2bhujh.asia/arts/172177.Doc

原标题：Architecture：监控告警架构避免告警风暴设计
简介：golang go 程序 CPU 占用高定位步骤，pprof 定位热点函数，分析 CPU 高占用，优化耗时代码逻辑。
 | 原文链接：http://wiki.2bhujh.asia/arts/554160.Doc

?
