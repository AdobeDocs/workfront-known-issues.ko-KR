---
title: "보고서: 보고서를 내보낼 때 500 오류 발생"
description: '"사용자가 보고서를 내보내려고 할 때 보고서가 내보내지지 않고 오류가 표시됩니다. 해결 방법을 사용할 수 있습니다.”'
hidefromtoc: true
feature: Reports and Dashboards
source-git-commit: 1f516bdbea40c2946dec1935b7ada63b28b3451c
workflow-type: tm+mt
source-wordcount: '99'
ht-degree: 16%

---


# 보고서: 보고서를 내보낼 때 500 오류 발생

사용자가 보고서를 내보내려고 할 때 보고서가 내보내지지 않고 다음과 같은 오류가 표시됩니다.

500: &quot;parameter&quot;가 null /attask/api-internal/report/export이므로 &quot;com.attask.biz.Parameter.getDisplayType()&quot;을 호출할 수 없습니다.

이 문제는 보고서가 프로젝트 수준의 사용자 지정 통화 필드를 참조할 때 발생합니다.

**해결 방법**

사용자 지정 통화 필드를 참조하는 열을 제거하고 보고서를 다시 내보냅니다.

_2024년 4월 4일 금요일에 처음 보고되었습니다._
