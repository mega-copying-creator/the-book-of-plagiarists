# 생성형 AI의 법적 지뢰밭 탐색: 창작자를 위한 저작권 및 상표권 리스크 종합 분석 보고서

_Gemini Deep Research_, _2025-08-31_

AI에 대한 법적인 문제는 아직 완결되지 않은 현재 진행형이므로, 이 보고서 작성 시점 이후에 상황이 크게 변화될 수 있고, 아래의 법적인 조언이 유효하지 않을 수 있습니다.

## Promprt

> 내가 느끼기에 현재 AI서비스를 제공하는 업체의 생각은, 생성형 AI를 통해 만들어진 결과물의 저작권은 프롬프트를 입력한 사람(사용자)에 귀속되는 것으로 생각하는 것 같아. 정확한 스텝이 기억이 나지는 않지만 생성된 텍스트를 복사/붙여넣기 했을 때, 프롬프트를 입력한 내 이름이 같이 붙여넣어진 것을 본 적이 있어.
> 
> 그렇지만 AI가 생성한 결과물은 학습 데이터의 모방이고, 학습에 사용된 원천 데이터에 대한 저작권 문제는 현재 시점에서 그 누구도 명확한 답을 할 수 없는 것으로 알고 있어.
> 
> 생성형 AI의 결과물을 자신의 창작물에 적용했을 때 발생할 수 있는 저작권(또는 상표권)의 문제는 좀 더 사회적 논의를 거치면서 명확해지기를 기다릴 수 밖에 없다고 생각되기는 해. 하지만 AI의 결과물을 사용했을 때 어떤 법적인 문제의 소지가 발생할 수 있는지는 알고 있을 필요가 있어. 이에 내용을 보고서로 정리해줘.

### **Executive Summary**

본 보고서는 생성형 인공지능(AI)을 활용하여 콘텐츠를 제작하는 창작자, 개발자 및 기업이 직면할 수 있는 저작권 및 상표권 관련 법적 문제와 잠재적 책임 소재를 심층적으로 분석한다. 현재 생성형 AI 기술은 창작의 패러다임을 바꾸고 있으나, 그 법적 기반은 여전히 불확실성의 영역에 놓여 있다. AI 서비스 제공업체들은 이용 약관을 통해 생성된 결과물(Output)의 소유권을 사용자에게 귀속시키는 경향을 보이지만, 이는 법률적으로 온전한 저작권 보호를 보장하지 않는다는 점을 명확히 인지해야 한다.

보고서의 핵심 분석 내용은 다음과 같다. 첫째, 현행 저작권법 체계(특히 미국과 대한민국)는 '인간의 창작성'을 저작권 보호의 핵심 요건으로 간주한다. 따라서 인간의 창작적 개입이 미미한, 순수 AI 생성물은 저작권 보호 대상이 아닐 가능성이 매우 높으며, 이는 사실상 공공의 영역(public domain)에 속하게 될 수 있음을 의미한다. 둘째, 생성형 AI 모델의 학습 과정에서 발생하는 대규모 저작물 무단 수집 및 복제는 AI 개발사들이 '공정 이용(fair use)'을 주장하는 핵심 쟁점이다. 그러나 최근 미국 연방대법원의 _'워홀 대 골드스미스'_ 판결은 공정 이용 판단 시 '상업적 목적'과 '원본 시장에 대한 잠식 효과'를 중시하는 방향으로 해석의 무게중심을 이동시켜, AI 개발사들의 법적 리스크를 증대시켰다. 셋째, 사용자는 AI가 학습 데이터를 그대로 출력하는 '결과물 regurgitation' 현상으로 인해 의도치 않게 원저작자의 저작권을 직접 침해할 위험에 노출된다. 또한, AI가 생성한 로고나 브랜드명이 기존 상표와 유사하여 상표권 침해 또는 저명상표의 식별력을 약화시키는 '상표 희석화' 문제를 야기할 수 있다.

이러한 복합적인 리스크에 대응하기 위해 주요 AI 제공업체들은 유료 기업 고객을 대상으로 '저작권 보호 프로그램(Copyright Shield)'과 같은 IP 면책 조항을 도입하고 있다. 하지만 이러한 보호는 사용자가 고의로 침해를 유도하지 않고 제공된 안전장치를 모두 사용했을 때만 적용되는 등 여러 예외 조항과 한계를 내포하고 있어 완전한 안전장치로 보기 어렵다.

결론적으로, 생성형 AI는 강력한 창작 도구이지만 그 결과물의 법적 지위는 매우 불안정하다. 사용자는 AI 서비스 약관상의 '소유권'이 법적인 저작권과 동일하지 않다는 점을 명확히 인식하고, 잠재적 법적 분쟁을 최소화하기 위해 방어적 프롬프트 엔지니어링, 결과물에 대한 권리관계 확인, 인간의 창작적 기여 과정에 대한 철저한 기록 관리 등 다각적인 리스크 완화 전략을 수립하고 실행해야 할 것이다. 본 보고서는 이러한 법적 지형도를 상세히 제시함으로써, 사용자가 보다 정보에 입각한 의사결정을 내릴 수 있도록 지원하는 것을 목표로 한다.

## **Part I: 저자의 문제 – AI 시대의 저작권 소유권**

생성형 AI가 만들어낸 결과물의 저작권이 누구에게 귀속되는지는 현재 가장 근본적이고 첨예한 법적 질문이다. 많은 AI 서비스 제공업체들이 약관을 통해 사용자에게 소유권을 부여한다고 명시하지만, 이는 현행 저작권법의 기본 원칙과 충돌하며 복잡한 법적 딜레마를 야기한다. 이 장에서는 저작권법의 핵심 원칙인 '인간 저작자 요건'을 시작으로, AI를 '도구'로 볼 수 있는지에 대한 규제 기관의 입장과 주요 판례를 분석하고, 마지막으로 서비스 약관이 갖는 법적 의미와 한계를 심층적으로 탐구한다.

### **1.1 저작권법의 초석: 인간 저작자 요건**

#### **핵심 법리**

저작권 보호의 대전제는 저작물이 인간의 사상이나 감정을 창작적으로 표현한 것이어야 한다는 점이다. 이는 특정 국가에 국한되지 않는 보편적인 원칙에 가깝다.

미국 저작권법은 "저작자의 독창적인 저작물(original works of authorship)"을 보호 대상으로 명시하고 있다.1 법원은 이 '저작자(author)'를 인간으로 한정하여 해석해왔으며, 이는 저작권 제도가 인간의 창작 활동을 장려하기 위한 인센티브라는 목적에 근거한다.2 기계나 자동화된 프로세스에 의해 창작적 개입 없이 무작위로 생성된 결과물은 저작권 보호를 받지 못한다는 것이 확립된 법리이다.

대한민국의 저작권법 역시 제2조 1호에서 "저작물"을 "인간의 사상 또는 감정을 표현한 창작물"로 명확히 정의하고 있다.4 이 정의는 저작의 주체를 '인간'으로 명시적으로 한정함으로써, 비인간, 즉 AI가 단독으로 생성한 결과물은 원칙적으로 저작물로 인정받기 어렵다는 점을 시사한다.

#### **비인간 저작자 선례: _나루토 대 슬레이터_ (원숭이 셀카 사건)**

인간 저작자 원칙을 가장 명확하게 보여준 사례는 일명 '원숭이 셀카 사건'으로 알려진 _나루토 대 슬레이터_ 소송이다. 이 사건에서 인도네시아의 검정짧은꼬리원숭이 '나루토'가 사진작가 데이비드 슬레이터의 카메라로 스스로 사진을 찍었고, 동물보호단체 PETA가 나루토를 대신해 저작권 침해 소송을 제기했다. 미국 제9순회항소법원은 최종적으로 동물은 저작권법상 소송을 제기할 법적 자격(statutory standing)이 없다고 판결했다.6 법원은 의회가 동물에게 저작권을 부여하려는 의도가 있었다면 법률에 명시적으로 규정했을 것이라고 판단하며, 저작의 주체를 인간으로 한정하는 전통적인 법 해석을 재확인했다. 이 판례는 AI와 같은 비인간 주체에게 저작권을 인정하는 데 높은 법적 장벽이 존재함을 보여주는 중요한 선례로 작용하고 있다.

### **1.2 AI는 '도구'인가: 규제 기관의 입장**

AI 생성물의 저작권 논쟁의 핵심은 AI를 창작의 주체로 볼 것인가, 아니면 인간이 사용하는 도구로 볼 것인가에 있다. 만약 AI가 카메라나 포토샵과 같은 도구에 불과하다면, 그 결과물은 도구를 사용한 인간의 창작물로 인정받을 수 있다. 그러나 현재 규제 기관은 이러한 비유에 신중한 입장을 취하고 있다.

#### **미국 저작권청(USCO)의 입장**

미국 저작권청(USCO)은 AI와 저작권 문제에 대해 가장 적극적으로 입장을 표명하고 있는 기관이다. USCO는 AI의 도움을 받아 제작된 저작물도 저작권 등록이 가능하다고 인정하지만, 이는 "인간이 저작물의 표현에 대한 창작적 통제권(creative control)을 가졌을 경우"에만 해당한다고 명시했다.1 즉, AI가 단순히 인간의 지시를 기계적으로 수행하는 '보조 도구'의 역할을 넘어, 저작물의 문학적, 예술적, 음악적 표현 요소를 스스로 결정했다면 그 결과물은 인간의 저작물이 아니라는 것이다.12

특히 USCO는 생성형 AI를 카메라에 비유하는 주장을 명확하게 거부한다. 사진작가는 구도, 조명, 피사체 배열 등 다양한 창작적 요소를 직접 통제하지만, 현재 기술 수준에서 프롬프트를 입력하는 사용자는 AI가 최종 결과물을 어떻게 표현할지에 대해 충분한 통제력을 갖지 못한다고 본다. 오히려 USCO는 이러한 사용자를 "예술가에게 일반적인 지시만 내리는 고객"에 비유하며, 실제 창작은 AI 시스템이 수행한다고 판단한다.1

#### **주요 USCO 결정 사례 분석**

USCO의 '창작적 통제권' 기준이 실제 사례에서 어떻게 적용되었는지를 살펴보는 것은 매우 중요하다.

- **_테일러 대 펄머터 (Thaler v. Perlmutter)_**: 스티븐 테일러는 자신이 개발한 AI '창의성 기계(Creativity Machine)'가 "인간의 개입 없이 자율적으로" 생성한 이미지의 저작권 등록을 신청했다. USCO가 이를 거부하자 소송을 제기했으나, 연방 법원은 "인간의 손길이 전혀 없는" 저작물은 보호받을 수 없다며 USCO의 결정을 지지했다.1 이 판결은 AI가 단독 저작자가 될 수 없다는 원칙을 법적으로 확립했다.
    
- **_새벽의 자랴 (Zarya of the Dawn)_**: 크리스 카슈타노바가 인간이 쓴 텍스트와 이미지 생성 AI '미드저니'로 만든 이미지를 결합한 그래픽 노블이다. USCO는 최종적으로 텍스트와 이미지들의 '선택, 조정, 배열'이라는 인간의 창작적 기여는 저작권으로 보호하지만, 미드저니가 생성한 개별 이미지 자체는 저작권 보호 대상이 아니라고 결정했다.14 이는 AI 보조 저작물에 대해 부분적이고 '얇은(thin)' 저작권 개념을 도입한 중요한 사례이다.
    
- **_SURYAST_ 및 _Théâtre D'opéra Spatial_**: 이 사례들은 _자랴_의 선례를 더욱 공고히 했다. _SURYAST_ 사건에서 신청자는 자신이 찍은 사진을 기본 이미지로, 반 고흐의 '별이 빛나는 밤'을 스타일 이미지로 AI에 제공했다. 그러나 USCO는 "이 두 입력을 최종 이미지로 어떻게 결합할지를 결정한 것은 AI"라며 인간의 창작적 통제력이 부족하다고 판단했다.1 콜로라도 주 박람회에서 수상하여 화제가 된
    
    _Théâtre D'opéra Spatial_ 역시, 인간의 기여가 프롬프트 입력과 약간의 후반 수정에 그쳤다는 이유로 저작권 등록이 거부되었다.25
    

#### **프롬프트의 불충분성**

USCO는 현재 기술 수준을 전제로, "프롬프트 입력만으로는 사용자가 AI 시스템 결과물의 저작자가 되기에 충분한 인간적 통제력을 제공하지 않는다"고 명확히 밝혔다.27 프롬프트는 아이디어나 콘셉트를 전달할 뿐, 그것이 구체적인 표현으로 전환되는 과정은 AI가 주도하며 상당한 예측 불가능성을 내포하기 때문이다.16

#### **대한민국의 입장**

대한민국 저작권위원회(KCC) 역시 유사한 가이드라인을 발표했다. 인간의 창작적 기여 없이 순수하게 AI가 생성한 결과물은 저작권 등록 대상이 아니지만, 인간이 창의적으로 수정, 선택, 배열한 부분이 있다면 그 부분에 한해 저작물로 보호받을 수 있다는 입장이다.31 이는 USCO의 접근 방식과 거의 일치한다.

### **1.3 계약 대 법률: AI 서비스 제공업체 이용 약관의 역할**

#### **소유권의 약속**

대부분의 주요 AI 서비스 제공업체는 이용 약관(Terms of Service, ToS)을 통해 사용자가 생성한 결과물의 소유권을 갖는다고 명시한다. 이는 서비스를 이용하는 창작자와 기업들에게 매력적인 조건으로 작용한다.

- **OpenAI**: "OpenAI는 결과물에 대한 모든 권리, 소유권, 이권을 사용자에게 양도합니다." 34
    
- **Midjourney**: "귀하는 관련 법률이 허용하는 최대 범위까지 귀하가 서비스로 생성한 모든 자산(Assets)을 소유합니다." 35
    
- **Google**: "Google은 해당 콘텐츠에 대한 소유권을 주장하지 않습니다." 37
    

#### **저작권의 역설: 계약적 소유권 대 법적 비보호**

AI 서비스 제공업체들의 약관은 사용자에게 '소유권'을 약속하지만, 이는 법적으로 완전한 저작권을 의미하지 않는다는 점에서 중대한 역설이 발생한다. 이 구조를 단계적으로 분석하면 다음과 같다.

1. AI 서비스 제공업체는 이용 약관을 통해 AI가 생성한 결과물에 대한 자신들의 권리를 사용자에게 계약적으로 양도한다.34 이는 상업적 사용자들에게 서비스를 매력적으로 만들기 위한 사업적 결정이다.39
    
2. 그러나 앞서 1.2절에서 확립된 바와 같이, 미국과 한국을 포함한 주요국의 저작권법은 충분한 '인간의 창작적 기여'가 없는 저작물은 저작권 보호를 받을 수 없다고 규정한다.1
    
3. 저작권 보호를 받을 수 없는 저작물은 법적으로 '공공의 영역(public domain)'에 속하게 되며, 이는 누구나 자유롭게 복제하고 사용할 수 있음을 의미한다.13
    
4. 결론적으로, 사용자는 AI 제공업체와의 계약 관계 내에서는 해당 결과물을 '소유'하지만, 제3자에 대해서는 저작권을 주장하여 복제나 무단 이용을 막을 법적 권리가 없을 수 있다. 즉, 약관이 부여하는 '소유권'은 전 세계를 대상으로 효력을 갖는 배타적인 저작권이 아니라, 해당 서비스 제공업체에 대한 계약상의 권리에 불과할 수 있다. 이는 사용자에게 법적 보호에 대한 잘못된 인식을 심어줄 수 있는 매우 중요한 함정이다.
    

#### **권리 재허여 (Grant-Back Licenses)**

더욱이 사용자는 약관을 통해 결과물의 소유권을 부여받는 동시에, 자신의 프롬프트와 생성된 결과물을 AI 제공업체가 서비스 개선, 홍보 등의 목적으로 사용할 수 있도록 광범위하고 영구적인 라이선스를 다시 부여하게 된다.35 이는 사용자가 '소유'한다고 믿는 콘텐츠가 실제로는 AI 회사의 자산 증식에 기여하게 되는 구조임을 의미한다.

## **Part II: 보이지 않는 책임 – AI 학습 데이터에 내재된 저작권 리스크**

생성형 AI의 법적 문제를 이해하기 위해서는 결과물뿐만 아니라 그 근간을 이루는 학습 데이터의 문제를 반드시 짚어야 한다. AI 모델의 성능은 방대한 양의 데이터를 학습함으로써 결정되는데, 이 과정에서 발생하는 대규모 저작권 침해 가능성은 현재 AI 산업 전체를 뒤흔드는 가장 큰 법적 뇌관이다. 이 장에서는 AI 학습의 현실과 이로 인해 촉발된 주요 소송들을 살펴보고, AI 개발사들의 핵심 방어 논리인 '공정 이용'이 최근 법원의 판례 변화로 어떻게 도전을 받고 있는지 심층 분석한다.

### **2.1 생성형 AI의 기반: 대규모 저작권 데이터 학습**

#### **복제의 규모**

생성형 AI 모델, 특히 대규모 언어 모델(LLM)과 이미지 생성 모델은 인터넷에서 수집된 수십억, 수조 개의 데이터 포인트를 기반으로 훈련된다. 이 데이터에는 필연적으로 저작권으로 보호되는 수많은 서적, 기사, 이미지, 소스 코드 등이 포함된다.45 AI 개발사가 이 데이터를 수집하여 자신들의 서버에 저장하고 훈련에 사용하는 과정은 저작권법상 '복제권'을 침해하는 명백한 행위로 간주될 수 있다.1

#### **주요 소송 사례**

이러한 대규모 무단 복제는 창작자들의 강력한 반발을 불러일으켰고, 현재 다수의 중대한 소송이 진행 중이다.

- **_뉴욕 타임스 대 OpenAI & 마이크로소프트_**: 뉴욕 타임스는 자사의 수백만 개 기사가 무단으로 ChatGPT 훈련에 사용되었으며, 그 결과 ChatGPT가 유료 구독자만 볼 수 있는 기사 내용을 요약하거나 거의 그대로 제공함으로써 자사의 비즈니스 모델을 직접적으로 위협한다고 주장한다.46
    
- **_게티이미지 대 스태빌리티 AI_**: 세계적인 스톡 이미지 기업 게티이미지는 이미지 생성 AI인 스테이블 디퓨전이 자사의 사진 1,200만 장 이상을 무단으로 학습했으며, 심지어 생성된 이미지에 게티이미지의 워터마크가 왜곡된 형태로 나타나기도 한다며 소송을 제기했다.53
    
- **작가 및 예술가들의 집단 소송**: 코미디언 사라 실버맨을 비롯한 다수의 작가와 예술가들이 자신들의 저작물이 동의나 보상 없이 AI 훈련에 사용되었다며 집단 소송을 제기했다.60
    

### **2.2 공정 이용 방어: 논쟁의 여지가 있는 법적 방패**

#### **네 가지 판단 기준**

이러한 소송에 맞서 AI 개발사들이 내세우는 가장 강력한 법적 방어 논리는 미국 저작권법상의 '공정 이용(fair use)'이다. 공정 이용은 특정 조건 하에서 저작권자의 허락 없이도 저작물을 사용할 수 있도록 허용하는 예외 규정으로, 법원은 다음 네 가지 요소를 종합적으로 고려하여 판단한다: (1) 이용의 목적과 성격, (2) 저작물의 성격, (3) 이용된 부분의 양과 중요성, (4) 이용이 원저작물의 잠재적 시장이나 가치에 미치는 영향.1

#### **'변형적 이용' 주장과 _구글 북스_ 선례**

AI 개발사들은 특히 첫 번째 요소인 '이용의 목적과 성격'에서 자신들의 행위가 '변형적 이용(transformative use)'에 해당한다고 주장한다. 이들의 주장은 _작가 조합 대 구글_ (일명 '구글 북스' 사건) 판결에 상당 부분 기대고 있다. 해당 사건에서 법원은 구글이 도서관의 책들을 디지털로 스캔하여 검색 가능한 데이터베이스를 구축한 행위가, 원본 도서의 시장을 대체하는 것이 아니라 정보 검색이라는 새로운 목적을 가진 '변형적 이용'에 해당하므로 공정 이용이라고 판결했다.64 AI 개발사들 역시 저작물을 그대로 보여주는 것이 아니라, 통계적 패턴을 추출하여 AI 모델이라는 새로운 도구를 만드는 것이므로 변형적 이용이라고 주장한다.47

### **2.3 _워홀 대 골드스미스_ 판례: 공정 이용의 새로운 렌즈**

#### **연방대법원의 입장 변화**

그러나 2023년 미국 연방대법원의 _앤디 워홀 재단 대 골드스미스_ 판결은 공정 이용 분석의 흐름을 바꾸는 중요한 전환점이 되었다. 이 사건에서 법원은 앤디 워홀이 사진작가 린 골드스미스가 촬영한 가수 프린스의 사진을 기반으로 만든 실크스크린 작품을 잡지사에 라이선스한 행위가 공정 이용에 해당하지 않는다고 판결했다. 법원은 워홀의 작품이 새로운 미학적 의미를 추가했더라도, 그 상업적 '이용 목적'(잡지 기사의 초상화로 사용)이 원본 사진의 이용 목적과 실질적으로 동일하여 원본의 라이선스 시장을 잠식했다고 판단했다.71

#### **_워홀_ 판례가 AI 공정 이용 주장을 약화시키는 논리**

_워홀_ 판결은 AI 개발사들의 공정 이용 주장에 상당한 타격을 줄 수 있다. 그 논리적 흐름은 다음과 같다.

1. _워홀_ 이전의 AI 훈련에 대한 공정 이용 주장은 _구글 북스_ 판례에 기대어, AI 모델 자체가 원본 저작물과는 다른 목적을 가진 '변형적' 기술이라는 점에 초점을 맞추었다.
    
2. _워홀_ 판결은 분석의 초점을 추상적인 기술의 '변형성'에서 해당 기술의 구체적인 '이용'과 그 '상업적 목적'으로 이동시켰다. 핵심 질문은 "2차적 이용이 원본과 동일하거나 매우 유사한 목적을 공유하며, 상업적 성격을 띠는가?"가 되었다.72
    
3. 생성형 AI는 훈련에 사용된 저작물과 동일한 시장에서 직접 경쟁하는 결과물을 생성하는 데 사용된다. 예를 들어, 뉴스 기사로 훈련된 AI는 뉴스 요약을 생성하여 원본 기사의 시장을 잠식하고 50, 스톡 사진으로 훈련된 AI는 스톡 사진을 생성하여 원본 시장을 대체한다.53
    
4. 따라서 _워홀_의 프레임워크 하에서 볼 때, AI의 이용은 원본 저작물의 시장을 직접적으로 대체하려는 상업적 목적이 뚜렷하므로 공정 이용으로 인정받기 매우 어려워졌다. 이는 AI 개발사뿐만 아니라, 그 결과물을 사용하는 사용자에게까지 이어지는 법적 리스크의 근원이 된다.
    

### **2.4 유럽의 프레임워크: 텍스트 및 데이터 마이닝(TDM) 예외 조항**

#### **CDSM 지침 제4조**

유럽연합(EU)은 미국과 다른 접근 방식을 취한다. 2019년 제정된 '디지털 단일 시장 저작권 지침(CDSM Directive)'은 텍스트 및 데이터 마이닝(TDM)에 대한 명시적인 예외 조항을 두고 있다. 특히 제4조는 상업적 목적을 포함한 일반적인 TDM을 허용하되, 저작권자가 `robots.txt` 파일과 같은 기계가 읽을 수 있는 방식으로 자신의 권리를 "명시적으로 유보(opt-out)"한 경우에는 예외가 적용되지 않도록 규정한다.79

#### **법적 불확실성**

그러나 이 조항이 강력한 생성형 AI의 등장 이전에 설계되었다는 점에서, 대규모 상업적 AI 모델 훈련에 그대로 적용될 수 있는지에 대한 법적 불확실성이 크다.83 EU AI법은 일반목적 AI(GPAI) 제공업체에게 이 옵트아웃 규정을 준수하고 훈련 데이터에 대한 요약 정보를 공개할 의무를 부과하고 있지만, TDM의 정확한 범위와 옵트아웃의 실효성에 대한 논쟁은 계속되고 있다.79

## **Part III: 사용자 대상 리스크 – AI 결과물로 인한 직접적 침해**

AI 기술의 법적 문제는 모델 훈련 단계에만 국한되지 않는다. 사용자가 AI로부터 결과물을 받아 자신의 창작물에 활용하는 순간, 새로운 차원의 직접적인 법적 책임이 발생할 수 있다. 이 장에서는 사용자가 직면할 수 있는 가장 즉각적인 위협인 저작권 침해와 상표권 침해 리스크를 기술적 원인과 법적 논리를 결합하여 상세히 분석한다.

### **3.1 저작권 침해 리스크**

#### **Regurgitation과 Memorization: AI의 기억이 사용자의 책임이 될 때**

사용자에게 가장 직접적인 저작권 침해 위험은 AI 모델이 학습 데이터를 거의 그대로 '토해내는(regurgitate)' 현상에서 비롯된다.

- **기술적 원인**: 이 현상은 AI의 창의적 활동이 아니라 기술적 결함에 가깝다. 주된 원인은 '과적합(overfitting)'으로, 모델이 데이터의 일반적인 패턴을 학습하는 대신 특정 데이터 포인트를 과도하게 암기하는 현상이다. 이는 특정 데이터가 훈련 데이터셋에 반복적으로 포함될 때 발생하기 쉽다.86 모델이 특정 구절이나 이미지를 너무 많이 학습하면, 해당 내용을 새로운 창작의 재료가 아닌 암기된 정답으로 인식하고 그대로 출력하게 된다.
    
- **법적 결과**: 사용자가 이러한 결과물을 인지하지 못하고 자신의 블로그, 광고, 제품 등에 사용할 경우, 원저작물의 저작권을 직접 침해한 것으로 간주되어 법적 책임을 지게 된다. _뉴욕 타임스_ 소송에서 원고 측은 ChatGPT가 최소한의 프롬프트만으로도 자사 기사의 전체 단락을 거의 똑같이 복제해냈다는 구체적인 증거를 제시하며 이 위험성을 부각시켰다.46
    

#### **2차적 저작물**

결과물이 학습 데이터와 완전히 동일하지 않더라도, 원본 저작물의 창작적 표현과 '실질적으로 유사(substantially similar)'하다면 2차적 저작물 무단 작성에 해당하여 저작권을 침해할 수 있다. AI는 수많은 저작물의 스타일과 요소를 조합하여 결과물을 생성하므로, 특정 저작물(들)과 법적으로 문제가 될 정도의 유사성을 가진 결과물이 생성될 가능성은 항상 존재한다.

### **3.2 상표권 침해 및 희석화 리스크**

저작권만큼이나 중요한 또 다른 법적 위험은 상표권과 관련된다. AI는 브랜드 로고, 제품 디자인, 슬로건 등 상표로 보호되는 요소들도 학습 데이터로 흡수하기 때문에, 이와 관련된 다양한 문제를 야기할 수 있다.

#### **혼동 가능성 (상표권 침해)**

상표권 침해의 핵심은 소비자가 상품이나 서비스의 출처에 대해 혼동을 일으킬 가능성이 있는지 여부이다. 사용자가 AI를 이용해 로고나 브랜드명을 생성하고 이를 상업적으로 사용할 경우, 해당 결과물이 기존에 등록된 상표와 유사하다면 상표권 침해에 해당할 수 있다.93

_게티이미지 대 스태빌리티 AI_ 소송에서는 스테이블 디퓨전이 생성한 이미지에 게티이미지의 워터마크가 변형된 형태로 포함되어 출처에 대한 혼동을 야기한다는 주장이 제기되었다.53

#### **저명상표의 희석화**

저명상표의 경우, 혼동 가능성이 없더라도 상표의 가치가 손상될 위험이 있다. 이를 '희석화(dilution)'라고 하며, 주로 두 가지 형태로 나타난다.

- **희석화 (Tarnishment)**: 저명상표가 저품질의, 비윤리적이거나 불쾌한 콘텐츠와 연관되어 브랜드의 명성이 손상되는 경우이다. _뉴욕 타임스_ 소송은 이 문제를 정면으로 다룬다. 소장에 따르면, AI 챗봇이 "흡연이 천식을 치료할 수 있다는 덴버 포스트의 연구 결과"와 같은 명백한 허위 정보(hallucination)를 생성하면서 뉴욕 타임스를 출처로 인용하는 경우가 있었는데, 이는 뉴욕 타임스라는 브랜드가 가진 신뢰성과 명성을 훼손하는 행위라고 주장한다.26
    
- **희석화 (Blurring)**: 저명상표가 관련 없는 다양한 상품이나 서비스에 무분별하게 사용되어 고유의 식별력이 약화되는 경우이다. AI가 특정 브랜드의 로고나 스타일을 포함한 이미지를 무한정 생성할 수 있게 되면서, 해당 브랜드가 가진 고유한 이미지가 희미해지고 평범해질 위험이 있다.97
    

이처럼 사용자는 AI 결과물을 활용하는 과정에서 저작권뿐만 아니라 상표권과 관련된 복잡한 법적 문제에 직면할 수 있으며, 이는 특히 상업적 목적으로 콘텐츠를 제작할 때 심각한 법적, 재정적 위험으로 이어질 수 있다.

## **Part IV: 리스크 완화 프레임워크 – 계약적 및 실무적 안전장치**

생성형 AI를 둘러싼 복잡하고 진화하는 법적 환경 속에서, 사용자는 잠재적 책임을 최소화하기 위한 다각적인 전략을 모색해야 한다. AI 서비스 제공업체들이 내놓는 계약적 보호 장치인 '저작권 보호 프로그램'의 실효성을 정확히 이해하는 동시에, 사용자 스스로가 창작 과정에서 법적 리스크를 줄일 수 있는 실무적 방안을 적극적으로 도입하는 것이 중요하다. 이 장에서는 제공업체 측의 보호 장치와 사용자 측의 방어 전략을 나누어 심층적으로 분석한다.

### **4.1 제공업체 측 보호 장치: '저작권 보호 프로그램'의 부상**

#### **IP 면책 정책**

AI 생성물의 저작권 침해에 대한 기업 고객들의 우려가 커지자, 주요 AI 제공업체들은 자사 서비스를 사용한 결과물로 인해 발생하는 특정 저작권 소송으로부터 사용자를 보호하겠다는 IP 면책(indemnification) 정책을 경쟁적으로 도입하고 있다.99 이는 사용자가 제3자로부터 저작권 침해 소송을 당할 경우, AI 제공업체가 소송 비용을 방어하고 최종 판결이나 합의로 발생하는 손해배상액을 대신 지불하겠다는 계약상의 약속이다.

#### **제공업체 면책 조항의 한계와 사용자에게 전가되는 리스크**

AI 제공업체들이 제공하는 IP 면책 조항은 기업 사용자의 불안감을 완화하는 중요한 장치이지만, 결코 모든 위험을 제거하는 '만능 방패'는 아니다. 이들 정책의 이면에는 사용자가 반드시 인지해야 할 중대한 한계와 예외 조항이 존재한다.

1. 기업 고객들은 AI 사용에 따른 법적 리스크를 우려하며, 이는 AI 서비스 도입의 주요 장벽으로 작용한다. 이에 따라 잠재 고객을 확보하고 시장 경쟁력을 높이기 위해 Microsoft, Google, Adobe, OpenAI와 같은 주요 제공업체들은 '저작권 보호 프로그램(Copyright Shield)' 또는 유사한 IP 면책 프로그램을 도입했다.101
    
2. 그러나 이 면책 조항들은 무조건적인 보호를 제공하지 않는다. 약관을 자세히 살펴보면 공통적으로 중요한 예외 조항들이 포함되어 있다. 예를 들어, OpenAI의 면책은 사용자가 "결과물이 침해적이거나 침해할 가능성이 있다는 것을 알았거나 알았어야 하는 경우" 또는 제공된 안전 필터링 기능을 사용하지 않은 경우에는 적용되지 않는다.108 Microsoft 역시 고객이 내장된 "가드레일과 콘텐츠 필터"를 사용해야만 보호를 제공한다고 명시하고 있다.103
    
3. 이러한 예외 조항들은 상당한 수준의 주의 의무와 입증 책임을 사용자에게 전가한다. 만약 소송이 발생했을 때, AI 제공업체는 사용자가 특정 결과물이 침해 소지가 있다는 점을 '알았어야 했다'고 주장하거나, 안전 기능을 제대로 활용하지 않았다고 주장하며 면책 의무를 회피할 수 있다.
    
4. 결과적으로, 이 면책 조항은 법적 분쟁의 성격을 변화시킨다. 사용자는 이제 제3자 저작권자와의 분쟁뿐만 아니라, 면책 적용 여부를 두고 자신이 계약한 AI 제공업체와 다툴 가능성까지 대비해야 한다. 따라서 이 '보호 프로그램'은 리스크를 완전히 제거하는 장치가 아니라, 일부 리스크를 완화하고 분쟁의 당사자를 바꿀 수 있는 계약적 도구로 이해해야 한다.
    

#### **표 1: 주요 생성형 AI 제공업체 IP 면책 정책 비교 분석**

|제공업체|보호 프로그램 명칭|적용 대상 서비스|보호 대상|주요 예외 및 조건|책임 한도|
|---|---|---|---|---|---|
|**OpenAI**|Copyright Shield|ChatGPT Enterprise, API|저작권 침해|- 사용자가 침해 사실을 알았거나 알았어야 하는 경우<br><br>- 안전 필터링 기능을 비활성화/무시한 경우<br><br>- 결과물을 수정한 경우<br><br>- 상표권 침해는 제외 108|지난 12개월간 지불한 요금 109|
|**Microsoft**|Customer Copyright Commitment|상용 Copilot 서비스, Azure OpenAI Service|저작권, 특허, 상표 등|- 고의로 침해물을 생성하려 한 경우<br><br>- 제공된 안전장치 및 콘텐츠 필터를 사용하지 않은 경우<br><br>- 허가되지 않은 데이터를 입력한 경우 103|명시되지 않음 (계약에 따름)|
|**Google**|Generative AI Indemnity|Duet AI in Workspace, Vertex AI 등|저작권 침해 (학습 데이터 및 생성물)|- 고의로 침해물을 생성하거나 사용한 경우<br><br>- 출처 인용 도구를 사용하지 않는 등 책임 있는 AI 관행을 따르지 않은 경우 102|계약에 명시된 일반 책임 한도|
|**Adobe**|Firefly IP Indemnification|특정 기업용 플랜의 Firefly 기능|저작권, 특허, 상표, 퍼블리시티권 등|- 베타 기능으로 생성된 결과물<br><br>- 사용자가 추가한 콘텐츠(예: 텍스트 효과를 적용한 글자 모양 자체)<br><br>- 약관을 위반하여 사용한 경우 106|계약에 따름|

### **4.2 책임 있는 창작을 위한 사용자 측 전략**

AI 제공업체의 보호 장치가 불완전한 만큼, 사용자는 스스로 법적 리스크를 관리하고 최소화하기 위한 적극적인 노력을 기울여야 한다.

#### **방어적 프롬프트 엔지니어링**

결과물 생성 단계에서부터 법적 분쟁의 소지를 줄이는 프롬프트 작성 기법을 활용하는 것이 중요하다.

- 특정 작가나 예술가의 이름, 캐릭터명, 상표명 등 저작권이나 상표권으로 보호되는 고유명사를 프롬프트에 직접적으로 사용하는 것을 피해야 한다. "반 고흐 스타일로 그려줘"와 같은 프롬프트는 의도적인 모방으로 해석될 수 있다.113
    
- 대신, 추상적인 화풍, 색감, 구도, 분위기 등을 묘사하는 방식으로 원하는 스타일을 유도하는 것이 안전하다. 예를 들어, "거칠고 두꺼운 붓 터치와 소용돌이치는 듯한 역동적인 하늘을 표현해줘"와 같이 구체적인 표현 방식을 지시하는 것이 좋다.115
    
- "독창적인 이미지를 생성해줘", "기존의 캐릭터나 로고를 사용하지 마"와 같은 부정적 지시어(negative prompt)나 명시적 제약 조건을 프롬프트에 포함시켜 AI가 저작권 침해 가능성이 있는 결과물을 생성할 확률을 낮출 수 있다.113
    

#### **결과물에 대한 실사(Due Diligence)**

AI가 생성한 결과물을 그대로 사용하는 것은 위험하다. 사용 전, 해당 결과물이 기존 저작물과 유사하지 않은지 최소한의 검증 절차를 거쳐야 한다.

- **역 이미지 검색**: 구글 이미지 검색, TinEye, Reversely.ai와 같은 도구를 사용하여 AI가 생성한 이미지가 웹상에 존재하는 다른 이미지와 유사한지 확인할 수 있다.119
    
- **표절 및 AI 검사기**: 텍스트 결과물의 경우, 표절 검사 도구나 AI 콘텐츠 탐지기를 활용할 수 있다. 하지만 이러한 도구들은 정교하게 생성된 AI 텍스트를 완벽하게 탐지하지 못하거나, 반대로 인간이 작성한 글을 AI 생성물로 오인하는(false positive) 경우가 있어 한계가 명확하다.127
    
- **한계점 인지**: 이러한 검증 도구들은 완전하지 않으며, 특히 개념적 유사성이나 법적 '실질적 유사성'을 판단해주지는 못한다는 점을 명확히 인지해야 한다. 이들은 최소한의 위험 점검 수단일 뿐, 법적 안전을 보장하지는 않는다.132
    

#### **인간의 창작성 기록**

AI 보조 저작물에 대한 저작권을 주장하기 위해서는 인간의 창작적 기여를 입증할 수 있는 증거를 확보하는 것이 매우 중요하다.

- 단순한 프롬프트 입력에서 그치지 않고, 수많은 프롬프트 수정을 통해 원하는 결과물을 얻어내는 과정, 생성된 여러 결과물 중에서 특정 결과물을 선택하고 배열하는 과정, 그리고 포토샵이나 기타 편집 도구를 사용하여 결과물을 상당 부분 수정하고 다른 요소와 결합하는 모든 과정을 상세히 기록으로 남겨야 한다.118 이러한 기록은 향후 저작권 등록 신청이나 법적 분쟁 시, USCO가 요구하는 '인간의 창작적 통제력'을 입증하는 핵심적인 증거 자료가 될 수 있다. 이는
    
    _새벽의 자랴_ 사건에서 저작권청이 개별 이미지의 저작권은 불인정했지만 텍스트와 이미지의 '선택과 배열'에 대한 저작권은 인정한 논리와 일맥상통한다.
    

## **결론: 진화하는 법적 지형도 속에서의 항해**

생성형 AI 기술은 창작의 가능성을 무한히 확장시키고 있지만, 그 법적 토대는 여전히 유동적이고 불확실하다. 본 보고서에서 심층적으로 분석한 바와 같이, 사용자는 AI 서비스 제공업체가 약관을 통해 '소유권'을 부여한다는 점에 안심해서는 안 된다. 계약상의 소유권과 법적으로 보호받고 집행할 수 있는 배타적 저작권 사이에는 명백한 간극이 존재하기 때문이다.

현재 법적 지형도의 핵심은 다음과 같이 요약될 수 있다. 첫째, '인간 저작자' 원칙은 여전히 저작권법의 확고한 기둥이다. 순수 AI 생성물은 저작권 보호를 받지 못하고 공공의 영역에 속할 가능성이 높으며, 저작권을 인정받기 위해서는 인간의 실질적이고 창조적인 개입을 입증해야만 한다. 둘째, AI 모델 훈련의 근간이 되는 데이터 수집 행위는 '공정 이용'이라는 방패 뒤에 숨어 있지만, _워홀_ 판결 이후 그 방패에는 균열이 생기기 시작했다. 법원이 AI 결과물의 상업적 목적과 원본 시장 잠식 효과를 중시할수록, AI 개발사와 사용자의 법적 리스크는 커질 수밖에 없다. 마지막으로, 사용자는 AI의 기술적 한계로 인한 '결과물 regurgitation'과 의도치 않은 상표권 침해 및 희석화 문제로 인해 직접적인 법적 책임의 당사자가 될 위험을 안고 있다.

AI 제공업체들이 내놓은 '저작권 보호 프로그램'은 이러한 위험을 일부 완화해주지만, 수많은 예외 조항으로 인해 완전한 해결책이 될 수는 없다. 결국, 현재로서는 AI를 창작 과정의 파트너로 활용하는 사용자 스스로가 법적 위험을 인지하고 관리하는 '책임 있는 창작자'가 되어야 한다. 이는 방어적 프롬프트 엔지니어링 기법을 습득하고, 생성된 결과물에 대한 최소한의 권리관계 확인을 습관화하며, 자신의 창작적 기여 과정을 꼼꼼히 기록하는 실천적인 노력을 통해 가능하다.

앞으로 _뉴욕 타임스 대 OpenAI_와 같은 중대한 소송의 결과, 미국 저작권청과 각국 규제 기관의 추가적인 가이드라인 발표, 그리고 AI 기술 자체의 발전이 이 법적 지형도를 계속해서 바꾸어 나갈 것이다. 따라서 창작자들은 이러한 변화에 지속적으로 주의를 기울이며, 기술이 제공하는 무한한 가능성을 법적 테두리 안에서 안전하게 탐색하는 지혜를 발휘해야 할 것이다.


## 참고 문헌

1. Generative Artificial Intelligence and Copyright Law - Congress.gov, 8월 31, 2025에 액세스, [https://www.congress.gov/crs-product/LSB10922](https://www.congress.gov/crs-product/LSB10922)
    
2. Appellate Court Affirms Human Authorship Requirement for Copyrighting AI-Generated Works | Insights | Skadden, Arps, Slate, Meagher & Flom LLP, 8월 31, 2025에 액세스, [https://www.skadden.com/insights/publications/2025/03/appellate-court-affirms-human-authorship](https://www.skadden.com/insights/publications/2025/03/appellate-court-affirms-human-authorship)
    
3. Copyright and Artificial Intelligence, Part 2 Copyrightability Report - U.S. Copyright Office, 8월 31, 2025에 액세스, [https://www.copyright.gov/ai/Copyright-and-Artificial-Intelligence-Part-2-Copyrightability-Report.pdf](https://www.copyright.gov/ai/Copyright-and-Artificial-Intelligence-Part-2-Copyrightability-Report.pdf)
    
4. COPYRIGHT ACT, 8월 31, 2025에 액세스, [https://elaw.klri.re.kr/eng_service/lawView.do?lang=ENG&hseq=32626](https://elaw.klri.re.kr/eng_service/lawView.do?lang=ENG&hseq=32626)
    
5. Copyright and AI – the Korean View - Dentons, 8월 31, 2025에 액세스, [https://www.dentons.com/en/insights/articles/2022/april/11/copyright-and-ai-the-korean-view](https://www.dentons.com/en/insights/articles/2022/april/11/copyright-and-ai-the-korean-view)
    
6. Naruto v. Slater, No. 16-15469 (9th Cir. 2018) - Justia Law, 8월 31, 2025에 액세스, [https://law.justia.com/cases/federal/appellate-courts/ca9/16-15469/16-15469-2018-04-23.html](https://law.justia.com/cases/federal/appellate-courts/ca9/16-15469/16-15469-2018-04-23.html)
    
7. Naruto v. Slater | Loeb & Loeb LLP, 8월 31, 2025에 액세스, [https://www.loeb.com/en/insights/publications/2016/02/naruto-v-slater](https://www.loeb.com/en/insights/publications/2016/02/naruto-v-slater)
    
8. En Banc Review Requested in “Monkey Selfie” Copyright Case, 8월 31, 2025에 액세스, [https://aldf.org/article/en-banc-review-requested-in-monkey-selfie-copyright-case/](https://aldf.org/article/en-banc-review-requested-in-monkey-selfie-copyright-case/)
    
9. Naruto v. Slater: One Small Step for a Monkey, One Giant Lawsuit for Animal-Kind, 8월 31, 2025에 액세스, [https://www.wakeforestlawreview.com/2020/02/naruto-v-slater-one-small-step-for-a-monkey-one-giant-lawsuit-for-animal-kind/](https://www.wakeforestlawreview.com/2020/02/naruto-v-slater-one-small-step-for-a-monkey-one-giant-lawsuit-for-animal-kind/)
    
10. Naruto v. Slater | Loeb & Loeb LLP, 8월 31, 2025에 액세스, [https://www.loeb.com/en/insights/publications/2018/04/naruto-v-slater](https://www.loeb.com/en/insights/publications/2018/04/naruto-v-slater)
    
11. The U.S. Copyright Office's Position on the Copyrightability of Works Made with the Assistance of Generative AI (Part Two) | Sterne Kessler, 8월 31, 2025에 액세스, [https://www.sternekessler.com/news-insights/insights/the-u-s-copyright-offices-position-on-the-copyrightability-of-works-made-with-the-assistance-of-generative-ai-part-two/](https://www.sternekessler.com/news-insights/insights/the-u-s-copyright-offices-position-on-the-copyrightability-of-works-made-with-the-assistance-of-generative-ai-part-two/)
    
12. Copyright Registration Guidance: Works Containing Material Generated by Artificial Intelligence, 8월 31, 2025에 액세스, [https://www.copyright.gov/ai/ai_policy_guidance.pdf](https://www.copyright.gov/ai/ai_policy_guidance.pdf)
    
13. Is AI-Generated Output Protected by Copyright? - Copyright Alliance, 8월 31, 2025에 액세스, [https://copyrightalliance.org/faqs/is-ai-generated-protected-by-copyright/](https://copyrightalliance.org/faqs/is-ai-generated-protected-by-copyright/)
    
14. Zarya of the Dawn: How AI is Changing the Landscape of Copyright Protection, 8월 31, 2025에 액세스, [https://jolt.law.harvard.edu/digest/zarya-of-the-dawn-how-ai-is-changing-the-landscape-of-copyright-protection](https://jolt.law.harvard.edu/digest/zarya-of-the-dawn-how-ai-is-changing-the-landscape-of-copyright-protection)
    
15. 2023.02.21 Zarya of the Dawn Letter - U.S. Copyright Office, 8월 31, 2025에 액세스, [https://www.copyright.gov/docs/zarya-of-the-dawn.pdf](https://www.copyright.gov/docs/zarya-of-the-dawn.pdf)
    
16. US Copyright Office Grants Limited Registration for AI-Generated Graphic Novel - Cooley, 8월 31, 2025에 액세스, [https://www.cooley.com/news/insight/2023/2023-02-28-us-copyright-office-grants-limited-registration-for-ai-generated-graphic-novel](https://www.cooley.com/news/insight/2023/2023-02-28-us-copyright-office-grants-limited-registration-for-ai-generated-graphic-novel)
    
17. Sorry HAL, You Cannot Be an Author: How Much AI Is Too Much? - New York State Bar Association, 8월 31, 2025에 액세스, [https://nysba.org/sorry-hal-you-cannot-be-an-author-how-much-ai-is-too-much/](https://nysba.org/sorry-hal-you-cannot-be-an-author-how-much-ai-is-too-much/)
    
18. Zarya of the Dawn: US Copyright Office Affirms Limits on Copyright of AI Outputs, 8월 31, 2025에 액세스, [https://creativecommons.org/2023/02/27/zarya-of-the-dawn-us-copyright-office-affirms-limits-on-copyright-of-ai-outputs/](https://creativecommons.org/2023/02/27/zarya-of-the-dawn-us-copyright-office-affirms-limits-on-copyright-of-ai-outputs/)
    
19. U.S Copyright Office affirms copyright of AI-assisted comic book Zarya of the Dawn : r/StableDiffusion - Reddit, 8월 31, 2025에 액세스, [https://www.reddit.com/r/StableDiffusion/comments/1196wl6/us_copyright_office_affirms_copyright_of/](https://www.reddit.com/r/StableDiffusion/comments/1196wl6/us_copyright_office_affirms_copyright_of/)
    
20. Copyright Office Rejects Another Bid to Register Artwork “Co-Authored” by AI, 8월 31, 2025에 액세스, [https://www.intellectualproperty.law/2023/12/copyright-office-rejects-another-bid-to-register-artwork-co-authored-by-ai/](https://www.intellectualproperty.law/2023/12/copyright-office-rejects-another-bid-to-register-artwork-co-authored-by-ai/)
    
21. Registration of “SURYAST” - Knowing Machines, 8월 31, 2025에 액세스, [https://knowingmachines.org/knowing-legal-machines/legal-explainer/cases/registration-of-suryast](https://knowingmachines.org/knowing-legal-machines/legal-explainer/cases/registration-of-suryast)
    
22. AI-Generated Copyright Registration: The Case of”Suryast” - Soundmark Law Firm, 8월 31, 2025에 액세스, [https://soundmarklaw.com/ai-generated-copyright-registration-the-case-ofsuryast/](https://soundmarklaw.com/ai-generated-copyright-registration-the-case-ofsuryast/)
    
23. AI Artistry on Trial: Can Machines Hold Copyright? | Lenczner Slaght, 8월 31, 2025에 액세스, [https://litigate.com/ai-artistry-on-trial-can-machines-hold-copyright/pdf](https://litigate.com/ai-artistry-on-trial-can-machines-hold-copyright/pdf)
    
24. Copyrightability of works created using generative AI: Will Canada align with the US?, 8월 31, 2025에 액세스, [https://www.dentons.com/en/insights/newsletters/2025/february/13/dentons-intellectual-property-hub/copyrightability-of-works-created-using-generative-ai](https://www.dentons.com/en/insights/newsletters/2025/february/13/dentons-intellectual-property-hub/copyrightability-of-works-created-using-generative-ai)
    
25. Tragic Ending: Award-Winning AI Artwork Refused Copyright Registration - IP Update, 8월 31, 2025에 액세스, [https://www.ipupdate.com/2023/09/tragic-ending-award-winning-ai-artwork-refused-copyright-registration/](https://www.ipupdate.com/2023/09/tragic-ending-award-winning-ai-artwork-refused-copyright-registration/)
    
26. AI Copyright & Human Authorship: The Legal Battle Over Theatre D'opéra Spatial, 8월 31, 2025에 액세스, [https://naiknaik.com/2024/10/16/ai-copyright-human-authorship-the-legal-battle-over-theatre-dopera-spatial/](https://naiknaik.com/2024/10/16/ai-copyright-human-authorship-the-legal-battle-over-theatre-dopera-spatial/)
    
27. Copyright Office Releases Part 2 of Artificial Intelligence Report, 8월 31, 2025에 액세스, [https://www.copyright.gov/newsnet/2025/1060.html](https://www.copyright.gov/newsnet/2025/1060.html)
    
28. Generative AI in Focus: Copyright Office's Latest Report - Wiley Rein LLP, 8월 31, 2025에 액세스, [https://www.wiley.law/alert-Generative-AI-in-Focus-Copyright-Offices-Latest-Report](https://www.wiley.law/alert-Generative-AI-in-Focus-Copyright-Offices-Latest-Report)
    
29. Copyright Office Publishes Report on Copyrightability of AI-Generated Materials | Insights, 8월 31, 2025에 액세스, [https://www.skadden.com/insights/publications/2025/02/copyright-office-publishes-report](https://www.skadden.com/insights/publications/2025/02/copyright-office-publishes-report)
    
30. Copyrightability and Artificial Intelligence: A new report from the U.S. Copyright Office, 8월 31, 2025에 액세스, [https://www.authorsalliance.org/2025/02/20/copyrightability-and-artificial-intelligence-a-new-report-from-the-u-s-copyright-office/](https://www.authorsalliance.org/2025/02/20/copyrightability-and-artificial-intelligence-a-new-report-from-the-u-s-copyright-office/)
    
31. South Korean Copyright Office Issues AI Guidance, Nick Palmieri - Our Take, 8월 31, 2025에 액세스, [https://ourtake.bakerbotts.com/post/102kyht/south-korean-copyright-office-issues-ai-guidance](https://ourtake.bakerbotts.com/post/102kyht/south-korean-copyright-office-issues-ai-guidance)
    
32. South Korea Denies Copyright Registration to AI-Generated Content, 8월 31, 2025에 액세스, [https://www.ciplawyer.com/articles/152426.html](https://www.ciplawyer.com/articles/152426.html)
    
33. South Korea's largest music copyright collective just banned registration of songs created with AI - Music Business Worldwide, 8월 31, 2025에 액세스, [https://www.musicbusinessworldwide.com/south-koreas-largest-music-copyright-collective-just-banned-registration-of-songs-created-with-ai/](https://www.musicbusinessworldwide.com/south-koreas-largest-music-copyright-collective-just-banned-registration-of-songs-created-with-ai/)
    
34. Who owns the copyright? : r/OpenAI - Reddit, 8월 31, 2025에 액세스, [https://www.reddit.com/r/OpenAI/comments/122ui2g/who_owns_the_copyright/](https://www.reddit.com/r/OpenAI/comments/122ui2g/who_owns_the_copyright/)
    
35. Terms of Service - Midjourney, 8월 31, 2025에 액세스, [https://docs.midjourney.com/hc/en-us/articles/32083055291277-Terms-of-Service](https://docs.midjourney.com/hc/en-us/articles/32083055291277-Terms-of-Service)
    
36. Legal reprecussions for using Midjourney commercially - Reddit, 8월 31, 2025에 액세스, [https://www.reddit.com/r/midjourney/comments/13bfna7/legal_reprecussions_for_using_midjourney/](https://www.reddit.com/r/midjourney/comments/13bfna7/legal_reprecussions_for_using_midjourney/)
    
37. Gemini API Additional Terms of Service | Google AI for Developers, 8월 31, 2025에 액세스, [https://ai.google.dev/gemini-api/terms](https://ai.google.dev/gemini-api/terms)
    
38. EU terms of use - OpenAI, 8월 31, 2025에 액세스, [https://openai.com/policies/eu-terms-of-use/](https://openai.com/policies/eu-terms-of-use/)
    
39. ChatGPT: what the law says about who owns the copyright of AI-generated content | University of Portsmouth, 8월 31, 2025에 액세스, [https://www.port.ac.uk/news-events-and-blogs/blogs/security-and-risk/chatgpt-what-the-law-says-about-who-owns-the-copyright-of-ai-generated-content](https://www.port.ac.uk/news-events-and-blogs/blogs/security-and-risk/chatgpt-what-the-law-says-about-who-owns-the-copyright-of-ai-generated-content)
    
40. Generative AI: How it works, content ownership, and copyrights | Inside Tech Law, 8월 31, 2025에 액세스, [https://www.insidetechlaw.com/blog/2024/05/generative-ai-how-it-works-content-ownership-and-copyrights](https://www.insidetechlaw.com/blog/2024/05/generative-ai-how-it-works-content-ownership-and-copyrights)
    
41. Copyright and Generative AI | The Regulatory Review, 8월 31, 2025에 액세스, [https://www.theregreview.org/2025/06/07/seminar-copyright-and-generative-ai/](https://www.theregreview.org/2025/06/07/seminar-copyright-and-generative-ai/)
    
42. Intellectual Property Rights and AI-Generated Content — Issues in Human Authorship, Fair Use Doctrine, and Output Liability | by Adnan Masood, PhD. | Medium, 8월 31, 2025에 액세스, [https://medium.com/@adnanmasood/intellectual-property-rights-and-ai-generated-content-issues-in-human-authorship-fair-use-8c7ec9d6fdc3](https://medium.com/@adnanmasood/intellectual-property-rights-and-ai-generated-content-issues-in-human-authorship-fair-use-8c7ec9d6fdc3)
    
43. copyright - How is Midjourney's ToS Legal? - Law Stack Exchange, 8월 31, 2025에 액세스, [https://law.stackexchange.com/questions/93389/how-is-midjourneys-tos-legal](https://law.stackexchange.com/questions/93389/how-is-midjourneys-tos-legal)
    
44. AI-Generated Works Dilemma: Balancing AI Terms of Service With Contractual Obligations | Offit Kurman Blogs, 8월 31, 2025에 액세스, [https://www.offitkurman.com/offit-kurman-blogs/ai-generated-works-dilemma-balancing-ai-terms-of-service-with-contractual-obligations](https://www.offitkurman.com/offit-kurman-blogs/ai-generated-works-dilemma-balancing-ai-terms-of-service-with-contractual-obligations)
    
45. Discussing the Copyrightability of Generative AI Outputs | TechPolicy.Press, 8월 31, 2025에 액세스, [https://www.techpolicy.press/discussing-the-copyrightability-of-generative-ai-outputs/](https://www.techpolicy.press/discussing-the-copyrightability-of-generative-ai-outputs/)
    
46. The New York Times v. OpenAI: The Biggest IP Case Ever - Sunstein LLP, 8월 31, 2025에 액세스, [https://www.sunsteinlaw.com/publications/the-new-york-times-v-openai-the-biggest-ip-case-ever](https://www.sunsteinlaw.com/publications/the-new-york-times-v-openai-the-biggest-ip-case-ever)
    
47. Copyright Office Weighs In on AI Training and Fair Use, 8월 31, 2025에 액세스, [https://www.skadden.com/insights/publications/2025/05/copyright-office-report](https://www.skadden.com/insights/publications/2025/05/copyright-office-report)
    
48. From Copyright Case to AI Data Crisis: How The New York Times v. OpenAI Reshapes Companies' Data Governance and eDiscovery Strategy - Nelson Mullins, 8월 31, 2025에 액세스, [https://www.nelsonmullins.com/insights/blogs/corporate-governance-insights/all/from-copyright-case-to-ai-data-crisis-how-the-new-york-times-v-openai-reshapes-companies-data-governance-and-ediscovery-strategy](https://www.nelsonmullins.com/insights/blogs/corporate-governance-insights/all/from-copyright-case-to-ai-data-crisis-how-the-new-york-times-v-openai-reshapes-companies-data-governance-and-ediscovery-strategy)
    
49. New York Times v. Microsoft Corp., 8월 31, 2025에 액세스, [https://www.loeb.com/en/insights/publications/2025/04/new-york-times-v-microsoft-corp](https://www.loeb.com/en/insights/publications/2025/04/new-york-times-v-microsoft-corp)
    
50. NYT v. OpenAI: The Times's About-Face - Harvard Law Review, 8월 31, 2025에 액세스, [https://harvardlawreview.org/blog/2024/04/nyt-v-openai-the-timess-about-face/](https://harvardlawreview.org/blog/2024/04/nyt-v-openai-the-timess-about-face/)
    
51. The New York Times Case against OpenAI is Different. Here's Why. - Patent Docs, 8월 31, 2025에 액세스, [https://www.patentdocs.org/2024/02/the-new-york-times-case-against-openai-is-different-heres-why.html](https://www.patentdocs.org/2024/02/the-new-york-times-case-against-openai-is-different-heres-why.html)
    
52. OpenAI, The New York Times debate copyright infringement of AI tech companies in trial arguments - Digiday, 8월 31, 2025에 액세스, [https://digiday.com/media/openai-the-new-york-times-debate-copyright-infringement-of-ai-tech-companies-in-first-trial-arguments/](https://digiday.com/media/openai-the-new-york-times-debate-copyright-infringement-of-ai-tech-companies-in-first-trial-arguments/)
    
53. Getty Images v. Stability AI | BakerHostetler, 8월 31, 2025에 액세스, [https://www.bakerlaw.com/getty-images-v-stability-ai/](https://www.bakerlaw.com/getty-images-v-stability-ai/)
    
54. Getty Images v Stability AI: why the remaining copyright claims are of more than secondary significance - Pinsent Masons, 8월 31, 2025에 액세스, [https://www.pinsentmasons.com/out-law/analysis/getty-images-v-stability-ai-copyright-claims-significance](https://www.pinsentmasons.com/out-law/analysis/getty-images-v-stability-ai-copyright-claims-significance)
    
55. Generative AI in the courts - Getty Images v Stability AI, 8월 31, 2025에 액세스, [https://www.penningtonslaw.com/news-publications/latest-news/2024/generative-ai-in-the-courts-getty-images-v-stability-ai](https://www.penningtonslaw.com/news-publications/latest-news/2024/generative-ai-in-the-courts-getty-images-v-stability-ai)
    
56. Getty Images v. Stability AI: A Prelude to The Long-Awaited Trial, 8월 31, 2025에 액세스, [https://www.simmons-simmons.com/en/publications/cmbk5e155006cubvw9ho9r5wn/getty-images-v-stability-ai-a-prelude-to-the-long-awaited-trial](https://www.simmons-simmons.com/en/publications/cmbk5e155006cubvw9ho9r5wn/getty-images-v-stability-ai-a-prelude-to-the-long-awaited-trial)
    
57. Getty Images vs. Stability AI: The UK Court Battle That Could Reshape AI and Copyright Law, 8월 31, 2025에 액세스, [https://www.finnegan.com/en/insights/articles/getty-images-vs-stability-ai-the-uk-court-battle-that-could-reshape-ai-and-copyright-law.html](https://www.finnegan.com/en/insights/articles/getty-images-vs-stability-ai-the-uk-court-battle-that-could-reshape-ai-and-copyright-law.html)
    
58. Navigating representative actions: takeaways from Getty Images v Stability AI, 8월 31, 2025에 액세스, [https://www.hsfkramer.com/notes/ip/2025-01/navigating-representative-actions-takeaways-from-getty-images-v-stability-ai](https://www.hsfkramer.com/notes/ip/2025-01/navigating-representative-actions-takeaways-from-getty-images-v-stability-ai)
    
59. Getty Images v Stability AI: where are we after the trial - copyright? - Taylor Wessing, 8월 31, 2025에 액세스, [https://www.taylorwessing.com/en/insights-and-events/insights/2025/07/getty-v-stability](https://www.taylorwessing.com/en/insights-and-events/insights/2025/07/getty-v-stability)
    
60. Silverman v. OpenAI - Knowing Machines, 8월 31, 2025에 액세스, [https://knowingmachines.org/knowing-legal-machines/legal-explainer/cases/silverman-v-openai](https://knowingmachines.org/knowing-legal-machines/legal-explainer/cases/silverman-v-openai)
    
61. AI and Copyright in 2023: In the Courts, 8월 31, 2025에 액세스, [https://copyrightalliance.org/ai-copyright-courts/](https://copyrightalliance.org/ai-copyright-courts/)
    
62. U.S. Copyright Office Releases Part 3 of AI Report: What Authors Should Know, 8월 31, 2025에 액세스, [https://authorsguild.org/news/us-copyright-office-ai-report-part-3-what-authors-should-know/](https://authorsguild.org/news/us-copyright-office-ai-report-part-3-what-authors-should-know/)
    
63. Copyright Office Issues Key Guidance on Fair Use in Generative AI Training, 8월 31, 2025에 액세스, [https://www.wiley.law/alert-Copyright-Office-Issues-Key-Guidance-on-Fair-Use-in-Generative-AI-Training](https://www.wiley.law/alert-Copyright-Office-Issues-Key-Guidance-on-Fair-Use-in-Generative-AI-Training)
    
64. Authors Guild, Inc. v. Google Inc., No. 13-4829-cv (2d Cir. Oct. 16, 2015) Year 2015 Court - U.S. Copyright Office, 8월 31, 2025에 액세스, [https://www.copyright.gov/fair-use/summaries/authorsguild-google-2dcir2015.pdf](https://www.copyright.gov/fair-use/summaries/authorsguild-google-2dcir2015.pdf)
    
65. Authors Guild v. Google, Inc., No. 13-4829 (2d Cir. 2015) - Justia Law, 8월 31, 2025에 액세스, [https://law.justia.com/cases/federal/appellate-courts/ca2/13-4829/13-4829-2015-10-16.html](https://law.justia.com/cases/federal/appellate-courts/ca2/13-4829/13-4829-2015-10-16.html)
    
66. Authors Guild v. Google, Inc. - Stanford Copyright and Fair Use Center, 8월 31, 2025에 액세스, [https://fairuse.stanford.edu/case/authors-guild-v-google-inc/](https://fairuse.stanford.edu/case/authors-guild-v-google-inc/)
    
67. Authors Guild, Inc. v. Google, Inc. - Wikipedia, 8월 31, 2025에 액세스, [https://en.wikipedia.org/wiki/Authors_Guild,_Inc._v._Google,_Inc.](https://en.wikipedia.org/wiki/Authors_Guild,_Inc._v._Google,_Inc.)
    
68. Authors Guild v. Google - Supreme Court of the United States, 8월 31, 2025에 액세스, [https://www.scotusblog.com/wp-content/uploads/2016/01/Authors-Guild-v.-Google.pdf](https://www.scotusblog.com/wp-content/uploads/2016/01/Authors-Guild-v.-Google.pdf)
    
69. Fair Use Week 2023: Looking Back at Google Books Eight Years Later - Authors Alliance, 8월 31, 2025에 액세스, [https://www.authorsalliance.org/2023/02/24/fair-use-week-2023-looking-back-at-google-books-eight-years-later/](https://www.authorsalliance.org/2023/02/24/fair-use-week-2023-looking-back-at-google-books-eight-years-later/)
    
70. Copyright and AI: the Cases and the Consequences | Electronic Frontier Foundation, 8월 31, 2025에 액세스, [https://www.eff.org/deeplinks/2025/02/copyright-and-ai-cases-and-consequences](https://www.eff.org/deeplinks/2025/02/copyright-and-ai-cases-and-consequences)
    
71. U.S. Supreme Court Holds That First Factor of Fair Use Test Favors Photographer | Insights, 8월 31, 2025에 액세스, [https://www.hklaw.com/en/insights/publications/2023/06/us-supreme-court-holds-that-first-factor-of-fair-use](https://www.hklaw.com/en/insights/publications/2023/06/us-supreme-court-holds-that-first-factor-of-fair-use)
    
72. Andy Warhol Foundation for the Visual Arts, Inc. v. Goldsmith | Loeb & Loeb LLP, 8월 31, 2025에 액세스, [https://www.loeb.com/en/insights/publications/2023/05/andy-warhol-foundation-for-the-visual-arts-inc-v-goldsmith](https://www.loeb.com/en/insights/publications/2023/05/andy-warhol-foundation-for-the-visual-arts-inc-v-goldsmith)
    
73. Andy Warhol Found. for the Visual Arts, Inc. v. Goldsmith 143 S. Ct. 1258 (2023) Year 2023 Court Supreme Court of the United Sta, 8월 31, 2025에 액세스, [https://www.copyright.gov/fair-use/summaries/Andy-Warhol-Found-for-the-Visual-Arts-Inc-v-Goldsmith-143-S-Ct-1258-2023.pdf](https://www.copyright.gov/fair-use/summaries/Andy-Warhol-Found-for-the-Visual-Arts-Inc-v-Goldsmith-143-S-Ct-1258-2023.pdf)
    
74. Comment on Andy Warhol Found. for the Visual Arts, Inc. v. Goldsmith, 992 F.3d 99 (2d Cir. 2021) - Scholarship Archive, 8월 31, 2025에 액세스, [https://scholarship.law.columbia.edu/cgi/viewcontent.cgi?article=3760&context=faculty_scholarship](https://scholarship.law.columbia.edu/cgi/viewcontent.cgi?article=3760&context=faculty_scholarship)
    
75. Fair Use in a Post-Warhol World: Part I - Copyright Alliance, 8월 31, 2025에 액세스, [https://copyrightalliance.org/fair-use-post-warhol-world-part-i/](https://copyrightalliance.org/fair-use-post-warhol-world-part-i/)
    
76. Supreme Court Addresses Copyright Fair Use Defense in Goldsmith | Insights, 8월 31, 2025에 액세스, [https://www.skadden.com/insights/publications/2023/05/supreme-court-addresses-copyright-fair-use-defense](https://www.skadden.com/insights/publications/2023/05/supreme-court-addresses-copyright-fair-use-defense)
    
77. Everything might be OK! Warhol v. Goldsmith - Creative Commons, 8월 31, 2025에 액세스, [https://creativecommons.org/2023/05/18/warhol-v-goldsmith/](https://creativecommons.org/2023/05/18/warhol-v-goldsmith/)
    
78. The Fair Use Defense for Generative AI Tools After Warhol V. Goldsmith - A Fresh Take, 8월 31, 2025에 액세스, [https://blog.freshfields.us/post/102ih2k/the-fair-use-defense-for-generative-ai-tools-after-warhol-v-goldsmith](https://blog.freshfields.us/post/102ih2k/the-fair-use-defense-for-generative-ai-tools-after-warhol-v-goldsmith)
    
79. AI and copyright: The training of general-purpose AI - European Parliament, 8월 31, 2025에 액세스, [https://www.europarl.europa.eu/RegData/etudes/ATAG/2025/769585/EPRS_ATA(2025)769585_EN.pdf](https://www.europarl.europa.eu/RegData/etudes/ATAG/2025/769585/EPRS_ATA\(2025\)769585_EN.pdf)
    
80. The TDM Opt-Out in the EU – Five Problems, One Solution | Kluwer Copyright Blog, 8월 31, 2025에 액세스, [https://legalblogs.wolterskluwer.com/copyright-blog/the-tdm-opt-out-in-the-eu-five-problems-one-solution/](https://legalblogs.wolterskluwer.com/copyright-blog/the-tdm-opt-out-in-the-eu-five-problems-one-solution/)
    
81. European Parliament's New Study on Generative AI and Copyright Calls for Overhaul of Opt-Out Regime | Insights | Jones Day, 8월 31, 2025에 액세스, [https://www.jonesday.com/en/insights/2025/08/european-parliaments-new-study-on-generative-ai-and-copyright-calls-for-overhaul-of-optout-regime](https://www.jonesday.com/en/insights/2025/08/european-parliaments-new-study-on-generative-ai-and-copyright-calls-for-overhaul-of-optout-regime)
    
82. Is opt-out a relevant tool for protection against AI? - Crealo, 8월 31, 2025에 액세스, [https://www.crealo.app/en/post/opt-out](https://www.crealo.app/en/post/opt-out)
    
83. 'Blistering' EU report calls for copyright reform to combat large-scale AI data training, 8월 31, 2025에 액세스, [https://www.globallegalpost.com/news/blistering-eu-report-calls-for-copyright-reform-to-combat-large-scale-ai-data-training-1289113154](https://www.globallegalpost.com/news/blistering-eu-report-calls-for-copyright-reform-to-combat-large-scale-ai-data-training-1289113154)
    
84. Key Issue 5: Transparency Obligations - EU AI Act, 8월 31, 2025에 액세스, [https://www.euaiact.com/key-issue/5](https://www.euaiact.com/key-issue/5)
    
85. EU AI Act: first regulation on artificial intelligence | Topics - European Parliament, 8월 31, 2025에 액세스, [https://www.europarl.europa.eu/topics/en/article/20230601STO93804/eu-ai-act-first-regulation-on-artificial-intelligence](https://www.europarl.europa.eu/topics/en/article/20230601STO93804/eu-ai-act-first-regulation-on-artificial-intelligence)
    
86. What Is Overfitting in Machine Learning? - Grammarly, 8월 31, 2025에 액세스, [https://www.grammarly.com/blog/ai/what-is-overfitting/](https://www.grammarly.com/blog/ai/what-is-overfitting/)
    
87. What is Overfitting? - Overfitting in Machine Learning Explained - AWS, 8월 31, 2025에 액세스, [https://aws.amazon.com/what-is/overfitting/](https://aws.amazon.com/what-is/overfitting/)
    
88. Overfitting In AI Future Trends - Meegle, 8월 31, 2025에 액세스, [https://www.meegle.com/en_us/topics/overfitting/overfitting-in-ai-future-trends](https://www.meegle.com/en_us/topics/overfitting/overfitting-in-ai-future-trends)
    
89. When More Data Breaks the Model: The Paradox of Overfitting in AI - Medium, 8월 31, 2025에 액세스, [https://medium.com/@devikareddykundavaram/when-more-data-breaks-the-model-the-paradox-of-overfitting-in-ai-2dcd77a6b59a](https://medium.com/@devikareddykundavaram/when-more-data-breaks-the-model-the-paradox-of-overfitting-in-ai-2dcd77a6b59a)
    
90. What is Overfitting? | IBM, 8월 31, 2025에 액세스, [https://www.ibm.com/think/topics/overfitting](https://www.ibm.com/think/topics/overfitting)
    
91. The Limits of Learning: How Overfitting Influences Large Language Models - RapidCanvas, 8월 31, 2025에 액세스, [https://www.rapidcanvas.ai/blogs/the-limits-of-learning-how-overfitting-influences-large-language-models](https://www.rapidcanvas.ai/blogs/the-limits-of-learning-how-overfitting-influences-large-language-models)
    
92. Overfitting: Causes and Remedies - Towards AI, 8월 31, 2025에 액세스, [https://towardsai.net/p/l/overfitting-causes-and-remedies](https://towardsai.net/p/l/overfitting-causes-and-remedies)
    
93. Understanding Generative AI and Trademark Infringement Risks - Christian & Barton, 8월 31, 2025에 액세스, [https://www.cblaw.com/generative-ai-and-trademark-infringement-risks](https://www.cblaw.com/generative-ai-and-trademark-infringement-risks)
    
94. Generative AI in fashion design complicates trademark ownership | Inside Tech Law, 8월 31, 2025에 액세스, [https://www.insidetechlaw.com/blog/2024/05/generative-ai-in-fashion-design-complicates-trademark-ownership](https://www.insidetechlaw.com/blog/2024/05/generative-ai-in-fashion-design-complicates-trademark-ownership)
    
95. Hallucinations as Trademark Tarnishment: How Wrong Answers Led to a Lawsuit | JD Supra, 8월 31, 2025에 액세스, [https://www.jdsupra.com/legalnews/hallucinations-as-trademark-tarnishment-6143582/](https://www.jdsupra.com/legalnews/hallucinations-as-trademark-tarnishment-6143582/)
    
96. Snapshot: A Rising Claim in Generative AI Cases - Trademark Dilution - The Fashion Law, 8월 31, 2025에 액세스, [https://www.thefashionlaw.com/snapshot-a-rising-claim-in-generative-ai-cases-trademark-dilution/](https://www.thefashionlaw.com/snapshot-a-rising-claim-in-generative-ai-cases-trademark-dilution/)
    
97. dilution (trademark) | Wex | US Law | LII / Legal Information Institute, 8월 31, 2025에 액세스, [https://www.law.cornell.edu/wex/dilution_(trademark)](https://www.law.cornell.edu/wex/dilution_\(trademark\))
    
98. AI and Trademark Dilution: Protecting Famous Brands from Tarnishment and Blurring, 8월 31, 2025에 액세스, [https://www.fortislawpartners.com/blog/ai-trademark-dilution-brand-protection/](https://www.fortislawpartners.com/blog/ai-trademark-dilution-brand-protection/)
    
99. AI Service Agreements in Health Care: Indemnification Clauses, Emerging Trends, and Future Risks | ArentFox Schiff, 8월 31, 2025에 액세스, [https://www.afslaw.com/perspectives/health-care-counsel-blog/ai-service-agreements-health-care-indemnification-clauses](https://www.afslaw.com/perspectives/health-care-counsel-blog/ai-service-agreements-health-care-indemnification-clauses)
    
100. IP and AI Indemnity | BakerHostetler, 8월 31, 2025에 액세스, [https://www.bakerlaw.com/services/ip-and-ai-indemnity/](https://www.bakerlaw.com/services/ip-and-ai-indemnity/)
    
101. Exploring AI indemnities: their purpose and impact - Farrer & Co, 8월 31, 2025에 액세스, [https://www.farrer.co.uk/news-and-insights/exploring-ai-indemnities-their-purpose-and-impact/](https://www.farrer.co.uk/news-and-insights/exploring-ai-indemnities-their-purpose-and-impact/)
    
102. Protecting customers with generative AI indemnification | Google Cloud Blog, 8월 31, 2025에 액세스, [https://cloud.google.com/blog/products/ai-machine-learning/protecting-customers-with-generative-ai-indemnification](https://cloud.google.com/blog/products/ai-machine-learning/protecting-customers-with-generative-ai-indemnification)
    
103. Microsoft announces new Copilot Copyright Commitment for customers, 8월 31, 2025에 액세스, [https://blogs.microsoft.com/on-the-issues/2023/09/07/copilot-copyright-commitment-ai-legal-concerns/](https://blogs.microsoft.com/on-the-issues/2023/09/07/copilot-copyright-commitment-ai-legal-concerns/)
    
104. Microsoft Announces Copilot Copyright Commitment to Address IP Infringement Concerns, 8월 31, 2025에 액세스, [https://www.infoq.com/news/2023/09/copilot-copyright-commitment/](https://www.infoq.com/news/2023/09/copilot-copyright-commitment/)
    
105. Google is latest company to indemnify AI users against infringement | Legal Dive, 8월 31, 2025에 액세스, [https://www.legaldive.com/news/google-indemnify-generativeai-users-against-infringement-copyright-IP-genAI/696593/](https://www.legaldive.com/news/google-indemnify-generativeai-users-against-infringement-copyright-IP-genAI/696593/)
    
106. Adobe Firefly | Product Description, 8월 31, 2025에 액세스, [https://helpx.adobe.com/legal/product-descriptions/adobe-firefly.html](https://helpx.adobe.com/legal/product-descriptions/adobe-firefly.html)
    
107. OpenAI's “Copyright Shield” Broadens User IP Indemnities for AI-created Content - Insights, 8월 31, 2025에 액세스, [https://www.proskauer.com/blog/openais-copyright-shield-broadens-user-ip-indemnities-for-ai-created-content](https://www.proskauer.com/blog/openais-copyright-shield-broadens-user-ip-indemnities-for-ai-created-content)
    
108. Service terms - OpenAI, 8월 31, 2025에 액세스, [https://openai.com/policies/service-terms/](https://openai.com/policies/service-terms/)
    
109. OpenAI offers to indemnify ChatGPT customers for copyright infringement - The Lens, 8월 31, 2025에 액세스, [https://thelens.slaughterandmay.com/post/102iscn/openai-offers-to-indemnify-chatgpt-customers-for-copyright-infringement](https://thelens.slaughterandmay.com/post/102iscn/openai-offers-to-indemnify-chatgpt-customers-for-copyright-infringement)
    
110. Adobe Firefly | Comprehensive & Commercially Safe AI Content Creation for Businesses, 8월 31, 2025에 액세스, [https://business.adobe.com/products/firefly-business/firefly-ai-approach.html](https://business.adobe.com/products/firefly-business/firefly-ai-approach.html)
    
111. Adobe Generative AI Product Specific Terms (en_US), 8월 31, 2025에 액세스, [https://wwwimages2.adobe.com/content/dam/cc/en/legal/servicetou/adobe-generative-ai-product-specific-terms-en-us-20250617.pdf](https://wwwimages2.adobe.com/content/dam/cc/en/legal/servicetou/adobe-generative-ai-product-specific-terms-en-us-20250617.pdf)
    
112. Adobe Firefly offers indemnity from generative AI copyright claims - Tech Monitor, 8월 31, 2025에 액세스, [https://techmonitor.ai/technology/ai-and-automation/adobe-firefly-generative-ai](https://techmonitor.ai/technology/ai-and-automation/adobe-firefly-generative-ai)
    
113. Safer Prompts: Reducing IP Risk in Visual Generative AI - arXiv, 8월 31, 2025에 액세스, [https://arxiv.org/html/2505.03338v1](https://arxiv.org/html/2505.03338v1)
    
114. Prompt Engineering: From Words to Art and Copy - Saxifrage Blog, 8월 31, 2025에 액세스, [https://www.saxifrage.xyz/post/prompt-engineering](https://www.saxifrage.xyz/post/prompt-engineering)
    
115. Prompt Engineering for AI Guide | Google Cloud, 8월 31, 2025에 액세스, [https://cloud.google.com/discover/what-is-prompt-engineering](https://cloud.google.com/discover/what-is-prompt-engineering)
    
116. 10 Image Prompting Mistakes—and how to avoid them | by Rob Laughter | Medium, 8월 31, 2025에 액세스, [https://roblaughter.medium.com/10-image-prompting-mistakes-and-how-to-avoid-them-244f972d0c2a](https://roblaughter.medium.com/10-image-prompting-mistakes-and-how-to-avoid-them-244f972d0c2a)
    
117. AI Art Prompting Guide: Image Prompting | Microsoft Copilot, 8월 31, 2025에 액세스, [https://www.microsoft.com/en-us/microsoft-copilot/for-individuals/do-more-with-ai/ai-art-prompting-guide/image-prompting-101](https://www.microsoft.com/en-us/microsoft-copilot/for-individuals/do-more-with-ai/ai-art-prompting-guide/image-prompting-101)
    
118. Prompting: What to know and does it matter for Intellectual Property? | Skrine, 8월 31, 2025에 액세스, [https://www.skrine.com/insights/alerts/august-2024/prompting-what-to-know-and-does-it-matter-for-inte](https://www.skrine.com/insights/alerts/august-2024/prompting-what-to-know-and-does-it-matter-for-inte)
    
119. How to Know if an Image Is Copyrighted - LegalZoom, 8월 31, 2025에 액세스, [https://www.legalzoom.com/articles/how-to-know-if-an-image-is-copyrighted](https://www.legalzoom.com/articles/how-to-know-if-an-image-is-copyrighted)
    
120. Reverse Image Search - Search By Image Online, 8월 31, 2025에 액세스, [https://www.reverseimagesearch.org/](https://www.reverseimagesearch.org/)
    
121. Reverse Image Search - Search by Image to Find Similar Photos, 8월 31, 2025에 액세스, [https://www.reverseimagesearch.com/](https://www.reverseimagesearch.com/)
    
122. Reversely.ai - AI Reverse Image Search, 8월 31, 2025에 액세스, [https://www.reversely.ai/](https://www.reversely.ai/)
    
123. Reverse Image Search - Find Similar Photos Online - Small SEO Tools, 8월 31, 2025에 액세스, [https://smallseotools.com/reverse-image-search/](https://smallseotools.com/reverse-image-search/)
    
124. Free AI Reverse Image Search - Vecteezy, 8월 31, 2025에 액세스, [https://www.vecteezy.com/reverse-image-search](https://www.vecteezy.com/reverse-image-search)
    
125. TinEye - Reverse Image Search and Recognition, 8월 31, 2025에 액세스, [https://tineye.com/](https://tineye.com/)
    
126. Free Reverse Image Search - Artist Ninja, 8월 31, 2025에 액세스, [https://artist.ninja/reverse-image-search](https://artist.ninja/reverse-image-search)
    
127. Free AI Detector | GPT-4, GPT-3, & ChatGPT AI Checker - Grammarly, 8월 31, 2025에 액세스, [https://www.grammarly.com/ai-detector](https://www.grammarly.com/ai-detector)
    
128. When Does AI Use Become Plagiarism? A Student Guide to Avoiding Academic Misconduct, 8월 31, 2025에 액세스, [https://www.thesify.ai/blog/when-does-ai-use-become-plagiarism-what-students-need-to-know](https://www.thesify.ai/blog/when-does-ai-use-become-plagiarism-what-students-need-to-know)
    
129. AI Detector - Trusted AI Checker for ChatGPT, Copilot & Gemini - Scribbr, 8월 31, 2025에 액세스, [https://www.scribbr.com/ai-detector/](https://www.scribbr.com/ai-detector/)
    
130. Plagiarism Checker | Accurate and Fast - QuillBot AI, 8월 31, 2025에 액세스, [https://quillbot.com/plagiarism-checker](https://quillbot.com/plagiarism-checker)
    
131. Careful use of AI detectors - Center for Teaching Excellence, 8월 31, 2025에 액세스, [https://cte.ku.edu/careful-use-ai-detectors](https://cte.ku.edu/careful-use-ai-detectors)
    
132. Why AI Models Are Bad at Verifying Photos - Columbia Journalism Review, 8월 31, 2025에 액세스, [https://www.cjr.org/tow_center/why-ai-models-are-bad-at-verifying-photos.php](https://www.cjr.org/tow_center/why-ai-models-are-bad-at-verifying-photos.php)
    
133. Spotting AI: Knowing How to Recognise Real vs AI Images - Britannica Education, 8월 31, 2025에 액세스, [https://elearn.eb.com/real-vs-ai-images/](https://elearn.eb.com/real-vs-ai-images/)
