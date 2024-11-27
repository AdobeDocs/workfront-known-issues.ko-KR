---
title: 'Workfront: ZScaler 설정으로 인해 성능이 저하될 수 있음'
description: ZScaler의 웹 서비스는 기본적으로 http/1.1을 사용하므로 Workfront에서 성능이 저하될 수 있습니다.
hidefromtoc: true
feature: System Setup and Administration
exl-id: 35588d30-3290-4522-b66f-a38a1f0d7237
source-git-commit: 8bb5041a13374ce5dde6a1db173487f50d049f17
workflow-type: tm+mt
source-wordcount: '81'
ht-degree: 6%

---

# Workfront: ZScaler 설정으로 인해 성능이 저하될 수 있습니다.

>[!NOTE]
>
>이 문제는 ZScaler와 관련된 문제이며 Workfront에서 수정하지 않습니다.

ZScaler의 웹 서비스는 기본적으로 `http/1.1`을(를) 사용하므로 Workfront에서 성능이 저하될 수 있습니다.

**해결 방법**

`http/2`을(를) 사용하도록 ZScaler 소프트웨어를 구성합니다. Workfront에서는 구성할 수 없습니다.

ZScaler 설명서에서 `http/2`에 대한 정보를 찾을 수 있습니다.

_2024년 11월 18일 화요일에 처음 보고되었습니다._
