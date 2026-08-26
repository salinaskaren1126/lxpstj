最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang 系统设计网关性能压测优化简单思路
简介：全局时间标准统一逻辑错乱修复，全服务统一使用同一时间标准，不要混用本地时间 UTC，修复时间逻辑 bug。
 | 原文链接：http://wiki.9jnxlh.asia/arts/906568.Doc

原标题：golang 系统设计本地缓存 redis 缓存多级组合
简介：跨库查询性能优化处理，减少跨库关联查询，做数据冗余或者中间表，规避跨库查询性能低下。
 | 原文链接：http://wiki.9jnxlh.asia/arts/456187.Doc

原标题：实战：搭建本地对象存储兼容S3协议demo
简介：golang cron 任务漂移问题处理，cron 任务执行超时导致任务漂移，通过分布式锁防止任务重叠执行。
 | 原文链接：http://wiki.9jnxlh.asia/arts/994400.Doc

原标题：Issue：防火墙拦截ICMP，MTU问题网络丢包
简介：分布式 ID 生成器高并发实现，实现高性能分布式 ID 生成器，适配高并发业务，生成全局唯一 ID。
 | 原文链接：http://wiki.9jnxlh.asia/arts/333539.Doc

原标题：调优方案：JVM内存参数优化，降低GC频率
简介：golang ssh 客户端远程命令执行，golang ssh 连接远程服务器，执行 shell 命令，获取命令输出结果。
 | 原文链接：http://wiki.9jnxlh.asia/arts/539425.Doc

原标题：golang gorm 批量插入性能调优
简介：golang go 并发模式 errgroup 使用，errgroup 结合 context，协程组，任意协程出错整体取消任务。
 | 原文链接：http://wiki.9jnxlh.asia/arts/872035.Doc

原标题：DNS TTL 配置域名切换生效
简介：golang go 爬虫 html 解析 goquery，goquery 解析 html 文档，css 选择器提取网页内容，实现网页数据抓取。
 | 原文链接：http://wiki.9jnxlh.asia/arts/928491.Doc

原标题：性能复盘：GC停顿过长业务卡顿优化记录
简介：开发代理服务网络限制解决，搭建本地代理服务，解决开发环境网络访问受限，实现外部接口正常调用。
 | 原文链接：http://wiki.9jnxlh.asia/arts/779387.Doc

原标题：架构复盘：数据库索引架构设计原则与边界
简介：golang go‑zero 分布式锁组件使用，go‑zero 内置 redis 分布式锁，业务直接调用实现并发控制。
 | 原文链接：http://wiki.9jnxlh.asia/arts/512614.Doc

原标题：golang 系统设计读写分离架构示例
简介：golang gin 路由分组权限管控，Gin 路由分组，不同分组绑定鉴权中间件，实现接口权限分组管控。
 | 原文链接：http://wiki.9jnxlh.asia/arts/527062.Doc

原标题：架构复盘：服务灰度发布架构设计与流量切分
简介：golang channel 关闭规则与坑点，关闭已经关闭 channel 会 panic，判断 channel 是否关闭正确写法。
 | 原文链接：http://wiki.9jnxlh.asia/arts/796620.Doc

原标题：rebase 操作防止代码丢失
简介：golang 故障演练服务模拟超时报错，程序模拟接口超时、报错，做混沌测试验证熔断降级有效性。
 | 原文链接：http://wiki.9jnxlh.asia/arts/448651.Doc

原标题：golang 系统设计分库分表本地测试调试技巧
简介：golang cgroup 读取容器资源限制，go 程序读取 cgroup，获取容器 cpu 内存限额，适配容器环境。
 | 原文链接：http://wiki.9jnxlh.asia/arts/635514.Doc

原标题：Hands‑on：简易短链接服务完整开发实践
简介：golang 命令行交互 cobra 开发 cli，cobra 库开发功能完善命令行工具，子命令参数标志解析。
 | 原文链接：http://wiki.9jnxlh.asia/arts/815816.Doc

原标题：golang aes 对称加密解密示例
简介：调试工具断点调试变量查看技巧，演示断点设置、变量监视、调用栈查看，借助调试工具高效排查业务逻辑错误。
 | 原文链接：http://wiki.9jnxlh.asia/arts/230348.Doc

原标题：Debug日志：生产环境偶发空指针异常排查
简介：golang 表格驱动测试完整示例，表格驱动多组输入输出，批量执行测试用例，减少重复代码。
 | 原文链接：http://wiki.9jnxlh.asia/arts/522037.Doc

原标题：golang minio 分片上传断点续传
简介：后端登录鉴权模块完整开发，实现完整登录模块，包含账号校验、令牌发放、接口鉴权整套能力。
 | 原文链接：http://wiki.9jnxlh.asia/arts/425295.Doc

原标题：性能笔记：线程池参数调优任务队列策略
简介：nodejs redis 缓存业务实战，Node 对接 Redis 实现业务缓存，缓存热点查询结果，减轻数据库压力。
 | 原文链接：http://wiki.9jnxlh.asia/arts/127714.Doc

原标题：优化实践：接口返回字段裁剪减少报文大小
简介：文件句柄耗尽资源泄露处理，定位文件句柄泄露，修复文件忘记关闭问题，解决句柄耗尽服务报错。
 | 原文链接：http://wiki.9jnxlh.asia/arts/932162.Doc

原标题：新手向：开源项目依赖安装失败排查
简介：golang alertmanager 告警配置实践，alertmanager 配置告警路由，告警发送邮件钉钉，异常及时通知运维。
 | 原文链接：http://wiki.9jnxlh.asia/arts/834662.Doc

原标题：golang 系统设计日志本地打印线上关闭调试信息
简介：读懂开源项目 README 实用技巧，教你快速解析开源项目说明文档，提取安装、运行、配置关键信息，快速上手项目。
 | 原文链接：http://wiki.9jnxlh.asia/arts/795815.Doc

原标题：Troubleshooting：依赖安装失败完整排查清单
简介：操作系统内核版本适配服务，针对服务运行要求，适配操作系统内核版本，规避内核兼容 bug。
 | 原文链接：http://wiki.9jnxlh.asia/arts/069081.Doc

原标题：排错：内网域名解析不稳定导致服务随机报错
简介：golang 模糊测试 go fuzz 基础编写，Fuzz 测试函数，自动生成随机输入，发现代码崩溃 panic。
 | 原文链接：http://wiki.9jnxlh.asia/arts/307551.Doc

原标题：golang docker compose 部署 minio
简介：golang grpc keepalive 保活配置，grpc keepalive 参数调优，检测断开僵死连接，释放无效连接资源。
 | 原文链接：http://wiki.9jnxlh.asia/arts/890510.Doc

原标题：批量操作分批处理防止 OOM
简介：代码模块化组件化拆分思路，讲解代码拆分原则，将大业务拆分为独立模块组件，提升代码复用与维护能力。
 | 原文链接：http://wiki.9jnxlh.asia/arts/544546.Doc

原标题：安全复盘：业务登录暴力破解防护完整方案
简介：golang go 程序权限最小化运行，容器内使用普通用户运行程序，拒绝 root 运行提升安全等级。
 | 原文链接：http://wiki.9jnxlh.asia/arts/222694.Doc

原标题：坑点：gitreset误删本地代码恢复方案
简介：golang go 调度器 GMP 模型通俗讲解，拆解 GMP 模型，理解 goroutine M P 调度原理，看懂调度状态。
 | 原文链接：http://wiki.9jnxlh.asia/arts/900628.Doc

原标题：golang kafka offset 提交策略
简介：数据库 utf8mb4 支持 emoji 存储，数据库字段设置 utf8mb4 字符集，完整支持 emoji 表情存储入库。
 | 原文链接：http://wiki.9jnxlh.asia/arts/756377.Doc

原标题：golang 系统设计内部服务熔断降级配置思路
简介：golang 限流熔断放在代理层实践，代理层统一限流熔断，对后端服务做流量保护。
 | 原文链接：http://wiki.9jnxlh.asia/arts/704547.Doc

原标题：golang es bool 查询条件组合技巧
简介：golang gin 路由动态注册实现方案，根据配置动态注册接口路由，无需硬编码路由，适配动态业务模块。
 | 原文链接：http://wiki.9jnxlh.asia/arts/531861.Doc

原标题：golang minio 存储桶权限管控配置
简介：golang gin 框架接口开发实战，Gin 框架搭建 HTTP 服务，开发增删改查接口，快速完成后端接口开发。
 | 原文链接：http://wiki.9jnxlh.asia/arts/603816.Doc

原标题：golang 系统设计错误码体系完整设计
简介：消息队列重复消费业务处理，实现消息消费幂等，处理重复投递消息，保证多次消费业务结果一致。
 | 原文链接：http://wiki.9jnxlh.asia/arts/675355.Doc

原标题：golang 系统设计 mq 消息重复消费处理
简介：golang ip2regionIP 地址解析实战，集成 ip2region 库，根据 IP 解析归属地城市，实现 IP 地域解析。
 | 原文链接：http://wiki.9jnxlh.asia/arts/635198.Doc

原标题：golang 系统设计大文件上传架构
简介：golang fuzz corpus 语料库使用，fuzz 语料存储历史输入，回归测试，持续复现曾经触发 bug 输入。
 | 原文链接：http://wiki.9jnxlh.asia/arts/192134.Doc

原标题：golang 系统设计内部服务 mock 集成测试方案
简介：golang systemd 配置 go 服务部署，编写 systemd unit 文件管理 go 服务，开机自启、崩溃自动重启。
 | 原文链接：http://wiki.9jnxlh.asia/arts/492195.Doc

原标题：排错：本地[localhost](https://localhost)可以，127001访问失败
简介：服务器 Swap 关闭提升响应速度，关闭服务器 Swap 交换分区，避免内存交换磁盘拖慢程序响应性能。
 | 原文链接：http://wiki.9jnxlh.asia/arts/384328.Doc

原标题：开发测试生产多环境配置区分
简介：极简 API 网关路由转发实现，开发极简网关服务，完成请求路由转发，理解网关基础实现原理。
 | 原文链接：http://wiki.9jnxlh.asia/arts/220818.Doc

原标题：开发复盘：实现定时任务调度服务支持动态任务
简介：全量回归测试提升代码质量，搭建全量回归测试集，版本发布执行回归测试，避免迭代引入旧 bug。
 | 原文链接：http://wiki.9jnxlh.asia/arts/567517.Doc

原标题：优化实践：Redis性能调优，避免大key热key
简介：golang gorm 索引设置与优化技巧，定义数据库索引，理解索引生效条件，避免索引失效慢查询。
 | 原文链接：http://wiki.9jnxlh.asia/arts/558645.Doc

原标题：快速入门ORM，实现简单数据库增删改查
简介：磁盘 inode 耗尽文件创建失败，排查磁盘 inode 占用，清理大量小文件，恢复文件创建能力。
 | 原文链接：http://wiki.9jnxlh.asia/arts/884965.Doc


二、踩坑排错｜Troubleshooting
原标题：线上故障：消息队列重复消费业务处理异常
简介：Nginx 缓冲区调优大文件上传，调大 Nginx 请求缓冲区，支持客户端上传大体积文件，避免上传被截断。
 | 原文链接：http://wiki.9jnxlh.asia/arts/672813.Doc

原标题：新手向：Mac/Windows开发环境差异踩坑
简介：golang go 网络编程 net 包基础，net 包 tcp udp socket 编程，监听接收连接，读写数据。
 | 原文链接：http://wiki.9jnxlh.asia/arts/692409.Doc

原标题：Security：限流防爬虫防恶意攻击防护体系
简介：golang 故障演练服务模拟超时报错，程序模拟接口超时、报错，做混沌测试验证熔断降级有效性。
 | 原文链接：http://wiki.9jnxlh.asia/arts/160991.Doc

原标题：实战：Nginx配置静态站点、反向代理、负载均衡
简介：golang interface 接口使用避坑，interface 判 nil 坑点，理解接口底层结构，避免判空逻辑失效。
 | 原文链接：http://wiki.9jnxlh.asia/arts/940866.Doc

原标题：实战：基于内存实现简单消息广播组件
简介：提交第一个开源 PR 完整流程，Fork 项目、修改代码、提交 Pull Request，讲解 PR 规范，提升合并通过率。
 | 原文链接：http://wiki.9jnxlh.asia/arts/157497.Doc

原标题：记一次分库分表路由计算错误数据写入错误分片
简介：golang 多协程任务池并发控制，实现协程任务池，控制并发协程数量，防止无限制创建 goroutine。
 | 原文链接：http://wiki.9jnxlh.asia/arts/818524.Doc

原标题：golang 系统设计创建更新时间自动维护方案
简介：nodejs 集群模式多核利用实现，使用 cluster 集群模式，充分利用服务器多核 CPU，提升服务处理能力。
 | 原文链接：http://wiki.9jnxlh.asia/arts/295242.Doc

原标题：golang 系统设计 issue 模板 bug 反馈模板
简介：WSL 文件权限访问异常修复，处理 WSL 环境文件权限错乱，调整权限配置，实现文件正常读写访问。
 | 原文链接：http://wiki.9jnxlh.asia/arts/692604.Doc

原标题：golang 系统设计配置灰度下发简单实现思路
简介：golang makefile 多平台编译脚本，makefile 一键交叉编译多平台二进制，打包镜像，执行测试。
 | 原文链接：http://wiki.9jnxlh.asia/arts/943681.Doc

原标题：golang mongodb 索引优化查询速度
简介：eslint prettier 代码规范落地，配置 eslint 与 prettier，做代码检查格式化，统一前端团队代码风格。
 | 原文链接：http://wiki.9jnxlh.asia/arts/202699.Doc

原标题：golang 系统设计接口幂等架构设计
简介：golang docker compose 开发环境 go 服务，docker compose 编排 go 服务与中间件，本地一键拉起整套开发环境。
 | 原文链接：http://wiki.9jnxlh.asia/arts/911288.Doc

原标题：避坑：CookieSecure属性造成测试环境登录失败
简介：golang html 模板渲染简单示例，Go HTML 模板渲染，服务端渲染页面，填充数据输出 HTML 页面。
 | 原文链接：http://wiki.9jnxlh.asia/arts/580060.Doc

原标题：调优方案：MySQL缓冲池参数性能调优实践
简介：大事务拆分回滚日志暴涨解决，拆分大型数据库事务，减少回滚日志生成量，避免磁盘被回滚日志占满。
 | 原文链接：http://wiki.9jnxlh.asia/arts/481054.Doc

原标题：特殊输入字符过滤解析防护
简介：golang time duration 解析时间字符串，time.ParseDuration 解析 1h30m 时间间隔字符串。
 | 原文链接：http://wiki.9jnxlh.asia/arts/009336.Doc

原标题：线程调度优化减少上下文切换
简介：golang go 代码覆盖率线上统计，单元测试覆盖率统计，找出未测试代码分支，提升测试质量。
 | 原文链接：http://wiki.9jnxlh.asia/arts/178487.Doc

原标题：坑点：缓存过期策略不当引发业务异常
简介：golang ioutil 已废弃替换方案，ioutil 废弃之后替换为 os io 包函数，更新旧项目代码。
 | 原文链接：http://wiki.9jnxlh.asia/arts/189787.Doc

原标题：Hands‑on：编写GitLabCI配置自动测试部署
简介：golang 模板函数自定义拓展，自定义 template 模板函数，在 html 模板调用自定义逻辑处理数据。
 | 原文链接：http://wiki.9jnxlh.asia/arts/741991.Doc

原标题：Hands‑on：简易布隆过滤器实现与测试验证
简介：golang errgroup 协程组错误处理，errgroup 捕获协程错误，context 取消剩余协程，简化并发任务。
 | 原文链接：http://wiki.9jnxlh.asia/arts/301609.Doc

原标题：项目实践：实现数据脱敏组件支持多种脱敏规则
简介：开源项目本地运行排错完整清单，汇总开源项目拉取后运行失败各类问题，给出排查思路，快速解决本地启动异常。
 | 原文链接：http://wiki.9jnxlh.asia/arts/931997.Doc

原标题：消息消费重试次数限制防爆炸
简介：golang go 输入数据校验防御，所有外部入参严格校验长度格式，防止恶意输入造成业务异常。
 | 原文链接：http://wiki.9jnxlh.asia/arts/053926.Doc

原标题：线上故障：热点Key打满RedisCPU节点过载
简介：golang time.After 内存泄漏场景，for 循环使用 time.After 会创建大量 timer，造成内存泄漏。
 | 原文链接：http://wiki.9jnxlh.asia/arts/317800.Doc

原标题：golang minio 预签名 url 临时访问
简介：golang go mod exclude 排除依赖版本，exclude 排除有问题依赖版本，规避有 bug 的第三方包。
 | 原文链接：http://wiki.9jnxlh.asia/arts/379112.Doc

原标题：项目实践：本地模拟多节点分布式系统实践
简介：nodejs 跨域中间件配置细节，Express 跨域中间件配置细节，处理预检请求，修复偶现跨域失效。
 | 原文链接：http://wiki.9jnxlh.asia/arts/688503.Doc

原标题：golang 系统设计唯一索引业务使用场景
简介：monorepo 项目多包管理最佳实践，monorepo 仓库管理多子包，统一版本管理，处理包之间互相依赖。
 | 原文链接：http://wiki.9jnxlh.asia/arts/595492.Doc

原标题：nestjs 权限守卫鉴权实现方案
简介：golang goroutine 泄露检测告警实现，监控 goroutine 数量，突增触发告警，提早发现协程泄露。
 | 原文链接：http://wiki.9jnxlh.asia/arts/468636.Doc

原标题：golang 系统设计防重复提交实现
简介：前端 pdf 预览渲染方案对比，对比前端 PDF 预览库，分析性能、兼容性，给出业务选型参考。
 | 原文链接：http://wiki.9jnxlh.asia/arts/614188.Doc

原标题：Troubleshoot：RPC序列化对象字段增减兼容踩坑
简介：nodejs 项目 pm2 部署运维指南，使用 PM2 管理 Node 服务，进程守护、日志、重启，线上部署运维实操。
 | 原文链接：http://wiki.9jnxlh.asia/arts/822643.Doc

原标题：golang 系统设计内部服务链路 trace 传递实现
简介：批量数据处理脚本编写技巧，编写脚本批量处理大量业务数据，循环处理、分批执行，提升数据处理效率。
 | 原文链接：http://wiki.9jnxlh.asia/arts/661602.Doc

原标题：golang 系统设计配置敏感信息加密存储
简介：开源项目本地运行排错完整清单，汇总开源项目拉取后运行失败各类问题，给出排查思路，快速解决本地启动异常。
 | 原文链接：http://wiki.9jnxlh.asia/arts/995546.Doc

原标题：Hands‑on：简易消息推送服务开发实践
简介：golang rsa 公钥加密私钥解密，rsa 非对称加密，大文件分块加密，处理非对称加密长度限制。
 | 原文链接：http://wiki.9jnxlh.asia/arts/026168.Doc

原标题：调优方案：Docker容器内核参数性能调优
简介：开源项目构建失败排查步骤，梳理构建报错排查流程，从依赖、网络、权限、脚本多角度定位项目构建失败原因。
 | 原文链接：http://wiki.9jnxlh.asia/arts/633513.Doc

原标题：css 动画性能优化 GPU 加速
简介：前端静态缓存更新生效处理，修改静态资源版本标识，处理浏览器强缓存，让更新资源生效。
 | 原文链接：http://wiki.9jnxlh.asia/arts/878784.Doc

原标题：golang 系统设计数据库扩容几种方式
简介：golang http cookie jar 会话处理，客户端 cookie jar 自动管理 cookie，处理登录态会话。
 | 原文链接：http://wiki.9jnxlh.asia/arts/359851.Doc

原标题：安全实践：防止JSON解析漏洞恶意payload
简介：golang 速率限制令牌桶实现，Go 实现令牌桶限流算法，可复用限流器，控制业务调用速率。
 | 原文链接：http://wiki.9jnxlh.asia/arts/836988.Doc

原标题：golang mysql 分表自增 id 方案
简介：nodejs 内存溢出问题排查修复，Node.js 程序 OOM 排查流程，定位内存泄露，调整内存限制修复崩溃。
 | 原文链接：http://wiki.9jnxlh.asia/arts/709492.Doc

原标题：架构笔记：WebSocket大规模连接服务架构
简介：golang gorm 索引设置与优化技巧，定义数据库索引，理解索引生效条件，避免索引失效慢查询。
 | 原文链接：http://wiki.9jnxlh.asia/arts/194691.Doc

原标题：静态博客部署 GitHub Pages 教程
简介：Git LFS 大文件推送失败解决，配置 Git LFS，处理仓库大文件，解决大文件推送报错推送失败。
 | 原文链接：http://wiki.9jnxlh.asia/arts/159632.Doc

原标题：限流规则误拦截正常请求修复
简介：golang 错误栈捕获打印方案，捕获错误完整调用堆栈，线上日志输出堆栈，快速定位错误发生代码位置。
 | 原文链接：http://wiki.9jnxlh.asia/arts/186706.Doc

原标题：golang redis 五种数据结构实战
简介：golang clickhouse go 客户端数据写入，clickhouse‑go 客户端写入查询，海量时序数据分析业务。
 | 原文链接：http://wiki.9jnxlh.asia/arts/024123.Doc

原标题：开发记录：实现完整用户登录鉴权业务模块
简介：Nginx 缓冲区调优大文件上传，调大 Nginx 请求缓冲区，支持客户端上传大体积文件，避免上传被截断。
 | 原文链接：http://wiki.9jnxlh.asia/arts/185261.Doc

三、实战开发｜Practice
原标题：golang 分页查询封装通用工具
简介：文件句柄耗尽资源泄露处理，定位文件句柄泄露，修复文件忘记关闭问题，解决句柄耗尽服务报错。
 | 原文链接：http://wiki.9jnxlh.asia/arts/201702.Doc

原标题：golang 系统设计 hot‑reload 热重载 go 开发工具
简介：golang race 检测器性能开销，race 检测器有性能损耗，只用于测试环境，禁止生产开启 race。
 | 原文链接：http://wiki.9jnxlh.asia/arts/312401.Doc

原标题：golang 系统设计数据库迁移工具 go‑migrate 实操
简介：提交第一个开源 PR 完整流程，Fork 项目、修改代码、提交 Pull Request，讲解 PR 规范，提升合并通过率。
 | 原文链接：http://wiki.9jnxlh.asia/arts/501652.Doc

原标题：踩坑：大报文传输，RPC消息超过大小限制
简介：短信服务封装失败自动重试，封装短信发送组件，处理发送失败自动重试，兼容多短信服务商。
 | 原文链接：http://wiki.9jnxlh.asia/arts/817336.Doc

原标题：性能笔记：压测如何定位真实系统瓶颈
简介：Git 代码冲突正确处理方式，讲解冲突产生场景，演示冲突文件修改，正确合并代码，防止代码丢失。
 | 原文链接：http://wiki.9jnxlh.asia/arts/598640.Doc

原标题：实战项目：容器资源限制配置压力测试实践
简介：golang bcrypt 密码哈希加密存储，bcrypt 做用户密码哈希，加盐存储密码，保障用户密码安全。
 | 原文链接：http://wiki.9jnxlh.asia/arts/261921.Doc

原标题：一次数据库死锁现场分析与解决方案记录
简介：程序预加载加快服务启动速度，把高频使用资源提前预加载，减少请求阶段初始化，加快服务启动。
 | 原文链接：http://wiki.9jnxlh.asia/arts/416093.Doc

原标题：golang 优雅停机服务关闭实现
简介：golang 重试退避机制代码实现，Go 实现请求重试与指数退避，处理临时故障，提升调用稳定性。
 | 原文链接：http://wiki.9jnxlh.asia/arts/337084.Doc

原标题：设计思考：分布式锁选型、风险、业务约束
简介：golang os 文件权限 mode，os.FileMode 文件权限，读写执行权限位，跨平台权限注意事项。
 | 原文链接：http://wiki.9jnxlh.asia/arts/045706.Doc

原标题：golang redis 缓存雪崩完整处理
简介：DNS 解析异常第三方调用故障，排查 DNS 解析故障，修复域名解析，恢复第三方接口网络调用。
 | 原文链接：http://wiki.9jnxlh.asia/arts/810331.Doc

原标题：多实例部署 Session 共享方案
简介：golang 反向代理 http 服务开发，手写简易 http 反向代理，转发请求，修改请求头响应头。
 | 原文链接：http://wiki.9jnxlh.asia/arts/089579.Doc

原标题：golang 系统设计缓存 key 命名规范最佳实践
简介：手写简易 ORM 理解对象映射，手写极简 ORM 示例，理解对象与数据库表字段映射底层原理。
 | 原文链接：http://wiki.9jnxlh.asia/arts/881250.Doc

原标题：排错：对象存储跨域配置不生效前端上传失败
简介：golang 图片处理 go 图片裁剪压缩，golang 图像处理库，图片缩放裁剪水印，服务端图片处理。
 | 原文链接：http://wiki.9jnxlh.asia/arts/665075.Doc

原标题：代码模块化组件化拆分思路
简介：无用对象回收抑制内存上涨，优化对象生命周期，及时释放不再使用对象，抑制内存持续不断增长。
 | 原文链接：http://wiki.9jnxlh.asia/arts/021867.Doc

原标题：配置与镜像分离防止信息泄露
简介：golang tar gz 压缩解压处理，tar.gz 归档压缩解压，服务端日志备份、文件打包场景使用。
 | 原文链接：http://wiki.9jnxlh.asia/arts/530240.Doc

原标题：Issue：Docker网络模式选择错误容器互通失败
简介：golang contract 契约测试微服务，微服务契约测试，保证接口变更不破坏调用方，提前发现兼容性问题。
 | 原文链接：http://wiki.9jnxlh.asia/arts/187564.Doc

原标题：golang redis bitmap 位图统计实现
简介：golang go 调用动态链接库 so 文件，go 加载 so 动态库调用函数，复用编译好的 C 动态库。
 | 原文链接：http://wiki.9jnxlh.asia/arts/365527.Doc

原标题：运维笔记：线上服务健康检查脚本编写
简介：golang go cover 覆盖率报告生成，go test‑cover 生成测试覆盖率，html 可视化查看未覆盖代码行。
 | 原文链接：http://wiki.9jnxlh.asia/arts/651938.Doc

原标题：架构复盘：数据库索引架构设计原则与边界
简介：golang go 项目安全检查漏洞扫描，扫描 go 项目依赖漏洞，代码安全审计，规避安全风险。
 | 原文链接：http://wiki.9jnxlh.asia/arts/380206.Doc

原标题：golang 系统设计短链接服务实现思路
简介：GitHub 项目提交推送完整流程讲解，从仓库初始化到提交推送远程仓库，梳理全流程细节，避开新手高频错误。
 | 原文链接：http://wiki.9jnxlh.asia/arts/016230.Doc

原标题：golang redis pipeline 原子性说明
简介：golang interface 接口使用避坑，interface 判 nil 坑点，理解接口底层结构，避免判空逻辑失效。
 | 原文链接：http://wiki.9jnxlh.asia/arts/665360.Doc

原标题：重复提交幂等防护再次讲解
简介：golang net/url 路径拼接处理，url.ParseRequestURI 处理请求 url，正确拼接 url 路径避免拼接错误。
 | 原文链接：http://wiki.9jnxlh.asia/arts/426055.Doc

原标题：golang 系统设计数据脱敏架构实现
简介：OAuth2 第三方登录服务搭建，搭建 OAuth2 服务，支持第三方账号登录，实现授权登录能力。
 | 原文链接：http://wiki.9jnxlh.asia/arts/896068.Doc

原标题：调优方案：Nginx性能参数调优高并发配置
简介：服务启动依赖顺序配置正确，配置服务启动依赖关系，保证依赖服务就绪之后再启动当前业务服务。
 | 原文链接：http://wiki.9jnxlh.asia/arts/898081.Doc

原标题：golang 重试退避机制代码实现
简介：golang http body 必须关闭的重要性，无论成功失败必须关闭 request.Body，否则连接无法复用泄漏。
 | 原文链接：http://wiki.9jnxlh.asia/arts/122365.Doc

原标题：性能笔记：压测如何定位真实系统瓶颈
简介：golang go 错误包装 fmt.Errorf % w，使用 % w 包装错误，支持 errors.Is errors.As 判断错误类型。
 | 原文链接：http://wiki.9jnxlh.asia/arts/759969.Doc

原标题：项目语义化版本号规范管理
简介：golang grpc 负载均衡客户端实现，grpc 客户端负载均衡，轮询随机权重，分发请求到多个服务实例。
 | 原文链接：http://wiki.9jnxlh.asia/arts/721239.Doc

原标题：开源实践：开源项目本地调试构建排坑经验
简介：golang go cover 覆盖率报告生成，go test‑cover 生成测试覆盖率，html 可视化查看未覆盖代码行。
 | 原文链接：http://wiki.9jnxlh.asia/arts/926722.Doc

原标题：坑点：Git工作区换行符CRLF/LF跨平台坑
简介：nestjs 权限守卫鉴权实现方案，使用 Nest 守卫实现接口鉴权，角色权限控制，拦截未授权接口访问。
 | 原文链接：http://wiki.9jnxlh.asia/arts/721199.Doc

原标题：排错：本地[localhost](https://localhost)可以，127001访问失败
简介：golang 错误栈捕获打印方案，捕获错误完整调用堆栈，线上日志输出堆栈，快速定位错误发生代码位置。
 | 原文链接：http://wiki.9jnxlh.asia/arts/861430.Doc

原标题：AI实践：大模型生成测试用例实践与校验
简介：golang 系统调用跟踪 strace 排查 go 程序，strace 跟踪系统调用，定位文件网络 IO 慢的底层原因。
 | 原文链接：http://wiki.9jnxlh.asia/arts/509259.Doc

原标题：golang 系统设计缓存 key 命名规范最佳实践
简介：golang go 应用内存使用优化手段，减少对象分配，复用对象，降低 GC 压力，减少 GC 停顿时间。
 | 原文链接：http://wiki.9jnxlh.asia/arts/346192.Doc

原标题：安全复盘：环境变量密钥泄露风险与防护
简介：游标分页大数据查询性能提升，使用游标分页替代偏移分页，解决大数据 offset 分页性能越来越差问题。
 | 原文链接：http://wiki.9jnxlh.asia/arts/166076.Doc

原标题：实战：Redis管道批量操作性能优化实践
简介：golang 配置文件多格式兼容加载，同时支持 yaml toml json 多种格式配置文件，灵活适配不同部署环境。
 | 原文链接：http://wiki.9jnxlh.asia/arts/442214.Doc

原标题：实践：多配置文件合并加载组件实现
简介：消息队列重复消费业务处理，实现消息消费幂等，处理重复投递消息，保证多次消费业务结果一致。
 | 原文链接：http://wiki.9jnxlh.asia/arts/125042.Doc

原标题：golang 系统设计数据库慢查询治理方案
简介：golang base64 大文件流式编解码，大文件流式 base64 转换，不用一次性加载全部文件进入内存。
 | 原文链接：http://wiki.9jnxlh.asia/arts/459956.Doc

原标题：服务器 Swap 关闭提升响应速度
简介：nodejs 信号处理优雅关闭服务，监听系统信号，执行资源清理，实现 Node 服务优雅停机，拒绝粗暴杀死进程。
 | 原文链接：http://wiki.9jnxlh.asia/arts/075921.Doc

原标题：golang 优雅处理数据库事务
简介：golang 模板函数自定义拓展，自定义 template 模板函数，在 html 模板调用自定义逻辑处理数据。
 | 原文链接：http://wiki.9jnxlh.asia/arts/080034.Doc

原标题：Architecture：对象存储接入业务整体架构
简介：golang json omitempty 零值坑，omitempty 会忽略零值，区分业务是否需要输出零值字段。
 | 原文链接：http://wiki.9jnxlh.asia/arts/888343.Doc

原标题：golang 系统设计第三方接口调用封装思路
简介：golang gin 参数绑定 query form json，掌握 Gin 多种参数绑定方式，适配不同请求格式参数读取。
 | 原文链接：http://wiki.9jnxlh.asia/arts/414631.Doc

四、架构设计｜Architecture
原标题：实战项目：实现分布式任务调度最小原型
简介：Fork 开源项目同步上游代码，Fork 开源仓库之后，配置上游源，同步官方最新代码，保持代码版本对齐。
 | 原文链接：http://wiki.9jnxlh.asia/arts/282676.Doc

原标题：golang es 聚合统计查询实现
简介：golang os 环境变量读取设置，os.Getenv os.Setenv os.Unsetenv 读写环境变量，环境变量多值处理。
 | 原文链接：http://wiki.9jnxlh.asia/arts/536813.Doc

原标题：WebSocket 双向通信 demo 开发
简介：golang grpc 拦截器开发鉴权日志，开发 grpc 服务端拦截器，统一做鉴权、日志打印、异常捕获处理。
 | 原文链接：http://wiki.9jnxlh.asia/arts/631997.Doc

原标题：Practice：实现请求大小限制中间件防护大报文
简介：本地运行正常线上报错排查，对比本地与线上环境差异，从配置、系统版本、文件权限定位线上独有的 bug。
 | 原文链接：http://wiki.9jnxlh.asia/arts/446519.Doc

原标题：golang 系统设计代码安全审计简单思路
简介：前端错误监控上报系统搭建，搭建前端错误监控，捕获页面 JS 错误，上报后端，快速发现线上页面 bug。
 | 原文链接：http://wiki.9jnxlh.asia/arts/053294.Doc

原标题：Troubleshoot：CPU调度频繁上下文切换性能下降
简介：golang 命令行参数解析开发，解析命令行入参，开发自定义 CLI 程序，读取启动参数配置服务。
 | 原文链接：http://wiki.9jnxlh.asia/arts/932472.Doc

原标题：架构复盘：供应链安全架构依赖包风险治理
简介：golang 静态编译缩小镜像体积，Go 程序静态编译，不依赖系统库，产出单二进制文件，缩小镜像。
 | 原文链接：http://wiki.9jnxlh.asia/arts/539158.Doc

原标题：排错：反向代理后获取真实IP全部变成内网IP
简介：nodejs 单元测试 jest 实操教程，Jest 单元测试实操，编写测试用例，mock 依赖，验证业务逻辑正确性。
 | 原文链接：http://wiki.9jnxlh.asia/arts/978666.Doc

原标题：golang docker 基础命令实操汇总
简介：前端防抖节流高频事件处理，封装防抖节流工具，处理滚动、输入框输入等高频触发事件减少执行次数。
 | 原文链接：http://wiki.9jnxlh.asia/arts/311039.Doc

原标题：架构复盘：系统扩容缩容架构无状态优先原则
简介：特殊输入字符过滤解析防护，过滤用户输入特殊字符，防止解析报错，规避恶意字符带来业务异常。
 | 原文链接：http://wiki.9jnxlh.asia/arts/719339.Doc

原标题：复盘总结：微服务改造踩坑经验总结记录
简介：golang GC 频繁 STW 停顿优化，减少小对象分配，调整 GOGC，降低 GC 停顿对接口延迟影响。
 | 原文链接：http://wiki.9jnxlh.asia/arts/376777.Doc

原标题：HTTPS 证书过期更新操作
简介：包管理器依赖缓存清理，清理本地依赖缓存，解决缓存旧包引发问题，拉取最新版本依赖包。
 | 原文链接：http://wiki.9jnxlh.asia/arts/163079.Doc

原标题：记一次分库分表路由计算错误数据写入错误分片
简介：服务启动依赖顺序配置正确，配置服务启动依赖关系，保证依赖服务就绪之后再启动当前业务服务。
 | 原文链接：http://wiki.9jnxlh.asia/arts/074906.Doc

原标题：golang 系统设计最小权限原则落地实践
简介：golang socket 文件描述符继承重启，父进程传递 listener fd 给子进程，实现 go 程序零停机热重启。
 | 原文链接：http://wiki.9jnxlh.asia/arts/721114.Doc

原标题：golang 系统设计监控大盘故障快速定位思路
简介：包管理器依赖缓存清理，清理本地依赖缓存，解决缓存旧包引发问题，拉取最新版本依赖包。
 | 原文链接：http://wiki.9jnxlh.asia/arts/855392.Doc

原标题：预编译 SQL 防注入实现
简介：时间精度统一业务判断修复，统一业务使用时间戳精度，毫秒秒区分清楚，修复时间判断逻辑错误。
 | 原文链接：http://wiki.9jnxlh.asia/arts/851841.Doc

原标题：golang 系统设计开源项目依赖版本升级维护
简介：CLI 工具进度条交互效果开发，在命令行工具增加进度条展示，直观反馈任务执行进度，优化命令行体验。
 | 原文链接：http://wiki.9jnxlh.asia/arts/042446.Doc

原标题：项目依赖安全扫描漏洞防范
简介：golang go 包循环导入报错解决，A 导入 B B 导入 A，循环导入报错，重构代码拆分包消除循环依赖。
 | 原文链接：http://wiki.9jnxlh.asia/arts/455573.Doc

?
