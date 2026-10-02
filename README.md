<h1 align="center">Chandru M G</h1>
<p align="center"><strong>DevOps / Platform Engineer | CI/CD, Kubernetes, Cloud Delivery, DevSecOps</strong></p>

<p align="center">
Portfolio organized for senior DevOps review: production-style pipelines, container delivery, Kubernetes manifests, environment-driven configuration, operational runbooks, and one product-minded private demo.
</p>

---

## Professional Positioning

I use this GitHub profile to show practical DevOps and platform engineering evidence. The strongest repositories are organized so a hiring manager or engineering reviewer can quickly understand the application, delivery flow, deployment model, and operational thinking behind each project.

The account is intentionally separated into primary portfolio projects, supporting labs, small experiments, forks/reference repos, and private/internal work. I keep claims tied to repository evidence instead of presenting every repo as production experience.

## Senior DevOps Evidence

| Area | Evidence available in repositories |
|---|---|
| CI/CD engineering | Jenkins pipelines, GitHub Actions workflows, build/test/package stages, deployment checks. |
| Containers | Dockerfiles, Docker Compose local stacks, image build flow, registry/publish notes. |
| Kubernetes delivery | Namespace, Deployment, Service manifests, probes, resources, rollout verification and rollback notes. |
| DevSecOps | SonarQube quality gate, Trivy image scan stage, credential hygiene improvements, environment-based config. |
| Application support | Java/Spring Boot, Node.js/Express, Python/Flask, PostgreSQL/Supabase-backed services. |
| Operations | Runbooks, health checks, troubleshooting notes, rollback commands, service ownership boundaries. |
| Product thinking | Milk Ledger private product demo for dairy collection, farmer records, payments, and operational readiness. |

## Strongest Public Projects

### [Employee Portal — DevSecOps Delivery Pipeline](https://github.com/Chandrumgchandu/employee-portal)
Spring Boot application with a Jenkins delivery pipeline covering compile, tests, SonarQube analysis, quality gate, Maven package, Nexus publishing, Docker build, Trivy scan, Amazon ECR push, and Kubernetes rollout verification.

Evidence to review: `Jenkinsfile`, `Dockerfile`, `k8s/`, and `docs/runbook.md`.

### [E-Book Store — Full-Stack Application](https://github.com/Chandrumgchandu/ebook-store)
Spring Boot backend, PostgreSQL persistence, and Vite frontend. The backend uses environment variables for database settings, and the architecture notes describe the application boundary and DevOps extension path.

Evidence to review: `backend/`, `frontend/`, `architecture.md`, Maven/npm lock files, and environment-driven Spring configuration.

### [Todo Application — Full-Stack DevOps Lab](https://github.com/Chandrumgchandu/todo_app_jenkins)
Node.js/Express Todo API with PostgreSQL, JWT auth, Docker packaging, Docker Compose local stack, and runtime configuration through environment variables.

Evidence to review: `backend/`, `frontend/`, `docker-compose.yml`, `.env.example`, and backend validation script.

### [DevOps / SRE Lab](https://github.com/Chandrumgchandu/devops-lab)
Operations learning lab with Spring Boot API code, API tests, and structured notes on troubleshooting, repository verification, backend foundations, and project state.

Evidence to review: Spring Boot backend, `IncidentSummaryApiTest`, and `docs/knowledge-base/`.

### [Ecommerce Platform — Spring Boot CI/CD Sample](https://github.com/Chandrumgchandu/Ecommerce-Platform)
Compact Spring Boot sample with Maven tests, Docker packaging, and GitHub Actions validation. Generated JAR files were removed from source control to keep the repository clean.

Evidence to review: `.github/workflows/build.yml`, `app/store/Dockerfile`, Maven project files, and tests.

## Product Demo

### [Milk Ledger — Dairy Collection and Payments Platform](https://milk-ledger-pink.vercel.app)
Private Flask/Supabase product demo with a public Vercel landing page. The project is aimed at a real local-business workflow: farmer records, daily milk collection entries, payment tracking, reporting, health checks, and operational deployment notes.

Platform evidence in the private repo includes Render backend configuration, Vercel frontend configuration, Supabase migrations, backend tests, Docker build validation, GitHub Actions CI, WhatsApp webhook support, and an operations runbook.

Use the demo link for resume review. Source access can be granted separately when appropriate.

## Repository Triage

| Category | Repositories |
|---|---|
| Primary portfolio | `employee-portal`, `ebook-store`, `todo_app_jenkins`, `devops-lab`, `Ecommerce-Platform` |
| Product/private demo | `milk-ledger` |
| Supporting labs | `Devops-todo-app`, `Todo_app`, `myapps`, `End-to-end-CI-CD` |
| Forks/reference only | `e-commerce-platform`, `my-java-devops-assignment` |
| Empty or internal labs | `End-to-end-CI-CD-ansible`, `git-conflict-demo`, `ansible-production-lab`, `Devops-Pattern`, `End-to-end-CI-CD-gitops`, `terraform-production-lab` |

## Delivery Philosophy

```text
Understand the business workflow
  -> make configuration safe
  -> build repeatable CI/CD
  -> containerize the service
  -> scan and validate
  -> deploy with rollback path
  -> monitor health
  -> document operations
```

I like DevOps work that connects engineering discipline with business usefulness: reliable releases, clean handover, recoverable systems, clear documentation, and a product mindset where the software solves an actual workflow.

## Manual GitHub UI Actions To Complete

These actions are best done from GitHub's UI because they affect account presentation rather than repository code:

1. Pin the 3-5 strongest repositories: `employee-portal`, `ebook-store`, `todo_app_jenkins`, `devops-lab`, and `Ecommerce-Platform`.
2. Keep forks unpinned so they do not look like primary portfolio work.
3. Add short repository descriptions for the primary projects.
4. Add topics such as `devops`, `ci-cd`, `jenkins`, `docker`, `kubernetes`, `spring-boot`, `nodejs`, `postgresql`, and `devsecops` where accurate.
5. Confirm the Milk Ledger backend health before using the demo link in a resume.

---

<p align="center">
<a href="https://github.com/Chandrumgchandu?tab=repositories">Explore all repositories</a> | <a href="https://milk-ledger-pink.vercel.app">View Milk Ledger Demo</a>
</p>
