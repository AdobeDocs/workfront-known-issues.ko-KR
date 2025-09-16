---
title: 'Workfront Fusion: Jira 검색 모듈이 오류를 반환함'
description: 기존 Jira 커넥터에서 사용하는 검색 모듈로 인해 오류가 발생할 수 있습니다. 해결 방법을 사용할 수 있습니다.
hidefromtoc: true
feature: Workfront Fusion
source-git-commit: 0f4dba4664f645920752cc0c346782c9582b0e54
workflow-type: tm+mt
source-wordcount: '186'
ht-degree: 4%

---


# Workfront Fusion: Jira 검색 모듈이 오류를 반환함

>[!NOTE]
>
>이번 이슈는 Jira가 그들의 제품에서 변경한 것에 기인합니다.

기존 Jira 커넥터에서 사용하는 검색 모듈로 인해 다음 오류가 발생할 수 있습니다.

`[410] The requested API has been removed. Please migrate to the /rest/api/3/search/jql API. A full migration guideline is available at https://developer.atlassian.com/changelog/#CHANGE-2046`

이는 Jira 측의 사용 중단 때문입니다.

참고:

* 검색 모듈만 영향을 받습니다. 현재 Fusion 커넥터에서 사용하는 다른 Jira API 종단점은 이 사용 중지의 영향을 받지 않습니다.

* 지리적 롤아웃으로 인해 불일치가 발생할 수 있습니다. Atlassian은 이 변경 사항을 지역적으로 롤아웃합니다. 즉, 일부 Jira Cloud 인스턴스가 여전히 이전 끝점을 일시적으로 지원할 수 있습니다. 이로 인해 환경 간에 일관되지 않은 동작이 발생할 수 있습니다.

**해결 방법**

이 오류가 발생하면 기존 Jira 커넥터의 검색 모듈을 새 커넥터의 검색 모듈로 바꿀 수 있습니다. 새 커넥터를 사용하면 사용된 API 버전을 선택할 수 있습니다. 연결을 만들 때 **API 버전** 필드에서 **V3**&#x200B;을(를) 선택하십시오.

_2025년 9월 15일 화요일에 처음 보고되었습니다._

