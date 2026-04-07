---
name: cover-letter-writer
description: Generate personalized cover letters — connect resume experience to job requirements with industry-appropriate tone, hook openings, and gap-addressing strategy
---

# Cover Letter Writer

## Trigger

Use when the user wants to write a cover letter or application letter.

Keywords: "cover letter", "write cover letter", "cover letter generator", "application letter", "write letter for job", "cover letter for job", "cover letter template", "how to start cover letter", "cover letter opening", "personalized cover letter", "job application letter"

Best used after job-fit-analyzer to have clear talking points.

## Inputs Needed

- User's resume or key experience details
- Job description or target role details
- Company name
- Any special context: referral, career change, gap to address

## Process

### Step 1: Structure (250-400 words, 3-4 paragraphs)

**Paragraph 1 — Hook + Position (2-3 sentences)**
Open with something specific: company knowledge, mutual connection, relevant achievement, or industry insight. State the role. Never open with "I am writing to apply for..."

**Paragraph 2 — Strongest Match (3-4 sentences)**
Connect your #1 most relevant experience to their #1 requirement. Include a specific metric. Formula: [Their need] + [Your experience] + [Your result].

**Paragraph 3 — Additional Value + Gap Handling (3-4 sentences)**
Second qualification match. If there's an obvious gap, address it proactively and honestly. If no gaps, show company research and culture fit.

**Paragraph 4 — Close (2-3 sentences)**
Enthusiasm for something specific about the role/company. Suggest next step. Thank them.

### Step 2: Adjust Tone

- **Startup**: Conversational, show initiative and scrappiness
- **Enterprise**: Formal, emphasize process and scale
- **Creative roles**: Show personality, reference their brand
- **Finance/Legal**: Conservative, lead with credentials

### Step 3: Generate Alternatives

Always provide 2 opening hook options so the user can choose the approach they prefer.

## Output Format

```
## Cover Letter: [Position] at [Company]

**Strategy:**
- Strengths to highlight: [list]
- Gaps to address: [list or "none"]
- Tone: [formal/conversational/creative]

---

[Full cover letter text]

---

**Alternative opening:**
[Different hook approach]

**Talking points for interview:**
- [Point from letter to expand on]
- [Point from letter to expand on]
```

## Rules

- Never open with "I am writing to apply" or "Dear Sir/Madam"
- Don't repeat the resume — add context, personality, and narrative
- Every claim must connect to a specific result or example
- Address hiring manager by name if known; "Dear Hiring Manager" otherwise
- One specific company detail per letter proves it's not a template
- Keep to 250-400 words — respect the reader's time
