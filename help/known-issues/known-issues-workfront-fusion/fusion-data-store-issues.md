---
title: "Workfront Fusion: 데이터 저장소 문제"
description: "데이터 저장소의 부울 필드와 관련하여 다음과 같은 문제가 보고되었습니다. 데이터 저장소는 값이 EMPTY인 필드에 값을 반환하지 않으며 사용자가 데이터 저장소에서 값을 직접 FALSE로 설정할 수 없습니다."
hidefromtoc: true
feature: Workfront Fusion
source-git-commit: 2cbde79df7bb110e083f8e8b65b319d9c682e188
workflow-type: tm+mt
source-wordcount: '100'
ht-degree: 5%

---


# Workfront Fusion: 데이터 저장소 문제

데이터 저장소의 부울 필드와 관련하여 다음 문제가 보고됨:

* 데이터 저장소가 값이 EMPTY인 필드에 대해 값을 반환하지 않습니다.
* 사용자가 데이터 저장소에서 직접 값을 FALSE로 설정할 수 없습니다.

**해결 방법**

값을 FALSE로 설정하려면 해당 레코드 업데이트 모듈을 사용합니다.

_2024년 9월 19일 금요일에 처음 보고되었습니다._
