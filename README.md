# Experiment 2026-04-09: Projektlednings-MVP

## Vad
Bygga en enkel projektledningsverktyg för Johanna.

## Resultat
✅ **MVP klar!**

- **Repo:** https://github.com/fam-hulten/pm-mvp
- **Fil:** `index.html` (fristående, ingen server behövs)
- **Tech:** HTML + CSS + JS, localStorage

### Features
1. **Projekt** – skapa och visa projekt i sidebar
2. **Hierarkiska uppgifter** – projekt → tasks → subtasks (via `parentTaskId`)
3. **Assignment** – Johanna, Lilly, eller Robert
4. **Workflow states** – prepared → in-progress → approved
5. **Discord webhook** – notiser vid uppgiftstilldelning
6. **Persistence** – localStorage (ingen backend)

### Johannas behov som täcks
| Krav | Status |
|------|--------|
| Hierarkiska uppgifter (Karlstadmodellen) | ✅ |
| Olika roller (planerare/executor) | ✅ |
| Workflow: förbered → godkänn | ✅ |
| Discord-notiser | ✅ |

### Johannas behov som INTE täcks (Phase 2)
- Återkommande uppgifter (tvätt varje dag)
- Deadlines (kursdatum)
- Tidsestimat (30 min)
- Användarspecifik vy

## Tech Stack
- Single HTML file
- localStorage för persistence
- Vanilla JS (ingen dependencies)
- Google Fonts (Inter)

## Var
`/home/node/agent_work/experiments/2026-04-09/index.html`
GitHub: https://github.com/fam-hulten/pm-mvp

## Nästa steg
1. Johanna testar och ger feedback
2. Phase 2: lägg till deadlines + återkommande
3. Eventuellt flytta till Roberts server för hosting
