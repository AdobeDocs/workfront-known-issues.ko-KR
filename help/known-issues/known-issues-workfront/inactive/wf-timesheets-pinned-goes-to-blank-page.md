---
title: "타임시트: 고정된 타임시트가 빈 페이지로 이동함"
description: '"사용자가 Workfront에서 타임시트로 이동하기 위한 핀을 클릭하면 대신 핀이 빈 페이지로 이동합니다. 해결 방법을 사용할 수 있습니다.”'
hidefromtoc: true
feature: Timesheets
source-git-commit: d3068f21ba6e1a9a1dd4a9ed78da43cef88f4fde
workflow-type: tm+mt
source-wordcount: '123'
ht-degree: 7%

---


# 타임시트: 고정된 타임시트가 빈 페이지로 이동함

사용자가 Workfront에서 타임시트로 이동하기 위한 핀을 클릭하면 대신 핀이 빈 페이지로 이동합니다.

타임시트의 URL이 변경되었기 때문입니다. 다음 `/own` URL의 끝에 있는 은 더 이상 올바른 URL이 아닙니다. 사용자가 다음을 포함하는 URL을 고정한 경우 `/own`: 해당 고정 항목이 빈 페이지로 연결됩니다.

**해결 방법**

1. 타임시트를 고정 해제합니다.
1. 제거 `/own` URL 끝부터
1. 타임시트를 다시 고정합니다.

_2024년 5월 7일 수요일에 처음 보고되었습니다._
