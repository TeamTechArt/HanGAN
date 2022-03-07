# AKMA (Audio Kinetic Media Art)
AIFFEL SeSAC Hackathon Project


## Member
- 팀장 : [최동현](https://github.com/donghyundavidchoi)

- 팀원 : [김영현](https://github.com/kim1987), [윤세영](https://github.com/uni1023), [이상현](https://github.com/oddhyeon), [이호진](https://github.com/ghwlsdl)

- 사외이사 : [김수연](https://github.com/estela19)


## Project Timeline
* Project Term : 2022.01.17 ~ 2022.03.10
* 
* 2022.01.17 : 기획안 발표 / TechArt 팀 빌딩 (팀장 : 최동현 / 팀원 : 김영현, 윤세영, 이상현, 이호진)
* 2022.01.18 : 기획서 작성
* 2022.01.19 ~ 21 : 미니 해커톤 (모델 파이프 라인 설계 및 개발)
*         19 : 1차 미팅 - 전체적인 Flow 공유, Notion page Active, Membership Training
*         20 : Pipline Gerneration, Trello Active, Mini-Hackathon-Report 초안 작성
*         21 : 미니 해커톤 마무리 & 앞으로의 계획 정립
* 2022.01.24 ~ : 3차 해커톤 Start
* 2022.01.25 : 해커톤 진행 워크샵 (at.동대입구 커피빈)
* 2022.01.26 : Pipline 1차 수정
* 2022.01.27 : 미팅 (at. 싹캠퍼스) (진행 현황 공유)
* 2022.02.03 : 미팅 (at. 싹캠퍼스)
* 2022.02.04 : 미팅 (at. 싹캠퍼스)
* 2022.02.06 : GAN ~ StyleGAN3 논문 리뷰
* 2022.02.09 ~ 11 : **Crunch mode** 합숙 기간
*         09 : 음향에 따른 파형 평탄화 작업 완료, Audio-Reactive StyleGAN2 코드를 StyleGAN3 화 진행
*         10 : Audio-Reactive StyleGAN2 코드를 StyleGAN3 화 완료
*         11 : 위의 코드를 기반으로 영상 제작 Start
* 2022.02.14 : Awesome-beach pkl 을 기반으로 영상 제작 start
* 2022.02.15 : choi 알고리즘 수식 탄신일
* 2022.02.16 : 중간 발표 준비
* 2022.02.17 : 중간 발표회 (진행상황 보고 & 피드백)
* 2022.02.18 ~ 02.28 : GCP 사용, Encoder Control, MLOps, BentoML
* 2022.03.02 ~ 03.04 : 파도 데이터 수집 (at. Samcheok, Gangwon-do)
* 2022.03.05 ~ 03.07 : 지금까지 해 온 것들 정리
* 2022.03.08 : 결과물 제출
* 2022.03.10 : 최종 발표회


## Tech Art Team Piple Line

### 초기 Pipline
![Tech Art 초기 Pipline drawio](https://user-images.githubusercontent.com/90362869/150274518-22b3e367-765b-43f4-94b8-c5dd6a85e6a6.png)

### 중간발표 시기 Pipline
![Tech Art 중간발표 시기 Pipline drawio](https://user-images.githubusercontent.com/90362869/154292356-cf968c4f-e0f4-47e1-a8ec-0fd06088c636.jpeg)


## Requirement
---
- We recommend Linux for performance and compatibility (Ubuntu = 20.04) 
- We have done all testing and development using Tesla V100 and A100 GPUs. (at. Colab Pro)
- 64-bit Python 3.8 and PyTorch 1.9.0 (or later). See https://pytorch.org for PyTorch install instructions.
- [CUDA toolkit 11.1](https://developer.nvidia.com/cuda-toolkit) or later.
  - PyTorch invokes `nvcc` to compile our CUDA kernels.
  - Why is CUDA toolkit installation necessary?
    > The PyTorch package contains the required CUDA toolkit libraries needed to run PyTorch, so why is a separate CUDA toolkit installation required? Our models use custom CUDA kernels to implement operations such as efficient resampling of 2D images. PyTorch code invokes the CUDA compiler at run-time to compile these kernels on first-use. The tools and libraries required for this compilation are not bundled in PyTorch and thus a host CUDA toolkit installation is required.
- Ninja
  - PyTorch uses [Ninja](https://ninja-build.org/) as its build system.
- GCC 7 or later (Linux) compilers. Recommended GCC version depends on CUDA version, see for example [CUDA 11.6 system requirements](https://docs.nvidia.com/cuda/archive/11.6.0/index.html).
- Python libraries: see [environment.yml](https://github.com/TeamTechArt/HanGAN/blob/main/environment.yml) for exact library dependencies. You can use the following commands with Miniconda3 to create and activate your StyleGAN3 Python environment:
  - `conda env create -f environment.yml`
  - `conda activate stylegan3`

## Reference
[Stylegan3](https://github.com/NVlabs/stylegan3)
[StyleGAN2 Reactive Audio](https://github.com/dvschultz/ai/blob/master/StyleGAN2_AudioReactive.ipynb)
