---
layout: homepage
---

## About Me

Welcome! I am a Researcher (Dec. 2022 - present) in the AI Framework & Data Tech. Lab, Huawei Hong Kong Research Center. Before I joined Huawei, I earned my Ph.D. degree in September 2022 at the [Department of Electrical and Electronic Engineering](https://www.eee.hku.hk/) (EEE), [The University of Hong Kong](https://www.hku.hk/), under the supervision of Prof. [Ngai Wong](https://www.eee.hku.hk/~nwong/) and Prof. [Graziano Chesi](https://www.eee.hku.hk/~chesi/). Prior to that, I received my B.S. degree in the [School of Mathematics and Statistics](http://maths.whu.edu.cn/Englishversion/) from [Wuhan University](https://en.whu.edu.cn/) in June 2018.

## Projects
<h4 style="margin:0 10px 0;">Data Curation: Pretrain and SFT Data Preparation for Large Text-to-Video Generation Models and the Design of Tag System for Multimodal Data</h4>
* **Institution**: AI Framework & Data Tech. Lab, Huawei Hong Kong Research Center.
* **Time**: Jul. 2024 - Present
* **Project Overview**:
  1. This work aims to boost the performance of Xiaoyi, who is Huawei’s AI agent. 
  2. For data preparation, the primary challenges are: (a) determining the proper ratio of data belonging to different categories, (b) maintaining the diversity of the data while making the semantics concentrated, and (c) improving the efficiency of data selection by utilizing less labor resources.
  3. For tag system design, the goal is to develop a system that can cover Xiaoyi’s application scenarios, while taking the correlation between different modal data into consideration.

<h4 style="margin:0 10px 0;">GTN-F: A General Tensor-Native Format Representation of Multimodal Data</h4>
* **Institution**: AI Framework & Data Tech. Lab, Huawei Hong Kong Research Center.
* **Time**: Jul. 2023 - Jul. 2024
* **Project Overview**: 
	1. 0-1 Technology & Research Innovation Project in Huawei. This project aims to solve the problems in large model scenarios like (a) the lack of unified data representation, (b) multiple copies are required due to multiple systems, and (c) difficulties in management and source tracing, thus improving data access and management efficiency.
	2. GTN-F can convert multi-modal data from different sources with heterogeneous structures into the general tensor format. Based on the chunk storage strategy, GTN-F supports using idx to quickly access all necessary information related to the same sample, improving the random-access efficiency by 2×. 
	3. GTN-F provides tensor query and materialized view loading functions to facilitate data filtering, and operation commands similar to git are provided to facilitate data version management.
<h4 style="margin:0 10px 0;">GTN: A General Tensor-Native Data Processing Framework</h4>
* **Institution**: AI Framework & Data Tech. Lab, Huawei Hong Kong Research Center.
* **Time**: Dec. 2022 - Jul. 2023
* **Project Overview**: 
	1. 0-1 Technology & Research Innovation Project in Huawei. This project aims to leverage tensor abstraction as the basis for automatic optimization and enable the compilation of the same code over heterogeneous hardware.  
	2. With GTN, the computation process of large-scale feature engineering tasks can be converted into Tensor plus Tensor Operators.
	3. By extensive experiments, it is verified that target tasks can be deployed on heterogeneous hardware to achieve acceleration optimization: compared with the common CPU baseline, the efficiency can be improved by 100× in 70% verification scenarios.


## Publications
<h4 style="margin:0 10px 0;">Journal</h4>
+ **Lin, R.** *, Li, C. *, Zhou, J., Huang, B., Ran, J., Wong, N. (2023). Lite it fly: An All-Deformable-Butterfly Network. Brief Paper in the IEEE Transactions on Neural Networks and Learning Systems (TNNLS). [[PDF](https://arxiv.org/abs/2311.08125)][[Codes](https://github.com/jasonli0707/All-DeBut)]
+ Mao, R., Wen, B., Arman, K., Zhao Y., Ann Franchesca, L., **Lin, R.**, Wong, N., Michael, N., Hu, X., Sheng, X., Catherine, G., John Paul, S. & Li, C. (2022). Experimentally Realized Memristive Memory Augmented Neural Network. Nature Communications. [[PDF](https://assets.researchsquare.com/files/rs-1821052/v1_covered.pdf?c=1657039003)]
+ Tao, C. *, **Lin, R.** *, Chen, Q., Zhang, Z., Luo, P., & Wong, N. (2022). FAT: Learning Low-Bitwidth Parametric Representation via Frequency-Aware Transformation. IEEE Transactions on Neural Networks and Learning Systems (TNNLS). [[PDF](https://arxiv.org/abs/2102.07444)][[Codes](https://github.com/ChaofanTao/FAT_Quantization)]
+ Xiao, X., Wang, J., **Lin, R.**, Hill, D. J., & Kang, C. (2020). Large-scale aggregation of prosumers toward strategic bidding in joint energy and regulation markets. Applied Energy, 271, 115159. [[PDF](https://www.sciencedirect.com/science/article/pii/S0306261920306711)]

<h4 style="margin:0 10px 0;">Conference</h4>
+ Li, C. *, **Lin, R.** *, Zhou, J., Lam, E., Wong, N. (2023). A Unifying Tensorview for Lightweight CNNs. In proceeding of the 15th International Conference on ASIC (ASICON'23). [[PDF](https://arxiv.org/abs/2312.09922)]
+ Huang, B., Tao, C., **Lin, R.**, Wong, N. (2023). Frequency Regularization for Improving Adversarial Robustness. In proceedings of the 2nd International Workshop on Practical Deep Learning in the Wild at the AAAI Conference on Artificial Intelligence (Workshop at AAAI'23) [[PDF](\files\pdf\AAAI2023_Workshop.pdf)][[Codes](https://github.com/Harr7y/FR)]
+ Ran, J., **Lin, R.**, Li, C., Zhou, J., Wong, N. (2023). PECAN: A Product-Quantized Content Addressable Memory Network. In proceedings of the Design, Automation and Test in Europe Conference (DATE'23) [[PDF](\files\pdf\PECAN.pdf)]
+ **Lin, R.**, Cong, C. & Wong, N. (2022). Coarse to Fine: Image Restoration Boosted by Multi-Scale Low-Rank Tensor Completion. In 2022 26th International Conference on Pattern Recognition (ICPR'22), IEEE.  [[PDF](\files\pdf\ICPR_2022_C2F.pdf)][[Codes](https://github.com/rlin27/C2FLRTC)][[Poster](\files\pdf\ICPR2022_ePoster.pdf)]
+ **Lin, R.** *, Ran, J. *, Chiu, K. H., Chesi, G. & Wong, N. * (2021). Deformable Butterfly: A Highly Structured and Sparse Linear Transform. In proceedings of the Advances in Neural Information Processing Systems (NeurIPS'21) [[PDF](\files\pdf\DeBut_final.pdf)][[Codes](https://github.com/rlin27/DeBut)][[Slides](\files\slides\DeBut_Slides.pdf)][[Poster](\files\slides\DeBut_Poster.pdf)]
+ **Lin, R.** *, Ran, J. *, Wang, D., Chiu, K. H., & Wong, N. (2021). EZCrop: Energy-Zoned Channels for Robust Output Pruning. In proceeding of the Winter Conference on Applications of Computer Vision (WACV'22). [[PDF](https://arxiv.org/abs/2105.03679)][[Codes](https://github.com/rlin27/EZCrop)][[Slides](\files\slides\EZCrop_Slides.pdf)][[Poster](\files\slides\EZCrop_Poster.pdf)]
+ Cheng, Y., **Lin, R.**, Zhen, P., Hou, T., ... & Wong, N. (2021). FASSST: Fast Attention Based Single-Stage Segmentation Net for Real-Time Instance Segmentation. In proceeding of the Winter Conference on Applications of Computer Vision (WACV'22). [[PDF](\files\pdf\FASSST.pdf)][[Slides](\files\slides\FASSST_Slides.pdf)][[Poster](\files\slides\FASSST_Poster.pdf)]
+ Ren, Y.*, **Lin, R.** *, Ran, J., Liu, C., Tao, C., Wang, Z., Li, C. & Wong, N *. (2021). BATMANN: A Binarized-All-Through Memory-Augmented Neural Network for Efficient In-Memory Computing. In proceeding of IEEE 14th International Conference on ASIC (ASICON'21). [[PDF](\files\pdf\ASICON2021__BATMANN.pdf)][[Codes](https://github.com/rlin27/BATMANN)][[Slides](\files\slides\BATMANN_Slides.pdf)]
+ Ran, J.*, **Lin, R.** *, So, H. K., Chesi, G. & Wong, N. (2021, January). Exploiting Elasticity in Tensor Ranks for Compressing Neural Networks. In 2020 25th International Conference on Pattern Recognition (ICPR'20) (pp. 9866-9873). IEEE. [[PDF](https://arxiv.org/abs/2105.04218)][[Codes](https://github.com/rlin27/NRMF)][[Slides](\files\slides\NRMF.pdf)]
+ **Lin, R.**, Ko, C. Y., He, Z., Chen, C., Cheng, Y., Yu, H., ... & Wong, N. (2020, November). HOTCAKE: Higher Order Tucker Articulated Kernels for Deeper CNN Compression. In 2020 IEEE 15th International Conference on Solid-State & Integrated Circuit Technology (ICSICT'20) (pp. 1-4). IEEE. [[PDF](https://arxiv.org/abs/2002.12663)][[Codes](https://github.com/rlin27/HOTCAKE)][[Slides](\files\slides\HOTCAKE.pdf)]
+ Ko, C. Y., **Lin, R.**, Li, S., & Wong, N. (2019). MiSC: mixed strategies crowdsourcing. Proceedings of the Twenty-Eighth International Joint Conference on Artificial Intelligence Main track (IJCAI'19). Pages 1394-1400. [[PDF](\files\pdf\MiSC.pdf)][[Codes](https://github.com/rlin27/MiSC)][[Slides](\files\slides\IJCAI_Pre_v4.pdf)]

\* Equal Authorship Statement

## Professional Activities
<h4 style="margin:0 10px 0;">Talks</h4>
+ An invited talk in Tsinghua University "[AI TIME](https://mp.weixin.qq.com/s/tqkOgA4G6ZwnoR7ecVGLPw)", Mar. 2022.
+ An invited seminar in AI Chip Center for Emerging Smart Systems [(ACCESS)](https://hkustcareers.ust.hk/ai-chip-center-for-emerging-smart-systems), Feb. 2022.
+ An invited lightning talk in IJCAI 2019 workshop “[Humanizing AI](https://www.humanizing-ai.com/hai-19.html)”, Aug. 2019.

<h4 style="margin:0 10px 0;">Teaching</h4>
+ **The University of Hong Kong.** MATH1853: Linear Algebra, Probability and Statistics (Tutor, Fall 2019, Fall 2020, Fall 2021)
+ **Wuhan University.** Advanced Algebra and Analytic Geometry (Tutor, Spring 2018)

<h4 style="margin:0 10px 0;">Duties</h4>
+ Member of Hong Kong Institution of Science [(HKIS)](http://www.science.org.hk/index.php?action=index) (Jul. 2023 - Present)
+ Conference reviewer of ICLR'24, NeurIPs'23, ICML'23, NeurIPs'22, ICML'22, CVPR'22, ICPR'22, CVPR'21, ICCV'21.
+ Part-time Research Assistant at the University of Hong Kong, dealing with additional projects, including my regular research tasks. (Jun. 2022 - Aug. 2022)
+ Contest Judge of [EDAthon'21](https://sites.google.com/view/ceda-hk/edathon-2021). (Aug. 2021)

## Personal
1. I value all my life moments, whether good or bad, depressing or joyful. I am big fan of journaling, and it is a habit I have maintained since I was in elementary school.
2. I am a BIG fan of the movie series [*The Hobbit*](https://en.wikipedia.org/wiki/The_Hobbit_(film_series)) and [*The Lord of the Rings*](https://en.wikipedia.org/wiki/The_Lord_of_the_Rings_(film_series)), which set in the [fictional world of Middle-earth](https://en.wikipedia.org/wiki/Middle-earth_in_film). In particular, [Aragorn](https://en.wikipedia.org/wiki/Aragorn) is my favorite role, brave, tenacity, and loyal to friends.
3. My leisure time is mainly spent on [Kindle](https://www.amazon.com/Kindle-eBooks/b?ie=UTF8&node=154606011), [Switch](https://www.nintendo.com/switch/) and working out. My favorite books so far are [*Ordinary World*](https://en.wikipedia.org/wiki/Ordinary_World_(novel)), and [*A Song of Ice and Fire*](https://en.wikipedia.org/wiki/A_Song_of_Ice_and_Fire). \\
    For switch, [*Spiritfarer*](https://www.nintendo.com/games/detail/spiritfarer-switch/) is the most touching game I have ever played, which is related to hospice care. My favourite game is [*The Legend of Zelda: Breath of the Wild*](https://www.zelda.com/breath-of-the-wild/), I like the feeling to take adventure on the mainland of Hyrule with my shining Master Sword and Master Cycle Zero. \\
    To maintain good physical and mental health, I do exercise regularly like hiking, and boxing, etc. I took [this photo](\files\fig\Victoria_Peak.jpg) when hiking Victoria Peak in May 2020.
4. I do **not** think I am a very talented researcher, but certain that I am a down-to-earth and a hardworking one :P.

The Chinese version of my CV can be downloaded [here](./files/pdf/LINRUI_CV_Chinese_2024.pdf).