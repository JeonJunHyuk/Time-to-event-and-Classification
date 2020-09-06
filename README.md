# Time-to-event-and-Classification

* Possibilities of 5 primary cancers prediction: 5대 주요 암 발병확률 예측 모델 ppt

* LOS_prediction Final-Report.pptx: 입원기간 예측 모델 ppt

* keras-wtt-rnn-engine: 시간에 따른 사건 발생(Time-to-Event) 확률 예시 코드

* Time-to-Event 시각화

<img width="769" alt="time-to-event" src="https://user-images.githubusercontent.com/49193062/92318743-be0da480-f04b-11ea-8542-56cd0ccaff30.PNG">

Weibull 분포를 이용한 pdf, loss 구성으로 시간에 따른 사건 발생 확률을 구한다.

좌측 상단 그래프: unit 5 의 현재 train set 의 상태를 time step 에 따라 시각화한 것.

좌측 하단 1: 현 시점에서 사건 발생확률을 time step 에 따라 pdf 로 보여준다.
좌측 하단 2: 각 time step 에서 pdf 를 그려 전체 시점에서 언제 발생 확률이 높은지 보여준다.
좌측 하단 3: 현 시점에서 remaining time 의 기대값을 보여준다.

우측 그래프: 여러 Unit 중 선택한 Unit 의 Weibull distribution에 따라 failure rate, reliability, mean life 를 보여준다. 아래가 그 식.

<img width="526" alt="Weibull 식" src="https://user-images.githubusercontent.com/49193062/92318897-7daf2600-f04d-11ea-92d6-a7f22c73919f.PNG">

Time-to-Event: https://github.com/ragulpr/wtte-rnn
Weibull distribution: https://www.weibull.com/hotwire/issue14/relbasics14.htm
