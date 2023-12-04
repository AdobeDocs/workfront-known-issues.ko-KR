---
title: '“보고서: 보고서를 내보낼 때 500 오류 발생”'
description: 사용자가 보고서를 내보내려고 하면 500 오류와 함께 내보내기가 실패합니다.
hidefromtoc: true
feature: Reports and Dashboards
exl-id: 5275a4f4-4786-4a87-970f-774dcd526a39
source-git-commit: 88126bda7f7c51895ae512bb5f7686119febd32f
workflow-type: tm+mt
source-wordcount: '70'
ht-degree: 100%

---

# 보고서: 보고서를 내보낼 때 500 오류 발생

>[!NOTE]
>
>이 문제는 2023년 11월 30일 금요일에 해결되었습니다.

사용자가 보고서를 내보내려고 하면 다음과 같은 오류 메시지와 함께 내보내기가 실패합니다.

```
500: Cannot invoke "Object.getClass()" because "parentObj" is null /attask/api-internal/report/export
```

이 문제는 `lastNote` 메모 텍스트를 참조하기 위해 `valueexpression`을 사용하는 보고서에서 보고되었습니다.

_2023년 11월 8일에 처음 보고되었습니다._
