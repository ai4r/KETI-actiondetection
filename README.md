# KETI ACTION IMU DATASET
=========================

> 본 데이터는 Myo Arm band로부터 취득된 데이터를 55종에 해당하는 행동분류에 적용함.



### Data set directory layout
    POdd
    ├── accel                  # 가속도(3-axis)  학습 데이터(50Hz)
    ├── emg                    # 근전도(8-ch)    학습 데이터(200Hz)
    └── gyro                   # 각속도(3-axis)  학습 데이터(50Hz)
* 딥러닝 학습에 사용한 데이터 세트로 추후에 추가적으로 데이터 공개 예정

### Data file name layout

    A01_accel_P19_20180802PM123706
    |    |    |        └──────────  Date : 측정 날짜, 오전/오후, 시간
    |    |    └───────────────────  Sbject : 피실험자 번호 
    |    └────────────────────────  Sensor data : accel(3축), gyro(3축), emg(8 채널)
    └─────────────────────────────  Action : 행동 01~55 라벨링

### Link QR Image
![KETIQRImage](image/keti_github_qrcode_f.PNG)
