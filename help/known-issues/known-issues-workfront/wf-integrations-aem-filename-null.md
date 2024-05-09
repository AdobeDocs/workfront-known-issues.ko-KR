---
title: '“통합: 통합 기능을 통해 AEM으로 전송 시 파일 이름이 null이 됨”'
description: “Workfront 통합 기능을 통해 대용량 파일(100MB 초과)을 Adobe Experience Manager로 전송하면 AEM에서의 파일 이름이 null이 됩니다. ”
hidefromtoc: true
feature: Workfront Integrations and Apps, Digital Content and Documents
exl-id: c2d15424-ae04-414f-9384-a7b083212313
source-git-commit: e24d266002a913e5c6e2d5e40e9dad36deff541a
workflow-type: tm+mt
source-wordcount: '110'
ht-degree: 52%

---

# 통합: 문서 통합으로 전송할 때 파일 이름이 &quot;null&quot;입니다.

>[!NOTE]
>
>이 문제는 2024년 5월 8일 목요일에 해결되었습니다.

Workfront 통합을 통해 대형 파일(100MB 초과)을 문서 공급자에게 전송하는 경우 문서 공급자의 파일 이름은 &quot;null&quot;입니다.

이 문제는 ZIP 및 TIF 파일 모두에서 보고되었습니다.

**해결 방법**

다음 중 하나를 수행하십시오.

* 문서 이름을 문서 공급자의 제목에 매핑합니다.
* 문서 공급자에서 직접 파일 이름을 입력합니다.

_2024년 4월 23일에 처음 보고되었습니다._

