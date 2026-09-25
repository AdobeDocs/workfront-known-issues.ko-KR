---
title: '레이아웃 템플릿: 레이아웃 템플릿을 통해 작업 요약에 추가하면 사용자 정의 데이터 필드가 표시되지 않음'
description: 관리자가 레이아웃 템플릿을 통해 작업 요약 섹션에 사용자 정의 데이터 필드를 추가하면 작업 요약 섹션을 조회하는 사용자에게 해당 필드가 비어 있는 것으로 표시됩니다.
feature: System Setup and Administration
exl-id: f37ecfc5-30b9-4fe2-9e76-a97be0ae969f
product_v2:
  - id: c4a86a5d-6562-4fc6-aa00-bfa25833aed9
    internal-label: Workfront
feature_v2:
  - id: d5896d07-2812-5418-8b18-8957a0d7f0fb
    internal-label: System Setup and Administration
role_v2:
  - id: b69b2659-1057-424e-8fc5-ed9e016dc554
    internal-label: User
source-git-commit: 70ec59e07299bc7d7bb4649c67dff23161a50efa
workflow-type: tm+mt
source-wordcount: '139'
ht-degree: 100%
---
# 레이아웃 템플릿: 레이아웃 템플릿을 통해 작업 요약에 추가하면 사용자 정의 데이터 필드가 표시되지 않음

>[!NOTE]
>
>이 문제는 설계대로 작동하는 것이므로 종결되었습니다. 아래 해결 방법을 참조하십시오.

관리자가 레이아웃 템플릿을 통해 작업 요약 섹션에 사용자 정의 데이터 필드를 추가하면 작업 요약 섹션을 조회하는 사용자에게 해당 필드가 비어 있는 것으로 표시됩니다.

**해결 방법**

이 문제를 방지하려면 사용자 정의 필드 이름에 마침표(.)를 사용하지 마십시오. 원하는 경우 요약 섹션에서 사용자 정의 필드의 레이블을 다시 지정하고 마침표를 포함할 수 있습니다.

_2024년 10월 2일 목요일에 처음 보고되었습니다._
