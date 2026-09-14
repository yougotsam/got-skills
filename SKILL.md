---
name: got-skills
description: Use when applying the Got Skills playbooks to marketing copy, product decisions, TanStack Query data fetching, Supabase authentication and row-level security, or Stripe webhook handling. Select only the bundled guidance relevant to the request.
---

# Got Skills

Route the user's request to the relevant bundled playbook. This package contains five playbooks; it does not install five separate workspace skills or provide the other skills mentioned in their related-skill lists.

## Select the playbook

Paths are relative to this SKILL.md, not to the app's source directory.

| Task | Read |
| --- | --- |
| Write or rewrite marketing pages, headlines, or calls to action | [Copywriting](skills/copywriting/SKILL.md) |
| Evaluate a product, pricing, hiring, or business decision | [Decide](skills/decide/SKILL.md) |
| Work on client-side fetching and caching with TanStack Query | [TanStack Query](skills/tanstack-query-alternative/SKILL.md) |
| Work on Supabase authentication or row-level security | [Supabase RLS and auth](skills/supabase-rls-and-auth/SKILL.md) |
| Handle Stripe webhook events | [Stripe payment webhooks](skills/stripe-payment-webhooks/SKILL.md) |

## Apply the guidance

1. Identify the requested outcome and read the matching bundled file before applying its guidance. For a mixed task, read only the files needed.
2. Treat these as concise playbooks, not complete API documentation or proof of production readiness. For implementation, inspect the existing code and installed versions, and verify version-sensitive details against the provider's current official documentation.
3. Preserve the user's requested scope and the project's working architecture. A review or decision request does not authorize code changes, deployments, payments, or database mutations.
4. Treat related-skill names inside the playbooks as external suggestions, not bundled dependencies. Do not claim to load them or install anything automatically.
5. If a bundled file is unavailable in the imported package, report that limitation rather than inventing its instructions.
6. Return the requested result concisely. For implementation work, state what changed, what was tested, and what remains unverified. Do not claim an integration works based only on this guidance.
