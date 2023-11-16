---
title: '“업데이트: API 또는 Workfront Fusion을 통해 작성된 댓글에 추가 행이 있음”'
description: “사용자가 API 또는 Workfront Fusion을 통해 댓글을 제출하면 업데이트 영역에 표시되는 댓글에 추가 행이 표시됩니다. 경우에 따라 행이 너무 많아서 사용자가 댓글 내용을 보려면 아래로 스크롤해야 할 때도 있습니다.”
hidefromtoc: true
feature: Updates and Notifications
source-git-commit: 6d87394383aaf54385163729f85ea065588967c9
workflow-type: tm+mt
source-wordcount: '173'
ht-degree: 100%

---


# 업데이트: API 또는 [!DNL Workfront Fusion]을 통해 작성된 댓글에 추가 행이 있음

>[!NOTE]
>
>이 문제는 2023년 11월 16일에 해결되었습니다.

사용자가 API 또는 [!DNL Workfront Fusion]을 통해 댓글을 제출하면 업데이트 영역에 표시되는 댓글에 추가 행이 표시됩니다. 경우에 따라 행이 너무 많아서 사용자가 댓글 내용을 보려면 아래로 스크롤해야 할 때도 있습니다.

이는 새로운 댓글 환경에서 보고되었습니다.

**해결 방법**

이 문제는 댓글에 제출된 HTML의 공백이나 줄 바꿈으로 인해 발생합니다.

이러한 문제를 방지하려면 HTML 요소 사이에 공백이나 줄 바꿈 없이 모든 HTML이 한 줄에 있는지 확인하십시오.

추가 행 없이 영향을 받은 댓글을 보려면 클래식 댓글 환경으로 전환하십시오.

_2023년 27월 10일에 처음 보고되었습니다._
