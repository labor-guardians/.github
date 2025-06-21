<a href="https://club-project-one.vercel.app/" target="_blank">
<img src="https://github.com/user-attachments/assets/9ff88e7d-c569-4a4d-84b9-881d46f3c13c" alt="배너" width="50%"/>
</a>

<br/>
<br/>

# 0. Getting Started (시작하기)

[서비스 링크](https://labor-lawbot.site/)

<br/>
<br/>

# 1. Project Overview (프로젝트 개요)
- 프로젝트 이름: 노동 Lawbot
- 프로젝트 설명: 노동 법률 정보를 쉽고 빠르게 제공하는 공공데이터 기반 AI 상담 플랫폼

<br/>
<br/>

# 2. Team Members (팀원 및 팀 소개)
| 천지윤 | 최지원 | 이종현 | 최혜림 |
|:------:|:------:|:------:|:------:|
| <img src="https://avatars.githubusercontent.com/u/70828192?v=4" alt="천지윤" width="150"> | <img src="https://avatars.githubusercontent.com/u/128473259?v=4" alt="최지원" width="150"> | <img src="https://avatars.githubusercontent.com/u/127838675?v=4" alt="이종현" width="150"> | <img src="https://avatars.githubusercontent.com/u/94698088?v=4" alt="최혜림" width="150"> |
| FE | FE | BE | BE |
| [GitHub](https://github.com/cheonjiyu) | [GitHub](https://github.com/zziwonCHOI) | [GitHub](https://github.com/2-jjong) | [GitHub](https://github.com/hyeriimm) |

<br/>
<br/>

# 3. Key Features (주요 기능)
- **회원가입**:
  - 회원가입 시 DB에 유저정보가 등록됩니다.

- **로그인**:
  - 사용자 인증 정보를 통해 로그인합니다.

- **노무사 리스트**:
  - 지역을 설정해 내 주변 노무사 리스트를 확인할 수 있습니다.
  - 카테고리별 전문 노무사를 필터링할 수 있습니다. 

- **챗봇**:
  - gpt api와 고용노동부 공공데이터를 활용한 노동 관련 챗봇 기능입니다.
  - 좌측에 지난 채팅 목록을 활인할 수 있습니다.

- **채팅**:
  - 노무사와 사용자와의 채팅이 가능합니다.

- **마이페이지**:
  - 이메일, 프로필 사진, 소개글 수정 가능합니다.


<br/>
<br/>

# 4. Tasks & Responsibilities (작업 및 역할 분담)
|  |  |  |
|-----------------|-----------------|-----------------|
| 천지윤    |  <img src="https://avatars.githubusercontent.com/u/70828192?v=4" alt="천지윤" width="100"> | <ul><li>로그인 개발</li><li>노무사와 채팅 개발</li><li>노무사 리스트</li></ul>     |
| 최지원   |  <img src="https://avatars.githubusercontent.com/u/128473259?v=4" alt="최지원" width="100"> | <ul><li>회원가입 개발</li><li>챗봇 패이지 개발</li><li>마이페이지 개발</li><li>aws 프론트 배포</li></ul> |
| 이종현   |  <img src="https://avatars.githubusercontent.com/u/127838675?v=4" alt="이종현" width="100"> | <ul><li>웹소켓 기반 실시간 채팅 시스템 개발</li><li>노동 법률 자문 AI 챗봇 API 개발</li><li>OpenAI API 연동 및 공공데이터 활용</li><li>ONNX Runtime 임베딩 모델 구현</li></ul> |
| 최혜림    |  <img src="https://avatars.githubusercontent.com/u/94698088?v=4" alt="최혜림" width="100"> | <ul><li>로그인 API 개발</li><li>회원가입 API 개발</li><li>마이페이지 API 개발</li></ul> |

<br/>
<br/>

# 5. Technology Stack (기술 스택)
## 5.1 Language
|  |  |
|-----------------|-----------------|
| HTML5    |<img src="https://github.com/user-attachments/assets/2e122e74-a28b-4ce7-aff6-382959216d31" alt="HTML5" width="100">| 
| CSS3    |   <img src="https://github.com/user-attachments/assets/c531b03d-55a3-40bf-9195-9ff8c4688f13" alt="CSS3" width="100">|
| Javascript    |  <img src="https://github.com/user-attachments/assets/4a7d7074-8c71-48b4-8652-7431477669d1" alt="Javascript" width="100"> | 
| Java    |  <img src="https://github.com/user-attachments/assets/5f30dd1b-4fb3-49c2-abe7-f236e3452ba2" alt="Java" width="100"> | 
| mysql    |  <img src="https://github.com/user-attachments/assets/3770669d-097d-4c40-881e-f2810b423add" alt="mysql" width="100"> | 

<br/>

## 5.2 Frotend
|  |  |  |
|-----------------|-----------------|-----------------|
| React    |  <img src="https://github.com/user-attachments/assets/e3b49dbb-981b-4804-acf9-012c854a2fd2" alt="React" width="100"> | 19.1    |
| daisy UI   |  <img src="https://github.com/user-attachments/assets/8566e5d8-5e22-4b76-b233-f83337d1cc8e" alt="daisy UI" width="100">| 5.0.43   |
| tailwind css   |  <img src="https://github.com/user-attachments/assets/5180ca0f-607b-48a2-86dd-bad54e5db39d" alt="tailwind" width="100">    | 4.1  |

<br/>

## 5.3 Backend
|  |  |  |
|-----------------|-----------------|-----------------|
| Java    |  <img src="https://github.com/user-attachments/assets/5f30dd1b-4fb3-49c2-abe7-f236e3452ba2" alt="Java" width="100"> | 17    |
| Spring Boot    |  <img src="https://github.com/user-attachments/assets/5e25f051-396d-4922-a9b2-d4e4aa10ebaf" alt="Spring Boot" width="100"> | 3.2.5    |
| Spring Data JPA    |  <img src="https://github.com/user-attachments/assets/846d111f-350a-4dd1-a322-3b905259d1a1" alt="Spring JPA" width="100"> | 3.2.5    |
| Spring Security    |  <img src="https://github.com/user-attachments/assets/0e3cba22-3620-48da-899e-ec8d561d875f" alt="Spring Security" width="100"> | 3.2.5    |
| MySQL    |  <img src="https://github.com/user-attachments/assets/3770669d-097d-4c40-881e-f2810b423add" alt="mysql" width="100"> | 8.0    |
| WebSocket    |  <img src="https://github.com/user-attachments/assets/7fa55969-2b2b-47a7-9fbf-5872049b8f1f" alt="WebSocket" width="100"> | 3.2.5    |
| JWT    |  <img src="https://github.com/user-attachments/assets/c122f084-e23f-4462-b8d4-284f9085fe35" alt="JWT" width="100"> | 0.12.3    |
| OpenAI API    |  <img src="https://github.com/user-attachments/assets/745f66c1-7bc9-45e6-9f79-2516639d9039" alt="OpenAI" width="100"> | GPT-4    |
| ONNX Runtime    |  <img src="https://github.com/user-attachments/assets/dbc7b999-6646-4898-8713-845eb6e76659" alt="ONNX" width="100"> | 1.16.3    |

<br/>

## 5.4 Cooperation
|  |  |
|-----------------|-----------------|
| Git    |  <img src="https://github.com/user-attachments/assets/483abc38-ed4d-487c-b43a-3963b33430e6" alt="git" width="100">    |
| Figma  |  <img src="https://github.com/user-attachments/assets/1e937007-637b-4841-b425-eb66b03a0f66" alt="figma" width="100">    |
| Swagger  |  <img src="https://github.com/user-attachments/assets/44024de4-8ff2-4242-97c0-90c0edf9fb0f" alt="swagger" width="100">    |
| Notion    |  <img src="https://github.com/user-attachments/assets/34141eb9-deca-416a-a83f-ff9543cc2f9a" alt="Notion" width="100">    |

<br/>
