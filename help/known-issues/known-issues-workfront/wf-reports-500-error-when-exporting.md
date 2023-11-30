---
title: '보고서: 보고서를 내보낼 때 500 오류 발생'
description: 사용자가 보고서를 내보내려고 하면 500 오류가 발생하여 내보내기가 실패합니다.
hidefromtoc: true
feature: Reports and Dashboards
exl-id: 5275a4f4-4786-4a87-970f-774dcd526a39
source-git-commit: 88126bda7f7c51895ae512bb5f7686119febd32f
workflow-type: tm+mt
source-wordcount: '65'
ht-degree: 9%

---

# 보고서: 보고서를 내보낼 때 500 오류 발생

>[!NOTE]
>
>이 문제는 2023년 11월 30일에 해결되었습니다.

사용자가 보고서를 내보내려고 할 때 내보내기에 실패하고 다음 오류가 표시됩니다.

```
500: Cannot invoke "Object.getClass()" because "parentObj" is null /attask/api-internal/report/export
```

이 문제는 을 사용하는 보고서에서 보고되었습니다. `valueexpression` 을(를) 참조하려면 `lastNote` 참고 텍스트입니다.

_2023년 11월 8일에 처음 보고되었습니다._
