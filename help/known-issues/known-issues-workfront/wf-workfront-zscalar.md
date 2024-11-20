---
title: "Workfront: ZScalar 설정으로 인해 성능이 저하될 수 있음"
description: "ZScalar의 웹 서비스는 기본적으로 http/1.1을 사용하므로 Workfront에서 성능이 저하될 수 있습니다."
hidefromtoc: true
feature: System Setup and Administration
source-git-commit: 77345937934851b8ebfdf257f44e25133eade971
workflow-type: tm+mt
source-wordcount: '81'
ht-degree: 6%

---


# Workfront: ZScalar 설정으로 인해 성능이 저하될 수 있습니다.

>[!NOTE]
>
>이 문제는 ZScalar의 문제이며 Workfront에서 수정되지 않습니다.

ZScalar의 웹 서비스는 기본적으로 `http/1.1`을(를) 사용하므로 Workfront에서 성능이 저하될 수 있습니다.

**해결 방법**

`http/2`을(를) 사용하도록 ZScalar 소프트웨어를 구성합니다. Workfront에서는 구성할 수 없습니다.

ZScalar 설명서에서 `http/2`에 대한 정보를 찾을 수 있습니다.

_2024년 11월 18일 화요일에 처음 보고되었습니다._
