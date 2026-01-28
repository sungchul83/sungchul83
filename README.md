## Principal Backend Engineer & Systems Architect

> Turning chaos into structure.

15년 이상 백엔드 시스템을 설계하고 운영해오며,  
레거시 현대화와 Observability 확보를 중심으로 아키텍처를 설계해왔습니다.

추측이 아닌 **데이터 기반 판단**,  
강한 결합이 아닌 **명확한 책임 분리**,  
복잡함을 줄이는 **구조 중심 설계**를 가장 중요하게 생각합니다.

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
| Backend | Java, Python, FastAPI |
| Infra | Kubernetes, KubeVirt, Docker |
| Data Pipeline | OpenTelemetry, Kafka, Redis |
| Observability | VictoriaMetrics, VictoriaLogs |
| Analysis | Pandas, Time-series processing |

## 🧪 프로토타입 저장소 및 진행 현황

현재 비공개 저장소에서 다음과 같은 프로토타입을 운영하며 구조를 검증하고 있습니다.  
코드는 Private 이지만, 각 저장소의 목적과 진행 상황을 공개합니다.

| Repository | 목적 | 진행률 |
| --- | --- | --- |
| `sheltiex-backend` | Hexagonal 기반 API / Engine 구조 실험 | ████████░░ 80% |
| `sheltiex-agent` | Cluster Agent 기반 연동 구조 검증 (Golang) | ██████░░░░ 60% |
| `sheltiex-observability-pipeline` | OTel → VictoriaLogs/Metrics 데이터 흐름 검증 | ███████░░░ 70% |
| `sheltiex-portal` | 운영자 중심 대시보드 UI 프로토타입 | █████░░░░░ 50% |
| `sheltiex-ai-insight` | 시계열 기반 이상 탐지 실험 (Python/Pandas) | ████░░░░░░ 40% |
| `sheltiex-kubevirt-lab` | KubeVirt 기반 VM 관리 가능성 테스트 | █████░░░░░ 50% |

> 진행률은 기능 완성도가 아닌, **구조 검증 단계 기준**입니다.

## 📝 엔지니어링 기록

기술적 의사결정과 설계 과정은 문서로 정리하고 있습니다.

- Hexagonal Architecture 설계 기준
- KubeVirt 도입 검토 과정
- Observability 데이터 파이프라인 구조
- 운영 대시보드 정보 구조 설계

## 📫 연락

<a href="mailto:your_email@example.com">
  <img src="https://img.shields.io/badge/Email-Contact_Me-gray?style=for-the-badge&logo=gmail" />
</a>
