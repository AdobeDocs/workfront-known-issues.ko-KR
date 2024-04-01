---
title: "보고서: 보고서 필터가 예상 결과를 반환하지 않음"
description: '"보고서의 필터는 예상 결과를 모두 반환하지 않을 수 있습니다. 해결 방법을 사용할 수 있습니다.”'
hidefromtoc: true
feature: Reports and Dashboards
source-git-commit: ed1fbb6e6c13ad41430e7351e0c9a28cefd46d12
workflow-type: tm+mt
source-wordcount: '98'
ht-degree: 14%

---


# 보고서: 보고서 필터가 예상 결과를 반환하지 않음

>[!NOTE]
>
>이 문제는 종결되었습니다.

보고서의 필터가 예상 결과를 모두 반환하지 않을 수 있습니다.

이 문제는 필터가 특정 기준을 가진 결과를 반환하도록 구성되어 있고 동일한 기준의 하위 집합인 결과를 반환하는 OR 규칙을 포함할 때 발생할 수 있습니다.

**해결 방법**

필터의 OR 블록에 동일한 평가 기준이 포함되어 있지 않은지 확인합니다.

_2024년 3월 11일 화요일에 처음 보고되었습니다._

