# 1. Shooting game

 ![자연어처리-002 (2)](https://user-images.githubusercontent.com/94778681/151274968-1c50579e-4348-4bac-b8d5-db2ae49a3dc2.jpg)

## 1.1 사용 기술 
 Python 3.8 , Pygame , Pycharm
 
## 1.2 개발 일정
21.12.1 ~ 21.12.3 기본 코드 구현  
21.12.4 ~ 21.12.5 컨셉 구체화 및 보완점 제시  
21.12.6 ~ 21.12.7 에러 해결 및 보완점 해결  
21.12.8 ~ 21.12.10 마무리 작업 및 발표

## 1.3 코드
https://github.com/kimch963/test1/blob/main/pygame.py

## 1.4 구현 기능
메인화면(시작, 나가기, 도움말, 시나리오)  
게임캐릭터 선택 기능  
게임 실행 화면  
게임 결과 화면  


## 1.5 결과
![슈팅1](https://user-images.githubusercontent.com/94778681/151296510-e10e2714-51e1-4b24-9887-59392a5778bc.PNG)
![슈팅2](https://user-images.githubusercontent.com/94778681/151296516-0dc76422-32fd-422f-a340-e65802bb8d49.PNG)
![슈팅3](https://user-images.githubusercontent.com/94778681/151296517-5089eb3f-2ecc-45ee-b075-a84e60f2e64d.PNG)
![슈팅4](https://user-images.githubusercontent.com/94778681/151296526-5aab9ace-0ff4-4ed6-b26b-1cdcd23bae09.PNG)


## 1.6 보완해야 할 점
시간의 부족으로 인해 캐릭터 별 상이한 기능을 구현하지 못함  
class 개념을 제대로 숙지하지 못해 다수의 미사일을 구현하는데 많은 시간이 소요됨

***
---

# 2.머신러닝을 이용한 암 진단 
![자연어처리-003](https://user-images.githubusercontent.com/94778681/151276614-9073d572-2259-45a8-88db-a26c53483b6a.jpg)

## 2.1 사용 기술
Jupyter Lab, Python 3.8 ,Tensorflow 2.7 , Pandas, Numpy 
## 2.2 개발 일정
22.1.5 ~ 22.1.6 구조 파악 및 신경망 제작  
22.1.7 에러해결 및 발표

## 2.3 코드
https://github.com/kimch963/portfolio/blob/main/diabetes_homework.ipynb

## 2.4 구현 기능

인공신경망 학습  
학습된 인공신경망으로 8개의 피쳐 데이터 입력시 암 진단 예측값 제공

## 2.5 결과
![암 1](https://user-images.githubusercontent.com/94778681/151297258-3bf9bc29-b0e1-445c-a177-3b534a95fba2.PNG)
![암 2](https://user-images.githubusercontent.com/94778681/151297266-9cceba85-9d37-4d7e-ab63-27e72a5f900a.PNG)


## 2.6 보완해야 할 점
데이터의 개수가 약 800개 정도로 적어 더 많은 데이터의 필요성  
다양한 방법으로 신경망을 제작하여 정확도를 상승시키는 방법의 필요성

***
---

# 3. LSTM을 이용한 비트코인 실시간 예측
![자연어처리-001 (1)](https://user-images.githubusercontent.com/94778681/151271099-c755a3d4-9144-418f-8b4b-987bfebbb715.jpg)

## 3.1 사용 기술
Colab, python 3.8, tensorflow 2.7, Numpy, Pandas, PyUpbit, Scikit-learn

## 3.2 개발 일정
22.1.3 주제 선정 및 계획  
22.1.4 데이터 수집, 전처리, 모델구성  
22.1.5 ~ 22.1.6 모델 개선, 시각화  
1.7 결과 정리 및 발표 

## 3.3 코드
https://github.com/kimch963/portfolio/blob/main/bitcoin_LSTM.ipynb

## 3.4 구현 기능
과거 비트코인 데이터를 인공신경망에 학습  
학습된 신경망을 활용해 다음 1분의 종가 예측

## 3.5 LSTM을 사용한 이유
과거의 데이터를 이용하여 미래의 데이터를 예측하는 프로젝트의 특성상, 루프가 들어있고 과거의 데이터가 미래에 영향을 줄 수 있는 RNN 알고리즘중 LSTM을 사용해야 한다고 생각했습니다.

## 3.6 결과
![image](https://user-images.githubusercontent.com/94778681/151298775-5ae4b33b-055a-404e-9980-a2ebafbbddc6.png)
![image](https://user-images.githubusercontent.com/94778681/151298832-01d43531-18af-4e05-b994-7adaef7934cc.png)
![image](https://user-images.githubusercontent.com/94778681/151298848-a32a994c-b7a3-4f48-a578-af00e9dcbee9.png)

## 3.7 보완해야 할 점
정규화 과정에서 이상치가 있는지 확인하는 과정을 추가해 이상치를 제거해야 함  
학습 결과와 테스트 예측치가 너무 이상적으로 부합하는 이유를 찾지 못했음
***
---

# 4. 자연어 처리를 이용한 청소기 리뷰 감성분석
![image](https://user-images.githubusercontent.com/94778681/151272847-08bb7e55-8244-4206-8b8e-ffc303a193dc.png)

## 4.1 사용 기술
Colab, python 3.8, tensorflow 2.7, Numpy, Selenium, BeautifulSoup, Konlpy, Github

## 4.2 개발 일정
22.1.8 ~ 22.1.10 데이터 크롤링  
22.1.11 데이터 전처리  
22.1.12 감성사전 제작 및 감성분석  
22.1.13 에러 해결, 점수화 및 시각화  

## 4.3 코드
https://github.com/kimch963/portfolio/blob/main/vacuum_cleaner_natural_language_processing.ipynb

## 4.4 구현 기능
리뷰 분석을 통한 감성분석  
등장 단어 빈도수를 기반으로 한 감성 점수화  
리뷰 워드클라우드화 및 모델별 점수 

## 4.5 결과 

<img src="https://user-images.githubusercontent.com/94778681/151299047-96308dad-5cb6-4d7a-9e81-e01ebd67b191.png" width="600" height="700"/>
<img src="https://user-images.githubusercontent.com/94778681/151299068-d8030ed7-5cfa-4e48-ad7f-7f26f3739019.png" width="600" height="700"/>
<img src="https://user-images.githubusercontent.com/94778681/151299098-adcfca22-69e6-4f7e-8fba-6915ef84203c.png" width="600" height="700"/>

## 4.6 보완해야 할 점
자연어 처리 라이브러리를 사용했을 때 너무 오랜 시간이 걸려 데이터 양을 크게 하지 못한 점  
협업 도구(GitHub, Colab) 의 사용 방법을 익혀 불필요한 시간 낭비를 줄여야 함
