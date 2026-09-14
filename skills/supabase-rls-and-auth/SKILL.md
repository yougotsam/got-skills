---
name: supabase-rls-and-auth
description: Use when implementing row-level security and authentication. Protect data at the database layer.
source: yougotsam/lovable-skills
category: ["backend", "security", "auth"]
tags: ["supabase", "rls", "postgres"]
difficulty: advanced
version: "1.0.0"
related: ["supabase-auth-flows", "multi-tenant-backend"]
---

# Supabase RLS & Auth

Implement row-level security policies to enforce data access at the database layer.

## When to Use

Multi-user apps needing fine-grained data access control. RLS is your security foundation.

## Key Patterns

- Enable RLS on tables
- Create policies: `SELECT`, `INSERT`, `UPDATE`, `DELETE`
- Use `auth.uid()` in WHERE clauses
- Test policies before production

## Common Traps

- Infinite recursion in RLS (avoid `auth_user` table references)
- Forgetting to grant permissions to service role
- Not testing edge cases (NULL values, role transitions)

## Related Skills

- `supabase-auth-flows` — Authentication setup
- `multi-tenant-backend` — Organizations + RLS composition

---

*Source: yougotsam/lovable-skills*
