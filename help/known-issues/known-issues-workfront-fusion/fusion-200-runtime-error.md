---
title: "Workfront Fusion: Workfront 모듈에서 200 응답 포함 RuntimeError"
description: Workfront 모듈은 'RuntimeError [200]' 응답을 반환할 수 있습니다. 200은 성공적인 응답을 의미하지만, 오류는 요청이 실패했음을 나타냅니다.
hidefromtoc: true
feature: Workfront Fusion
exl-id: 99967e3b-08bd-4035-b0b2-b90eff8cf1a1
source-git-commit: 58d9dedba766417d68892c94d18d0ee4e9c03b51
workflow-type: tm+mt
source-wordcount: '96'
ht-degree: 80%

---

# Workfront Fusion: Workfront 모듈에서 반환되는 RuntimeError [200] 응답

>[!NOTE]
>
>이 문제는 2024년 3월 28일 금요일에 해결되었습니다.

Workfront 모듈은 `RuntimeError [200]` 응답을 반환할 수 있습니다. 200은 성공적인 응답을 의미하지만, 오류는 요청이 실패했음을 나타냅니다.

응답이 너무 길면 이런 일이 발생할 수 있습니다. 데이터가 Fusion으로 반환되나, Fusion에서 처리할 수는 없습니다.

_2024년 1월 3일에 처음 보고되었습니다._
