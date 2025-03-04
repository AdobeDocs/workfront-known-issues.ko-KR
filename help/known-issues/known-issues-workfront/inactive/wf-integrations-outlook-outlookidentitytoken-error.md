---
title: '통합: Outlook용 Workfront을 사용할 때 outlookIdentityToken 오류 발생'
description: 사용자가 Outlook용 Workfront 통합을 사용할 때 오류가 표시될 수 있습니다.
hidefromtoc: true
feature: Workfront Integrations and Apps
source-git-commit: 19d438b3a368b076aa03a89fe6648ec4b225225f
workflow-type: tm+mt
source-wordcount: '127'
ht-degree: 0%

---


# 통합: Outlook용 Workfront을 사용할 때 outlookIdentityToken 오류 발생

사용자가 Outlook용 Workfront 통합을 사용할 때 다음과 같은 오류가 표시될 수 있습니다.

```
Unexpected error
Unable to get the outlookIdentityToken
```

**해결 방법**


이 오류를 해결하려면 조직에 대해 Microsoft 365 레거시 토큰을 활성화해야 합니다. 이 작업은 Microsoft 365에서 수행해야 하므로 Workfront에서 조직에 대해 이러한 토큰을 활성화할 수 없습니다.

Microsoft 365 레거시 토큰을 사용하는 방법에 대한 지침은 Microsoft 설명서의 [레거시 Exchange Online 토큰 켜기 또는 끄기](https://learn.microsoft.com/en-us/office/dev/add-ins/outlook/turn-exchange-tokens-on-off)를 참조하십시오.

레거시 토큰에 대한 자세한 내용은 [Exchange Online 레거시 토큰을 다시 켤 수 있습니까?Microsoft 설명서의 ](https://learn.microsoft.com/en-us/office/dev/add-ins/outlook/faq-nested-app-auth-outlook-legacy-tokens#can-i-turn-exchange-online-legacy-tokens-back-on).


_2025년 3월 3일에 처음 보고되었습니다. 2024._
