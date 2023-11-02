---
title: "업데이트: API 또는 Workfront Fusion을 통해 만들어진 댓글에 추가 줄 표시"
description: "사용자가 API 또는 Workfront Fusion을 통해 댓글을 제출하면 업데이트 영역에 표시되는 댓글에 추가 줄이 표시됩니다. 때로는 줄이 너무 많아 사용자가 아래로 스크롤하여 주석 콘텐츠를 확인해야 합니다."
hidefromtoc: true
feature: Updates and Notifications
source-git-commit: 1854e4a003722f1398c703dfba7bc23ef534f81f
workflow-type: tm+mt
source-wordcount: '167'
ht-degree: 8%

---


# 업데이트: API 또는 를 통해 작성한 댓글의 추가 줄 [!DNL Workfront Fusion]

사용자가 API 또는 를 통해 댓글을 제출할 때 [!DNL Workfront Fusion]업데이트 영역에 표시되는 주석에 추가 줄이 표시됩니다. 줄이 너무 많아 사용자가 아래로 스크롤해야 주석 콘텐츠를 볼 수 있습니다.

이는 새로운 댓글 환경에서 보고되었습니다.

**해결 방법**

이 문제는 댓글에 제출된 HTML에서 공백이나 줄바꿈으로 인해 발생합니다.

이 문제를 방지하려면 HTML 요소 사이에 공백이나 줄 바꿈 없이 모든 HTML이 한 줄에 있어야 합니다.

영향을 받는 주석을 추가 줄 없이 보려면 클래식 주석 달기 경험으로 전환하십시오.

_2023년 27월 10일에 처음 보고되었습니다._
