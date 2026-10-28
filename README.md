<div align="center">

# Jeshwanth Singh

**Backend & Infrastructure Engineer** · systems · runtime security · AI infra · San Francisco

*I build execution infrastructure that produces proof, not just logs.*

[![Portfolio](https://img.shields.io/badge/portfolio-jeshwanth.com-FF6B35?style=for-the-badge&logoColor=white)](https://www.jeshwanth.com)
[![LinkedIn](https://img.shields.io/badge/linkedin-connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/jeshwanthsingh23)
[![Email](https://img.shields.io/badge/email-say_hi-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:jeshwanthsingh@gmail.com)

</div>

---

### About me

```var me = Engineer{
    Name:      "Jeshwanth Singh",
    Base:      "San Francisco, CA",
    Education: "Recent CS graduate from SFSU",
    Languages: []string{
        "Go",
        "C++",
        "Python",
        "TypeScript",
    },
    Focus: []string{
        "Distributed Systems",
        "Runtime Security",
        "AI Infrastructure",
    },
    Building: []string{
        "Aegis",
        "Unfoolable",
        "MuseGuard",
    },
}
```

---

### Where I've shipped

<table>
<tr>
<td width="50%" valign="top">

**Rockwell Automation** · *Systems Software Engineer Co-op*
`Jun 2024 – May 2025`

p99 latency spikes under burst load →
profiled CPU hot paths with pprof →
**400 ms → 80 ms p99 under production traffic**

`Go` `C++` `gRPC` `PostgreSQL` `Docker` `Linux`

</td>
<td width="50%" valign="top">

**Associated Students – SFSU** · *Software Engineer (Part-Time)*
`Apr 2022 – Present`

APIs timing out every registration week →
traced connection-pool exhaustion with jstack →
**stable through every peak enrollment cycle**

`C#` `Python` `PostgreSQL` `Azure Functions`

</td>
</tr>
</table>

---

### Featured projects

<table>
<tr>
<td width="50%" valign="top">

#### 🛡️ [Aegis](https://github.com/jeshwanthsingh/Aegis)
**Secure microVM runtime for AI-generated code**

Runs untrusted code in Firecracker microVMs with policy checks, a host-mediated secret broker, and Ed25519-signed DSSE receipts for offline verification.

**1.496 s median boot-to-ready** · [5 nano-profile runs](https://github.com/jeshwanthsingh/Aegis/blob/main/docs/benchmarks/current-stack.md)

`Go` `Firecracker` `Linux/KVM` `in-toto/DSSE`

![status](https://img.shields.io/badge/status-active-2ea44f?style=flat-square)

</td>
<td width="50%" valign="top">

#### 🔒 [Unfoolable](https://github.com/jeshwanthsingh/Unfoolable)
**AI coding agent that can't grade its own homework**

AI agents do the engineering work; a separate, locked grader checks the frozen changes, and you review the evidence before deciding what to keep.

**2,000 candidate request pairs, zero observed failures** · [one bounded concurrency experiment](https://github.com/jeshwanthsingh/Unfoolable/blob/main/artifacts/verify-only-coverage-round/RESULT.md)

`TypeScript` `Node.js` `React` `SQLite` `Codex`

![status](https://img.shields.io/badge/status-active-2ea44f?style=flat-square)

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### 🎨 [MuseGuard](https://github.com/jeshwanthsingh/muse-guard)
**Built solo at the Meta Global AI Developer Hackathon (Indie track)**

Finds conflicts in confirmed requirement rules, lets the developer resolve them, and independently checks the repaired code.

**40/40 guarded recoveries vs. 39/40 plain** after one developer decision in the [recorded study](https://github.com/jeshwanthsingh/muse-guard/blob/main/docs/MEASURED_RESULTS.md); not a proven advantage.

`Python` `Muse Code` `Muse Spark` `JavaScript` `HTML/CSS`

![status](https://img.shields.io/badge/status-hackathon_2026-8A2BE2?style=flat-square)

</td>
<td width="50%" valign="top">

#### ⚡ CacheFlow
**LLM inference benchmarking**

Benchmarks vLLM and SGLang with PyTorch, measuring latency, throughput, and tokens per GPU-hour, with CUDA-level profiling in Nsight Systems.

`Python` `PyTorch` `vLLM` `SGLang` `CUDA` `Nsight Systems`

![status](https://img.shields.io/badge/status-active-2ea44f?style=flat-square)

</td>
</tr>
<tr>
<td colspan="2" valign="top">

#### 📡 [Distributed Telemetry & Chaos Platform](https://github.com/jeshwanthsingh/Edge-Observatory)
Go telemetry ingestion → Kafka → Java/Spring consumers, with failure testing, automated remediation, and Prometheus/Grafana latency tracking.

`Go` `Java` `Spring Boot` `Kafka` `gRPC` `Kubernetes` `Prometheus` `Grafana` `PostgreSQL` · ![status](https://img.shields.io/badge/status-complete-blue?style=flat-square)

</td>
</tr>
</table>

---

### Stack

<div align="center">

![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Firecracker](https://img.shields.io/badge/Firecracker-FF4B4B?style=flat-square&logoColor=white)
![eBPF](https://img.shields.io/badge/eBPF-000000?style=flat-square&logoColor=white)
![CUDA](https://img.shields.io/badge/CUDA-76B900?style=flat-square&logo=nvidia&logoColor=white)
![Kafka](https://img.shields.io/badge/Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat-square&logo=postgresql&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-FF9900?style=flat-square&logo=amazonaws&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white)

</div>

---

<div align="center">

**Recent CS graduate from SFSU** · Dean's List · GPA 3.7

**Open to new-grad backend, infrastructure, platform, and AI-infra roles.**

</div>
