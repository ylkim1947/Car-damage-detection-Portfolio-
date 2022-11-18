## 본 프로젝트의 목적
본 프로젝트는 데이터(학습+테스트)들의 전처리에 따른 자동차 손상 탐지 모델의 성능 개선을 목표로 수행되었습니다. 자동차 손상탐지 모델은 가장 큰 취약점 중 하나는  소비자가 촬영한 이미지와 학습데이터를 제작할 때 선별한 이미지의 퀄리티 차이가 클 경우 모델의 성능이 저하된다는 것입니다. 학습 데이터의 사진들은 빛의 양이나, 거리 등등이 어느정도 일정하게 유지가 되지만 소비자들의 이미지는 그렇지 못한 경우들이 있습니다. 이번 프로젝트에서는 모델에 입력될 이미지들의 빛 혹은 색상 차이를 줄이는 방식의 전처리 단계를 추가하여서 모델의 성능 개선을 시도해보았습니다. 

[요약]

실제데이터에서 발생할 수 있는 '빛'관련 노이즈를 통제 할 수 있는 전처리 기술 성능 비교 

# Car-damage-detection-Portfolio (cp 1)-
## 0. 문제 정의

## 1. Goal of this project
학습데이터 전처리에 따른 손상탐지 모델 비교

## 2. Experiment design
  
   (1) 정상데이터 (비교군)
   
   (2) Greyscale 방식
   
   (3) Contrast 방식
   
   (4) RGB 값을 해당 이미지의 평균값으로 나눠서 만든 데이터
  
    (TEST data): 어두운 데이터
   
## 3. Data 
  -roboflow:
  
  -kaggle:
  
## 4. data preprocessing 
   -Adding noise
   
   -augmentation of images 
   
   -Nomalization

## 5. Models 

YOLOv5, ~RCNN~
