# mini-projects
robot-action-decider
로봇 행동 결정 프로그램
로봇이 거리·배터리 상태에 따라
어떻게 행동할지 판단하는 프로그램
mini-projects
 └─ robot-action-decider
     ├─ action_decider.py
     └─ README.md
# 로봇 행동 결정 프로그램
# 거리와 배터리 상태에 따라 로봇의 행동을 결정한다

distance = int(input("장애물과의 거리(cm)를 입력하세요: "))
battery = int(input("배터리 잔량(%)을 입력하세요: "))

if distance < 20:
    print("정지")
elif battery < 30:
    print("충전 필요")
else:
    print("전진")
# 로봇 행동 결정 프로그램

## 프로젝트 개요
로봇이 주변 상황(거리, 배터리 상태)에 따라  
어떤 행동을 해야 할지 판단하도록 만든 미니 프로젝트입니다.

## 사용 기술
- Python

## 구현 기능
- 장애물 거리 입력
- 배터리 잔량 확인
- 조건에 따른 행동 출력 (정지 / 충전 / 전진)

## 배운 점
조건문을 활용해 여러 상황을 고려하는 로직을 구성하는 방법을 배웠습니다.

## 향후 개선
실제 센서 입력과 연동해 보고 싶습니다.
