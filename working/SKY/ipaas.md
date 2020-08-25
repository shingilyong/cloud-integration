
# ipaas (integration platform as a service)


ipaas의 개념과 특징에 대해서 알아보고 ipaas를 사용하기 전에 필요한 사전기술은 어떠한 것들이 있는지 살펴보자.

<br/>
<br/>

## Contents

#### [1. ipaas ?](#ipaas)
#### [2. ipaas 작동방식](#ipaas-작동방식)
#### [3. ipaas 특징](#ipaas-특징)
#### [4. ipaas 장점](#ipaas-장점)
#### [5. ipaas 단점](#ipaas-단점)
#### [6. ipaas 에 필요한 사전기술](#ipaas에-필요한-사전기술)
#### [7. 요약](#요약)

---

### ipaas
<img src = "https://user-images.githubusercontent.com/69182192/91016009-0fb73780-e627-11ea-9fb1-c67772b3b0e3.png" width="250px"> <img src = "https://user-images.githubusercontent.com/69182192/91016099-2fe6f680-e627-11ea-9ebe-40665d388895.png" width="300x600px"> <br/>
1. iPaaS 는 소프트웨어 엔지니어가 응용 프로그램 및 서비스를 배포, 관리 및 통합 할 수있는 클라우드 기반 도구 모음

2. iPaaS를 통해 사용자는 클라우드 또는 온-프레미스에있는 응용 프로그램을 연결하는 통합 흐름을 개발 한 다음 하드웨어 나 미들웨어를 설치하거나 관리하지 않고도 배포 할 수 있음


---

### ipaas 작동방식
![ipaas2](https://user-images.githubusercontent.com/69182192/91016102-307f8d00-e627-11ea-9edc-eb6e18c6ca22.png) <br/>
1. iPaaS에는 여러 분산 된 응용 프로그램이 정보를 공유하고 동기화 된 상태로 유지할 수 있도록 하는 일련의 기본 프로세스가 포함됨.

2. ipaas는 다른 애플리케이션과 통신하여 데이터를 추출.

3. 매핑 프로세스를 통해 데이터를 대상 응용 프로그램의 형식으로 변환하고 통합.



---
## ipaas 특징
1. 일반적으로 통합 flow와 API 개발 속도를 높이고 효율적으로 하기 위해서,<br/> 사전 구축 된 커넥터, 비즈니스 규칙, 맵 및 세션 변환을 제공<br/><br/>
2. 사용자는 클라우드 또는 온프레미스에 있는 응용 프로그램을 연결하는 통합 flow를 개발 한 다음,<br/> 소프트웨어 애플리케이션을 구축, 테스트, 배포 및 관리하기 위한 미들웨어 및 기타 소프트웨어 도구 뿐만 아니라 서버 및 데이터 인프라를 제공<br/><br/>
3. 기업은 온프레미스, 클라우드 또는 하이브리드 환경을 사용하여 애플리케이션 및 데이터를 통합함으로써 차별화되고 경쟁력 있는 서비스를 제공<br/><br/>
4. 기능이나 데이터를 신속하게 추가 또는 제거할 수 있으므로 장애나 다운 타임 및 개발 시간이 줄어듬<br/>→ 빠른 릴리스 시간이 핵심 요건인 대규모 B2B 기업에서 주로 사용<br/><br/>



--- 
# ipaas 장점


접근성 : iPaaS는 인터넷 연결을 통해 어디서나 액세스 할 수 있는 웹 인터페이스가 특징

연결성 : ERP 등 주요 시장 응용 프로그램과 MYSQL, ORACLE과 같은 데이터베이스에 대한 커넥터를 통한 통신을 제공

통합 : 조직 내외부의 가상 및 로컬 환경에서 온 솔루션과 데이터를 통합

실시간 처리 : 효율적인 의사결정 및 신속한 처리 및 고객 응답 시간 개선

비용 절감 : 하드웨어나 미들웨어를 따로 구매 및 관리를 하지 않아 비용 절감이 됨

---
# ipaas 단점

복잡한 통합 X : 복잡한 수준의 시스템 통합 및 Work-flow에는 버그가 발생할 수 있음

제한적 : 공식적으로 지원되는 앱만 사용하도록 제한

---
# ipaas에 필요한 사전기술
<img src = "https://user-images.githubusercontent.com/69182192/91016103-31182380-e627-11ea-9004-6535fb154245.png" width="200px"> <br/>
## OAuth <br/>
OAuth는 기존의 쿠키와 세션 기반의 사용자 인증 방식을 보완한 토큰 기반의 인증 방식입니다. <br/><br/>엄밀히 말하면, 사용자 인증을 인가하는 방식이라고 할 수 있습니다<br/>
<br/>
<br/>
<img src = "https://user-images.githubusercontent.com/69182192/91052383-57a48180-e65c-11ea-9b50-f6114d777355.png" width="200px"><br/>
## JWT (JSON Web Tokens) <br/>
JWT는 Json 포맷을 이용하여 사용자에 대한 속성을 저장하는 Claim 기반의 Web Token. <br/><br/>
JWT 토큰은 발급자, 제목 (클레임), 만료 시간 등에 대한 정보를 포함하는 JSON 인코딩 된 데이터 구조.<br/><br/>
변조 및 신뢰성을 위해 서명되며 대칭 또는 비대칭 접근 방식을 사용하여 토큰 정보를 보호하기 위해 암호화 될 수 있음.<br/><br/>
<br/>
<br/>


<img src = "https://user-images.githubusercontent.com/69182192/91053908-802d7b00-e65e-11ea-83d0-69faac3c0749.png" width="200px"> <br/>
## OPENID <br/>
OpenID는 현재 구글 뿐만 아니라 많은 글로벌 플랫폼들이 다른 서비스에게 사용자 인증을 제공을 위해 사용하고 있는 프로토콜<br/><br/>
OpenID Connect는 기본적으로 OAuth 프로토콜을 기반으로 작동하는 프로토콜이기 때문에 기술적으로 사용하는 방법이 매우 유사하지만 사용하는 목적에서는 큰 차이가 있다.<br/><br/>
OPENID는 인증(Authentication)을 위해서 사용하고, OAuth는 인가(Authroization)를 위해서 사용. <br/>
<br/>
<br/>

<img src = "https://user-images.githubusercontent.com/69182192/91016104-31b0ba00-e627-11ea-9ce0-46b82b3fc864.png" width="200px"> <br/>
## REST API <br/>
REST API는 REST 아키텍처의 제약 조건을 준수하는 애플리케이션 프로그래밍 인터페이스입니다.<br/> <br/>REST API를 통해 중요한 데이터를 은행 또는 의료 앱과 같은 모바일 앱에 쉽게 연결할 수있는 iPaaS 솔루션을 사용하면 <br/> 기업이 보다 민첩해져 디지털 비즈니스 가치를 더 빠르고 정확하게 제공 할 수 있습니다. <br/>
<br/>
<br/>

<img src = "https://user-images.githubusercontent.com/69182192/91055351-7ce6bf00-e65f-11ea-8556-4bd20415a99f.png" width="200px"> <br/>
## ODATA (Open Data Protocol) <br/>
OADTA는 단순하고 표준적인 방법으로 쿼리 가능하고 상호 운용 가능한 REST API를 생성하고 사용할 수있는 개방형 프로토콜.

---
# 요약

iPaaS 는 소프트웨어 엔지니어가 응용 프로그램 및 서비스를 배포, 관리 및 통합 할 수있는 클라우드 기반 도구 모음이며,<br/>
하드웨어나 미들웨어를 설치하거나 관리하지 않고도 배포 할 수 있는 통합 플랫폼.

ipaas 통합 플랫폼을 사용하기 위해서는 보안이 생명이므로 사용자인증 및 인가방식인 OAuth, JWT, OPENID에 대해서 살펴보고<br/>
통합을 효율적으로 하기 위한 REST API와 ODATA 대해서 알아봄
