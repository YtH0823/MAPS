


<h1 align="center">MAPS: Multi-Anchor Projection Similarity for Joint Vision-Language Geo-Localization</h1>

<p align="center">
  Yutong Hu, Siyuan Tan, Shaocheng Yan, Pengcheng Shi, Qingwu Hu, Jiayuan Li
</p>



## 🔥 Update
- **2026.6.21** The paper is post on arXiv!
[([MAPS](https://arxiv.org/abs/2606.22543))


##  Abstract
<p align="justify">
Humans localize places by integrating perceptual cues from vision with semantic reasoning from language, forming a scene understanding that is both intuitive and structured. Although existing geo-localization models have made substantial progress in cross-view and cross-modal settings, they are largely built upon point-to-point alignment, which is insufficient for joint vision-language queries. In such queries, visual and textual cues do not simply act as independent references, but jointly define a semantic subspace for locating the target. In this paper, we formulate vision-language geo-localization (VLGL) with joint image-text queries as a multi-anchor geometric alignment problem and propose a unified framework for this setting. To realize this formulation, we propose Multi-Anchor Projection Similarity (MAPS), a new metric which constructs an anchor plane from visual and textual query features in a high-dimensional space and measures similarity by the projection length of the target feature onto this plane. Unlike cosine similarity which evaluates isolated pairwise relations, MAPS captures the geometric consistency between the target feature and the joint query subspace, providing a more discriminative ranking criterion during retrieval. To make the learned representation consistent with this geometry, we further introduce a MAPS-based contrastive loss that drives target features toward the corresponding anchor plane. The proposed framework, similarity metric, and training objective jointly yield state-of-the-art performance in VLGL. 
</p>


<img width="3127" height="1261" alt="motivation" src="https://github.com/user-attachments/assets/9d7822e1-b5fd-4d47-9f13-94c911817415" />


<img width="3127" height="1261" alt="motivation" src="https://github.com/user-attachments/assets/57a82718-c585-49c7-831a-c43aa10febe8" /><img width="3049" height="1258" alt="MAPS" src="https://github.com/user-attachments/assets/146a4f51-5fea-4a9d-839a-cc7decd23cfe" />

##  Code
The complete source code will be made publicly available upon acceptance.

##  Model
Model weights for MAPS (on CORE and other datasets) will be released upon acceptance.
