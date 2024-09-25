---
title: "SPEAR: Software-defined Python-EnhAnced RFSoC for Wideband Radio Applications"
collection: publications
permalink: /publication/SPEAR
excerpt: 'SPEAR is an SDR platform based on the Xilinx RFSoC ZCU216 evaluation board capable of supporting real-time streaming of signals with a bandwidth of up to 1.25 GHz employing the direct RF radio architecture.'
date: 2024-09-25
venue: 'ACM MobiCom’24 Workshop on Wireless Network Testbeds, Experimental Evaluation & CHaracterization (WiNTECH’24)'
paperurl: 'https://doi.org/10.1145/3636534.3697310'
---
## Abstract
Next-generation wireless systems utilize large signal bandwidths to meet the growing data rate demands of emerging applications and to provide enhanced resolution for wireless sensing and imaging. This poses significant challenges in the design of the underlying datapaths that carry and transfer signals across different domains, such as between memory and data converters in various software-defined radio (SDR) platforms. In this paper, we present the design and implementation of SPEAR, which is an SDR platform based on the Xilinx RFSoC ZCU216 evaluation board capable of supporting real-time streaming of signals with a bandwidth of up to 1.25 GHz employing the direct RF radio architecture. SPEAR features hardware-assisted direct memory access (DMA) control for real-time data streaming, and a Python-based hardware configuration tool and signal processing framework. Our experiments show that SPEAR can support a real-time bandwidth of up to 1.25 GHz for 256QAM modulation that satisfies the 3GPP error vector magnitude (EVM) requirement of 3.5%. SPEAR will be open-sourced.

[Download pdf from IEEE](https://doi.org/10.1145/3636534.3697310)

[Download pdf from this site](http://WeiCheng14159.github.io/files/publications/SPEAR.pdf)

[Github](https://github.com/functions-lab/SPEAR)

```
@inproceedings{
  title     = {SPEAR: Software-defined Python-EnhAnced RFSoC for Wideband Radio Applications},
  isbn      = {979-8-4007-0489-5/24/11},
  address   = {Washington D.C.},
  url       = {},
  doi       = {10.1145/3636534.3697310},
  booktitle = {Proc. {ACM} {WiNTECH’24}},
  author    = {Cheng, Wei and Gao, Zhihui and Chen, Tingjun},
  year      = {2024},
  pages     = {}
}
```