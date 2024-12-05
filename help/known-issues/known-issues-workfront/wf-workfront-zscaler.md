---
title: 'Workfront: ZScaler 설정으로 인해 성능이 저하될 수 있음'
description: ZScaler 웹 서비스는 기본적으로 http/1.1을 사용하는데, 이로 인해 Workfront의 성능이 저하될 수 있습니다.
hidefromtoc: true
feature: System Setup and Administration
exl-id: 35588d30-3290-4522-b66f-a38a1f0d7237
source-git-commit: 8bb5041a13374ce5dde6a1db173487f50d049f17
workflow-type: ht
source-wordcount: '81'
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

_2024년 11월 18일에 처음 보고되었습니다._
