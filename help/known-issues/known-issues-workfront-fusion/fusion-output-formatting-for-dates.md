---
title: '“Workfront Fusion: 날짜에 대한 출력 서식”'
description: “날짜가 문자열로 출력되는 경우, 날짜는 UTC 또는 ISO 문자열로 출력될 수 있습니다. 이는 매핑 패널 내의 논리에 따라 달라집니다.”
hidefromtoc: true
feature: Workfront Fusion
source-git-commit: 32196793e652b6b498e623ba8857039d6311c796
workflow-type: ht
source-wordcount: '120'
ht-degree: 100%

---


# Workfront Fusion: 날짜에 대한 출력 서식

날짜가 문자열로 출력되는 경우, 날짜는 UTC 또는 ISO 문자열로 출력될 수 있습니다. 이는 매핑 패널 내의 논리에 따라 달라집니다.

* 함수 내의 날짜가 문자열에 연결되면 문자열은 **UTC** 형식으로 출력됩니다.
* 날짜가 함수 내에서 연결되지 않으면 **ISO 문자열**&#x200B;로 출력됩니다.

고객은 `toString`(ISO의 경우) 또는 `formatDate` 함수를 사용하여 출력이 필요한 형식인지 확인해야 합니다.
