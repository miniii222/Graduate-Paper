# Graduate-Paper
2020.02 통계학 석사 졸업 예정

## Session-Based Recommendation with RNN
### 참고 논문
1. [***Session-Based Recommendations with Recurrent Nerual Network***](https://arxiv.org/pdf/1511.06939.pdf) (original Paper)
Balázs et al., ICLR, 2016.
- RS에 RNN 적용
- https://github.com/hidasib/GRU4Rec (original code) : theano로 구현, RecSys2015
- https://github.com/Songweiping/GRU4Rec_TensorFlow : theano -> tensorlow implementation
- https://github.com/khlee88/GRU4Rec_tutorial : tensorflow tutorial
- https://github.com/pcerdam/KerasGRU4Rec : keras ver
- https://github.com/yhs-968/pyGRU4REC : pyTorch ver
  
2. [***Improving Session Recommendation with Recurrent Neural Networks by Exploiting Dwell Time***](https://arxiv.org/pdf/1706.10231.pdf)
Alexander et al., 2017
- 

3.[***Incorporating Dwell Time in Session-Based Recommendations with Recurrent Nerual Networks***](http://ceur-ws.org/Vol-1922/paper11.pdf)
Veronika et al., RecSys2017


### 과정 정리
- [2019-08-23] 교수님께 논문 방향 컨펌. 모델 설명 잘 정리할 수 있을지..?
- [2019-08-24] keras 소스코드 이용해서 모델 돌아가는 거 확인!(GPU 사용), class를 이용해서 데이터 로드하는 거까지 대강 파악! SessionDataLoader의 iter를 이용하여 yield되는 inp, target, mask 원리 파악이 더 필요함
