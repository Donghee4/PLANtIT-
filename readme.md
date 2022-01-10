# 파일 목록 #
ResNet_crop_name, ResNet_crop_risk, ResNet_crop_disease, custom_model

## 프로젝트에 사용한 모델 2가지 ##
**작물의 질병이름과 risk(진행정도)를 나타내기 위해 모델 2가지를 사용함**
1. ResNet_crop_disease : 작물의 질병을 분류하기 위한 모델 **[핵심모델]**
2. ResNet_crop_risk : 작물의 진행정도(risk)를 분류하기 위한 모델

## 사용되지 않은 모델 2가지 ##
<u>작물의 이름은 모델을 구축했으나 필요없어서 사용하지 않음</u>

1. custom_model : 시도했으나 낮은 정확성을 이유로 탈락시킨 모델
2. ResNet_crop_name : 작물의 종류를 분류함. 하지만 질병 분류 모델에서 이름을 알 수 있으므로 사용하지 않음

# 작동 화면 #
![plantit](https://user-images.githubusercontent.com/84669207/148690742-fbff2e6d-d313-4404-8fc9-1621ce9231b1.gif)
