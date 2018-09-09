# pythorch - CRNN( Convolutional-recurrent-Neural-Network )

네이버 영화 평점 예측 공모전 관련 코드 업로드 합니다.

Pythorch 로 작성이 되어있었으며,

네이버에서 자체 Charachter-Embedding 데이터를 제공해 주었습니다.


 Charachter-Embedding 단어단위의 정보를 의미있는 정보로 변환해주기위해서 
 
 RNN을 사용했으며,  간단한 Text-Classification에 많이 사용되는 CNN과 결합하였습니다.
 
 ## CRNN ( Convolutional recurrent Neural Network ) 
 
 CNN에서는 문장의 다양한 패턴을 학습하기 위해서 Inception Module을 사용했으며,
 
 RNN과 결합되어 Gradient Vanishing 문제가 발생 할 수 있으므로, Residual Connection을 
 
 적용하였습니다.
 
 또한, 학습시간의 단축을 위하여, 동적 학습을 진행했습니다.
 
