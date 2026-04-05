<div align="center">

# GitOps Fundamentals with Flux

**From Manual Deployments to AI-Assisted Operations**

[![Workshop](https://img.shields.io/badge/Workshop-DevOps%20Pro%20Europe%202026-D4A843?style=for-the-badge&labelColor=0A0F1C)](https://workshop.platformfix.com/gitops/)
[![Instructor](https://img.shields.io/badge/Instructor-Steve%20Wade-D4A843?style=for-the-badge&labelColor=0A0F1C)](https://www.linkedin.com/in/stevendavidwade/)

</div>

---

This is your personal GitOps repository. Over the next 6 hours, you'll build a complete GitOps pipeline in this repo, from first deployment to encrypted secrets to AI-assisted debugging.

By the end of the day, this repo will contain a working GitOps setup you can fork, adapt, and use at your organisation on Monday.

## What You'll Build

| Lab | What Gets Added |
|-----|----------------|
| **0** | Flux Operator bootstrap. Flux manages itself from this repo. |
| **1** | First application deployment via GitOps. Push to Git, watch it deploy. |
| **2** | Multi-environment overlays. Dev, staging, production from one codebase. |
| **3** | Helm integration. HelmRepository and HelmRelease managed by Flux. |
| **4** | Encrypted secrets with SOPS. Secrets in Git, safely. |
| **5** | Monitoring, alerting, and troubleshooting patterns. |

## Repository Structure

```
.
├── clusters/           # Flux configuration (FluxInstance, Kustomizations)
├── apps/               # Application deployments (raw YAML, overlays, HelmReleases)
├── infrastructure/     # Shared infrastructure (HelmRepositories, namespaces)
└── notes.md            # Your scratchpad. Take notes. Compare scores. Plan your adoption.
```

**Start empty. End complete.** Every file in this repo will be created by you during the workshop.

## Quick Links

| Resource | Link |
|----------|------|
| Workshop Labs | [workshop.platformfix.com/gitops](https://workshop.platformfix.com/gitops/) |
| Your Environment | [Access your bastion and cluster](https://workshop.platformfix.com/gitops/access/) |
| Flux Documentation | [fluxcd.io](https://fluxcd.io/) |
| Flux Operator | [fluxoperator.dev](https://fluxoperator.dev/) |

## After the Workshop

| Resource | Description |
|----------|-------------|
| [The 10 GitOps Landmines](https://guides.platformfix.com/gitops-10-landmines) | Free guide with the 25-question readiness audit. Share it with your team. |
| [Production Kustomize Template](https://github.com/swade1987/flux2-kustomize-template) | The template Steve uses with clients. CI, validation, multi-env. Fork it. |
| [Production SOPS Template](https://github.com/swade1987/flux2-sops-template) | Encrypted secrets for production. Pre-commit hooks that prevent leaks. |
| [Book a Platform Review](https://calendly.com/platformfixer/devops-pro) | 30 minutes. You describe your stack. I tell you what I'd delete first. |

---

<div align="center">

**Platform Fix** - Delete before you add.

[LinkedIn](https://www.linkedin.com/in/stevendavidwade/) · [Newsletter](https://newsletter.platformfix.com)

</div>
