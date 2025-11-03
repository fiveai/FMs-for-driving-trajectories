# A Repository of the Papers That Benefit From Foundation Models in Trajectory Planning for Autonomous Driving

This repository provides an up-to-date the list of approaches that utilizes foundation models (FM) in trajectory planning for autonomous driving. It follows the taxonomy provided in the following paper:

"A Review: How are Foundation Models Helping Trajectory Planning for Autonomous Driving?". [[preprint]](???)

# Table of Contents (Follows the taxonomy in the paper)
1. [Foundation Models Tailored for Trajectory Planning](#1)  
    1.1 [Methods Focused Solely on Trajectory Planning](#1.1)  
    1.2 [Methods Providing Additional Capabilities](#1.2)    
2. [Foundation Models Guiding Trajectory Planning](#2)  
    2.1 [Knowledge Distillation Only During Training](#2.1)  
    2.2 [Knowledge Transfer During Inference](#2.2)    

# 1.Foundation Models Tailored for Trajectory Planning <a name="1"></a>

## 1.1. Methods Focused Solely on Trajectory Planning <a name="1.1"></a>
- Methods without Chain-of-Thought Reasoning:
   - **CarLlava**, *CARLA challenge winner in 2024*. [[paper]](https://arxiv.org/pdf/2406.10165) [[code]](https://github.com/RenzKa/simlingo)
   - **DriveGPT4v2**, *CVPR 2025*. [[paper]](https://openaccess.thecvf.com/content/CVPR2025/papers/Xu_DriveGPT4-V2_Harnessing_Large_Language_Model_Capabilities_for_Enhanced_Closed-Loop_Autonomous_CVPR_2025_paper.pdf)
   - **V2X-VLM**, preprint in 2024. [[paper]](https://arxiv.org/pdf/2408.09251)

- Methods using text output of the FM for the Chain-of-Thought Reasoning:
   - **GPT-Driver**, *NeurIPS 2024 Workshops*. [[paper]](https://arxiv.org/pdf/2310.01415) [[code]](https://github.com/PointsCoder/GPT-Driver)
   - **DriveVLM**, *CoRL 2024*. [[paper]](https://arxiv.org/pdf/2402.12289)
   - **Auto-VLA**, *NeurIPS 2025*. [[paper]](https://arxiv.org/pdf/2506.13757) [[code]](https://github.com/ucla-mobility/AutoVLA)
   - **RAG Driver**, *RSS 2024*. [[paper]](https://www.roboticsproceedings.org/rss20/p075.pdf) [[code]](https://github.com/YuanJianhao508/RAG-Driver)
   - **S4 Driver**, *CVPR 2025*. [[paper]](https://arxiv.org/pdf/2505.24139)

- Methods using an initial trajectory prediction for the Chain-of-Thought Reasoning (with/without text output of the FM)
   - **Agent-driver**, *CoLM 2024*. [[paper]](https://arxiv.org/pdf/2311.10813) [[code]](https://github.com/USC-GVL/Agent-Driver)
   - **FeD**, *CVPR 2024*. [[paper]](https://openaccess.thecvf.com/content/CVPR2024/papers/Zhang_Feedback-Guided_Autonomous_Driving_CVPR_2024_paper.pdf)
   - **Solve-VLM**, *CVPR 2025*. [[paper]](https://arxiv.org/pdf/2505.16805)


## 1.2. Methods Providing Additional Capabilities <a name="1.2"></a>

- Methods Providing Language Interaction Capability Only:
   - **DriveGPT4**, *IEEE Robotics and Automation Letters in 2024*. [[paper]](https://arxiv.org/pdf/2310.01412) [[code]](https://drive.google.com/drive/folders/1PsGL7ZxMMz1ZPDS5dZSjzjfPjuPHxVL5)
   - **DriveLM-Agent**, *ECCV 2024*. [[paper]](https://arxiv.org/pdf/2312.14150) [[code]](https://github.com/OpenDriveLab/DriveLM)
   - **Emma**, *TMLR in 2025*. [[paper]](https://arxiv.org/pdf/2410.23262) [[code]](https://github.com/taco-group/OpenEMMA)
   - **OpenDriveVLA**, preprint in 2025. [[paper]](https://arxiv.org/pdf/2503.23463) [[code]](https://github.com/DriveVLA/OpenDriveVLA)
   - **DiMA-MLLM**, *CVPR 2025*. [[paper]](https://arxiv.org/pdf/2501.09757)
   - **Omni-Q/L**, *CVPR 2025*. [[paper]](https://arxiv.org/pdf/2405.01533v2) [[code]](https://github.com/NVlabs/OmniDrive)
   - **Orion**, *ICCV 2025*. [[paper]](https://arxiv.org/pdf/2503.19755) [[code]](https://github.com/xiaomi-mlab/Orion)

- Methods Providing Action Interaction Capability Only:
   - **DriveMLM**, preprint in 2023. [[paper]](https://arxiv.org/pdf/2312.09245) [[code]](https://github.com/OpenGVLab/DriveMLM)
   - **LMDrive**, *CVPR 2024*. [[paper]](https://arxiv.org/pdf/2312.07488) [[code]](https://github.com/opendilab/LMDrive)

- Methods Providing Language and Action Interaction Capabilities:
    - **SimLingo**, *CVPR 2025*. [[paper]](https://arxiv.org/pdf/2503.09594) [[code]](https://github.com/RenzKa/simlingo)

# 2. Foundation Models Guiding Trajectory Planning <a name="2"></a>

## 2.1. Knowledge Distillation Only During Training <a name="2.1"></a>

- Methods:

    - **VLP**, *CVPR 2024*. [[paper]](https://arxiv.org/pdf/2401.05577)
    - **VLM-AD**, *CoRL 2025*. [[paper]](https://arxiv.org/pdf/2412.14446)
    - **DiMA**, *CVPR 2025*. [[paper]](https://arxiv.org/pdf/2501.09757)
    - **Solve-E2E**, *CVPR 2025*. [[paper]](https://arxiv.org/pdf/2505.16805)

## 2.2. Knowledge Transfer During Inference <a name="2.2"></a>

- Methods:

    - **VLM-E2E**, preprint in 2025. [[paper]](https://arxiv.org/pdf/2502.18042)
    - **DME-Driver**, *AAAI 2025*. [[paper]](https://ojs.aaai.org/index.php/AAAI/article/view/32346)
    - **Senna-E2E**, preprint in 2024. [[paper]](https://arxiv.org/pdf/2410.22313) [[code]](https://github.com/hustvl/Senna)
    - **DiffVLA**, Runner Up in *Autonomous Grand Challenge 2025*. [[paper]](https://arxiv.org/pdf/2505.19381)
    - **DriveVLM-Dual**, *CoRL 2024*. [[paper]](https://arxiv.org/pdf/2402.12289)
    - **Solve-E2E-Async**, *CVPR 2025*. [[paper]](https://arxiv.org/pdf/2505.16805)
    - **DiMA-Dual**, *CVPR 2025*. [[paper]](https://arxiv.org/pdf/2501.09757)
    - **HE-Drive**, preprint in 2024. [[paper]](https://arxiv.org/pdf/2410.05051)
    - **VDT-Auto**, preprint in 2025. [[paper]](https://arxiv.org/pdf/2502.20108) [[code]](https://github.com/ZionGo6/VDT-Auto)
    - **FasionAD++**, preprint in 2025. [[paper]](https://arxiv.org/pdf/2503.08162)
    - **AsyncDriver**, *ECCV 2024*. [[paper]](https://arxiv.org/pdf/2406.14556) [[code]](https://github.com/memberRE/AsyncDriver)

## How to request addition of a paper
If you know of an approach built on a FM (VLM/LLM etc.) or utilizes a foundation model for knowledge transfer, and is not on this repository, you are welcome to request the addition of that paper. For such an addition, please open a pull request by briefly explaining which section of the taxonomy that the paper fits into.

## How to cite?

## Contact 
Please contact Kemal Öksüz (kemal.oksuz@bosch.com) for your questions about this webpage.
