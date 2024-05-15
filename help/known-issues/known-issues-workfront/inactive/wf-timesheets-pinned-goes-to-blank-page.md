---
title: '“타임시트: 고정된 타임시트가 빈 페이지로 이동”'
description: “사용자가 Workfront에서 타임시트로 이동하기 위해 핀을 클릭하면 핀이 빈 페이지로 이동합니다. 해결 방법을 사용할 수 있습니다.”
hidefromtoc: true
feature: Timesheets
source-git-commit: 89eb14bfaccb517764af1711ca31e2926de63795
workflow-type: ht
source-wordcount: '123'
ht-degree: 100%

---


# 타임시트: 고정된 타임시트가 빈 페이지로 이동

사용자가 Workfront에서 타임시트로 이동하기 위해 핀을 클릭하면 핀이 빈 페이지로 이동합니다.

타임시트의 URL이 변경되었기 때문입니다. URL 끝에 있는 `/own`이 더 이상 올바른 URL이 아닙니다. 사용자가 `/own`을 포함하는 URL을 고정한 경우 해당 핀은 빈 페이지로 연결됩니다.

**해결 방법**

1. 타임시트를 고정 해제합니다.
1. URL 끝의 `/own`을 삭제합니다.
1. 타임시트를 다시 고정합니다.

_2024년 5월 7일에 처음 보고되었습니다._

