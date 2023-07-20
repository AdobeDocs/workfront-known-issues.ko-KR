---
title: '“사용자 정의 양식: 계산된 필드에서 소유자를 참조할 때 잘못된 사용자 정의 표현식 메시지”'
description: '“사용자가 문제 수준 사용자 정의 양식에 계산된 필드를 추가하고 소유자에 대한 참조(예: “ownerID”)를 추가하려고 하면 필드가 저장되지 않고 사용자에게 다음 메시지가 표시됩니다. 잘못된 사용자 정의 표현식입니다. 다시 시도해 주십시오.”'
hidefromtoc: true
feature: Custom Forms
exl-id: 254f1fae-0784-4332-99a1-cc1895c50896
source-git-commit: 2a41264d6f477f51eaeda6ae3675b1a6d816249c
workflow-type: tm+mt
source-wordcount: '135'
ht-degree: 100%

---

# 사용자 정의 양식: 계산된 필드에서 “[!UICONTROL 소유자]”를 참조할 때 “[!UICONTROL 잘못된 사용자 정의 표현식]” 메시지

>[!NOTE]
>
>이 문제는 2023년 3월 9일에 해결되었습니다.

<!--
>[!NOTE]
>
>This issue was fixed on December 1, 2022.
-->

사용자가 문제 수준 사용자 정의 양식에 계산된 필드를 추가하고 “[!UICONTROL 소유자]”에 대한 참조(예: `ownerID`)를 추가하려고 하면 필드가 저장되지 않고 사용자에게 다음 메시지가 표시됩니다.

“[!UICONTROL 잘못된 사용자 정의 표현식입니다. 다시 시도해 주십시오.]”

이는 표현식이 유효한 경우에도 발생합니다.

_2022년 11월 8일에 처음 보고되었습니다._
