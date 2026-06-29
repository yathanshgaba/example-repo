# example-repo AGENTS.md

<!-- codex-project-brain:start -->
## Codex And Lovable Brain Layer

Use Obsidian as the active brain layer for this repo, not as a passive archive.

### Before Dev Work

- Read `/Users/yathansh.gaba/Documents/Codex/Yathansh-Ops-Vault/Maps/Brain Home.md`.
- Read `/Users/yathansh.gaba/Documents/Codex/Yathansh-Ops-Vault/Maps/Development Brain MOC.md`.
- Read `/Users/yathansh.gaba/Documents/Codex/Yathansh-Ops-Vault/Projects/_all-projects-index.md`.
- Read `/Users/yathansh.gaba/Documents/Codex/Yathansh-Ops-Vault/Projects/example-repo.md`.
- Read this `AGENTS.md`.

### During Dev Work

- Use `Daily/` or `Logs/Dev Work Ledger.md` for substantial work notes.
- Use `Inbox/` only for temporary captures that still need triage.
- Keep links between commits, files, Lovable project IDs, Supabase evidence, and project notes.
- Keep source proof and live proof separate.

### After Dev Work

- Update `/Users/yathansh.gaba/Documents/Codex/Yathansh-Ops-Vault/Projects/example-repo.md` with durable facts, changed behavior, verified proof, and remaining blockers.
- Update `/Users/yathansh.gaba/Documents/Codex/Yathansh-Ops-Vault/Lovable Context/Projects/example-repo.md` when Lovable should safely benefit from the context.
- Update repo `AGENTS.md` when a new rule should travel with the GitHub repo.
- Update runbooks or decisions when the learning applies across projects.

### Safety

- Do not store secrets, raw private chat dumps, OAuth tokens, API keys, service-role keys, DB URLs, cookies, OTPs, or `.env` contents in repo docs, Obsidian, or Lovable Context.
- Do not infer live deployment from GitHub `main`, Lovable `Ready`, or local tests.

## Current Source Context

- GitHub repo: `yathanshgaba/example-repo`
- Local checkout: `/Users/yathansh.gaba/codex-repos/yathanshgaba/example-repo`
- Current local branch: `master`
- Current local HEAD: `9cde11d18a72`
- Current local HEAD date: `2026-06-30T00:09:13+05:30`
- Worktree state when this documentation block was generated: `clean`
- Repo-context dossier: `/Users/yathansh.gaba/.codex/repo-context/yathanshgaba/repos/example-repo/DOSSIER.md`
- Repo-context `AGENTS.md` proposal: `/Users/yathansh.gaba/.codex/repo-context/yathanshgaba/repos/example-repo/AGENTS.proposed.md`
- Repo-context generated at: `2026-06-18T11:56:58.684457+00:00`
- Dossier may be stale versus local HEAD: `True`

## Lovable Context

- No Lovable Desktop project ID is confidently mapped yet.
<!-- codex-project-brain:end -->

Repository: `yathanshgaba/example-repo`

## Project Purpose

example-repo

## Detected Stack

- No stack detected.

## How To Run Locally

- `No local dev script detected. Inspect repo before running.`

## How To Test

- `No test/lint/typecheck script detected. Add or identify targeted tests before behavior changes.`

## How To Build

- `No build script detected. Inspect package/config files before claiming build success.`

## Deploy Commands

Do not deploy without explicit user approval.

- `No deploy-like script detected.`

## What Not To Break

- Do not commit secrets, OAuth tokens, API keys, credentials, or database connection strings.
- Do not weaken auth, RLS, protected routes, secure headers, audit logs, role permissions, provider honesty, or production data integrity.
- Do not replace real DB-driven pages with mock data.
- Do not run destructive database writes or deployments without explicit approval.

## Security Guardrails

- Inspect auth, permissions, data access, and provider boundaries before editing related code.
- Preserve least privilege and tenant/user isolation.
- Keep external calls auditable and server/edge mediated where the repo already uses that pattern.

## Data Guardrails

- Preserve real data flows, auditability, and status transition integrity.
- Do not alter migrations, RLS policies, storage policies, or production records without explicit approval.

## Provider And Integration Guardrails

- Do not hardcode provider success or fake external API results.
- Do not print provider secrets or tokens in logs, docs, commits, or chat.
- Keep retry, status, and failure handling honest and observable.

## Codex Workflow

- Start with `$repo-context-router` and load the repo dossier before planning or coding.
- Use `$lovable-grill-me` for unclear product requirements.
- Use `$lovable-to-prd` for specs and `$lovable-to-vertical-issues` for implementation slicing.
- Use `$lovable-tdd-implementation` for code changes.
- Use `$lovable-architecture-audit` for refactor or architecture review.
- Do not use `$recruit-ai-guardrails` unless this repo is Recruit AI Copilot or dossier evidence clearly matches that product family.

## Required Final Report After Changes

- Files changed
- Behavior changed
- Tests run and exact results
- Build/lint/typecheck results if run
- Risks and rollback notes
- Manual QA steps
