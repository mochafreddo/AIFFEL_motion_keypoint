# [Dacon] 모션 키포인트 검출 AI 경진대회 참여

![motion](https://user-images.githubusercontent.com/76798200/113500617-4d375800-955a-11eb-8120-3ae607ff43ba.png)


## [대회 개요]

### 1. 대회 설명
: 특정 운동 동작을 수행하고 있는 사람의 미리 지정된 각 신체 부위의 위치에서 측정한 데이터를 활용하여 **신체 동작 마다의 키포인트를 검출하는 대회**



 ![image](https://user-images.githubusercontent.com/76798200/113500627-78ba4280-955a-11eb-8ed2-58b61ccade88.png)
 ![image](https://user-images.githubusercontent.com/76798200/113500634-88d22200-955a-11eb-9c0c-89367ab192bb.png)
 





### 2. 주제 및 배경
: **Motion keypoint detection 알고리즘 개발**, **스마트 헬스케어 산업**에 적용 가능한 데이터 분석 방법

### 3. 주최 및 주관
: 슬릭, 데이터연구소, DACON

### 4. 일정
: 2021년 2월 10일 18:00 ~ 2021년 4월 5일 17:59 
  
.
.
.
.


## [팀 소개]
멤버: 김정우, 양창원, 이병현

.
.
.
.



## [프로젝트 진행 내용]
### 1. Baseline 필사
프로젝트 진행에 앞서 주최즉에서 제공한 Baseline을 필사하며 분석하였다.
데이터셋과 모델, 키포인트 접근 방법들을 확인하는 단계였다.

### 2. Augmentatoin (+ reset_index)
더 많은 데이터를 확보하기 위해 다양한 방법의 Augmentation을 적용하였다.

### 3. 전이학습 (Transfer Learning)
세 번째 접근 방법으로 전이학습을 진행하였다. 
Keras application에서 제공하는 여러가지 모델 중, 각 멤버가 하나의 모델을 선정하고 augmentation을 적용한 데이터를 전이학습 모델을 이용해 학습을 진행하였다.

**1) 김정우 - MobileNetV3Small, InceptionResNetV2**   

**2) 이병현 - Xception**   

**3) 양창원 - NASNet Large**

팀 운영사항에 대한 자세한 내용 확인: https://www.notion.so/vgrlo/22a6d252eaa1441bb0cfe53fd2326ca6


![image](https://user-images.githubusercontent.com/76798200/113500997-3d6d4300-955d-11eb-98a0-69661b1098cb.png)
