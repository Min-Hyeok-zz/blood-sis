# BD 기획 초안 2차 수정

## 환경

> Backend : Node.js
> Frontend : Vue.js, PWA
> Database : Mysql

## 기능

- 채굴 대시보드
  - 마이닝풀 데이터테이블
  - 데이터테이블의 차트
- 랜드 대시보드
  - 일별 랜드 가격 및 비례하는 블러드 시세 차트
  - 지역별 판매량 (가장 중요하지만 구현이 가장 어려움)
- BLDENV (랜드, 채굴 가상환경)

### 채굴 대시보드

하루에 한번 크롤링

크롤링할 데이터 : https://wallet.blood.land/#/mining/stats



### 랜드 대시보드



### BLDENV (랜드, 채굴 가상환경)

구매할 갯수를 입력해서 이자+그로 받은 가중치로 나에게 돌아오는 금액를 합산해서 출력

- 구매할 갯수 입력
- 심기 유무 선택 -> 종류 SelectBox로 선택
- 마이닝 여부 체크
- 가중치 입력

1. 가중치 계산식
  > 가중치 : w
  > 틱 : t
  > B = w * t * 48

2. 이자 계산식

>p : 금액
>q : 수량
>(p * 0.041 / 100 ) * q





### 계산식

2. 가중치 계산식

> 가중치 : w
> 틱 : t
> B = w * t * 48

2. 이자 계산식

> p : 금액
> q : 수량
> (p * 0.041 / 100 ) * q

### 해쉬 / 가중치 대시보드

하루에 한번 크롤링

### VENV (가상 환경)

구매할 갯수를 입력해서 이자+그로 받은 가중치로 나에게 돌아오는 금액를 합산해서 출력

- 구매할 갯수 입력
- 심기 유무 선택 -> 종류 SelectBox로 선택
- 마이닝 여부 체크
- 가중치 입력