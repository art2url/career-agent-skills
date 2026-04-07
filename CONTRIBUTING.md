# Contributing

## Ways to Contribute

- Improve existing skill instructions (clarity, better examples, edge cases)
- Create new skills for uncovered career use cases
- Fix typos or inaccuracies
- Report issues when skills don't produce good results

## Skill File Format

Skills live in `skills/<skill-name>/SKILL.md`. Each skill is a single markdown file with frontmatter metadata and structured instructions that any AI agent can follow.

```markdown
---
name: skill-name
description: One-line description of what the skill does
---

# Skill Title

## Trigger
[When the agent should use this skill — keywords and user intent]

## Process
[Step-by-step execution instructions]

## Output Format
[Expected output structure]

## Rules
[Constraints and guardrails]
```

## Writing Guidelines

### Do

- Write actionable instructions, not educational content
- Keep skills to 80-120 lines — tight and focused
- Include output format templates with placeholder structure
- Add rules/constraints to prevent bad outputs
- Test with actual resumes and job descriptions
- Add SEO-rich keywords to the Trigger section for discoverability

### Don't

- Write blog posts or encyclopedic references — AI agents already have general career knowledge
- Include huge example outputs that should be generated dynamically
- Add content any AI agent would already know (what ATS stands for, why metrics matter)
- Duplicate content that exists in another skill

## Naming Skills

- Use kebab-case: `software-engineer-resume`, not `SoftwareEngineerResume`
- Lead with the most searched term: `ats-resume-checker` > `resume-checker-ats`
- Be specific: `compensation-negotiator` > `negotiator`
- Check existing skills to avoid overlap in scope

## Submitting

### Small Changes

Fork, edit, pull request with clear description.

### New Skills

1. Open an issue to discuss the idea first
2. Follow the format above
3. Keep it focused — one skill, one job
4. Test with real inputs
5. Submit PR

## Pull Request Format

- **Title**: Clear and descriptive (e.g., "Add healthcare-resume skill")
- **Description**: What changed and why
- **Testing**: How you verified it works
