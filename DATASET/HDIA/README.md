# HDIA 데이터셋
Human Daily Indoor Actions (HDIA) 데이터셋은 실내에서 이루어지는 일상 행동을 담은 데이터셋으로, 가정용 서비스 로봇의 보급을 대비하여 구축된 데이터셋입니다. 로봇과 인간의 원활한 의사소통을 위해 로봇은 사람의 행동을 이해할 수 있는 지능이 요구되며, 이를 위해선 로봇 관점에서 보는 사람의 행동 데이터가 필수적입니다. 본 데이터셋은 로봇의 사람 행동 인식 기술 개발에 주요한 요소를 포함한 데이터를 제공하고 있습니다. 

## 수집 환경
> Living lab
로봇과 사람이 한 집에 공존한다는 가정 아래 아파트에 실제 가정 환경을 모사한 테스트베트 환경을 구축하였습니다. 실험자들은 

<img src="image/daejeon.png"  width="500">     <img src="image/room.png"  width="480">

#### Raw Data
<img src="image/A024_P064_G001_TIC.gif">

## Action class List 48
<img src="image/class_num.png"  width="200">

note) 실제 고령자 행동을 관찰하여 정의한 55종 행동 중 팔을 사용하지 않는 7종 행동을 제외하여 48종 행동 인식에 활용 
*

### Data file name layout

    A005_P068_G001
    |    |    |
    |    |    └────────  Trial : 횟수 
    |    └─────────────  Subject : 피실험자 id
    └──────────────────  Action : 행동 id

### Action Trainning Dataset Link
https://drive.google.com/drive/folders/1VWrVRpRQVgi8zJ-KiLAnfZGGekVRliSu


<img src="image/data_stat.png"  width="500">

