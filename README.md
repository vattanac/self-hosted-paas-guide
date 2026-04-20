# Self-Hosted PaaS Guide

🔗 **Live site:** [https://self-hosted-paas-guide.netlify.app/](https://self-hosted-paas-guide.netlify.app/)
🔗 **ArgoCD Guide:** [https://self-hosted-paas-guide.netlify.app/argocd/](https://self-hosted-paas-guide.netlify.app/argocd/)

An interactive, single-page comparison of four deployment platforms — **Canine**, **Coolify**, **Dokploy**, and **Railway** — covering setup, cost, and a step-by-step live demo walkthrough for each.

## What's inside

[index.html](index.html) is a self-contained static page with:

- Side-by-side comparison cards for all four platforms
- Underlying engine, setup time, and monthly cost at a glance
- Complete setup instructions per platform
- A 5-step live demo walkthrough per platform

| Platform | Focus |
| --- | --- |
| 🐶 Canine | Kubernetes-based self-hosted PaaS |
| ⚡ Coolify | Docker-based open-source Heroku alternative |
| 💗 Dokploy | Lightweight self-hosted deployment platform |
| 🚆 Railway | Managed cloud PaaS (reference baseline) |

## Run it

No build step — it's pure HTML/CSS/JS.

```bash
open index.html
```

Or serve locally:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Structure

```
.
├── index.html   # The entire comparison page (styles + logic inlined)
└── README.md
```
