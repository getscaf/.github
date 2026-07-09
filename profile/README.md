Welcome to the getscaf organization 🏗️ — the home of Scaf and its
ecosystem of project templates and tooling that help developers scaffold,
build and evolve modern applications efficiently.

🌟 What is Scaf?

Scaf is a CLI-based template manager that simplifies project creation and
ongoing project updates. With a single command, Scaf can:

🎨 Bootstrap a new project from a GitHub template

🔄 Update existing projects created from supported templates

📦 Support any GitHub-hosted template or local path

⚙️ Offer advanced options for defaults and version selection

It ships with batteries for both Linux and macOS users and also offers Nix
support for reproducible local environments.

📦 Organization Contents

This org hosts repositories related to the Scaf ecosystem. Notable repos
include:

🛠️ scaf

The core CLI tool and manager that:

Installs and runs templates from any GitHub repo

Updates existing scoped projects

Offers options for default answers and versioned template selection

Highlights:

🍃 Simplifies bootstrapping and updating projects

🧰 Supports custom templates via GitHub URL or local path

🔁 Template choices include full-stack and AWS Lambda starters

📜 BSD-3-Clause license 📥

📘 scaf-fullstack-template (or similar)

A comprehensive full-stack project template (often used with Scaf):

🐍 Backend: Django app with production settings

⚛️ Frontend: Optional Next.js or React integration

🐘 PostgreSQL (with CloudNativePG for prod)

🧠 Redis for caching and message brokering

📦 Infra: Kubernetes manifests, Terraform bits, ArgoCD configs

🧪 Dev tooling: GitHub Actions CI/CD, Tilt, Kind, Prometheus, Grafana

📡 Automated semantic-release driven versioning

Note: The template repo structure and docs may evolve; check each template’s own
README for exact usage details.
