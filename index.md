---
layout: default
---

Language: [English](/index), [简体中文](/zh-cn/index)

# Maple Dataset

The Maple Dataset is an intrusion detection evaluation dataset aimed at enhancing the performance and reliability of
anomaly-based intrusion detection systems (IDS) and intrusion prevention systems (IPS). With the increasing
sophistication of network attacks, having a reliable and up-to-date dataset is crucial for testing and validating IDS
and IPS solutions.

## Background

Traditional evaluation datasets have shown inconsistencies and unreliability, mainly due to outdated content, lack of
traffic diversity, insufficient attack variety, anonymized packet payload data, and inadequate feature sets and
metadata. The Maple Dataset addresses these challenges by providing a comprehensive and contemporary dataset for
intrusion detection research.

## Compatible with Your Previous Work on CIC-IDS Dataset

The Maple Dataset is compatible with your previous work on the CIC-IDS 2017 dataset. It offers a more comprehensive and
more diverse dataset, which is ideal for your previous work. You can use CICFlowMeter to generate the CSV files as same
as you used before! **No more code or work is needed.**

## Dataset Category Overview (What's inside?)

- **Content**: The dataset contains benign and the most recent common attacks, resembling real-world network traffic
  (PCAP/PCAPNGs).
- **Traffic Analysis**: Results of network traffic analysis using CICFlowMeter with labeled flows based on timestamps,
  source and destination IPs, ports, protocols, and attack types are included in CSV files.
- **Feature Definition**: The dataset includes definitions for extracted features.
- **DDoS Attacks**: The dataset includes DDoS attacks, which are common in the real-world network traffic. And with
  random content, the dataset is more diverse. GET, POST, HEAD and OPTIONS are the most common HTTP methods.
- **N-day Vunerability**: The dataset includes n-day vulnerabilities, such as HeartBleed.
- **More scenarios**: Netflow in IoT devices, DNS tunneling, and more.

## More Features Coming Soon

- DPDK, PF_RING support
- More attacks and vulnerabilities
- More metadata for each flow

> Please feedback to us if you have any questions or suggestions.

## Data Generation

We profile the traffic by the mode and pattern we have observed in the real-world network traffic by mirroring the
dataflow. The abstract behaviors o8wf users based on HTTP, HTTPS with SM3/4 (People's Republic of China), GOST (Russian
Federation) and more. SSH, RESTful API, gRPC, WASM, these modern +protocols with various of implementations, and more
were constructed for this dataset.

## Middleware and Tools Available

> We have used a lot of tools developed by us during the creation of the dataset
> They are open-sourced and available to download.

|      Tool      | Description                         | Link                                                            |
|:--------------:|:------------------------------------|:----------------------------------------------------------------|
|   pcap2para    | extract http payload from pcap file | [maple-nefu/pcap2para](https://github.com/maple-nefu/pcap2para) |
| more is coming | ...                                 | ...                                                             |

---

## Cite Us!

```
Q. Li, B. Wang, X. Wen, Y. Chen, Cybersecurity situational awareness framework based on ResNet modeling
```

## Download Dataset

> [Download Here](https://maple.nefu.edu.cn/dataset)

## Contact Us

If you have any questions or need assistance, please feel free to contact us:

- Email: [maple@nefu.edu.cn](mailto:maple@nefu.edu.cn)
- GitHub: [github.com/maple-nefu](https://github.com/maple-nefu)
- QQ Group: 631300176
- Telegram: [@maple_dataset](https://t.me/maple_dataset)
- Discord: [Maple Dataset](https://discord.gg/CkaAaaVKHm)

## Open Source

[About Open Source Projects](./open-source)

---
