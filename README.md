# ChatServer
本项目包含集群聊天服务器与客户端源码。服务器基于 muduo 库构建，能够适配 nginx 的 tcp 负载均衡环境，实现集群化部署，高效处理大量聊天请求。 在数据存储方面，运用 MySQL 存储用户信息、聊天记录等持久化数据，确保数据的稳定存储与高效查询。 借助 Redis 的发布 - 订阅模式实现实时消息推送。发布者将聊天消息发布到特定频道，订阅该频道的客户端可即时接收消息，从而实现高效、实时的聊天功能交互，打造一个高性能、高可用的集群聊天系统。
