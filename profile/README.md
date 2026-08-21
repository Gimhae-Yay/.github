![](https://github.com/user-attachments/assets/ffb3474b-e29a-4e8a-9b05-954da733f607)

<h1 align="center">로컬스탬프</h1>
  
<h2 align="center">
예약부터 현장 체크인, 방문 기록 축적까지 연결하는 지역 참여형 스탬프·리워드 플랫폼
</h2>

<p align="center">
  <strong>프론트엔드</strong><br><br>
  <img alt="React" src="https://img.shields.io/badge/React-61DAFB?logo=react&logoColor=black">
  <img alt="TypeScript" src="https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white">
  <img alt="Vite" src="https://img.shields.io/badge/Vite-646CFF?logo=vite&logoColor=white">
  <img alt="React Router" src="https://img.shields.io/badge/React_Router-CA4245?logo=reactrouter&logoColor=white">
  <img alt="Tailwind CSS" src="https://img.shields.io/badge/Tailwind_CSS-06B6D4?logo=tailwindcss&logoColor=white">
  <img alt="Vitest" src="https://img.shields.io/badge/Vitest-6E9F18?logo=vitest&logoColor=white">
</p>

<p align="center">
  <strong>백엔드</strong><br><br>
  <img alt="Java 21" src="https://img.shields.io/badge/Java_21-437291?logo=openjdk&logoColor=white">
  <img alt="Spring Boot" src="https://img.shields.io/badge/Spring_Boot-6DB33F?logo=springboot&logoColor=white">
  <img alt="Spring Security" src="https://img.shields.io/badge/Spring_Security-6DB33F?logo=springsecurity&logoColor=white">
  <img alt="Spring Data JPA" src="https://img.shields.io/badge/Spring_Data_JPA-6DB33F?logo=spring&logoColor=white">
  <img alt="Flyway" src="https://img.shields.io/badge/Flyway-CC0200?logo=flyway&logoColor=white">
</p>

<p align="center">
  <strong>데이터 · 외부 연동 · 검증 및 운영</strong><br><br>
  <img alt="MySQL" src="https://img.shields.io/badge/MySQL-4479A1?logo=mysql&logoColor=white">
  <img alt="Redis" src="https://img.shields.io/badge/Redis-DC382D?logo=redis&logoColor=white">
  <img alt="PortOne" src="https://img.shields.io/badge/PortOne-결제_연동-4B6BFB">
  <img alt="AWS S3" src="https://img.shields.io/badge/AWS_S3-569A31?logo=amazons3&logoColor=white">
  <br><br>
  <img alt="JUnit" src="https://img.shields.io/badge/JUnit-25A162?logo=junit5&logoColor=white">
  <img alt="Testcontainers" src="https://img.shields.io/badge/Testcontainers-2496ED?logo=docker&logoColor=white">
  <img alt="JaCoCo" src="https://img.shields.io/badge/JaCoCo-Coverage-9B4F96">
  <img alt="Actuator" src="https://img.shields.io/badge/Actuator-6DB33F?logo=springboot&logoColor=white">
  <img alt="GitHub Actions" src="https://img.shields.io/badge/GitHub_Actions-2088FF?logo=githubactions&logoColor=white">
</p>

<p align="center">
  🚀 <a href="https://서비스-주소">서비스 체험하기</a> ·
  ⚙️ <a href="https://github.com/Gimhae-Yay/Regional-Event-Platform-Backend">백엔드</a> ·
  🎨 <a href="https://github.com/Gimhae-Yay/local-stamp-front">프론트엔드</a>
</p>

---

## 프로젝트 개요

> 개발 기간: 2026.07.21 - 2026.08.24

로컬스탬프는 지역 행사와 체험을 탐색·예약하고,
현장에서 QR로 체크인한 뒤 방문 기록을 스탬프와 미션 혜택으로 이어갈 수 있는 서비스입니다.

---

## 주요 기능

![](https://github.com/user-attachments/assets/59a0cf74-fe7f-4054-b351-d60360c4e81e)

<details>
<summary>🗺 원하는 지역의 행사를 확인할 수 있습니다</summary>
  
- 원하는 지역을 선택하면 해당 지역의 행사와 체험만 볼 수 있습니다.
- 남은 자리와 예약 가능 여부는 항상 최신 상태로 표시되어 마감된 행사가 "예약 가능"으로 보이지 않습니다.
  
</details>

<details>
<summary>⏳ 예약 확정 전까지 10분간 안전하게 확보됩니다</summary>

- 결제 완료 전까지 선택한 좌석을 10분간 임시로 확보해 놓습니다.
- 마지막 한 자리에 여러 명이 동시에 예약을 해도 예약은 한 명만 할 수 있습니다.

</details>

<details>
<summary>📱 체크인용 QR은 5분간 유효합니다</summary>

- 미리 캡처한 QR로는 입장할 수 없습니다. 현장에서 바로 발급해서 사용해야 합니다.
- 한 예약에 입장은 한 번만 처리합니다. QR을 여러 번 스캔해도 방문 기록은 갱신되지 않습니다.
- QR 스캔이 되지 않는 경우 예약번호로 수동 체크인이 가능합니다.

</details>

<details>
<summary>✍️ 체크인이 확인된 방문자만 후기 작성이 가능합니다</summary>

- 체크인이 확인된 방문에만 후기 한 건을 작성할 수 있습니다.  (별점 1~5, 최대 2,000자)
- 후기 등록 후 30일 안에는 수정 가능하며 삭제는 언제든 가능합니다. 삭제하면 30일동안 보존 후에 완전히 파기합니다.
 
</details>

<details>
<summary>🏷 모든 행사가 바로 공개되지는 않습니다</summary>

- 운영자가 등록하면 지역 담당자가 심사하고, 정해둔 시각에 자동으로 공개됩니다.
- 공개된 이후에 수정을 하는 경우에는 다시 심사받아야하며, 심사가 통과되기 전까지 원본 내용이 유지됩니다.
 
</details>

<details>
<summary>💳 결제가 완료되면 예약이 확정됩니다</summary>

- 자리를 잡아둔 상태에서만 결제할 수 있고, 금액은 그 시점 가격으로 고정됩니다.
- 결제 성공 여부는 서버가 결제사에 확인하여 처리합니다.
- 쿠폰으로 최종 금액이 0원이 되면 결제 없이 바로 예약이 확정됩니다.
- 취소·환불은 전액 기준으로 한 건으로 처리됩니다. 현재 부분 환불은 제공되지 않습니다.
 
</details>

<details>
<summary>🎟 여러 번 방문 시 혜택을 받을 수 있습니다</summary>
  
- 방문이 쌓아 미션을 달성하고 스탬프를 모아 할인 쿠폰을 받습니다.
- 같은 방문으로 여러 번 적립되지 않습니다.
 
</details>

### 역할별 주요 기능

![](https://github.com/user-attachments/assets/509f04be-5483-4d2d-85d4-746b80272ff7)

> 이용자: 탐색·예약·체크인·리워드 / 운영자: 행사 등록·현장 체크인 / 지역 담당자: 행사 심사·지역 운영

---

## 아키텍처

![](https://github.com/user-attachments/assets/6986a806-6e97-4090-99d8-f8c803bd6b66)

---

## 팀 소개

|  팀원                                                   |  담당                                       |
|---------------------------------------------------------|---------------------------------------------|
|  [@Astro-Luminoso](https://github.com/Astro-Luminoso)   | 콘텐츠 관리자, 스탬프, 인프라, CI/CD          |
|  [@kolyn092](https://github.com/kolyn092)               | 예약, 결제, 환불, 정합성 및 성능 검증         |
|  [@minkim11](https://github.com/minkim11)               | 인증·인가, 회원, 쿠폰                        |
|  [@devdong1231](https://github.com/devdong1231)         | 콘텐츠, 미션, 프론트엔드                     |

---

## 팀 개발 원칙

- API 계약, 구현, 테스트, 배포 상태를 구분해 관리합니다.
- 예약·결제·체크인처럼 데이터 정합성이 중요한 기능은 상태 전이와 예외 흐름까지 검증합니다.
- 비밀값은 저장소에 기록하지 않고 환경변수와 비밀 관리 수단으로 주입합니다.
- 기술 선택과 변경 이유는 ADR, Issue, Pull Request 등 근거와 함께 남깁니다.
- 확인하지 못한 범위는 완료로 표현하지 않고 후속 검증 항목으로 기록합니다.

---
