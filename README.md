# mdss-platform
mssd-platform（micro service+spark+deep learning） 是一个基 于微服务模式构建的智能云服务平台。
该平台具有以下特点：
1.	模块化、轻耦合、无共享架构
2.	事件驱动架构
3.	基于命令查询职责分离模式（CQRS）
4.	DDD----Event Sourcing && Aggregates
使用基于Spring Boot、Netflix OSS、Docker等构建底层基础框架，为云业务应用开发中的配置管理、服务发现、断路器、智能路由、微代理、控制总线、全局锁、决策竞选、分布式会话和集群状态管理等操作，实现了基于Event Sourcing的最终一致性，提供了构建端到端微服务的最佳实践方案。
二期：
针对业务数据量的快速递增以及后期大规模海量数据，我们采用spark对数据进行处理和计算。
三期：
对于更高一级的deep learing,放在后期添加。

