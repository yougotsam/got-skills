---
name: tanstack-query-alternative
description: Use when adding client-side data fetching with TanStack Query. Lovable's default data layer.
source: yougotsam/lovable-skills
category: ["frontend", "data-fetching"]
tags: ["tanstack", "query", "react"]
difficulty: intermediate
version: "1.0.0"
related: ["tanstack-mutations-and-invalidation", "tanstack-infinite-queries"]
---

# TanStack Query — Primary Patterns

Use TanStack Query as Lovable's default data layer for client-side fetching, caching, and synchronization.

## When to Use

Adding any client-side data fetching: lists, forms, real-time subscriptions, dependent queries.

## Key Patterns

- Query keys: `['posts', id]`, `['users', userId, 'posts']`
- Fetchers: `const { data } = useQuery({ queryKey, queryFn })`
- Defaults: `staleTime`, `gcTime` for caching strategy
- Hooks: `useQuery`, `useQueries`, `useSuspenseQuery`

## Related Skills

- `tanstack-mutations-and-invalidation` — Mutations and cache updates
- `tanstack-infinite-queries` — Pagination patterns
- `tanstack-prefetch-and-hydration` — Performance optimization

---

*Source: yougotsam/lovable-skills*
