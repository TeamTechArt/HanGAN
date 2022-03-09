# AKMA (Audio Kinetic Media Art) Project Overview

AIFFEL X SeSAC Hackathon Project

## Table of Contents

- [Overview](#Overview)
  - [Team-Introduction](#Team-Introduction)
  - [Project-Introduction](#Project-Introduction)
  - [Project-Timeline](#Project-Timeline)
- [Workflow](#Workflow)
  - [Data-Acquisition](#Data-Acquisition)
  - [Architecture](#Architecture)
  - [Model](#Model)
- [Tech-Stack](#Tech-Stack)
- [Repositories](#Repositories)
- [Demo](#Demo)
- [Reference](#Reference)

## Overview

2022.01.17 ~ 2022.03.10 약 2 달간 진행한 AKMA (Audio Kinetic Media Art) 프로젝트의 Overview와 각 리포지토리 설명, 노션의 다큐멘테이션을 정리해보았습니다.

**모두의연구소 AIFFEL** 에서 개인 과제 **_StyleGAN3 Based Audio Reactive Media Art Generator Model_**를 주제로 프로젝트를 진행하였습니다.

## Team-Introduction

| Name | Role | Email | Focus |
|:-------------:|:-------------:|:-------------:|:-------------:|
| [최동현](https://github.com/donghyundavidchoi) | 팀장 | david0302@naver.com | ? |
| [김영현](https://github.com/kim1987) | 팀원 | overevo489@gmail.com | ? |
| [윤세영](https://github.com/uni1023) | 팀원 | yoonsy1023@gmail.com | ? |
| [이상현](https://github.com/oddhyeon) | 팀원 | roughideal@gmail.com | ? |
| [이호진](https://github.com/ghwlsdl) | 팀원 | hojinlee93@gmail.com | ? |

## Project-Introduction

- 공사 중 입니다.

## Project-Timeline


Project Term : 2022.01.17 ~ 2022.03.10

| Weekly | Term | Content | Detail |
|:-------------:|:-------------:|:-------------:|:-------------:|
| Week 1 : | 2022.01.17 ~ 2022.01.23 | 기획안 발표, 팀 빌딩, 기획서 작성, 미니해커톤 | ? |
| Week 2 : | 2022.01.24 ~ 2022.01.30 | ? | ? |
| Week 3 : | 2022.01.31 ~ 2022.02.06 | ? | ? |
| Week 4 : | 2022.02.07 ~ 2022.02.13 | ? | ? |
| Week 5 : | 2022.02.14 ~ 2022.02.20 | ? | ? |
| Week 6 : | 2022.02.21 ~ 2022.02.27 | ? | ? |
| Week 7 : | 2022.02.28 ~ 2022.03.06 | ? | ? |
| Week 8 : | 2022.03.07 ~ 2022.03.10 | ? | ? |




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

## Workflow

### Data-Acquisition

- 공사 중 입니다.

## Model Architecture

### StyleGAN3
![styelgan3](https://user-images.githubusercontent.com/67223441/157396919-04b48c92-6787-4610-aacb-6794c6bb4f12.png)

### Real-ESRGAN
![Real-ESRGAN](https://user-images.githubusercontent.com/67223441/157398801-5922a4d4-c06e-4946-adf2-fbad0ff95245.png)


## Tech Art Team Piple Line

## 초기 Pipline

![Tech Art 초기 Pipline drawio](https://user-images.githubusercontent.com/90362869/150274518-22b3e367-765b-43f4-94b8-c5dd6a85e6a6.png)

## 중간발표 시기 Pipline

![Tech Art 중간발표 시기 Pipline drawio](https://user-images.githubusercontent.com/90362869/154292356-cf968c4f-e0f4-47e1-a8ec-0fd06088c636.jpeg)

## Tech-Stack

- Model
  - PyTorch
  - [Stylegan3](https://github.com/NVlabs/stylegan3)
  - [Real-ESRGAN](https://github.com/xinntao/Real-ESRGAN)
- Custom Data
  - [YOUTUBE-WAVE](https://drive.google.com/drive/folders/1197NN3gqxi2mEQ5do1Lmp4UQIq-SfO9L)
  - [EAST-SEA](https://drive.google.com/file/d/1SscfF-3Zy9_IPvU6DsBXvmT_isvcoWe4/view?usp=sharing)
- Serving
  - BentoML
  - Google Cloud Platform

## Sample
 - https://drive.google.com/file/d/1dX7UPuy-rlaeYYTrlXPJFFV4FssCj7-N/view?usp=sharing
 - https://drive.google.com/file/d/1fGUIIfBadJuCWPwkMxHawxT8wfl1iNUJ/view?usp=sharing


## Reference
- [Stylegan3](https://github.com/NVlabs/stylegan3)
- [StyleGAN2 Reactive Audio](https://github.com/dvschultz/ai/blob/master/StyleGAN2_AudioReactive.ipynb)
- [Real-ESRGAN](https://github.com/xinntao/Real-ESRGAN)
