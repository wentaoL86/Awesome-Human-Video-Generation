# Awesome-Human-Body-Video-Generation
[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/hee9joon/Awesome-Diffusion-Models) 
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)
[![Made With Love](https://img.shields.io/badge/Made%20With-Love-red.svg)](https://github.com/chetanraj/awesome-github-badges)

A curated list of recent human body video generation method.
This repository focus on half/full body human body video generation method, The Nerf, Gaussian splashing, Motion Pose, and talking head/Portrait is not included.

## human body video Demo  

Here are some Demo results from latest repository/paper.

<table class="center">
    
<tr>
    <td width=50% style="border: none">
        <video controls autoplay loop src="https://github.com/wentaoL86/Awesome-Human-Body-Video-Generation/assets/61672329/6fadf315-aacb-4fce-81ed-09e593fdb472" muted="false"></video>
    </td>
    <td width=50% style="border: none">
        <video controls autoplay loop src="https://github.com/wentaoL86/Awesome-Human-Body-Video-Generation/assets/61672329/102c3ace-2f01-4b95-bcaf-87b182925033" muted="false"></video>
    </td>
</tr>





<tr>
    <td width=50% style="border: none">
        <video controls autoplay loop src="https://github.com/wentaoL86/Awesome-Human-Body-Video-Generation/assets/61672329/91343897-0412-4e89-b29f-27b32016eafb" muted="false"></video>
    </td>
    <td width=50% style="border: none">
        <video controls autoplay loop src="https://github.com/wentaoL86/Awesome-Human-Body-Video-Generation/assets/61672329/274d8dec-5425-405f-a74c-2c9185eaf1e4" muted="false"></video>
    </td>
</tr>
</table>


## Table of Contents <!-- omit in toc -->
- [Open-source Toolboxes and Foundation Models](#open-source-toolboxes-and-foundation-models)
- [Evaluation Benchmarks and Metrics](#evaluation-benchmarks-and-metrics)
- [Video Generation](#video-generation)

### Open-source Toolboxes and Foundation Models 
+ [Open-Sora-Plan](https://github.com/PKU-YuanGroup/Open-Sora-Plan)  
  [![Star](https://img.shields.io/github/stars/PKU-YuanGroup/Open-Sora-Plan.svg?style=social&label=Star)](https://github.com/PKU-YuanGroup/Open-Sora-Plan)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://github.com/PKU-YuanGroup/Open-Sora-Plan/blob/main/docs/Report-v1.0.0.md)

+ [Open-Sora](https://github.com/hpcaitech/Open-Sora)  
  [![Star](https://img.shields.io/github/stars/hpcaitech/Open-Sora.svg?style=social&label=Star)](https://github.com/hpcaitech/Open-Sora)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://github.com/hpcaitech/Open-Sora/blob/main/docs/zh_CN/README.md)

+ [Stable Video Diffusion](https://github.com/Stability-AI/generative-models)  
  [![Star](https://img.shields.io/github/stars/Stability-AI/generative-models.svg?style=social&label=Star)](https://github.com/Stability-AI/generative-models)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://stability.ai/news/stable-video-diffusion-open-ai-video-model) 

+ [Show-1](https://github.com/showlab/Show-1)  
  [![Star](https://img.shields.io/github/stars/showlab/Show-1.svg?style=social&label=Star)](https://github.com/showlab/Show-1)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://showlab.github.io/Show-1/) 

+ [Hotshot-XL (text-to-GIF)](https://huggingface.co/cerspense/zeroscope_v2_576w)  
  [![Star](https://img.shields.io/github/stars/hotshotco/Hotshot-XL.svg?style=social&label=Star)](https://github.com/hotshotco/Hotshot-XL)

+ [zeroscope_v2](https://huggingface.co/cerspense/zeroscope_v2_576w)  
  [![Website](https://img.shields.io/badge/576w-9cf)](https://huggingface.co/cerspense/zeroscope_v2_576w) 
  [![Website](https://img.shields.io/badge/XL-9cf)](https://huggingface.co/cerspense/zeroscope_v2_XL) 

+ [I2VGen-XL (image-to-video / video-to-video)](https://modelscope.cn/models/damo/Image-to-Video/summary)  
  [![Website](https://img.shields.io/badge/Website(I2V)-9cf)](https://modelscope.cn/models/damo/Image-to-Video/summary) 
  [![Website](https://img.shields.io/badge/Website(V2V)-9cf)](https://modelscope.cn/models/damo/Video-to-Video/summary) 

+ [text-to-video-synthesis-colab](https://github.com/camenduru/text-to-video-synthesis-colab)  
  [![Star](https://img.shields.io/github/stars/camenduru/text-to-video-synthesis-colab.svg?style=social&label=Star)](https://github.com/camenduru/text-to-video-synthesis-colab)

+ [VideoCrafter: A Toolkit for Text-to-Video Generation and Editing](https://github.com/VideoCrafter/VideoCrafter)  
  [![Star](https://img.shields.io/github/stars/VideoCrafter/VideoCrafter.svg?style=social&label=Star)](https://github.com/VideoCrafter/VideoCrafter)

+ [ModelScope (Text-to-video synthesis)](https://modelscope.cn/models/damo/text-to-video-synthesis/summary)  
  [![Star](https://img.shields.io/github/stars/modelscope/modelscope.svg?style=social&label=Star)](https://github.com/modelscope/modelscope)

+ [Diffusers (Text-to-video synthesis)](https://huggingface.co/docs/diffusers/main/en/api/pipelines/text_to_video#texttovideo-synthesis)  
  [![Star](https://img.shields.io/github/stars/huggingface/diffusers.svg?style=social&label=Star)](https://github.com/huggingface/diffusers)

### Evaluation Benchmarks and Metrics
+ [PEEKABOO: Interactive Video Generation via Masked-Diffusion](https://arxiv.org/abs/2312.07509) (CVPR, 2024)  
  [![Star](https://img.shields.io/github/stars/microsoft/Peekaboo.svg?style=social&label=Star)](https://github.com/microsoft/Peekaboo)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.07509)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://jinga-lala.github.io/projects/Peekaboo/)

+ [T2VScore: Towards A Better Metric for Text-to-Video Generation](https://arxiv.org/abs/2401.07781) (Jan., 2024)      
  [![Star](https://img.shields.io/github/stars/showlab/T2VScore.svg?style=social&label=Star)](https://github.com/showlab/T2VScore)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2401.07781)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://showlab.github.io/T2VScore/) 

+ [VBench: Comprehensive Benchmark Suite for Video Generative Models](https://arxiv.org/abs/2311.17982) (Nov., 2023)      
  [![Star](https://img.shields.io/github/stars/Vchitect/VBench.svg?style=social&label=Star)](https://github.com/Vchitect/VBench?tab=readme-ov-file)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.17982)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://vchitect.github.io/VBench-project/) 

+ [FETV: A Benchmark for Fine-Grained Evaluation of Open-Domain Text-to-Video Generation](https://arxiv.org/abs/2311.01813) (Nov., 2023)      
  [![Star](https://img.shields.io/github/stars/llyx97/FETV.svg?style=social&label=Star)](https://github.com/llyx97/FETV)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.01813)

+ [EvalCrafter: Benchmarking and Evaluating Large Video Generation Models](https://arxiv.org/abs/2310.11440) (Oct., 2023)      
  [![Star](https://img.shields.io/github/stars/EvalCrafter/EvalCrafter.svg?style=social&label=Star)](https://github.com/EvalCrafter/EvalCrafter)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2310.11440)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://evalcrafter.github.io/) 
  [![Dataset](https://img.shields.io/badge/Dataset-e97451)](https://huggingface.co/datasets/RaphaelLiu/EvalCrafter_T2V_Dataset) 

### Video Generation 

+ [Collaborative Video Diffusion: Consistent Multi-video Generation with Camera Control](https://arxiv.org/abs/2405.17414) (May, 2024)      
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2405.17414)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://collaborativevideodiffusion.github.io/)



