### <캡스톤 디자인 - 모기 개체 수 예측>
​
​
# 0. 목차 
> [1. 목적](#1-목적)  
> [2. 프로젝트](#2-프로젝트)    
> [3. 웹 페이지](#3-웹-페이지)

​
​
# 1. 목적  
> * 플라스크를 이용한 웹 서비스 제공
> * 머신러닝으로 모기 출현등급을 예측하는 서비스를 제공하여 등급별 시민 행동 요령 안내 

​
​
# 2. 프로젝트
### 2.1. 프로젝트 소개
> * 2020년도 컴퓨터공학과 캡스톤 디자인
> * 2020.03 ~ 2020.12   
![image](https://user-images.githubusercontent.com/82797757/121142133-a7180f00-c876-11eb-9498-02de27b4811e.png)
> * 지구 온난화에 의한 기후 변화로 모기 개체 수가 증가함에 따라 모기와 관련된 질병 감염률이 증가하고 있음. 이를 예방하기 위해 기상청에서 웹 크롤링으로 온도, 습도, 일출시간 등의 데이터를 추출하여 기온과 모기의 상관관계로 모기 개체 수를 예상하고 이에 대한 행동 강령을 제공 

​
​
### 2.2. 프로젝트 진행 과정
> 1. 데이터 수집   
>     * 날짜, 평균기온, 최고기온, 최저기온, 일교차, 강수량, 풍속, 습도, 전운량, 일조시간, 일몰시간, 모기 채집 수로 구성
>     * 훈련 데이터 : 2017 ~ 2018년도 / 테스트 데이터 : 2019년도
![image](https://user-images.githubusercontent.com/82797757/121142244-c2831a00-c876-11eb-87fe-f870802afa51.png)
> 2. 상관관계 
>     * 온도와 관련된 데이터는 관련성이 높음
>     * 풍속과 관련된 데이터는 관련성이 낮음   
![image](https://user-images.githubusercontent.com/82797757/121142607-21489380-c877-11eb-839a-2f24cd3b5665.png)
> 3. 예측 모델 선정   
>    * 정확도가 가장 높은 XGB 모델 사용   
![image](https://user-images.githubusercontent.com/82797757/121142801-51903200-c877-11eb-916a-2c2064d4616d.png)
> 4. 웹 페이지 제작

​
​
### 2.3. 개발 환경
> * Flask Framework
> * 툴 : Anaconda – Jupyter Notebook
> * 언어 : Python, HTML, CSS

​
​ 
# 3. 웹 페이지
![image](https://user-images.githubusercontent.com/82797757/121143012-88fede80-c877-11eb-8400-fff1c50f0ebe.png)
![image](https://user-images.githubusercontent.com/82797757/121143066-987e2780-c877-11eb-9ad7-2a1fcd321100.png)
![image](https://user-images.githubusercontent.com/82797757/121143134-ac298e00-c877-11eb-8771-48d61f696849.png)

