# 딥러닝 학습 과정

##### 모든 Parameter θ를 초기화

 ##### => Cost Function 상의 가장 낮은 지점을 향해 나아가며 

##### => 선택한 Gradient descent method를 적용해 θ를 계속 update



### 1) Weight Initialization

- Xavier Initialization : Sigmoid, tanh 할 때
- He Initialization : Relu 할 때



### 2) Weight regularization

- L1 regularization -> Lasso
- L2 regularization -> Ridge



### 3) Advanced gradient descent algorithms (최적화)

- SGD ( 확률적 경사 하강법) : 하나의 Training data (Batch size = 1) 마다 Cost를 계산하고 바로 Gradient descent를 적용하여 weight를 빠르게 update
- Mini-Batch SGD : Training data 에서 일정한 크기 ( Batch size )의 데이터를 선택하여 Cost function 계산 및 Gradient descent를 적용
- Adam



## < 오버피팅 피하는 방법>

### 1) Dropout

​     : Training을 진행할 때 매 Batch 마다 Layer 단위로 일정 비율 만큼의 Neuron을 꺼뜨리는 방식으로 적용



### 2) Batch Normalization





