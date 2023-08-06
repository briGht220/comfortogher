# Comfortogether  

시각장애인을 위한 영상인식 기반 어플리케이션  

## Description

케인을 통해 인지하지 못하는 위험 요소 및 점자 블럭을 청각, 촉각적으로 인식시켜 보행을 보조하는 오프라인 기반 어플리케이션

## People

- 곽엘림, 정재원, 최서연, 황성민  

## 제안 필요성

#### 점자블럭 위의 장애물 (개인형 이동장치, 자전거, 불법주차)
---
최근 킥보드나 전기 자전거와 같은 개인형 이동장치(PM) 무인 대여 서비스업이 증가하면서 시각장애인의 통행이 위협받고 있다. 시각장애인은 외부 활동에서 케인을 사용하여 주로 움직이는데, 사정거리가 있어 멀리 있는 전방의 물체 및 인파를 파악하기 힘들 수 있다. 자전거는 허리 높이까지 오기 때문에 장애물임을 인지하고 피할 수 있지만, 전동 킥보드는 성인을 기준으로 고작 발목 정도의 높이이기 때문에, 일반인이라도 전동 킥보드에 발이 걸린다면 쉽게 넘어질 수 있다. 

#### 시각장애인 일상의 불편함 해결
---
국민권익위원회에 따르면 시각장애인은 디지털정보 이용, 카드 사용, 의약품 구매 및 사용 등의 일상에서 답답함을 느끼지만 가장 어렵게 느껴지는 것은 바로 ‘길 찾기’다. 사실 시각장애인이 의존하고 있는 점자블록은 2018년부터 2020년까지 2847건의 민원이 들어왔다. 점자블록 파손 및 훼손(1257건), 불법주차 차량 및 다른 시설물의 점자블록 침범(603건), 점자블록 미설치 지역에 신규 설치 요구(596건), 잘못 설치된 점자블록 재설치 요구(325건) 등의 민원이 제기되었으며, 우리는 이 중 불법주차 차량 및 다른 시설물의 점자블록 침범에 대한 민원을 해결해 보고자 한다. 

#### 안내견 분양과 그 비용
---
안내견 한 마리를 분양하기까지의 비용은 대략 1&#126;2억 정도로, 약 2년의 훈련과정을 거치고 최종적으로30&#126;40% 정도가 안내견으로 선택된다. 안내견을 분양받기 위해서는 매일 다니는 목적지가 있어야 하고, 직업을 가지고 있어야 분양받을 수 있으며, 가정에 10세 미만의 아이가 없어야 한다는 등의 조건에 부합해야 한다. 안내견을 무료로 분양해 주는 곳도 있지만 안내견과 함께 살아가는 비용은 본인 부담이기 때문에 비용적인 측면에서 부담을 느낄 수 있다.

## 개발환경

- GPU 환경 :
- Collaboration tools : ASANA, Github
- Development Tools : Visual Studio 2019, Jupyter Lab
- Libraries & Frameworks : OpenCV, Pytorch
- Annotation Tools : VIA
  
## Folder Structure

```C
root
│  
├─android // Android App sources 
│     
└─python  // Image Processing sources 
│
└─ML  // Machine Learning sources
```

