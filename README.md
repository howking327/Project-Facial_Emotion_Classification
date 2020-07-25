# Project-Facial_Emotion_Classification :smile: :angry: 

Python-Jupyter Notebook으로 MachineLearning, DeepLearning을 이용한 감정분석 프로젝트입니다.  
(2020/02/10 ~ 2020/03/20)

### ▶ Concept
사람의 표정에서 나타나는 감정을 분석하여 소비자 패턴 분석이나 마케팅등에 활용하는 사례가 증가함에 있어 실습 자료를 바탕으로 더 나은 결과를 찾기위한 적용 프로젝트 입니다.

### ▶ Tool
- **Language** : Python  
- **Tool** : Jupyter Notebook

## Collaborators
- [howking327](https://github.com/howking327)
- [yiy829](https://github.com/yiy829)
- [jaden7856](https://github.com/jaden7856)


## Data Set
- 출처 및 구성
![dataset](https://user-images.githubusercontent.com/57980363/78030703-75b3d180-739d-11ea-97c6-3216bd265827.PNG)
![1](https://user-images.githubusercontent.com/57980363/78030749-8a906500-739d-11ea-9b6e-55f4eaa1274c.PNG)
감정별 Image 구성
![2](https://user-images.githubusercontent.com/57980363/78030768-9419cd00-739d-11ea-8a04-700f195ca194.PNG)
성별 Image 구성
![3](https://user-images.githubusercontent.com/57980363/78030784-9b40db00-739d-11ea-9709-e5f211fe9757.PNG)
연령대별 Image 구성

## MachineLearning
![ml](https://user-images.githubusercontent.com/57980363/78032546-21f6b780-73a0-11ea-9460-2b613403ca90.PNG)
![rf](https://user-images.githubusercontent.com/57980363/78031157-1d310400-739e-11ea-8054-051fa6800075.png)

## DeepLearning
![67](https://user-images.githubusercontent.com/57980363/88459754-9e268500-ced2-11ea-80f0-087d9c23e5f1.png)

## Source Code
- DeepLearning
- MachineLearning
- Pixelize : Image data에 눈,코,입 벡터 location에 dot 생성
- Processing&Crop : Data 정제 및 배경 제거 ( Focus Image )
- Vectification&Division : 벡터 location 별 구역 설정하여 각각의 개별 눈,코,입 Image 생성 
  
## Improvements
  
- **Machine Learning과 DeepLearning model에 사용된 Image Data를 공통화 작업**  
지금 구현 상태로는 개별적으로 적용하기 위한 데이터 처리를 하였습니다. 두 model 간 정확한 비교를 위한 데이터 공통화가 필요합니다.
  
- **Data set의 추가 확보 및 pumping을 통해 정확도 개선**  
DeepLearning model의 경우에도 그다지 성과있는 정확도가 도출되지는 않았습니다. Data의 추가적인 확보가 필요합니다. + 추가 : Algorithm 수정도 고려

- **실제 외부 Data를 이용한 결과 도출을 위해 model ensemble**  
내부적으로 구분지은 test data가 아닌 외부 data를 입력하였을 때 분석 결과 도출을 위해 DeepLearning model의 파트별 emsemble이 필요합니다.

- **추천 Algorithm 으로 확대**  
감정분석 결과에 따른 추천 서비스로 확대하여 프로젝트를 확장할 계획에 있습니다.
