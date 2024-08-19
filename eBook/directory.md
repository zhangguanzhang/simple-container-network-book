# 目录
- [前言](preface.md)

## 网络基础概念

- 第 1 章：网络基础
    - 1.1 [网络分层概念](01.01.md)
    - 1.2 [应用层以下的排查工具](01.02.md)
    - 1.3 [常见的应用层协议的排查工具](01.03.md)

## iptables

- 第 2 章：iptables
    - 2.1 [iptables 概念和一些基础知识](02.01.md)

## Docker 的网络

- 第 3 章：Docker 网络
    - 3.1 [默认的桥接网络](03.01.md)
    - 3.2 [none 和 host 网络](03.02.md)
    - 3.3 [container 网络](03.03.md)
    - 3.4 [Docker 容器跨节点通信](03.04.md)

## k8S 的网络

- 第 4 章：K8S 网络：
    - 4.1：[基础概念](04.01.md)
    - 4.2：[Service 工作原理](04.02.md)
        - 4.2.1: [iptables 模式](04.02.01.md)
        - 4.2.2: [ipvs 模式](04.02.02.md)
        - 4.2.3: [externalIPs 和坑](04.03.md)
    - 4.3：[NodePort 和 SNAT 以及 hostPort](04.03.md)
    - 4.4: [探针和一些坑](04.04.md)
    - 4.5: [CNI 和 cni-plugins](04.05.md)
    - 4.6: [CNI flannel 原理](04.06.md)
    - 4.7: [CNI calico 原理和基础使用](04.07.md)
    - 4.8: [K8S DNS 相关](04.08.md)
    - 4.9: [K8S 高可用和 SLB 相关](04.09.md)
    - 4.10: [Ingress Controller](04.10.md)

## 案例

欢迎投稿案例，尽量不要使用截图命令输出形式，只能是网络拓扑图相关

- 第 5 章：一些网络排查案例：
    - 5.1：[部署后 calico-kube-controllers 日志报错 dial tcp 10.96.0.1:443: i/o timeout](05.01.md)
