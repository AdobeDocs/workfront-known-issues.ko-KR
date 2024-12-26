---
title: '교정쇄: Webcapture 교정쇄가 생성하지 않음'
description: 사용자가 Webcapture 교정쇄를 만들려고 할 때 해당 교정쇄가 정상적으로 생성되지 않습니다.
hidefromtoc: true
feature: Digital Content and Documents
exl-id: 339c5a0a-cfc8-4cfc-946d-b87d760f9106
source-git-commit: 7b66d253831c83bf6166cc5be39e18be704503a6
workflow-type: ht
source-wordcount: '98'
ht-degree: 100%

---

# 교정쇄: Webcapture 교정쇄가 생성하지 않음

>[!NOTE]
>
>이 문제는 설계대로 작동하는 것이므로 종결되었습니다. 아래 해결 방법을 참조하십시오.

사용자가 Webcapture 교정쇄를 만들려고 할 때 해당 교정쇄가 정상적으로 생성되지 않습니다.

**해결 방법**

이 문제는 특정 PDF 파일의 교정쇄 생성 시간이 길어서 발생합니다. 생성 시간 제한을 기본값인 30초에서 더 늘리려면 교정쇄 관리자의 계정 수준에서 처리 설정에서 아래 속성을 편집하십시오.

`WebCaptureNavigationTimeout -> 120`

_2024년 10월 3일에 처음 보고되었습니다._
