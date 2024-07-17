---
title: '홈: 승인됨 또는 계획 상태의 프로젝트 작업이 내 작업 또는 홈 작업 목록에 포함되지 않음'
description: 승인됨 또는 계획 상태의 프로젝트의 작업이 홈에 표시되지 않습니다. 해결 방법을 사용할 수 있습니다.
hidefromtoc: true
feature: Get Started with Workfront
exl-id: 5994508b-ee9f-40a9-bca3-e17d7a7708b5
source-git-commit: 036cedbdabb7dd32cd78cb0c924dbcefabeb05bb
workflow-type: tm+mt
source-wordcount: '195'
ht-degree: 100%

---

# 홈: 승인됨 또는 계획 상태의 프로젝트 작업이 내 작업 또는 홈 작업 목록에 포함되지 않음

>[!NOTE]
>
>제품 팀이 현재 이 문제 해결을 평가 중입니다. 이 문제가 해결되면 유지 보수 업데이트가 아니라 제품 공지를 통해 전달됩니다.

승인됨 또는 계획 상태의 프로젝트의 작업이 다음 영역에 표시되지 않습니다.

* Classic 홈: 작업 목록
* 새로운 홈: 내 작업 위젯

이는 이러한 상태의 프로젝트 작업이 현재 2000개 항목 쿼리 제한에 포함되어 있지만 내 작업 또는 홈 작업 목록에는 표시되지 않기 때문입니다. 이로 인해 작업이 2000개 미만인 사용자에게 이러한 작업이 표시되지 않는 상황이 발생할 수 있습니다.

**해결 방법**

다음 텍스트 모드 필터를 포함하는 사용자 정의 할당 보고서를 만듭니다.

할당이 AWAITING_ACCEPTANCE인 경우 CURRENT|APPROVED 프로젝트를 포함합니다.

```
assignedToID=$$USER.ID
status=AA
status_Mod=eq
project:statusEquatesWith=CUR,APR
project:statusEquatesWith_Mod=in
task:statusEquatesWith=CPL
task:statusEquatesWith_Mod=ne
```

할당이 승인된 경우 CURRENT|APPROVED|PLANNING 프로젝트를 포함합니다.

```
OR:1:assignedToID=$$USER.ID
OR:1:status=AD
OR:1:status_Mod=eq
OR:1:project:statusEquatesWith=CUR,APR,PLN
OR:1:project:statusEquatesWith_Mod=in
OR:1:task:statusEquatesWith=CPL
OR:1:task:statusEquatesWith_Mod=ne
```

_2023년 11월 6일에 처음 보고되었습니다._
