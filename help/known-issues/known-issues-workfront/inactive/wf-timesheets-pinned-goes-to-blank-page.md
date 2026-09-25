---
title: '타임시트: 고정된 타임시트가 빈 페이지로 이동'
description: 사용자가 Workfront에서 타임시트로 이동하기 위해 핀을 클릭하면 핀이 빈 페이지로 이동합니다. 해결 방법을 사용할 수 있습니다.
feature: Timesheets
exl-id: 684ccdfa-f419-451e-836a-11831fbc1816
product_v2:
  - id: c4a86a5d-6562-4fc6-aa00-bfa25833aed9
    internal-label: Workfront
feature_v2:
  - id: d968a1bc-9a90-4926-a531-bcf272c32aad
    internal-label: Administration
subfeature_v2:
  - id: ce22a157-dd2c-405f-b740-c2f204bb4c1a
    internal-label: Timesheets
role_v2:
  - id: b69b2659-1057-424e-8fc5-ed9e016dc554
    internal-label: User
source-git-commit: 70ec59e07299bc7d7bb4649c67dff23161a50efa
workflow-type: tm+mt
source-wordcount: '126'
ht-degree: 100%
---
# 타임시트: 고정된 타임시트가 빈 페이지로 이동

<!--article live for workaround-->

사용자가 Workfront에서 타임시트로 이동하기 위해 핀을 클릭하면 핀이 빈 페이지로 이동합니다.

타임시트의 URL이 변경되었기 때문입니다. URL 끝에 있는 `/own`이 더 이상 올바른 URL이 아닙니다. 사용자가 `/own`을 포함하는 URL을 고정한 경우 해당 핀은 빈 페이지로 연결됩니다.

**해결 방법**

1. 타임시트를 고정 해제합니다.
1. URL 끝의 `/own`을 삭제합니다.
1. 타임시트를 다시 고정합니다.

_2024년 5월 7일 수요일에 처음 보고되었습니다._
