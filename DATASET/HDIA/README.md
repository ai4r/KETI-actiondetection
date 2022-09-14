# KETI ACTION DATASET
==============================

> 본 데이터는 Myo Arm band로부터 취득된 IMU/EMG데이터를 48종에 해당하는 행동인식에 적용함.
    
### Environment
#### Living lab
![Myo1](image/daejeon.png)
![Myo1](image/room.png)
> 암 밴드 외형(좌) \ 밴드 착용 사진(우)

#### Raw Data
![rawdata](image/data_example_A005G068G001.png)

### Action Type List 48
![actionlist](image/class_num.png)
* 실제 고령자 행동을 관찰하여 정의한 55종 행동 중 팔을 사용하지 않는 7종 행동을 제외하여 48종 행동 인식에 활용 

### Data file name layout

    A005_P068_G001
    |    |    |
    |    |    └───────────────────  Trial : 횟수 
    |    └────────────────────────  Subject : 피실험자 id
    └─────────────────────────────  Action : 행동 id

### Action Trainning Dataset Link
https://drive.google.com/drive/folders/1VWrVRpRQVgi8zJ-KiLAnfZGGekVRliSu

![image](image/data_stat.png)



