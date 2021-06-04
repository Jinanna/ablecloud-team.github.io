---
layout: page-fullwidth
title:  "ABLESTACK 1.0 Allo 릴리즈"
subheadline:  "제품 및 기능 릴리즈"
teaser: "<br/>우리는 기업의 새로운 클라우드 데이터센터 구축을 위한 최고의 소프트웨어스택인 ABLESTACK의 첫번째 버전을 릴리즈 하게 됨을 기쁘게 생각하며, 사용자 여려분에게 자신있게 제품을 선보입니다. 지금 바로 ABLESTACK을 기업에서 사용할 수 있습니다. "

categories:
    - Release
tags:
  - ablestack
  - release
  - allo

header:
   title: ''
   image_fullwidth: ablestack-allo-background.png

image:
   thumb: home_product_thumb.png
   homepage: ablestack-allo-background.png
---

<div class="row">
<div class="medium-4 medium-push-8 columns" markdown="1">
  <div class="panel radius" markdown="1">
  **Table of Contents**
  {: #toc }
  *  TOC
  {:toc}
  </div>
</div><!-- /.medium-4.columns -->

<div class="medium-8 medium-pull-4 columns" markdown="1">

### SDDC란 무엇인가?
<br/>
SDDC(소프트웨어 정의 데이터센터)는 서버, 스토리지, 네트워크, 보안과 같은 모든 인프라 요소가 가상화 되어 서비스 처럼 제공되는 새로운 개념의 데이터센터입니다. 배포, 운영, 프로비저닝 및 구성 등은 가상화 기술을 이용해 제공되며, 이러한 모든 작업은 소프트에어 인텔리전스를 통해 구현됩니다. 이러한 용어는 전 VMWare CTO인 스티브 해러드에 의해 2012년에 만들어진 것으로 알려져 있습니다. 

최근에는 실제 이러한 SDDC를 클라우드 서비스 회사 및 데이터센터 기업 등에 의해 구체적으로 실현 하는 단계까지 발전하고 있습니다. 이러한 SDDC는 향후 기업의 IT 환경의 혁신 및 비즈니스의 혁신에 핵심이 될 개념이 될 것입니다. 

<br/>

#### 전통적인 데이터센터의 특징
</div>
</div>

<br/>
지금까지의 데이터센터는 무수히 많은 베어메탈 하드웨어와 하드웨어별로 설치되어 있는 소프트웨어, 그리고 이러한 인프라를 관리하기 위한 인력/전문가로 정의될 수 있습니다. 이러한 전통적인 데이터센터는 다음과 같은 특징을 가집니다. 

  - 수많은 벤더사와 벤더사별로 서로 다른 베어메탈 하드웨어
  - 안정성 유지를 위한 이중화 구성과 대규모 외장 스토리지
  - 벤더 락인 및 하드웨어 단위 앱 관리로 인한 높은 경직성
  - 하드웨어별 서로 다른 관리 환경으로 인한 복잡성
  - 개발환경과 운영환경의 차이로 개발계/운영계로 나누어 관리되는 조직
  - 넓은 면적과 높은 전력 소모량, 높은 운영 비용
  - 전문 인력에 의한 상시적인 기술지원


위와 같은 특징은 대규모로 데이터센터를 운영하는 전문 데이터센터 기업에게 있어서 장점이 될 수 있으나, 일반 기업이 데이터센터를 운영하거나 또는 대규모 데이터센터의 상면을 임대해 운영하는데 있어서 많은 어려움을 갖게 합니다. 

<br/>

#### 미래의 데이터센터의 방향
<br/>
앞으로의 데이터센터는 클라우드의 발전 및 확대, 그리고 소프트웨어 정의 기술, 가상화 기술을 바탕으로 단순화, 효율화, 자동화, 지능화된 데이터센터로의 발전 및 진화를 꾀하게 될 것입니다. 미래의 데이터센터는 최종적으로 다음과 같은 특징을 갖게 될 것입니다. 

  - 소프트웨어로 정의된 컴퓨트 및 네트워크
  - 소프트웨어로 정의된 고성능, 안정적인 스토리지
  - 가상화를 통한 유연한 인프라 제공
  - 벤더와 상관없는 단일 관리 환경
  - 개발/테스트/운영환경 통합을 통한 지속적 통합/개발
  - 클러스터링 기술을 통한 적은 면적 및 전력 소모량
  - 공유 가능한 자동화 기술을 통한 셀프서비스

위와 같은 특징은 기업이 직접 소프트웨어적인 방법으로 데이터센터 인프라를 소유하고, 안정적으로 운영할 수 있는 환경을 제공하며, 어떤 인프라 환경을 사용할지 결정하는데 있어서 선택의 자유를 제공할 수 있게 됩니다. 클라우드 데이터센터를 비롯해 기업의 모든 인프라 환경은 
이러한 SDDC를 얼마나 완벽하게 구현하느냐의 방향으로 지속적으로 발전해 갈 것입니다. 

<br/>

### SDDC 아키텍처

<br/>
<div class="row">
   <div class="small-7 columns">
      <img src="/images/sddc-architecture.png">
   </div>
   <div class="small-5 columns">
      <p>
         SDDC는 크게 물리레이어, 가상화레이어, 관리레이어로 나누어 구성됩니다. <br/>
         <br/>
         물리레이어는 전통적인 데이터센터와 동일한 구조를 가지며, 서버, 스토리지, 스위치 등으로 이루어집니다. <br/><br/>
         가상화레이어는 물리레이어를 이용해 컴퓨트 자원을 제공하고, 이를 컨트롤하는 역할을 합니다. 일반적인 가상머신을 비롯해 컨테이너, 그리고 가상화를 통해 만들어진 스토리지 서비스, 가상화를 통해 제공되는 네트워크 서비스를 포함합니다. <br/><br/>
         관리레이어는 가상화레이어와 물리레이어를 효과적으로 관리하고, 사용자에게 셀프서비스 환경을 제공해주는 역할을 합니다. 일반적인 IT 운영, 자동화, 연속성 지원, 보안 관리 등의 서비스를 포함합니다. 
      </p>
   </div>
</div>

물리레이어는 일반 데이터센터의 구성요소와 동일한 구성입니다. 서버와 스토리지, 스위치 등으로 구성됩니다. 이 물리레이어는 SDDC 관점에서 어떻게 TCO를 줄이면서 동일한 데이터센터 워크로드를 처리할 수 있도록 할 것인가, 그리고 어떻게 사용자에게 투명하게 물리적인 인프라를 관리할 수 있도록 할 것인가가 중요합니다. 

가상화 레이어는 물리레이어가 제공하는 인프라를 이용해 효율적으로 자원을 가상화 하고 고가용성을 유지하도록 하며, 이러한 가상화 기술을 이용해 스토리지 또는 네트워크를 제공하는 기반으로써 동작합니다. 가상화 영역은 소프트웨어로 구성됩니다. 하이퍼바이저, 컨테이너 등의 소프트웨어, 스토리지 및 네트워크 소프트웨어 등이 필요한데, 이러한 소프트웨어를 어떤 방식으로, 또 어떤 제품으로 구성하느냐가 SDDC를 구성함에 있어 매우 중요한 요소가 됩니다. 

마지막으로 관리 레이어는 SDDC를 사용하는 관리자/사용자가 직접 보게 되는 구성요소입니다. 관리 레이어는 기본적인 IT 운영, 그리고 사용자의 셀프서비스를 지원하는 자동화 기능, 고가용성 및 백업, 재해복구 등을 지원하는 연속성 지원 기능, 그리고 각종 정책 관리 및 보안 정책을 관리하는 기능 등이 포함되어, 사용자 인터페이스를 통해 데이터센터 기능 전체를 사용할 수 있도록 구성되야 합니다. 

<br/>

### SDDC의 이점과 문제점
<br/>
소프트웨어 정의 데이터센터는 데이터센터에 애플리케이션, 인프라 및 IT 리소스를 동적으로 구성하고 프로비저닝하는 방법을 제공합니다. SDDC 디자인은 데이터센터가 통합된 시스템으로 관리될 수 있도록 합니다. 사용자에게는 통합된 관리 환경을 제공하여, 관리 환경과 인프라 환경을 사용자로부터 분리합니다. 

SDDC는 기업에 물리레이어의 인프라를 효과적으로 관리할 수 있는 자체적인 프라이빗 클라우드를 제공합니다. 

소프트웨어 정의 데이터센터 는 클라우드 컴퓨팅의 민첩성, 탄력성 및 확장성을 핵심으로합니다. 가장 큰 장점은 그 동안 수동으로 이루어졌던 프로비저닝 작업 및 운영 관리와 관련된 작업에 대한 지능형 소프트웨어를 통한 모든 기능의 자동화 입니다.

이는 기존의 기업 데이터센터에 높은 수준의 유연성을 제공합니다. IT자원은 프라이빗 클라우드 또는 하이브리드 클라우드를 통해 프로비저닝 됩니다. 워크로드는 물리적 IT 인프라와 독립적으로 작동합니다.

인프라 관리 와 워크로드 관리는 모두 프로그래밍 방식으로 제어되며 이를 통해 비용과 관리 오버 헤드를 줄일 수 있게 됩니다.

SDDC구현하기 위해서는 다양한 구성 요소로 구성됩니다. 따라서 기업은 SDDC 구성 시 효율적인 아키텍처의 계획 및 통합이 복잡해집니다.

<br/>

### 완벽한 SDDC의 구현 - ABLESTACK
<br/>
ABLESTACK은 기업에 완벽한 SDDC를 구현할 수 있는 솔루션입니다. SDDC의 이점을 모두 누리면서, SDDC 구축의 어려움을 한번에 해결할 수 있기 때문입니다. 

기업의 SDDC 구현을 위해 ABLESTACK은 다음과 같은 아키텍처 및 특징을 갖고 있습니다. 

<br/>

#### SDDC 관점에서 바라본 ABLESTACK 아키텍처
<br/>
ABLESTACK은 SDDC를 구현하기 위한 모든 구성요소를 담고 있으며, 이러한 구성요소를 SDDC 관점의 아키텍처로 구성해 보면 다음과 같습니다. 

<div class="row" style="text-align: center;">
   <img src="/images/sddc-ablestack-architecture.png">
</div>

<br/>

#### ABLESTACK의 특징 및 이점
<br/>
SDDC를 구현하기 위한 솔루션으로써 ABLESTACK이 가지는 구성요소별 특징은 다음과 같습니다. 

   - 물리레이어
      * ABLESTACK은 SDDC를 구현하기 위해 x86 서버만으로 인프라를 구성합니다. 
      * 별도의 스토리지가 필요 없기 때문에 인프라 구성이 매우 단순해 집니다. 
      * 스위치는 최소한의 ToR 스위치로 구성되기 때문에 종단 페브릭 및 횡단 페브릭이 모두 단순해 집니다. 
   - 가상화레이어
      * Cell 하이퍼바이저가 내장되어 있어 별도의 가상화 소프트웨어가 필요 없습니다. 
      * Koral을 통해 Docker 기반의 Kubernetes 클러스터를 자동으로 구성하여 컨테이너 기반 환경을 동시에 제공합니다. 
      * Glue를 통해 고가용성 및 자가치유, 백업, 재해복구 기능을 내장한 스토리지 서비스를 포함합니다.
      * Track을 통해 가상라우터를 기반으로 하는 L4, L3, L2, Firewall, VPN, NAT 등의 네트워크 서비스를 제공합니다. 
   - 관리레이어
      * Mold를 통해 완벽한 프라이빗 클라우드를 제공하여, 사용자에게 인프라와 분리된 편리한 프로비저닝 환경을 제공합니다. 
      * Mold에 내장된 백업, 복구 기능을 통해 비즈니스 연속성을 보장합니다. 
      * Genie를 이용해 사전에 만들어진 플레이북으로 애플리케이션을 자동으로 배포할 수 있고 바로 사용하며 관리할 수 있습니다. 
      * Station은 개발자에게 필요한 프로덕션 레벨의 플랫폼을 제공하여 바로 개발하고 배포할 수 있도록 도와줍니다. 
      * Atom은 마이크로세그멘테이션을 지원하고, 보안 정책을 수립하고 반영할 수 있도록 함으로써 종적 또는 횡적 공격에 안전하게 자원을 보호합니다. 

ABLESTACK은 기업이 SDDC를 목표로 데이터센터를 구현하기 위한 모든 소프트웨어를 제공하는 Full Stack HCI입니다. **'벤더 락인 없는 완전한 SDDC 소프트웨어 스택'**인 ABLESTACK을 지금 바로 경험할 수 있습니다. 

<br/><br/>
{% include next-previous-post-in-category %}

<br/><br/>
<h3>제품 및 기능 릴리즈 카테고리의 다른 문서</h3>
<br/>
{% include list-posts entries='3' offset='0' category='Release' %}