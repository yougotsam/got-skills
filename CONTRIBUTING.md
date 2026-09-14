# Contributing

Got Skills welcomes PRs for:

- Bug fixes in existing skills
- Syncing updates from source repos
- New skills (must be production-tested, recurring, portable)
- Documentation improvements

## Skill Template

```markdown
---
name: skill-name
description: Use when [specific trigger].
source: yougotsam/got-skills
category: ["category"]
tags: ["tag1", "tag2"]
difficulty: intermediate
version: "1.0.0"
---

# Skill Title

One paragraph on what + why.

## When to Use

Specific triggers.

## Instructions

Step-by-step or key patterns.

## Avoid

- Anti-pattern 1
```

## Process

1. Write skill following template
2. Test in Lovable, Cursor, or Claude
3. Open PR with example prompts
4. Maintainers review for quality + scope

---

**Quality over quantity.** We reject skills that are one-off, unfocused, or not battle-tested.
