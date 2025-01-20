# RSHazeDiff: A Unified Fourier-aware Diffusion Model for Remote Sensing lmage Dehazing (TITS2024)

[Jiamei Xiong](https://scholar.google.com/citations?user=-epzM98AAAAJ&hl=en), [Xuefeng Yan](https://scholar.google.com/citations?hl=en&user=C_sZsC0AAAAJ&view_op=list_works&sortby=pubdate), [Yongzhen Wang](https://scholar.google.com/citations?hl=en&user=fLeZQYkAAAAJ), Wei Zhao, [Xiao-Ping Zhang](https://scholar.google.ca/citations?hl=en&user=1fzb_z8AAAAJ&view_op=list_works&sortby=pubdate), [Mingqiang Wei](https://scholar.google.com/citations?user=TdrJj8MAAAAJ&hl=en&oi=ao)

[![paper](https://img.shields.io/badge/paper-TITS2024-blue)](https://ieeexplore.ieee.org/document/10747754)
[![arXiv](https://img.shields.io/badge/arXiv-2405.09083-red)](https://arxiv.org/abs/2405.09083)

#### News
- **Dec 20, 2023:** This repo is released. 
- **May 15, 2024:** Arxiv paper available.
- **Nov 8, 2024:** 🤗 Paper is accepted by IEEE TITS2024. 
- **Jan 17, 2025:** 🔈The code is available now, enjoy yourself!
- **Jan 20, 2025:** Updated README file with detailed instruciton.

<hr />

> **Abstract:** *Haze severely degrades the visual quality of remote sensing images and hampers the performance of road extraction, vehicle detection, and traffic flow monitoring. The emerging denoising diffusion probabilistic model (DDPM) exhibits the significant potential for dense haze removal with its strong generation ability. Since remote sensing images contain extensive small-scale texture structures, it is important to effectively restore image details from hazy images. However, current wisdom of DDPM fails to preserve image details and color fidelity well, limiting its dehazing capacity for remote sensing images. In this paper, we propose a novel unified Fourier-aware diffusion model for remote sensing image dehazing, termed RSHazeDiff. From a new perspective, RSHazeDiff explores the conditional DDPM to improve image quality in dense hazy scenarios, and it makes three key contributions. First, RSHazeDiff refines the training phase of diffusion process by performing noise estimation and reconstruction constraints in a coarse-to-fine fashion. Thus, it remedies the unpleasing results caused by the simple noise estimation constraint in DDPM. Second, by taking the frequency information as important prior knowledge during iterative sampling steps, RSHazeDiff can preserve more texture details and color fidelity in dehazed images. Third, we design a global compensated learning module to utilize the Fourier transform to capture the global dependency features of input images, which can effectively mitigate the effects of boundary artifacts when processing fixed-size patches. Experiments on both synthetic and real-world benchmarks validate the favorable performance of RSHazeDiff over state-of-the-art methods.* 
<hr />

## Network Architecture

<img src = "https://i.imgur.com/ulLoEig.png"> 

## Requirements:

Python 3.6 or above

Pytorch 1.10.2

CUDA 11.0

## Train &Test

The code will be released soon.
