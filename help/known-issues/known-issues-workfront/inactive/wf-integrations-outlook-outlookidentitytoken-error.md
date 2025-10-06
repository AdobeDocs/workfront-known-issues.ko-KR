---
title: '통합: Outlook에 Workfront를 사용할 때 outlookIdentityToken 오류 발생'
description: 사용자가 Outlook 통합을 위해 Workfront를 사용하는 경우 오류가 표시될 수 있습니다.
hidefromtoc: true
feature: Workfront Integrations and Apps
exl-id: a5abe90c-4583-467e-8131-60bead300673
source-git-commit: 87c56abf4a5020632877263329f1455bbf4cc7f3
workflow-type: tm+mt
source-wordcount: '145'
ht-degree: 87%

---

# 통합: Outlook에 Workfront를 사용할 때 outlookIdentityToken 오류 발생

>[!NOTE]
>
>Outlook용 Workfront 통합을 더 이상 사용할 수 없습니다. 이 문서는 가까운 시일 내에 제거됩니다.

사용자가 Outlook 통합을 위해 Workfront를 사용하는 경우 다음과 같은 오류가 표시될 수 있습니다.

```
Unexpected error
Unable to get the outlookIdentityToken
```

**해결 방법**


이 오류를 해결하려면 조직에 대해 Microsoft 365 레거시 토큰을 활성화해야 합니다. 이 작업은 Microsoft 365에서 수행되어야 하므로 Workfront는 조직에 대해 이들 토큰을 활성화할 수 없습니다.

Microsoft 365 레거시 토큰을 활성화하는 방법에 대한 자세한 내용은 Microsoft 설명서의 [레거시 Exchange Online 토큰 켜기 또는 끄기](https://learn.microsoft.com/en-us/office/dev/add-ins/outlook/turn-exchange-tokens-on-off)를 참조하십시오.

레거시 토큰에 대한 자세한 내용은 Microsoft 설명서의 [Exchange Online 레거시 토큰을 다시 켤 수 있나요?](https://learn.microsoft.com/en-us/office/dev/add-ins/outlook/faq-nested-app-auth-outlook-legacy-tokens#can-i-turn-exchange-online-legacy-tokens-back-on)를 참조하십시오.


_2025년 3월 3일에 처음 보고되었습니다._
