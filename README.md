# 방문 요양 고객관리 ERP OnCare

<p align="center">
  <img width="1430" height="806" alt="image" src="https://github.com/Ace-Time/be19-final-A-Team/blob/main/img/%EB%A9%94%EC%9D%B8%EC%82%AC%EC%A7%84/%EB%B0%A9%EB%AC%B8%EC%9A%94%EC%96%91%20%EB%A9%94%EC%9D%B8%EC%82%AC%EC%A7%84.jpg" />
</p>


<h1>현장 중심의 요양 서비스 운영을 위한 올인원 관리 솔루션</h1>

> 수급자, 요양보호사, 방문 일정, 직원, 용품, 업무 현황을 하나의 시스템에서 통합 관리할 수 있는 방문 요양 전용 ERP입니다.<br/>
현장의 실제 업무 흐름을 기반으로 설계되어, 반복적인 행정 업무를 줄이고 운영 효율을 높이며 안정적인 요양 서비스 제공을 지원합니다.

---

## 😊 조원 소개

<table style="width:100%;">
  <thead>
    <tr align="center">
      <th>팀원</th>
      <th>팀원</th>
      <th>팀원</th>
      <th>팀원</th>
      <th>팀원</th>
      <th>팀원</th>        
    </tr>
  </thead>
  <tbody>
    <tr align="center">
      <td>
        <a href="https://github.com/kjin0204" target="_blank">
          <img src="https://github.com/Ace-Time/be19-final-A-Team/blob/main/img/%EA%B0%9C%EC%9D%B8%EC%9D%B4%EB%AF%B8%EC%A7%80/%EA%B0%95%ED%98%95%EA%B7%9C.png" width="210" style="border-radius:100%" alt="강형규"/><br/>
          <b>강형규</b>
        </a>
      </td>
      <td>
        <a href="https://github.com/Yunji458" target="_blank">
          <img src="https://github.com/Ace-Time/be19-final-A-Team/blob/main/img/%EA%B0%9C%EC%9D%B8%EC%9D%B4%EB%AF%B8%EC%A7%80/%EA%B9%80%EC%9C%A4%EC%A7%80.png" width="210" style="border-radius:100%" alt="김윤지"/><br/>
          <b>김윤지</b>
        </a>
      </td>
      <td>
        <a href="https://github.com/woo-kyoung-nam" target="_blank">
          <img src="https://github.com/Ace-Time/be19-final-A-Team/blob/main/img/%EA%B0%9C%EC%9D%B8%EC%9D%B4%EB%AF%B8%EC%A7%80/%EB%82%A8%EC%9A%B0%EA%B2%BD.png" width="210" style="border-radius:100%" alt="남우경"/><br/>
          <b>남우경</b>
        </a>
      </td>
      <td>
        <a href="https://github.com/seoguhoe2" target="_blank">
          <img src="https://github.com/Ace-Time/be19-final-A-Team/blob/main/img/%EA%B0%9C%EC%9D%B8%EC%9D%B4%EB%AF%B8%EC%A7%80/%EB%B0%B1%EC%A4%80%EC%8A%B9.png" width="210" style="border-radius:100%" alt="백준승"/><br/>
          <b>백준승</b>
        </a>
      </td>
      <td>
        <a href="https://github.com/leejaeguen" target="_blank">
          <img src="https://github.com/Ace-Time/be19-final-A-Team/blob/main/img/%EA%B0%9C%EC%9D%B8%EC%9D%B4%EB%AF%B8%EC%A7%80/%EC%9D%B4%EC%9E%AC%EA%B7%BC.png" width="210" style="border-radius:100%" alt="이재근"/><br/>
          <b>이재근</b>
        </a>
      </td>
      <td>
        <a href="https://github.com/LeeHyeunSoo" target="_blank">
          <img src="https://github.com/Ace-Time/be19-final-A-Team/blob/main/img/%EA%B0%9C%EC%9D%B8%EC%9D%B4%EB%AF%B8%EC%A7%80/%EC%9D%B4%ED%98%84%EC%88%98.png" width="210" style="border-radius:100%" alt="이현수"/><br/>
          <b>이현수</b>
        </a>
      </td>
    </tr>
  </tbody>
</table>

---

**📜 목차**

[**💡 Tech Stack**](#-Tech-Stack)

[**📌 프로젝트 수립 배경**](#-프로젝트-수립-배경)

[**📊 사용자 설문 조사 및 피드백**](#-사용자-설문-조사-및-피드백)

[**📢 프로젝트 설명**](#-프로젝트-설명)

[**🛠️ 주요 기능**](#️-주요-기능)

[**📄 WBS**](#-WBS)

[**🙆‍♀️ 요구사항 명세서**](#️-요구사항-명세서)

[**💭 DDD 설계**](#-DDD-설계)

[**🗃️ DB 모델링**](#️-DB-모델링)

[**🛜 AWS 배포 전략**](#-AWS-배포-전략)

[**🚩 성능 개선과 모니터링 전략**](#-성능-개선과-모니터링-전략)

[**🍪 개인 회고록**](#-개인-회고록)

---

## 💡 Tech Stack
### 🌿 Backend
![Spring](https://img.shields.io/badge/Spring-6DB33F?style=for-the-badge&logo=spring&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)
![Spring Security](https://img.shields.io/badge/Spring_Security-6DB33F?style=for-the-badge&logo=springsecurity&logoColor=white)
![Spring Data JPA](https://img.shields.io/badge/Spring_Data_JPA-6DB33F?style=for-the-badge)
![Gradle](https://img.shields.io/badge/Gradle-02303A?style=for-the-badge&logo=gradle&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=JSON%20web%20tokens&logoColor=white)
![Hibernate](https://img.shields.io/badge/Hibernate-59666C?style=for-the-badge&logo=hibernate&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Python](https://img.shields.io/badge/PYTHON-blue?style=for-the-badge&logo=python&logoColor=white)

### 🌿 Frontend
![Vue.js](https://img.shields.io/badge/Vue.js-4FC08D?style=for-the-badge&logo=vue.js&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![Axios](https://img.shields.io/badge/Axios-5A29E4?style=for-the-badge)
![Vue Router](https://img.shields.io/badge/Vue_Router-4FC08D?style=for-the-badge)
![Vuetify](https://img.shields.io/badge/Vuetify-1867C0?style=for-the-badge)

### 🗃️ Database
![MariaDB](https://img.shields.io/badge/MariaDB-003545?style=for-the-badge&logo=mariadb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)

### 🛠️ Tools
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)
![Figma](https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white)
![Discord](https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)

### 🏗️ Infrastructure
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white)
![MySQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white)
![Grafana Loki](https://img.shields.io/badge/Grafana_Loki-F46800?style=for-the-badge&logo=grafana&logoColor=white)

---

## 📌 프로젝트 수립 배경

대한민국은 초고령사회로 진입하며 노인 인구가 빠르게 증가하고 있고, 이에 따라 요양 서비스 수요 또한 지속적으로 확대되고 있습니다.  
그러나 요양 시설의 수용 인원은 한계가 있어, 재가 요양(방문 요양)이 주요 대안으로 제시되고 있으며 정부 역시 재가 요양 서비스 확대 정책을 추진하고 있습니다.

이와 함께 관리해야 할 수급자와 요양보호사 인원이 증가하면서, 방문 요양 기관의 운영 효율을 높이기 위한 **전용 ERP 시스템의 필요성**이 점점 커지고 있습니다.  
하지만 실제 현장에서 사용되는 기존 ERP 시스템은 사용자 환경과 업무 흐름을 충분히 반영하지 못해, 도입 효과가 제한적이라는 문제점이 존재합니다.

이에 본 프로젝트는 **현장 중심의 방문 요양 고객관리 ERP 시스템(OnCare)**을 기획·개발하여, 실제 사용자에게 도움이 되는 실질적인 운영 도구를 제공하는 것을 목표로 시작되었습니다.

---

### 문제 정의

#### 1. 기존 ERP 시스템의 낮은 사용성
- 현장에서 사용 중인 ERP의 UI가 실질 사용자에게 적합하지 않아 사용 빈도가 낮음  
- 그로 인해 ERP 도입 효과가 충분히 발휘되지 못하는 상황 발생

#### 2. 요양보호사를 고려하지 않은 기능 구성
- 실제 주요 사용자인 요양보호사에게 필요한 기능이 부족
- 비교적 높은 연령대의 요양보호사들에게 ERP 사용 자체가 어렵고 부담으로 작용

#### 3. 고객 맞춤 관리의 한계
- 수급자 개개인의 병력, 위험 요소, 특이사항 등을 체계적으로 관리하기 어려움
- 기존 시스템에서는 고객별 맞춤 관리가 구조적으로 제한됨

---

### 솔루션 제안

#### 1. 사용자 중심 UI/UX 설계
- 직관적이고 단순한 화면 구성으로 고령 종사자도 쉽게 사용 가능하도록 개선
- 불필요한 복잡성을 제거하고 핵심 기능 위주로 재구성

#### 2. 요양보호사 맞춤 기능 제공
- 요양 기록 **AI 요약 기능**을 통해 인수인계 및 기록 부담 감소
- 수급자별 위험 등급 제공으로 현장 판단을 돕는 정보 시각화
- 요양보호사의 사용 경험 개선을 통해 서비스 품질 향상

#### 3. 고객 맞춤형 관리 시스템 구축
- 수급자별 특이사항, 병력, 위험 요소를 체계적으로 관리
- 개인 맞춤 관리 기반으로 서비스 만족도 향상 및 이탈 방지
- 체계적인 고객 관리를 통해 잠재 고객 유치 기반 마련

---

### 현장 설문 조사 결과

본 프로젝트는 **현재 근무 중인 요양보호사 20명을 대상으로 한 설문 조사**를 바탕으로 기획되었습니다.

**Q1. 현재 사용 중인 ERP에 대해 불편함을 느끼고 계신가요?**
- 불편함을 느낀다: **12명**
- 잘 모르겠다: 2명
- 편하게 사용하고 있다: 6명

**Q2. ERP 사용 시 가장 개선이 필요하다고 느끼는 부분은 무엇인가요?**
- 기능 부족: **8명**
- UI 개선 필요: **11명**
- 기능이 너무 복잡함: 3명

**Q3. ERP 개선에 대한 자유 의견**

> “상담 업무를 병행하는 경우가 많은데 관련 기능이 없어 불편했다.”  
> “화면이 너무 복잡해서 보기에도 이쁘지 않고 사용하기 힘들다.”  
> “특정 기능을 직관적으로 찾기 어려워 따로 ERP를 공부해야 하는 느낌이었다.”

## 📊 사용자 설문 조사 및 피드백

본 설문 조사는 **OnCare 서비스 기획 및 기능 개선을 위해 "실제 요양보호사 및 관계자를 대상" 으로 진행**되었습니다.

---

### Q1. OnCare에서 가장 도움이 될 것 같은 기능은 무엇인가요?

- 일정 관리: 1명  
- 직원 관리: **4명**  
- 수급자 관리: 2명  
- 고객 관리: **7명**  
- 용품 관리: 2명  
- 업무 관리: 0명  
- 요양보호사 페이지: **4명**

👉 **고객 관리, 직원 관리, 요양보호사 페이지**에 대한 기대가 가장 높게 나타났습니다.

---

### Q2. OnCare에서 가장 개선이 필요하다고 느낀 부분은 무엇인가요?

- 일정 관리: 0명  
- 직원 관리: **7명**  
- 수급자 관리: 1명  
- 고객 관리: 2명  
- 용품 관리: 0명  
- 업무 관리: **9명**  
- 요양보호사 페이지: 1명  

👉 **업무 관리와 직원 관리 영역의 개선 요구가 가장 높았습니다.**

---

### Q3. OnCare에 대한 자유 의견

> “실제 사용하려면 공단 시스템과 연계돼야 하는데, 그 부분이 없어 아쉬웠다.”  
> “수급자에서 위험 등급이 산정되는 게 알아보기 좋고, AI 요약 기능도 신기했다.”  
> “가입을 안 한 고객에 대해 상담 대처가 쉬워질 것 같아 신선하고 좋았다.”

---

### 설문 결과 요약

- **고객 관리 기능에 대한 기대가 가장 높았으며**,  
  이는 기존 ERP에서 다루기 어려웠던 잠재 고객 관리, 상담 흐름 관리에 대한 니즈가 크다는 것을 보여줍니다.
- **업무 관리와 직원 관리 영역의 개선 요구가 높아**,  
  현장에서 실제로 체감하는 업무 피로도가 이 영역에 집중되어 있음을 확인할 수 있었습니다.
- AI 요약, 위험 등급 시각화 등 **OnCare의 차별화 기능에 대한 긍정적 반응**도 확인되었습니다.

---

## 📢 프로젝트 설명

### 1. 프로젝트 주제

**방문 요양 고객관리 ERP 시스템 – OnCare**

---

### 2. 프로젝트 개요

OnCare는 방문 요양 기관의 운영 효율을 높이기 위해 기획·개발된 **현장 중심 요양 고객관리 ERP 시스템**입니다.  
수급자 관리, 요양보호사 관리, 일정 배정, 매칭, 근무 기록, 물품 관리 등  
방문 요양 운영에 필요한 모든 기능을 하나의 시스템에서 통합 관리할 수 있도록 설계되었습니다.

기존 요양 ERP의 낮은 사용성과 복잡한 UI, 현장 흐름과 맞지 않는 기능 구성 문제를 해결하기 위해  
**실제 요양보호사 인터뷰 및 설문 조사 결과를 기반으로 기획**되었으며,  
고령 종사자도 쉽게 사용할 수 있는 직관적인 UI와 실무 중심 기능 제공을 목표로 합니다.

또한 고객(수급자) 개개인의 병력, 위험 요소, 특이사항을 체계적으로 관리하고,  
요양 기록 AI 요약, 위험 등급 시각화, 맞춤 매칭 기능 등을 통해  
**요양보호사의 업무 부담을 줄이고 서비스 품질을 향상시키는 것**을 핵심 목표로 합니다.

---

## 🛠️ 주요 기능

### 1. 직원 관리

- 직원 개개인의 **전자 결재 기능**
- 자격증 만료 알림 및 관리 기능
- 직원 정보, 근무 상태, 이력 관리 기능 제공

---

### 2. 수급자 관리

- 수급자 정보 통합 관리 (기본 정보, 병력, 특이사항 등)
- **장기 요양 등급 만료 알림, 청구서 수신 알림** 등 다양한 알림 제공
- 수급자 요청에 맞는 **맞춤 요양보호사 추천 매칭 기능**

---

### 3. 요양보호사 관리

- 요양보호사 **일정 관리 및 근무 스케줄 관리**
- 수급자별 **위험 등급 및 위험 요소 정보 제공**
- 요양 기록 **AI 요약 기능 제공**으로 인수인계 및 기록 업무 효율화

---

### 4. 물품 관리

- 렌탈 물품 계약 관리 및 상태 관리
- 물품 히스토리 기반 **예상 이익 분석 및 인사이트 제공**
- 물품 분실, 회수, 교체 이력 관리

---

### 5. 고객 관리

- 가입 상담 시 고객 상태에 따른 **맞춤 정보 제공**
- 이탈 고객에 대한 사유 저장 및 관리
- 고객 정보 변화에 따른 **주기적인 인텐션 분석 및 알림 제공**
- 이탈 징후 감지 후 대응 솔루션 제공

---

## 📄 WBS

🔗 [WBS 바로가기](https://docs.google.com/spreadsheets/d/1_9muPoG2TCygdrsBb2QGj5fwmSjnReSOMnvmmsylSCk/edit?gid=1154634314#gid=1154634314)

---

## 🙆‍♀️ 요구사항 명세서

🔗 [요구사항 명세서 바로가기](https://docs.google.com/spreadsheets/d/1_9muPoG2TCygdrsBb2QGj5fwmSjnReSOMnvmmsylSCk/edit?gid=0#gid=0)

---

## 💭 DDD 설계

**1. Domain Event Storming**

![](https://github.com/Ace-Time/be19-final-A-Team/blob/main/img/DDD/DDD.png)

---

## 🗃️ DB 모델링

![](https://github.com/Ace-Time/be19-final-A-Team/blob/main/img/ERD/erd%20cloud.png)

---

## 🛜 AWS 배포 전략

![](https://github.com/Ace-Time/be19-final-A-Team/blob/main/img/AWS%20%EB%B0%B0%ED%8F%AC%20%EC%A0%84%EB%9E%B5/1.png)
![](https://github.com/Ace-Time/be19-final-A-Team/blob/main/img/AWS%20%EB%B0%B0%ED%8F%AC%20%EC%A0%84%EB%9E%B5/2.png)

---

## 🚩 성능 개선과 모니터링 전략

![](https://github.com/Ace-Time/be19-final-A-Team/blob/main/img/%EC%84%B1%EB%8A%A5%20%EA%B0%9C%EC%84%A0%EA%B3%BC%20%EB%AA%A8%EB%8B%88%ED%84%B0%EB%A7%81%20%EC%A0%84%EB%9E%B5/1.png)
![](https://github.com/Ace-Time/be19-final-A-Team/blob/main/img/%EC%84%B1%EB%8A%A5%20%EA%B0%9C%EC%84%A0%EA%B3%BC%20%EB%AA%A8%EB%8B%88%ED%84%B0%EB%A7%81%20%EC%A0%84%EB%9E%B5/2.png)
![](https://github.com/Ace-Time/be19-final-A-Team/blob/main/img/%EC%84%B1%EB%8A%A5%20%EA%B0%9C%EC%84%A0%EA%B3%BC%20%EB%AA%A8%EB%8B%88%ED%84%B0%EB%A7%81%20%EC%A0%84%EB%9E%B5/3.png)
![](https://github.com/Ace-Time/be19-final-A-Team/blob/main/img/%EC%84%B1%EB%8A%A5%20%EA%B0%9C%EC%84%A0%EA%B3%BC%20%EB%AA%A8%EB%8B%88%ED%84%B0%EB%A7%81%20%EC%A0%84%EB%9E%B5/4.png)

---

## 😊 개인 회고록

**🍪 개인 회고록 - 강형규**

**자체 평가**

- 언어의 장벽을 넘어선 본질적 깨달음: 초기에는 Java 고유의 라이브러리와 문법, 형변환 등에 적응하는 데 어려움이 있었지만 학습과 구현을 반복하며 "프로그래밍 언어(C#, Java, JS)는 결국 도구일 뿐, 객체지향의 원리와 논리적 사고는 동일하다"는 것을 깨달을 주는 프로젝트였습니다.
- JPA(ORM)의 이해: SQL 중심적 사고에서 벗어나 객체 중심의 패러다임인 JPA에 익숙해지며 생산성과 유지보수성을 높였고 ORM 활용에 익숙 해 질수있었습니다.
- 인프라 및 아키텍처 구축 (Architecture & DevOps)
단순히 배운 내용을 따라 하기만 한게 아닌 cost를 낮추기 위해 natgateway 대신 instance를 사용하는등 AWS를 다양하게 활용 해보고 사용 해 볼 수 있는 좋은 경험 이였습니다.

---

**🍪 개인 회고록 - 김윤지**

**자체 평가**

- 개발이라는 도구가 실제 사용자의 삶에 어떻게 녹아들어야 하는지를 진지하게 고민하며 시작한 이 여정은 기술의 본질을 깊이 이해하는 귀중한 시간이었습니다. 단순한 기능 구현을 넘어 백엔드의 데이터 안정성과 프론트엔드의 사용성이 조화를 이룰 때 비로소 가치 있는 서비스가 완성된다는 것을 체득했습니다.
가장 중점을 둔 부분은 요양보호사분들의 업무 동선을 최소화하는 것이었습니다. 현장의 바쁜 흐름을 고려해 출근 → 퇴근 → 일지 작성으로 이어지는 과정을 버튼 하나에 담아냈습니다. 버튼의 상태가 상황에 따라 유연하게 변하며 다음 할 일을 자연스럽게 안내하도록 설계했고 이 과정에서 사용자가 기능을 찾아 헤매지 않게 만드는 것이 진정한 편의성임을 깨달았습니다.
기술적인 완성도를 높이는 과정도 뜻깊었습니다. AI 요약 처리 시 발생하는 시스템 지연을 비동기 방식으로 해결해 쾌적한 환경을 만들고 복잡하게 얽힌 일정들을 화면에 나란히 정렬하는 로직을 고민하며 문제를 논리적으로 풀어내는 즐거움을 느꼈습니다. 특히 설계의 빈틈을 발견하고 구조를 다시 잡아나갔던 경험은 눈에 보이는 UI만큼이나 보이지 않는 탄탄한 기초 데이터가 얼마나 중요한지 가르쳐준 값진 교훈이었습니다.
협업에서도 큰 배움이 있었습니다. 동료와 약속한 데이터 형식이 어긋나 발생하는 에러를 마주하고 예기치 못한 코드 충돌을 해결하며 소통의 무게를 배웠습니다. 명확한 API 명세와 소통은 단순한 정보 교환이 아니라 서로에 대한 신뢰와 약속이라는 것을 알게 되었습니다. 어려움 앞에서 도망치지 않고 끝까지 파고들어 문제를 해결해낸 시간은 제게 어떤 기술적 난관도 결국 이겨낼 수 있다는 단단한 자신감을 주었습니다.
결국 백엔드의 신뢰도가 프론트엔드의 편리함을 지탱한다는 서비스의 본질을 배운 여정이었습니다. 이번 경험을 발판 삼아 앞으로도 사용자에게 실질적인 도움을 줄 수 있는 견고하고 친절한 시스템을 만드는 개발자로 성장해 나가겠습니다.

---

**🍪 개인 회고록 - 남우경**

**자체 평가**

- 1차 데이터베이스부터, 백엔드, 프론트, 데브옵스 프로젝트를 거쳐 배운 기술을 모두 활용해 최종 프로젝트도 마무리 하는 단계까지 오며 개발 흐름, DB 모델링, 개발 능력 등 모든 측면에서 한단계 성장했습니다. 좋은 팀원들과 훌륭한 강사님 덕에 많은 언덕을 넘을 수 있었다고 생각합니다. 
최종 프로젝트에서는 고객 관리 ERP를 카테고리로 정하고, 요양보호사와 수급자에 관해 주제로 설정하였습니다. 제가 맡은 수급자 관리 파트에서는 수급자를 고객으로 생각하여 관리자가 수급자의 모든 정보를 시각적으로 한눈에 확인할 수 있도록 하는 것이 가장 큰 핵심이었습니다. 세세한 기능으로 수급자의 기본정보, 일정, 서비스내역, 요양일지 및 평가내용, 상담내용, 문의이력, 서류관리, 장기요양등급 만료예정인 수급자 등 많은 기능을 다루어야 했습니다. 그렇기 때문에 다른 팀원들의 개발파트에서도 조금씩 관여를 하며 정확하고 완벽한 기능을 구현하도록 노력했습니다. 특히 위험요소, 서비스 유형, 렌탈과 같은 부분은 백엔드에서 날짜 기준으로 금액 및 점수로 산정하여 원하는 집계 결과를 나올 수 있게 로직을 구현했습니다. 위험요소 같은 경우엔 점수를 기준으로 저/중/고위험 등급으로 나누었고, 서비스 유형-렌탈과 같은 경우엔 현재날짜 기준으로 금액을 산정하여 수급자의 총 서비스 내역으로 도출하였습니다. MyBatis를 활용해 이러한 로직을 구현하다보니 처음엔 복잡했지만, 점점 자신감이 생겼습니다.
또한 평소에도 AI를 활용하여 개발을 경험하고 싶었는데 좋은 기회로 이번 프로젝트에서 일일 요양일지에 대해 월별로 AI 요약 기능을 구현해 보았습니다. LLM을 사용해 프롬프트를 작성하고, Open API를 호출하며 백엔드와의 통신을 위해 Fast API를 설정하는 등 너무 좋은 경험이 되었습니다. LLM을 처음 활용하면서 느낀점은 Open API와 백엔드 호출은 수월했으나 프롬프트를 기존 데이터 정합성과 맞게 작성하는 것이 중요하다는 것을 깨달았습니다. 프롬프트를 자세하게 작성하지 않으면 AI가 자신의 추론대로 요약을 했기 때문입니다.
이처럼 한화비욘드 부트캠프에서 여러 프로젝트를 거치면서 DB모델링, 백엔드와 프론트엔드 개발 실력, LLM을 활용한 AI 기술 등 많은 것을 얻어갈 수 있어서 전체적인 측면에서 레벨 업을 할 수 있던 것 같습니다.

---

**🍪 개인 회고록 - 백준승**

**자체 평가**

- Keep
- 이전 프로젝트에서는 RAG라는 새로운 기능에 도전했다면, 이번 프로젝트에서는 CRM이라는 새로운 시스템에 도전해봤다. 새로운 기능에 대한 학습보다 새로운 시스템에 대한 학습이 참 방대하고 어려운 영역이라는 걸 이번에 직접 체감할 수 있었다. 짧은 기간이었지만 CRM을 확실히 이해할 수 있는 One step이었다고 생각됐고 이런 도전적인 시도를 계속핸나가야 겠다고 생각했다.
- Problem
- 도입하는 시스템의 안정성을 너무 고려해서인지 이번엔 오히려 새로운 기술 도입에 있어 너무 인색했던 문제가 있었다. 프로젝트를 진행할 때는 안정적인 시스템 구축을 위해 과한 시도를 자제하는 것도 좋은 방향이라고 생각하고 진행했지만, 지나고보니 충분히 기술적으로도 도전할 수 있는 부분이 많았던 것 같은 아쉬움이 크게 남았다. 차후 프로젝트를 진행할 땐 계획 단계에서부터 신규 기술을 적용할 기능을 산정해 적용하며 두 마리 토끼를 모두 잡아야겠다고 생각했다.
- Try
- 실서비스로 이어지는 시도에 대해 좀 더 적극적으로 도전해야겠다고 생각했다.
---

**🍪 개인 회고록 - 이재근**

**자체 평가**

- 요양 관련 회사 고객관리 프로젝트를 진행하며, 기존 서비스 웹과 다른 구조의 회사 웹을 처음 기획하는 과정에서 어려움을 많이 느꼈습니다. 초반에는 무엇부터 정리해야 할지 막막했지만, 그 과정을 겪으면서 기획 단계에서의 방향 설정과 구조 설계가 프로젝트 전체의 완성도에 얼마나 큰 영향을 미치는지 체감하게 되었습니다. 단순히 기능을 나열하는 기획이 아니라, 서비스의 목적과 사용자 흐름을 먼저 고민해야 한다는 점을 깨닫게 된 것이 큰 수확이었습니다.
개발 단계에서는 프론트, 백엔드의 폴더 구조를 설계하며, 그동안 '작동만 하면 된다'는 생각에서 벗어나 유지보수성과 확장성을 고려한 구조 설계의 중요성을 인식하게 되었습니다. 아직 완벽하다고는 할 수 없지만, 팀원들과의 협업과 이후 관리까지 고려햐 구조를 고민해본 경험 자체가 제게는 의미가 컸습니다.
특히 매칭 로직을 맡아 거리 계산 기능을 구현하면서, 무작정 외부 API를 사용하는 방식이 아니라 공공데이터의 위도, 경도 정보를 활용해 로직을 구성해보았습니다. 이 과정에서 같은 기능이라도 구현 방식에 따라 비용, 성능, 유지보수 측면에서 큰 차이가 날 수 있다는 점을 몸소 느꼈고, 앞으로는 더 주도적으로 다양한 방법을 비교하고 선택할 수 있어야겠다는 과제도 함께 인식하게 되었습니다.
이번 프로젝트를 통해 아직 부족한 점도 많다는 것을 알게 되었지만, 그만큼 기획부터 설계,구현까지 전 과정을 고민하는 개발자로 한 단계 성장할 수 있는 계기가 되었다고 생각합니다. 단순히 주어진 기능을 만드는 개발자가 아니라, 왜 이 방식이 필요한지 고민하고 더 나은 선택을 할 수 있는 개발자가 되기 위해 계속해서 노력해야겠다고 느낀 프로젝트였습니다.

---

**🍪 개인 회고록 - 이현수**

**자체 평가**

- 기능 구현보다 전체 흐름을 이해하고 연결하는 일이 더 중요하다는 걸 많이 느꼈다. 각각의 기능은 잘 동작해도 실제 사용 과정에서 자연스럽게 이어지지 않으면 의미가 없다는 점이다.
SSE 기반 알림을 구현하면서 실시간 기능의 어려움을 직접 경험했다. 처음에는 이벤트를 보내는 구조로 생각했지만 연결이 끊겼을 때의 대응, 재연결 과정에서의 중복 이벤트 처리 등 운영 환경을 고려해야 할 요소가 많았다. 이 과정을 거치고 실시간 기능은 관리가 중요하다는 생각을 하게 됐다.
대시보드를 만들면서는 많이 보여주는 것’이 항상 좋은 선택은 아니라는 점을 느꼈다. 초반에는 지표를 최대한 노출했지만 오히려 사용자가 핵심을 파악하기 어렵다는 걸 깨닫고 정보의 우선순위를 다시 고민하게 됐다.
이번 경험을 통해 기술적인 완성도가 아니라 사용자 관점과 운영 관점을 함께 고려하는 개발이 필요하다는 점을 배웠다. 앞으로 기능을 만들기 전에 흐름과 정보 구조부터 먼저 고민해야 될 거 같다 되고자 한다.
