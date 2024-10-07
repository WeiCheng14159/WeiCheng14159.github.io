---
title: "Real-time Wideband Software-defined Radio with Python Programmability based on RFSoC"
collection: publications
permalink: /publication/SPEAR_demo
excerpt: 'Real-time Wideband Software-defined Radio with Python Programmability based on RFSoC'
date: 2024-11-18
venue: 'ACM MobiCom’24'
paperurl: 'https://doi.org/10.1145/3636534.3698855'
---
## Abstract
Next-generation wireless networks necessitate large signal bandwidth to support the growing demands of high data rates, which poses significant challenges in the design of real-time radio platforms. We demonstrate SPEAR, a real-time wideband software-defined radio (SDR) utilizing the Xilinx RFSoC ZCU216 evaluation board. SPEAR leverages a customized “Streaming Direct Memory Access (DMA)” IP
to address the latency issues associated with DMA control, thereby enabling high bandwidth data streaming in real-time. It also features a Python-based hardware configuration tool and signal processing framework incorporating an OFDM-based Physical layer. We showcase a real-time data link using the direct RF radio architecture between two RFSoC ZCU216 boards, achieving an error vector magnitude (EVM) of 3.2% for 256QAM across a bandwidth of 1.25 GHz.

[Download pdf from IEEE](https://doi.org/10.1145/3636534.3698855)

[Download pdf from this site](http://WeiCheng14159.github.io/files/publications/SPEAR_demo.pdf)

[Github](https://github.com/functions-lab/SPEAR)

```bibtex
@inproceedings{cheng2024real,
  author    = {Cheng, Wei and Gao, Zhihui and Chen, Tingjun},
  title     = {% raw %}{{Real}-{time} {Wideband} {Software}-{defined} {Radio} with {Python} {Programmability} based on {RFSoC}}{% endraw %},
  booktitle = {% raw %}{Proc. {ACM} {MobiCom'24}}{% endraw %},
  year      = {2024},
}