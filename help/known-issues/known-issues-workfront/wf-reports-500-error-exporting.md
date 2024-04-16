---
title: '“보고서: 보고서를 내보낼 때 500 오류 발생”'
description: 사용자가 보고서를 내보내려고 할 때 보고서를 내보낼 수 없으며 오류가 표시됩니다. 해결 방법을 사용할 수 있습니다.
hidefromtoc: true
feature: Reports and Dashboards
exl-id: 5ebdf00e-122b-4646-b9d8-8775d6e7c1cf
source-git-commit: cebbfd27b0d07c77706a609e38935f01d9727404
workflow-type: ht
source-wordcount: '105'
ht-degree: 100%

---

# 보고서: 보고서를 내보낼 때 500 오류 발생

>[!NOTE]
>
>이 문제는 2024년 4월 5일에 해결되었습니다.

사용자가 보고서를 내보내려고 할 때 보고서를 내보낼 수 없으며 다음과 같은 오류가 표시됩니다.

500: “매개변수”가 null /attask/api-internal/report/export이므로 “com.attask.biz.Parameter.getDisplayType()”을 호출할 수 없음

이 문제는 보고서가 프로젝트 수준 사용자 정의 통화 필드를 참조할 때 발생합니다.

**해결 방법**

사용자 정의 통화 필드를 참조하는 열을 제거하고 보고서를 다시 내보냅니다.

_2024년 4월 4일에 처음 보고되었습니다._
