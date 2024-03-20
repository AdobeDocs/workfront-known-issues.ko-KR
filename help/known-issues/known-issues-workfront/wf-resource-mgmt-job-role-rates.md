---
title: '“리소스 관리: 작업 역할 문제로 인해 재무 계산이 잘못됨”'
description: “시간 및 재무 계산이 잘못되어 비용 요율이 있는 작업 역할에 시간이 기록되어 있어도 비용이 0으로 표시될 수 있습니다.”
hidefromtoc: true
feature: Resource Management
source-git-commit: f8579e17458f702580e1a4cf3600c14376d7591b
workflow-type: ht
source-wordcount: '141'
ht-degree: 100%

---


# 리소스 관리: 작업 역할 문제로 인해 재무 계산이 잘못됨

>[!NOTE]
>
>이 문제는 2024년 2월 8일에 해결되었습니다.

시간 및 재무 계산이 잘못되어 비용 요율이 있는 작업 역할에 시간이 기록되어 있어도 비용이 0으로 표시될 수 있습니다.

이는 작업 역할이 시작 일자나 종료 일자 없이 중복 요율을 자동으로 생성하기 때문입니다. 시작 일자나 종료 일자가 없기 때문에 재무 계산이 실행될 때 값이 0으로 처리됩니다.

**해결 방법**

1. 이전의 정확한 데이터가 저장되었는지 확인합니다.
1. 시작 일자나 종료 일자가 없는 중복 요율을 삭제합니다.
1. 재무를 다시 계산합니다.

_2023년 1월 18일에 처음 보고되었습니다._