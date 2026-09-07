<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0f2027,50:203a43,100:2c5364&height=200&section=header&text=DaeHyuk%20Kang&fontSize=58&fontColor=ffffff&fontAlignY=35&desc=Backend%20Developer&descAlignY=55&descSize=18" />

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=20&duration=3000&pause=800&color=4A9DEC&center=true&vCenter=true&width=560&lines=Java+21+%7C+Spring+Boot+%7C+MSA+Backend;%EC%84%9C%EB%B9%84%EC%8A%A4%EA%B0%80+%EB%81%8A%EA%B8%B0%EC%A7%80+%EC%95%8A%EB%8A%94+%EA%B5%AC%EC%A1%B0%EB%A5%BC+%EB%A7%8C%EB%93%AD%EB%8B%88%EB%8B%A4;Always+building%2C+always+learning" />

<br/>

[![Gmail](https://img.shields.io/badge/kfhyuk0430@gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:kfhyuk0430@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/DaeHyuk-kang)
![Profile Views](https://komarev.com/ghpvc/?username=DaeHyuk-kang&style=flat-square&color=4A9DEC&label=visitors)

</div>

---

### 👋 About Me

```java
public class DaeHyuk {
    String  role     = "Backend Developer";
    String  course   = "프로그래머스 백엔드 심화 데브코스 7기";
    String[] focus   = { "MSA 설계", "동시성 제어", "검색 · 배치 파이프라인" };
    String  learning = "Kafka, Observability (Prometheus · Grafana · Zipkin)";
    String[] motto   = { "동작하는 코드보다, 무너지지 않는 구조",
                         "왜 이렇게 짰는지 설명할 수 있는 코드" };
}
```

> ⚠️ 배포 사이트는 AWS 비용 관리 차원에서 잠시 내려둔 상태입니다.
> 확인이 필요하시면 언제든 이메일 주세요 📧

---

### 🛠 Tech Stack

<div align="center">

**Language & Core**

![Java](https://img.shields.io/badge/Java%2021-007396?style=for-the-badge&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)
![Spring Cloud](https://img.shields.io/badge/Spring%20Cloud-6DB33F?style=for-the-badge&logo=spring&logoColor=white)
![Spring Batch](https://img.shields.io/badge/Spring%20Batch-6DB33F?style=for-the-badge&logo=spring&logoColor=white)
![JPA](https://img.shields.io/badge/JPA-59666C?style=for-the-badge&logo=hibernate&logoColor=white)
![Gradle](https://img.shields.io/badge/Gradle-02303A?style=for-the-badge&logo=gradle&logoColor=white)

**MSA**

![Eureka](https://img.shields.io/badge/Eureka-0E7C7B?style=for-the-badge&logo=spring&logoColor=white)
![Gateway](https://img.shields.io/badge/API%20Gateway-6DB33F?style=for-the-badge&logo=spring&logoColor=white)
![OpenFeign](https://img.shields.io/badge/OpenFeign-4A9DEC?style=for-the-badge&logo=spring&logoColor=white)
![Resilience4j](https://img.shields.io/badge/Resilience4j-E85D3D?style=for-the-badge&logo=resilience4j&logoColor=white)
![Kafka](https://img.shields.io/badge/Kafka-231F20?style=for-the-badge&logo=apachekafka&logoColor=white)

**Data & Infra**

![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Elasticsearch](https://img.shields.io/badge/Elasticsearch-005571?style=for-the-badge&logo=elasticsearch&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![AWS S3](https://img.shields.io/badge/AWS%20S3-569A31?style=for-the-badge&logo=amazons3&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)

**Test & Observability**

![JUnit5](https://img.shields.io/badge/JUnit5-25A162?style=for-the-badge&logo=junit5&logoColor=white)
![Testcontainers](https://img.shields.io/badge/Testcontainers-291A44?style=for-the-badge&logo=docker&logoColor=white)
![k6](https://img.shields.io/badge/k6-7D64FF?style=for-the-badge&logo=k6&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white)

</div>

---

### 🚀 Now Building

<div align="center">

[![Earlybird](https://img.shields.io/badge/prgrms--be--adv--devcourse%2Fbeadv7__7__earlybird__BE-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/prgrms-be-adv-devcourse/beadv7_7_earlybird_BE)

</div>

**얼리버드 (Earlybird)** — 리워드 기반 크라우드펀딩 플랫폼. All-or-Nothing 모델로, 마감까지 목표 금액을 채우면 창작자에게 정산하고 실패하면 후원자 전원에게 일괄 환불합니다.

- `Spring Boot 4.1` · `Spring Cloud 2025.1.2` · `Java 21` Gradle 멀티모듈 **MSA (13개 서비스)**
- 도메인 간 참조를 **객체가 아닌 ID로만** 두고, 포트 인터페이스 + HTTP 어댑터로 호출하는 구조
- 담당: **project-service** (펀딩 프로젝트 · 리워드 · Elasticsearch 검색/자동완성 · 리워드 재고 동시성 제어), **file-service** (S3 presigned URL)
- Testcontainers 기반 통합 테스트 + k6 부하 테스트로 검증

---

### 📌 Projects

| Project | 한 줄 소개 | Stack |
|---|---|---|
| [**ocr-parser-java**](https://github.com/DaeHyuk-kang/ocr-parser-java) | 차량 계근표 OCR 텍스트에서 중량·날짜·차량번호를 정규화해 뽑아내는 파서 | `Java` |
| [**kosis-etl-java**](https://github.com/DaeHyuk-kang/kosis-etl-java) | KOSIS API 수집 → 정규화 → JSON 적재 ETL 파이프라인 | `Java` |
| [**GITHUB-RISK-ANALYZER**](https://github.com/DaeHyuk-kang/GITHUB-RISK-ANALYZER) | 활동성·기여자 집중도·이슈 관리로 저장소 건강도를 평가 | `HTML` `JS` |
| [**SKHU_BOX-Backend**](https://github.com/DaeHyuk-kang/SKHU_BOX-Backend) | SKHUBOX 백엔드 | `Java` `Spring` |

---

### 📊 GitHub Stats

<div align="center">

<img width="42%" src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=DaeHyuk-kang&theme=tokyonight" />

<img width="32%" src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=DaeHyuk-kang&theme=tokyonight" />
<img width="32%" src="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=DaeHyuk-kang&theme=tokyonight" />
<img width="32%" src="https://github-profile-summary-cards.vercel.app/api/cards/productive-time?username=DaeHyuk-kang&theme=tokyonight&utcOffset=9" />

<br/>

<img width="91%" src="https://github-readme-streak-stats.herokuapp.com/?user=DaeHyuk-kang&theme=tokyonight&hide_border=true" />

</div>

<div align="center">
<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:2c5364,50:203a43,100:0f2027&height=120&section=footer" />
</div>
