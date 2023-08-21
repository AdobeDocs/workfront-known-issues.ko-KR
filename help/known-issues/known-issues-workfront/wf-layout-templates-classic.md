---
title: "레이아웃 템플릿: 보고서에서 불일치를 초래하는 레이아웃 템플릿"
description: "클래식 Workfront 경험의 레이아웃 템플릿은 Workfront 인터페이스에서 더 이상 사용할 수 없지만, Workfront 데이터에 영향을 줄 수 있습니다. 이로 인해 보고서나 대시보드의 레이아웃 템플릿(예: 와 공유)의 영향을 받는 필드에 불일치가 발생할 수 있습니다."
hidefromtoc: true
feature: System Setup and Administration
source-git-commit: 045e2bd200aa2fffaf2e763a73eb8729517be197
workflow-type: tm+mt
source-wordcount: '195'
ht-degree: 0%

---


# 레이아웃 템플릿: 보고서에서 불일치를 발생하는 레이아웃 템플릿

클래식 Workfront 경험의 레이아웃 템플릿은 Workfront 인터페이스에서 더 이상 사용할 수 없지만, Workfront 데이터에 영향을 줄 수 있습니다. 이로 인해 보고서나 대시보드의 레이아웃 템플릿(예: 와 공유)의 영향을 받는 필드에 불일치가 발생할 수 있습니다.

**해결 방법**

API 호출을 사용하여 클래식 레이아웃 템플릿을 삭제합니다. Workfront에 로그인해야 합니다.

>[!NOTE]
>
>글로벌 및 시스템 레이아웃 템플릿은 삭제할 수 없습니다.

1. 다음 API 호출을 사용하여 삭제할 레이아웃 템플릿을 찾습니다.
   `https://{yourDomain}.com/attask/api/v16.0/LYTMPL/search`
1. 삭제할 레이아웃 템플릿의 ID를 기록해 둡니다.
1. 다음 API 호출을 사용하여 세션 ID를 찾습니다.
   `https://{yourDomain}.com/attask/api/v16.0/session`

   >[!IMPORTANT]
   >
   >세션 ID는 다른 사용자와 공유하지 마십시오.

1. 레이아웃 템플릿 ID 및 세션 ID를 다음 API 호출에 삽입합니다.
   `https://{yourDomain}.com/attask/api/v16.0/LYTMPL?ID={layoutTemplateID}&method=delete&sessionID={yourSessionID}`
1. 4단계의 API 호출을 브라우저의 URL 표시줄에 붙여 넣고 Enter 키를 누릅니다.

   이렇게 하면 레이아웃 템플릿이 삭제됩니다.

