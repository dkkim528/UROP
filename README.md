# UROP
## 1. 프로젝트 개요
Bézier curve 컨벡스 최적화 기반 충돌회피 알고리즘 모듈을 개발하고, LIMO 플랫폼에 탑재하여 실증한다.

## 2. 프로젝트 멤버
정태훈(PL)
### - H/W
김동건(L)

최현준

서대환
### - Algorithm
이송하(L)

이윤재
### - Control
강현민(L)

## 3. Technology Stack
### 3.1 Language
| ![Python](https://github.com/dkkim528/UROP/blob/main/py.png)    | ![C++](https://github.com/dkkim528/UROP/blob/main/C%2B%2B.png) |
| ---------- | ---------------------------------------------- |
| Python | C++  |

- 파이썬 스펙 (미완성)
```shell
  Python==3.6.7
  Cython
  dlib==19.8.1
  face-recognition==1.3.0
  numpy==1.15.0
  torch==1.7.0+cu101
  torchvision==0.8.1+cu101
  tensorflow==1.13.1
  tensorflow-gpu==1.13.1
  tqdm
  Keras==2.3.1
  opencv-python
  scikit-learn==0.21.2
  scipy==1.4.1
  Pillow
  visdom
  Nibabel
  GTTS
```

### 3.2 Development Environment
| ![ubuntu](https://github.com/dkkim528/UROP/blob/main/ubuntu.png)  | ![ROS2](https://github.com/dkkim528/UROP/blob/main/ros2.png)    |
| ---------- | ---------------------------------------------- |
| ubuntu 22.04 | ROS2 Humble  |

### 3.3 Cooperation
| ![ubuntu](https://github.com/dkkim528/UROP/blob/main/gitlab.png)  | ![ROS2](https://github.com/dkkim528/UROP/blob/main/notion.png)    |
| ---------- | ---------------------------------------------- |
| Gitlab | Notion  |

## 4. Project Structure
```shell
src/rplidar_ros
├── CHANGELOG.rst
├── CMakeLists.txt
├── config
│   └── params.yaml
├── debian
│   
├── include
│
├── build
│   ├── my_cartographer_2d.launch.py
│   ├── __pycache__
│   │   └── rplidar_with_pointcloud.launch.cpython-310.pyc
│   ├── rplidar_a1_launch.py
│ 
└── src
    ├── rplidar_ros
    ├── nav2_navigation
    . 
    .   
    .
```
    
## 5. Coding Convention
- 상수 : 영문 대문자 + 스네이크 케이스

- 변수 & 함수 : 카멜케이스
