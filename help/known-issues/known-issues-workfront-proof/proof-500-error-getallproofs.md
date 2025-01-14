---
title: 'Workfront Proof: API 또는 Workfront Fusion을 통해 Workfront Proof에 액세스할 때 500 오류 발생'
description: 사용자가 Proof API getAllProof 작업에 액세스하면 Workfront Proof 서버가 500 내부 서버 오류 메시지를 반환합니다.
hidefromtoc: true
feature: Workfront Proof
exl-id: 3c968354-58e2-43fc-8c27-2670683ac862
source-git-commit: 2426476490c3762c7511afee99380afa0bfd85e3
workflow-type: tm+mt
source-wordcount: '106'
ht-degree: 68%

---

# [!DNL Workfront Proof]: API 또는 [!DNL Workfront Fusion]을 통해 [!DNL Workfront Proof]에 액세스할 때 500 오류 발생

>[!NOTE]
>
>제품 팀이 현재 이 문제 해결을 평가 중이며 이에 따라 제품 개선이 필요할 수 있습니다. 제품 개선 사항은 유지 보수 업데이트가 아니라 제품 공지를 통해 전달됩니다.

<!--This article is on Proof and Fusion TOCs-->

사용자가 [!DNL Workfront Proof] API [!UICONTROL `getAllProofs`] 작업에 액세스하면 서버에서 다음 메시지가 반환됨:

[!UICONTROL 500 내부 서버 오류]

[!DNL Workfront Fusion]은 [!DNL Workfront Proof] 모듈용 [!DNL Workfront Proof] API를 사용하기 때문에 이 오류가 모듈에 반환되어 시나리오가 중단될 수 있습니다.

_2023년 4월 28일에 처음 보고되었습니다._
