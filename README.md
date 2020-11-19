<h1 align="center">COVID-19 Face Mask Detection  </h1>

<h4 align="center">코로나의 장기화에 따라 OpenCV, TensorFlow, Keras를 활용하여 마스크 감지 시스템 제작
</h4>

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
![Python](https://img.shields.io/badge/python-v3.6+-white.svg)
![tensorflow](https://img.shields.io/badge/tensorflow-1.15.2-red.svg)
![keras](https://img.shields.io/badge/keras-v2.3.1-orange.svg)
![numpy](https://img.shields.io/badge/numpy-1.18.2-yellow.svg)

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;  

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src=https://raw.githubusercontent.com/sunnyleeee/OpenSource_Team-F/main/dataset/with_mask/mask_img%20(22).png width=500 height = 300>  

#  
##  
### 1. 기획 계기

현재 전 세계적으로 코로나가 고조되고 있으며, 몇 나라를 제외하고 아직 많은 나라들이 코로나로 인하여 고통을 호소하고 있다.  
우리는 이미 창궐한 상황에서 가장 중요한 것은 마스크라고 생각했다. 실제로 확진자와 같은 장소에 있었더라도 마스크를 정확히 착용한 사람은 비 접촉자로 간주하며, 질병관리본부 자료를 보았을 때, 마스크를 제대로 착용하는 것 하나로 감염률이 100%에서 1.5%로 현저히 감염률이 감소한 것을 확인할 수 있었다.  
이런 결과로 보아 사람이 많이 모이게 되는 지하철 혹은 음식점 및 카페를 통과할 때 마스크의 착용 유무를 한 번 더 집어준다면 코로나의 확산 방지에 도움이 될 것이라 생각되어 프로젝트로 구현하게 되었다.  

#  
##  
### 2. 개발환경 선택  
<img src=environment.png width=550 height = 120>  
각기 다른 개발환경에서 오픈소스와 OpenCV, TensorFlow, Keras를 활용하며 더 좋고 매끄러운 결과를 위해 여러 시도를 하였다.  
jupyter notebook, pycharm, spider 각기 다른 환경에서 매끄러운 결과를 위해 증진하였고 결과는 Google에서 만들어진 트레이닝 알고리즘(MobileNet_v2)을 사용하는 점을 생각하여 매끄럽게 연결되는 Google Colab 환경을 선택하게 되었다.  
추가로 오픈소스와 라이브러리 활용에 최적화 되어있는 Linux_Ubuntu를 사용하였다.  

#
##
### 3. 프로젝트 내용  
**1단계(오픈소스 활용)**  
 -오픈소스를 이용한 얼굴인식/ keras를 활용한 마스크검사(딥러닝)  
**2단계(데이터 라벨링 테스트)**  
 -팀원들 마스크사진 및 기타 마스크 사진 업로드  
**3단계(알고리즘 커스텀마이징)**  
 -오픈소스 활용 및 알고리즘 수정  
**4단계(결과 확인)**  
 -결과 확인 및 버그 수정  
 -Demo 제작

#  
##  
###  4. Model Selection  

------------------------------------------
### Member_git_address
>>### 박진홍  [![Generic badge](https://img.shields.io/badge/github-go-red?logo=github)](https://github.com/HallymhongE)
>>### 김기훈  [![Generic badge](https://img.shields.io/badge/github-go-orange?logo=github)](https://github.com/daedu0813)
>>### 윤찬우  [![Generic badge](https://img.shields.io/badge/github-go-green?logo=github)](https://github.com/GitCWoo)
>>### 용권순 [![Generic badge](https://img.shields.io/badge/github-go-blue?logo=github)](https://github.com/reversesky)
>>### 이선재  [![Generic badge](https://img.shields.io/badge/github-go-blueviolet?logo=github)](https://github.com/sunnyleeee)
>>### 유예린  [![Generic badge](https://img.shields.io/badge/github-go-ff69b4?logo=github)](https://github.com/yl-zzzz)
![Hits](https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https://github.com/sunnyleeee/OpenSource_Team-F)  
