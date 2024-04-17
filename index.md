---
layout: default
---

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
as you used before! No more code or work is needed.

## Dataset Category Overview

- **Content**: The dataset contains benign and the most recent common attacks, resembling real-world network traffic
  (PCAP/PCAPNGs).
- **Traffic Analysis**: Results of network traffic analysis using CICFlowMeter with labeled flows based on timestamps,
  source and destination IPs, ports, protocols, and attack types are included in CSV files.
- **Feature Definition**: The dataset includes definitions for extracted features.

## More Features Coming Soon

- DPDK, PF_RING support

> Please feedback to us if you have any questions or suggestions.

## Data Generation

We profile the traffic by the mode and pattern we have observed in the real-world network traffic by mirroring the
dataflow. The abstract behaviors of users based on HTTP, HTTPS with SM3/4 (People's Republic of China), GOST (Russian
Federation) and more. SSH, RESTful API, gRPC, WASM, these modern protocols with various of implementations, and more
were constructed for this dataset.

## Middleware and Tools Available

> We have used a lot of tools developed by us during the creation of the dataset
> They are open-sourced and available to download.

|      Tool      | Description                         | Link                                                            |
|:--------------:|:------------------------------------|:----------------------------------------------------------------|
|   pcap2para    | extract http payload from pcap file | [maple-nefu/pcap2para](https://github.com/maple-nefu/pcap2para) |
| more is coming | ...                                 | ...                                                             |

* * *

## Cite Us!

```
[1] Alice, Bob IEEE Explore 114514 1919810
```

## Download Dataset

> Download link Here

## Contact Us

If you have any questions or need assistance, please feel free to contact us:

- Email: [maple@nefu.edu.cn](mailto:maple@nefu.edu.cn)
- GitHub: [github.com/maple-nefu](https://github.com/maple-nefu)
- QQ Group: 631300176
- Telegram: [@maple_dataset](https://t.me/maple_dataset)
- Discord: [Maple Dataset](https://discord.gg/CkaAaaVKHm)

## Open Source

[About Open Source Projects](./open-source)

* * *
