# BEVWorld: A Multimodal World Model for Autonomous Driving via Unified BEV Latent Space
> BEVWorld: A Multimodal World Model for Autonomous Driving via Unified BEV Latent Space

> [Yumeng Zhang], [Shi Gong], [Kaixin Xiong], [Xiaoqing Ye], [Xiao Tan], [Fan Wang], [Jizhou Huang], [Hua Wu], [Haifeng Wang]


## Overview
![overview](./figs/overview.pdf)

World models are receiving increasing attention in autonomous driving for their ability to predict potential future scenarios. In this paper, we present BEVWorld, a novel approach that tokenizes multimodal sensor inputs into a unified and compact Bird's Eye View (BEV) latent space for environment modeling. The world model consists of two parts: the multi-modal tokenizer and the latent BEV sequence diffusion model. The multi-modal tokenizer first encodes multi-modality information and the decoder is able to reconstruct the latent BEV tokens into LiDAR and image observations by ray-casting rendering in a self-supervised manner. Then the latent BEV sequence diffusion model predicts future scenarios given action tokens as conditions. Experiments demonstrate the effectiveness of BEVWorld in autonomous driving tasks, showcasing its capability in generating future scenes and benefiting downstream tasks such as perception and motion prediction.
