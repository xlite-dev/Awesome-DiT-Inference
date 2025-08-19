
<div align='center'>
  <img src=https://github.com/user-attachments/assets/decc861e-fe77-4eb7-aacf-7d27b6430e54 width=250px>
</div>   
 
<div align='center'>
  <img src=https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg >
  <img src=https://img.shields.io/github/forks/xlite-dev/Awesome-DiT-Inference.svg?style=social >
  <img src=https://img.shields.io/github/stars/xlite-dev/Awesome-DiT-Inference.svg?style=social >
  <img src=https://img.shields.io/badge/Release-v0.5-brightgreen.svg >
  <img src=https://img.shields.io/badge/License-GPLv3.0-turquoise.svg >
 </div>   

📒A curated list of Awesome **Diffusion** Inference Papers with codes. For Awesome LLM Inference, please check 📖[Awesome-LLM-Inference](https://github.com/xlite-dev/Awesome-LLM-Inference)  ![](https://img.shields.io/github/stars/xlite-dev/Awesome-LLM-Inference.svg?style=social) for more details.

## 📖 News 🔥🔥
<div id="news"></div>

- [2025-08-18]: **[🤗cache-dit](https://github.com/vipshop/cache-dit)** is released! 🤗An Unified and Training-free Cache Acceleration Toolbox for DiTs: Cache Acceleration with One-line Code ~ ♥️. Feel free to take a try!

<div align='center'>
  <img src=https://github.com/vipshop/cache-dit/raw/main/assets/cache-dit-v1.png height="320px">
</div>

## 🤖Contents

- [📙Sampling](#Sampling)
- [📙Caching](#Caching)
- [📙Parallelism](#Parallelism)
- [📙Quantization](#Quantization)
- [📙Attention](#Attention)


## ©️Citations 

```BibTeX
@misc{Awesome-DiT-Inference@2024,
  title={Awesome-DiT-Inference: A small curated list of Awesome Diffusion Inference.},
  url={https://github.com/xlite-dev/Awesome-DiT-Inference},
  note={Open-source software available at https://github.com/xlite-dev/Awesome-DiT-Inference},
  author={xlite-dev},
  year={2024}
}
```


## 📙 Sampling  

<div id="Sampling"></div>  

|Date|Title|Paper|Code|Recom|
|:---:|:---:|:---:|:---:|:---:|   
|2020.06| 🔥[**DDPM**] Denoising Diffusion Probabilistic Models(@UC Berkeley)  | [[pdf]](https://arxiv.org/abs/2006.11239) |[[diffusion]](https://github.com/hojonathanho/diffusion) ![](https://img.shields.io/github/stars/hojonathanho/diffusion.svg?style=social) |⭐️⭐️ | 
|2020.10| 🔥[**DDIM**] DENOISING DIFFUSION IMPLICIT MODELS(@cs.stanford.edu) | [[pdf]](https://arxiv.org/pdf/2010.02502) |⚠️|⭐️⭐️ |
|2022.02| 🔥[**PNDM**] PSEUDO NUMERICAL METHODS FOR DIFFUSION MODELS ON MANIFOLDS(@) | [[pdf]](https://arxiv.org/pdf/2202.09778) |[[PNDM]](https://github.com/luping-liu/PNDM) ![](https://img.shields.io/github/stars/luping-liu/PNDM.svg?style=social) |⭐️⭐️ | 
|2022.02| 🔥[**DPM-Solver**] DPM-Solver: A Fast ODE Solver for Diffusion Probabilistic Model Sampling in Around 10 Steps(@Cheng Lu) | [[pdf]](https://arxiv.org/pdf/2206.00927) |[[dpm-solver]](https://github.com/LuChengTHU/dpm-solver) ![](https://img.shields.io/github/stars/LuChengTHU/dpm-solver.svg?style=social) |⭐️⭐️ | 
|2022.11| 🔥[**DPM-Solver++**] DPM-SOLVER++: FAST SOLVER FOR GUIDED SAMPLING OF DIFFUSION PROBABILISTIC MODELS(@Cheng Lu) | [[pdf]](https://arxiv.org/pdf/2211.01095) |[[dpm-solver]](https://github.com/LuChengTHU/dpm-solver) ![](https://img.shields.io/github/stars/LuChengTHU/dpm-solver.svg?style=social) |⭐️⭐️ | 
|2023.10| 🔥[**DPM-Solver-v3**] DPM-Solver-v3: Improved Diffusion ODE Solver with Empirical Model Statistics(@Kaiwen Zheng) | [[pdf]](https://arxiv.org/pdf/2310.13268) |[[DPM-Solver-v3]](https://github.com/thu-ml/DPM-Solver-v3) ![](https://img.shields.io/github/stars/thu-ml/DPM-Solver-v3.svg?style=social) |⭐️⭐️ | 
|2023.11| 🔥[**Parallel Sampling**] Parallel Sampling of Diffusion Models(@Stanford University) | [[pdf]](https://papers.nips.cc/paper_files/paper/2023/file/0d1986a61e30e5fa408c81216a616e20-Paper-Conference.pdf) | [[paradigms]](https://github.com/AndyShih12/paradigms) ![](https://img.shields.io/github/stars/AndyShih12/paradigms.svg?style=social) |⭐️⭐️ |
|2023.11| 🔥[**SAMPLER SCHEDULER**] SAMPLER SCHEDULER FOR DIFFUSION MODELS(@sysu)| [[pdf]](https://arxiv.org/pdf/2311.06845) |⚠️|⭐️⭐️ |
|2024.02| 🔥[**Parallel Sampling**] Accelerating Parallel Sampling of Diffusion Models(@Zhiwei Tang) | [[pdf]](https://arxiv.org/pdf/2402.09970) | [[ParaTAA-Diffusion]](https://github.com/TZW1998/ParaTAA-Diffusion) ![](https://img.shields.io/github/stars/TZW1998/ParaTAA-Diffusion.svg?style=social) |⭐️⭐️ | 
|2024.01| 🔥[**YONOS**] You Only Need One Step: Fast Super-Resolution with Stable Diffusion via Scale Distillation(@Samsung AI) | [[pdf]](https://arxiv.org/pdf/2401.17258) |⚠️|⭐️⭐️ |
|2024.01| 🔥[**S^2-DM**] S^2-DMs: Skip-Step Diffusion Models(@Yixuan Wang) | [[pdf]](https://arxiv.org/pdf/2401.01520) |⚠️|⭐️⭐️ |
|2024.08| 🔥[**StepSaver**] StepSaver: Predicting Minimum Denoising Steps for Diffusion Model Image Generation(@intel) | [[pdf]](https://arxiv.org/pdf/2408.02054) |⚠️|⭐️⭐️ |
|2024.09| 🔥[**DC-Solver**] DC-Solver: Improving Predictor-Corrector Diffusion Sampler via Dynamic Compensation(@Tsinghua University)| [[pdf]](https://arxiv.org/pdf/2409.03755v1) | [[DC-Solver]](https://github.com/wl-zhao/DC-Solver) ![](https://img.shields.io/github/stars/wl-zhao/DC-Solver.svg?style=social) |⭐️⭐️ | 

## 📙 Caching  

<div id="Caching"></div>  

- **UNet Based (DeepCache)**

<img width="1645" alt="image" src="https://github.com/user-attachments/assets/a7257462-80d3-40af-a4ce-3550508fabe7">


- **DiT Based (Fast-Forward Caching)**
<img width="1119" alt="image" src="https://github.com/user-attachments/assets/fad8f187-d4ac-4290-9943-7b34116fed05">

|Date|Title|Paper|Code|Recom|
|:---:|:---:|:---:|:---:|:---:|   
|2023.05|🔥🔥[**Cache-Enabled Sparse Diffusion**] Accelerating Text-to-Image Editing via Cache-Enabled Sparse Diffusion Inference(@pku.edu.cn etc)|[[pdf]](https://arxiv.org/pdf/2305.17423) |⚠️|⭐️⭐️ | 
|2023.12|🔥🔥[**DeepCache**] DeepCache: Accelerating Diffusion Models for Free(@nus.edu)|[[pdf]](https://arxiv.org/pdf/2312.00858) | [[DeepCache]](https://github.com/horseee/DeepCache) ![](https://img.shields.io/github/stars/horseee/DeepCache.svg?style=social)| ⭐️⭐️ |   
|2023.12|🔥🔥[**Block Caching**] Cache Me if You Can: Accelerating Diffusion Models through Block Caching(@Meta GenAI etc)|[[pdf]](https://arxiv.org/pdf/2312.03209) |⚠️|⭐️⭐️ | 
|2023.12|🔥🔥[**Approximate Caching**] Approximate Caching for Efficiently Serving Diffusion Models(@Adobe)|[[pdf]](https://arxiv.org/pdf/2312.04429) |⚠️|⭐️⭐️ |
|2024.06| 🔥🔥[**Layer Caching**] Learning-to-Cache: Accelerating Diffusion Transformer via Layer Caching(@nus.edu)  | [[pdf]](https://arxiv.org/pdf/2406.01733) | [[learning-to-cache]](https://github.com/horseee/learning-to-cache/) ![](https://img.shields.io/github/stars/horseee/learning-to-cache.svg?style=social)| ⭐️⭐️ | 
|2024.07|🔥[**ElasticCache-LVLM**] Efficient Inference of Vision Instruction-Following Models with Elastic Cache(@Tsinghua University etc)|[[pdf]](https://arxiv.org/pdf/2407.18121)|[[ElasticCache]](https://github.com/liuzuyan/ElasticCache) ![](https://img.shields.io/github/stars/liuzuyan/ElasticCache.svg?style=social)|⭐️ |
|2024.07| 🔥🔥[**Fast-Forward Caching(DiT)**] FORA: Fast-Forward Caching in Diffusion Transformer Acceleration(@microsoft.com etc) | [[pdf]](https://arxiv.org/pdf/2407.01425) | [[FORA]](https://github.com/prathebaselva/FORA) ![](https://img.shields.io/github/stars/prathebaselva/FORA.svg?style=social)|⭐️⭐️ |
|2024.07| 🔥🔥[**Faster I2V Generation**] Faster Image2Video Generation: A Closer Look at CLIP Image Embedding’s Impact on Spatio-Temporal Cross-Attentions(@Ashkan Taghipour etc)|[[pdf]](https://arxiv.org/pdf/2407.19205) |⚠️|⭐️⭐️ |
|2024.04| 🔥🔥[**T-GATE V1**] Cross-Attention Makes Inference Cumbersome in Text-to-Image Diffusion Models(@Wentian Zhang etc)|[[pdf]](https://arxiv.org/pdf/2404.02747v1) | [[T-GATE]](https://github.com/HaozheLiu-ST/T-GATE) ![](https://img.shields.io/github/stars/HaozheLiu-ST/T-GATE.svg?style=social)|⭐️⭐️ |
|2024.04| 🔥🔥[**T-GATE V2**] Faster Diffusion via Temporal Attention Decomposition(@Haozhe Liu etc)|[[pdf]](https://arxiv.org/pdf/2404.02747v2) | [[T-GATE]](https://github.com/HaozheLiu-ST/T-GATE) ![](https://img.shields.io/github/stars/HaozheLiu-ST/T-GATE.svg?style=social)|⭐️⭐️ |
|2024.06| 🔥🔥[**DiTFastAttn**] DiTFastAttn: Attention Compression for Diffusion Transformer Models(@Zhihang Yuan etc)|[[pdf]](https://arxiv.org/pdf/2406.08552) | [[DiTFastAttn]](https://github.com/thu-nics/DiTFastAttn) ![](https://img.shields.io/github/stars/thu-nics/DiTFastAttn.svg?style=social)|⭐️⭐️ |
|2024.06| 🔥🔥[**∆-DiT**] ∆-DiT: A Training-Free Acceleration Method Tailored for Diffusion Transformers(@Fudan University)|[[pdf]](https://arxiv.org/pdf/2406.01125) | ⚠️|⭐️⭐️ |  
|2024.09| 🔥🔥[**TokenCache**] Token Caching for Diffusion Transformer Acceleration(@Institute of Automation, Chinese Academy of Sciences)|[[pdf]](https://arxiv.org/pdf/2409.18523) | ⚠️|⭐️⭐️ |  
|2024.11| 🔥🔥[**AdaCache**] Adaptive Caching for Faster Video Generation with Diffusion Transformers(@Meta)|[[pdf]](https://adacache-dit.github.io/clarity/adacache_meta.pdf) | [[AdaCache]](https://github.com/AdaCache-DiT/AdaCache) ![](https://img.shields.io/github/stars/AdaCache-DiT/AdaCache.svg?style=social)|⭐️⭐️ |
|2024.11| 🔥🔥[**TeaCache**] Timestep Embedding Tells: It’s Time to Cache for Video Diffusion Model(@Alibaba)| [[pdf]](https://arxiv.org/pdf/2411.19108) | [[TeaCache]](https://github.com/LiewFeng/TeaCache) ![](https://img.shields.io/github/stars/LiewFeng/TeaCache.svg?style=social)|⭐️⭐️ |
|2024.11| 🔥🔥[**LazyDiT**] LazyDiT: Lazy Learning for the Acceleration of Diffusion Transformers(@Adobe Research)|[[pdf]](https://arxiv.org/pdf/2412.12444)| ⚠️|⭐️⭐️ |  
|2024.11| 🔥🔥[**Ca2-VDM**] Ca2-VDM: Efficient Autoregressive Video Diffusion Model with Causal Generation and Cache Sharing(@ZJU)|[[pdf]](https://arxiv.org/pdf/2411.16375) | [[CausalCache-VDM]](https://github.com/Dawn-LX/CausalCache-VDM/) ![](https://img.shields.io/github/stars/Dawn-LX/CausalCache-VDM.svg?style=social)|⭐️⭐️ |
|2024.11| 🔥🔥[**SmoothCache**] SmoothCache: A Universal Inference Acceleration Technique for Diffusion Transformers(@Roblox) | [[pdf]](https://arxiv.org/pdf/2411.10510) | [[SmoothCache]](https://github.com/Roblox/SmoothCache) ![](https://img.shields.io/github/stars/Roblox/SmoothCache.svg?style=social)|⭐️⭐️ |
|2024.10| 🔥🔥[**FasterCache**] FASTERCACHE: TRAINING-FREE VIDEO DIFFUSION MODEL ACCELERATION WITH HIGH QUALITY(@S-Lab)|[[pdf]](https://arxiv.org/pdf/2410.19355) | [[FasterCache]](https://github.com/Vchitect/FasterCache) ![](https://img.shields.io/github/stars/Vchitect/FasterCache.svg?style=social)|⭐️⭐️ |
|2024.10| 🔥🔥[**ToCa**] ToCa: Accelerating Diffusion Transformers with Token-wise Feature Caching(@SJTU)|[[pdf]](https://arxiv.org/pdf/2410.05317) | [[ToCa]](https://github.com/Shenyi-Z/ToCa) ![](https://img.shields.io/github/stars/Shenyi-Z/ToCa.svg?style=social)|⭐️⭐️ |
|2024.11| 🔥🔥[**SkipCache**] Accelerating Vision Diffusion Transformers with Skip Branches(@SJTU)|[[pdf]](https://arxiv.org/pdf/2411.17616) | [[Skip-DiT]](https://github.com/OpenSparseLLMs/Skip-DiT) ![](https://img.shields.io/github/stars/OpenSparseLLMs/Skip-DiT.svg?style=social)|⭐️⭐️ |
|2024.12| 🔥🔥[**DuCa**] Accelerating Diffusion Transformers with Dual Feature Caching(@SJTU)|[[pdf]](https://arxiv.org/pdf/2412.18911) | [[DuCa]](https://github.com/Shenyi-Z/DuCa) ![](https://img.shields.io/github/stars/Shenyi-Z/DuCa.svg?style=social)|⭐️⭐️ |
|2025.01| 🔥🔥[**FBCache**] Fastest HunyuanVideo Inference with Context Parallelism and First Block Cache on NVIDIA L20 GPUs(@chengzeyi)| [[docs]](https://github.com/chengzeyi/ParaAttention/blob/main/doc/fastest_hunyuan_video.md) | [[ParaAttention]](https://github.com/chengzeyi/ParaAttention) ![](https://img.shields.io/github/stars/chengzeyi/ParaAttention.svg?style=social)|⭐️⭐️ |
|2025.01| 🔥🔥[**FlexCache**] FlexCache: Flexible Approximate Cache System for Video Diffusion(@University of Waterloo)| [[pdf]](https://arxiv.org/pdf/2501.04012) | ⚠️|⭐️⭐️ |  
|2025.01| 🔥🔥[**Token Pruning**] Token Pruning for Caching Better: 9× Acceleration on Stable Diffusion for Free(@SJTU) | [[pdf]](https://arxiv.org/pdf/2501.00375) | [[DaTo]](https://github.com/EvelynZhang-epiclab/DaTo) ![](https://img.shields.io/github/stars/EvelynZhang-epiclab/DaTo.svg?style=social)|⭐️⭐️ |
|2025.04| 🔥🔥[**AB-Cache**] AB-Cache: Training-Free Acceleration of Diffusion Models via Adams-Bashforth Cached Feature Reuse(@USTC) |  [[pdf]](https://arxiv.org/pdf/2504.10540) | ⚠️|⭐️⭐️ |  
|2025.03| 🔥🔥[**DiTFastAttnV2**] DiTFastAttnV2: Head-wise Attention Compression for Multi-Modality Diffusion Transformers(@Infinigence AI)|[[pdf]](https://arxiv.org/pdf/2503.22796) | [[DiTFastAttn]](https://github.com/thu-nics/DiTFastAttn) ![](https://img.shields.io/github/stars/thu-nics/DiTFastAttn.svg?style=social)|⭐️⭐️ |
|2025.03| 🔥🔥[**TaylorSeers**] From Reusing to Forecasting: Accelerating Diffusion Models with TaylorSeers(@SJTU)|[[pdf]](https://arxiv.org/pdf/2503.06923)| [[TaylorSeer]](https://github.com/Shenyi-Z/TaylorSeer) ![](https://img.shields.io/github/stars/Shenyi-Z/TaylorSeer.svg?style=social)|⭐️⭐️ |
|2025.04| 🔥🔥[**Increment-Calibrated Cache**] Accelerating Diffusion Transformer via Increment-Calibrated Caching with Channel-Aware Singular Value Decomposition(@PKU)|[[pdf]](https://arxiv.org/pdf/2505.05829) | [[icc]](https://github.com/ccccczzy/icc) ![](https://img.shields.io/github/stars/ccccczzy/icc.svg?style=social)|⭐️⭐️ |
|2025.05| 🔥🔥[**FastCache**] FastCache: Fast Caching for Diffusion Transformer Through Learnable Linear Approximation(@yale)| [[pdf]](https://arxiv.org/pdf/2505.20353) | [[FastCache-xDiT]](https://github.com/NoakLiu/FastCache-xDiT) ![](https://img.shields.io/github/stars/NoakLiu/FastCache-xDiT.svg?style=social)|⭐️⭐️ |
|2025.06| 🔥🔥[**DBCache**] DBCache: Dual Block Caching for Diffusion Transformers(@DefTruth, @vipshop, etc) | [[docs]](https://github.com/vipshop/cache-dit) | [[cache-dit]](https://github.com/vipshop/cache-dit) ![](https://img.shields.io/github/stars/vipshop/cache-dit.svg?style=social)|⭐️⭐️ |
|2025.06| 🔥🔥[**DBPrune**] DBPrune: Dynamic Block Prune with Residual Caching(@DefTruth, @vipshop, etc) | [[docs]](https://github.com/vipshop/cache-dit) | [[cache-dit]](https://github.com/vipshop/cache-dit) ![](https://img.shields.io/github/stars/vipshop/cache-dit.svg?style=social)|⭐️⭐️ |
|2025.06| 🔥🔥[**BACache**] Block-wise Adaptive Caching for Accelerating Diffusion Policy(@THU) | [[pdf]](https://arxiv.org/pdf/2506.13456) | ⚠️|⭐️⭐️ |  

## 📙 Parallelism

<div id="Parallelism"></div>  

- **UNet Based: Displaced Patch parallelism (DistriFusion)**

<img width="1677" alt="image" src="https://github.com/user-attachments/assets/aefb2ae7-73eb-4e9c-bf1a-ec540f4dfa7d">

- **DiT Based: Displaced Patch parallelism (PipeFusion)**

<img width="1346" alt="image" src="https://github.com/user-attachments/assets/692c5d54-19b3-4ce7-9613-9eb8bb035c7d">


|Date|Title|Paper|Code|Recom|
|:---:|:---:|:---:|:---:|:---:|   
|2024.02|🔥🔥[**DistriFusion**] DistriFusion: Distributed Parallel Inference for High-Resolution Diffusion Models(@MIT etc)|[[pdf]](https://arxiv.org/abs/2402.19481) | [[distrifuser]](https://github.com/mit-han-lab/distrifuser) ![](https://img.shields.io/github/stars/mit-han-lab/distrifuser.svg?style=social)| ⭐️⭐️ |   
|2024.05|🔥🔥[**PipeFusion**] PipeFusion: Displaced Patch Pipeline Parallelism for Inference of Diffusion Transformer Models(@Tencent etc)|[[pdf]](https://arxiv.org/pdf/2405.14430) | [[xDiT]](https://github.com/xdit-project/xDiT) ![](https://img.shields.io/github/stars/xdit-project/xDiT.svg?style=social)| ⭐️⭐️ | 
|2024.06| 🔥🔥[**AsyncDiff**] AsyncDiff: Parallelizing Diffusion Models by Asynchronous Denoising(@nus.edu) | [[pdf]](https://arxiv.org/pdf/2406.06911) | [[AsyncDiff]](https://github.com/czg1225/AsyncDiff) ![](https://img.shields.io/github/stars/czg1225/AsyncDiff.svg?style=social)| ⭐️⭐️ |   
|2024.05 | 🔥🔥[**TensorRT-LLM SDXL**] SDXL Distributed Inference with TensorRT-LLM and synchronous comm(@Zars19) | [[pdf]](https://arxiv.org/abs/2402.19481) | [[SDXL-TensorRT-LLM]](https://github.com/NVIDIA/TensorRT-LLM/pull/1514) ![](https://img.shields.io/github/stars/NVIDIA/TensorRT-LLM.svg?style=social)| ⭐️⭐️ | 
|2024.06| 🔥🔥[**Clip Parallelism**] Video-Infinity: Distributed Long Video Generation(@nus.edu)|[[pdf]](https://arxiv.org/pdf/2406.16260) | [[Video-Infinity]](https://github.com/Yuanshi9815/Video-Infinity) ![](https://img.shields.io/github/stars/Yuanshi9815/Video-Infinity.svg?style=social)|⭐️⭐️ | 
|2024.05| 🔥🔥[**FIFO-Diffusion**] FIFO-Diffusion: Generating Infinite Videos from Text without Training(@Seoul National University)|[[pdf]](https://arxiv.org/pdf/2405.11473) |  [[FIFO-Diffusion]](https://github.com/jjihwan/FIFO-Diffusion_public) ![](https://img.shields.io/github/stars/jjihwan/FIFO-Diffusion_public.svg?style=social) |⭐️⭐️ | 
|2025.01| 🔥🔥[**ParaAttention**] Context parallel attention that accelerates DiT model inference with dynamic caching(@chengzeyi)| [[docs]](https://github.com/chengzeyi/ParaAttention) | [[ParaAttention]](https://github.com/chengzeyi/ParaAttention) ![](https://img.shields.io/github/stars/chengzeyi/ParaAttention.svg?style=social)|⭐️⭐️ |

## 📙 Quantization
<div id="Quantization"></div>  

|Date|Title|Paper|Code|Recom|
|:---:|:---:|:---:|:---:|:---:|   
|2024.08| 🔥[**Transfusion**] Transfusion: Predict the Next Token and Diffuse Images with One Multi-Modal Model(@meta)|[[pdf]](https://www.arxiv.org/pdf/2408.11039) | [[transfusion-pytorch]](https://github.com/A-suozhang/MixDQ) ![](https://img.shields.io/github/stars/lucidrains/transfusion-pytorch.svg?style=social)|⭐️⭐️ |
|2024.08| 🔥[**MixDQ**] MixDQ: Memory-Efficient Few-Step Text-to-Image Diffusion Models with Metric-Decoupled Mixed Precision Quantization (@THU&Infinigence AI.)|[[pdf]](https://arxiv.org/abs/2405.17873) | [[mixdq]](https://github.com/thu-nics/MixDQ) ![](https://img.shields.io/github/stars/thu-nics/MixDQ.svg?style=social)|⭐️⭐️|
|2024.08| 🔥[**ViDiT-Q**] ViDiT-Q: Efficient and Accurate Quantization of Diffusion Transformers for Image and Video Generation (@THU&Infinigence AI.)|[[pdf]](https://arxiv.org/abs/2406.02540) | [[viditq]](https://github.com/thu-nics/ViDiT-Q) ![](https://img.shields.io/github/stars/thu-nics/ViDiT-Q?style=social)|⭐️⭐️|
|2024.08| 🔥[**VQ4DiT**] VQ4DiT: Efficient Post-Training Vector Quantization for Diffusion Transformers(@ZJU)|[[pdf]](https://arxiv.org/pdf/2408.17131)  |⚠️|⭐️⭐️ |
|2024.08| 🔥[**LBQ**] Low-Bitwidth Floating Point Quantization for Efficient High-Quality Diffusion Models(@toronto.edu)|[[pdf]](https://arxiv.org/pdf/2408.06995)  |⚠️|⭐️⭐️ |
|2024.08| 🔥[**EE-Diffusion**] A Simple Early Exiting Framework for Accelerated Sampling in Diffusion Models(@KAIST AI)|[[pdf]](https://arxiv.org/pdf/2408.05927) | [[ee-diffusion]](https://github.com/taehong-moon/ee-diffusion) ![](https://img.shields.io/github/stars/taehong-moon/ee-diffusion.svg?style=social)|⭐️⭐️ |
|2024.08| 🔥[**TFM-PTQ**] Temporal Feature Matters: A Framework for Diffusion Model Quantization(@SenseTime)|[[pdf]](https://arxiv.org/pdf/2407.19547)  |⚠️|⭐️⭐️ |
|2024.08| 🔥[**Diffusion-RWKV**] Diffusion-RWKV: Scaling RWKV-Like Architectures for Diffusion Models(@Zhengcong Fei)|[[pdf]](https://arxiv.org/pdf/2404.04478) | [[Diffusion-RWKV]](https://github.com/feizc/Diffusion-RWKV) ![](https://img.shields.io/github/stars/feizc/Diffusion-RWKV.svg?style=social)|⭐️⭐️ |
|2024.09| 🔥[**LinFusion**] LINFUSION: 1 GPU, 1 MINUTE, 16K IMAGE(@NUS)|[[pdf]](https://arxiv.org/pdf/2409.02097) | [[LinFusion]](https://github.com/Huage001/LinFusion) ![](https://img.shields.io/github/stars/Huage001/LinFusion.svg?style=social)|⭐️⭐️ |
|2024.11| 🔥🔥[**SVDQuant**] SVDQuant: Absorbing Outliers by Low-Rank Components for 4-Bit Diffusion Models|[[pdf]](https://arxiv.org/pdf/2411.05007) | [[nunchaku]](https://github.com/mit-han-lab/nunchaku) ![](https://img.shields.io/github/stars/mit-han-lab/nunchaku.svg?style=social)|⭐️⭐️ |

## 📙 Attention
<div id="Attention"></div>  

|Date|Title|Paper|Code|Recom|
|:---:|:---:|:---:|:---:|:---:| 
|2024.10|🔥🔥[**SageAttention**] SAGEATTENTION: ACCURATE 8-BIT ATTENTION FOR PLUG-AND-PLAY INFERENCE ACCELERATION(@thu-ml)|[[pdf]](https://arxiv.org/pdf/2410.02367)|[[SageAttention]](https://github.com/thu-ml/SageAttention) ![](https://img.shields.io/github/stars/thu-ml/SageAttention) | ⭐️⭐️ |
|2024.11|🔥🔥[**SageAttention-2**] SageAttention2: Efficient Attention with Thorough Outlier Smoothing and Per-thread INT4 Quantization(@thu-ml)|[[pdf]](https://arxiv.org/pdf/2411.10958)|[[SageAttention]](https://github.com/thu-ml/SageAttention) ![](https://img.shields.io/github/stars/thu-ml/SageAttention) | ⭐️⭐️ |
|2025.03|🔥🔥[**SpargeAttention**] SpargeAttn: Accurate Sparse Attention Accelerating Any Model Inference(@thu-ml)|[[pdf]](https://arxiv.org/pdf/2502.18137)|[[SpargeAttn]](https://github.com/thu-ml/SpargeAttn) ![](https://img.shields.io/github/stars/thu-ml/SpargeAttn) | ⭐️⭐️ |
|2025.05|🔥🔥[**SageAttention-3**] SageAttention3: Microscaling FP4 Attention for Inference and An Exploration of 8-bit Training(@thu-ml)|[[pdf]](https://arxiv.org/pdf/2505.11594)|[[SageAttention]](https://github.com/thu-ml/SageAttention) ![](https://img.shields.io/github/stars/thu-ml/SageAttention) | ⭐️⭐️ |
|2025.05| 🔥🔥[**DraftAttention**] DraftAttention: Fast Video Diffusion via Low-Resolution Attention Guidance(@Northeastern University) | [[pdf]](https://arxiv.org/pdf/2505.14708)|[[draft-attention]](https://github.com/shawnricecake/draft-attention) ![](https://img.shields.io/github/stars/shawnricecake/draft-attention) | ⭐️⭐️ |


## ©️License  

GNU General Public License v3.0  

## 🎉Contribute  

Welcome to star & submit a PR to this repo! 

<div align='center'>
<a href="https://star-history.com/#xlite-dev/Awesome-DiT-Inference&Date">
  <picture align='center'>
    <source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/svg?repos=xlite-dev/Awesome-DiT-Inference&type=Date&theme=dark" />
    <source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/svg?repos=xlite-dev/Awesome-DiT-Inference&type=Date" />
    <img width="350" height="250" alt="Star History Chart" src="https://api.star-history.com/svg?repos=xlite-dev/Awesome-DiT-Inference&type=Date" />
  </picture>
</a>
</div>
