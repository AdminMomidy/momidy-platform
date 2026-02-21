# Momidy Project Bible

## Goal (Phase 1)
Public website + Admin backoffice to manage public content:
- Landing, Features, Pricing, About, Contact
- FAQs, Testimonials
- Contact messages inbox

## Repo
- GitHub: (https://github.com/AdminMomidy/momidy-platform.git)

## Architecture (Monorepo)
- apps/web   (Next.js + TypeScript)
- apps/admin (Next.js + TypeScript)
- apps/api   (NestJS + TypeScript)
- packages/* (shared code later)

## Stack (Locked)
- Node: 20.20.0
- Frontend: Next.js + TypeScript + Tailwind + shadcn/ui
- Backend: NestJS (Node)
- DB: PostgreSQL
- ORM: Prisma
- Auth: Auth.js + RBAC for admin
- CI: GitHub Actions
- Local dev DB: Docker Compose (Postgres)

## Commands
- Install: npm install
- Dev: npm run dev

## Status
- [x] GitHub repo created
- [x] Repo cloned locally
- [x] Turborepo scaffold running
- [ ] Brain files committed
- [ ] apps/web created
- [ ] apps/admin created
- [ ] apps/api created