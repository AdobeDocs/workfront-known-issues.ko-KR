---
title: '“레이아웃 템플릿: 보고서에서 불일치를 유발하는 레이아웃 템플릿”'
description: 'Classic Workfront 경험의 레이아웃 템플릿은 더 이상 Workfront 인터페이스에서 사용할 수 없지만 여전히 Workfront 데이터에 영향을 줄 수 있습니다. 이로 인해 보고서 또는 대시보드의 레이아웃 템플릿(예: 다음 사용자와 공유)의 영향을 받는 필드에 불일치가 발생할 수 있습니다.'
hidefromtoc: true
feature: System Setup and Administration
exl-id: 1542291f-4797-477e-83b8-0706ac6801ae
source-git-commit: 2631a7a9cd6c07feae192cb0e29f168929fc9f3c
workflow-type: tm+mt
source-wordcount: '193'
ht-degree: 100%

---

# 레이아웃 템플릿: 보고서에서 불일치를 유발하는 레이아웃 템플릿

<!--Live for workaround-->

Classic [!DNL Workfront] 경험의 레이아웃 템플릿은 더 이상 [!DNL Workfront] 인터페이스에서 사용할 수 없지만 여전히 [!DNL Workfront] 데이터에 영향을 줄 수 있습니다. 이로 인해 보고서 또는 대시보드의 레이아웃 템플릿(예: [!UICONTROL 공유 대상])의 영향을 받는 필드에 불일치가 발생할 수 있습니다.

**해결 방법**

API 호출을 사용하여 클래식 레이아웃 템플릿을 삭제합니다. Workfront에 로그인되어 있어야 합니다.

>[!NOTE]
>
>전역 및 시스템 레이아웃 템플릿은 삭제할 수 없습니다.

1. 다음 API 호출을 사용하여 삭제하려는 레이아웃 템플릿을 찾습니다.
   `https://{yourDomain}.com/attask/api/v16.0/LYTMPL/search`
1. 삭제하려는 레이아웃 템플릿의 ID를 기록해 두십시오.
1. 다음 API 호출을 사용하여 세션 ID를 찾습니다.
   `https://{yourDomain}.com/attask/api/v16.0/session`

   >[!IMPORTANT]
   >
   >세션 ID를 누구와도 공유하지 마십시오.

1. 다음 API 호출에 레이아웃 템플릿 ID 및 세션 ID를 삽입합니다.
   `https://{yourDomain}.com/attask/api/v16.0/LYTMPL?ID={layoutTemplateID}&method=delete&sessionID={yourSessionID}`
1. 4단계의 API 호출을 브라우저의 URL 표시줄에 붙여넣고 Enter 키를 누릅니다.

   이렇게 되면 레이아웃 템플릿이 삭제됩니다.
