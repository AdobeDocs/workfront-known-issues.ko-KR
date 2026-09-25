---
title: '교정쇄: 기한을 기존 단계의 기한과 일치시킬 수 없어 새 단계가 만들어짐'
description: 새 교정쇄를 만들 때 기한을 15분 단위(10:00, 10:15, 10:30, 20:45 등)로 설정할 수 있습니다. 그러나 교정쇄를 만든 후 해당 교정쇄에 사용자를 추가할 때는 30분 단위(10:00, 10:30, 11:00 등)로만 기한을 설정할 수 있습니다.
feature: Workfront Proof
exl-id: dc0725f4-d31b-4f55-a3ea-24486ce73ebf
product_v2:
  - id: c4a86a5d-6562-4fc6-aa00-bfa25833aed9
    internal-label: Workfront
feature_v2:
  - id: e14a7f57-c82c-4874-a495-5d036cbbdc3d
    internal-label: Resource management
subfeature_v2:
  - id: b18b693b-6d59-4359-95fd-a386b7a615fe
    internal-label: Workfront Proof
role_v2:
  - id: b69b2659-1057-424e-8fc5-ed9e016dc554
    internal-label: User
source-git-commit: 70ec59e07299bc7d7bb4649c67dff23161a50efa
workflow-type: tm+mt
source-wordcount: '243'
ht-degree: 64%
---
# 교정쇄: 기한을 기존 단계의 기한과 일치시킬 수 없어 새 단계가 만들어짐

<!--Requested article-->

새 교정쇄를 만들 때 기한을 15분 단위(10:00, 10:15, 10:30, 20:45 등)로 설정할 수 있습니다. 그러나 교정쇄를 만든 후 해당 교정쇄에 사용자를 추가할 때는 30분 단위(10:00, 10:30, 11:00 등)로만 기한을 설정할 수 있습니다. 따라서 기한을 일치시킬 수 없어 기한이 :15 또는 :45로 끝나는 단계에 새 사용자를 추가할 수 없습니다. 대신 새 사용자가 기한이 30분 단위로 설정된 새 단계에 추가됩니다.

**해결 방법**:

* 새 증명의 기한을 선택하는 경우 :00 또는 :30으로 끝나는 시간(10:00, 10:30, 11:00 등)으로 기한을 설정합니다.
* 증명을 만들 때 기한이 자동으로 설정되는 경우 :00 또는 :30으로 끝나는 시간(10:00, 10:30, 11:00 등)으로 증명 기한을 수동으로 설정합니다.
