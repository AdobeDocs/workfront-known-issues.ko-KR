---
title: 2024년 Workfront 유지 관리 업데이트
description: ' [!DNL Adobe Workfront] 유지 관리 업데이트'
feature: Get Started with Workfront
exl-id: 8a8ade95-d940-4773-8032-724bc2d8301e
source-git-commit: abb417f3b19f2c8a5ef27a2318f4fde55fadc99d
workflow-type: ht
source-wordcount: '7353'
ht-degree: 100%

---

# [!DNL Workfront] 유지 관리 업데이트

>[!NOTE]
>
>Workfront를 포함한 모든 Adobe 제품의 유지 관리 중단에 대한 자세한 내용은 [Adobe 상태 페이지](https://status.adobe.com/)를 참조하십시오.

이 페이지에서는 주간 Workfront 업데이트에서 해결된 문제를 설명합니다.

이 업데이트에는 다른 사소하거나 눈에 잘 띄지 않는 버그 수정도 포함되어 있습니다. [!DNL Workfront] 지원 센터에서는 제출된 문제가 해결되면 알려 드립니다.

2024년 이전 유지 관리 업데이트는 [이전 유지 관리 업데이트](#previous-maintenance-updates)를 참조하십시오.

2024년에 유지 관리가 다음과 같이 업데이트되었습니다.

## 2024년 12월 업데이트

+++**2024년 12월 19일 유지 관리 업데이트**

### 2024년 12월 19일 유지 관리 업데이트

이번 업데이트에는 사소하거나 부수적인 버그 수정만 포함되어 있습니다. Workfront 지원 센터에서는 제출된 문제가 해결되면 알려 드립니다.

+++

+++**2024년 12월 12일 유지 관리 업데이트**

### 2024년 12월 12일 유지 관리 업데이트

#### 대시보드

**대시보드 보고서에서 열을 사용하여 정렬하면 열이 사라짐**

대시보드에 배치된 보고서를 열을 기준으로 정렬하면 열이 사라지고 내용이 정렬되지 않습니다.

#### 보고서

**차트 아래 열 그룹화 옵션으로 인해 오류 발생**

차트가 있는 보고서에서 “차트 아래 열 그룹화” 옵션을 활성화하면 다음과 같은 오류 메시지가 표시됩니다. “오류가 발생했으며 문제를 해결하기 위해 노력 중입니다. 작업을 계속하려면 이 브라우저 페이지를 새로 고침해 보십시오.”

**보고서에서 일괄 편집 및 삭제 아이콘이 누락됨**

여러 보고서 항목을 일괄적으로 편집하거나 삭제하려고 할 때 [편집] 및 [삭제] 아이콘이 나타나지 않는 경우가 있습니다.

**프로젝트(재무 데이터) 보고서 오류**

세부 정보 페이지와 매트릭스 페이지 모두에서 프로젝트(재무 데이터) 보고서에 대해 간헐적으로 “죄송합니다” 오류가 표시됩니다.

이러한 문제를 해결하기 위해, 해당 보고서 유형의 프로젝트는 데이터를 로드하기 전에 자동으로 다시 계산되지 않도록 변경되었습니다. 사용자는 재무 데이터 보고서의 데이터를 업데이트하기 위해 개별 프로젝트의 재무를 수동으로 다시 계산해야 합니다.

+++

+++**2024년 12월 5일 유지 관리 업데이트**

### 2024년 12월 5일 유지 관리 업데이트

#### 사용자 정의 양식

**“estimateByHours” 또는 “hoursPerPoint” 작업 필드를 추가할 수 없음**

사용자가 양식 빌더에서 사용자 정의 양식에 “estimateByHours” 또는 “hoursPerPoint” 필드를 추가하려고 하면 “잘못된 사용자 정의 표현식입니다. 다시 시도해 주십시오.”라는 오류 메시지가 표시됩니다.

**사용자 정의 양식에서 표시 논리가 작동하지 않음**

사용자가 표시 논리를 갖춘 사용자 정의 양식에 정보를 입력하면 표시 논리에 따라 나타나야 하는 필드가 나타나지 않습니다.

#### 홈

**참여자에게 작동하지 않는 “작업 실행” 버튼이 표시됨**

참여자 사용자가 홈의 내 작업 위젯에서 작동하지 않는 “작업 실행” 버튼에 액세스할 수 있습니다.

#### 보고서

**사용자 정의 분기가 보고서 프롬프트에 나타나지 않음**

사용자가 날짜 기반 프롬프트를 사용하여 보고서를 실행할 때 프롬프트의 선택 목록에 사용자 정의 분기가 나타나지 않습니다.

+++

## 2024년 11월 업데이트

+++**2024년 11월 28일 유지 관리 업데이트**

### 2024년 11월 28일 유지 관리 업데이트

#### 프로젝트

**“삭제 액세스 권한” 오류로 인해 프로젝트를 공유할 수 없음**

프로젝트를 공유하려고 하면 사용자에게 “이 프로젝트를 삭제할 수 있는 권한이 없습니다” 오류가 표시됩니다. 이는 사용자가 프로젝트를 삭제하려고 하지 않았고 사용자가 프로젝트 소유자이며 프로젝트에 대한 공유 및 관리 액세스 권한이 있음에도 불구하고 발생합니다.

#### 보고서

**카테고리 이름 필드가 사용자 정의 양식에 연결되지 않음**

카테고리 이름 필드가 포함된 보고서에서 목록을 볼 때, 카테고리 이름 열의 콘텐츠를 클릭해도 해당 사용자 정의 양식이 열리지 않습니다.

**보고서에서 그룹 사용자 정의 색상이 작동하지 않음**

Report Builder에서 그룹에 사용자 정의 색상을 할당하는 경우, 보고서를 실행할 때 색상 선택 항목이 나타나지 않습니다.

**보고서 로드 시간이 오래 소요됨**

보고서를 로드하는 데 시간이 오래 걸립니다. 이는 Report Builder에서 보고서를 확인하고, 편집하고 작성하는 데 영향을 미칩니다.

**보고서 프롬프트에서 계산된 날짜/시간 필드에 대한 시간 필드가 누락됨**

사용자 정의 날짜/시간 필드를 프롬프트로 사용하여 보고서를 실행하는 경우 프롬프트 인터페이스에서 시간 선택 필드가 누락됩니다.

**공유 보고서/대시보드를 볼 수 없음**

사용자가 공유된 보고서나 대시보드에 액세스하려고 하면 해당 보고서나 대시보드에 액세스할 수 없습니다.

#### 타임시트

**참여자 사용자에게 “승인을 위해 제출” 버튼이 있음**

참여자 액세스 수준을 가진 사용자가 타임시트에 시간을 입력할 수 없음에도 불구하고 “승인을 위해 제출” 버튼이 클릭할 수 있도록 표시됩니다.

+++

+++**2024년 11월 21일 유지 관리 업데이트**

### 2024년 11월 21일 유지 관리 업데이트

#### 대시보드

**대시보드에서 막대 그래프 보고서의 막대와 상호 작용할 수 없음**

대시보드에서 막대 그래프 보고서의 막대를 클릭하거나 마우스를 가져다 대도, 세부 정보 메뉴가 열리지 않거나 툴팁이 표시되지 않습니다.

#### 프로젝트

**프로젝트가 로드되지 않음**

프로젝트로 이동할 때 가끔 페이지가 콘텐츠를 로드하지 못하는 경우가 있습니다.

#### 보고서

**차트 목록에서 일괄 편집이 응답하지 않음**

사용자가 보고서에서 차트를 보고 있을 때 목록에서 여러 항목을 선택하여 대량 편집하면 커서가 사라지고 대량 편집을 위한 텍스트 상자가 응답하지 않게 됩니다.

**타임시트 보고서에서 편집 및 삭제 버튼이 반응하지 않음**

타임시트 보고서에서 편집 또는 삭제 아이콘을 클릭해도 응답이 없습니다.

**자동 완성 필드를 포함하는 보고서가 로드되지 않음**

사용자 정의 자동 완성 필드가 포함된 보고서를 열 때 해당 보고서가 로드되지 않고 오류 메시지가 표시되는 경우가 종종 있습니다.

+++

+++**2024년 11월 14일 유지 관리 업데이트**

### 2024년 11월 14일 유지 관리 업데이트

#### 홈

**새로운 할 일 및 완료된 할 일에 대한 할 일 위젯 오류**

홈의 할 일 위젯에서 할 일을 새로 만들거나 기존 할 일을 완료하려고 하면 오류가 발생하여 할 일을 만들거나 완료할 수 없습니다.

#### 사용자

**“이들 사용자에게 초대 이메일 보내기” 확인란 누락됨**

Workfront로 신규 사용자를 가져올 때 대화 상자 창에서 “이들 사용자에게 초대 이메일 보내기” 확인란이 누락됩니다.

+++

+++**2024년 11월 7일 유지 관리 업데이트**

### 2024년 11월 7일 유지 관리 업데이트

이번 업데이트에는 사소하거나 부수적인 버그 수정만 포함되어 있습니다. Workfront 지원 센터에서는 제출된 문제가 해결되면 알려 드립니다.

+++

## 2024년 10월 업데이트

+++**2024년 10월 31일 유지 관리 업데이트**

### 2024년 10월 31일 유지 관리 업데이트

이번 업데이트에는 사소하거나 부수적인 버그 수정만 포함되어 있습니다. Workfront 지원 센터에서는 제출된 문제가 해결되면 알려 드립니다.

+++

+++**2024년 10월 24일 유지 관리 업데이트**

### 2024년 10월 24일 유지 관리 업데이트

#### 할당

**작업 할당 시 휴무 아이콘이 나타나지 않음**

사용자가 작업을 할당하고 작업 중에 휴무가 예약된 담당자의 이름을 입력하기 시작하면 제안되는 할당 영역 아래의 사용자 아이콘에 휴무(비행기) 아이콘이 표시되지 않습니다. 사용자가 사용자 및 팀 영역 아래에 이름이 표시되도록 입력을 계속하면 해당 아이콘이 표시됩니다.

#### 사용자 정의 양식

**완료된 프로젝트에서 사용자 정의 데이터를 업데이트할 수 없음**

사용자가 완료된 프로젝트에서 사용자 정의 데이터를 업데이트하려고 할 때 데이터를 업데이트할 수 없으며 다음과 같은 메시지가 표시됩니다.

“상태가 완료인 프로젝트에 대한 작업을 완료할 수 없습니다.”

#### 프로젝트

**완료된 프로젝트에 문제를 추가할 수 없음**

사용자가 완료 상태의 프로젝트에 문제를 추가하려고 할 때 문제를 추가할 수 없습니다. 이 문제는 “문제 추가 및 편집” 옵션이 활성화되어 있어도 발생할 수 있습니다.

**간트 차트가 정확하지 않음**

사용자가 간트 차트를 보고 보기를 전환하면 간트 차트에 정확한 데이터가 표시되지 않거나 데이터가 전혀 표시되지 않을 수 있습니다.

+++

+++**2024년 10월 17일 유지 관리 업데이트**

### 2024년 10월 17일 유지 관리 업데이트

#### 교정쇄

**증거에 잘못된 날짜가 표시됨**

문서 목록에 나열된 날짜에 최신 버전이 생성된 날짜 대신 문서의 첫 번째 버전이 생성된 날짜가 표시됩니다.

#### 타임시트

사용자가 제출 또는 마감 상태인 타임시트에 시간을 기록하려고 할 때 시간을 기록할 수 없습니다.

이는 예상되는 동작이며 문제로 간주되어서는 안 됩니다.

이전에는 Workfront API 또는 Workfront Fusion을 통해 제출된 타임시트 또는 마감된 타임시트에 시간을 기록할 수 있었습니다.

+++

+++**2024년 10월 10일 유지 관리 업데이트**

### 2024년 10월 10일 유지 관리 업데이트

#### 보드

**카드 이동 또는 사용자 할당 시 오류 발생**

카드를 이동하거나 사용자를 할당할 때 가끔 액션이 진행되지 않고 지연된 이후에 “응답 실패: 상태 코드 502 수신” 오류가 발생합니다.

**보드 로드 시 오류**

사용자가 보드를 로드하려고 하면 보드가 로드되지 않고 사용자에게 다음과 같은 메시지가 표시됩니다.

“보드를 로드하는 도중 오류 발생”

“이 보드를 로드하는 도중 문제가 발생했습니다. 페이지를 새로 고침해 다시 시도하거나, 문제가 지속되면 아래 오류 ID를 첨부하여 지원 센터에 문의하십시오.”

#### 홈

**“완료로 표시” 버튼 사용 시 내 문제 위젯에 대한 요약 창 닫힘**

내 문제 위젯을 통해 열린 문제의 요약 창에서 [완료로 표시] 버튼을 사용하면 요약 창이 예기치 않게 닫힙니다.

**레이아웃 템플릿 위젯 설정 시 열 추가 실패**

레이아웃 템플릿 위젯 설정을 통해 위젯에 추가할 필드를 선택할 때 필드를 선택할 수는 있지만 해당 열이 위젯에 나타나지 않습니다.

#### 작업

**타임라인 재계산 문제**

타임라인 재계산과 관련하여 다음과 같은 문제가 보고되었습니다.

* 타임라인 작업 기간을 업데이트할 때 시스템에서 다시 계산하는 데 상당한 시간이 소요됩니다.
* 재계산이 완료되면 타임라인이 계속 재계산 중인 것처럼 날짜가 비활성화된 상태로 유지되거나 비활성화될 수 있습니다.

**작업 경비가 표시되지 않음**

작업에 경비를 추가한 후 API 확인을 입력했음에도 불구하고 작업 정보에 해당 경비가 나타나지 않습니다.

+++

+++**2024년 10월 3일 유지 관리 업데이트**

### 2024년 10월 3일 유지 관리 업데이트

#### 보드

**보관된 연결 카드가 동기화되지 않음**

성능 문제 해결을 위해 보관된 연결 카드는 더 이상 동기화되지 않습니다. Workfront 작업이나 문제에 대한 변경 사항이 보관된 카드에 반영되지 않습니다. 카드를 복원하면 다시 동기화됩니다.

#### 사용자 정의 양식

**사용자 정의 양식에서 표시 유형 전환 오류 발생**

서식이 있는 텍스트 필드로 인해 사용자 정의 양식에 다음 오류가 표시됩니다.

“오류: 텍스트에서 서식이 있는 텍스트로의 표시 유형 전환이 허용되지 않습니다.”

이는 다음과 같은 조건에서 발생할 수 있습니다.

* 사용자가 양식을 편집하기 시작했으나 변경 사항 없이 적용을 클릭합니다.
* 사용자가 사용자 정의 양식을 만듭니다.

두 경우 모두, 서식이 있는 텍스트 필드로 인해 문제가 발생합니다.

#### 알림

**참여자 사용자에게 이메일 알림이 수신되지 않음**

참여자 라이선스가 있는 사용자에게 알림 이메일이 수신되지 않습니다. 이 문제는 즉시 알림 이메일과 일일 요약 이메일 모두에 영향을 미칠 수 있습니다.

#### 교정쇄

**교정쇄용 SSO를 사용하는 경우 전자 서명을 추가할 수 없음**

SSO를 사용하여 교정쇄에 로그인하는 경우 사용자는 전자 서명을 요구하도록 교정쇄를 설정할 수 없습니다.

+++

## 2024년 9월 업데이트

+++**2024년 9월 26일 유지 관리 업데이트**

### 2024년 9월 26일 유지 관리 업데이트

#### 애자일

**스크럼 팀 할당 시 반복에 추가 옵션이 두 번 나열됨**

애자일 스크럼 팀에 작업이나 문제를 할당할 때 “반복에 추가” 옵션이 “더 보기” 메뉴에 두 번 나타납니다. 이는 팀 배정 기능에 영향을 미치지 않으며 스크럼이 아닌 애자일 팀에는 나타나지 않습니다.

#### 사용자 정의 양식

**계산 편집기 필드 목록이 200개 항목으로 제한됨**

이제 사용자 정의 양식의 계산된 필드에 대한 계산 편집기에서 오브젝트의 필드 목록이 시스템 성능을 개선하기 위해 200개 항목으로 제한됩니다. 필드 이름을 알고 있는 경우 목록을 스크롤하지 않고도 자동 완성 옵션을 사용하여 검색할 수 있습니다.

#### 보고서

**보고서 게재가 지연 또는 누락됨**

게재 예약된 보고서가 예상대로 게재되지 않습니다. 게재가 늦을 수도 있고 전혀 게재되지 않을 수도 있습니다.

+++

+++**2024년 9월 19일 유지 관리 업데이트**

### 2024년 9월 19일 유지 관리 업데이트

#### 대시보드

**보고서에서 내보내기 버튼을 선택하면 페이지 상단으로 스크롤됨**

대시보드에서 보고서의 내보내기 버튼을 클릭하면 창이 페이지 상단으로 스크롤되고 열려 있는 내보내기 옵션 메뉴를 찾으려면 다시 아래로 스크롤해야 합니다.

+++

+++**2024년 9월 12일 유지 관리 업데이트**

### 2024년 9월 12일 유지 관리 업데이트

#### 통합

**Outlook에서 요청을 생성할 때 오류 발생**

사용자가 Workfront에서 Outlook 통합을 위한 요청을 생성하려고 시도하고 첨부 파일을 추가하면 “문제가 발생했습니다. 나중에 다시 시도하십시오”라는 메시지가 표시됩니다.

요청이 생성되었고, 요청에 이메일 첨부 파일 폴더가 있지만, 해당 폴더는 비어 있으며 첨부 파일이 요청에 추가되지 않습니다.

+++

+++**2024년 9월 5일 유지 관리 업데이트**

### 2024년 9월 5일 유지 관리 업데이트

#### 그룹

**하위 그룹이 올바르게 표시되지 않음**

사용자가 설정 영역에서 그룹 목록을 조회할 때 하위 그룹이 상위 그룹 아래에 올바르게 나열되지 않은 것을 확인할 수 있습니다. 하위 그룹은 상위 그룹 아래에 올바르게 저장되었지만 목록으로 인해 혼란이 발생할 수 있습니다.

사용자가 하위 그룹을 열면 하위 그룹이 상위 그룹 아래에 올바르게 저장되었음을 이동 경로에서 확인할 수 있습니다.

#### 사용자

**사용자를 다시 활성화할 수 없음**

사용자가 더 보기 메뉴의 “사용자 재활성화” 옵션을 사용하여 사용자를 다시 활성화하려고 하면 사용자의 액세스 수준을 선택할 수 있지만 변경 사항은 저장되지 않습니다. 대신 사용자에게 다음과 같은 오류가 표시됩니다.

“homeGroupID는 null일 수 없음”

+++

## 2024년 8월 업데이트

+++**2024년 8월 29일 유지 관리 업데이트**

### 2024년 8월 29일 유지 관리 업데이트

#### 사용자 정의 양식

**양식이 기본적으로 프로젝트 양식으로 설정됨**

사용자가 사용자 정의 양식을 만들고 양식에 대한 오브젝트 유형을 선택하면 오브젝트 유형이 무시되고 양식은 프로젝트 사용자 정의 양식으로 생성됩니다.

#### 문서

**문서 이름을 클릭하면 빈 페이지로 이동함**

사용자가 문서 목록에서 문서 이름을 클릭하여 문서 세부 정보를 보려고 하면 목록이 사라지고 사용자는 문서 세부 정보로 이동하지 않습니다.

#### 홈

**보류 중인 승인 위젯에 삭제된 문서가 표시됨**

사용자가 홈에서 보류 중인 승인 위젯을 볼 때 삭제된 문서가 표시됩니다. 사용자가 이들 문서 중 하나를 클릭하면 빈 페이지로 이동됩니다.

#### 사용자

**사용자 프로필 이메일 로케일 필드가 비활성화됨**

IMS를 사용하는 조직의 경우 언어 환경 설정은 각 사용자의 Adobe Experience Cloud 프로필에 저장됩니다. Workfront 사용자 프로필의 이메일 로케일 필드가 비활성화되었으며(IMS 조직에만 해당) 해당 필드의 툴팁에 Adobe 프로필에서 언어 설정에 액세스하는 방법에 대한 지침이 제공됩니다.

이는 관리자가 사용자의 이메일 로케일 설정을 변경하려고 할 때 영어로 돌아가는 문제를 해결해 줍니다.

+++

+++**2024년 8월 22일 유지 관리 업데이트**

### 2024년 8월 22일 유지 관리 업데이트

#### 보고서

**설정의 맞춤형 필드 영역에서 보고서를 클릭할 수 없음**

사용자가 사용자 정의 양식 > 설정의 필드 영역을 보고 있고, 해당 보기에 기본 보고서 필드가 포함되어 있는 경우, 보고서에 대한 링크가 작동하지 않습니다. 사용자가 보고서 이름을 클릭하면 해당 보고서로 이동되어야 하지만, 보고서 이름을 클릭해도 이동되지 않습니다.

+++

+++**2024년 8월 15일 유지 관리 업데이트**

### 2024년 8월 15일 유지 관리 업데이트

#### 보드

**카드 중복과 관련된 문제**

보드의 카드 중복과 관련하여 다음과 같은 문제가 보고되었습니다.

* 카드가 두 번 표시됩니다. 이 문제는 페이지를 새로 고쳐 해결할 수 있습니다.
* 사용자가 중복된 카드 중 하나를 삭제하면 해당 중복 카드의 모든 인스턴스가 삭제됩니다.

#### 알림

**알림 환경 설정 도중 “죄송합니다” 오류 발생**

사용자가 알림 환경 설정을 보려고 할 때 다음 오류 메시지가 표시됩니다.

“[!UICONTROL 죄송합니다. 문제가 발생했습니다. 무엇이 잘못되었는지 파악하여 수정할 수 있도록 Workfront에 문의해 주시기 바랍니다.]”

이 문제는 다음 영역에서 보고되었습니다.

* 사용자 프로필의 알림 설정
* 설정의 이벤트 알림 영역

#### 프로젝트

**내보내기 시 통화 기호가 올바르지 않음**

사용자가 문제를 내보낼 때 내보낸 내용의 통화 기호가 프로젝트나 문제에 설정된 통화 기호와 일치하지 않습니다.

#### 교정쇄

**교정쇄 마크업이 정확하지 않음**

교정쇄 인쇄 기능에서 이메일을 통해 수신한 PDF 인쇄물에서 교정쇄 마크업이 잘못 정렬됩니다.


+++

+++**2024년 8월 8일 유지 관리 업데이트**

### 2024년 8월 8일 유지 관리 업데이트

#### 보드

**카드에 하위 작업이 포함되지 않음**

사용자가 상위 작업에 대한 카드를 조회할 때 해당 상위 작업의 하위 작업이 카드에 표시되지 않습니다. 대신 카드에는 하위 작업이 0개 있다고 표시됩니다.

### 보고서

**보고서 게재가 지연 또는 누락됨**

게재 예약된 보고서가 예상대로 게재되지 않습니다. 게재가 늦을 수도 있고 전혀 게재되지 않을 수도 있습니다.

#### 설정

**“다음으로 로그인” 기능을 사용하면 빈 화면이 표시됨**

관리자가 다른 사용자로 로그인하면 해당 사용자의 계정이 아닌 빈 화면이 표시됩니다.

+++

+++**2024년 8월 1일 유지 관리 업데이트**

### 2024년 8월 1일 유지 관리 업데이트

#### 문서

**문서 목록에 대한 보기를 만들 수 없음**

사용자가 문서 목록에서 새 보기를 만들려고 하면 빈 화면으로 바뀌며 사용자가 보기를 만들 수 없게 됩니다.

기존 보기는 예상대로 작동합니다.

#### 통합

**Dropbox 통합 관련 문제**

Dropbox 통합과 관련하여 다음과 같은 문제가 보고되었습니다.

* 사용자가 Dropbox 파일 선택기에서 파일을 검색하려고 할 때 인증 오류 메시지가 표시되며 파일 선택기로 Dropbox에서 파일을 검색할 수 없습니다.
* 사용자가 링크된 폴더를 열려고 할 때 해당 파일이나 폴더가 Dropbox에 더 이상 존재하지 않는다는 오류 메시지가 표시됩니다.

해당 문제는 Workfront가 아닌 Dropbox의 문제로 인해 발생합니다.

+++

## 2024년 7월 업데이트

+++**2024년 7월 25일 유지 관리 업데이트**

### 2024년 7월 25일 유지 관리 업데이트

#### 사용자 정의 양식

**여러 값을 선택하면 드롭다운이 닫힘**

사용자가 사용자 정의 양식 필드에서 여러 값을 선택하려고 하면 첫 번째 값을 선택한 후 드롭다운이 닫힙니다.

이는 필드가 사용자 정의 양식의 표시 논리와 관련되어 있을 때 발생합니다.

#### 알림

**이메일 알림에 썸네일이 표시되지 않음**

사용자가 문서 승인에 관한 이메일 알림을 볼 때 문서 썸네일이 이메일에 표시되지 않습니다.

이 문제가 Gmail에서 보고되었습니다.

+++

+++**2024년 7월 18일 유지 관리 업데이트**

### 2024년 7월 18일 유지 관리 업데이트

#### 애자일

**하위 작업을 추가할 때 스토리 보드가 비어 있음**

필터가 선택된 상태에서 사용자가 스토리보드에 하위 작업을 추가하려고 할 때 화면에 아무것도 표시되지 않으며 사용자가 하위 작업을 추가할 수 없게 됩니다.

#### 홈

**[!UICONTROL 홈 캘린더] 또는 [!UICONTROL 작업 목록]**&#x200B;의 항목을 열 수 없습니다.

사용자가 [!UICONTROL 홈 캘린더] 또는 [!UICONTROL 홈 작업 목록]에서 작업 항목이나 교정쇄를 열려고 하면 해당 항목이 열리지 않습니다.

**다른 사용자로 로그인하면 관리자의 홈이 표시됨**

관리자가 다른 사용자로 로그인하여 해당 사용자의 홈을 볼 경우, 관리자의 홈이 표시됩니다.

#### 교정쇄

**교정쇄를 닫으면 제품 문서 페이지로 연결됨**

사용자가 교정쇄를 보고 닫으려고 할 때 교정쇄를 열기 전에 있던 페이지 대신 프로젝트 문서 페이지로 이동됩니다.

#### Workfront

**사용자 정의 용어가 적용되지 않음**

레이아웃 템플릿에 설정된 사용자 정의 용어가 Workfront의 일부 영역에 표시되지 않습니다. 그 대신 기본 비사용자 정의 용어가 나타납니다.

이 문제는 다음 영역에서 보고되었습니다.

* 메뉴 탭
* 페이지 헤더
* 프로젝트가 나열되어 있는 설명


+++

+++**2024년 7월 11일 유지 관리 업데이트**

### 2024년 7월 11일 유지 관리 업데이트

#### 문제

**문제에 고급 할당을 할 때 오류 발생**

사용자가 Workfront에서 문제에 대한 고급 할당을 시도하면 문제가 할당되지 않고 사용자에게 다음의 오류 메시지가 표시됩니다.

“[!UICONTROL APIModel INTERNAL이 필드 기간(OpTask)을 지원하지 않습니다]”

#### 보고서

**시간 보고서에 매트릭스 설정 시 오류 발생**

사용자가 시간 보고서에서 매트릭스 설정을 수행하려고 하면 설정할 수 없으며 다음과 같은 오류가 표시됩니다.

* “[!UICONTROL 죄송합니다. 문제가 발생했습니다. 무엇이 잘못되었는지 파악하여 수정할 수 있도록 Workfront에 문의해 주시기 바랍니다.]”


+++

+++**2024년 7월 4일 유지 관리 업데이트**

### 2024년 7월 4일 유지 관리 업데이트

#### 홈

**점 3개 메뉴가 작동하지 않음**

사용자가 기존 홈 워크플로에서 점 3개 더 보기 메뉴를 클릭해도 아무런 액션이 실행되지 않습니다.

#### 보고서

**그룹 이름에 슬래시나 백슬래시가 있는 경우 “표시할 데이터 없음”**

사용자가 보고서에서 차트를 보면서 차트의 그룹화를 클릭했을 때 해당 그룹의 이름에 / 또는 \가 있는 경우, 열리는 세부 정보에 그룹의 항목이 표시되지 않고 사용자에게는 “표시할 데이터 없음” 메시지가 표시됩니다.

#### 작업

**사용자가 작업에 할당될 때 작업 역할이 목록에서 사라지지 않음**

작업에 작업 역할이 할당되고 해당 작업이 작업 역할을 가진 사용자에게 할당될 때 작업 역할이 할당 목록에서 사라지지 않습니다.


+++

## 2024년 6월 업데이트

+++**2024년 6월 27일 유지 관리 업데이트**

### 2024년 6월 27일 유지 관리 업데이트

#### 보드

**보드 소유자만 구성 필터를 업데이트할 수 있습니다.**

보안상의 이유로 보드 소유자만 구성 패널에서 보드 필터를 변경할 수 있습니다.

#### 보고서

**기본 통화가 USD인 경우 보고서가 로드되지 않음**

사용자가 기본 통화가 USD인 보고서를 보려고 할 때 보고서가 로드되지 않습니다.

#### 업데이트

**복사한 링크가 올바르게 붙여넣어지지 않음**

사용자가 마우스 오른쪽 클릭을 통해 “[!UICONTROL 링크 주소 복사]”를 선택하여 업데이트에서 링크를 복사하고 업데이트에서 해당 링크를 붙여넣으면 링크가 올바르게 붙여넣어지지 않습니다. 링크의 첫 번째 부분만 링크로 처리되며 나머지 URL은 무시됩니다.

다른 “[!UICONTROL 링크 주소 복사]” 방법으로 링크를 복사하면 링크가 의도한 대로 붙여넣어집니다.

+++

+++**2024년 6월 20일 유지 관리 업데이트**

### 2024년 6월 20일 유지 관리 업데이트

#### 탐색

**뒤로 버튼을 사용하여 이전 페이지로 돌아갈 수 없음**

Workfront 사용자가 브라우저의 뒤로 버튼을 클릭하면 다음과 같은 문제 중 하나가 발생할 수 있습니다.

* 브라우저 탭의 이름은 변경되지만 페이지는 변경되지 않습니다. 뒤로 버튼을 다시 클릭하면 문제가 해결될 수 있습니다.
* 사용자가 브라우저 랜딩 페이지로 이동됩니다.

#### 교정쇄

**교정쇄 뷰어를 닫을 수 없음**

사용자가 교정쇄 뷰어에서 교정쇄를 보고 오른쪽 상단의 X를 클릭하여 교정쇄를 닫으려고 할 때 교정쇄가 닫히지 않습니다.

+++

+++**2024년 6월 13일 유지 관리 업데이트**

### **2024년 6월 13일 유지 관리 업데이트**

#### 그룹

**하위 그룹을 추가할 수 없음**

사용자가 기존 하위 그룹을 그룹에 추가하려고 하면 저장 버튼이 비활성화되고 하위 그룹이 추가되지 않습니다.

+++

+++ **2024년 6월 6일 유지 관리 업데이트**

### 2024년 6월 6일 유지 관리 업데이트

#### 사용자 정의 양식

**양식 디자이너의 기본 필드에 대한 제한 사항**

이제 양식 디자이너에서 만든 사용자 정의 양식에서 여러 기본 필드가 지원됩니다. 이전에는 양식당 하나의 기본 필드로 제한되었습니다.

+++

## 2024년 5월 업데이트

+++ **2024년 5월 30일 유지 관리 업데이트**

### 2024년 5월 30일 유지 관리 업데이트

#### 사용자 정의 양식

설명 텍스트 필드를 편집하는 도중 오류 발생

사용자가 사용자 정의 양식의 설명 텍스트를 편집하려고 하면 텍스트가 저장되지 않고 다음과 같은 오류가 표시됩니다.

“중복 키 값이 고유 제한 사항을 위반함”

이는 기존 양식 빌더에서 보고되었습니다.

#### 업데이트

**멘션을 복사하여 붙여넣어도 언급된 사용자에게 알리지 않음**

사용자가 @ 형식의 멘션이 포함된 댓글을 복사한 다음 해당 댓글을 다른 오브젝트의 업데이트 영역에 붙여넣어도 언급된 사용자에게 붙여넣은 댓글에 대한 알림이 전송되지 않습니다.

+++

+++ **2024년 5월 23일 유지 관리 업데이트**

### 2024년 5월 23일 유지 관리 업데이트

#### 보고서

사용자가 보고서를 조회할 때 브라우저의 뒤로 버튼을 클릭하면 다음과 같은 문제 중 하나가 발생할 수 있습니다.

* 사용자가 해당 보고서 페이지에 남아 있습니다.
* 사용자가 브라우저의 랜딩 페이지로 이동하게 됩니다.
* 사용자가 로그인 페이지로 이동하게 됩니다.

이 문제는 Chrome 브라우저에서 보고되었습니다.

#### 업데이트

**태그된 사용자가 자신을 태그한 사람이 누구인지 확인할 수 없음**

사용자가 업데이트에서 태그된 경우 누가 자신에게 태그를 지정했는지 확인할 수 없습니다. 이는 “다른 회사의 직원들은 다음 위치의 사용자만 조회할 수 있음...” 설정이 “자신의 회사”로 설정된 경우에 발생합니다.

**요약 패널에서 @을 사용하여 사용자를 태그하면 아무 반응이 없음**

사용자가 요약 패널의 업데이트 영역에서 @을 사용하여 다른 사용자를 태그하려고 할 때 드롭다운에서 사용자 이름을 클릭하면 아무 반응이 없습니다. 사용자를 다시 태그하면 예상대로 동작합니다.

+++

+++**2024년 5월 16일 유지 관리 업데이트**

### 2024년 5월 16일 유지 관리 업데이트

#### 설정

**설정의 일부 문제 유형에서 기본 문제 상태가 누락됨**

사용자가 설정에서 문제 상태를 조회할 때 일부 문제 유형에서 문제의 기본 상태(신규, 진행 중, 완료)가 누락된 상태로 표시됩니다. 기본 상태에는 문제 유형을 변경할 수 있는 옵션이 없으므로 사용자는 영향을 받는 문제 유형에 대해 표시할 상태를 재구성할 수 없습니다.

#### 사용자

**사용자를 삭제할 수 없음**

사용자가 사용자를 삭제하려고 해도 해당 사용자가 삭제되지 않습니다. 이는 Adobe Admin Console로 마이그레이션한 조직에서 보고되었습니다.

+++

+++**2024년 5월 9일 유지 관리 업데이트**

### 2024년 5월 9일 유지 관리 업데이트

이번 업데이트에는 사소하거나 부수적인 버그 수정만 포함되어 있습니다. [!DNL Workfront] 지원 센터에서는 제출된 문제가 해결되면 알려 드립니다.

+++

+++**2024년 5월 2일 유지 관리 업데이트**

### 2024년 5월 2일 유지 관리 업데이트

#### 시간 로깅 중

**작업 또는 문제에 대한 시간을 편집할 수 없음**

사용자가 작업 또는 문제에 대한 시간을 편집하려고 할 때 변경 사항이 저장되지 않습니다.

+++

## 2024년 4월 업데이트

+++**2024년 4월 25일 유지 관리 업데이트**

### 2024년 4월 25일 유지 관리 업데이트

#### 업데이트

**번호가 지정된 목록에 번호가 올바르게 매겨지지 않음**

사용자가 번호가 매겨진 목록이 포함된 댓글을 제출하면 업데이트에서 해당 목록에 잘못된 매겨진 번호가 표시됩니다.

이는 새로운 댓글 환경에서 보고되었습니다.

**다른 곳으로 이동했다가 댓글로 돌아갈 때 텍스트가 유지되지 않음**

사용자가 @멘션이 포함된 댓글을 작성한 후 제출하기 전에 댓글에서 다른 곳으로 이동했다가 다시 돌아오면 @멘션 뒤에 입력된 모든 텍스트가 댓글 초안에서 누락됩니다.

이는 새로운 댓글 환경에서 보고되었습니다.

+++

+++**2024년 4월 18일 유지 관리 업데이트**

### 2024년 4월 18일 유지 관리 업데이트

#### 애자일

**Kanban 카드에 사용자 정의 필드가 표시되지 않음**

사용자가 사용자 정의 필드를 포함하도록 구성된 Kanban 보드를 조회할 때 해당 사용자 정의 필드가 표시되지 않을 수 있습니다.

#### 캘린더

**캘린더를 새로 고칠 때 오류 발생**

사용자가 캘린더를 보고 페이지를 새로 고칠 때 “죄송합니다” 오류가 표시됩니다. 캘린더의 데이터가 예상대로 표시되지만 오류 메시지로 인해 가려질 수 있습니다.

#### 사용자 정의 양식

**외부 조회 필드가 결과를 반환하지 않음**

외부 조회 필드가 값이 하나만 선택된 다중 선택 필드를 참조하는 경우 해당 필드는 값을 반환하지 않습니다.

예를 들어 외부 조회 필드가 “빨간색” 및 “파란색” 값이 모두 선택된 다중 선택 필드를 참조하는 경우 해당 필드는 예상대로 작동합니다. 필드에 “빨간색”만 선택된 경우 외부 조회 필드가 값을 반환하지 않습니다.

#### 프로젝트

**웹 교정쇄가 첨부된 경우 문제를 프로젝트로 전환할 수 없음**

문제에 웹 교정쇄(SharePoint와 같은 외부 문서 공급자의 링크를 사용하는 URL 교정쇄)가 첨부되어 있고 사용자가 해당 문제를 프로젝트로 전환하려고 시도하면 전환이 실패하고 프로젝트가 생성되지 않습니다. 사용자에게 다음과 같은 오류가 표시됩니다.

“파일(파일 GUID)을 복사하는 도중 문제가 발생했습니다. 해당 파일을 제거하거나 지원 센터에 문의하고 다시 시도하십시오.”

+++

+++**2024년 4월 11일 유지 관리 업데이트**

### 2024년 4월 11일 유지 관리 업데이트

#### 검색

**검색에서 편집할 수 없음**

고급 검색을 사용 중인 사용자가 검색 결과를 편집 또는 일괄 편집하려고 하면 [편집] 아이콘이 응답하지 않습니다.

#### 업데이트

**업데이트의 이미지 미리보기가 흐릿하게 표시됨**

사용자가 업데이트를 조회하고 이미지를 미리 보기 위해 이미지의 돋보기를 클릭하면 열리는 미리보기가 매우 픽셀화되어 흐릿하게 표시됩니다.

사용자가 이미지를 다운로드하면 이미지가 예상 해상도로 표시됩니다.

**회신할 때 “[!UICONTROL 댓글을 게시할 수 없습니다.]” 메시지가 표시됨**

사용자가 새로운 댓글 달기 경험에서 메시지에 회신하려고 하면 회신이 저장되지 않고 사용자에게 다음과 같은 메시지가 표시됩니다.

“[!UICONTROL 지금은 댓글을 게시할 수 없습니다. 잠시 후 다시 시도해 주십시오.]”

+++

+++**2024년 4월 4일 유지 관리 업데이트**

### 2024년 4월 4일 유지 관리 업데이트

#### 검색

**검색에서 편집할 수 없음**

고급 검색을 사용 중인 사용자가 검색 결과를 편집 또는 일괄 편집하려고 하면 [편집] 아이콘이 응답하지 않습니다.

#### 업데이트

**업데이트의 이미지 미리보기가 흐릿하게 표시됨**

사용자가 업데이트를 조회하고 이미지를 미리 보기 위해 이미지의 돋보기를 클릭하면 열리는 미리보기가 매우 픽셀화되어 흐릿하게 표시됩니다.

사용자가 이미지를 다운로드하면 이미지가 예상 해상도로 표시됩니다.

**회신할 때 “[!UICONTROL 댓글을 게시할 수 없습니다.]” 메시지가 표시됨**

사용자가 새로운 댓글 달기 경험에서 메시지에 회신하려고 하면 회신이 저장되지 않고 사용자에게 다음과 같은 메시지가 표시됩니다.

“[!UICONTROL 지금은 댓글을 게시할 수 없습니다. 잠시 후 다시 시도해 주십시오.]”

+++

+++**2024년 4월 4일 유지 관리 업데이트**

### 2024년 4월 4일 유지 관리 업데이트

#### 통합

**[!DNL Outlook]**&#x200B;에서 요청을 생성할 때 문서가 첨부되지 않음

사용자가 [!DNL Outlook]에서 요청을 만들면 이메일에 첨부된 문서가 요청에 첨부되지 않습니다.

이 문제는 다음 첨부 파일 유형에 대해 보고되었습니다.

XLS
PDF

#### 시간 로깅 중

**사용자가 현재 날짜의 시간을 기록할 수 없음**

사용자가 업데이트 영역에서 시간을 기록하려고 하면 현재 날짜가 회색으로 표시되고 사용자가 현재 날짜의 시간을 기록할 수 없습니다.

#### 업데이트

<!--no article-->

**댓글 조회 시 오류 발생**

사용자가 새로운 댓글 달기 경험에서 댓글을 보려고 하면 댓글을 볼 수 없으며 대신 다음 오류가 표시됩니다.

“문제가 발생했습니다. 나중에 다시 시도해 주십시오.”

레거시 댓글 달기 경험은 예상대로 작동합니다.

+++

## 2024년 3월 업데이트

+++**2024년 3월 28일 유지 관리 업데이트**

### 2024년 3월 28일 유지 관리 업데이트

#### 통합

**[!DNL Outlook]**&#x200B;에서 요청을 생성할 때 문서가 첨부되지 않음

사용자가 [!DNL Outlook]에서 요청을 만들면 이메일에 첨부된 문서가 요청에 첨부되지 않습니다.

이 문제는 다음 첨부 파일 유형에 대해 보고되었습니다.

XLS
PDF

#### 교정쇄

**교정쇄가 “내 승인” 위젯에 남아 있음**

“내 승인” 위젯에서 사라져야 할 교정쇄가 위젯에 그대로 남아 있습니다. 이는 여러 사용자가 동시에 교정쇄에 대해 결정을 내리거나 한 명의 사용자가 결정을 내리고 이를 빠르게 변경할 때 발생할 수 있습니다.

#### 리소스 관리

**예산 시간에서의 불일치**

다음 영역 중 하나에서 표시되는 예산 시간이 다른 영역에서 표시되는 것과 일치하지 않을 수 있습니다.

* 비즈니스 사례
* 보고서
* 리소스 예산 책정 도구

#### 작업

**전임 작업 도구 설명에 작업 이름이 표시되지 않음**

사용자가 작업 목록을 보고 더 많은 정보를 얻기 위해 전임 작업 아이콘 위로 마우스를 가져가면 나타나는 도구 설명에 전임 작업 이름이 표시되지 않습니다.

#### 업데이트

**문서 댓글이 상위 오브젝트 업데이트에 표시되지 않음**

사용자가 문서에 댓글을 달면 해당 댓글이 문서 &#x200B;&#x200B;상위 오브젝트의 업데이트 영역에 즉시 나타나지 않습니다.

이 문제는 새로운 댓글 달기 환경에서 보고되었습니다. 기존 댓글 달기 환경에서는 댓글이 예상대로 표시됩니다.

**사용자 태그 지정이 효과가 없음**

댓글에 사용자를 태그 지정하면 해당 댓글이 태그 지정된 사용자에게 표시되지 않습니다. 또한 태그 지정된 사용자에게 이메일이나 인앱 알림을 통해 해당 댓글에 대한 알림이 전송되지 않습니다.

이는 기존 댓글 달기 경험에서 보고되었습니다.

+++

+++**Workfront Fusion 2024년 3월 28일 유지 관리 업데이트**

### Workfront Fusion 2024년 3월 28일 유지 관리 업데이트

**Workfront 모듈에서 반환되는 RuntimeError [200] 응답**

Workfront 모듈은 `RuntimeError [200]` 응답을 반환할 수 있습니다. 200은 성공적인 응답을 의미하지만, 오류는 요청이 실패했음을 나타냅니다.

응답이 너무 길면 이런 일이 발생할 수 있습니다. 데이터가 Fusion으로 반환되나, Fusion에서 처리할 수는 없습니다.

+++

+++**2024년 3월 21일 유지 관리 업데이트**

### 2024년 3월 21일 유지 관리 업데이트

#### 업데이트

**줄 사이의 넓은 공백**

사용자가 Return 또는 Enter 키를 사용하여 여러 줄의 업데이트를 입력하거나 업데이트에 여러 줄을 붙여넣으면 업데이트가 예상대로 나타납니다. 그러나 사용자가 보고서에서 해당 업데이트를 조회하면 줄 사이에 넓은 공백이 있습니다.

이는 새로운 댓글 환경에서 보고되었습니다.

**@를 사용한 사용자 태그 지정이 효과가 없음**

사용자가 댓글에 다른 사용자를 @로 태그 지정하면 해당 사용자가 태그 지정된 사용자 영역에 추가되지 않으며 해당 댓글에 대한 알림도 받지 않습니다.

이 수정 사항은 새로운 댓글 달기 경험에만 적용됩니다.

+++

+++**2024년 3월 14일 유지 관리 업데이트**

### 2024년 3월 14일 유지 관리 업데이트

#### 교정쇄

**연결된 문서에서 생성된 교정쇄에 교정 템플릿이 적용되지 않음**

사용자가 연결된 문서에서 교정쇄를 만들면 교정 템플릿이 올바르게 적용되지 않으며 교정쇄에 워크플로와 같은 정보가 누락될 수 있습니다.

이는 API 및 Workfront Fusion을 통해 생성된 교정쇄에도 적용됩니다.

#### 사용자

**사용자 생성 시 더 낮은 액세스 수준을 사용할 수 없음**

사용자가 다른 사용자를 생성하는 경우 새로 생성된 사용자는 첫 번째 사용자의 액세스 수준만 사용할 수 있습니다. 새 사용자를 생성한 사용자의 권한보다 낮은 권한을 가진 모든 액세스 수준을 새 사용자에게도 할당할 수 있어야 합니다.

+++

+++**2024년 3월 7일 유지 관리 업데이트**

### 2024년 3월 7일 유지 관리 업데이트

#### 보드

**보드에 작업 추가 시 400 오류**

사용자가 프로젝트를 조회하고 보드에 작업을 추가하려고 하면 작업이 추가되지 않고 사용자에게 다음 오류가 표시됩니다.

오류: “400: 정의되지 않음 /boards-service/graphql”

#### 홈

**내 작업 위젯에서 작업을 인라인 편집할 때 오류 발생**

사용자가 내 작업 위젯에서 작업을 인라인 편집하려고 하면 다음 오류가 표시됩니다.

“오류가 발생했으며 문제를 해결하기 위해 노력 중입니다. 작업을 계속하려면 이 브라우저 페이지를 새로 고침해 보십시오.”


#### 워크로드 밸런서

**계획된 시간이 워크로드 밸런서에서 업데이트되지 않음**

프로젝트의 계획된 시간이 업데이트되어도 워크로드 밸런서에서 업데이트되지 않습니다. 변경 사항이 프로젝트에 정확하게 반영되었음에도 불구하고 이런 현상이 발생할 수 있습니다.

+++

+++**Workfront Fusion 2024년 3월 7일 유지 관리 업데이트

**Workfront Proof > 교정쇄 보기 모듈 시간 초과**

[Workfront Proof] > [교정쇄 보기] 모듈을 사용하는 시나리오는 교정쇄 보기 모듈 시간 초과로 인해 비활성화될 수 있습니다.

+++

## 2024년 2월 업데이트

+++**2024년 2월 29일 유지 관리 업데이트**

### 2024년 2월 29일 유지 관리 업데이트

#### 업데이트

**업데이트: 다른 회사의 사용자에게 회신하면 빈 화면이 표시됨**

다른 회사의 사용자가 작성한 댓글에 사용자가 회신하려고 하면 빈 화면이 표시됩니다.

이는 해당 사용자가 다른 회사의 사용자를 볼 수 있는 권한이 없기 때문입니다.

+++

+++**2024년 2월 22일 유지 관리 업데이트**

### 2024년 2월 22일 유지 관리 업데이트

#### 홈

**[!UICONTROL 홈]: [!UICONTROL Workspace] 및 핀이 로드되지 않음**

사용자가 로그인하면 다음과 같은 문제가 발생할 수 있습니다.

* 사용자의 새 [!UICONTROL 홈 작업 영역]이 로드되지 않고 다음과 같은 오류 메시지가 표시됩니다. “[!UICONTROL Workspace 정보를 로드할 수 없습니다. 무엇이 잘못되었는지 파악하여 수정할 수 있도록 Workfront에 문의해 주시기 바랍니다.]”
* 사용자의 핀이 로드되지 않고 다음과 같은 오류 메시지가 표시됩니다. “[!UICONTROL 시스템 오류로 인해 핀을 사용할 수 없습니다. 문제를 해결하려면 브라우저를 새로 고쳐 보십시오.]”

#### 사용자

**그룹 관리자가 사용자의 액세스 수준을 설정하거나 변경할 수 없음**

<!--no article-->

그룹 관리자가 사용자의 액세스 수준을 변경하려고 하면 다음 중 하나가 발생할 수 있습니다.

* 액세스 수준 필드가 비활성화됩니다.
* 그룹 관리자가 더 낮은 액세스 수준을 선택할 수 없습니다.

#### 워크로드 밸런서

**휴무 시간 레이블**

이제 워크로드 밸런서 및 개인 휴무 캘린더에 사용자의 휴무에 대해 “[!UICONTROL 휴무 시간]”이 표시됩니다. 이전에는 휴무 시간에 대해 “[!UICONTROL 작업 시간]”이 표시되었습니다.

+++

+++**2024년 2월 15일 유지 관리 업데이트**

### 2024년 2월 15일 유지 관리 업데이트

#### 문제

**문제를 일괄 편집할 때 시간 필드에 잘못된 시간이 저장됨**

사용자가 문제를 일괄 편집하고 날짜 필드에 대한 날짜와 시간을 선택하고 저장하면 해당 문제에서 이 필드에 저장되는 시간이 사용자가 선택한 시간과 다릅니다. 대신 사용자가 저장하면 시간이 UTC로 변환되는 것처럼 보입니다.

#### 작업

**사용자가 하나 이상의 작업에서 할당 해제됨**

사용자가 자신에게 할당된 작업에서 자동으로 할당 해제될 수 있습니다. 이는 하나 이상의 작업에서 발생할 수 있습니다. 할당 해제는 설정 메뉴의 업데이트 피드 섹션에는 표시되지만 해당 작업의 시스템 업데이트 영역에는 표시되지 않습니다.

#### 업데이트

**댓글 편집 시 비활성화된 이미지 옵션을 사용할 수 있음**

[!DNL Workfront] 관리자가 댓글에 이미지를 추가하는 옵션을 비활성화한 후에는 댓글을 작성할 때 해당 옵션을 사용할 수 없습니다. 단, 사용자가 기존 댓글을 편집하는 경우에는 이미지 옵션을 사용할 수 있습니다.

+++

+++**2024년 2월 8일 유지 관리 업데이트**

### 2024년 2월 8일 유지 관리 업데이트

#### 보드

**[!UICONTROL 이동] 옵션**&#x200B;을 사용하여 열의 카드를 이동할 수 없음

사용자가 점 3개로 된 메뉴의 “[!UICONTROL 열 상단]” 또는 “[!UICONTROL 열 하단]” 옵션을 사용하여 열의 카드를 이동하려고 하면 카드가 이동하지 않습니다.

**반복을 변경할 때 카드가 지속됨**

사용자가 보드에서 반복을 본 다음 반복을 변경할 때 사용자가 이전에 보았던 반복의 카드가 새 반복에 대해 표시됩니다.

#### 보고서

**“값 없음” 열에 결과가 표시되지 않음**

차트 보고서에 “[!DNL No value]” 열이 있으면 데이터가 있어야 함에도 불구하고 해당 열에 데이터가 표시되지 않습니다.

#### 리소스 관리

**작업 역할 문제로 인해 재무 계산이 잘못됨**

시간 및 재무 계산이 잘못되어 비용 요율이 있는 작업 역할에 시간이 기록되어 있어도 비용이 0으로 표시될 수 있습니다.

이는 작업 역할이 시작 일자나 종료 일자 없이 중복 요율을 자동으로 생성하기 때문입니다. 시작 일자나 종료 일자가 없기 때문에 재무 계산이 실행될 때 값이 0으로 처리됩니다.

+++

+++**2024년 2월 1일 유지 관리 업데이트**

### 2024년 2월 1일 유지 관리 업데이트

#### 로그인

**SSO를 사용하는 사용자는**&#x200B;에 로그인 시 원래 위치로 리디렉션되지 않음

사용자가 [!DNL Workfront] 페이지에 있고 SSO로 로그인하는 경우, 로그인이 완료되면 로그인하기 전에 있었던 이전 페이지 대신 [!UICONTROL 홈]으로 이동됩니다.

#### 템플릿

**템플릿을 복사하는 중 오류 발생**

사용자가 신규 또는 기존 템플릿을 복사하려는 경우, 템플릿이 복사되지 않고 다음과 같은 오류가 표시됩니다.

“[!UICONTROL ID는 null일 수 없습니다.]”

+++

## 2024년 1월 업데이트

+++**2024년 1월 30일 유지 관리 업데이트 (핫픽스)**

### 2024년 1월 30일 유지 관리 업데이트 (핫픽스)

#### 보고서

**외부 API 필드에는 목록 및 보고서에 사용 가능한 모든 값이 표시되지 않음**

이전에는 사용자가 목록 및 보고서의 외부 조회 필드에 대해 선택한 값을 보고 값을 편집할 수 있었지만, API에서 제공되는 옵션이 포함된 드롭다운은 볼 수 없었습니다.

이제 외부 조회 사용자 정의 필드가 목록이나 보고서에 사용될 때 외부 API의 모든 옵션이 포함된 드롭다운을 사용할 수 있습니다.

+++

+++**2024년 1월 25일 유지 관리 업데이트**

### 2024년 1월 25일 유지 관리 업데이트

#### 보드

**상태가 변경되면 카드가 해당 열로 이동하지 않음**

연결된 카드의 연결 오브젝트 상태가 해당 오브젝트에서 직접 변경되면 카드가 해당 열로 이동하지 않습니다. 카드에서 오브젝트 상태가 변경되거나 카드를 새 열로 드래그하면 카드가 예상대로 작동합니다.

#### 알림

**알림을 본 것으로 표시하는 것이 지속되지 않음**

사용자가 알림을 본 것으로 표시한 다음 [!DNL Workfront] 내의 다른 페이지로 이동하면 알림 아이콘에는 사용자가 본 것으로 표시하기 전에 있었던 읽지 않은 알림 수가 계속 표시되고, 사용자가 해당 아이콘을 클릭하면 알림이 계속 나열됩니다. 이는 사용자가 해당 페이지를 본 것으로 표시하고 다른 페이지로 이동하거나 원래 페이지로 돌아가는 경우에도 계속됩니다.

#### 업데이트

**기존 댓글 달기 경험에서 태그 지정 관련 문제 발생**

기존 댓글 달기 경험에서 사용자가 댓글에 태그되면 다음과 같은 문제가 발생합니다.

* 댓글에 사용자의 이름만 표시됨
* 사용자 이름에 @ 기호가 표시되지 않음
* 사용자 이름이 파란색으로 표시되지 않음
* 사용자의 이름이 해당 사용자의 프로필에 대한 링크가 아님

사용자는 예상대로 태그에 관한 이메일 알림을 받습니다.

+++

+++**2024년 1월 18일 유지 관리 업데이트**

### 2024년 1월 18일 유지 관리 업데이트

#### 보드

**카드에 문서를 첨부할 수 없음**

사용자가 연결된 카드에 문서를 첨부하려고 할 때 첨부할 문서를 선택할 수는 있으나 카드의 문서 영역에 해당 문서가 표시되지 않고 카드가 연결된 오브젝트에 문서가 첨부되지 않는 문제가 발생합니다.

이는 문제와 연결된 카드에서 보고되었습니다.

**여러 스프린트에 카드가 표시됨**

사용자가 보드에서 스프린트를 볼 때 다른 스프린트에 있는 카드가 보드에 표시됩니다. 이 문제는 간헐적으로 발생합니다.

**프로젝트에서 보드 보기를 사용할 때 카드가 닫히지 않음**

사용자가 프로젝트의 작업 목록에서 보드 보기를 보고 카드를 만들면 카드가 닫히거나 저장되지 않습니다. 이로 인해 사용자가 프로젝트로 돌아갈 수 없습니다.

카드를 닫으려면 사용자가 URL을 편집하여 “보드”와 “보드” 오른쪽에 있는 모든 항목을 제거해야 합니다.

**반복을 변경할 때 카드가 지속됨**

사용자가 보드에서 반복을 본 다음 반복을 변경할 때 사용자가 이전에 보았던 반복의 카드가 새 반복에 대해 표시됩니다.

**카드의 [!UICONTROL 댓글] 섹션에 오류 발생**

사용자가 카드를 보고 있을 때 [!UICONTROL 댓글] 섹션으로 스크롤하면 댓글이 표시되지 않고 사용자에게 다음 오류가 표시됩니다.

“[!UICONTROL 문제가 발생했습니다. 나중에 다시 시도해 주십시오.]”

**하위 작업 상태를 조회할 때 오류 발생**

보드의 카드에서 하위 작업 상태를 보는 것과 관련해 다음과 같은 문제가 보고되었습니다.

* 작업에 이미 상태가 있는 경우에도 상태가 “상태 선택”으로 표시됩니다. 이 상태는 작업을 직접 볼 때 표시됩니다.
* 사용자가 상태를 선택하려고 하면 빈 화면으로 바뀌고 새로 고침해야 합니다.

**카드에서 댓글 조회 시 “[!UICONTROL 액세스 권한 없음]”**

사용자가 [!DNL Workfront] 오브젝트에 연결되지 않은 카드에서 댓글을 조회하려고 하면 다음과 같은 오류 메시지가 표시됩니다.

“[!UICONTROL 이 오브젝트에 대한 댓글을 볼 수 있는 액세스 권한이 없습니다.]”

이는 해당 사용자가 이전에 카드에서 댓글을 볼 수 있었던 경우에도 발생할 수 있습니다.

#### 사용자 정의 양식

**템플릿 작업에서 사용자 정의 양식을 일괄 추가하거나 제거할 수 없음**

사용자가 템플릿 작업에서 사용자 정의 양식을 일괄 추가하거나 제거하려고 하면 양식이 추가 또는 제거되지 않고 사용자에게 다음과 같은 오류 메시지가 표시됩니다.

[!UICONTROL 다시 시도해 보십시오. 잘못된 매개변수: templateID 값 “XXXXXXXXXXXXXXXX”]

사용자가 지정된 GUID가 있는 템플릿을 찾은 다음 나머지 템플릿 작업에서 사용자 정의 양식을 추가하거나 제거하려고 하면 다른 템플릿 ID를 사용하는 오류가 다시 발생합니다.

단일 템플릿 작업에서는 사용자 정의 양식을 추가하거나 제거할 수 있습니다. 이 오류는 일괄 추가 또는 제거 시에만 발생합니다.

#### 포트폴리오

**그룹 페이지에 사용자 정의 용어가 적용되지 않음**

사용자가 포트폴리오 수준에서 사용자 정의 용어를 설정하면 해당 용어가 그룹 수준 페이지에 적용되지 않습니다.

#### 설정

**선택적 상태를 숨길 수 없음**

사용자가 시스템 및 그룹 수준에서 선택적 상태를 숨기려고 하면 상태가 숨겨지지 않습니다. 사용자가 상태를 보면 사용자가 상태를 숨기는 옵션을 활성화하고 변경 사항을 저장한 경우에도 활성화되지 않습니다.

**설정의 일부 문제 유형에서 기본 문제 상태가 누락됨**

사용자가 설정에서 문제 상태를 조회할 때 일부 문제 유형에서 문제의 기본 상태(신규, 진행 중, 완료)가 누락된 상태로 표시됩니다. 기본 상태에는 문제 유형을 변경할 수 있는 옵션이 없으므로 사용자는 영향을 받는 문제 유형에 대해 표시할 상태를 재구성할 수 없습니다.

#### 팀

**[!UICONTROL 완료] 버튼에 대한 팀 상태 설정 관련 문제**

팀을 편집하거나 생성할 때 [!UICONTROL 완료] 버튼 상태와 관련된 다음과 같은 문제가 보고되었습니다.

* [!UICONTROL 새 팀] 창 또는 기존 팀의 [!UICONTROL 팀 설정] 영역의 완료 버튼에서 일부 상태가 누락될 수 있습니다.
* 사용자가 팀을 저장하려고 하면 “각 카테고리에서 상태를 하나 이상 선택해야 합니다”라는 오류 메시지가 표시될 수 있습니다.

#### 템플릿

**프로젝트에 템플릿을 첨부할 때 오류 발생**

사용자가 프로젝트에 템플릿을 첨부하려고 하면 다음과 같은 오류 메시지가 표시됩니다.

“죄송합니다. 문제가 발생했습니다. 무엇이 잘못되었는지 파악하여 수정할 수 있도록 Workfront에 문의해 주시기 바랍니다.”

이는 사용자에게 템플릿에 첨부된 사용자 정의 양식에 대한 보기 권한이 없을 때 발생합니다.

#### 업데이트

**댓글이 기존 경험과 새 경험 간에 이전되지 않음**

기존 댓글 달기 환경에서 작성된 댓글이 새로운 댓글 달기 환경에서는 표시되지 않을 수 있습니다. 반대의 경우도 발생할 수 있습니다.

+++

+++**2024년 1월 11일 유지 관리 업데이트**

### 2024년 1월 11일 유지 관리 업데이트

#### 보드

**완료된 카드가 동적 보드에 제대로 로드되지 않음**

이전에는 완료된 작업을 동적 보드에 포함시키는 유일한 방법은 카드를 보관된 카드로 로드하는 것이었습니다. 그렇지 않으면 완료된 카드가 보드에 전혀 로드되지 않았습니다. 이로 인해 카드를 찾는 데 문제가 발생했습니다.

이제 동적 보드를 생성할 때 완료된 카드는 기본적으로 보관된 카드로 로드되지만, “완료된 카드 보관 안 함”을 선택하여 보드의 모든 완료된 카드를 완료됨 열에 표시되는 카드로 로드할 수 있습니다.

+++

## 이전 유지 관리 업데이트

이전 유지 관리 업데이트 관련 정보가 여기에 제공됩니다.

* [[!DNL Workfront] 유지 관리 업데이트 보관 - 2023](2023-updates.md)
* [[!DNL Workfront] 유지 관리 업데이트 보관 - 2022](2022-updates.md)
* [[!DNL Workfront] 유지 관리 업데이트 보관 - 2021](2021-updates.md)