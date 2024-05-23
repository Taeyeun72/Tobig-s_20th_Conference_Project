# Viewtfolio: 나만의 성향을 반영한 최적 포트폴리오
- 최적의 주식 포트폴리오를 구성해주는 모델 개발
  - **역할**: Black-Litterman 모델에 포함되는 주식 수익률 예측 모델링 (PatchTSMixer 모델 사용)
  - Black-Litterman 모델과 Fear-Greed 지수를 활용한다.
  - 파일 구분
    - 06_Bi-LSTM_Stock_Price_Prediction: PatchTSMixer 모델과의 대조군으로 Bi-LSTM 이용
    - 07_MLP-Based_Stock_Price_Prediction(4): PatchTSMixer를 이용한 주식 수익률 예측 모델 학습
    - 08_MLP-Based_Stock_Price_Prediction(Custom): Black-Litterman 모델 개발하는 조원이 07에서 개발한 모델을 커스텀할 수 있도록 코딩
- 기간: 2023.10.08. ~ 2023.01.06.
