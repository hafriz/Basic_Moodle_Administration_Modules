# Basic Moodle Administration Modules

This repository contains modular Moodle administration training materials for technical staff, LMS administrators, system administrators, and IT support teams.

## Available Training Packages

| Package | Level | Duration | Purpose |
|---|---:|---:|---|
| [Moodle Administration Basics](moodle-administration-basics/README.md) | Beginner to intermediate | 1 day | Introduces Moodle administration concepts, daily support tasks, core technical components, basic performance concepts, customization, maintenance, and troubleshooting. |
| [Moodle Administration Advance](moodle-administration-advance/README.md) | Intermediate to advanced | 2 days | Expands into advanced architecture, security, scalability, automation, integrations, upgrade planning, disaster recovery, and operational troubleshooting. |

## Repository Structure

```text
.
├── moodle-administration-basics/
│   ├── README.md
│   ├── training-overview.md
│   ├── modules/
│   └── supporting trainer resources
└── moodle-administration-advance/
    ├── README.md
    ├── training-overview.md
    ├── modules/
    └── supporting trainer resources
```

## How to Use These Materials

- Start with the basics package when learners are new to Moodle administration or need a structured refresher.
- Use the advance package for technical staff responsible for production operations, scaling, security, integrations, upgrades, and incident response.
- Each module is written as Markdown so trainers can export, reorder, customize, or distribute topics independently.
- Adapt examples, timing, and demonstrations to match your Moodle version, hosting model, institutional policy, and available administrative access.

## Recommended Learning Path

1. Complete [Moodle Administration Basics](moodle-administration-basics/README.md).
2. Practice routine administrative tasks in a non-production Moodle site.
3. Complete [Moodle Administration Advance](moodle-administration-advance/README.md).
4. Build an institution-specific runbook for monitoring, upgrades, backups, integrations, and incident response.

## GitHub Pages Documentation

This repository is configured as a MkDocs site for publishing the Moodle administration training materials to GitHub Pages.

### Local Preview

```bash
pip install -r requirements.txt
mkdocs serve
```

Open the local preview URL shown by MkDocs, usually `http://127.0.0.1:8000/`.

### Build Locally

```bash
mkdocs build --strict
```

The generated static site is written to the ignored `site/` directory.

### Deploy to GitHub Pages

A GitHub Actions workflow builds and deploys the MkDocs site when changes are pushed to the `main` branch. In the repository settings, set **Pages** to use **GitHub Actions** as the build and deployment source. After the workflow completes, the site will be available at the repository GitHub Pages URL, typically:

```text
https://<github-username>.github.io/<repository-name>/
```
