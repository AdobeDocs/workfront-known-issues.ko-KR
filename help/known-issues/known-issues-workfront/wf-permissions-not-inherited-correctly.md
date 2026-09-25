---
title: '권한: 오브젝트 권한이 올바르게 상속되지 않음'
description: 상속된 권한이 오브젝트에 올바르게 적용되지 않습니다. 이 문제는 상속된 권한의 복잡성으로 인해 발생할 수 있습니다.
feature: Projects, Tasks, Work Management
exl-id: 589733a7-2bd6-4b73-afb8-a14cc1f5076a
product_v2:
  - id: c4a86a5d-6562-4fc6-aa00-bfa25833aed9
    internal-label: Workfront
feature_v2:
  - id: a0dacc9f-0e23-495b-8e9f-a77c2e60b40c
    internal-label: Work management
subfeature_v2:
  - id: f0dd7b45-76b5-49d4-afe3-39f436b6fbd3
    internal-label: Projects
  - id: b91c0848-76c4-4da4-8b81-3aade0518dd0
    internal-label: Tasks
role_v2:
  - id: b69b2659-1057-424e-8fc5-ed9e016dc554
    internal-label: User
source-git-commit: 70ec59e07299bc7d7bb4649c67dff23161a50efa
workflow-type: tm+mt
source-wordcount: '146'
ht-degree: 100%
---
# 권한: 오브젝트 권한이 올바르게 상속되지 않음

>[!NOTE]
>
>제품 팀이 현재 이 문제 해결을 평가 중이며 이에 따라 제품 개선이 필요할 수 있습니다. 제품 개선 사항은 유지 관리 업데이트가 아니라 제품 공지를 통해 전달됩니다.

상속된 권한이 오브젝트에 올바르게 적용되지 않습니다. 이 문제는 상속된 권한의 복잡성으로 인해 발생할 수 있으며, 다음과 같은 요인의 영향을 받을 수 있습니다.

* 오브젝트가 많은 사용자와 공유됨
* 많은 오브젝트가 상속된 권한 변경에 의해 영향을 받습니다

**해결 방법**

오브젝트의 크기나 복잡성을 제한하면 이 문제를 방지할 수 있습니다. 상위 오브젝트 아래에 10,000개 이하의 하위 오브젝트가 있는 것이 좋습니다.

_2025년 3월 21일에 처음 보고되었습니다._
