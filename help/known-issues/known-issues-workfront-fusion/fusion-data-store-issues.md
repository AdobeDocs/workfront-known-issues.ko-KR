---
title: 'Workfront Fusion: 데이터 저장소 문제'
description: 데이터 저장소의 부울 필드와 관련하여 다음과 같은 문제가 보고되었습니다. 데이터 저장소에서 값이 EMPTY인 필드에 값이 반환되지 않으며 사용자가 데이터 저장소에서 값을 FALSE로 직접 설정할 수 없습니다.
hidefromtoc: true
feature: Workfront Fusion
exl-id: 1e0c807c-dab0-46ab-bdfa-f0a99f5db986
source-git-commit: 7194330acbc940d959cee30517a06adf272bb6c1
workflow-type: tm+mt
source-wordcount: '106'
ht-degree: 65%

---

# Workfront Fusion: 데이터 저장소 문제

>[!NOTE]
>
>이 문제는 2024년 9월 26일에 수정되었습니다.

데이터 저장소의 부울 필드와 관련하여 다음과 같은 문제가 보고되었습니다.

* 데이터 저장소에서 EMPTY 값을 갖는 필드에 대해 값을 반환하지 않습니다.
* 사용자가 데이터 저장소에서 직접 FALSE로 값을 설정할 수 없습니다.

**해결 방법**

값을 FALSE로 설정하려면 적절한 레코드 업데이트 모듈을 사용합니다.

_2024년 9월 19일에 처음 보고되었습니다._
