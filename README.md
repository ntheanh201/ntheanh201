<h1 align="center">The Anh Nguyen</h1>

<p align="center">
  Software Engineer &nbsp;·&nbsp; Tech Lead, Viettel AI Platform
  <br />
  CNCF Ambassador &amp; Kubestronaut
</p>

<p align="center">
  Building &amp; shaping the AI/GPU Platform @
  <img align="center" src="./assets/viettel_networks.png" alt="Viettel Networks" height="24" />
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/ntheanh201/">LinkedIn</a> ·
  <a href="https://ntheanh201.id.vn/">Blog</a> ·
  <a href="https://github.com/ntheanh201">GitHub</a>
</p>

---

## `whoami`

```yaml
apiVersion: cloudnative.io/v1
kind: Engineer
metadata:
  name: the-anh-nguyen
  labels:
    title: software-engineer
    company: viettel-networks
    role: tech-lead/viettel-ai-platform
    community: cncf-ambassador/kubestronaut
    location: hanoi-vietnam
spec:
  focus:
    - GPU supercomputing on NVIDIA H200 / NVIDIA AI Enterprise
    - Kubernetes platform engineering on NVIDIA Base Command Manager (BCM)
    - Fractional & multi-tenant GPU (HAMi, MIG, GPU Operator)
    - InfiniBand / GPUDirect RDMA & multi-node NCCL
    - MLOps platforms on Kubernetes (Kubeflow, KServe)
  community:
    - kubernetes-org-member
    - project-hami-org-member
    - kubernetes-sig-docs-vi-approver
    - cncf-glossary-vietnamese-lead
```

## Currently

**Software Engineer @ Viettel Networks**, **Technical Lead — Viettel AI Platform**

Leading the engineering team and driving product development for the **Viettel AI Platform**,
a multi-tenant GPU supercomputing platform.

```text
gpu fleet     H200 clusters on NVIDIA AI Enterprise + Base Command Manager (BCM)
scheduling    Kubernetes on Base Command Manager (BCM)
              + Slurm-on-Kubernetes (Slinky)
              -> one fleet, both K8s and HPC scheduling
gpu & fabric  GPU Operator + Network Operator: InfiniBand / GPUDirect RDMA,
              multi-node NCCL, HAMi fractional-GPU sharing for multi-tenancy
```

## Recognition

<p align="center">
  <a href="https://www.cncf.io/people/ambassadors/">
    <img height="80" src="https://raw.githubusercontent.com/cncf/artwork/main/other/ambassador/stacked/color/cncf-ambassador-stacked-color.svg" alt="CNCF Ambassador" />
  </a>
  &nbsp;&nbsp;&nbsp;&nbsp;
  <a href="https://www.credly.com/badges/aac477c8-f802-4264-88ba-0dc84f84e046/linked_in?t=syf2pp">
    <img height="80" src="https://raw.githubusercontent.com/cncf/artwork/main/other/kubestronaut/stacked/color/kubestronaut-stacked-color.svg" alt="Kubestronaut" />
  </a>
  &nbsp;&nbsp;&nbsp;&nbsp;
  <a href="https://www.credly.com/badges/9237fdde-0176-416a-95e0-5c2568599ae4">
    <img height="30" src="https://github.com/user-attachments/assets/c9aa7f36-42d3-475f-bbf8-79c49f48b5bf" alt="NVIDIA-Certified Professional in AI Operations" />
  </a>
</p>

- [**CNCF Ambassador**](https://www.cncf.io/people/ambassadors/) — Cloud Native Computing Foundation
- [**Kubestronaut**](https://www.credly.com/badges/aac477c8-f802-4264-88ba-0dc84f84e046/linked_in?t=syf2pp) — CKA · CKAD · CKS · KCNA · KCSA
- [**NVIDIA-Certified Professional**](https://www.credly.com/badges/9237fdde-0176-416a-95e0-5c2568599ae4) — AI Operations (NCP-AIO)
- **[Kubernetes](https://github.com/kubernetes) org member** — SIG Docs, Vietnamese localization approver
- **[Project-HAMi](https://github.com/Project-HAMi) org member** — fractional GPU sharing for Kubernetes
- **CNCF Cloud Native Glossary** — Vietnamese localization lead
- **The Shubhra Kar Linux Foundation Training (LiFT) Scholarship** — 2025 recipient

## Upstream

| Project | What I work on |
|---|---|
| [kubernetes/website](https://github.com/kubernetes/website/pulls?q=is%3Apr+author%3Antheanh201+) | SIG Docs — Vietnamese localization approver, Kubernetes org member |
| [cncf/glossary](https://github.com/cncf/glossary/pulls?q=is%3Apr+author%3Antheanh201+) | Cloud Native Glossary — Vietnamese localization lead |
| [kubeflow/kubeflow](https://github.com/kubeflow/kubeflow/pulls/ntheanh201) | AI platform on Kubernetes |
| [Project-HAMi/HAMi](https://github.com/Project-HAMi/HAMi/pulls?q=is%3Apr+author%3Antheanh201+) | Fractional GPU sharing for Kubernetes — org member |
| [apache/trafficcontrol](https://github.com/apache/trafficcontrol/pulls?q=is%3Apr+author%3Antheanh201+) | Content delivery network |

## Projects

| Repository | Description |
|---|---|
| [trafficcontrol-grafana-scenes](https://github.com/ntheanh201/trafficcontrol-grafana-scenes) | Grafana dynamic dashboards for Apache Traffic Control built on Scenes — upstreamed via [trafficcontrol PR #7927](https://github.com/apache/trafficcontrol/pull/7927) |
| [k8s-auto-healing](https://github.com/ntheanh201/k8s-auto-healing) | Go controller (client-go) running periodic health checks and auto-remediating known failures — e.g. Zalando Postgres replication lag — driven by Prometheus alerts. Go clean architecture + Registry pattern |
| [kodekloud-engineer](https://github.com/ntheanh201/kodekloud-engineer) | Ansible-driven solutions for KodeKloud Engineer tasks (Linux, Kubernetes, Jenkins, Git, …) |
| [gitops-cert-level-2-examples](https://github.com/ntheanh201/gitops-cert-level-2-examples) | GitOps certification level 2 examples |
| [aws-lambda-go-mongodb](https://github.com/ntheanh201/aws-lambda-go-mongodb) | Go Lambda talking to MongoDB, triggered by CloudWatch Events |
| [udacity-capstone](https://github.com/ntheanh201/udacity-capstone) | Capstone for the Cloud DevOps Nanodegree |

## Talks

- **From Project to Production: HAMi and Viettel Cloud** — [KCD & OpenInfra Days Vietnam 2026](https://sessionize.com/view/c0qvrydt/GridSmart)
- **Auditable Autonomy: Engineering With AI Teammates That Leave a Trace** — [The Future of Software Engineering: Kỹ nghệ phần mềm trong kỷ nguyên Agentic AI](https://viettelfamily.com/news/vds-quy-tu-chuyen-gia-viettel-ban-ve-tuong-lai-software-engineering-global)
- **From Vietnam to the World: Contributing to Kubernetes and earning the Linux Foundation Scholarship** — [#cTENcf Birthday Bash Hanoi 🇻🇳](https://community.cncf.io/events/details/cncf-cloud-native-hanoi-presents-ctencf-birthday-bash-hanoi/)
- **VIETTELDX TALKS #8: AI GÕ CỬA — DOANH NGHIỆP VIỆT ĐÃ SẴN SÀNG** — [YouTube](https://www.youtube.com/watch?v=8pN4ft0OzpY)
- **HAMi: Fractional GPU for Efficient AI in Cloud Native** — [OpenInfra & Cloud Native Day Vietnam 2025](https://www.vietopeninfra.org/void2025)
- **Fractional GPU for AI: Open Source Solutions in Cloud Native** — [Cloud Native Hanoi May Meetup: GPU and eBPF on Kubernetes](https://community.cncf.io/events/details/cncf-cloud-native-hanoi-presents-may-meetup-gpu-and-ebpf-on-kubernetes/)

## Writing

- [Apache Traffic Control — Migrating Grafana scripted CDN metrics dashboards to Scenes: a seamless transition](https://ntheanh201.hashnode.dev/apache-traffic-control-migrating-grafana-scripted-cdn-metrics-dashboards-to-scenes-a-seamless-transition)
- [How GlitchTip helped me solve a real-world problem](https://ntheanh201.id.vn/articles/how-glitchtip-helped-me-solve-real-world-problem.html) — using GlitchTip to gather statistics for KPI/KQI reporting
