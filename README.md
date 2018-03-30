## 概述

通过接入基础联网SDK，客户端之间即可实现实时通信。如果游戏需要依赖服务端的逻辑判定和安全校验等功能，则可以使用 Matchvs 提供的 gameServer 框架。在 gameServer 里，开发者可以自定义游戏服务端逻辑。

## 特色

### 便捷开发

Matchvs 在 gameServer 框架里提供了与客户端 SDK 一致的流程。客户端的匹配、游戏过程在 gameServer 里可以实时接收，开发者可以自定义游戏开始机制以及游戏逻辑。gameServer 里支持给各个客户端广播消息或推送给指定客户端消息。

在开发过程中，开发者无需关注底层通信机制，也无需自己搭建复杂的服务器环境。Matchvs 框架提供了友好的本地调试方法，只需一行命令即可开启本地调试。开发者可以更专注于游戏逻辑本身。

### 简易部署

Matchvs 提供了云端一键部署功能：开发者只需在完成调试后将代码上传至指定仓库，然后在控制台点击启动服务即可。从代码上传至服务启动全流程不超过5分钟，极大地节省了开发时间和运维成本。

Matchvs 基于原生的 Kubernetes 提供了容器管理服务。每个 gameServer 都对应一个容器，可以进行弹性伸缩。gameServer 支持不中断业务持续更新：在更新代码后，重启服务即可。每个用户的gameServer资源相互隔离，不会互相影响。

更多使用详情请前往 Matchvs官网查看： http://www.matchvs.com/service?page=processgameServerJS
