---
title: '사용자 정의 양식: 계산된 필드를 설정할 때 죄송합니다 오류 발생'
description: 사용자가 사용자 정의 양식에서 계산된 필드를 만들거나 편집할 때 계산된 필드의 표현식에 사용자 정의 필드를 포함하면 표현식이 유효하지 않은 것으로 간주됩니다. 저장 버튼이 비활성화되고 사용자가 사용자 정의 필드에서 다른 곳으로 이동할 수 없습니다. 또한 필드 아래에 “죄송합니다” 메시지가 표시됩니다.
feature: Custom Forms
exl-id: e499c680-2fdf-40cb-a1fa-b0d4ae799ad2
product_v2:
  - id: c4a86a5d-6562-4fc6-aa00-bfa25833aed9
    internal-label: Workfront
feature_v2:
  - id: d968a1bc-9a90-4926-a531-bcf272c32aad
    internal-label: Administration
subfeature_v2:
  - id: d87de1f9-8e24-4c4d-aa4c-a403075091a1
    internal-label: Custom forms
role_v2:
  - id: b69b2659-1057-424e-8fc5-ed9e016dc554
    internal-label: User
source-git-commit: 70ec59e07299bc7d7bb4649c67dff23161a50efa
workflow-type: tm+mt
source-wordcount: '180'
ht-degree: 94%
---
# 사용자 정의 양식: 계산된 필드를 설정할 때 “[!UICONTROL 죄송합니다]” 오류 발생

<!--Requested: Do not delete without approval from Alex Beach-->

>[!NOTE]
>
>이 문제는 2023년 1월 12일에 해결되었습니다

사용자가 사용자 정의 양식에서 계산된 필드를 만들거나 편집할 때 계산된 필드의 표현식에 사용자 정의 필드를 포함하면 표현식이 유효하지 않은 것으로 간주됩니다. [!UICONTROL Save] 버튼이 비활성화되고 사용자가 사용자 정의 필드에서 다른 곳으로 이동할 수 없습니다. 또한 필드 아래에 다음 메시지가 표시됩니다.

“[!UICONTROL 죄송합니다. 문제가 발생했습니다. 무엇이 잘못되었는지 파악하여 수정할 수 있도록 Workfront에 문의해 주시기 바랍니다.]”

표현식에서 사용자 정의 필드를 제거하면 사용자가 필드를 저장하고 다른 곳으로 이동할 수 있습니다.

_2022년 10월 11일 수요일에 처음 보고되었습니다._
