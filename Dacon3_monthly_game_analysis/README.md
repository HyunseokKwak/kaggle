## Dacon3 Game Data Analysis

- [대회링크](https://dacon.io/competitions/official/235583/data/)

### Overview

### Evaluation

- AUC

### 일정

2020.03.31까지 Free Stage

2020.04.15까지 Regular Stage

2020.04.22까지 코드제출

### data

```
- train.csv
- test.csv
- sample_submission.csv
```

### data 설명
변수명 | 변수설명 | 비고
----|----|----|
game_id| 경기 구분 기호 | .|
winner | 승리선수 | . |
time | 경기시간 | 분. 초 단 ex) 5.06은 5분 6초 |
player | 선수 | . |
species | 종족 | . |
event | 행동종류 | . |
event_contents | 행동상세 . |

event_contents 세분화

종류 | 설명 | 비고 |
----|----|----|
**Ability** | 생산 공격 등 선수의 주요행동 |
AddToControlGroup | 부대에 추가 | 상세설명이 따로 없음. NaN.
Camera | 시점선택 | 좌표로 찍힘
CotrolGroup | 부대행동 |
GetControlGroup | 부대 불러오기 |
Right click | 마우스 우클릭 |
**Selection** | 객체 선택 | 유닛, 건물, 중립건물
SetControlGroup | 부대 지정 |



## 캐글일지.

2020.03.02

```
- 베이스라인 재출
- 간단한 EDA
```
