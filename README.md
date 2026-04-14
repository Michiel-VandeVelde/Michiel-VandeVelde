<h1 align="center">Michiel Van de Velde</h1>

<p align="center">
  Cloud & DevOps Engineer · Intern at imec-IDLab · Open Source Enthusiast
</p>

<p align="center">
  <a href="https://be.linkedin.com/in/michiel-van-de-velde-1a9962388">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin" />
  </a>
  <a href="https://open.spotify.com/playlist/7BVlPHsoGk6hp4FTFirXVx">
    <img src="https://img.shields.io/badge/Spotify-The_Open_Source-1DB954?style=for-the-badge&logo=spotify&logoColor=white" />
  </a>
</p>

---

I build infrastructure that's **boring on purpose** — reproducible, automated, and well-documented. Currently interning at **imec-IDLab**, one of the world's leading R&D hubs for semiconductors and other technology 5-10 years ahead of whats currently on the market, where I work on research infrastructure and a funded knowledge graph project on top of GitLab.

---

## Current Work — imec-IDLab

**Knowledge Graph layer for GitLab** *(funded research + paper)*

Large engineering teams at imec self-host GitLab across multiple research groups. A single change can have significant downstream impact — but that impact isn't queryable anywhere.

I'm building a lightweight **RDF-based knowledge graph** that sits on top of GitLab workflows, capturing company-specific ontologies: which components are high-risk, who owns what, what depends on what. Semantic metadata is automatically generated during commits and CI/CD runs — making system relationships **explicit and machine-readable** for the first time.

For engineers and AI models this enables:
- **Impact analysis** — what does this change affect?
- **Smarter debugging** — trace issues across commits, pipelines, and dependencies
- **Intelligent code review** — suggest reviewers based on impacted components
- **AI that reasons over structure** — local models query the graph instead of guessing from raw logs

This work is part of broader research into improving AI systems with knowledge graphs and will be tied to a research publication.

---

##  Featured Project — Hephaestus

A fully automated development platform. One `terraform apply` from bare metal to a running DevOps stack, built as the foundation for the GitLab platform I'll be developing at Odisee Co-Create.

**What it provisions:**
- **GitLab CE** — self-hosted Git, CI/CD, container registry
- **Prometheus + Grafana** — full observability with live GitLab CI pipeline dashboards with alert systems in place
- **GitLab Runners** — Docker-based CI executor on dedicated VM's
- **Automated backups** — daily snapshots rsynced to an offsite node

**How it works:** Terraform provisions VMs on Proxmox → waits for SSH → generates Ansible inventory → runs 4 idempotent playbooks. No manual steps.

**Stack:** Terraform · Ansible · Prometheus · Grafana · Docker · Tailscale · Cloudflare Zero Trust

→ [github.com/Michiel-VandeVelde/Hephaestus](https://github.com/Michiel-VandeVelde/Hephaestus)

---

## 🛠️ Tech Stack

**Infrastructure & Automation**

![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white)
![Ansible](https://img.shields.io/badge/Ansible-E00000?style=for-the-badge&logo=ansible&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-F2C811?style=for-the-badge&logo=linux&logoColor=black)

**Containers & Orchestration**

![Docker](https://img.shields.io/badge/Docker-4F7DF3?style=for-the-badge&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-6A5AF9?style=for-the-badge&logo=kubernetes&logoColor=white)

**CI/CD & Observability**

![GitLab CI](https://img.shields.io/badge/GitLab_CI-FC6D26?style=for-the-badge&logo=gitlab&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white)

**Knowledge & Semantic Web**

![RDF](https://img.shields.io/badge/RDF-8A2BE2?style=for-the-badge&logo=w3c&logoColor=white)
![SPARQL](https://img.shields.io/badge/SPARQL-00897B?style=for-the-badge&logo=w3c&logoColor=white)
![Linked Data](https://img.shields.io/badge/Linked_Data-E65100?style=for-the-badge&logo=w3c&logoColor=white)

*Microcredential, Linked Data — UGent, taught by Pieter Colpaert, Ruben Verborgh and Ruben Taelman*

---

## 📌 Other Work

| Repo | Description |
|---|---|
| [Imec-IDLab](https://github.com/Michiel-VandeVelde/Imec-IDLab) | Internship documentation — research infrastructure & knowledge graph development |
| [Thesis](https://github.com/Michiel-VandeVelde/Thesis) | Bachelor's thesis written at imec-IDLab |

---

<p align="center">
  Always open to collaboration on Cloud, DevOps & Open Source projects.
</p>
