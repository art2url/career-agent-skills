# Career Agent Skills

AI agentic skills for resume building, job search strategy, and career development. Works with Claude Code, Cursor, Windsurf, Codex, Gemini CLI, OpenCode, and 30+ other AI agents.

Each skill gives your AI agent actionable instructions for specific career tasks — from ATS checks to compensation negotiation.

## Available Skills

| Skill | Description |
| --- | --- |
| [ats-resume-checker](skills/ats-resume-checker) | Check and fix ATS compatibility — formatting, bullet points with metrics, keyword matching, readiness scoring |
| [resume-customizer](skills/resume-customizer) | Customize resumes for any job posting — keyword integration, section reordering, version management, match scoring |
| [job-fit-analyzer](skills/job-fit-analyzer) | Analyze job postings to see if you're a fit — match score, skill gaps, red flags, application strategy |
| [cover-letter-writer](skills/cover-letter-writer) | Write personalized cover letters — hook openings, experience-to-requirements mapping, industry-appropriate tone |
| [linkedin-profile-booster](skills/linkedin-profile-booster) | Boost LinkedIn for recruiter visibility — headline rewriting, About section, keyword placement, profile audit |
| [mock-interview-coach](skills/mock-interview-coach) | Practice mock interviews — STAR story building, behavioral answers, "tell me about yourself" scripts, reference prep |
| [compensation-negotiator](skills/compensation-negotiator) | Negotiate full compensation — market rate research, counter-offer emails, total comp breakdown, offer comparison |
| [career-pivot-planner](skills/career-pivot-planner) | Plan a career pivot — transferable skill mapping, experience translation, transition narratives, bridge credentials |
| [software-engineer-resume](skills/software-engineer-resume) | Build software engineer resumes — tech stack formatting, metrics-driven bullets, project showcasing, GitHub profile |
| [executive-leadership-resume](skills/executive-leadership-resume) | Write executive resumes — VP/Director/CxO positioning, leadership branding, transformation narratives |
| [academic-research-cv](skills/academic-research-cv) | Build academic CVs — publications, grants, teaching, service sections formatted by discipline convention |
| [portfolio-case-study](skills/portfolio-case-study) | Write portfolio case studies — structured project narratives, before/after results, ATS-safe creative resumes |

## Installation

### CLI Install

```bash
# Install all skills globally
npx skills add art2url/career-agent-skills -g -y

# Install to current project only
npx skills add art2url/career-agent-skills -y

# List installed skills
npx skills list
```

### Manual Install

```bash
git clone https://github.com/art2url/career-agent-skills.git

# Copy to your agent's skills directory
cp -r career-agent-skills/skills/* ~/.<your-agent>/skills/
```

### Uninstall

```bash
npx skills remove art2url/career-agent-skills
```

## Usage

Ask your AI agent for help with any career task:

```text
"Check my resume for ATS issues"       → ats-resume-checker
"Customize my resume for this job"     → resume-customizer
"Am I a fit for this role?"            → job-fit-analyzer
"Write a cover letter"                 → cover-letter-writer
"Boost my LinkedIn profile"            → linkedin-profile-booster
"Practice interview questions"         → mock-interview-coach
"Help me negotiate this offer"         → compensation-negotiator
```

## Skill Categories

### Resume Building

- `ats-resume-checker` — Check ATS compatibility, fix formatting, rewrite bullets with metrics, score readiness
- `resume-customizer` — Customize for specific job postings, keyword integration, version management
- `software-engineer-resume` — SWE, data, DevOps, and PM resumes with tech stack formatting and project showcasing
- `executive-leadership-resume` — VP, Director, and C-suite resumes with leadership branding and transformation narratives
- `academic-research-cv` — Faculty, research, and postdoc CVs with publications, grants, and teaching

### Job Search

- `job-fit-analyzer` — Match scoring, skill gap breakdown, red flag detection, application strategy
- `cover-letter-writer` — Personalized cover letters with hook openings and gap-addressing strategy
- `linkedin-profile-booster` — Recruiter visibility, headline rewriting, keyword placement, profile audit

### Interview & Negotiation

- `mock-interview-coach` — STAR stories, behavioral answers, "tell me about yourself" scripts, reference prep
- `compensation-negotiator` — Counter-offer emails, market research, total comp breakdown, multi-offer comparison

### Career Development

- `career-pivot-planner` — Transferable skill mapping, industry translation, transition narratives, bridge credentials
- `portfolio-case-study` — Project case studies with before/after results, ATS-safe creative resumes

## Contributing

PRs and issues welcome. See [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines.

## License

MIT License. See [LICENSE](LICENSE) for details.
