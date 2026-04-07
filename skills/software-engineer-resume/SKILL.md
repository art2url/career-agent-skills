---
name: software-engineer-resume
description: Build a software engineer resume that gets interviews — format tech stacks, write metrics-driven bullets, showcase projects, and optimize your GitHub profile
---

# Software Engineer Resume

## Trigger

Use when the user is applying for technical roles: software engineering, data engineering/science, DevOps/SRE, or technical PM.

Keywords: "software engineer resume", "developer resume", "SWE resume", "tech resume", "engineering resume", "data science resume", "DevOps resume", "backend developer resume", "frontend developer resume", "full stack resume", "programmer resume", "GitHub profile", "technical skills section", "coding resume", "IT resume", "software developer resume"

## Structure

Recommended section order:
1. Contact — include GitHub and portfolio links
2. Summary — optional, helpful for senior roles
3. Technical Skills — critical for ATS
4. Experience — technical achievements with scale
5. Projects — especially important for early career
6. Education
7. Certifications — if relevant

## Process

### Step 1: Structure Technical Skills

Organize by category:
```
Languages: Python, TypeScript, Go, SQL
Frameworks: React, Node.js, FastAPI, Django
Databases: PostgreSQL, Redis, MongoDB, Elasticsearch
Cloud/Infra: AWS (EC2, S3, Lambda), Docker, Kubernetes, Terraform
Tools: Git, GitHub Actions, Datadog, Grafana
```

Rules:
- Only list tech you can discuss in an interview
- Order by relevance to target role
- Be specific on cloud (list services, not just "AWS")
- Omit: Microsoft Office, operating systems (unless DevOps), skill bars/ratings, tech you touched once

### Step 2: Write Technical Bullets

Formula: **[Action Verb] + [Technical What] + [Scale/Performance] + [Tech Used]**

Key metrics:
- **Scale**: DAU/MAU, requests/sec, data volume (TB/day)
- **Performance**: latency reduction, uptime %, load time
- **Efficiency**: cost savings, deployment time, automation hours saved
- **Business**: revenue impact, conversion improvement, user growth

Examples:
- **SWE**: "Architected auth microservice (OAuth 2.0, JWT) serving 500K+ DAU, reducing login latency from 5s to 2s"
- **Data**: "Built ETL pipeline processing 100M+ events/day (Kafka, Spark), reducing data latency from hours to minutes"
- **DevOps**: "Implemented IaC with Terraform, reducing provisioning from 2 days to 30 minutes across 200+ services"
- **Tech PM**: "Led API platform roadmap for 10K+ developers, driving 40% increase in API adoption"

### Step 3: Projects Section

Format:
```
Project Name | Tech Stack | Link
- What it does + technical highlight
- Scale or usage metric
```

Good projects: real users, open-source contributions, solve real problems, show system design thinking.

Skip: tutorial follow-alongs, trivial to-do apps, incomplete projects.

### Step 4: GitHub Profile

Recommend:
- Pin 6 best repositories
- Add profile README
- Ensure pinned repos have complete READMEs (what it does, how to run, tech used)
- Active contribution graph

## Output Format

```
## Software Engineer Resume Review

### Skills Restructure
[Reorganized by category]

### Bullet Improvements
**Original:** "[weak bullet]"
**Improved:** "[technical bullet with metrics]"

### Projects to Highlight
[Suggestions]

### GitHub Recommendations
- [ ] [action]
```

## Rules

- Generic bullets like "built features" waste space — every bullet needs technical specificity
- Every bullet needs a scale or performance metric
- Don't claim technologies you can't whiteboard
- Balance technical detail with business impact
- ATS rules still apply — no fancy formatting
