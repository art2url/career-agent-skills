---
name: job-fit-analyzer
description: Analyze any job posting to see if you're a fit — match score, skill gap breakdown, red flag detection, and whether it's worth applying
---

# Job Fit Analyzer

## Trigger

Use when the user wants to analyze a job posting, know if they should apply, or understand their fit for a role.

Keywords: "am I a fit", "job fit", "should I apply", "am I qualified", "analyze this job", "analyze job posting", "job description", "job requirements", "qualification check", "match score", "skill gap", "is this job right for me", "job red flags", "do I qualify", "job match"

Use BEFORE resume-customizer to determine if customizing is worth the effort.

## Process

### Step 1: Extract Requirements

Parse the job description into:
- **Required** (must-have): stated as required/essential/minimum qualifications
- **Preferred** (nice-to-have): stated as bonus/preferred/ideal
- **Implicit**: inferred from the responsibilities section

For each, note: hard skills, soft skills, years of experience, education, certifications, domain knowledge.

### Step 2: Calculate Match Score

```
Required match  = matched required / total required
Preferred match = matched preferred / total preferred
Overall = (required × 0.7) + (preferred × 0.3)
```

Interpretation:
- **85%+**: Strong fit — apply immediately
- **70-84%**: Good fit — apply with targeted resume
- **55-69%**: Stretch role — apply if motivated
- **<55%**: Under-qualified — skip unless dream job

### Step 3: Gap Analysis

Classify each missing requirement:
- **Dealbreaker**: Required license/clearance/degree you can't obtain
- **Addressable**: Significant gap you can explain in cover letter
- **Minor**: Easy to learn or close enough to dismiss

### Step 4: Red Flag Scan

Flag warning signs neutrally:
- Vague responsibilities or scope creep ("wear many hats")
- Culture signals ("rockstar", "family", "hustle")
- Compensation opacity ("competitive salary" with no range, equity-heavy)
- Role instability (reposted multiple times, vague about why it's open)

### Step 5: Recommend Strategy

Based on match score and gaps:
- Apply / Skip / Apply with caveats
- Which experiences to emphasize
- Gaps to address in cover letter
- Keywords to add to resume
- Estimated customization effort (quick tweak vs. significant rework)

## Output Format

```
## Job Analysis: [Title] at [Company]

**Match Score: X%** — [STRONG FIT / GOOD FIT / STRETCH / SKIP]

### Requirements Breakdown
| Requirement | Status | Notes |
|---|---|---|
| [Skill] | ✅ Match | [your evidence] |
| [Skill] | ❌ Gap | [severity + strategy] |
| [Skill] | ⚠️ Partial | [explanation] |

### Strengths to Emphasize
1. [Top selling point for this role]
2. [Second strongest match]
3. [Third]

### Gaps to Address
- [Gap]: [How to handle in resume/cover letter]

### Red Flags
- [Flag]: [What it might mean]

### Application Strategy
- Resume focus: [what to emphasize]
- Cover letter: [key points to address]
- Timeline: [urgency based on posting age]
```

## Rules

- Be honest about match — don't encourage applying to clearly wrong roles
- Distinguish "required" from "preferred" carefully (many JDs inflate requirements)
- Years-of-experience requirements are often flexible (±2 years is normal)
- If the job description is vague, flag that as a concern itself
