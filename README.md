# Car-damage-detection-Portfolio (cp 1)
### "학습데이터 전처리에 따른 손상탐지 모델 비교" 프로젝트



## 1. Goal of this project

본 프로젝트는 데이터(학습+테스트)들의 전처리에 따른 자동차 손상 탐지 모델의 성능 개선을 목표로 수행되었습니다. 자동차 손상탐지 모델은 가장 큰 취약점 중 하나는  소비자가 촬영한 이미지와 학습데이터를 제작할 때 선별한 이미지의 퀄리티 차이가 클 경우 모델의 성능이 저하된다는 것입니다. 학습 데이터의 사진들은 빛의 양이나, 거리 등등이 어느정도 일정하게 유지가 되지만 소비자들의 이미지는 그렇지 못한 경우들이 있습니다. 이번 프로젝트에서는 모델에 입력될 이미지들의 빛 혹은 색상 차이를 줄이는 방식의 전처리 단계를 추가하여서 모델의 성능 개선을 시도해보았습니다. 

[요약]

실제데이터에서 발생할 수 있는 '빛'관련 노이즈를 통제 할 수 있는 전처리 기술 성능 비교 





## 2. Experiment design
  
<img src="https://user-images.githubusercontent.com/51395479/208250322-86816919-3d1b-4427-af6e-cafee944fed7.png" width=820 height=300/>

 
     
## 3. Data 
<img src="https://user-images.githubusercontent.com/51395479/208250496-acbc6bc4-3494-4fbd-9103-d4089a26ef46.png" width=820 height=350/>

  
## 4. Model: **YOLOv5**


<img src="https://user-images.githubusercontent.com/51395479/208250689-c00e8ddb-d081-4ff2-bdfa-39f9f59ae70b.png" width=820 height=350/>


## 5. Results

<img src="https://user-images.githubusercontent.com/51395479/208250801-d56b96b2-50bf-487c-a214-e3a1c41e6acf.png" width=820 height=380/>

<img src="https://user-images.githubusercontent.com/51395479/208250804-0f3d7ab6-1e64-4217-a4dc-8ad3e83819af.png" width=820 height=380/>


