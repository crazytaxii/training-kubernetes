# Kubernetes-Administration

## Prefix

- 授课时长：
    - 上午：9:30 至 11:30
    - 下午：13:30 至 16:30
- Prerequisite
    - vim 基础操作 -- 编辑、修改、保存文件
    - 网络基础知识 -- 网段 cidr、vlan、vxlan、配置 linux 网卡等等
    - 基础的 linux 知识 -- 权限、文件系统、服务
    - systemd 的基础操作 -- 重启、关闭、启动、重载、查看 systemd 的服务

## Catalog

| Date | Time | Title | Content |
| ---- | ---- | ----- | ------- |
| 第 1 天 | 上午 | [Lesson 01：Linux 容器和 Docker]() | [什么是 Linux 容器]() |
| | | | [什么是 Docker]() |
| | | | [Docker 的网络模型]() |
| | | | [Docker 的存储模型]() |
| | | | [实验：Docker Quick Start]()  |
| | 下午 | [Lesson 02：Kubernetes 的基本概念]() | [Kubernetes（ K8S ）的起源和适用场景]() |
| | | | [YAML]() |
| | | | [Namespace & Quota]() |
| | | | [Pod / Deployment / ReplicaSet]() |
| | | | [实验：K8S Dashboard]() |
| | | | [实验：K8S 对象管理操作]() |
| | | | [DeamonSet & SetfulSet]() |
| | | [Lesson 03：K8S 的模块架构和部署]() | [Kubernetes 的模块架构]() |
| | | | [ETCD]() |
| | | | [静态 Pod]() |
| | | | [实验：K8S 的部署]() |
| 第 2 天 | 上午 | | [HA 部署方案]() |
| | | [Lesson 04：K8S 的认证和安全]() | [认证、鉴权和准入]() |
| | | | [网络安全]() |
| | | | [用户和角色]() |
| | | | [实验：添加用户 & 绑定角色]() |
| | | [Lesson 05：K8S 的调度]() | [Labels：标签](#) |
| | | | [Taints：污染标签 & Toleration：容忍标签](#) |
| | | | [Node Affinity：节点亲和 ](#) |
| | | | [Inter-Pod Affinity / Anti：Pod 的亲和 / 反亲和](#) |
| | | | [实验：Pod 调度](#) |
| | 下午 | [Lesson 06：K8S 的数据持久化]() | [ConfigMap & Secret](#) |
| | | | [PV / PVC](#) |
| | | | [Storage Class](#) |
| | | | [实验：ConfigMap / Secret / PV & PVC / StorageClass](#) |
| | | [Lesson 07：服务发布](#) | [Service](#) |
| | | | [实验：发布服务](#) |
| | | | [Ingress](#) |
| | | | [实验：对集群外发布服务](#) |
| | | [Lesson 08：其它]() | [监控、日志、排错](#) |
| | | | [HPA / CA / VA](#) |
| | | | [Federation](#) |
| | | | [CRD & Operator](#) |
| 第 3 天 | 上午 | [Lesson 09：CKA 考试讲解](#) | [考试注意事项](#) |
| | | | [模拟题讲解](#) |
| | 下午 | | [实验：做模拟题](#) |
