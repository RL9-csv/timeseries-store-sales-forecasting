# timeseries-store-sales-forecasting
Time series forecasting model to predict store sales and optimize inventory.

핵심요약
- 프로젝트 목표: 유통 매장의 일별 판매량 데이터를 분석하여, 재고 비용을 최소화하고 매출 기회를 극대화하기 위한 시계열 예측 모델을 개발을 목표로 합니다.
- 핵심결과: 여러가지 피처엔지니어링과 하이퍼파라미터 튜닝을 통해 5-Fold 시계열 교차검증 기준 평균 MAE (평균 절대 오차) 58.15를 달성했습니다. 이는 초기 베이스라인 모델 대비 예측 오차를 약 17.5% 개선한 수치입니다.
- 기대 효과: 향상된 예측 정확도를 통해 불필요한 재고 비용을 절감하고, 결품으로 인한 기회손실을 줄여 비즈니스 수익성을 개선할 수 있습니다.
- 주요 기술 스택: Python, Pandas, LightGBM, Optuna, SHAP
