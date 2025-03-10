# 🎮 Awesome Remote Sensing Image-Text Retrieval | Remote Sensing Cross-model Retrieval | Remote Sensing Vision-Lanuage Models
## 🧭 Guideline
A Benchmark and Awesome Collection of Methods for **Remote Sensing Image-Text Retrieval (RSITR) ｜ Remote Sensing Cross-model Retrieval (RSCMR)** from the Internet, if there are any omissions, please contact me [jiancheng.pan.plus@gmail.com](https://jianchengpan.space/email.html).

<!-- 🤝 If you want to join **Remote Sensing Vision-Language Models (RSVLMs)**, you can click [Slack Group](https://join.slack.com/t/slack-nws5068/shared_invite/zt-1zpu3xt85-m8I3kVCp4qxAA1r1bDmKmQ). -->

- [🎮 Awesome Remote Sensing Image-Text Retrieval | Remote Sensing Cross-model Retrieval | Remote Sensing Vision-Lanuage Models](#-awesome-remote-sensing-image-text-retrieval--remote-sensing-cross-model-retrieval--remote-sensing-vision-lanuage-models)
  - [🧭 Guideline](#-guideline)
  - [💻 News](#-news)
  - [📊 Remote Sensing Captions Dataset](#-remote-sensing-captions-dataset)
  - [🆚 RSITR | RSCMR Benchmark](#-rsitr--rscmr-benchmark)
  - [📖 RSITR | RSCMR Method](#-rsitr--rscmr-method)
    - [Open-Domain Method](#open-domain-method)
    - [Closed-Domain Method](#closed-domain-method)
    - [Hashing Method](#hashing-method)

## 💻 News
> Record the major news of RSVLMs community.
- **2023/12/20**: SkyScript - A comprehensive vision-language dataset for remote sensing images covering 29K distinct semantic tags (AAAI 2024)  
  [[📝 Paper]](https://arxiv.org/abs/2312.12856) | [[📂 GitHub]](https://github.com/wangzhecheng/SkyScript)  
- **2023/11/24**: GeoChat - Grounded Large Vision-Language Model for Remote Sensing  
  [[📝 Paper]](https://arxiv.org/abs/2311.15826)  
- **2023/06/20**: RS5M - A dataset with 5M+ image-text pairs for remote sensing  
  [[📂 GitHub]](https://github.com/om-ai-lab/RS5M)  
- **2023/06/19**: RemoteCLIP - The first vision-language foundation model for remote sensing  
  [[📂 GitHub]](https://github.com/ChenDelong1999/RemoteCLIP)  

## 📊 Remote Sensing Captions Dataset
> Collect the more popular image-text pairs datasets on remote sensing, and welcome contact for additions if there are more.

| Dataset Name                                                         | No. of images | Image Resolution      | Vision-Lanuage Model |
| ------------------------------------------------------------ | ---------- | --------------- | ------------------------------------------------------------ |
| [UCM-Captions](https://github.com/201528014227051/RSICD_optimal) | 613        | 256 × 256       | - |
| [Sydney-Captions](https://github.com/201528014227051/RSICD_optimal) | 2,100      | 500 × 500       | - |
| [RSICD](https://github.com/201528014227051/RSICD_optimal)    | 10,921     | 224 × 224       | - |
| [RSITMD](https://github.com/xiaoyuan1996/AMFMN/tree/master/RSITMD) | 4,743      | 256 × 256       | - |
| [NWPU-Captions](https://github.com/HaiyanHuang98/NWPU-Captions) | 31,500     | 256 × 256       | - |
| [RET-3, SEG-4, DET-10](https://github.com/ChenDelong1999/RemoteCLIP) | -     | All Resolutions       | [RemoteCLIP](https://github.com/ChenDelong1999/RemoteCLIP) |
| [RS5M](https://github.com/om-ai-lab/RS5M)                    | 5 million+ | All Resolutions | [GeoRSCLIP](https://huggingface.co/Zilun/GeoRSCLIP) |
| [SkyScript](https://github.com/wangzhecheng/SkyScript)                    | 5.2 million+ | All Resolutions | [SkyCLIP](https://github.com/wangzhecheng/SkyScript) |

## 🆚 RSITR | RSCMR Benchmark
> Welcome to add more RSITR | RSCMR methods.


📌 **Cross-Modal Retrieval on RSICD**:  
🔗 [[Papers with Code]](https://paperswithcode.com/sota/cross-modal-retrieval-on-rsicd)  

📌 **Cross-Modal Retrieval on RSITMD**:  
🔗 [[Papers with Code]](https://paperswithcode.com/sota/cross-modal-retrieval-on-rsitmd)  


## 📖 RSITR | RSCMR Method
> 🔒 Closed-Domain Method: Training and testing on a single dataset.
> 
> 🌍 Open-Domain Method: Using extra datasets for pre-training to gain more inter-domain knowledge.
>
> ⚡️ Hashing Method: Efficient retrieval on large-scale datasets becomes feasible.
### 🌍 Open-Domain Method
- [AAAI 2024] | **SkyScript: A Large and Semantically Diverse Vision-Language Dataset for Remote Sensing** |  [[📝 Paper]](https://arxiv.org/abs/2312.12856) [[📂 GitHub]](https://github.com/wangzhecheng/SkyScript)
  - Zhecheng Wang, Rajanie Prabha, Tianyuan Huang, Jiajun Wu, Ram Rajagopal

- [TGRS 2023] | **RemoteCLIP: A Vision Language Foundation Model for Remote Sensing** | [[📝 Paper]](https://arxiv.org/pdf/2306.11029) [[📂 GitHub]](https://github.com/ChenDelong1999/RemoteCLIP)
  - Fan Liu, Delong Chen, Zhan-Rong Guan, Xiaocong Zhou, Jiale Zhu, Jun Zhou
- [TGRS 2023] | **RS5M: A Large Scale Vision-Language Dataset for Remote Sensing Vision-Language Foundation Model** | [[📝 Paper]](https://arxiv.org/abs/2306.11300) [[📂 GitHub]](https://github.com/om-ai-lab/RS5M)
  - Zilun Zhang, Tiancheng Zhao, Yulong Guo, Jianwei Yin.

- [ArXiv 2023] | **RSGPT: A Remote Sensing Vision Language Model and Benchmark** | [[📝 Paper]](https://arxiv.org/pdf/2307.15266)
  - Yuan Hu, Jianlong Yuan, Congcong Wen, Xiaonan Lu, Xiang Li.

- [TGRS 2023] | **Parameter-Efficient Transfer Learning for Remote Sensing Image–Text Retrieval** | [[📝 Paper]](https://doi.org/10.1109/TGRS.2023.3308969)
  - Yuan Yuan, Yangfan Zhan, Zhitong Xiong.
### 🔒 Closed-Domain Method
- [ACMMM 2023] | **A Prior Instruction Representation Framework for Remote Sensing Image-text Retrieval** |  [[📝 Paper]](https://dl.acm.org/doi/10.1145/3581783.3612374) [[📂 GitHub]](https://github.com/jaychempan/PIR)
  - Jiancheng Pan, Qing Ma, Cong Bai.

- [TGRS 2023] | **Direction-Oriented Visual-semantic Embedding Model for Remote Sensing Image-text Retrieval** |  [[📝 Paper]](https://arxiv.org/abs/2310.08276)
  - Jiancheng Pan, Qing Ma, Cong Bai.

- [Sensors 2023] | **A Fine-Grained Semantic Alignment Method Specific to Aggregate Multi-Scale Information for Cross-Modal Remote Sensing Image Retrieval** |  [[📝 Paper]](https://doi.org/10.3390/s23208437)
  - Fuzhong Zheng, Xu Wang, Luyao Wang, Xiong Zhang, Hongze Zhu, Long Wang, Haisu Zhang.

- [Remote Sensing 2023] | **A Fusion Encoder with Multi-Task Guidance for Cross-Modal Text–Image Retrieval in Remote Sensing** |  [[📝 Paper]](https://www.mdpi.com/2072-4292/15/18/4637)
  - Xiong Zhang, Weipeng Li, Xu Wang, Luyao Wang, Fuzhong Zheng, Long Wang, Haisu Zhang.

- [IGARSS 2023] | **A Texture and Saliency Enhanced Image Learning Method For Cross-Modal Remote Sensing Image-Text Retrieval** |  [[📝 Paper]](https://doi.org/10.1109/IGARSS52108.2023.10282896)
  - Rui Yang, Di Zhang, Yanhe Guo, Shuang Wang.

- [IGARSS 2023] | **A Fast and Accurate Method for Remote Sensing Image-Text Retrieval Based On Large Model Knowledge Distillation** |  [[📝 Paper]](https://doi.org/10.1109/IGARSS52108.2023.10281578)
  - Yu Liao, Rui Yang, Tao Xie, Hantong Xing, Dou Quan, Shuang Wang, B. Hou.

- [TGRS 2023] | **Knowledge-Aided Momentum Contrastive Learning for Remote-Sensing Image Text Retrieval** |  [[📝 Paper]](https://doi.org/10.1109/TGRS.2023.3332317)
  - Zhong Ji, Changxu Meng, Yan Zhang, Yanwei Pang, Xuelong Li.

- [Mathematics 2023] | **An End-to-End Framework Based on Vision-Language Fusion for Remote Sensing Cross-Modal Text-Image Retrieval** | [[📝 Paper]](https://doi.org/10.3390/math11102279)
  - Liu He, Shuyan Liu, Ran An, Yudong Zhuo, Jian Tao.

- [TGRS 2023] **Hypersphere-based Remote Sensing Cross-Modal Text-Image Retrieval via Curriculum Learning** | [[📝 Paper]](https://ieeexplore.ieee.org/abstract/document/10261223/)
  - Weihang Zhang, Jihao Li, Shuoke Li, Jialiang Chen, Wenkai Zhang, Xin Gao, Xian Sun.

- [TGRS 2023] | **Interacting-Enhancing Feature Transformer for Cross-Modal Remote-Sensing Image and Text Retrieval** | [[📝 Paper]](https://doi.org/10.1109/TGRS.2023.3280546)
  - Xu Tang, Yijing Wang, Jingjing Ma, Xiangrong Zhang, F. Liu, Licheng Jiao.

- [ICMR 2023] | **Reducing Semantic Confusion: Scene-aware Aggregation Network for Remote Sensing Cross-modal Retrieval** | [[📝 Paper]](https://doi.org/10.1145/3591106.3592236) [[📂 GitHub]](https://github.com/jaychempan/SWAN-pytorch)
  - Jiancheng Pan, Qing Ma, Cong Bai.

- [CDCEO 2022] | **Knowledge-Aware Cross-Modal Text-Image Retrieval for Remote Sensing Images** | [[📝 Paper]](https://infoscience.epfl.ch/record/300085/files/Mi_2022.pdf)
  - Li Mi, Siran Li, Christel Chappuis, D. Tuia.

- [IGARSS 2022] | **A transformer-based cross-modal image-text retrieval method using feature decoupling and reconstruction** | [[📝 Paper]](https://ieeexplore.ieee.org/abstract/document/9883242/)
  - Huan Zhang, Yingzhi Sun, Yu Liao, Siyuan Xu, R. Yang, Shuang Wang, B. Hou, Licheng Jiao.

- [INT J APPL EARTH OBS 2022] | **MCRN: A Multi-source Cross-modal Retrieval Network for remote sensing** | [[📝 Paper]](https://www.sciencedirect.com/science/article/pii/S156984322200259X)
  - Zhiqiang Yuan, Wenkai Zhang, Changyuan Tian, Yongqiang Mao, Ruixue Zhou, Hongqi Wang, K. Fu, Xian Sun.
  
- [JSTARS 2022] | **Multilanguage Transformer for Improved Text to Remote Sensing Image Retrieval** | [[📝 Paper]](https://ieeexplore.ieee.org/iel7/4609443/9656571/09925582.pdf)
  - Mohamad Mahmoud Al Rahhal, Y. Bazi, Norah A. Alsharif, Laila Bashmal, N. Alajlan, F. Melgani.

- [Applied Sciences 2022] | **Contrasting Dual Transformer Architectures for Multi-Modal Remote Sensing Image Retrieval** | [[📝 Paper]](https://www.mdpi.com/2076-3417/13/1/282)
  - Mohamad Mahmoud Al Rahhal, M. Bencherif, Y. Bazi, Abdullah Alharbi, M. L. Mekhalfi.
  
- [TGRS 2022] | **Remote Sensing Cross-Modal Text-Image Retrieval Based on Global and Local Information** | [[📝 Paper]](https://arxiv.org/pdf/2204.09860) [[📂 GitHub]](https://github.com/xiaoyuan1996/GaLR)
  - Zhiqiang Yuan, Wenkai Zhang, Changyuan Tian, Xuee Rong, Zhengyuan Zhang, Hongqi Wang, K. Fu, Xian Sun.

- [TGRS 2021] | **A Lightweight Multi-Scale Crossmodal Text-Image Retrieval Method in Remote Sensing** | [[📝 Paper]](https://ieeexplore.ieee.org/abstract/document/9594840/)
  - Zhiqiang Yuan, Wenkai Zhang, Xuee Rong, Xuan Li, Jialiang Chen, Hongqi Wang, K. Fu, Xian Sun.

- [TGRS 2021] | **Exploring a Fine-Grained Multiscale Method for Cross-Modal Remote Sensing Image Retrieval** | [[📝 Paper]](https://ieeexplore.ieee.org/document/9437331) [[📂 GitHub]](https://github.com/xiaoyuan1996/AMFMN)
  - Zhiqiang Yuan, Wenkai Zhang, K. Fu, Xuan Li, Chubo Deng, Hongqi Wang, Xian Sun.

- [JSTARS 2021] | **A Deep Semantic Alignment Network for the Cross-Modal Image-Text Retrieval in Remote Sensing** | [[📝 Paper]](https://ieeexplore.ieee.org/iel7/4609443/4609444/09395191.pdf)
  - Qimin Cheng, Yuzhuo Zhou, Peng Fu, Yuan Xu, Liang Zhang.

- [LGRS 2021] | **Fusion-Based Correlation Learning Model for Cross-Modal Remote Sensing Image Retrieval** | [[📝 Paper]](https://ieeexplore.ieee.org/abstract/document/9628066/)
  - Yafei Lv, Wei Xiong, Xiaohan Zhang, Yaqi Cui.

- [Remote Sensing 2020] | **TextRS: Deep Bidirectional Triplet Network for Matching Text to Remote Sensing Images** | [[📝 Paper]](https://www.mdpi.com/2072-4292/12/3/405/pdf)
  - T. M. Ali, Y. Bazi, Mohamad Mahmoud Al Rahhal, M. L. Mekhalfi, Lalitha Rangarajan, M. Zuair.

### ⚡️ Hashing Method
- [JSTARS 2022] | **Remote Sensing Cross-Modal Retrieval by Deep Image-Voice Hashing** | [[📝 Paper]](https://doi.org/10.1109/JSTARS.2022.3216333)
  - Yichao Zhang, Xiangtao Zheng, Xiaoqiang Lu.


- [ArXiv 2022] | **Deep Unsupervised Contrastive Hashing for Large-Scale Cross-Modal Text-Image Retrieval in Remote Sensing** | [[📝 Paper]](https://arxiv.org/pdf/2201.08125)
  - Georgii Mikriukov, Mahdyar Ravanbakhsh, Beg&uuml;m Demir.

- [ICIP 2022] | **An Unsupervised Cross-Modal Hashing Method Robust to Noisy Training Image-Text Correspondences in Remote Sensing** | [[📝 Paper]](https://arxiv.org/pdf/2202.13117)
  - Georgii Mikriukov, Mahdyar Ravanbakhsh, Beg&uuml;m Demir.

