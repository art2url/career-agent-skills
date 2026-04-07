---
name: resume-customizer
description: Customize your resume for any job posting — reorder sections, integrate keywords, manage multiple versions, and score your match before applying
---

# Resume Customizer

## Trigger

Use when the user wants to customize their resume for a specific job posting or manage multiple resume versions.

Keywords: "customize resume", "customize resume for job", "adjust resume", "resume for this job", "target role", "specific position", "resume version", "which resume did I send", "match resume to job", "job-specific resume", "adapt resume", "resume keywords for job", "targeted resume", "resume per job"

Best used after job-fit-analyzer has identified what to emphasize.

## Process

### Step 1: Identify What to Emphasize

From the job description, extract:
- **Must-have skills** — stated as required, appear 3+ times
- **Nice-to-have skills** — stated as preferred/bonus
- **Key terminology** — exact phrases the company uses
- **Priority competencies** — what the role centers on

### Step 2: Customize the Summary

Rewrite the professional summary to mirror the job's top 3-4 requirements. Include the exact job title or close variant. Reference the user's most relevant experience.

### Step 3: Reorder for Relevance

- **Skills section**: Most relevant skills first
- **Experience bullets**: Lead each role with the bullet that best matches the target job
- **Job order**: If a less recent role is more relevant, consider reordering (keep dates visible)
- **Sections**: Move education/certs up if the role emphasizes them

### Step 4: Integrate Keywords

Add job description keywords into existing bullets naturally. Use exact phrasing where it truthfully describes the user's work. Place critical keywords in multiple locations (summary, skills, experience).

### Step 5: Trim and Focus

Remove or shrink content that doesn't support this application. Every line should earn its space by connecting to what this employer wants.

## Customizing vs. Lying

**Acceptable:** Reordering true information, using the employer's terminology for things you actually did, emphasizing certain achievements, adding context to vague statements.

**Not acceptable:** Adding skills you don't have, changing numbers, claiming titles or certifications you don't hold, inventing experiences.

## Version Management

When the user manages multiple versions:
- Maintain one **master resume** with ALL bullets and experiences as source of truth
- Each customized version pulls from the master
- Name files: `LastName_Role_Company_Date.pdf`
- Track which version went to which company
- Never edit the master directly for a single application

## Output Format

```
## Customization Plan: [Role] at [Company]

### Summary
**Current:** [original]
**Customized:** [rewritten]

### Skills Reorder
**New order:** [reordered list, additions noted]

### Experience Changes
**[Company/Role]:**
- Lead with: "[most relevant bullet]"
- Modify: "[original]" → "[customized version]"
- Add keyword: "[phrase]" to bullet about [topic]

### Keywords Added: [count]
### Estimated Match Score: [X]%
```

## Rules

- Always start from the user's real experience
- Don't keyword-stuff — language must read naturally
- Maintain ATS compatibility in all customized versions
- Document changes so the user can reference them in interviews
