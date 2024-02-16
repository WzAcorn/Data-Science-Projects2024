# 3주차 활동 정리

## 미팅 준비
- **미팅 일시**: 2024년 1월 29일, 21:00~22:00
- **사전 작업 요약**:
  - **코드 공유**: 팀원들이 자신의 코드를 GitHub에 업로드.
  - **의견 교환**: Issues 탭을 활용하여 각자의 미션에 대한 데이터 분석 의견을 공유하고 피드백 제공.

## 🐿️개발하는도토리(민윤홍) 님의 피쳐엔지니어링 리뷰
![image](https://github.com/WzAcorn/Data-Science-Projects2024/assets/77008882/10a596dd-4829-4070-9584-870374f7d323)
- Tolacharges의 수치형 Data => 범주형 Data 로 바꿧으나, 성능이 떨어짐.
- 상관관계 분석 결과, 이는 Tolacharges의 변수가 다중공선성이 크므로 의미없는 데이터임을 알 수 있었음.
- ensemble 및 staking을 통해 모델의 정확도를 기존대비 약 5%p 끌어 올림. [3주차 미션 코드](https://github.com/WzAcorn/Data-Science-Projects2024/blob/main/Week3/03_week_mission_acorn.ipynb)
