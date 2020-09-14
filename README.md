DACON : 컴퓨터 비전 학습 경진대회

https://dacon.io/competitions/official/235626/overview

### 최종 결과
- Public : 0.95588 (2위) (Public : 전체 테스트 데이터 중 1%로 채점)
- Private : 0.93134 (6위)

### 데이터 소개
- 글자(letter)에 가려진 숫자(digit)를 예측.
- csv 파일을 통해 글자(letter)와 숫자(digit) 그리고 28\*28 흑백 이미지의 각 픽셀값이 주어진다.
- 이미지 예시
  - digit(3) / letter(B)  
    <img src="https://user-images.githubusercontent.com/37574274/93104825-4e518680-f6e9-11ea-9f60-d70fd3b1ed71.png" width=20% height=20% />
  - digit(7) / letter(X)  
    <img src="https://user-images.githubusercontent.com/37574274/93104827-4eea1d00-f6e9-11ea-9994-84ab15935c65.png" width=20% height=20% />
  - digit(5) / letter(L)  
    <img src="https://user-images.githubusercontent.com/37574274/93106181-eef47600-f6ea-11ea-84cd-b2ec697e1b97.png" width=20% height=20% />
- 단순히 글자와 숫자가 겹쳐있는 형태가 아니라, 글자는 회색이나 흰색으로 모두 표현되고 숫자는 글자와 겹치는 부분만 흰색으로 표현된다.

