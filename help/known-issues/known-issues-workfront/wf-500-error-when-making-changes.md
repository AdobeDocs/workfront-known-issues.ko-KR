---
title: "Workfront: Workfront 개체를 변경할 때 500 오류"
description: "사용자가 Workfront 개체를 변경하려고 하면 변경 내용이 저장되지 않고 사용자에게 오류가 표시됩니다."
hidefromtoc: true
source-git-commit: d425d85b81c88bf301fce143b7cbed55c3c64cbb
workflow-type: tm+mt
source-wordcount: '91'
ht-degree: 4%

---


# [!DNL Workfront]: 변경 시 500 오류 [!DNL Workfront] 개체

사용자가 [!DNL Workfront] 개체를 변경하면 변경 내용이 저장되지 않고 사용자에게 다음 오류가 표시됩니다.

&quot;[!UICONTROL 500: 잘못된 SQL 문으로 인해 데이터베이스 오류가 발생했습니다.]&quot;

다음과 같은 상황에서 이 문제가 보고되었습니다.

* 객체의 상태 변경
* 타임라인 다시 계산
* 템플릿 첨부
* 로깅 시간

_2022년 11월 3일에 처음 보고되었습니다._
