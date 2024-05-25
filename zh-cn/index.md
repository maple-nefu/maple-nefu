---
layout: default
---

Language: [English](/), [简体中文](/zh-cn/)

# 枫叶数据集

枫叶数据集是一个入侵检测评估数据集，旨在增强异常基础入侵检测系统（IDS）和入侵预防系统（IPS）的性能和可靠性。随着网络攻击的日益复杂化，拥有一个可靠和最新的数据集对于测试和验证IDS和IPS解决方案至关重要。

## 背景

传统的评估数据集的攻击流量和利用方式，往往内容过时、流量多样性不足、攻击种类不足、特征不足，最重要的是 HTTPS/TLS
加密已经普及了。枫叶数据集提供了一个全面、现代的数据集来应对这些挑战，用于入侵检测研究。

## 兼容使用CIC-IDS数据集的代码

如果你的代码是用CIC-IDS数据集训练或者编写的，那么可以直接更换到枫叶数据集上。

枫叶数据集与您之前的工作兼容。可以直接使用 CICFlowMeter 生成 CSV 文件！
**无需重写代码或进行其他工作。**

## 数据集类别概览（包含内容）

- **内容**：数据集包含最新的常见攻击，类似于真实世界的网络流量（PCAP/PCAPNG 格式）。
- **流量分析**：使用 CICFlowMeter 进行的网络流量分析结果，标记基于时间戳、源和目标IP地址、端口、协议和攻击类型的流，存储在CSV文件中。
- **DDoS 攻击**：数据集包括 DDoS 攻击，这些在真实世界的网络流量中很常见。并且由于随机内容，数据集更加多样化。GET、POST、HEAD 和
  OPTIONS 是最常见的 HTTP 方法。
- **对每种服务细分的流量包和数据集** ：我们对于每种服务（HTTP、HTTPS、SMTP、IMAP、POP3、FTP、SSH、RESTful API、gRPC、WASM）都提供了数据集。
- **多样的流量** ：对于 ping 或者 HTTP，DDoS 的形式就多种多样，TCP，UDP, SYN 攻击，还有 ICMP 走私，我们的数据集都有覆盖到。
- **N-day 漏洞**：数据集包括 n-day 漏洞，如 OpenSSL 中存在的著名漏洞 HeartBleed，日后打算囊括更多的 CVE 漏洞。

## 更多功能即将推出

- DPDK、PF_RING 支持

> 如果您有任何问题或建议，请给我们反馈。

## 数据生成

我们通过模拟真实世界的网络流量中观察到的模式和模式来对流量进行配置。基于HTTP、HTTPS与SM3/4（中华人民共和国）、GOST（俄罗斯联邦）等，我们构建了用户的抽象行为。SSH、RESTful
API、gRPC、WASM，这些现代+协议及其各种实现等，都为这个数据集构建了内容。

## 我们提供的处理工具

> 在创建数据集的过程中，我们使用了许多自己开发的工具。  
> 它们是开源的，可以免费下载。  
> 一般来说，工具的仓库中都有教程。

|    工具     | 描述                        | 链接                                                              |
|:---------:|:--------------------------|:----------------------------------------------------------------|
| pcap2para | 从 pcap 文件中提取 HTTP Payload | [maple-nefu/pcap2para](https://github.com/maple-nefu/pcap2para) |
| 更多工具即将推出  | ...                       | ...                                                             |

* * *

## 引用我们的论文

```
Q. Li, B. Wang, X. Wen, Y. Chen, Cybersecurity situational awareness framework based on ResNet modeling
```

## 下载数据集

> [点击下载](https://maple.nefu.edu.cn/dataset)

## 联系我们

有任何问题或需要帮助，请随时与我们联系：

- 电子邮件：[maple@nefu.edu.cn](mailto:maple@nefu.edu.cn)
- GitHub：[github.com/maple-nefu](https://github.com/maple-nefu)
- QQ 群：631300176
- Telegram：[@maple_dataset](https://t.me/maple_dataset)
- Discord：[Maple Dataset](https://discord.gg/CkaAaaVKHm)

## 开源

[关于我们使用的开源项目](./open-source)

* * *