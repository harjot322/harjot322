<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0F2027,50:203A43,100:2C5364&height=200&section=header&text=Harjot%20Singh%20Makkar&fontSize=42&fontColor=FFFFFF&animation=fadeIn&fontAlignY=38&desc=Cloud%20Site%20Reliability%20Engineer%20%7C%20Platform%20and%20Infrastructure%20Engineering&descSize=16&descAlignY=60" width="100%" />

<a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=20&duration=2800&pause=1000&color=38BDF8&center=true&vCenter=true&width=820&lines=Kubernetes+(AKS+%2F+EKS)+and+Declarative+GitOps+(FluxCD);Multi-Account+AWS+and+Azure+Infrastructure+Automation;Observability%2C+DevSecOps+and+Zero-Downtime+Migrations;Building+ATS+Certify+%E2%80%94+Parser-First+Resume+Engineering" alt="Typing SVG" /></a>

<br/>

<p>
  <a href="https://linkedin.com/in/harjotmakkar322"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="https://harjotsinghmakkar.substack.com"><img src="https://img.shields.io/badge/Substack_Writing-FF6719?style=for-the-badge&logo=substack&logoColor=white" alt="Substack" /></a>
  <a href="https://atscertify.com"><img src="https://img.shields.io/badge/ATS_Certify-10B981?style=for-the-badge&logo=vercel&logoColor=white" alt="ATS Certify" /></a>
  <a href="mailto:harjotdesk@gmail.com"><img src="https://img.shields.io/badge/harjotdesk%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
</p>

</div>

---

### About & Engineering Philosophy

I work at the intersection of **Cloud Infrastructure**, **Platform Engineering**, and **Site Reliability Engineering**—operating remote, multi-account enterprise cloud environments across **AWS** and **Azure**.

I treat infrastructure strictly as software: **declarative, version-controlled, observable, and recoverable**. Rather than treating a successful deployment command as the finish line, I focus on automated verification, traffic-safe migrations, security gates, and eliminating repetitive operational toil.

- **Current Focus:** Production Kubernetes operations, GitOps delivery, multi-account cloud automation, and resilience engineering.
- **Independent Product:** Architecting [**ATS Certify**](https://atscertify.com) — an ATS-first résumé engineering and validation platform combining deterministic parsing with targeted semantic analysis.
- **Technical Writing:** Publishing deep dives on Kubernetes migrations, restore probes, and cloud automation on [**Substack**](https://harjotsinghmakkar.substack.com).

---

### Production Engineering Highlights

<table>
  <tr>
    <td width="50%" valign="top">
      <h4>Kubernetes & Traffic Engineering</h4>
      <ul>
        <li><strong>Zero-Downtime Cluster Cutovers:</strong> Executed live AKS platform migrations via declarative FluxCD GitOps and Terraform workflows.</li>
        <li><strong>Ingress Modernization:</strong> Migrated live production traffic from legacy Nginx Ingress to <strong>Envoy Gateway</strong> with zero dropped requests.</li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <h4>Cloud Automation & FinOps</h4>
      <ul>
        <li><strong>400+ Account Inventory:</strong> Built Python and Kubernetes CronJob automation using cross-account IAM roles and Vault, cutting recurring reporting effort by up to 90%.</li>
        <li><strong>Event-Streaming Cleanup:</strong> Automated Terraform teardowns of idle Event Hubs capacity across 4 environments (~$70K annualized savings).</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h4>Reliability & Storage Pipelines</h4>
      <ul>
        <li><strong>Verified Disaster Recovery:</strong> Engineered automated OpenSearch snapshot and restore-probe verification workflows to prove recovery readiness.</li>
        <li><strong>Batch Pipeline Acceleration:</strong> Refactored sequential file-transfer workflows into validated batch pipelines, cutting benchmark runtime from ~33m to ~72s.</li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <h4>DevSecOps & CI/CD Governance</h4>
      <ul>
        <li><strong>Reusable Security Gates:</strong> Authored GitHub Composite Actions integrating <strong>Wiz</strong>, <strong>Coverity</strong>, and <strong>Black Duck</strong> with automated severity parsing.</li>
        <li><strong>Data-Platform Hardening:</strong> Triaged and remediated 170+ Critical/High vulnerabilities across Schema Registry infrastructure down to zero.</li>
      </ul>
    </td>
  </tr>
</table>

---

### Reference Architecture Showcase

> *Sanitized architectural blueprints stored in `./assets/diagrams/`. Click each panel to inspect.*

<details open>
  <summary><strong>01. Multi-Account Cloud Inventory Automation (400+ Accounts)</strong></summary>
  <br/>
  <div align="center">
    <img src="./assets/diagrams/400awsaccounts.svg" alt="Multi-Account AWS Inventory Architecture" width="92%" />
  </div>
  <br/>
</details>

<details>
  <summary><strong>02. Zero-Downtime Kubernetes Cluster Cutover (GitOps + Terraform)</strong></summary>
  <br/>
  <div align="center">
    <img src="./assets/diagrams/AKS_cutover.svg" alt="Zero-Downtime AKS Cutover Architecture" width="92%" />
  </div>
  <br/>
</details>

<details>
  <summary><strong>03. Zero-Drop Ingress Modernization (Nginx to Envoy Gateway)</strong></summary>
  <br/>
  <div align="center">
    <img src="./assets/diagrams/Envoy.svg" alt="Envoy Gateway Migration Architecture" width="92%" />
  </div>
  <br/>
</details>

<!-- UNCOMMENT ONCE backup.svg IS ADDED TO assets/diagrams/
<details>
  <summary><strong>04. OpenSearch Automated Snapshot & Restore-Probe Verification</strong></summary>
  <br/>
  <div align="center">
    <img src="./assets/diagrams/backup.svg" alt="OpenSearch Disaster Recovery Probe Architecture" width="92%" />
  </div>
  <br/>
</details>
-->

<!-- UNCOMMENT ONCE migration.svg IS ADDED TO assets/diagrams/
<details>
  <summary><strong>05. High-Throughput Storage & Cross-Boundary Migration Pipeline</strong></summary>
  <br/>
  <div align="center">
    <img src="./assets/diagrams/migration.svg" alt="Storage and Cross-Boundary Migration Architecture" width="92%" />
  </div>
  <br/>
</details>
-->

---

### Tech Stack & Tooling

**Cloud & Infrastructure as Code**  
![AWS](https://img.shields.io/badge/AWS-FF9900?style=for-the-badge&logo=amazon-aws&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white)
![OpenTofu](https://img.shields.io/badge/OpenTofu-FFDA18?style=for-the-badge&logo=opentofu&logoColor=black)
![Ansible](https://img.shields.io/badge/Ansible-EE0000?style=for-the-badge&logo=ansible&logoColor=white)

**Containers, Orchestration & Networking**  
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Helm](https://img.shields.io/badge/Helm-0F1689?style=for-the-badge&logo=helm&logoColor=white)
![FluxCD](https://img.shields.io/badge/FluxCD-5468FF?style=for-the-badge&logo=flux&logoColor=white)
![Envoy](https://img.shields.io/badge/Envoy_Gateway-AC6199?style=for-the-badge&logo=envoyproxy&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white)

**Observability, CI/CD & DevSecOps**  
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white)
![OpenTelemetry](https://img.shields.io/badge/OpenTelemetry-425CC7?style=for-the-badge&logo=opentelemetry&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![GitLab CI](https://img.shields.io/badge/GitLab_CI-FC6D26?style=for-the-badge&logo=gitlab&logoColor=white)
![Vault](https://img.shields.io/badge/HashiCorp_Vault-FFEC6E?style=for-the-badge&logo=vault&logoColor=black)
![SonarQube](https://img.shields.io/badge/SonarQube-4E9BCD?style=for-the-badge&logo=sonarqube&logoColor=white)

**Languages, Automation & Data Platforms**  
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white)
![OpenSearch](https://img.shields.io/badge/OpenSearch-005EB8?style=for-the-badge&logo=opensearch&logoColor=white)
![Apache Kafka](https://img.shields.io/badge/Apache_Kafka-231F20?style=for-the-badge&logo=apachekafka&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)

---

### GitHub Metrics & Activity

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=harjot322&theme=tokyonight&hide_border=true&count_private=true&v=3" height="165" alt="GitHub Stats" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=harjot322&theme=tokyonight&hide_border=true&layout=compact&v=2" height="165" alt="Top Languages" />
</div>

<div align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=harjot322&theme=tokyonight&hide_border=true" alt="GitHub Streak" />
</div>

<br/>

<div align="center">
  <img src="https://komarev.com/ghpvc/?username=harjot322&label=PROFILE+VIEWS&color=0E75B6&style=for-the-badge" alt="Profile Views" />
</div>
