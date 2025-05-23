---
title: '사용자: 신규 사용자에게 보류 중인 승인 배지가 표시됨'
description: Workfront의 새 사용자가 승인 보류 중 배지와 함께 사용자 목록에 표시될 수 있습니다. 배지는 몇 분 이상 지속되며 페이지를 새로 고칠 때 계속 표시됩니다.
hidefromtoc: true
feature: People Teams and Groups
source-git-commit: 9c46f9006fa25481a012619a16d627e16f23c15e
workflow-type: tm+mt
source-wordcount: '245'
ht-degree: 1%

---


# 사용자: &quot;승인 보류 중&quot; 배지가 새 사용자에게 표시됨

>[!NOTE]
>
>이 문제는 Adobe Admin Console으로 마이그레이션된 조직에 있을 수 있습니다.

Workfront의 새 사용자가 사용자 목록에 &quot;승인 보류 중&quot; 배지와 함께 표시될 수 있습니다. 배지는 몇 분 이상 지속되며 페이지를 새로 고칠 때 계속 표시됩니다.

이 문제는 사용자가 스프레드시트나 Workfront 킥스타트 등의 일괄 처리로 업로드될 때 더욱 악화됩니다.

예상되는 동작은 몇 분 후에 배지가 사라지고 페이지를 새로 고칠 때 배지가 나타나지 않는 것입니다.

## 해결 방법

이 문제는 Workfront에 추가된 사용자가 Adobe Admin Console과 동기화되지 않을 때 발생합니다.

다음 해결 방법을 권장합니다.

### 개별 사용자 해결

사용자 목록에서 개별 사용자를 확인할 수 있습니다.

1. 사용자 목록에서 사용자를 선택합니다.
1. 목록 헤더에서 점 3개 메뉴를 클릭합니다.
1. **승인**&#x200B;을 선택합니다.
1. 몇 분 후에 페이지를 새로 고칩니다.

### 대량으로 추가된 사용자 해결

대규모 배치에 추가된 사용자를 해결하려면 사용자 배치를 Adobe Admin Console에 직접 추가할 수 있습니다.

지침은 [여러 사용자 관리를 참조하십시오. | Adobe 설명서의 일괄 CSV 업로드](https://helpx.adobe.com/kr/enterprise/using/bulk-upload-users.html).


_2025년 5월 8일 금요일에 처음 보고되었습니다._
