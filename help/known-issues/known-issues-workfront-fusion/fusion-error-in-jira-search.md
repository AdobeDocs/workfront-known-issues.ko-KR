---
title: 'Workfront Fusion: Jira 검색 모듈이 오류를 반환함'
description: 이전 Jira 커넥터에서 사용하는 검색 모듈로 인해 오류가 발생할 수 있습니다. 해결 방법을 사용할 수 있습니다.
feature: Workfront Fusion
exl-id: 9502ffb3-f287-47b2-9b35-1a906345e924
source-git-commit: 92419281092e3172a33499e288dd7867567a4ad5
workflow-type: tm+mt
source-wordcount: '188'
ht-degree: 100%

---

# Workfront Fusion: Jira 검색 모듈이 오류를 반환함

>[!NOTE]
>
>이 문제는 Jira가 제품을 변경했기 때문입니다.

이전 Jira 커넥터에서 사용하는 검색 모듈은 다음과 같은 오류를 발생할 수 있습니다.

`[410] The requested API has been removed. Please migrate to the /rest/api/3/search/jql API. A full migration guideline is available at https://developer.atlassian.com/changelog/#CHANGE-2046`

이는 Jira 측의 사용 중단 때문입니다.

참고:

* 검색 모듈만 영향을 받습니다. 현재 Fusion 커넥터에서 사용되는 다른 Jira API 엔드포인트는 이 사용 중지의 영향을 받지 않습니다.

* 지리적 롤아웃으로 인해 불일치가 발생할 수 있습니다. Atlassian은 이 변경 사항을 지역적으로 롤아웃하고 있으며, 이는 일부 Jira 클라우드 인스턴스가 여전히 이전 엔드포인트를 일시적으로 지원할 수 있음을 의미합니다. 이로 인해 환경 간에 일관되지 않은 동작이 발생할 수 있습니다.

**해결 방법**

이 오류가 발생하면 이전 Jira 커넥터의 검색 모듈을 새 커넥터의 검색 모듈로 바꿀 수 있습니다. 새 커넥터를 사용하면 사용할 API 버전을 선택할 수 있습니다. 연결을 만들 때 **API 버전** 필드에서 **V3**&#x200B;를 선택하십시오.

_2025년 9월 15일에 처음 보고되었습니다._
