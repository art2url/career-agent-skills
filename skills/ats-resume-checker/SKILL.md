---
name: ats-resume-checker
description: Check and fix resume ATS compatibility — scan for formatting issues, rewrite weak bullets with metrics, match keywords to job descriptions, score overall readiness
---

# ATS Resume Checker

## Trigger

Use when the user wants to check, fix, optimize, or review their resume for ATS compatibility — including formatting issues, weak bullets, missing metrics, or keyword gaps.

Keywords: "check resume", "ats check", "ats resume checker", "ats score", "ats scan", "resume scanner", "is my resume ats friendly", "optimize resume", "improve resume", "fix my resume", "resume not getting interviews", "resume not working", "add metrics to resume", "format resume", "resume score", "applicant tracking system", "resume keywords", "resume bullet points", "one-page resume"

## Process

### Step 1: Assess

Scan for issues in priority order:

1. **ATS blockers** — tables, columns, text boxes, images, headers/footers with contact info, non-standard fonts, embedded graphics
2. **Weak bullets** — passive language ("responsible for", "helped with"), missing metrics, duties instead of achievements
3. **Keyword gaps** — if a job description is provided, check for missing required terms
4. **Formatting** — inconsistent dates, mixed fonts/sizes, poor hierarchy, wrong length
5. **Section issues** — missing summary, missing skills section, non-standard headers

### Step 2: Fix ATS Issues

- Single-column layout only
- Standard headers: "Professional Experience", "Education", "Skills", "Summary"
- Contact info in document body, never in headers/footers
- Standard fonts (Arial, Calibri, Georgia, Times New Roman), 10-12pt body
- Simple bullet characters (-, *)
- Consistent date format (Mon YYYY)
- File naming: `FirstName_LastName_Resume.pdf`

### Step 3: Rewrite Bullets

Every bullet follows: **[Action Verb] + [What You Did] + [Measured Result] + [Scale/Context]**

- Start with a strong verb (Led, Built, Grew, Reduced, Launched — never "Responsible for" or "Helped with")
- Every bullet needs at least one number
- 1-2 lines max per bullet
- Show achievements, not duties

When the user says "I don't have numbers" — find metrics through:
- **Scale**: team size, budget, customers, projects managed
- **Change**: before/after comparison, percentage improvement
- **Volume**: items processed per time period, annual totals
- **Estimates**: use "~", ranges ("8-12"), or "X+" for conservative approximations

### Step 4: Optimize Sections

**Summary** (3-4 sentences): [Role] + [years + domain] + [key skills] + [top achievement]. Skip for entry-level with straightforward background.

**Skills**: Relevant hard skills only, grouped by category for 10+ skills, ordered by relevance to target role. Omit Microsoft Office and generic soft skills.

**Experience**: 4-6 bullets for recent roles, 2-3 for older. Lead each role with strongest bullet.

**Education**: Degree, school, year. GPA only if 3.5+. Coursework only for recent graduates.

**Length**: 1 page for 0-10 years, 2 pages for 10+ years.

### Step 5: Keyword Match (if job description provided)

- Extract required skills from the job description
- Check each against the resume (exact match and synonyms)
- Place missing keywords naturally in summary, skills, and bullets
- Target 80%+ match on required skills

## Output Format

```
## Resume Review

**Overall Score:** X/100
**ATS Compatibility:** Pass/Fail — [issues if any]
**Keyword Match:** X% (if JD provided)

### Critical Fixes
1. [Most important fix]
2. [Next fix]

### Bullet Improvements

**Original:** "[weak bullet]"
**Improved:** "[strong bullet]"
**Why:** [what changed]

[Repeat for each weak bullet]

### Section Recommendations
[Any structural changes needed]
```

## Rules

- Never fabricate experience or inflate numbers
- Suggest estimates only with clear markers (~, +, ranges)
- Preserve the user's voice — improve, don't rewrite personality out
- If no job description provided, optimize for general strength
