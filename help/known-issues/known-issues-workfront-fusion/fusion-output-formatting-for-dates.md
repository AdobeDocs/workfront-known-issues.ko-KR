---
title: 'Workfront Fusion: 날짜에 대한 출력 서식'
description: 날짜가 문자열로 출력되는 경우, 날짜는 UTC 또는 ISO 문자열로 출력될 수 있습니다. 이는 매핑 패널 내의 논리에 따라 다릅니다.
feature: Workfront Fusion
exl-id: e01a2260-f230-4f72-a8c6-3dae56b22ff5
product_v2:
  - id: c4a86a5d-6562-4fc6-aa00-bfa25833aed9
    internal-label: Workfront
feature_v2:
  - id: c3a155b4-a54b-4a82-a3d2-c8f0f971673e
    internal-label: Workfront Fusion
role_v2:
  - id: b69b2659-1057-424e-8fc5-ed9e016dc554
    internal-label: User
source-git-commit: 70ec59e07299bc7d7bb4649c67dff23161a50efa
workflow-type: tm+mt
source-wordcount: '120'
ht-degree: 92%
---
# Workfront Fusion: 날짜에 대한 출력 서식

날짜가 문자열로 출력되는 경우, 날짜는 UTC 또는 ISO 문자열로 출력될 수 있습니다. 이는 매핑 패널 내의 논리에 따라 달라집니다.

* 함수 내의 날짜가 문자열에 연결되면 문자열은 **UTC** 형식으로 출력됩니다.
* 날짜가 함수 내에서 연결되지 않으면 **ISO 문자열**&#x200B;로 출력됩니다.

고객은 `toString`(ISO의 경우) 또는 `formatDate` 함수를 사용하여 출력이 필요한 형식인지 확인해야 합니다.
