---
nav_title: Stylitics
article_title: Stylitics
description: "이 참조 문서는 Braze와 클라우드 기반 SaaS 플랫폼인 Stylitics 간의 파트너십을 설명하며, 이를 통해 기존 이메일 캠페인을 매력적이고 관련성 있는 번들 콘텐츠로 강화하여 개인화된 고객 경험을 창출할 수 있습니다."
alias: /partners/stylitics/
page_type: partner
search_tag: Partner

---

# Stylitics

> [Stylitics](https://stylitics.com/)는 소매업체가 시각적 콘텐츠를 대규모로 자동화하고 배포할 수 있도록 지원하는 클라우드 기반 SaaS 플랫폼입니다. Stylitics 번들은 제품의 컨텍스트를 구성하고 구매 자신감을 높이며 인게이지먼트를 늘려 궁극적으로 평균 주문 가치와 전환율을 높임으로써 영감을 번들로 제공합니다.

귀하의 Braze 및 Stylitics 통합을 통해 기존 이메일 캠페인을 매력적이고 관련성 있는 번들 콘텐츠로 강화하여 개인화된 고객 경험을 창출할 수 있습니다.

![][0]{: style="max-width:60%;"}

## 전제 조건

| 요구 사항 | 설명 |
| ----------- | ----------- |
| Stylitics 계정 | [Stylitics](https://stylitics.com/) 계정을 사용해야 이 파트너십을 활용할 수 있습니다. |
{: .reset-td-br-1 .reset-td-br-2 role="presentation" }

## 사용 사례

다음에서는 트리거된 일반적인 이메일 프로그램 예제를 나열합니다.
- 유기한 장바구니 이메일 
- 유기한 찾아보기 이메일 
- 배송 확인 이메일
- 구매 후 이메일 

## 통합

Stylitics는 이 통합을 위한 번들 데이터를 제공합니다. 귀하의 이메일 서비스 제공업체는 Stylitics 번들을 포함하도록 이메일 템플릿을 생성하거나 업데이트할 수 있습니다. Stylitics는 이메일의 레이아웃이나 디자인을 변경할 수 없습니다. 

1. 번들을 이메일에 통합합니다. ESP는 위치와 사용자 지정을 결정합니다.
2. 이메일 서비스 공급자는 트리거 이메일 코드를 업데이트하여 Stylitics 콘텐츠를 포함합니다.
3. ESP는 트리거된 업데이트 시리즈를 테스트하고, 미리 보며, 시작합니다. 

Stylitics는 항목에 대한 번들 데이터만 제공합니다. 사용자와 ESP 사이에서 사용자 데이터를 보유하고 있으며, 사용자에게 전송할 Stylitics 번들 데이터를 연결할 수 있습니다.

## 데이터 교환

다음 세 가지 접근 방식으로 트리거된 이메일에 Stylitics 번들을 포함할 수 있습니다.

### 1\. API 접근 방식 (권장됨)

사용자 또는 사용자의 ESP는 항목당 API 호출을 수행하여 번들 데이터를 이메일에 채울 수 있습니다. Stylitics는 즉시 사용할 수 있도록 API를 사용하여 API 호출을 수행할 것을 권장합니다.

{% alert note %}
Stylitics에서 실행하는 A/B 테스트를 실행하는 경우, `styliticsCID` 및 `styliticsoverride` 매개변수를 사용자가 이메일에서 클릭하는 Stylitics 항목의 PDP URL에 추가해야 합니다.
<br><br>
예를 들어, {% raw %}`&styliticsoverride=001?styliticsCID=email[clientname]`{% endraw %}과 같습니다.
{% endalert %}

### 2\. 평면 파일 접근 방식
사용자 또는 사용자의 ESP는 플랫 파일에서 항목의 번들 데이터를 참조하여 번들 데이터를 이메일에 채울 수 있습니다. Stylitics는 번들 데이터를 CSV, TXT 또는 XML 형식으로 전개하여 매일 전송할 수 있습니다. 또한 ESP의 요구 사항에 따라 파일 형식을 조정하는 데 도움을 줄 수 있습니다. 이 파일을 생성하는 데 2~3주가 걸립니다.

#### 요구 사항:
- **위치**: Stylitics는 매일 선택할 수 있도록 Stylitics SFTP에서 파일을 삭제하거나 SFTP 자격 증명을 보내 파일을 삭제할 수 있습니다. 
- **시간**: Stylitics는 매일 아침 파일을 삭제합니다. 파일이 필요한 특정 시간이 있으면 이를 알립니다. 
- **파일 키**: 사용자와 Stylitics는 ESP가 데이터를 참조할 수 있도록 파일을 입력할 항목 데이터 문자열에 합의해야 합니다. SKU, `item_group_id`, 또는 `item_number`가 일반적으로 사용됩니다. 

### 3\. 웹사이트 데이터 추출 접근 방식
공급업체는 Stylitics 콘텐츠에 대해 사이트의 프론트 엔드를 스크레이핑하고 이메일에 번들 데이터를 삽입할 수 있습니다. Stylitics의 추가 작업은 필요하지 않습니다. 

## 이메일 템플릿 모범 사례 

사용자와 사용자의 ESP는 Stylitics 데이터 및 번들을 삽입하기 위해 HTML 이메일 템플릿을 생성합니다. 다음은 몇 가지 모범 사례 및 권장 사항입니다. 
- 이메일에서 사용자가 구매하거나 상호 작용한 가장 고가의 항목 또는 첫 번째 정가 항목에 대한 2~4개의 번들을 표시합니다. 
- 여러 `item_numbers` 호출 및 처음 몇 개의 번들 응답 표시 
- 항목에 대해 사용 가능한 번들이 없는 경우 대체 옵션 지원 
	- Stylitics 번들이 존재하는 섹션 숨기기 
	- 사용자가 조회한 다음 항목에 대한 번들 표시 
- 사용자가 명확한 클릭률을 보유함을 보장하기 위해 썸네일 이미지 및 제품 제목의 목록과 번들 이미지 표시

{% alert note %}
이메일은 JavaScript를 지원하지 않으므로 Stylitics 위젯 JavaScript는 이메일에 삽입할 수 없습니다.
{% endalert %}

## 분석

Stylitics는 이 유형의 이메일 프로그램에 대한 번들 데이터를 제공합니다. 따라서 사용자, 사용자의 ESP, Stylitics 간의 데이터 공유를 요청합니다. 가능하다면, 프로그램의 향상과 리프트를 이해하기 위해 다음의 측정기준을 제공해 주시기 바랍니다:
- 전송된 이메일 
- 이메일 열림 
- 조회수 및 참여도 
- 클릭률 
- 가방에 추가 
- 구매

## 다음 단계 

이메일 프로그램의 다음 단계와 일정을 조정하려면 Stylitics 계정 매니저에게 연락하십시오. 다음 단계에는 다음이 포함됩니다: 
- 사용할 이메일 결정
- Stylitics를 ESP와 연결하여 데이터 교환에 대해 논의하고 API 옵션 또는 플랫 파일 옵션 결정 
- ESP와 모의 항목 생성 
- 분석에 맞춰 정렬 
- 출시 일정에 맞춰 정렬 

[0]: {% image_buster /assets/img/stylitics.png %}