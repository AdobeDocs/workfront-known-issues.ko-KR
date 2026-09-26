---
title: 'Workfront: ZScaler 설정으로 인해 성능이 저하될 수 있음'
description: ZScaler 웹 서비스는 기본적으로 http/1.1을 사용하는데, 이로 인해 Workfront의 성능이 저하될 수 있습니다.
feature: System Setup and Administration
exl-id: 35588d30-3290-4522-b66f-a38a1f0d7237
product_v2:
  - id: c4a86a5d-6562-4fc6-aa00-bfa25833aed9
    internal-label: Workfront
feature_v2:
  - id: d5896d07-2812-5418-8b18-8957a0d7f0fb
    internal-label: System Setup and Administration
role_v2:
  - id: b69b2659-1057-424e-8fc5-ed9e016dc554
    internal-label: User
source-git-commit: 70ec59e07299bc7d7bb4649c67dff23161a50efa
workflow-type: tm+mt
source-wordcount: '83'
ht-degree: 100%
---
# Workfront: ZScaler 설정으로 인해 성능이 저하될 수 있음

>[!NOTE]
>
>이는 ZScaler의 문제이므로 Workfront에서는 해결되지 않습니다.

ZScaler 웹 서비스는 기본적으로 `http/1.1`을 사용하는데, 이로 인해 Workfront의 성능이 저하될 수 있습니다.

**해결 방법**

`http/2`를 사용하도록 ZScaler 소프트웨어를 구성하십시오. Workfront에서는 이를 구성할 수 없습니다.

`http/2`에 대한 정보는 ZScaler 설명서에서 확인할 수 있습니다.

_2024년 11월 18일 화요일에 처음 보고되었습니다._
