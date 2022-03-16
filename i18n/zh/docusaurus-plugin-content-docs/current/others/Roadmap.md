---
id: Roadmap
title: Roadmap
---

## 2022 Roadmap

### Manager

- 控制台
  - 优化页面 UI。
  - 项目增加 lint、test 等 Actions。
  - 增加开发文档。
  - 增加动态配置表单。
  - 增加 P2P 数据可视化。
  - 提供初始化用户安装页面
- 优化匹配 scheduler 集群规则。
- 增加应用级别安全限制和动态配置。
- 增加 Open API 接口鉴权。
- 无 CDN 场景下，预热功能实现。

### Scheduler

- 提高调度的稳定性以及效率，并收集可用数据。
- 实现基于机器学习的多场景自适应智能 P2P 节点调度算法及优化。
- 优化当前基于负载进行的调度策略，改为基于 Peer 带宽进行调度。
- 针对 Piece 下载优先级特征值进行调度。

### [WIP] Dfdaemon

### [WIP] CDN

### 文档

- 重构 d7y.io 官网，并完成 Dragonfly 2.0 项目文档。

### 其他

- perf-tests 仓库中提供压测解决方案。
- 提供 Kustomize 部署方案。
- 升级 Golang 1.18 版本，基于泛型重构已有代码。
