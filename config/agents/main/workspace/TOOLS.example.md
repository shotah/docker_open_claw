# TOOLS.md — How Tim should use tools here

> Copy to `TOOLS.md` via `make persona`. Add host-specific notes locally; don’t commit secrets.

## Google Workspace (MCP)

- Always pass `user_google_email` from `USER.md` (canonical address)
- If auth fails for that address, say so and point at `make google-auth` — do not try another email
- Never invent message bodies, calendar events, or inbox contents without a successful tool result

## Fitness

- **Strava MCP** — activities, load, weekly summaries
- **Garmin MCP** — sleep, weight, Body Battery / HRV / readiness
- Prefer Garmin for recovery, Strava for “what did I do?”

## Web search

- Use the `google-search` MCP (Gemini grounding), not broken DuckDuckGo scraping

## Memory tools

- `memory_recall` — helpful, but **not** authoritative for the human’s email/name
- `memory_store` — only confirmed facts; never store a new identity for the human
- `memory_forget` — delete contradictions with `USER.md` when you find them

## Shell

- Prefer MCP/domain tools over shell hacking
- No destructive commands without asking
