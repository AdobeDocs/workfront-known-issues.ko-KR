---
title: "Workfront Fusion: Google에 대한 연결을 만들 수 없음"
description: "사용자가 Google 커넥터(예: Google 시트 또는 Google 드라이브)에서 연결을 만들려고 하면 연결이 만들어지지 않고 사용자에게 다양한 오류 메시지가 표시됩니다."
hidefromtoc: true
source-git-commit: 7d50ddbd99edf3421ce92564590a2d8db76ae939
workflow-type: tm+mt
source-wordcount: '103'
ht-degree: 3%

---


# [!DNL Workfront Fusion]: 연결을 만들 수 없습니다. [!DNL Google]

사용자가 [!DNL Google] 커넥터(예 [!DNL Google Sheets] 또는 [!DNL Google Drive])이면 다음 오류가 발생하여 창이 열립니다.

```
"detail": "Unexpected token � in JSON at position 0",
"message": "Bad Request",
"code": "SC400",
"suberrors": []
```

사용자가 이 창을 닫으면 내부 오류 때문에 연결이 실패합니다 [!DNL Fusion]:

&quot;[!UICONTROL 오류: 이전 요청의 실패로 인해 요청이 실패했습니다. 액세스 토큰을 지정하지 않았습니다.]&quot;

_2022년 11월 21일에 처음 보고되었습니다._

