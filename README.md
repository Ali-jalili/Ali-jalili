<div align="center">

# Ali Jalili

**Frontend engineer · React, TypeScript, Next.js**

I build full-stack products where the frontend is the hard part:
multi-step forms, role-based dashboards, review workflows and server-state that stays correct.

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-ali--jalili-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ali--jalili)
[![Email](https://img.shields.io/badge/Email-ali.jalili.dev@gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:ali.jalili.dev@gmail.com)

</div>

---

## Selected work

| Project | What it is | Built with | Links |
|---|---|---|---|
| **FailStack** | Peer-reviewed incident postmortem platform. Six-step authoring flow, review workflow (`DRAFT → PENDING_REVIEW → PUBLISHED`), searchable public archive. | Next.js 16 (App Router), React 19, TypeScript, Supabase, Zod, Vitest | [Live](https://failstack.vercel.app) · [Code](https://github.com/Ali-jalili/failstack) |
| **NexusOS** | Multi-role agency dashboard (Admin / Client / Developer) with request lifecycle, project tracking and analytics. Access control enforced in the database with Row Level Security. | React, TanStack Query, Supabase, PostgreSQL | [Live](https://nexus-os-dashboard-seven.vercel.app) · [Code](https://github.com/Ali-jalili/NexusOS-Platform) |
| **FormFlow** | Form builder with drag-and-drop fields, live preview, draft/publish workflow and a responses dashboard. | React, React Hook Form, TanStack Query, Supabase | [Live](https://form-flow-phi.vercel.app) · [Code](https://github.com/Ali-jalili/FormFlow) |
| **DevDesk** | Workspace for organizing API requests, collections and environments. 240+ commits, feature-based architecture. | React, TypeScript, TanStack Query, Supabase | [Live](https://devdesk-six.vercel.app) · [Code](https://github.com/Ali-jalili/DevDesk) |

---

## How I build

```mermaid
flowchart LR
    A[Component] --> B[Custom hook]
    B --> C[Service layer]
    C --> D[(Supabase / PostgreSQL + RLS)]
```

- **Feature-based structure.** Code is grouped by product domain, not by file type.
- **Validate at both boundaries.** Zod schemas on the client and again on the server.
- **Server state belongs to a cache.** TanStack Query for fetching, invalidation and optimistic updates.
- **Security lives in the database.** Row Level Security and RPCs, not only UI guards.
- **Handle retries.** Idempotency keys so a double submit does not create two records.

---

## Stack

![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)
![TanStack Query](https://img.shields.io/badge/TanStack_Query-FF4154?style=flat-square&logo=reactquery&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Vitest](https://img.shields.io/badge/Vitest-6E9F18?style=flat-square&logo=vitest&logoColor=white)

---

## Currently working on

- End-to-end tests and CI for my projects
- Database migrations in the repos, so every project runs from a clean clone
- Deeper TypeScript patterns and production-readiness
