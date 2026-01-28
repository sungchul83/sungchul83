## 🧐 백엔드 엔지니어 및 시스템 설계자

> Turning chaos into structure.

15년 이상 백엔드 시스템을 설계하고 운영해오며,  
레거시 현대화와 Observability 확보를 중심으로 아키텍처를 설계해왔습니다.

복잡한 시스템을 단순한 구조로 재정의하는 일을 가장 잘합니다.

추측이 아닌 **데이터 기반 판단**,  
강한 결합이 아닌 **명확한 책임 분리**,  
복잡함을 줄이는 **구조 중심 설계**를 가장 중요하게 생각합니다.

## 🧩 해결해 온 문제 유형

- 멀티 클러스터 환경에서의 운영 가시성 확보
- 레거시 구조를 Hexagonal 기반으로 점진적 전환
- 로그/메트릭/이벤트가 분리된 환경에서의 통합 관측 구조 설계
- Kubernetes 기반 플랫폼에서 VM, GPU, Container를 함께 다루는 구조 검증
- 운영자가 ‘원인’을 찾지 않아도 되도록 만드는 대시보드 설계

## 🎯 현재 집중 영역 (2026 H1)

도메인에 종속되지 않는 **관측 및 인사이트 분석 구조**를 설계하는 실험을 진행 중입니다.  
Kubernetes, VM, 시계열 데이터, 이벤트와 같이 서로 다른 성격의 요소를  
하나의 아키텍처 관점에서 처리할 수 있는지 검증하고 있습니다.

### 아키텍처 접근 방식

- Hexagonal Architecture
- Event-Driven Data Flow (Kafka / MQ)
- Real-time Feedback (SSE)
- OpenTelemetry 기반 데이터 수집
- Python / Pandas 기반 시계열 분석

## 🛠 사용 기술 영역

| 영역 | 기술 스택 |
| --- | --- |
| Backend | Java, Kotlin, Python, FastAPI |
| Infra | Kubernetes, KubeVirt, Docker |
| Data Pipeline | OpenTelemetry, Kafka, Redis |
| Observability | VictoriaMetrics, VictoriaLogs |
| Analysis | Pandas, Time-series processing |

## 🧪 프로토타입 저장소 및 진행 현황

아래 저장소들은 기능 구현이 아닌, **아키텍처 타당성을 검증하기 위한 실험 저장소**입니다.  
현재 상반기는 **핵심 기능 영역에 대한 구조 검증**에 집중하고 있습니다.

| Repository | 검증 목적 | 주요 기술 | 진행 현황 |
| --- | --- | --- | --- |
| `sheltiex-backend` | Hexagonal 기반 API / Engine 구조 및 프로토타입 대응 | Java, Kotlin, FastAPI | 🟩🟩🟩🟩🟩🟩🟩🟩⬜⬜ (85%) |
| `sheltiex-agent` | Cluster Agent 기반 플랫폼 ↔ 클러스터 연동 구조 검증 | Golang | 🟩🟩🟩🟩🟩🟩🟩⬜⬜⬜ (75%) |
| `ai-insight-prototype` | AI Insight 대시보드 및 시계열 분석 구조 검증 | Python, Pandas | 🟩🟩🟩🟩🟩🟩⬜⬜⬜⬜ (65%) |
| `kubevirt-prototype` | KubeVirt 기반 VM 관측 및 관리 대시보드 검증 | Kubernetes, KubeVirt | 🟩🟩🟩🟩🟩🟩⬜⬜⬜⬜ (65%) |
| `kafka-prototype` | 이벤트 기반 처리 및 Kafka 클라이언트 구조 검증 | Kafka | 🟩🟩🟩🟩🟩⬜⬜⬜⬜⬜ (55%) |
| `traces-prototype` | 분산 Traces 수집 및 분석 구조 검증 | OpenTelemetry | 🟩🟩🟩🟩🟩⬜⬜⬜⬜⬜ (55%) |
| `event-timeline-prototype` | 장애 타임라인 분석 및 이벤트 인과관계 시각화 | Time-series, Events | 🟩🟩🟩🟩⬜⬜⬜⬜⬜⬜ (45%) |

> 진행률은 기능 완성도가 아닌, **구조 검증 및 실험 진행 정도**를 의미합니다.

## 📝 엔지니어링 기록

모든 설계 과정과 의사결정은 문서화되어 있으며,  
재사용 가능한 **아키텍처 자산**으로 관리하고 있습니다.

- Hexagonal Architecture 설계 기준
- KubeVirt 도입 검토 과정
- Observability 데이터 파이프라인 구조
- 운영 대시보드 정보 구조 설계

## 📫 연락

<a href="mailto:your_email@example.com">
  <img src="https://img.shields.io/badge/Email-Contact_Me-gray?style=for-the-badge&logo=gmail" />
</a>
