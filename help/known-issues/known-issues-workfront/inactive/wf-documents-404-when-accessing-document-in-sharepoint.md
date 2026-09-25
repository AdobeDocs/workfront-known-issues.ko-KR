---
title: '문서: SharePoint에서 링크된 문서에 액세스할 때 404 오류 발생'
description: 사용자가 SharePoint를 통해 연결된 문서에 액세스하려고 하면 404 오류가 있는 페이지로 이동합니다.
feature: Digital Content and Documents, Workfront Integrations and Apps
exl-id: b86ec92b-a27f-4ec3-acc2-0f0118014760
product_v2:
  - id: c4a86a5d-6562-4fc6-aa00-bfa25833aed9
    internal-label: Workfront
feature_v2:
  - id: a1f87682-0525-5459-aa06-3560bb4c3b2a
    internal-label: Workfront Integrations and Apps
  - id: e14a7f57-c82c-4874-a495-5d036cbbdc3d
    internal-label: Resource management
subfeature_v2:
  - id: b70a979b-965d-47a9-a360-e7ec2a19b8c1
    internal-label: Digital content and documents
role_v2:
  - id: b69b2659-1057-424e-8fc5-ed9e016dc554
    internal-label: User
source-git-commit: 70ec59e07299bc7d7bb4649c67dff23161a50efa
workflow-type: tm+mt
source-wordcount: '110'
ht-degree: 91%
---
# 문서: [!DNL SharePoint]에서 연결되어 있는 문서에 액세스할 때 404 오류 발생

<!--Requested article. This issue is on the WF and WFP TOCs.-->

사용자가 [!DNL SharePoint]를 통해 연결된 문서에 액세스하려고 하면 다음 오류가 있는 페이지로 이동합니다.

“[!UICONTROL 오류 404: 페이지를 찾을 수 없습니다. 이 페이지는 사용할 수 없습니다. URL을 확인하거나 다른 페이지를 방문하십시오.]”

이는 사이트의 링크에 “@” 기호가 있을 때 발생하는 알려진 [!DNL SharePoint] 문제입니다.

**해결 방법**

[!DNL SharePoint]는 짧은 URL을 생성하고 해당 URL을 링크에 사용할 것을 권장합니다.

_2023년 3월 14일 수요일에 처음 보고되었습니다._
