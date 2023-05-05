# 👨🏻‍💻 Developers

본 프로젝트는 **개발자 성장 중심의 생태계를 형성**하기 위한 목적으로 진행하였으며, 개발과 관련된 CS 문제풀이 기능과 1:1 멘토링 기능을 웹 서비스 위에서 제공합니다.

<br>

## 👋 About
- 주제: WebRTC를 활용한 영상 채팅 서비스라는 주제를 개발자 성장 중심의 생태계를 만들기 위한 웹 서비스로 확장 및 응용
- 일정: 2023.02 ~ 2023.04
- 인원: 5명

<br>

## 🏆 Awards
카카오 클라우드 스쿨 2기 개발자 과정 **최우수 프로젝트로 선정**되었습니다.

<br>

## 🌟 Main function

- 모든 사용자가 자유롭게 개발과 관련된 다양한 CS 지식을 문제로 출제하고 풀 수 있는 기능을 제공합니다.
- 언택트 환경에서 1:1 멘토링을 진행할 수 있는 화상 회의 공간을 제공합니다. 이때, 화상회의 공간은 WebRTC 상용서비스 `daily.co`를 이용합니다.
- 사용자 개인의 이력 및 경력정보를 작성할 수 있는 이력서 작성 기능을 제공합니다.
- 사용자의 유입을 이끌어내기 위해 포인트 및, 칭호 시스템과 같은 재미요소를 첨가하여 사용자가 이유와 목적을 가지고 서비스를 이용할 수 있도록 개발했습니다.

### 서비스 시연 영상은 [링크](https://drive.google.com/file/d/1SzE9MZmdG3EeFcPES93MCmNSM5gNpXzR/view?usp=sharing)에서 시청하실 수 있습니다.

<br>

## 🏛️ Infra Architecture

<img width="80%" alt="Developers Infra Architecture" src="https://user-images.githubusercontent.com/59594946/236379718-bd7377f4-937b-432e-a1b6-2f0291391ac3.png">

<br>

## 🖥️ Service Architecture

<img width="80%" alt="Developers Service Architecture" src="https://user-images.githubusercontent.com/59594946/236380148-52bac1e9-f294-47bc-a6d4-0fb6e0c77953.png">

<br>

## ☁︎ Cloud Develop Skills and Tools

<table cellpadding="0">
  <tr style="padding: 0">
    <td valign="top"><img height="300" src="https://user-images.githubusercontent.com/59594946/236382322-db998485-88e9-4179-b025-17327009a7ca.png"/></td>
    <td valign="top"><img height="300" src="https://user-images.githubusercontent.com/59594946/236382346-ed3742e8-4977-4353-b7c9-0752175b8323.png"/></td>
  </tr>
</table>

- **AWS Tools**: EKS(Ingress, Service, Deployment, Pod), EC2, S3, Route53, ACM, Cloud Watch

<br>

## 🛠️ Application Develop Skills and Tools

<table cellpadding="0">
  <tr style="padding: 0">
    <td valign="top"><img height="200" src="https://user-images.githubusercontent.com/59594946/236380560-e8f8fcec-cb6e-4682-a399-5b22b4842273.png"/></td>
    <td valign="top"><img height="200" src="https://user-images.githubusercontent.com/59594946/236380712-b02737bb-d035-453a-8b50-14196fb71682.png"/></td>
    <td valign="top"><img height="200" src="https://user-images.githubusercontent.com/59594946/236381323-028dc35c-188c-4cf7-a9b7-7226cea69595.png"/></td>
  </tr>
</table>

- **Presentation Tier**: TypeScript, React, Nginx
- **Application Tier**: Java, Spring Boot, Gradle, Lombok, JUnut5, Mockito, Querydsl, JWT, RabbitMQ, Spring Security, Spring Data JPA, Spring Rest Docs
- **Data Tier**: MariaDB, Redis
- **CI/CD**: Jenkins, ArgoCD, Github, Docker
- **etc**: IntelliJ, VSCode, ERD Cloud, Notion, Slack, Figma

<br>

## 📝 API Specification

<img width="80%" alt="Developers API Specification" src="https://user-images.githubusercontent.com/59594946/236383710-84a1c8c9-4138-43ea-b524-538a213aba3c.png">

- Member(사용자) API 명세서: [링크](https://diveloper.site/docs/member/index.html)에서 확인하실 수 있습니다.
  - [Github 주소](https://github.com/kcs-developers/developers-member/blob/main/src/main/resources/static/docs/member/index.html)
- Solve(문제풀이) API 명세서: [링크](https://diveloper.site/docs/solve/index.html)에서 확인하실 수 있습니다.
  - [Github 주소](https://github.com/kcs-developers/developers-solve/blob/main/src/main/resources/static/docs/solve/index.html)
- Live(멘토링) API 명세서: [링크](https://diveloper.site/docs/live/index.html)에서 확인하실 수 있습니다.
  - [Github 주소](https://github.com/kcs-developers/developers-live/blob/main/src/main/resources/static/docs/live/index.html)


<br>

## 👥 Member

|이름|역할|Github|
|:--:|:--:|:--:|
|문태준|- 팀 리드 <br> - 사용자 인증 시스템 개발 <br> - AWS EKS Cluster 및 Managed 서비스 연동 <br> - CI/CD 파이프라인 구축|[lango](https://github.com/Jooney-95)|
|강지덕|- daily.co 연동 서비스 개발 <br> - 메시지 브로커를 이용한 알림 서비스 개발|[paduck-96](https://github.com/paduck-96)|
|김지수|- 멘토링 1:1 예약 서비스 개발 <br> - AWS RDS 및 Redis DB 연동 및 최적화|[soojik](https://github.com/soojik)|
|윤태호|- 문제풀이 서비스 검색 기능(동적쿼리) 개발|[EagerProgrammer](https://github.com/EagerProgrammer)|
|이정엽|- 문제풀이 답안 검증 시스템 개발 <br> - S3 파일 업로드 프로세스 구축|[ITfervor](https://github.com/ITfervor)|

