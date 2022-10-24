---
title: "사용자 지정 양식: 계산된 필드의 HOUR 함수는 UTC를 사용합니다."
description: "계산된 필드에 HOUR 함수가 포함되면 함수는 예상 시간대가 아닌 UTC를 기반으로 값을 반환합니다. 따라서 HOUR 값을 기반으로 한 모든 계산은 잘못되었습니다."
hidefromtoc: true
source-git-commit: 3950404543b428f98b4952e6cd01e72c69585644
workflow-type: tm+mt
source-wordcount: '0'
ht-degree: 0%

---


# 사용자 지정 양식: [!UICONTROL 시간] 계산된 필드의 함수는 UTC를 사용합니다

계산된 필드에 [!UICONTROL 시간] 함수를 호출하면 함수는 예상 표준 시간대가 아닌 UTC를 기반으로 값을 반환합니다. 따라서 HOUR 값을 기반으로 하는 모든 계산은 잘못되었습니다.

_2022년 10월 17일에 처음 보고되었습니다._

