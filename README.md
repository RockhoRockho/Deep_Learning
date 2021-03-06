# Deep_Learning_Tensorflow & Pytorch
Deep Learning

## Day 1 (2021-10-27)
- 딥러닝 상수, 변수, 플레이스홀더 학습

## Day 2 (2021-11-01)
- 딥러닝 선형회귀 이론
- 경사하강법 
- 로지스틱회귀 이론

## Day 3 (2021-11-02)
- 딥러닝 개요
- 딥러닝 기초수학학습

## Day 4 (2021-11-03)
- 신경망 데이터 표현(0, 1, 2, 3, 4, 5차원 텐서)
- 신경망 구조 학습
  - 퍼셉트론
  - 뉴련의 수학적 표현
  - 완전 연결 계층 수학적 표현
  - 논리회로(AND, OR, NAND, XOR 게이트)
  - 다층 퍼셉트론
  - 활성화 함수(Step Function, Sigmoid Function, ReLU, tanh, softmax, Identity Fuction)
  - 3층 신경망 구현
  - 다중로지스틱 회귀 

## Day 5 (2021-11-04)
- 모델학습과 손실함수(원-핫인코딩, 평균절대오차, 평균제곱오차, 교차엔트로피오차)
- 경사하강법학습(볼록함수, 비볼록함수, 전역최적값/지역최적값, 학습률, 안장점)

## Day 6 (2021-11-06)
- 신경망학습
  - 단순한 신경망 구현(AND/OR/NAND/XOR Gate)
  - 다중 클래스 분류(MNIST, 2층신경망 구현)

## Day 7 (2021-11-08)
- 군집화, K-근접이웃 이론 학습

## Day 8 (2021-11-09)
- 오차역전파 학습
  - 활성화함수 역전파(시그모이드, ReLU)
  - 행렬 연산에 대한 역전파
  - MNIST 분류 with 역전파

## Day 9 (2021-11-10)
- 최적화 방법(확률적 경사하강법, SGD의 단점, 모멘텀, AdaGrad, RMSProp, Adam)
- 가중치 초기화
- 비선형 함수에서의 가중치 초기화
- 배치정규화
- 과대적합/과서적합
- 규제화
- 드롭아웃
- 하이퍼 파라미터
- MNIST분류

## Day 10 (2021-11-11)

### 합성곱 신경망 CNN 학습
- 완전 연결계층과의 차이
- 합성곱 연산
- 패딩과 스트라이드
- 풀링
- 2차원 이미지에 대한 필터 연산 예시
- 3차원 데이터의 합성곱 연산
- 합성곱 신경망 구현
- 대표적인 CNN 모델(LeNet-5 , AlexNet, VGG-16)
- CNN 학습구현 - Mnist

## Day 11 (2021-11-15)

- 자연어처리 학습
  - CBOW, Skip-Gram Embedding, Word2Vec
  - 순환신경망 (BPTT, Truncated BPTT, Time RNN Layer)
  - LSTM(forget gate, input gate, output gate

## Day 12 (2021-11-16)

- 텐서플로우 학습(객체, 차원&연산, 난수생성, 즉시실행모드(Eager Mode), <->넘파이, 타입변환, 오토그래프, `@tf.function`, 변수생성, 자동미분(autograd))
- 간단한 신경망 구조(퍼셉트론학습(가중치 업데이트), AND/OR/XOR Gate 학습
- 시각화 사용(XOR Gate)

## Day 13 (2021-11-17)

- 텐서플로우 회귀분석 모델 학습
> 선형회귀, 다항회귀, 로지스틱 회귀학습

## Day 14 (2021-11-18)

- 케라스 학습(Dense, Activation, Flatten, Input, Sequential, subclassing, 모델 컴파일)
- 텐서플로우(변수, 인덱싱, 슬라이싱, Transpose, 연산, 예제)학습

## Day 14 (2021-11-19)

- 케라스 학습(Dense, Activation, Flatten, Input, Sequential, subclassing, 모델 컴파일)

## Day 15 (2021-11-20)

- 케라스 모델 가중치 확인
- 케라스 모델 컴파일 학습
- 모델 훈련 평가 및 예측
- Mnist 예제를 통한 모델구성(modules import 데이터셋 로드, 데이터 전처리, 모델 구성, 모델 컴파일, 모델 학습, 학습결과 시각화, 학습된 모델을 통햬 값예측, 모델 저장과 복원)
- 콜백(ModelCheckpoint, EarlyStopping, LearningRateScheduler, Tensorboard)

## Day 16 (2021-11-23)

- 케라스 보스턴 주택 가격 모델

## Day 17 (2021-11-24)

- 케라스 자동차 연비 예측 모델
- 케라스 Fashion-Mnist 모델예제

## Day 18 (2021-11-25)

- 케라스 다양한 학습 기술
- 고속 옵티마이저, 배치 정규화, 규제화, 드롭아웃 학습

## Day 19 (2021-11-29)

- Data API를 이용한 Fashion-Mnist 

## Day 20 (2021-11-30)

- 행렬곱, BMM
- Linear Layer
- GPU 사용법
- 손실함수

## Day 21 (2021-12-02)

- 손실함수 마무리
- 사이킷런 모듈 학습
- Iris data, Titanic data로 모델학습
- 케라스 CNN 신경망 

## Day 22 (2021-12-03)

- 소핑몰 고객 주문데이터 

## Day 23 (2021-12-13)

- 케라스 CNN CIFAR10을 이용한 

## Day 24 (2021-12-14)

- 케라스 전이학습
  - dog vs cat 자료를 이용한 모델학습
  - 사전 훈련된 모델 사용
  - feature Map 

- 케라스 텍스트 처리 및 임베딩
  - IMDB 데이터를 활용한 모델학습
  - Word2Vec
    - gensim으로 학습된 단어 임베딩을 keras에서 불러오기
    - keras에서 Word2Vec 직접학습
    - 사전 훈련된 단어 임베딩 사용하기 Glove임베딩

## Day 25 (2021-12-15)

- 파이토치 기초학습
  - 텐서연산, 조작, cpu<->gpu
  - Autograd(자동미분)
  - nn & nn.functional
  - Torchvision

- 파이토치 신경망 생성(선형회귀 모델)
  - MNIST 모델학습(전처리, 데이터로드, 신경망, 손실함수, 옵티마이저, 모델학습, 모델 저장 및 로드, 모델테스트)
  - GPU 설정 후 학습

## Day 26 (2021-12-17)

- 파이토치 CIFAR10 모델학습
- 파이토치 사전훈련 모델로드 후 사용
- 파이토치 RNN 분류 모델학습

- 텐서플로우 수업
  - 모델구현
  - 트레이닝 스크립트 구현
  - Data Augmentation
  - Transfer Learning

## Day 27 (2021-12-21)

- 자연어처리
  - 텍스트처리
  - 영어처리
  - 한국어처리
  - 토큰화 학습
- Bag of Words(BoW)
- 문서 단어 행렬(DTM)
- 어휘 빈도-문서 역빈도(TF-IDF) 분석


## Day 28 (2021-12-22)

- 키워드 분석
  - 단어빈도수 측정
  - 단어빈도 시각화
  - 워드클라우드
  - squarify 트리맵 시각화

- 군집분석
  - scikt-learn, scipy를 이용한 계층적 군집화
  - scikt-learn을 이용한 비계층적 군집화


## Day 29 (2021-12-23)

- 문서 분류
  - Scikit-learn(로지스틱회귀, 서포트벡터머신, 나이브베이스 분류기, 결정트리, XGBoost를 이용한 분류)
  - 교차 검증
  - 정밀도와 재현율
  - 그리드 검색을 이용한 파라미터 최적화

- 의미 연결망 분석
  - n-gram
  - 어휘 동시 출현 빈도의 계수화
  - 중심성 지수(연결중심성, 위세 중심성, 근접 중심성, 매개 중심성, 페이지랭크)

- 토픽 모델링
  - 잠재 의미 분석(Lsi Model)
  - 잠재 디리클레 할당(Lda Model)
  - Gensim을 이용한 토픽 모델링
  - 토픽 모델링 시각화

- 임베딩
  - 인코딩(정수 인코딩, 원핫인코딩)
  - IMDB 데이터
  - T-SNE
  - Gensim을 이용한 Word2Vec

## Day 30 (2021-12-27)

- 순환 신경망(IMDB데이터로 모델학습)
  - LSTM, GRU 적용
- 합성공 신경망(IMDB, Reuters 데이터적용)
- 케라스 Word2Vec 구현
  - Skipgram, CBOW 
- CNN 스팸메일 분류 

## Day 30 (2021-12-30)

- 감정 분석 자연어처리
  - 감정어휘 사전을 이용한 감정상태분류
  - 네이버 영화 리뷰데이터, 네이버 쇼핑리뷰데이터 기계학습
