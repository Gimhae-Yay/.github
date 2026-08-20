![](https://github.com/user-attachments/assets/4c68c333-2bf5-46ac-b871-6a8de4a9075c)

<h1 align="center">
로컬스탬프
</h1>
  
<h2 align="center">
예약부터 현장 체크인, 방문 기록 축적까지 올인원 플랫폼
</h2>

<div align="center">
  
[![Java](https://img.shields.io/badge/Java-21-437291?logo=openjdk&logoColor=white)](#)
[![Spring Boot](https://img.shields.io/badge/Spring%20Boot-4.1.0-6DB33F?logo=springboot&logoColor=white)](#)
[![Gradle](https://img.shields.io/badge/Gradle-02303A?logo=gradle&logoColor=white)](#)
[![MySQL](https://img.shields.io/badge/MySQL-8.0-4479A1?logo=mysql&logoColor=white)](#)
[![Redis](https://img.shields.io/badge/Redis-7.4-DC382D?logo=redis&logoColor=white)](#)
[![Flyway](https://img.shields.io/badge/Flyway-CC0200?logo=flyway&logoColor=white)](#)
[![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)](#)
[![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?logo=githubactions&logoColor=white)](#)
[![JaCoCo](https://img.shields.io/badge/Coverage%20Gate-Line%2085%25%20%2F%20Branch%2060%25-brightgreen)](#)

</div>

---

## 프로젝트 개요

> 개발 기간: 2026.07.21 - 2026.08.24

로컬스탬프는 지역 행사와 체험을 예약하고, 현장에서 QR 체크인할 수 있는 서비스입니다. 
운영자는 행사를 등록하고 현장 체크인을 진행하며, 지역 담당자는 행사 심사와 지역 운영을 맡습니다. 
이용자는 스탬프와 미션으로 혜택과 재미를 주어 자연스럽게 지역 행사에 다시 참여할 수 있습니다.

---

## 팀 소개

---

## 주요 기능

![](https://github.com/user-attachments/assets/42ba86f7-52d4-4b25-91d3-b78d73ac5b52)

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

![](https://github.com/user-attachments/assets/3b4e379c-edd0-4af4-a1e5-2f94f6be60de)

---
