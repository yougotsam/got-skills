# Got Skills

Five bundled playbooks for marketing copy, decisions, client-side data fetching, database access control, and payment webhooks.

## Import into Lovable

Go to **Settings → Skills → Add → Import from GitHub** and paste:

https://github.com/yougotsam/got-skills

The root `SKILL.md` defines **got-skills**, one routing skill that reads the relevant bundled playbook. This imports **one workspace skill**, not five separate slash commands. Use `/got-skills` with your request.

Lovable's [import documentation](https://docs.lovable.dev/features/skills#import-from-github) requires a root `SKILL.md` for a whole-repository import. Importing a collection URL does not automatically install every nested skill.

## Import individual skills instead

For separate workspace skills, import the relevant folder URL from [SKILLS_INDEX.md](SKILLS_INDEX.md). Each folder contains its own `SKILL.md`. Choose either the routing package or the individual skills to avoid overlapping guidance.

## What is actually included

- [Copywriting](skills/copywriting/SKILL.md)
- [Decide](skills/decide/SKILL.md)
- [TanStack Query](skills/tanstack-query-alternative/SKILL.md)
- [Supabase RLS and auth](skills/supabase-rls-and-auth/SKILL.md)
- [Stripe payment webhooks](skills/stripe-payment-webhooks/SKILL.md)

The earlier README and index advertised 130+ skills, but only these five playbooks are present. Related skills mentioned inside them are not bundled. These are short guidance documents; packaging validation does not establish production readiness.

## Package layout

- `SKILL.md`: Lovable-compatible root entry point.
- `skills/<name>/SKILL.md`: original playbooks, preserved in place.
- `SKILLS_INDEX.md`: inventory and individual import links.
- `SOURCES.md`: existing source attribution.
- `LICENSE`: repository license.

If using a GitHub-generated ZIP, the archive's single wrapping folder contains the root `SKILL.md`. Download a fresh archive after repository changes.

## Maintenance

Keep the root routing table and index aligned with files that actually exist. Keep the filename exactly `SKILL.md` (uppercase, singular). Re-import or update the workspace skill when changing this repository; do not assume an existing import stays synchronized with GitHub.

See [CONTRIBUTING.md](CONTRIBUTING.md) and [SOURCES.md](SOURCES.md).
