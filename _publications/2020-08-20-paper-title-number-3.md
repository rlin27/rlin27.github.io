---
title: "HOTCAKE: Higher Order Tucker Articulated Kernels for Deeper CNN Compression"
collection: publications
permalink: /publication/2020-08-20-paper-title-number-3
excerpt: 'A higher-order Tucker compression method.'
date: 2020-08-20
venue: 'ICSICT'
paperurl: 'https://arxiv.org/pdf/2002.12663.pdf'
citation: 'Lin, R., Ko, C. Y., He, Z., Chen, C., Cheng, Y., Yu, H., ... & Wong, N. (2020). HOTCAKE: Higher Order Tucker Articulated Kernels for Deeper CNN Compression. arXiv preprint arXiv:2002.12663.'
---
The emerging edge computing has promoted immense interests in compacting a neural network without sacrificing much accuracy. In this regard, low-rank tensor decomposition constitutes a powerful tool to compress convolutional neural networks (CNNs) by decomposing the 4-way kernel tensor into multi-stage smaller ones. Building on top of Tucker-2 decomposition, we propose a generalized Higher Order Tucker Articulated Kernels (HOTCAKE) scheme comprising four steps: input channel decomposition, guided Tucker rank selection, higher order Tucker decomposition and fine-tuning. By subjecting each CONV layer to HOTCAKE, a highly compressed CNN model with graceful accuracy trade-off is obtained. Experiments show HOTCAKE can compress even pre-compressed models and produce state-of-the-art lightweight networks.