---
title: "통합: 통합을 통해 AEM으로 전송할 때 파일 이름이 null입니다."
description: '"대형 파일(100MB 초과)이 Workfront 통합을 통해 Adobe Experience Manager으로 전송된 경우 AEM의 파일 이름은 null입니다. ”'
hidefromtoc: true
feature: Workfront Integrations and Apps, Digital Content and Documents
source-git-commit: 06a9c8dbbf73b6ee39e529c21248a3fc372cb252
workflow-type: tm+mt
source-wordcount: '98'
ht-degree: 10%

---


# 통합: 통합을 통해 AEM으로 전송할 때 파일 이름이 &quot;null&quot;입니다.

Workfront 통합을 통해 큰 파일(100MB 초과)이 Adobe Experience Manager으로 전송되는 경우 AEM의 파일 이름은 &quot;null&quot;입니다.

이 문제는 ZIP 및 TIF 파일과 함께 보고되었습니다.

**해결 방법**

다음 중 하나를 수행하십시오.

* 문서 이름을 AEM 제목에 매핑합니다.
* AEM에서 직접 파일 이름을 입력합니다.

_2024년 4월 23일 수요일에 처음 보고되었습니다._
