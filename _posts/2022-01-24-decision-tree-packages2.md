--- 
title: "[책] 그냥 하지 말라 - 송길영"  
excerpt: "코로나로 빨라진 사회의 변화 트렌드와 개인이 나아가야할 방향에 대한 책. "
categories: "book review"
tags: 책리뷰 그냥하지말라 송길영    
---  



# 0. Introduction
---

**Dataset: Heart Disease UCI** [UCI 데이터]([https://archive.ics.uci.edu/ml/datasets/heart+disease](https://archive.ics.uci.edu/ml/datasets/heart+disease)

이 데이터셋은 총 303명의 환자의 의료 정보와 심장병 발병 여부를 담고 있는 데이터셋입니다.  총 13개의 입력변수와 1개의 타겟변수로 구성되어 있습니다. 변수를 살펴보면:

- **age**: 환자의 나이
- **sex**: 성별 (1=남성, 0=여성)
- **cp**: 가슴 통증의 유형 (0-3)
- **trestbps**: 혈압
- **chol**: 콜레스테롤 수치 (mg/dl)
- **fbs**: 공복혈당수치가 120ml/dl을 초과하는지 여부 (1 = true, 0=false)
- **restecg**: 심전도 결과 (0=정상, 1=ST-T wave, 2=좌심실비대)
- **thalach**: 최대 심박수
- **exang**: 운동 유발성 협심증 여부 (1=yes, 0=no)
- **oldpeak**: ST분절 하강
- **slope**: the slope of the peak exercise ST segment (0-2)
- **ca**: 형광투시로 칠해진 주요 혈관의 개수(0-3)
- **thal**: 1 = normal; 2 = fixed defect; 3 = reversable defect
- **num** (타겟변수): 심장병 여부 (0=no disease, 1=disease)

Heart 데이터셋을 활용하여 R에서 제공하는 Decision Tree 패키지 4개로 Classsification tree를 만들어 보겠습니다. 모델마다 가지치기를 하기 전과 후의 성능을 비교해보고 패키지 간 성능도 비교해보겠습니다. 
