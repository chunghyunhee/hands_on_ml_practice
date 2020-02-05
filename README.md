# hands on machine learning
2020 상반기 진행하는 group stduy

## 날짜 및 장소
매주 수, 토 오전 11시, 스터디룸, 분석실

## 목적
- 수리통계학, 회귀분석, 표본론, 응용확률론 등 통계학을 기반으로 다양한 machine learning 모델을 이해하고
모델링을 해보기 위한 공부를 진행함. 최종적으로 실제 데이터를 바탕으로 한 프로젝트를 완성하는 것을 목표로
진행하고, 이론은 논문을 통한 구현으로 함께 이해한다. 
- 최종적인 목표로는 데이터형태에 따라 적절한 모델설계와 하이퍼파라미터 튜닝이 가능하며 의미있는 결과도출을 통해 문제해결방안을 제시하는 것을 목표로 한다. 


## 주교재 
hands on machine learing - Orelly

---
## context
### chapter02. 머신러닝 프로젝트 처음부터 끝까지

1. 실제 데이터 작업하기 
2. 큰 그림 보기(성능지표, 가정검색)
3. 데이터 파악하기
4. eda(cor, 특성조합)
5. 머신러닝모델 적용가능 dataset
6. 모델 선택과 훈련방법
7. 세부 튜닝방법

### chapter03. 분류
1. MNIST dataset활용
2. 이진분류기 훈련
3. 성능측정
4. 다중분류
5. 에러분석
6. 다중레이블 분류
7. 다중 출력분류


### chapter04. 모델훈련
1. 선형회귀
- 회귀 모델 min{J(theta)}계산방법
- 계산복잡도 비교
2. 경사하강법
- learning rate term 
- derivitive term(배치경사, 확률적 경사, 미니배치 경사하강)
3. 다항회귀
4. 학습곡선
- 과대적합 or 과소적합을 파악
- 교차검증(cross_val_score())
- 학습곡선
5. 규제가 있는 선형모델 
- ridge regression
- lasso regression
- elasticnet regression
- 조기종료 방법
6. 로지스틱 회귀
- logistic의 logit fuction활용이유
- cost function
- decision boundary
- softmax regression(다중클래스 지원)

### chapter05. SVM
1. 선형SVM분류
 - 소프트마진 분류(=비분리 SVM)
 - 하드마진 분류(=분리 SVM)
2. 비선형 SVM 분류
 - 커널법을 사용한 비선형 SVM
3. SVM 회귀
 - 선형 SVM회귀
 - 비선형 SVM회귀
4. SVM 이론
 - 분류기, 회귀, 온라인 SVM

### chapter06. 결정트리
1. 결정트리 학습과 시각화
2. 예측하기(결정트리 결과 해석 방법, 의미하는바)
3. 클래스 확률 추정
4. CART 훈련 알고리즘
5. 계산 복잡도
6. 지니 불순도 or 엔트로피
7. 규제 매개변수
8. 회귀
9. 불안정성

### chapter07. 앙상블 학습과 랜덤 포레스트
1. 투표기반 분류기(voting)
2. 배깅과 페이스팅(bagging)
3. 랜덤패치와 랜덤 서브스페이스 : 특성 샘플링
4. 랜덤포레스트 : 결정트리를 배깅방식으로 앙상블 학습
 - 엑스트라트리 : 무작위성 강화
 - 특성 중요도 : 오버피팅을 줄이는 하나의 방법
5. 부스팅
 - Adaboosting : 오차에 가중치를 부여하여 강분류기 만든다
 - Gradient Boosting : 잔여오차를 하나의 분류기로 (따로) 학습시켜 오차를 줄이는 강분류기 방식
6. 스태킹


# Reference
https://github.com/ageron/handson-ml <br>
https://1ambda.github.io/data-analysis/ <br>
http://www.riss.kr.proxy.cau.ac.kr/search/detail/DetailView.do?p_mat_type=be54d9b8bc7cdb09&control_no=8acda0de8560581bffe0bdc3ef48d419


