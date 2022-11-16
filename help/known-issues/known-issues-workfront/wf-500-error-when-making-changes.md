---
title: '“Workfront: Workfront 오브젝트를 변경할 때 500 오류 발생”'
description: 사용자가 Workfront 오브젝트를 변경하려 할 때 변경 사항이 저장되지 않고 사용자에게 오류가 표시됨
hidefromtoc: true
exl-id: 67c686a8-3c4f-48c2-a120-eca27816a367
source-git-commit: 66e3bc22d8aef2d6287161f4a13fbbe0f3ac99c8
workflow-type: ht
source-wordcount: '97'
ht-degree: 100%

---

# [!DNL Workfront]: [!DNL Workfront] 오브젝트를 변경할 때 500 오류 발생

>[!NOTE]
>
>이 문제는 2022년 11월 4일에 수정되었습니다.

사용자가 [!DNL Workfront] 오브젝트를 변경하려 할 때 변경 사항이 저장되지 않고 사용자에게 다음 오류가 표시됩니다.

“[!UICONTROL 500: 잘못된 SQL 문으로 인한 데이터베이스 오류.]”

이 문제는 다음 상황에서 보고되었습니다.

* 오브젝트의 상태 변경 중
* 타임라인 다시 계산 중
* 템플릿 첨부 중
* 시간 로깅 중

_2022년 11월 3일에 처음 보고되었습니다._
