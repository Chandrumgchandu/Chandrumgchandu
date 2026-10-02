<h1 align="center">Chandru M G</h1>
<p align="center"><strong>DevOps / Platform Engineering Portfolio</strong></p>

<p align="center">
Hands-on projects covering CI/CD, containers, Kubernetes delivery, DevSecOps checks, Java/Spring applications, Node.js services, and operations documentation.
</p>

---

## Portfolio Focus

This GitHub profile is organized around practical DevOps and platform engineering evidence. The public repositories show application code, delivery pipelines, containerization, environment-based configuration, Kubernetes manifests, runbooks, and documentation that a reviewer can inspect directly.

I avoid presenting forked or placeholder repositories as primary experience. The strongest projects are listed first, with claims limited to what is visible in the repositories.

## Core Skills Demonstrated

| Area | Evidence in public repositories |
|---|---|
| CI/CD | Jenkins pipeline stages, GitHub Actions build/test workflow, Maven and npm validation. |
| Containers | Dockerfiles, Docker Compose local stack, image-tagging and registry workflow notes. |
| Kubernetes | Deployment, Service, Namespace manifests, rollout verification, probes, resource controls. |
| DevSecOps | SonarQube quality gate, Trivy image scan stage, credential hygiene improvements. |
| Application delivery | Java/Spring Boot, Node.js/Express, PostgreSQL-backed services, frontend/backend separation. |
| Operations | Runbooks, rollout checks, rollback commands, troubleshooting notes, configuration boundaries. |

## Strongest Public Projects

### [Employee Portal — DevSecOps Delivery Pipeline](https://github.com/Chandrumgchandu/employee-portal)
Spring Boot application with a Jenkins delivery pipeline covering compile, tests, SonarQube analysis, quality gate, Maven package, Nexus publishing, Docker build, Trivy scan, Amazon ECR push, and Kubernetes rollout verification.

Visible evidence: `Jenkinsfile`, `Dockerfile`, `k8s/` manifests, and `docs/runbook.md`.

### [E-Book Store — Full-Stack Application](https://github.com/Chandrumgchandu/ebook-store)
Full-stack project with a Spring Boot backend, PostgreSQL persistence, and Vite frontend. The backend configuration uses environment variables for database settings, and the architecture notes define the application boundary and DevOps extension path.

Visible evidence: `backend/`, `frontend/`, `architecture.md`, Maven/npm lock files, and environment-driven Spring configuration.

### [Todo Application — Full-Stack DevOps Lab](https://github.com/Chandrumgchandu/todo_app_jenkins)
Node.js/Express Todo API with PostgreSQL, JWT auth, Docker packaging, a Compose-based local stack, and environment-based runtime configuration.

Visible evidence: `backend/`, `frontend/`, `docker-compose.yml`, `.env.example`, and syntax-check test script.

### [DevOps / SRE Lab](https://github.com/Chandrumgchandu/devops-lab)
Operations learning lab with Spring Boot API code, API tests, and structured notes on troubleshooting, repository verification, backend foundations, and project state.

Visible evidence: Spring Boot backend, `IncidentSummaryApiTest`, and `docs/knowledge-base/`.

### [Ecommerce Platform — Spring Boot CI/CD Sample](https://github.com/Chandrumgchandu/Ecommerce-Platform)
Compact Spring Boot sample with Maven tests, Docker packaging, and GitHub Actions validation. Generated JAR files have been removed from source control to keep the repo clean.

Visible evidence: `.github/workflows/build.yml`, `app/store/Dockerfile`, Maven project files, and tests.

## Deployed Private Project Demo

### [Milk Ledger — Dairy Collection and Payments Platform](https://milk-ledger-pink.vercel.app)
Private Flask/Supabase project with a public Vercel demo page. It demonstrates a Render backend, Vercel frontend, Supabase migrations, health checks, GitHub Actions backend CI, Docker build validation, WhatsApp webhook support, and an operations runbook.

Use the demo link for review; source access can be granted separately when appropriate.

## Repository Triage

| Category | Repositories |
|---|---|
| Portfolio-grade | `employee-portal` |
| Supporting labs/projects | `ebook-store`, `todo_app_jenkins`, `devops-lab`, `Ecommerce-Platform` |
| Forks/reference only | `e-commerce-platform`, `my-java-devops-assignment` |
| Small/experimental | `Devops-todo-app`, `Todo_app`, `myapps`, `End-to-end-CI-CD`, `End-to-end-CI-CD-ansible`, `git-conflict-demo` |
| Private/internal labs | `ansible-production-lab`, `Devops-Pattern`, `End-to-end-CI-CD-gitops`, `milk-ledger`, `terraform-production-lab` |

## Delivery Philosophy

```text
Build -> Test -> Analyze -> Package -> Scan -> Publish -> Deploy -> Verify -> Document
```

My preferred direction is practical and evidence-based: keep secrets out of source control, make builds reproducible, validate before deployment, add rollout and rollback commands, and document the operational path clearly enough for another engineer to follow.

## Current Improvement Path

- Add automated tests to the smaller Node.js and frontend projects.
- Add Kubernetes manifests and health probes where application scope justifies them.
- Add Terraform/Ansible evidence only where the repo actually contains working IaC or automation.
- Keep forks and experiments separate from the main portfolio story.
- Continue improving README quality so each project can be understood quickly by hiring managers and engineers.

---

<p align="center">
<a href="https://github.com/Chandrumgchandu?tab=repositories">Explore all repositories</a>
</p>
