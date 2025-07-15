# 자율주행 전공체험

## 1. 액추에이터 실습

## (1) 로봇에서 할일

윈도우즈 파워셸에서 젯슨보드에 원격접속

PS> ssh jetson@192.168.0.XXX 

$ ros2 run dxl sub

## (2) PC에서 할일

wsl2-ubuntu20.04 실행

$ ros2 run dxl_wsl pub

## 2. 카메라 실습

## (1) 로봇에서 할일

윈도우즈 파워셸에서 젯슨보드에 원격접속

 $ ros2 run camera pub

## (2) PC에서 할일

wsl2-ubuntu20.04 실행

$ ros2 run camera sub_wsl

## 3. 라이다 실습

## (1) 로봇에서 할일

윈도우즈 파워셸에서 젯슨보드에 원격접속

$ ros2 run sllidar_ros2 sllidar_node

## (2) PC에서 할일

wsl2-ubuntu20.04 실행

$ ros2 run lidarplot lidarplot

