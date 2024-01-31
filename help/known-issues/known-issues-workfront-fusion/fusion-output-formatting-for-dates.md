---
title: "Workfront Fusion: 날짜에 대한 출력 형식"
description: "날짜가 문자열로 출력되면 날짜가 UTC 또는 ISO 문자열로 출력될 수 있습니다. 이는 매핑 패널 내의 논리에 따라 다릅니다."
hidefromtoc: true
feature: Workfront Fusion
source-git-commit: 32196793e652b6b498e623ba8857039d6311c796
workflow-type: tm+mt
source-wordcount: '120'
ht-degree: 0%

---


# Workfront Fusion: 날짜에 대한 출력 형식

날짜가 문자열로 출력되면 날짜가 UTC 또는 ISO 문자열로 출력될 수 있습니다. 이는 매핑 패널 내의 논리에 따라 다릅니다.

* 함수 내의 날짜가 문자열에 결합되면 문자열이 출력됩니다 **UTC** 포맷.
* Date가 함수 내에 결합되지 않으면 Date가 함수 내에 **ISO 문자열**.

고객은 `toString` (ISO용) 또는 `formatDate` 출력을 필요한 형식으로 유지하는 함수입니다.
