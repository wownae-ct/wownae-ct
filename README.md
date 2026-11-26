## 대표 레포지토리

| 영역 | 레포 | 내용 |
|---|---|---|
| AI 서빙 | [cortex-vllm-serving](https://github.com/wownae-ct/cortex-vllm-serving) | RTX 5070 Ti(16GB) 한 장에서 Gemma 4 12B와 bge-m3를 vLLM으로 서빙하고 동시성별 처리량·KV cache를 측정한 기록. fp8 KV로 동시 16 처리량 404 → 528 tok/s, P99 TTFT 8.3 → 4.5초 |
| 인프라 | [homelab-gitops](https://github.com/wownae-ct/homelab-gitops) | 홈랩 Kubernetes GitOps 저장소. ArgoCD App of Apps, Helm, Ansible |
| 인프라 | [homelab-terraform](https://github.com/wownae-ct/homelab-terraform) | Proxmox 위 Kubernetes와 AWS·Cloudflare를 한 코드로 정의한 Terraform |
| AI 프로젝트 | [MS-AI-Project-3rd-Team-4](https://github.com/wownae-ct/MS-AI-Project-3rd-Team-4) | MarryMap: 결혼 준비 관리와 공개 자료 근거 AI 상담 서비스 (SeSAC 3차, 2인 팀) |
| AI 프로젝트 | [MS-AI-Project-2nd-Team-2](https://github.com/wownae-ct/MS-AI-Project-2nd-Team-2) | AD신호등: 광고 문구의 표시광고법 위반 가능성을 RAG로 자가진단 (SeSAC 2차, 4인 팀) |
| ML 프로젝트(팀 레포) | [MS-AI-Project-1st-Team-5](https://github.com/wownae-ct/MS-AI-Project-1st-Team-5) | HelmAI: 산업안전 관제 대시보드 (SeSAC 1차, 6인 팀, 포크) |
| ML | [helmet-detection](https://github.com/wownae-ct/helmet-detection) | YOLOv8 안전모·쓰러짐 탐지 모델의 라운드별 실험 기록. Airflow 학습 DAG, MLflow 지표 |

그 외: [jiong-minihome](https://github.com/wownae-ct/jiong-minihome)(Next.js 개인 포트폴리오 웹, 홈랩에 Jenkins → ArgoCD로 배포), [k3s-repo](https://github.com/wownae-ct/k3s-repo)(k3s GitOps 매니페스트)

## 기술 스택

- **실무(고객 환경)**: Linux, Cloudian HyperStore, Prometheus·Grafana, HAProxy·Keepalived·Nginx, DNS·NTP·L3 DSR, Puppet, Bash, Cassandra·Redis(장애 대응)
- **인프라·GitOps**: Kubernetes(kubeadm HA·AKS), Proxmox, Docker, Helm, Terraform, Ansible, ArgoCD, GitHub Actions(OIDC), Jenkins·Kaniko, Bicep, Istio
- **AI·ML**: vLLM, YOLOv8, MLflow, Airflow, Langfuse, Azure OpenAI, PostgreSQL(pgvector), Python(FastAPI)
- **클라우드**: AWS, Azure

## 자격

Azure Administrator Associate(2026.10) · Azure AI Fundamentals(2026.08) · AWS Solutions Architect Associate(2024.03) · 리눅스마스터 2급 · 네트워크관리사 2급
